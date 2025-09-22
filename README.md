# Taller1_DataScience

## Integrantes:
Mateo Parra Ochoa - 202213933

## Objetivo:
El propósito de este taller es poner en práctica la capacidad para analizar datos mediante el uso de técnicas estadísticas y de visualización, con el fin de comprender un conjunto de información, identificar hallazgos relevantes y proponer recomendaciones útiles para la toma de decisiones en el ámbito del negocio.

## Alcance:
El alcance de este trabajo se centró en comprender y depurar un conjunto de datos de reservas hoteleras, identificar las variables más relevantes, analizar patrones asociados a la cancelación y a la ocupación mediante técnicas estadísticas y de visualización, y finalmente proponer recomendaciones prácticas orientadas a mejorar la estabilidad de la demanda y optimizar la utilización de la capacidad hotelera.

## Conclusiones:
Se dereivaron insights con los que posteriormente se realizaron recomendaciones que estan adjuntas en el documento "Informe Ejecutivo.pdf". A continuacion se añaden los insgihts:

Los siguientes insights fueron extraidos a partir de los datos del dataset y derivan del analisis y la estrategia propuesta. 

### Cancelaciones 

El City Hotel registra una tasa de cancelación cercana al 65%, mientras que en el Resort Hotel esta es de solo el 24%, lo que evidencia que el tipo de establecimiento influye directamente en la estabilidad de las reservas. 

Las reservas con mayor anticipación presentan mayor riesgo de cancelación, lo que confirma que a medida que aumenta el tiempo entre la reserva y la fecha de llegada, crece la probabilidad de cambios en los planes de los clientes. 

Las tarifas promedio diarias más altas están asociadas con una mayor tasa de cancelación, lo que refleja sensibilidad al precio y un mayor grado de indecisión entre los clientes que enfrentan costos elevados. 

Los canales de distribución presentan diferencias marcadas: GDS y Undefined superan el 80% de cancelaciones, mientras que los canales Direct y Corporate muestran mayor estabilidad con tasas mucho más bajas. 

El tipo de cliente también es determinante: los clientes Transient concentran el 38% de las cancelaciones, en contraste con los clientes Group o Contract, que muestran tasas mucho menores y mayor confiabilidad. 

### Ocupación y demanda 

En el Resort Hotel las estadías son más largas, tanto entre semana como en fines de semana, lo que refleja su orientación al turismo vacacional, mientras que el City Hotel presenta estadías más cortas vinculadas al mercado laboral y de negocios. 

La demanda presenta un fuerte componente estacional: julio y agosto concentran los mayores volúmenes de reservas efectivas, mientras que enero y noviembre se ubican como meses de menor ocupación, lo que sugiere oportunidades para incentivar la demanda en temporada baja con descuentos o paquetes promocionales. 

Los clientes que viajan con hijos muestran una tasa de cancelación más alta (43.5%) frente a los que no viajan con hijos (32.6%), lo que indica que este segmento requiere estrategias diferenciadas, como mayor flexibilidad o beneficios específicos para familias. 

Los huéspedes que requieren parqueadero resultan ser más estables, con tasas de cancelación prácticamente nulas, lo que los convierte en un segmento atractivo para fidelizar mediante incentivos o servicios adicionales. 

### Instrucciones de Ejecución

Antes de ejecutar cualquier celda del notebook asegurarse de tener una version de python 3.8 o superior. Asi mismo se requiere la instalacion de librerias estandar como:

pandas
numpy
matplotlib
seaborn
scipy
jupyter

El primer paso despues de instaladas las dependencias sera modificar la ruta del archivo 

df = pd.read_csv("C:/Users/wired/Downloads/Taller1_DataScience/data/hotel_bookings_modified.csv")

debe tomarse la ruta o ruta relativa de donde se encuentre el dataset para poder trabajar con los datos solicitados.

Posteriormente se puede dar la ejecución total del notebook celda por celda de forma secuencial y su funcionamiento será optimo.