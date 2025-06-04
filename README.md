# formulario_Andres_Infante_3147235


## FORMS
- importante que por campo hay un label junto con un input
- usamos "autofocus" para autoseleccionar el campo
- para campos requeridos usamos etiqueta "required"
- texto de ayuda en cada campo "placeholder"
- Los checkboxes permiten seleccionar múltiples opciones

## BUENAS PRACTICAS
- Uso de contenedores div para separar adecuadamente cada sección
- Uso de los botones principales bien ubicados y diseñados segun lo establecido

## VALIDACIONES
- /pattern/ = define patrones
	- [] permite los caracteres permitidos ([A-Za-z ])
	- {} define caracteres mínimos y máximos ({3,40})

- Validación del archivo adjunto para asegurar que se cargue un documento.
- validaciones con atributos required, type, y pattern segun cada campo donde se requeria 

## TIPOS DE ENTRADA USADOS
- Texto (<input type="text">)
- Imagen (<input type="image">)
- Fecha (<input type="date">)
- Radio (<input type="radio">)
- Checkbox (<input type="checkbox">)
- Archivo (<input type="file">)
- Botón (<button>, <input type="submit">)

## CAMBIOS AL CODIGO ORIGINAL
    - Se reemplazo el campo de edad por fecha de nacimiento
    - Se agrego el campo de conocimiento en lenguajes para que se puedan marcar multiples opciones segun el    
    estudio de la persona
    - Se agrego el campo para subir un archivo en este caso "Subir hoja de vida"
    - Se agrego el campo para seleccionar el genero mediante las opciones de codigo radio
    - Se agrego una parte dedicada a las preferencias de desarrollo
