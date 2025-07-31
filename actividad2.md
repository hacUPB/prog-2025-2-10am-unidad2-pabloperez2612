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

[imagen](../prog-2025-2-10am-unidad2-pabloperez2612/Captura%20de%20pantalla%202025-07-31%20105016.png)


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