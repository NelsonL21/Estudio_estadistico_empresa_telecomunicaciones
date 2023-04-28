# Estudio estadístico de la empresa MEGALINE

Se realizará un estudio estadístico en la empresa de telecomunicaciones Megaline. La empresa ofrece a sus clientes dos tarifas de prepago, Surf y Ultimate.   El departamento comercial quiere saber cuál de los planes genera más ingresos para ajustar el presupuesto de publicidad.

Se realiza un análisis preliminar de las tarifas basado en una selección de
clientes relativamente pequeña. Se tienen los datos de 500 clientes de Megaline:
quiénes son los clientes, de dónde son, qué tarifa usan y la cantidad de llamadas
que hicieron y los mensajes de texto que enviaron en 2018. Tu trabajo es analizar el
comportamiento de los clientes y determinar qué tarifa de prepago genera más
ingresos.

## Conclusión general


Primeramente, se lograron corregir los errores en los datos, referentes a los minutos en las llamadas, en los cuales, habia tiempos inferiores a 1 minuto que debian ser redondeados.

Así mismo, se modificaron los tipos de datos, para que los calculos posteriores resultasen más sencillos.

Del mismo modo, se evidenció que las medias de cada una de las distribuciones de los planes se asemejan bastante, lo que a simple vista nos podría hacer pensar que los usuarios pagan los mismo, independientemente del plan, sin enbargo las medianas y la distribución estandar, nos hacen ver esto no es del todo cierto. 

Ya que, en el caso del plan Surf la desviaicón estandar es bastanet grande, haciando ver que los datos se distribuyen de una fomr amas alargada y no tanto hacia arriba. Al contrario de los que optan por el plan ultimate.

En los gráfico se vió la tendencia violatil del plan Surf con respecto al Ultimate, donde hubo personas que exdieron por mucho su limiete de datos, Quizas por no tomar en cuenta que por tener el plan mas económico, no necesariamente iban a gastar menos. Esto calramente iba a influir en la media de los datos, sin embargo la medianas nos daba el valor cercano a al realidad que son unos 40USD para ese plan, haciandonos ver, que no esta tan cerca de Ultimate como parece, es por ello que a continuación se plantean 2 hipótesis, que se resolveran por medio de métodos estdísticos de comparación de distribuciones. Llamadas y mensajes dispersando mucho la distribución.

Por último se evidenció que, ambas hipótesis nulas fueron rechazadas. Arrojando que lo más probable es que efectivamente ambos planes no ingresen lo mismo al mes y que, es muy improbable que en ambas ciudades se pague lo mismo, aceptando entonces la hipótesis de que el consumo es distinto entre Newark-Jersey y el resto de ciudades del DataSet.

Siendo entonces la hipótesis alternativa de cada una que:

1.   El ingreso promedio de los planes Surf y Ultimate Difiere.
2.   El ingreso promedio de los usuarios en el área de estados Nueva York-Nueva
Jersey es diferente al de los usuarios de otras regiones.
