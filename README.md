# DS_OilyGiant

Tipo de proyecto: DS - Data Science

Sector: Energético

Tecnologías implementadas: Pandas | Numpy | Sklearn <LinearRegression > | Scipy | Matplotlib 

Introducción:

Una empresa petrolera llamada OilyGiant busca identificar las mejores ubicaciones para la apertura de 200 nuevos pozos petroleros y esta buscando crear un modelo que pueda determinar aquellas que den el mayor beneficio posible y que cunmpla con los siguientes criterios:

- Construir modelo para predecir el volumen de reservas en nuevos pozos.
- Seleccionar los pozos con los valores estimados más altos.
- Seleccionar la región con la mayor rentabilidad total de los pozos seleccionados.

Condiciones especiales
 
- Durante la exploración de la región, se realiza un estudio de 500 puntos, seleccionando los 200 mejores para el cálculo de la rentabilidad.
- El presupuesto para el desarrollo de 200 pozos petroleros es de 100 millones de dólares.
- Un barril de materias primas genera 4,5 USD en ingresos. Los ingresos por unidad de producto son de 4500 dólares (el volumen de reservas se expresa en miles de barriles).
- Tras la evaluación de riesgos, conservar solo las regiones con un riesgo de pérdida inferior al 2,5 %. Entre las que cumplen los criterios, seleccionar la región con la mayor rentabilidad promedio.

Conclusiones:
Tras aplicar el método de bootstrap, podemos determinar que la región 2 es la que presenta la mayor probabilidad de generar ingresos y la menor cantidad de pérdidas, a pesar de parecer inicialmente la menos favorable. Esto contrasta con los resultados obtenidos antes del bootstrap, donde las regiones 1 o 3 parecían más prometedoras. En este caso, presentan un mayor porcentaje de riesgo, pero mejores beneficios.
