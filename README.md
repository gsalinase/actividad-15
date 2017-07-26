# actividad-15
Respuestas repaso Jquery / Javascript

## Actividad Presencial 1 de Jquery.

### Respuesta Nº 1

- ¿Cuál es el error?

~~~js
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

### Respuesta:

- Pon tu nombre al atributo value del campo first name
~~~js
  $ ('input[name= "firstname"]').val('Gonzalo');
  ~~~
- Pon el valor a la pregunta Favorite Day of Week a Monday
~~~js
  $ ('select[name="fav_day"]').val("Monday");
  ~~~
- Cambia la etiqueta de First name a 'Tu nombre'
~~~js
  $ ('label').text('Gonzalo Salinas');
  ~~~
- Obtén el valor del atributo 'name' del campo Favorite Day of The Week
~~~js
  
  ~~~
- Escoge la opción Female de la pregunta de género.
~~~js
  $ ('input[name="sex"]').last().prop('checked',true);
  ~~~
- Encuentra la primera form del documento y pon el atributo name = personal_info
~~~js
  $ ('form').before().attr("name","personal_info");
  ~~~
- Encuentra la primera form del documento y pon el atributo name = job_info
~~~js
  $('form').first().attr("name","job_info");
  ~~~
- Agrega un título h1 a cada una de las formas que diga 'Entrevista personal', 'Entrevista de trabajo' respectivamente
~~~js
  $('form').before('<h1>Entrevista Personal</h1>')
  ~~~
- Agrega un título a la pregunta Male/Female 'Gender'
~~~js
  
  ~~~
- Agrega una pregunta Email: con un input de tipo texto después de last name
~~~js
  
  ~~~
- Agrega la clase form a ambas for-.
~~~js
  
  ~~~
