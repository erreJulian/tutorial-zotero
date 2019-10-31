Tutorial para instalar Zotero, ZotFile y Better BibTex para Zotero.

## Primeros pasos
 
1. En [la página de Zotero](http://www.zotero.org) hacer click en "Download".
2. Descargar para el sistema operativo que usen e instalar. ![](https://i.imgur.com/fUxf4AE.png)
3. Luego instalar el Conector. Es lo que permite cargar cosas directamente desde el navegador que prefieran. (Más sobre esto, luego) ![](https://i.imgur.com/tXdNVoR.png)
4. Tenemos Zotero instalado en la compu, pero la base de datos todavía está vacía: ![](https://i.imgur.com/pCo4K1A.png)
5. Podemos sumarle cosas arrastrando y soltando archivos de cualquier carpeta a la pantalla principal: ![](https://i.imgur.com/bSJDgfL.png)
6. O usar el conector que se instaló en 3. y agregar desde la página de la revista que nos interese:![](https://i.imgur.com/0ny7xCO.png)
    + Debería salir un cartel como el siguiente: ![](https://i.imgur.com/dgERWmh.png)   
7. Y aparece el artículo en nuestra biblioteca, con los metadatos en el panel de la derecha. ![](https://i.imgur.com/MA9wiNQ.png)


## ZotFile

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

## Better BibTeX para Zotero
BibTeX es (una) de las maneras en las que se manejan las biblografías en LaTeX. _Better BibTeX for Zotero_ permite incorporar Zotero de manera más sencilla a LaTeX.

### Instalación

1. Tal como ZotFile, Better BibTex se instala como una extensión a Zotero.
