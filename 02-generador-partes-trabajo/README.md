## Generador de Partes de trabajo (en HTML) a partir de un fichero PDF o HTML
<img width="2422" height="447" alt="image" src="https://github.com/user-attachments/assets/b72e8197-fa3e-498b-a4c5-3eb3514e4ebb" />

### Datos de entrada
<b>fuente:</b> Fichero PDF o HTML de un acta de reunión o de la fuente de la que queramos sacar la información
<b>plantilla:</b> la plantilla de datos de salida, vease plantilla.html.
### Parametros
El sistema requiere de una Data Table llamada Paths con los siguientes datos:
<img width="1748" height="277" alt="image" src="https://github.com/user-attachments/assets/7ed218bd-de4d-448e-bf39-8f1a5e4f86ab" />
### Salida
El sistema autorrellena la plantilla HTML con las tareas a realizar. si se usa la plantilla que es adjunta:
  Se generar desplegables de estado que se pueden cambiar
  Se generan campos de observaciones editables
  Los datos se guardan en la cache del navegador por lo que al volver a abrir el navegador los datos se mantienen
