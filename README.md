# Proyecto 2: Limpieza y procesamiento de datos

## 📝 Descripción
Este proyecto consiste en un análisis profundo y tratamiento de un conjunto de datos de Lending Club, una empresa de préstamos en EE. UU.. El objetivo principal es realizar la limpieza, preprocesado y reducción de dimensionalidad de datos históricos de préstamos (2007-2015) para preparar el dataset para futuros modelos predictivos de riesgo crediticio o estado de préstamos.

## 🛠️ Herramientas y Tecnologías
•⁠ ⁠Lenguaje: Python 3.x 
• Librerías: Pandas, NumPy, Seaborn, Matplotlib, Scikit-Learn. 
• Técnicas Aplicadas: * Análisis Exploratorio de Datos (EDA) y correlaciones. * Imputación de valores faltantes (SimpleImputer). * Escalado de variables (StandardScaler). * Codificación de variables categóricas (LabelEncoder, OneHotEncoder). * Reducción de dimensionalidad (PCA).

## 📊 Dashboard / Resultados
•⁠  ⁠Varianza Explicada: Mediante el análisis de Componentes Principales (PCA), se determinó que los dos primeros componentes explican aproximadamente el 98% de la varianza total de los datos (87% el primero y 11% el segundo). 
• Reducción Óptima: El método del "codo" sugirió que el uso de dos componentes es suficiente para representar la mayor parte de la variabilidad original sin pérdida significativa de información. 
• Calidad de Datos: Se realizó un tratamiento exhaustivo de outliers y multicolinealidad para asegurar la estabilidad de futuros modelos.
