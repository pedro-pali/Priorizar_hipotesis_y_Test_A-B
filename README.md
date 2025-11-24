# Priorizar hipótesis y Test A/B
En la parte 1 de este proyecto aplicamos los frameworks ICE y RIC para analizar y priorizar las hipótesis de un dataset.

Con la librería de pandas y las formulas:
ICE = (Impact X Confidence) / Effort
RICE = (Reach X Impact X Confidence) / Effort
Calculamos para priorizar las hipótesis, ambos resultados salieron un poco diferentes, sin embargo, le dimos preferencia a los de RICE ya que es más serterto aunque la captación de los datos sea más larga.

Como conclusión de la parte 1:
hipótesis más prometedoras son la 9 (Add a subscription form to all the main pages. This will help you compile a mailing list), la 3 (Add product recommendation blocks to the store's site. This will increase conversion and average purchase size) y la 1 (Add two new channels for attracting traffic. This will bring 30% more users), en este orden. 

En la parte 2:
- los primeros 4 ejercicios son de estabilidad de métricas acumuladas; En los cuales agrupamos datos acumulados de promedio de ingresos y pedidos para gráficarlos, calcular su tasa de conversión y obtener conclusiones.

Conclusión de Parte 2. Actividades 1 a 4:
La tasa de conversión de los grupos A/B no se estabilizá, por lo tanto no podemos sacar conclusiones serteras.

Parte 3:
- Análisamos paso a paso los resultados de las pruebas A/B buscando  la significancia estadística de las diferencias en la tasa de conversión y el tamaño del pedido entre los grupos, utilizando los datos "sin procesar" y después procesando los datos (eliminando aomalías)

Conclusiones de parte 3. Actividades 5 a 13:
Calculando los porcentiles 95 y 99 para poner límites superiores, después, al calcular la diferencia relativa entre la conversión entre los grupos y la diferencia relativa del tamaño promedio de pedidos por grupo primero sin procesar y luego filtrados concluyo que la prueba debe de seguir por los menos dos o tres semanas más para volver a calcular las métricas nuevamente.
