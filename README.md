# ejercicioFunciones

Proyecto de Programación Secuencial:
Estimador de Remodelación
Práctica de Fundamentos de Programación
Marzo de 2026
Contexto del Problema
Una empresa de remodelaciones necesita un sistema automatizado para calcular la
cantidad de materiales y el presupuesto necesario para renovar una habitación rectan-
gular. El programa debe calcular el costo de instalar loseta en el piso y pintar las cuatro
paredes.
Requerimientos de Entrada
El programa debe solicitar al usuario ingresar los siguientes datos por teclado:
- Largo de la habitación (en metros).
- Ancho de la habitación (en metros).
- Altura de las paredes (en metros).
- Precio por metro cuadrado de loseta.
- Rendimiento de la pintura (cuántos metros cuadrados rinde un litro).
- Precio por litro de pintura.
Cálculos a Realizar (Salidas Esperadas)
El sistema debe procesar los datos de entrada e imprimir en pantalla la siguiente infor-
mación:
1. Área del suelo (para saber la base de loseta necesaria).
2. Total de loseta a comprar: Al área del suelo se le debe sumar obligatoriamente
un 10% adicional por concepto de desperdicio o recortes.
3. Área total de las paredes (perímetro de la habitación multiplicado por la altura).
4. Litros de pintura necesarios para cubrir toda el área de las paredes.
1
5. Presupuesto parcial de loseta (cantidad de loseta a comprar × precio unitario).
6. Presupuesto parcial de pintura (litros necesarios × precio por litro).
7. Costo Total Estimado (suma de ambos presupuestos).
Restricciones Técnicas y Estructura
Para evaluar el dominio de la programación estructurada y la modularidad, se deben
cumplir estrictamente las siguientes reglas:
- Cero Estructuras de Control: Queda absolutamente prohibido el uso de if, else,
switch, for, while o do-while. El flujo del programa debe ser 100% secuencial.
- Arquitectura de Dos Archivos: La solución debe dividirse en dos archivos .java:
- Archivo 1 (Clase de Herramientas): Debe contener únicamente métodos es-
táticos (public static) que realicen las operaciones matemáticas (ej. calcu-
lar área, calcular perímetro, aplicar porcentaje extra, calcular costo). No debe
contener ningún método main ni interactuar con el usuario.
- Archivo 2 (Clase Principal): Debe contener el método main. Su única respon-
sabilidad es leer los datos del usuario mediante Scanner, invocar los métodos
matemáticos del Archivo 1 para procesar la información, y mostrar los resul-
tados finales en consola.
2
