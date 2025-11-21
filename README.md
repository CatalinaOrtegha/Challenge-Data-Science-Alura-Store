# Análisis descriptivo del desempeño de las tiendas. Alura Store

Durante este desafío, se busca ayudar al Sr. Juan a decidir qué tienda de su cadena Alura Store debe vender para iniciar un nuevo emprendimiento. 
Para ello, se analizan datos de ventas, rendimiento y reseñas de las 4 tiendas de Alura Store. 

## Estructura del proyecto

/repo/
   /data
   /graficos
   /notebooks
   Informe_Final.pdf
   README.md

## Descripción general

Este análisis describe las ventas, reseñas y rendimientos de las cuatro tiendas, 
propiedades del Sr.Juan. El principal objetivo de este proyecto, es identificar la tienda con 
menor eficiencia y encontrar alternativas para obtener recursos destinados a una nueva 
inversión.

## Tecnologías utilizadas

*- Google Collab
*- Python
*- Pandas
*- Matplotlib
*- Numpy
*- Folium

## Metodología

*- Cargue y manipulación de datos
*- Creación de visualizaciones
*- Análisis de metricas

## Datos

Los datos provienen de 4 archivos CSV proporcionados por Alura Store, cada uno corresponde a información relevante de las 4 tiendas, los archivos cuentan
con las siguientes columnas:

 0   Producto                 
 1   Categoría del Producto  
 2   Precio                  
 3   Costo de envío          
 4   Fecha de Compra         
 5   Vendedor                
 6   Lugar de Compra          
 7   Calificación             
 8   Método de pago           
 9   Cantidad de cuotas        
 10  lat                     
 11  lon         

 ## Resultados / Visualizaciones

La tienda 1 genera mayores ingresos con un total de 1,150,880,400 en ventas, 
mientras que los menores ingresos se encuentran en la tienda 4 con un valor total 
de 1,038,375,700 en ventas. 

 <img width="477" height="477" alt="Ingresos totales por tienda" src="https://github.com/user-attachments/assets/6b8a28bd-7a55-4454-9c75-9161d52ed441" />

Las categorías con más items vendidos son: Muebles y Electrónicos. Por el 
contrario, la categoría Artículos para el hogar representa menor cantidad de ventas

<img width="550" height="328" alt="Ingresos por categoría del producto de cada tienda" src="https://github.com/user-attachments/assets/3919b9fb-1443-4356-a993-978e03068877" />

La mayor calificación de servicio es para la tienda 3, obteniendo un puntaje de 4.05.  

<img width="574" height="342" alt="Calificacion promedio por tienda" src="https://github.com/user-attachments/assets/9787f5a8-c21e-40eb-8347-1a361707f06b" />

El costo promedio de envío más alto corresponde a la tienda 1 con un valor de 
26,018.61.

<img width="1430" height="581" alt="Costo promedio de envio por tienda" src="https://github.com/user-attachments/assets/b3a52a93-30ed-4d67-a5f3-9e4ea98560ea" />

La Tienda 4 es la dominante en cobertura geográfica. El Caribe y la Zona Andina cuentan con mayor concentracion de puntos de ventas 

<img width="649" height="364" alt="Dispersion geográfica de ventas por tienda" src="https://github.com/user-attachments/assets/a1d1f811-6903-4372-8654-dfb7be0e9460" />


Existe superposición entre tiendas, lo cual indica que compiten en los mismos 
mercados

<img width="495" height="571" alt="Mapa interactivo distribucion geografica de las tiendas" src="https://github.com/user-attachments/assets/113a35ff-f33a-4830-bfbf-a380ab9febd2" />

## Conclusión / Recomendaciones

Se recomienda analizar los puntos de la Tienda 4 ubicados en zonas donde compiten 
directamente con tiendas más rentables, especialmente Tienda 1 y 3. En caso de que 
estos puntos presenten baja rentabilidad o alta canibalización, el Sr. Juan podría 
considerar su cierre o venta para generar liquidez y asignar recursos a su nueva inversión. 
Asi mismo, se sugiere evaluar la descontinuación de artículos como el Set de Vasos y el 
Ajedrez de Mesa, dado que presentan bajas ventas, bajo margen y mínima contribución al 
portafolio. Eliminar o reducir estos productos podría disminuir costos de almacenamiento 
y liberar espacio para productos de mayor rotación y rentabilidad. 

## Autor

Ingrid Catalina Parada Ortega
https://www.linkedin.com/in/ingrid-catalina-parada-ortega-/

