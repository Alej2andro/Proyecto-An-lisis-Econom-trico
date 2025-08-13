🎯 Objetivo del Análisis Econométrico
Evaluar rigurosamente el aporte explicativo de la variable dicotómica Género en la determinación del ingreso mensual, mediante la comparación estructural entre modelos de regresión lineal múltiple con y sin dicha variable. El análisis busca establecer si Género tiene un efecto estadísticamente significativo sobre el ingreso, incluso al controlar por otras variables económicas relevantes, y validar su incorporación en estudios orientados a comprender diferencias estructurales en la distribución del ingreso.


📘 Contenido del Análisis Econométrico.

I. Creación de Dataset

II Metodología de análisis estadístico para modelar regresión lineal múltiple
 1) Diagnosis hipotesis iniciales :
 a) normalidad
 b) linealidad
 c) Analisis de homogenidad de varianza (homoscedasticidad)
 d) observaciones independientes
 e) Ausencia multicolinealidad
 2) Construcción Modelo de Regresión lineal Multiple y R²
 3) Estimación puntual de los parámetros
 4) Intervalos de confianzas
 5) Contrastes de hipótesis
 6) Evaluación del aporte explicativo de Género
 7) Análisis de ANOVA
 8) Evalución de ajuste
    
 III Conclusión Final del Análisis Econométrico

🧰 Bibliotecas utilizadas en el análisis econométrico.

📊 Modelado estadístico y pruebas econométricas : 
- import statsmodels.api as sm
- from statsmodels.formula.api import ols
- from statsmodels.stats.stattools import durbin_watson
- from statsmodels.stats.outliers_influence import variance_inflation_factor


📐 Pruebas estadísticas y distribuciones : 
from scipy.stats import f, t, norm


🤖 Modelado predictivo y métricas : 
from sklearn.linear_model import LinearRegression
from sklearn.metrics import r2_score

#🧮 Manipulación numérica : 
import numpy as np


📊 Visualización : 
import matplotlib.pyplot as plt
import matplotlib.image as mpimg
import matplotlib
import seaborn as sns


🎨 Visualización en terminal con Rich : 
from rich import print
from rich.console import Console
from rich.table import Table
from rich.panel import Panel
from rich.markdown import Markdown as RichMarkdown
from rich.align import Align
from rich import box


🧠 Fórmulas y matrices de diseño : 
from patsy import dmatrices


📎 Visualización en Jupyter Notebook : 
from IPython.display import display, Markdown, Latex
    
