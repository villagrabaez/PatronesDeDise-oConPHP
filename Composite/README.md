# Introducción al Patrón Composite

El patrón Composite nos brinda una manera elegante y sencilla de componer objetos de manera recursiva en una estructura de árbol en la cual cada objeto individual o grupo de objetos puede ser tratado de la misma manera dado que todos compartirán la misma interfaz base. Composite es también un excelente ejemplo de mezcla entre herencia y composición de objetos que aprendimos en el Curso de programación orientada a objetos con PHP. En el siguiente videotutorial veremos una pequeña introducción a este patrón de diseño estructural antes de comenzar a escribir código.

## Participantes del Patrón Composite

- Componente: interfaz o clase abstracta. Por ejemplo un gráfico en vectores.
- Hoja: objeto primitivo, extiende o implementa de Componente. Por ejemplo una línea.
- Composición: Componente que tiene hijos. Por ejemplo un triángulo dibujado con 3 líneas o una casa dibujada con un rectángulo y un triángulo.
- Cliente:  Código que manipula y usa objetos de tipo Hoja o Composición a través de su interfaz pública «Componente». Por ejemplo el cliente va a llamar al método «dibujar» en un Componente sin importar si es una simple línea o una imagen más completa.

## El Patrón Composite nos permite:

- Representar jerarquías de objetos
- Ignorar las diferencias entre composiciones de objetos y objetos individuales
- Tratar a todos los objetos dentro de la composición de manera uniforme.
- Por lo tanto reducir los condicionales en el código del cliente.
- Escribir nuevas clases de componentes que trabajen de forma automática con estructuras existentes y código del cliente sin necesidad de cambios extra.
- Componer objetos de manera recursiva utilizando programación orientada a objetos.

## Ejemplos de aplicación del patrón Composite:

- Partes de computadora
- Un portafolio de bienes
- Vistas con sub-vistas
- Productos de comida
- Listas de tareas anidadas
- XML