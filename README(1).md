# Tasa de cambio y exportaciones en República Dominicana

En este proyecto analicé la relación entre las exportaciones mensuales y la tasa de cambio de venta del dólar estadounidense en República Dominicana. Trabajé con 33 meses de datos, desde enero de 2023 hasta septiembre de 2025, utilizando R para preparar la información, explorar las variables y ajustar un modelo de regresión lineal simple. El proceso y sus resultados quedaron documentados en R Markdown.

## Conclusiones del proyecto

El análisis mostró una **asociación positiva entre las exportaciones y la tasa de cambio** durante el período estudiado. En la muestra, los meses con mayores exportaciones tendieron a coincidir con una tasa de venta del dólar más alta, aunque con diferencias importantes entre los meses.

Según la recta estimada, una diferencia de **USD 100 millones en las exportaciones** se asocia con aproximadamente **RD$0.74 por dólar** adicionales en la tasa de cambio de venta. Esta estimación describe la relación observada en los datos y no demuestra que un aumento de las exportaciones provoque ese cambio.

El modelo explicó aproximadamente el **19.87 % de la variabilidad de la tasa de cambio**. Esto indica que las exportaciones, por sí solas, ofrecen una explicación limitada de su comportamiento. Aunque la pendiente resultó estadísticamente significativa bajo los supuestos del modelo clásico, ese resultado debe interpretarse con cautela por tratarse de observaciones mensuales cuya dependencia temporal no fue evaluada.

La conclusión principal es que existe una relación que merece seguir explorándose, pero este modelo no permite explicar por completo la dinámica cambiaria ni afirmar que pueda predecirla. Para ampliar el estudio sería necesario considerar otras variables económicas, revisar el comportamiento temporal de las series y evaluar el modelo con datos distintos de los utilizados para ajustarlo.
