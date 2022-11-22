# DEPLOY

**Sitios en los cuales podemos desplegar aplicaciones web.**

Actualmente (año 2022) existen numerosos sitios donde es posible desplegar aplicaciones web. La mayoría de las veces, como desarrolladores, nos interesará hacer uso de PaaS (Platform as a Service). A continuación se muestran algunos sitios que proporcionan PaaS. 

Podemos establecer **3 categorías**:

- **Contenido estático**. Sólo archivos HTML, CSS y JS. Además de ***assets***: imágenes, fuentes de letra, documentos PDF, ...
- **Frontend**
- **Backend**

Aunque he distinguido entre sitios para despliegue frontend y despliegue backend, en la práctica esta diferencia queda un poco difuminada, puesto que en ambos casos existe la posibilidad de despliegar aplicaciones fullstack, es decir, que dispongan tanto de frontend como backend.

---

## Contenido estático

Estos sitios se parecen más a un alojamiento o hosting tradicional que a un PaaS. Simplemente proporcionan un servidor web que sirve contenido estático, no siendo necesario que el servidor procese ningún lenguaje de servidor. No se realiza ningún tipo de ***build*** al contenido.

- ### GitHub Pages

- ### Amazon S3


---

## FrontEnd

Suele ser habitual realizar algún tipo de ***build***. Es decir, se transforma el código fuente a contenido estático. Es el caso de proyectos realizados con Angular, React, Vue o Svelte, entre otros.

Existe una tendencia a ofrecer cada vez mayores funcionalidades. Una de ellas es la ampliación al backend, es decir, poder alojar no sólo aplicaciones frontend sino también aplicaciones fullstack donde exista un frontend y un backend. Esto se consigue permitiendo desplegar aplicaciones desarrolladas con los frameworks Next, Nuxt o SvelteKit.

Prácticamente en todos los casos, la plataforma sobre la que se trabaja es **Nodejs**.

Estos sitios suelen ofrecer la opción de registranos con nuestra cuenta de GitHub. Una vez nos hayamos registrado, para desplegar una app basta con indicar el repositorio de GitHub donde tenemos el código fuente de la app.

Muchos de estos sitios están en proceso de constante evolución, por lo que es arriesgado indicar qué frameworks se soportan o no, puesto que esto puede cambiar con el tiempo. Se anima al lector a examinar las funcionalidades que cada sitio puede ofrecer.
 
- ### Vercel

- ### Netlify

- ### Surge.sh

- ### Glitch.com

---


## Backend

Cuando nuestra aplicación web tiene una lógica que debe ejecutarse en el servidor. Esta lógica se implementa en algún lenguaje de servidor, como pueder ser PHP, Java, Python, Node y muchos otros. 

Algunos sitios también proporcionan varios tipos bases de datos o DBaaS (DataBase as a Service).

Muchos de los sitios, sobre todo los de más reciente aparición, aún están redefiniendo la interfaz y servicios que ofrecen, por lo que es arriesgado indicar qué lenguajes de programación y frameworks del lado del servidor se soportan o no, puesto que esto puede cambiar con el tiempo. Se anima al lector a examinar las funcionalidades que cada sitio puede ofrecer.

En estos sitios también es posible alojar el frontend junto con el backend, siempre que sea contenido estático o generado mediante el patrón MVC.

Estos sitios suelen ofrecer la opción de registranos con nuestra cuenta de GitHub. Una vez nos hayamos registrado, para desplegar una app basta con indicar el repositorio de GitHub donde tenemos el código fuente de la app.

A continuación se comenta someramente, las características específicas más reseñables de cada sitio.


- ### Heroku.com

Es uno de los sitios más veteranos. Es el PaaS que más lenguajes soporta y cuya interfaz y forma de uso es más amigable. Desde finales de 2022 pasa a ser de pago. Sigue existiendo plan ***free*** pero es necesario registrar tarjeta de débito o crédito.

- ### Render.com

Nuevo sitio que pretende cubrir el hueco dejado por Heroku para desarrolladores que desean un plan free sin necesidad de indicar tarjeta de débito o crédito. Ofrece soporte a menos lenguajes de programación que Heroku.

- ### Railway.app

Nuevo sitio que pretende cubrir el hueco dejado por Heroku para desarrolladores que desean un plan free sin necesidad de indicar tarjeta de débito o crédito. Ofrece soporte a menos lenguajes de programación que Heroku.
Es posible desplegar usando distintos mecanismos. Uno de ellos es a través de contenedores Docker y archivos Dockerfile.
También ofrece algunos tipos de BBDD. 

- ### Cyclic.sh

Por ahora lo he usado muy poco, así que no puedo destacar nada en concreto.

- ### Fly.io

Por ahora lo he usado muy poco, así que no puedo destacar nada en concreto.

- ### Replit.com

Dispone de IDE on-line.

