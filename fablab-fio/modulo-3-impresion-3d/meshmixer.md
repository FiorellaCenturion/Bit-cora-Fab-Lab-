---
description: >-
  Meshmixer es un programa de edición y modificación de modelos 3D que permite
  combinar, transformar y preparar piezas para su posterior impresión.
icon: circle-nodes
cover: ../.gitbook/assets/Gundam Tech_.gif
coverY: 0
coverHeight: 700
layout:
  width: default
  cover:
    visible: true
    size: full
    mask: radial
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
  tags:
    visible: true
  actions:
    visible: true
  anchors:
    visible: true
---

# Meshmixer

### <mark style="color:$primary;">**¿Qué es, para qué sirve y cómo se utiliza?**</mark>

<figure><img src="../.gitbook/assets/recursos gitbook (17).png" alt=""><figcaption></figcaption></figure>

Es una herramienta que permite trabajar sobre modelos tridimensionales ya existentes. Se utiliza principalmente para unir diferentes piezas, modificar sus dimensiones, agregar o quitar elementos, corregir errores en las mallas y preparar modelos para imprimirlos en 3D.

Su funcionamiento se basa en importar los modelos al programa y utilizar sus herramientas de edición para realizar las modificaciones necesarias. Una vez terminado el trabajo, se exporta el resultado en formato STL para llevarlo a un programa de laminado, como Bambu Studio.

### <mark style="color:$primary;">Pasos para utilizar Meshmixer</mark>

{% stepper %}
{% step %}
#### **Instalación del programa**

{% embed url="https://meshmixer.com/download.html" %}

Primero ingresamos a la página oficial de Autodesk Meshmixer, descargamos el instalador y seguimos los pasos para instalar el programa en nuestra computadora.
{% endstep %}

{% step %}
#### **Exploración de la interfaz**

<figure><img src="../.gitbook/assets/Captura de pantalla 2026-11-02 120132.png" alt=""><figcaption></figcaption></figure>

Una vez abierto el programa, exploramos las herramientas y opciones disponibles para familiarizarnos con su funcionamiento y conocer las posibilidades de edición.
{% endstep %}

{% step %}
#### Búsqueda de modelos 3D

Luego buscamos dos modelos 3D de nuestra preferencia para realizar una composición y unirlos dentro de Meshmixer. En mi caso, elegí una figura de Uzumaki a la que quería agregarle una base.

<figure><img src="../.gitbook/assets/Captura de pantalla 2026-11-02 123918.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
#### **Preparación de los modelos**

Para la figura busqué un modelo que se acercara a lo que tenía pensado y, para la base, descargué una que ya tenía un texto predeterminado. Este texto lo modifiqué previamente en Bambu Studio y exporté la base en formato STL para poder trabajar con ella en Meshmixer.

<figure><img src="../.gitbook/assets/Captura de pantalla 2026-11-04 094145.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
#### Edición y unión de las piezas

<figure><img src="../.gitbook/assets/Captura de pantalla 2026-11-04 095354.png" alt=""><figcaption></figcaption></figure>

Una vez importados ambos modelos, comencé a realizar las modificaciones y uniones necesarias. También fui ajustando sus dimensiones y posiciones para conseguir que la figura encajara correctamente sobre la base y que el resultado quedara como lo había imaginado.

<figure><img src="../.gitbook/assets/Captura de pantalla 2026-11-04 100922.png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
#### **Exportación e impresión**

Cuando terminé de unir y ajustar las piezas, exporté el resultado final en formato STL y lo importé nuevamente en Bambu Studio para configurar los parámetros de impresión y proceder a realizar la impresión.

<figure><img src="../.gitbook/assets/Captura de pantalla 2026-11-04 123358.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**Ajuste de los parámetros de impresión**

En esta parte tuve un pequeño detalle que no consideré al principio: la densidad del relleno (infill). Había configurado un 15 %, cuando en realidad podía haber utilizado un 5 %, ya que se trataba de una pieza principalmente decorativa y no necesitaba tanta resistencia estructural. Esto me permitió darme cuenta de la importancia de considerar el uso final del objeto antes de definir los parámetros de impresión.
{% endhint %}
{% endstep %}
{% endstepper %}

### <mark style="color:$primary;">**Resultado final :)**</mark>

<div><figure><img src="../.gitbook/assets/WhatsApp Image 2026-11-09 at 5.31.27 AM.jpeg" alt=""><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/WhatsApp Image 2026-11-09 at 5.31.44 AM.jpeg" alt=""><figcaption></figcaption></figure></div>

<div><figure><img src="../.gitbook/assets/WhatsApp Image 2026-11-09 at 5.50.07 AM.jpeg" alt=""><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/WhatsApp Image 2026-11-09 at 5.50.07 AM (2).jpeg" alt=""><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/WhatsApp Image 2026-11-09 at 5.50.07 AM (1).jpeg" alt=""><figcaption></figcaption></figure></div>

<div><figure><img src="../.gitbook/assets/WhatsApp Image 2026-11-09 at 5.50.01 AM.jpeg" alt=""><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/WhatsApp Image 2026-11-09 at 5.50.12 AM (1).jpeg" alt=""><figcaption></figcaption></figure></div>

{% tabs %}
{% tab title="Archivos utilizados para este trabajo" %}
{% file src="../.gitbook/assets/Junji_Ito_Uzumaki_Bust.3mf" %}

{% file src="../.gitbook/assets/BASE UZUMAKI (1).stl" %}
{% endtab %}
{% endtabs %}
