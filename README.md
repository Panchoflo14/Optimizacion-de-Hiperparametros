# 📌 Clasificación de Correos Spam con Random Forest  

Este proyecto implementa un modelo de **Random Forest** para clasificar correos electrónicos como **spam** o **no spam**. Se optimizan los hiperparámetros utilizando `GridSearchCV` y `RandomizedSearchCV` para mejorar la precisión del modelo.  

## 📂 Contenido del Repositorio  
- `emails.csv` → Dataset utilizado para entrenar el modelo.  
- `modelo_random_forest.pkl` → Modelo entrenado y guardado en formato `.pkl`.  
- `Optimización_Hiperparametros.ipynb` → Notebook con la optimización del modelo.  
- `LICENSE` → Información sobre la licencia del proyecto.  
- `README.md` → Documentación del repositorio.  

## 🛠 Librerías Utilizadas  
Este proyecto usa las siguientes librerías en Python:  
- `pandas` → Manejo y análisis de datos.  
- `numpy` → Operaciones numéricas y manejo de matrices.  
- `scikit-learn` → Implementación de Random Forest y optimización de hiperparámetros.  
- `joblib` → Guardado y carga del modelo entrenado.  

Para instalarlas, puedes ejecutar:  
```
pip install pandas numpy scikit-learn joblib
```

## 📊 Modelo y Resultados  
- **Modelo:** `RandomForestClassifier` entrenado con hiperparámetros optimizados.  
- **Precisión obtenida:** `97.49%` en el conjunto de prueba.  
- **Optimización realizada con:** `GridSearchCV` y `RandomizedSearchCV`.  

## 📄 Licencia  
Este proyecto está bajo la **MIT License**.  

## 📬 Contacto  
📧 **Email:** panchoflo13@gmail.com
🔗 **GitHub:** [Panchoflo14](https://github.com/Panchoflo14)