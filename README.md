# Curriculum-vitae-

Etiquetas Nuevas Investigadas:

- details

- dialog

- iframe

¿Para qué sirven y cómo las apliqué en mi currículum?

- details : Esta etiqueta se utiliza para crear secciones de contenido colapsables.
  
- dialog: Esta etiqueta permite crear modales o cuadros de diálogo nativos sin necesidad de JavaScript.

- iframe: Esta etiqueta sirve para añadir multimedia en la pagina como un popup (popover)

Ejemplo de código en HTML donde las utilicé


!DOCTYPE html
html lang="es"
head
    meta charset="UTF-8"
    meta name="viewport" content="width=device-width, initial-scale=1.0"
    titleMi Currículum/title
/head
body

header
    h1Currículum de Ian Walter Badilla Vargas/h1
/header

section
    h2 Habilidades h2
    details
        summaryHabilidades Técnicas/summary
        pHTML, CSS, JavaScript, Python./p
        progress value="80" max="100"80%/progress
    details
section

section
    h2Contacto/h2
    button onclick="document.getElementById('myDialog').showModal()"Abrir Formulario de Contacto/button
    dialog id="myDialog"
        form method="dialog"
            plabelNombre: input type="text" required/label/p
            plabelEmail: input type="email" required/label/p
            pbutton type="submit"Enviar/button/p
            pbutton type="button" onclick="document.getElementById('myDialog').close()"Cerrar/button/p
        form
    dialog
section
