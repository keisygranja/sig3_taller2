# sig3_taller2
1. Se selecciono todas las capas correspondientes al equipamiento colectivo del POT 2014 a traves de la IDESC mediante el servicio WFS, exceptuando las capas de bienestar social y educación que se descargo de forma local. Caso similar ocurrio con la cartografia base; se selecciono las capas comunas y barrios como WFS de la IDESC, como WMS selecciono la capa de ríos, manzana y vías que se selecciono de la CVC.
2. Las capas locales además de 3 creadas se subieron a PostgreSQL.
3. Las capas contenidas en la base de datos se subieron a la nube
4. Las capas que estan en la nube se subieron a Geoserver el cual estuvo contenido en una maquina virtual
5. Se cargo el servicio WFS del geoserver que esta en la maquina virtual de forma local
6. Mediante el complemento qgis2web se creo un geovisor y de forma manual se agrego elementos como la escala, la flecha del norte y un minimapa.
   
Como observación, es posible que las capas no carguen debido a la configuración de GitHu
