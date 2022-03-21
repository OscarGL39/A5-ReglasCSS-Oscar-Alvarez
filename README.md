# A5-reglas 
1. El primer paso es crear una carpeta con la hoja de estilos, creamos una carpeta llamada "css" y dentro creamos un archivo llamado "styles.css".
2. A continuación enlazamos el index.html con la hoja "styles.css"
3. Tenemos que aplicar las fuentes que usaremos en nuestras páginas y para ello en la oja de estilos ponemos lo siguiente. 
    -@import url('https://fonts.googleapis.com/css2?family=Smooch+Sans:wght@500&display=swap');
    -@import url('https://fonts.googleapis.com/css2?family=Smooch+Sans:wght@300&display=swap');
4. Una vez hecho creamos un selector de clase llamado "flex" con las características "display: flex; align-items: center; justify-content: center;" 
5. A continuación creamos un selector id con la palbra "header" y le aplicamos las características " font-family: 'Smooch Sans', sans-serif; background-image: url("../img/Fondo-Encabezado.png"); height: 100vh; background-size: cover; background-position: center;" todo esto sirve para escoger el tipo de fuente que queremos, para que tengamos una imagen de fondo y lo demás para configurar que se proporcione bien a la resolución de la pantalla.
6. Ahora ponemos un selector de clase con nombre "h1-tittle" y las características " color: white; font-size: 50px; padding: 25% 35%; padding-top: 0; text-align: center;" esto se hace para que la letra sea de color blanco tenga un tamaño de 50px un margen determinado y que el texto se alinee al centro .
7. A continuación creamos un selector de tipo con la etiqueta "body" y de características ponemos "margin: 0%;" esto sirve para que no haya ningún margen.
8. Ahora creamos un selector id con nombre "body" y aplicamos las características "padding: 1% 25%; background-color: aqua; font-family: 'Smooch Sans', sans-serif;" estas características sirven para que el margen sea mínimo por los lados y arriba un 25%, para que el color de fondo sea color aqua y que el tipo de fuente sea la que deseas.
9. Ahora abrimos un selector de tipo con la etiqueta "h2" y la característica "color: blue;" para que la letra salga de color azul.
10. A continuación abrimos otro selector de tipo con la etiqueta "img" y las características "width: 100%; border-radius: 5%" para que se ajuste la imagen a la maxima altura y que los bordes sean un poco redondos.
11. Para casi acabar hacemos un selector de tipo de la etiqueta "iframe" y le aplicamos las características "width: 100%; border-radius: 5%;" para que se ajuste el video a la maxima altura y que los bordes sean un poco redondos.
12. Y para acabar abrimos el último selector de tipo "a" y ponemos la característica "text-decoration:none" para quitar todo tipo de subrayado, reborde ... 
13. A continuación hacemos un selector id con nombre "footer" y aplicamos las características "background-color: black; padding: 25%; padding-top: 25px; padding-bottom: 25px;" esto sirve para darle color de fondo a nuestro pie de página, darle margen tanto por los lados como por arriba.
14. Por último de verdad abrimos el selector de tipo "footer" y aplicamos las características "text-align: center;
    color: white;" esto sirve para darle color a las letras de dentro y para alinearlas en el centro.