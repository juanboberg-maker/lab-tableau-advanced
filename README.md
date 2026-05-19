![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# Lab | Advanced Tableau Visualization

### Learning Outcomes

Upon completion of this lab, you will be able to:

- Create a Choropleth map to analyze geographical data.
- Construct and interpret a regression plot to understand the relationship between two quantitative variables.
- Utilize boxplots to compare distributions and identify outliers in the context of vehicle size categories.
- Assemble a comprehensive dashboard that incorporates a variety of chart types.
- Craft a story in Tableau that summarizes your analytical findings.

### Instructions

Continue your exploration of Tableau's advanced visualization capabilities using the `tableau-lab.tbwx` from the previous lab.

1. **Choropleth Map**: Design a Choropleth map sheet to display the distribution of customers across different **States**. Utilize color density to represent the number of customers, providing an at-a-glance view of regional customer bases.

2. **Regression Plot**: Develop a regression plot sheet that examines the relationship between **Customer Lifetime Value** and **Income**. Interpret the regression line to understand how these variables correlate.

3. **Boxplot Analysis**: Create a boxplot sheet that relates **Total Claim Amount** to **Vehicle Size**. Use this visualization to assess the spread of claim amounts and identify any outliers by vehicle size category.

4. **Dashboard Creation**: Combine the above charts into a unified dashboard. Ensure that the dashboard is organized and allows for interactive exploration of the data.

5. **Story**: Synthesize your analysis into a Tableau story. Construct a narrative that guides viewers through your key findings, providing context and insights drawn from the visualizations
A través del análisis realizado en Tableau se han identificado varias relaciones relevantes entre las variables del dataset. En primer lugar, el scatter plot entre Income y Customer Lifetime Value (CLV) muestra una correlación positiva débil, ya que la línea de regresión asciende ligeramente de izquierda a derecha. Esto confirma parcialmente la hipótesis inicial: los clientes con mayores ingresos tienden a generar un mayor valor para la empresa. Sin embargo, la dispersión de los puntos indica que existen otros factores que influyen de forma más significativa en el CLV.

Por otro lado, el análisis mediante boxplot de Total Claim Amount según el tamaño del vehículo (Vehicle Size) permitió observar diferencias importantes entre categorías. La hipótesis inicial planteaba que los vehículos grandes tendrían reclamaciones más elevadas debido a su mayor coste, pero los resultados mostraron que los vehículos de tamaño medio (Medsize) presentan los importes de reclamación más altos y también la mayor cantidad de valores atípicos (outliers). Esto puede explicarse porque los vehículos medianos son más comunes y representan una opción más equilibrada entre precio, comodidad y uso cotidiano.

Además, el boxplot permitió analizar no solo los valores medios, sino también la dispersión y distribución de los datos, mostrando que existen diferencias significativas en la variabilidad de las reclamaciones entre categorías. En conjunto, las visualizaciones realizadas demuestran cómo Tableau facilita la identificación de patrones, tendencias y anomalías en los datos, ayudando a obtener conclusiones más claras y útiles para la toma de decisiones..
