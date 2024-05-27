
Terminal FAP-TEK

Accede aquí a la exposición

El Festival de Arte, Pensamiento y Tecnología FAP-TEK acoge una exposición en forma de entorno virtual inmersivo, diseñado por la artista digital Miyö Van Stenis, junto con la curadora Paula Cárcamo en colaboración con Cecilia Almirón. Este espacio 360º cobra forma a su vez con la colaboración de lxs cuatro artistas cuyas obras conforman la exposición:  Julia C. Parodi, Juan Covelli, Liliana Farber y Perla Zúñiga. El sonido ha sido diseñado por Daniel Sanz, y los elementos de la identidad visual del festival integrados en la exposición, por Daira Cañete.

INSTRUCCIONES Y RECOMENDACIONES:

 Se recomienda usar Chrome o Firefox como navegadores. La exposición es una experiencia inmersiva para ser visualizada en un ordenador, dispositivos móviles no son recomendados.

    Usa el ratón o trackpad de tu ordenador para controlar el rango de visión de la cámara. Usa las teclas “W”, “S”, “A”, “D” (teclados QWERTY) o las teclas direccionales para desplazarse en el espacio.
    La letra “T” cierra y abre el texto de la exposición. La tecla “Escape” desbloquea el cursor del ratón y te permitirá hacer click al botón “pantalla completa” en la parte inferior derecha de tu pantalla.
    Los carros de aeropuerto dentro de la terminal de la exposición son portales para entrar a los universos de cada artista. Camina hacia ellos para activar la transición, un sonido te avisará que has entrado en dicha zona de transición al igual que aparecerá el nombre del artista a quién pertenece el portal. Dirígete al carro de aeropuerto y espera unos segundos para la transición.
    Para volver a la terminal de la exposición usa el portal “Salida” ubicado en cada uno de los universos. Usa el mismo protocolo para activar la zona de transición. 



# FAP-Tek
WebGL/VR/AR Exhibition


World #1: Entrada 
World #2: Espacio Artista 

Projecto Template para la Exposicion Online de FAP-TEK (Uruguay).
El script corre bajo el Framework de A-Frame. Documentacion: https://aframe.io/docs/1.1.0/introduction/ 
Componentes a privilegiar que los artistas pueden utilizar en sus universos: environment, particle systems, physics, multiuser, teleportation, super hands, y augmented reality. ver documentacion. 

Dicho Framework ayudara no solo en la composicion de los elementos a utilizar pero tambien a que cada espacio sea VR-Ready. A-frame utiliza la plataforma de live-coding "https://glitch.com" ideal para visualizar en tiempo real todo cambio en el codigo al igual que cualquier trabajo en colaboracion, por lo que se recomienda a los artistas participantes a explorar y usar en el desarrollo de este proyecto dicha plataforma.

////Entrada///

Cada artista debe crear un icono 3D o 2D para su portal > producto final: imagen png o archivo .collada/.obj
Diseño e interaccion de la entrada bajo la supervision de las Curadoras y MVS.
Environment > Teleportation > multiuser

///Espacio Artistas///

Individualmente cada espacio mostrará la obra del artista, dicho espacio es una carta blanca por lo tanto el artista tiene la oportunidad de crear y editar su universo y como la obra ha de ser presentada. Interacciones y/o FX seran discutidos con el desarrollador para un optimo funcionamiento. El artista tiene la libertad de crear su espacio por si mismo con la ayuda de A-frame o en conjunto con el desarrollador.

Como base cada proyecto es un universo 360° con 3 o 4 botones interactivos o lightbox (ver: https://aframe.io/examples/showcase/responsiveui/) por lo que se requiere de cada artista una images de fondo y al menos una images png para activar el lightbox y mostrar la obra. Dicho universo sera un reflejo de la obra seleccionada y el lenguaje plastico del artista.

Elementos de base para cada universo:

* img-Background: 4096x2048 a 72dpi (4k Equitectangular imagen)
* icono de la obra: imagen png o archivo .collada/.obj (este sera el boton para abrir la obra en caso de que no sea integrada al espacio virtual puede ser la misma imagen usada en la Entrada)
* Sound-background (opcional): archivo audio editado para loop maximo 1 minuto - min 30 segundos. Formato mp3 stereo 44.000

Ejemplos de universos 360° e interacciones:
* https://haydenlee.io/networked-aframe/basic.html
* https://aframe.io/examples/showcase/360-video/
* http://www.deprogrammed.org/

enjoy!



