Tutorial para instalar Zotero, ZotFile y Better BibTex para Zotero.

## 1) Primeros pasos
 
1. En [la página de Zotero](http://www.zotero.org) hacer click en "Download".
2. Descargar para el sistema operativo que usen e instalar. ![](https://i.imgur.com/fUxf4AE.png)
3. Luego instalar el Conector. Es lo que permite cargar cosas directamente desde el navegador que prefieran. (Más sobre esto, luego) ![](https://i.imgur.com/tXdNVoR.png)
4. Tenemos Zotero instalado en la compu, pero la base de datos todavía está vacía: ![](https://i.imgur.com/pCo4K1A.png)
5. Podemos sumarle cosas arrastrando y soltando archivos de cualquier carpeta a la pantalla principal: ![](https://i.imgur.com/bSJDgfL.png)
6. O usar el conector que se instaló en 3. y agregar desde la página de la revista que nos interese:![](https://i.imgur.com/0ny7xCO.png)
    + Debería salir un cartel como el siguiente: ![](https://i.imgur.com/dgERWmh.png)   
7. Y aparece el artículo en nuestra biblioteca, con los metadatos en el panel de la derecha. ![](https://i.imgur.com/MA9wiNQ.png)

## Instalar complementos para los procesadores de texto.
Una de las últimas actualizaciones de Zotero hizo mucho más fácil instalar los complementos para los procesadores de texto. 

1. Abrimos Zotero y vamos a "Edición" y buscamos la opción "Preferencias" en el menú. ![](https://imgur.com/3ieW6sV)
2. Buscamos la sección "Citar" y después la pestaña "Procesadores de texto" ![](https://imgur.com/aN0lQjb)
3. Allí hacemos click en el procesador que usemos (puede ser Word o LibreOffice, pero es importante que **no** esté corriendo en ese momento) ![](https://imgur.com/FecBCCK)
4. ¡Listo! Debería aparecer un cartel indicando que ya está instalado. En Word debería aparecernos este menú arriba ![](https://imgur.com/quY5GrF)

## 2) ZotFile

ZotFile es el complemento que nxs permite manejar los archivos que la base de datos puede tener de una mejor manera. Entre otras:
+ Alojarlos en una nube, para tenerlos a disposición en múltiples lugares.
+ Renombrarlos para hacerlos más fáciles de encontrar sin el programa.

### Instalación

1. Bajar el _plugin_ desde [su sitio web](https://www.zotfile.com). El archivo tendrá extensión .xpi (ejemplo: zotfile-5.0.10-fx.xpi)
2. En Zotero, ir al menú "Herramientas", hacer click en "complementos". ![](https://i.imgur.com/tlwuiV8.png)
3. Se abrirá el gestor de complementos de Zotero. ![](https://i.imgur.com/QjjNf8y.png)
4. Hacemos click en el ícono del engranaje (o la ruedita) y después en "instalar complemento desde archivo": ![](https://i.imgur.com/h8YgO7E.png)
5. Seleccionamos el .xpi que bajamos en 1. y hacemos click en "instalar ahora": ![](https://i.imgur.com/oaFCUGk.png) ![](https://i.imgur.com/FTMGtQ7.png)
6. Necesitamos reiniciar Zotero para terminar la instalación. ![](https://i.imgur.com/u9DkAvq.png)
7. ¡Listo! Tenemos ZotFile en nuestro Zotero.

### Y... ¿como lo uso?
Recordemos que queríamos ZotFile para poder tener nuestra biblioteca disponible en algún servicio en la nube (o simplemente, más accesibles via exploradores de archivos que la intrincada estructura de carpetas que maneja Zotero)
Para ello, es necesario hacer lo siguiente:

> `Acá vamos a empezar a tocar cosas del funcionamiento de Zotero, así que debemos proceder con cuidado.`
 
1. Una vez hemos terminado la instalación, siguiendo las instrucciones de la sección anterior, en Zotero hacemos click en "Edición" y después en  "Preferencias". ![](https://i.imgur.com/27ZJLLv.png)
2. En las preferencias de Zotero, hacemos click en "Avanzadas" y luego en "Archivos y carpetas" ![](https://i.imgur.com/WDtPFP0.png)
3. En la sección "Directorio base de adjuntos enlazados" vamos a configurar cuál es la carpeta en la que queremos guardar todos los archivos de nuestra biblioteca.

    + En este caso, será la carpeta "Zotfile" que alojaremos en el servicio de almacenamiento OneDrive. ![](https://i.imgur.com/qvcG2j3.png)
4. Confirmamos que queremos que esa sea la carpeta base. ![](https://i.imgur.com/kTx99hO.png)

	+ Por último, debemos indicarle a ZotFile que queremos que cada vez que carguemos un archivo nuevo a nuestra biblioteca, lo mueva a esta carpeta.
5. Hacemos click en "Herramientas" y luego "Preferencias de ZotFile" ![](https://i.imgur.com/T815LNG.png)
6. Y seleccionamos la misma carpeta que seleccionamos en 3. ![](https://i.imgur.com/JwrDNIf.png)

## 3) Better BibTeX para Zotero
BibTeX es (una) de las maneras en las que se manejan las biblografías en LaTeX. _Better BibTeX for Zotero_ permite incorporar Zotero de manera más sencilla a LaTeX.

### Instalación

Tal como ZotFile, Better BibTex se instala como una extensión a Zotero.

1. Vamos al [sitio de Better BibTex] y descargamos el .xpi (https://retorque.re/zotero-better-bibtex/) ![](https://i.imgur.com/.png) ![](https://i.imgur.com/e7I97ex.png)
2. Tal como hicimos con ZotFile más arriba, lo instalamos desde el gestor de complementos de Zotero.
3. Hacemos click en "Herramientas" y luego "complementos". ![](https://i.imgur.com/iWZNDt1.png)
4. Ahora "Instalar complemento desde archivo" y buscamos el .xpi de Better BibTex que descargamos en 1. ![](https://i.imgur.com/u8SG2Sr.png)
5. Seguimos los pasos, tal como hicimos con ZotFile. También tendremos que reiniciar. ![](https://i.imgur.com/c7EvyTQ.png)
6. Después de reiniciar Zotero, nos recibe esta pantalla de bienvenida para configurar el complemento ![](https://i.imgur.com/iv0P9YJ.png)
7. Es muy probable que sea la primera vez que lo usan, así que recomendamos usar esa opción. Después hacemos click en "Siguiente" hasta terminar la configuración. ![](https://i.imgur.com/I5mOegr.png)

### Como usarlo

A diferencia de ZotFile, Better BibTex es un complemento que funciona casi solo. Recordemos que lo necesitamos sólo si quisiéramos usar LaTeX para escribir, por lo que queremos que Zotero (con Better BibTex) nos genere un archivo .bib con todas las "claves" que necesitamos para que LaTeX pueda armar la bibliografía automáticamente (como bien (mostró Valentín en el último encuentro del ciclo de talleres)[https://github.com/valentinbasel/taller_latex]).Para ello necesitamos hacer la primera exportación de manera manual. 

1. Para esto vamos a "Archivo" y seleccionamos "Exportar biblioteca". ![](https://i.imgur.com/R1gpm5k.png)
2. Del menú desplegable, seleccionamos Better BibLaTeX. ![](https://i.imgur.com/DQAORjn.png)
3. Y hacemos click en "Mantener actualizado". Esto último es muy importante, porque cada vez que hagamos un cambio en nuestra biblioteca, el complemento actualizará automáticamente el archivo .bib que generemos. (Y nos evita tener que hacer esto a mano cada vez que agreguemos algo a nuestro Zotero). ![](https://i.imgur.com/AfP39Ft.png)
4. Hacemos click en "Ok" y nos va a pedir que elijamos una carpeta para guardar el archivo .bib. A modo de sugerencia, para asegurarnos que esté disponible en cualquier dispositivo, pueden elegir la carpeta de la nube que usen (OneDrive para este ejemplo). ![](https://i.imgur.com/23KUA0l.png)
5. El archivo .bib con todas las claves bibliográficas listas para usar en LaTeX ya está creado y listo en la nube para que podamos trabajar desde cualquier dispositivo. ![](https://i.imgur.com/52d5HF9.jpg)
