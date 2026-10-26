---
icon: pen-paintbrush
cover: ../.gitbook/assets/descarga (2).gif
coverY: 0
coverHeight: 422
layout:
  width: default
  cover:
    visible: true
    size: full
    mask: none
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

# Introducción • Plotter de corte

## <mark style="color:$info;">**¿Qué es un plotter de corte?**</mark>

El plotter de corte es una máquina de fabricación digital que permite cortar diferentes materiales siguiendo diseños creados previamente en la computadora. Funciona mediante una cuchilla que se desplaza siguiendo las trayectorias de un archivo vectorial, lo que permite obtener formas y cortes precisos.

Se utiliza principalmente para trabajar con materiales como vinilo adhesivo, vinilo textil, papel y cartulina, entre otros. También puede utilizarse para realizar dibujos mediante la incorporación de un bolígrafo o marcador en lugar de la cuchilla.

En el caso del laboratorio tenemos la máquina de corte **GCC Puma IV** o coloquialmente conocida como **Vivi la rara,** que es un plotter de corte versátil y preciso, diseñado para aplicaciones de corte de vinilo y otros materiales en entornos profesionales y de diseño.

<details>

<summary><mark style="color:$info;"><strong>TODO SOBRE EL PLOTTER DE CORTE</strong></mark> (desplega para saber más)</summary>

#### ¿Cómo funciona un plotter de corte?

El funcionamiento del plotter comienza con la preparación de un diseño digital. Este diseño se realiza en un programa de edición vectorial y luego se envía a la máquina mediante un software compatible. El plotter interpreta las líneas del archivo y mueve el cabezal para realizar el corte o el trazado correspondiente.

El resultado depende tanto de la preparación del archivo como de la configuración de la máquina y del material utilizado.

#### ¿Cuál es la diferencia entre cortar y dibujar con un plotter?

* **Corte:** la máquina utiliza una cuchilla para seguir las líneas del diseño y cortar el material, ya sea completamente o solo en su capa superficial.
* **Dibujo:** se reemplaza la cuchilla por un portabolígrafo, que permite reproducir líneas, ilustraciones y patrones sobre papel u otras superficies compatibles.

Aunque ambos procesos utilizan trayectorias vectoriales, cada uno requiere una herramienta y una configuración específica.

#### ¿Qué materiales se pueden utilizar?

Los materiales que pueden trabajarse dependen del modelo del plotter, del grosor del material y de la herramienta utilizada. Algunos de los más comunes son:

* Vinilo adhesivo para stickers y señalética.
* Vinilo textil para personalizar prendas.
* Papel y cartulina para tarjetas, invitaciones y maquetas.
* Papeles de diferentes gramajes para realizar dibujos.
* Materiales especiales compatibles con la máquina, según sus especificaciones.

#### ¿Qué parámetros se deben configurar?

Antes de realizar un trabajo, es importante revisar algunos parámetros para obtener un resultado adecuado:

* **Fuerza:** determina la presión que ejerce la cuchilla sobre el material.
* **Velocidad:** controla la rapidez con la que se desplaza el cabezal.
* **Tipo de cuchilla:** se selecciona según el material y el tipo de corte.
* **Área de trabajo:** permite comprobar que el diseño entre dentro de las dimensiones disponibles.
* **Offset de la cuchilla:** compensa la posición de la punta para mejorar la precisión de esquinas y curvas, cuando el equipo permite configurarlo.

Estos valores no son iguales para todos los materiales, por lo que es recomendable realizar una prueba de corte antes de ejecutar el diseño definitivo.

#### ¿Qué aplicaciones tiene el plotter en el diseño?

El plotter permite materializar diseños digitales y se utiliza en diferentes áreas, como el diseño gráfico, la señalética, la personalización de productos, la elaboración de stickers, la creación de plantillas y la fabricación de prototipos.

En el caso del dibujo con bolígrafo, también permite experimentar con ilustraciones, patrones geométricos, mapas y composiciones generativas que pueden crearse mediante programas de diseño paramétrico.

</details>

### <mark style="color:$info;">¿Qué necesitamos para empezar a cortar o dibujar?</mark>

Para poder realizar nuestros cortes o dibujos lo que necesitamos primordiamente son los archivos en el formato que pueda leer la máquina, para eso lo que vamos a hacer es primeramente descargar los programas que nos van a estar ayudando a exportar todos nuestros archivos a los formatos correspondientes:

