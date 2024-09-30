# Prueba tecnica Brayan Ruiz


## Herramientas Utilizadas
- Consola del navegador: Se utilizo la consola para identificar errores de JavaScript en tiempo de ejecucion.
- Editor de codigo: Se utilizo VS code para revisar y corregir el codigo HTML, CSS, y JavaScript.
- GitHub: Se utilizo para controlar las versiones del codigo y documentar los cambios.

## Errores y Soluciones

### 1. Generacion Incorrecta del Numero Aleatorio
- Descripcion: El numero aleatorio no se generaba correctamente, ya que Math.random() * 10 producia un rango de 0 a 9.
- Solucion: Se cambio a Math.floor(Math.random() * 100) + 1 para generar un numero entre 1 y 100.

### 2. Selector de Elemento Incorrecto
- Descripcion: El selector para el elemento que muestra si el numero es mayor o menor estaba mal definido: document.querySelector('lowOrHi').
- Solucion: Se corrigio a document.querySelector('.lowOrHi') para seleccionar correctamente el elemento.

### 3. Escritura Incorrecta de addEventListener
- Descripcion: La funcion de escucha de eventos estaba mal escrita como addeventListener.
- Solucion: Se corrigio a addEventListener con la E en mayuscula para evitar errores de referencia.

## Pruebas Realizadas

- Prueba de funcionalidad basica: Se comprobo que el juego funcionara correctamente al ingresar numeros y recibir mensajes de retroalimentacion correctos.
- Prueba de limite de intentos: Se verifico que el juego termine despues de 10 intentos y muestre el mensaje correcto.
- Prueba de entrada no valida: Se probo que ocurre cuando se ingresan valores no enteros (letras, simbolos) para confirmar que no cuentan como intentos.


