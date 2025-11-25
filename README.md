# taller07-ciclos

## Problema 01 (generar una miniespecificación)
> En un centro de rehabilitación física se realiza un seguimiento a las personas que asisten a sus sesiones de terapia. Cada vez que llega un paciente, el personal registra sus datos en un sistema informático. No se conoce cuántos pacientes asistirán en el día, por lo que el sistema debe permitir ingresar pacientes de manera continua, uno tras otro, hasta que el usuario indique que no desea registrar más.

> De cada paciente se debe almacenar: nombre, edad, altura en metros y peso en kilogramos. Mientras el proceso esté activo, se van acumulando los datos de todos los pacientes ingresados. **Si la edad ingresada es menor a 10 años, ese registro no se considera y no se debe permitir ingresar datos, ni se lo toma como dato para los reportes y promedios.**
    
> Cuando el usuario decida detener el registro, el sistema debe generar un reporte final que incluya el listado completo de los pacientes registrados y, además, mostrar el promedio de las edades, el promedio de las alturas en centímetros y el promedio de los pesos en libras de todas las personas registradas durante la jornada. El informe debe ser útil para que los fisioterapeutas puedan analizar el perfil general de los pacientes atendidos.

> Consideraciones: **(1)** se debe usar una sola impresión final del reporte;
**(2)** Genera dos soluciones con ciclo mientras y haga-hasta

## Problema 02 (genera diagrama de flujo y miniespecificación)

> Una tienda desea registrar 4 productos. Por cada producto se debe ingresar: Nombre del producto, Precio, Categoría (1 = Abarrotes, 2 = Limpieza, 3 = Bebidas). Sin embargo, para el registro de los productos, se deben aplicar reglas internas: 
> * Si el precio es menor o igual a 0, el valor inicial del producto será $0, el
    valor final será $0, el valor del IVA será $0 y porcentaje del IVA será $0.
> * Si el precio es mayor a 0:
>   * Si la categoría es 1 o 2, aplicar un IVA del 12%.
>   * Si la categoría es 3 → aplicar un IVA del 15%.
>   * Cualquier otra categoria será consdirada con un IVA del 20%

> Se debe presentar un reporte como el siguiente.

| Listado de productos |
| :---|
| 1. Producto 1: Arroz (Abarrotes), valor inicial: $15, IVA (12%): $1.8, valor final $16.80
| 2. Producto 2: Agua (Bebida), valor inicial: $5, IVA (15%): $0.75, valor final $5.75
| 3. Producto 3: Pintura (Sin Categoria), valor inicial: $20, IVA (20%): $4, valor final $24.00
| 4. Producto 4: Cromos (Sin Categoria), valor inicial: $0, IVA (0%): $0, valor final $0.00
> 
