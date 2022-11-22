# DEPLOY

**Sitios en los cuales podemos desplegar aplicaciones web.**

Actualmente (año 2022) existen numerosos sitios donde es posible desplegar aplicaciones web. La mayoría de las veces, como desarrolladores, nos interesará hacer uso de PaaS (Platform as a Service). A continuación se muestran algunos sitios que proporcionan PaaS. 

Podemos establecer **3 categorías**:

- **Contenido estático** (sólo archivos HTML, CSS y JS. Además de assets -imágenes, fuentes de letra, documentos PDF, ...-)
- **Frontend**
- **Backend**


## Contenido estático

Estos sitios se parecen más a un alojamiento o hosting tradicional que a un PaaS. Simplemente proporcionan un servidor web que sirve contenido contenido estático, no siendo necesario que el servidor procese nigún lenguaje de servidor. No se realiza ningún tipo de ***build*** al contenido.

- ### GitHub Pages

- ### Amazon S3



## FrontEnd

Suele ser habitual realizar algún tipo de ***build***. Es decir, se transforma el código fuente a contenido estático. Es el caso de proyectos realizados con Angular, React, Vue o Svelte, entre otros.

Existe una tendencia a ofrecer cada vez mayores funcionalidades. Una de ellas es la ampliación al backend, es decir, poder alojar no sólo aplicaciones frontend sino también aplicaciones fullstack donde exista un frontend y un backend. Esto se consigue permitiendo desplegar aplicaciones desarrolladas con los frameworks Next, Nuxt o SvelteKit.

Muchos de estos sitios están en proceso de constante evolución, por lo que es arriesgado indicar qué frameworks se soportan o no, puesto que esto puede cambiar con el tiempo. Se anima al lector a examinar las funcionalidades que cada sitio puede ofrecer.
 
- ### Vercel

- ### Netlify

- ### Surge


## Backend

Cuando nuestra aplicación web tiene una lógica que debe ejecutarse en el servidor. Esta lógica se implementa en algún lenguaje de servidor, como pueder ser PHP, Java, Python, Node y muchos otros. 

Algunos sitios también proporcionan varios tipos bases de datos o DBaaS (DataBase as a Service).

Muchos de los sitios, sobre todo los de más reciente aparición, aún están redefiniendo la interfaz y servicios que ofrecen, por lo que es arriesgado indicar qué lenguajes de programación y frameworks del lado del servidor se soportan o no, puesto que esto puede cambiar con el tiempo. Se anima al lector a examinar las funcionalidades que cada sitio puede ofrecer.

En estos sitios también es posible alojar el frontend junto con el backend, siempre que sea contenido estático o generado mediante el patrón MVC.

A continuación se comenta someramente, las características específicas más reseñables de cada sitio.


- ### heroku.com

Es uno de los sitios más veteranos. Es el PaaS que más lenguajes soporta y cuya interfaz y forma de uso es más amigable. Desde finales de 2022 pasa a ser de pago. Sigue existiendo plan ***free*** pero es necesario registrar tarjeta de débito o crédito.

- ### render.com

Nuevo sitio que pretende cubrir el hueco dejado por Heroku para desarrolladores que desean un plan free sin necesidad de indicar tarjeta de débito o crédito. Ofrece soporte a menos lenguajes de programación que Heroku.

- ### railway.app

Nuevo sitio que pretende cubrir el hueco dejado por Heroku para desarrolladores que desean un plan free sin necesidad de indicar tarjeta de débito o crédito. Ofrece soporte a menos lenguajes de programación que Heroku.
Es posible desplegar usando distintos mecanismos. Uno de ellos es a través de contenedores Docker y archivos Dockerfile.
También ofrece algunos tipos de BBDD. 

- ### cyclic.sh

Por ahora lo he usado muy poco, así que no puedo destacar nada en concreto.

- ### fly.io

Por ahora lo he usado muy poco, así que no puedo destacar nada en concreto.


- ### glitch.com

Por ahora lo he usado muy poco, así que no puedo destacar nada en concreto.


- ### replit.com

Dispone de IDE on-line.

