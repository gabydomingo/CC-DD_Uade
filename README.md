Trabajo Práctico Obligatorio
Ciencia de Datos

Grupo: 1
Integrantes: Papaianni Lautaro Ivan (LU: 1170805), Domingo Gabriel Ivan (LU: 1168660), Gómez Etcheber Gerónimo (LU:1125482 )
Profesor: Fransisco Mariano Daniel
Tema a desarrollar: Siniestros viales en autopistas de CABA registrados por AUSA (Autopistas Urbanas Sociedad Anónima)
Consigna: Elegir un dominio a desarrollar, seleccionar la fuente de datos, adquirir un conjunto de datos desde la fuente de datos, investigar y trabajar en ese conjunto de datos y desarrollar una conclusión, análisis o predicción de los mismos.
Fuentes: https://data.buenosaires.gob.ar/dataset/seguridad-vial-autopistas-ausa , https://www.ausa.com.ar/img/mapa_de_autopistas.png
Link al Google Colab: [domingo/gomez/papaianni.ipynb](https://colab.research.google.com/drive/1J8L2AbKWfa6VL8lNYJ1mNF6pENPrGVPb?usp=sharing)
Link al Looker: https://lookerstudio.google.com/reporting/1fbe0e32-b198-4d86-b4d9-772466a82cba

Introducción:
Elegimos trabajar con siniestros viales por la vasta información que puede ofrecer (debido a la frecuencialidad, lamentablemente) y por la posibilidad de poder predecir tipos de siniestros en base a la descripción, para después poder catalogarlos como leves o graves.
Análisis Exploratorio de los Datos:
De los dataset extraídos de la fuente de datos, disponemos de los siguientes tipos de datos: “AUTOPISTA;BANDA_o_RAMAL;PK;CONDICIONES_METEOROLOGICAS;SUPERFICIE_DE_LA_VIA;LESIONADOS;FALLECIDOS;TIPO_DE_SINIESTRO;MOTO;LIVIANO;BUS;CAMION;AÑO;MES;DIA;HORA;DIASEMANA;MES_STR;AÑO_STR;AÑO_MES;FECHA_COMPLETA
”, de los cuales pudimos generar los siguientes gráficos relacionando los distintos tipos de datos en base a los siniestros ocurridos. Estos dataset constan de la cantidad de siniestros registrados por AUSA en los años 2022, 2023 y 2024.
