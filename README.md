# 🔍 Detección de URLs Maliciosas con Support Vector Machine (SVM)  

Este proyecto aborda la detección de URLs maliciosas utilizando **Support Vector Machines (SVM)**, un potente algoritmo de clasificación basado en la teoría de los espacios de características y los márgenes óptimos de separación.  

## 📌 Descripción del problema  
El crecimiento de la web ha facilitado la propagación de ataques cibernéticos mediante URLs maliciosas. Estas pueden utilizarse para phishing, distribución de malware o redirecciones fraudulentas. Tradicionalmente, las listas negras de URLs han sido la primera línea de defensa, pero su efectividad se ve limitada por la constante aparición de nuevas amenazas.  

Este proyecto busca mejorar la detección de URLs peligrosas utilizando **métodos de aprendizaje automático** que pueden identificar patrones en las características de las URLs y clasificarlas automáticamente.  

## 📂 Conjunto de datos  
El dataset incluye cinco tipos principales de URLs:  
- ✅ **Benignas**: Recopiladas de los sitios web más populares y confiables (Alexa Top Sites).  
- 🎣 **Phishing**: URLs utilizadas en ataques de suplantación de identidad.  
- 🦠 **Malware**: Enlaces que distribuyen software malicioso.  
- 🚨 **Defacement**: URLs de sitios legítimos comprometidos con contenido fraudulento.  
- 🔀 **Redirecciones maliciosas**: URLs diseñadas para engañar y redirigir a los usuarios a sitios no seguros.  

## 🎯 Objetivo  
Entrenar un modelo basado en **Support Vector Machines (SVM)** para clasificar automáticamente las URLs en benignas o maliciosas, reduciendo la dependencia de listas negras estáticas.  

## 🛠️ Tecnologías utilizadas  
- 🐍 Python  
- 📊 Pandas  
- 🤖 Scikit-learn  
- 📈 Matplotlib

## 📜 Contenido del notebook  
1. 📊 Exploración y preprocesamiento del dataset  
2. ✂️ División en conjuntos de entrenamiento y prueba  
3. 🏋️‍♂️ Entrenamiento del modelo **SVM**  
4. 🔬 Evaluación del rendimiento del clasificador  
 
