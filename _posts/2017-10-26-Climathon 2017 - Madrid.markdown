---
layout: default
modal-id: 2
date: 2017-10-27
img: climate.png
alt: image-alt
project-date: October 2017
client: EIT Climate-KIC
client-url: "https://climathon.climate-kic.org/madrid/"
category: Data Analytics
url-dir: "https://github.com/Climathon-Madrid-2017"
subtitle: "Comprendiendo mejor la contaminación lumínica y cómo afecta a nuestro entorno."
---

### ¿Qué es Climathon?

Climathon es un encuentro global de 24h que tiene lugar en más de 100 ciudades de forma simultánea y que busca poner en contacto a emprendedores, universitarios y profesionales para explorar estrategias y crear soluciones innovadoras a los problemas a los que se enfrentan las ciudades. 2017 es el tercer año que se celebra, con un crecimiento exponencial de participantes.

La temática elegida para Climathon Madrid es la contaminación lumínica, y el objetivo principal es mejorar la información disponible sobre este tema y concienciar el impacto que tiene sobre la sociedad y el entorno. Se crean diversos grups de trabajo con distintos enfoques. El evento es organizado por el departamento de Ontología de la Universidad Politécnica, por lo que se pone especial interés en la integración de datos a través de semántica y linked data.

Además sirve como punto de encuentro de expertos con distintas charlas organizadas a lo largo del Climathon.<br>
<br>

### IoT - Smart cities - Linked data

Participo en el grupo de IoT donde nuestro objetivo es estudiar los diferentes instrumentos utilizados para medir la contaminación lumínica, analizar los datos obtenidos, proponer visualizaciones, y proponer una estrategia para integrar estos datos sobre OpenStreetMap usando semántica de forma que los datos sean abiertos y disponibles para cualquier persona.

<img src="/img/posts/tess.jpg">

Realizamos diversos experimentos durante la noche:
1. Anotación de diversos elementos que tienen impacto sobre contaminación lumínica, sobre todo luminaria del campus, para poder trabajar con el equipo de vocabulario y dotarlos de una entidad. [OpenStreetMap](https://www.openstreetmap.org/#map=17/40.40506/-3.83654&layers=N)

2. Medición con distintos fotómetros situados en la cubierta del edificio para estudiar la contaminación lumínica a lo largo de toda la noche y ver su evolución temporal. [stars4all.eu/tess](http://www.stars4all.eu/index.php/tess/)

3. Elaboración de una herramienta con Google Vision API y Python para caracterizar elementos, con su geolocalización y poder importar más rápidamente a OpenStreetMap. [Repo en github](https://github.com/Climathon-Madrid-2017/vision_api)

4. Con todos los participantes al evento, visitamos una instalación de la Universidad con luminaria inteligente para recopilar datos, de forma que cada participante con su Smartphone se convierte en un sensor. Esta instalación de la Universidad regula la intensidad de la luminaria de forma automática, ahorrando más de un 80% mediante el uso de LEDs y de una estrategia de comunicación entre los distintos elementos.

5. Medida de contaminación usando [Loss of the night](http://lossofthenight.blogspot.com.es/), una app que permite estimar la cantidad de estrellas visibles mediante una encuesta al usuario con 8 estrellas de control.

6. Elaboración junto al equipo de [NixNox](http://nixnox.stars4all.eu/), investigadores de la Complutense Lucía y Carlos, de un mapa del cielo del campus. Esta herramienta permite visualizar de una forma muy gráfica el impacto que tienen las ciudades sobre el cielo. Se usan fotómetros SQM.

![](img/posts/UPM.png?raw=true)

### Wrap up
Una experiencia única, comparitiendo estas 24h con personas de diversos campos pero con la misma inquietud por promover un desarrollo sostenible.
