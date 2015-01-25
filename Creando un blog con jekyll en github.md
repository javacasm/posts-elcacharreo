---
layout: post
title: Blogging Like a Hacker
---

Vamos a ver el proceso de crear un blog usando **[jekyll](http://jekyllrb.com/)**  (motor de publicación estático, es decir no necesita recompilar tus páginas, sino que existen los ficheros .html que se sirven, lo que lo hace mucho más rápido y cómodo. Ya he intentado montarlo antes, y hablado de ello **[elcacharreo](http://blog.elcacharreo.com/tag/jekyll/)** )

## ¿Por qué hacerlo?

* Porque estoy cansado de lo pesado que es wordpress, de sus continuas actualizaciones, y de la cantidad de conocimiento y tiempo necesario para gestionar algo tan sencillo como [elcacharreo](http://elcacharreo.com). En un primer paso montaré este entorno, en un segundo paso quiero migrar [elcacharreo](http://blog.elcacharreo.com) a jekyll.
* Porque al estar alojado en github puedes tener una copia en local siempre accesible y puedes controlar el 100% del proceso.
* Esta sencillez te permite enfocarte en lo que quieres escribir no en el como, te permite hacerlo desde cualquier lugar.
* Puedes escribir offline y en cualquier momento sincronizar
* Porque es más eficiente
* Porque proporciona un entorno limpio y un diseño muy sencillo que me encanta
* Permite usar Markdown, que es el que me gusta escribir: nada de formatos engorros (ni por supuesto propietarios), nada de tener que instalar programas, basta con un editor de texto ascii.
* Porque mola

## Instalación

Decir que para iniciar el proceso me estoy inspirando en el blog de [fernand0](fernand0.github.io)

1. Empezamos clonando (fork) el repositorio oficial [jekyll now](https://github.com/barryclark/jekyll-now)

2. Cambiamos el nombre de nuestro repositorio (desde la opción settings) al que queremos que sea nuestro sub-dominio (colgando de github.io). En mi caso a javacasm.github.io  

3. Editamos el fichero _config.yml y el about.md

4. A partir de ahora sólo hay que crear ficheros en la carpeta post con el formato **yyyy-m-dd-titulo.md** y recordar incluir la cabera en el formato

	---
	layout: post
	title: Blogging Like a Hacker
	---

5. En la carpeta **layout** tenemos 3 ficheros: default (con el formato de toda la página, donde podemos cambiar la cabecera, el pie o el aspecto en general), post (que será el aspecto cuando estemos visualizando un post concreto) y page (con la estrucrra de una página). En la cabera de cada post indicaremos el layout que queremos usar.


Happy blogging !!