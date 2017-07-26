# actividad-15
Respuestas repaso Jquery / Javascript

## Actividad Presencial 1 de Jquery.

### Respuesta Nº 1

- ¿Cuál es el error?

~~~
  var calcularIMC = function(peso, estatura){
    return peso / (estatura * estatura);
  }

  var interpretarIMC = function(peso, estatura){
  var imc = calcularIMC(peso, estatura);
    if (imc >= 25){
      return "sobrepeso";
    } else if (imc > 19) {
      return "ok";
     } else {
      return "bajo peso";
      }
    }
  
  resultado = interpretarIMC(85,1.95);
  console.log(resultado);
  
  ~~~

## Ejercicios de desarrollo

Para realizar estos ejercicios entra a: https://jsfiddle.net/1fk5fyLc/7/
Recuerda documentar todos los pasos en un archivo llamado tunombre.md para que puedas subir tus respuestas a la plataforma.

- Pon tu nombre al atributo value del campo first name
- Pon el valor a la pregunta Favorite Day of Week a Monday
- Cambia la etiqueta de First name a 'Tu nombre'
- Obtén el valor del atributo 'name' del campo Favorite Day of The Week
- Escoge la opción Female de la pregunta de género.
- Encuentra la primera form del documento y pon el atributo name = personal_info
- Encuentra la primera form del documento y pon el atributo name = job_info
- Agrega un título h1 a cada una de las formas que diga 'Entrevista personal', 'Entrevista de trabajo' respectivamente
- Agrega un título a la pregunta Male/Female 'Gender'
- Agrega una pregunta Email: con un input de tipo texto después de last name
- Agrega la clase form a ambas for-.
