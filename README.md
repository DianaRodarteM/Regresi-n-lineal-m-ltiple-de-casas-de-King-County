# Regresi-n-lineal-m-ltiple-de-casas-de-King-County
Se realizó una regresión lineal múltiple para explicar el precio de casas de King County


El proyecto ajustó una regresión lineal múltiple para explicar el precio de casas de King County. Calculó los coeficientes con la fórmula matricial β = (X’X)⁻¹X’y y los verificó con statsmodels. Floors no fue significativa (p = 0.83) y se eliminó, así que el modelo final conserva 15 variables, todas significativas, y explica cerca del 70% del precio (R² = 0.695). Los mayores efectos en el precio son estar frente al agua (+$588 mil), la latitud (+$561 mil por unidad) y la calidad de construcción (+$97 mil por nivel). Más habitaciones y mayor año de construcción lo reducen, a igual tamaño. Los residuos no son normales y el número de condición es muy alto, lo que indica multicolinealidad, así que conviene interpretar los coeficientes con cautela.
