---
description: >-
  Lenguaje de programación visual y complemento (plugin) integrado en el
  software de modelado 3D Rhinoceros (Rhino)
icon: locust
cover: ../.gitbook/assets/@fabxiety follow me! Sígueme!.gif
coverY: -35.58620689655173
coverHeight: 658
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

# Grasshopper

### <mark style="color:$info;">**¿Qué es Grasshopper?**</mark>

<figure><img src="../.gitbook/assets/grasshopper.png" alt=""><figcaption></figcaption></figure>

Grasshopper es una herramienta de programación visual que funciona dentro de Rhino y permite crear modelos 3D mediante componentes que se conectan entre sí. A través de estos componentes podemos modificar formas y dimensiones cambiando distintos parámetros, sin necesidad de modelar cada elemento manualmente.

### <mark style="color:$info;">**¿Cómo usamos grasshopper para crear una vasija?**</mark>

{% stepper %}
{% step %}
#### **Búsqueda de un tutorial de referencia**

Para comenzar con el ejercicio, primero busqué un video que me sirviera de guía para entender cómo crear una vasija desde cero en Grasshopper. A partir de este tutorial fui siguiendo los pasos, colocando los componentes y conectando los parámetros necesarios para generar la forma.

{% embed url="https://youtu.be/n_Odk0kKH7k?si=H_8yW5F1FvjEcIqE" %}
{% endstep %}

{% step %}
#### **Primer intento de modelado**

<figure><img src="../.gitbook/assets/video grasshopper.gif" alt=""><figcaption></figcaption></figure>

Siguiendo el tutorial, logré desarrollar una primera vasija utilizando varias circunferencias que se iban uniendo y modificando para formar el volumen. Sin embargo, al finalizar empecé a tener algunos problemas con las uniones de las superficies, ya que el modelo tenía muchas curvas y capas, lo que hizo que corregirlo fuera bastante complicado.

<figure><img src="../.gitbook/assets/Video Project 6 (2).gif" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/Captura de pantalla 2026-11-05 002501.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**Recomendación:** Algo que me pasó durante el primer modelado fue que Rhino se cerró inesperadamente mientras estaba trabajando en Grasshopper y no había guardado el archivo, por lo que perdí todo el avance y tuve que volver a realizar el modelo desde cero. Así que les recomiendo ir guardando sus archivos cada cierto tiempo para evitar perder todo el trabajo, especialmente cuando están trabajando con modelos que llevan varios componentes y conexiones.&#x20;
{% endhint %}
{% endstep %}

{% step %}
#### **Segundo intento: modelo más sencillo**

{% embed url="https://youtu.be/dw4084NtW3o?si=ijhlEclFpt47uvv8" %}

Como no estaba consiguiendo resolver esos problemas, decidí volver a empezar, pero esta vez buscando otro tutorial que me permitiera realizar una vasija más sencilla. A diferencia del primer modelo, que se generaba a partir de varias circunferencias, este segundo diseño partía de una curva de perfil que posteriormente se utilizaba para generar el volumen de la vasija.

<figure><img src="../.gitbook/assets/vasija sencilla 1.gif" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
#### **Modificación de parámetros**

Una vez que entendí mejor cómo funcionaba el procedimiento y cómo se conectaban los componentes, empecé a modificar los valores de los puntos de control de la curva, los radios y otros parámetros para ir cambiando la forma de la vasija hasta conseguir el resultado que quería.

<figure><img src="../.gitbook/assets/vasija sencilla 2.gif" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
#### **Corrección del modelo**

En el primer resultado que preparé para imprimir, había configurado un radio demasiado grande en la parte inferior de la vasija. Esto generó una pequeña concavidad o hueco en la base que, aunque no era tan evidente en el modelo, terminó ocasionando problemas durante la impresión, ya que esa zona no tenía suficiente material para sostener las capas superiores.

<figure><img src="../.gitbook/assets/WhatsApp Image 2026-11-09 at 7.33.12 AM.jpeg" alt=""><figcaption></figcaption></figure>

Por eso, volví a abrir el archivo en Rhino y Grasshopper para corregir la curva y ajustar la forma de la base. Fui probando diferentes valores hasta conseguir una forma que me gustara y que también pudiera imprimirse correctamente.
{% endstep %}

{% step %}
#### Exportación e impresión

Una vez finalizadas las modificaciones, guardé el modelo y lo exporté en formato STL para importarlo en Bambu Studio. Allí configuré los parámetros finales de impresión y preparé el archivo para enviarlo a la Bambu Lab A1.

{% hint style="info" %}
**Algo que me quedó de este ejercicio:** al principio me enfoqué bastante en conseguir la forma que quería, pero después entendí que también era importante considerar cómo se iba a imprimir el modelo. No alcanza con que la vasija se vea bien en Rhino; también hay que revisar su geometría, las uniones y la base para evitar problemas durante la fabricación.
{% endhint %}
{% endstep %}
{% endstepper %}

### <mark style="color:$primary;">**Resultado Final :)**</mark>

<div><figure><img src="../.gitbook/assets/WhatsApp Image 2026-11-09 at 5.50.12 AM (2).jpeg" alt=""><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/WhatsApp Image 2026-11-09 at 5.50.12 AM (1) (1).jpeg" alt=""><figcaption></figcaption></figure></div>

<figure><img src="../.gitbook/assets/WhatsApp Image 2026-11-09 at 5.50.14 AM (2).jpeg" alt=""><figcaption></figcaption></figure>



{% tabs %}
{% tab title="Archivos utilizados para este trabajo" icon="folder-open" %}


{% file src="../.gitbook/assets/vasija final.3mf" %}

{% file src="../.gitbook/assets/vasija.gh" %}

{% file src="../.gitbook/assets/vasija finalisima.3dm" %}
{% endtab %}
{% endtabs %}
