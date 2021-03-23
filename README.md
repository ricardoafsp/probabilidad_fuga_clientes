# Probabilidad de una posible fuga de clientes de una compañía en base a su edad y sus consumos.

Los datos fueron obtenidos de distintos archivos csv, luego mergeados para trabajar con una única tabla.

Se usaron distintos algoritmos de machine learning, entre ellos random forest y xgboost, también se usó grid search para lograr obtener los mejores parámetros posibles.

# Conclusión:
Los clientes que tienen más de un 70% de probabilidad de marcharse de la compañía son los que cumplen las siguientes características:

* El 95.9% tienen menos de 40 años.
* El 93.6% no tienen incidencia o reclamación.
* El 99.8% no tienen ningún tipo de financiación o descuento.
* El 92.9% tienen contratado el paquete de tv-futbol.
* El 87.4% no tienen ninguna linea en impago.

Por tanto, la campaña que tendría que lanzar esta compañía es hacia clientes menores de 40 años, que sean buenos clientes (líneas sin impago), que no esten financiados o con descuentos por parte de la empresa y que tengan contratado el paquete de fútbol.

También me gustaría comentar que en base a la campaña que se quiera realizar los % se podrían ajustar, así como verificar alguna variable en concreto como verifiqué las anteriores, por poner ejemplo.
