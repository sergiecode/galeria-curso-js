## Link al curso completo de Javascript en Youtube:
[VIDEO CURSO GRATIS COMPLETO: JavaScript Desde Cero por Sergie Code](https://youtu.be/N8Xt5rP_DUo)


# Galería Simple con JavaScript

Este repositorio contiene una galería simple implementada con HTML, CSS y JavaScript.

## Funcionalidad

La galería permite ampliar una imagen cuando se hace clic en ella. Esto se logra mediante el uso de la siguiente función de JavaScript:

    function ampliarImagen(imageUrl) {
        var previsualizacionImagen = document.getElementById("previsualizacionImagen");
        previsualizacionImagen.src = imageUrl;
    }

Cuando se invoca la función `ampliarImagen` con la URL de la imagen como argumento, se actualiza el atributo `src` de un elemento de imagen con id "previsualizacionImagen". Esto muestra la imagen ampliada en un área específica de la página.

## Uso

Para utilizar esta galería en tu proyecto, sigue estos pasos:

1.  Clona este repositorio o descarga los archivos HTML y CSS provistos.
    
2.  Asegúrate de tener una estructura HTML adecuada para la galería, que incluya un elemento de imagen con el id "previsualizacionImagen" donde se mostrará la imagen ampliada.
    
3.  Enlaza el archivo JavaScript proporcionado (`script.js`) en tu archivo HTML.
    
4.  Asegúrate de tener las imágenes que deseas mostrar en la galería y obtén las URLs correspondientes.
    
5.  Para cada imagen en la galería, agrega un evento de clic que invoque la función `ampliarImagen` con la URL de la imagen correspondiente.
    
    `<img src="ruta-de-la-imagen.jpg" onclick="ampliarImagen('ruta-de-la-imagen.jpg')" alt="Descripción de la imagen">`

Reemplaza `'ruta-de-la-imagen.jpg'` con la URL de la imagen que deseas ampliar.

¡Y eso es todo! Ahora tendrás una galería simple con la capacidad de ampliar imágenes al hacer clic en ellas.
