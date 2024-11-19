Este proyecto tiene como objetivo obtener conclusiones de valor con respecto a la base de datos
'Internet.csv', que corresponde a la información del mercado Argentino sobre la prestación de Internet


A) Tecnologías empleadas:

import pandas as pd
import numpy as np

import matplotlib.pyplot as plt
import matplotlib

import seaborn as sns
import datetime
import statistics as stat
from random import randint
import decimal

Para realizar la presentación gráfica de los resultados, se empleó Power BI


B) CONCLUSIONES

El análisis se toma desde un punto de vista de negocio: 

I. Ingresos: los que se perciben por la prestación del servicio
II. Penetración hogares: cuántos hogares ya hacen uso de este servicio
III. Totales accesos por tecnología: % de tecnología presentes en el mercado y su evolución con el tiempo


I. INGRESOS

Para este caso tuvo que tenerse presente la particularidad del mercado argentino, el cual históricamente ha estado sujeto a una fuerte devaluación de su moneda, esto es: INFLACIÓN.
Motivo por el cual un ajuste de los datos acorde al IPC anual fue necesario antes de poder obtener la gráfica.
A pesar de esto, se puede ver como resultado un mercado creciente y en desarrollo, lo que da perspectivas de un buen negocio.

III. TOTAL DE ACCESOS
Se analizan el total de accesos por tecnología (sin distinción de provincia), se concluye que la fibra óptica tiene mayor demanda, mientras que ADSL va en caída y cablemódem parece haber alcanzado el límite de su fase de crecimiento.

VI. TOTAL ACCESOS POR PROVINCIA
Se desglosa la totalidad de accesos por provincia, para a analizar donde existe mayor adopción de fibra óptica y ver el margen que se tiene, cmparativamente entre provincias, para lograr esos mismos resultados.


C) Autores: Luis Mata