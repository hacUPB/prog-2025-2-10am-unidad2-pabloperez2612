## Símbolos de operaciones en diagramas de flujo

1. **Óvalo (Terminal):**  
   Representa el inicio y el fin del algoritmo.

2. **Rectángulo (Proceso):**  
   Indica una operación o acción, como cálculos o asignaciones.

3. **Paralelogramo (Entrada/Salida):**  
   Se usa para mostrar operaciones de entrada (leer datos) o salida (mostrar resultados).

4. **Rombo (Decisión):**  
   Representa una condición o pregunta que determina el flujo del algoritmo (sí/no).

5. **Flechas (Conector de flujo):**  
   Indican la dirección del flujo entre los símbolos.

6. **Círculo (Conector):**  
   Se utiliza para conectar partes del diagrama cuando el flujo se divide o continúa en otra parte.

### Fuente confiable:
La información fue consultada en el estándar ANSI y en la documentación de diagramas de flujo de la IEEE Computer Society.

![imagen](../prog-2025-2-10am-unidad2-pabloperez2612/Captura%20de%20pantalla%202025-07-31%20105016.png)
<img width="282" height="712" alt="image" src="https://github.com/user-attachments/assets/1837ae50-5580-40e5-b1a2-c5ac436b10ed" />

## ejercisio #2

Construye un algoritmo que, al recibir como datos el ID del empleado y los seis primeros sueldos del año, calcule el ingreso total semestral y el promedio mensual, e imprima el ID del empleado, el ingreso total y el promedio mensual.

##Solución

```
inicio
Leer ID, S1, S2, S3, S4, S5, S6
Total = S1+ S2 + S3 + S4 + S5 + S6
Promedio = Total / 6
Escribir ID, Total, Promedio
Fin
```

### Diagrama de flujo
![ejercisio2](../prog-2025-2-10am-unidad2-pabloperez2612/Diagrama%20de%20flujo%20de%20sueldos.drawio%20(1).png)

## tarea
´´´
inicio
leer Nota1, Nota2, Nota3, Nota4, Nota5, Nota6
Total= N1+N2+N3+N4+N5+N6
Promedio=(Total/6)
Acumulado= Promedio*0.70
Necesario= (3.0 - Acumulado) / 0.30
Escribir Necesario
Fin
´´´
### Diagrama de flujo
![tarea](../prog-2025-2-10am-unidad2-pabloperez2612/Captura%20de%20pantalla%202025-08-05%20102300.png)

### Ejercisio 3

|Variable| Tipo| Comentario|
|--------|-----|-----------|
| Lapices| entrada| Cantidad de lapices|





## pseudocodigo

```
inico
leer lapices
si lapices >= 1000:
   valor_unidad = 85
Si no
   valor_unidad = 90
Fin Si
Precipo = Lapices * valor_unidad
Escru¿ibir "El valor total es:", Precio
FIn
```
## ejercisio 4
 ### Analisis
|Variable| Tipo| Comentario|
 |-------|-----|--------|  
 |Total_compra| Entrada |valor de la compra|
 | descuento | salida | descuento segun el valor de la compra |
 | precio_final | salida | valor a pagar|
 | 15%, 8%, $250000 | Constantes | Descuentos y valor absoluto |

 ### pseudocodigo
 ```
 inicio
 Leer Total_compra
Si   Total_compra >250000
      descuento = Total_compra * 0.15
Si no 
      descuento = Total_compra * 0.8
Fin Si
precio_final = Total_compra = descuento
Escribir "Valor a pagar", precio_final
Fin
```
!imagemn hacerla

## ejercisio 5
El director de una escuela está organizando un viaje de estudios, y requiere determinar cuánto debe cobrar a cada alumno y cuánto debe pagar a la compañía de viajes por el servicio. La forma de cobrar es la siguiente: si son 100 alumnos o más, el costo por cada alumno es de $65.00; de 50 a 99 alumnos, el costo es de $70.00, de 30 a 49, de $95.00, y si son menos de 30, el costo de la renta del autobús es de $4000.00, sin importar el número de alumnos.
|Variable| Tipo| Comentario|
|------------|--------|-------|
| alumnos | entrada | alumnos que van al viaje de estudios | |
| precio_alumno | salida | precio por alumno dependiendo del numero de almunos que van |
| precio_compañia | salida | cuanto se le va a pagar a la compañia, por el numero total de alumnos que van|
| valor_total | salida | precio de entrada por numero de alumnos que van | 
|$65.00, $70.00, $95.00, $4000.00| constante | valor que paga cada alumno dependiendo del numero que vayan|

```
inicio
Leer alumnos 
Si alumno >= 100 
    precio_alumnos = 65
Si no 
   Si alumno >= 50
      precio_alumno = 70
   Si no
      Si alumno >= 30
         precio_alumno = 95
      Si no
         precio_compañia = 4000
         precio_alumno = 4000/alumnos
Fin Si 
Fin 
```


    
<img width="282" height="712" alt="image" src="https://github.com/user-attachments/assets/1837ae50-5580-40e5-b1a2-c5ac436b10ed" />
