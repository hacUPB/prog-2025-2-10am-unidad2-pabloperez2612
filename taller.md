# Taller en clase

## ejercisio 1
En una pista de pruebas de aeronaves, el sistema debe verificar si el peso total de la aeronave, incluyendo combustible y carga, supera el límite máximo permitido para el despegue. Dependiendo del resultado, el sistema deberá indicar si la aeronave está lista para despegar o si debe reducir carga o combustible.

| VARIABLE| TIPO| CONTENIDO|
|----------|-------|---------|
|Peso_combustible| Entrada| peso del combustible que tiene el avion|
|Peso_de_la_carga| Entrada| Peso de la carga en el avión|
|400 | Constante| peso del avión sin combustible y sin carga|
|600 | Constante| Límite de peso|
|Peso_total| Salida| Peso total del avión| 
```
Inicio
Leer P_Combustible, P_carga
P_Avion = 400
P_Maximo = 600
P_total = P_combustible + P_carga + P_Aavion
Si P_Maximo >= P_total
    Mostrar: "Adecuado Volar"
Si no 
    P_reducir = P_total - P_Maximo
    Mostrar: "Reducir ": P_reducir
Fin Si
Fin 
```
## ejercisio 2

1. **Registro de altitudes de vuelo**
    
    Un sistema debe registrar la altitud de vuelo cada 10 minutos durante una hora y mostrar todas las mediciones al final.

| VARIABLE| TIPO| 
|----------|-------|
|Altura| Entrada|
|medicion| salida|
```
inicio
Desde i = 0 Hasta i = 5
    Leer altura
    Alturas [i] = altura
Fin desde
Desde i = 0 Hasta i = 5
    mostrar: "alturas" [i]
Fin desde
Fin
``` 

## ejercisio 3
Un sistema mide cada 5 minutos la temperatura en cabina durante una hora. Si en algún momento se detecta una temperatura mayor a 27°C o menor a 18°C, debe indicar que se active el sistema de climatización.

```
inicio
Desde i = 0 Hasta i = 11
    Leer temperatura
    Temperaturas [i] = temperatura
    Si temperatura > 27 
        mostrar: "Activar sistema de climatización en la medición ", [i]
        Si no
        mostar: "no se permite sistrema de activacion", [i]
    Fin si
    Si temperatura < 18
        mostrar: "activar sistema de climatizacion", [i]
        Si no
        mostar: "no activar sistema de climatización", [i]
    Fin si 
Fin desde
Desde i = 0 Hasta i = 11
    mostrar: "Temperatura en medición ", i, ": ", Temperaturas[i]
Fin desde
Fin
```
 