{% tabs %}
{% tab title="Para vectorizar" %}
> **Inkscape:** [https://inkscape.app/es/](https://inkscape.app/es/) se pueden exportar archivos en .svg, .dxf y **.hpgl (MUY importante porque es el formato universal para máquinas de plotter)**

> **Illustrator:** [https://www.adobe.com/es/products/illustrator.html](https://www.adobe.com/es/products/illustrator.html) se puede exportar en .svg y .dxf

> **Grasshopper:** es un entorno de programación visual integrado en el software de modelado 3D Rhinoceros (Rhino) que ofrece la posibilidad de realizar vectorización de imágenes a través de circunferencias.
{% endtab %}

{% tab title="Para cambiar formato y ajustar" %}
**RdWorks:** [https://www.rdacs.com/en/download?type=software](https://www.rdacs.com/en/download?type=software) software estándar de diseño y control para máquinas de corte y grabado láser CO₂.
{% endtab %}

{% tab title="Para Vivi" %}
**CGG File Uploader:** [https://www.gccworld.com/es/download.php?act=view\&id=2](https://www.gccworld.com/es/download.php?act=view\&id=2) sirve para transferir nuestro archivo a Vivi para realizar el corte o dibujo&#x20;
{% endtab %}
{% endtabs %}

Lo primero que hacemos es instalar los programas que vamos a necesitar y realizar una exploración de los mismos para poder familiarizarnos un poquito con cada uno c:

### <mark style="color:$info;">**¿Cómo trabajar con Vivi?**</mark> <mark style="color:$info;"></mark><mark style="color:$info;">mini tutorial escrito</mark>

<figure><img src="../.gitbook/assets/recursos gitbook (9).png" alt=""><figcaption><p>Vivi the best one ⋆. 𐙚 ˚</p></figcaption></figure>

Lo primero que debemos de realizar SIEMPRE antes de prender a Vivi es colocar ya dentro de la máquina nuestra base de corte, en nuestro caso utilizamos una base de corte de PVC  que sirve para poder colocar encima de eso el material a cortar o dibujar, esto lo hacemos para que la máquina pueda al encender reconocer ya su espacio de trabajo.

#### **Pasos a seguir para poder preparar a Vivi para nuestro corte o dibujo:**

{% stepper %}
{% step %}
#### Colocar nuestra base de corte

<figure><img src="../.gitbook/assets/WhatsApp Image 2026-10-21 at 1.06.04 PM (1) (1).jpeg" alt=""><figcaption></figcaption></figure>

Lo primero que debemos de hacer es levantar la palanca que se encuentra en la parte de atrás de la máquina del lado derecho, luego introducimos nuestra base de corte y una vez acomodado lo que hacemos es volver a bajar la palanca para que la base quede debidamente ajustada.
{% endstep %}

{% step %}
#### Prender la máquina

Lo siguiente que hay que hacer es prender la máquina, su botón se encuentra en la parte lateral del lado izquierdo.

<figure><img src="../.gitbook/assets/WhatsApp Image 2026-10-21 at 1.05.55 PM.jpeg" alt=""><figcaption></figcaption></figure>

Una vez prendida lo que tenemos que hacer para que Vivi reconozca el área de trabajo de nuestra base es presionar el botón izquierdo que se encuentra en la parte superior, ya hecho eso la máquina va a hacer un recorrido de nuestra base tanto en el eje X como en el eje Y.

<figure><img src="../.gitbook/assets/WhatsApp Image 2026-10-21 at 1.06.04 PM (3) (1).jpeg" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
### Punto de origen

Con nuestra base reconocida lo que sigue es encontrar el punto de origen en nuestro vinilo para el corte o papel para el dibujo, para esto vamos a ir presionando las teclas con flechas hasta encontrar el punto o lugar que deseemos, ya con eso listo el siguiente paso es darle doble enter al botón central.

<figure><img src="../.gitbook/assets/WhatsApp Image 2026-10-21 at 1.05.55 PM (7).jpeg" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
### Transferir archivo a Vivi

Ya para finalizar lo único que nos quedaría es conectar nuestra computadora o notebook a través del cable USB y ya podemos cortar o dibujar con Vivi trasnfiriendole nuestros archivos a través del GCC file uploader y le damos a start para comenzar y listo! c:

<figure><img src="../.gitbook/assets/Captura de pantalla 2026-10-19 093101 (1).png" alt=""><figcaption><p>Buscamos el archivo que necesitamos en <strong>browse</strong> y una vez seleccionado le damos a <strong>start</strong></p></figcaption></figure>
{% endstep %}
{% endstepper %}

***
