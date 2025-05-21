contenido = """
# 📡 Proyecto: Predicción de Cancelación de Clientes en Interconnect Telecom

## 🧾 Descripción
Este proyecto busca desarrollar un modelo de Machine Learning que prediga si un cliente de la empresa **Interconnect Telecom** está en riesgo de cancelar su servicio. Esto permitirá a la empresa implementar estrategias de retención personalizadas y mejorar la satisfacción del cliente.

## 🎯 Objetivo
Construir un modelo predictivo con un **AUC-ROC ≥ 0.75** y alto rendimiento en otras métricas clave, como **accuracy** y **F1-score**, para detectar de forma precisa a los clientes propensos a abandonar el servicio.

## 📁 Estructura del Proyecto
- `interc_telecom.ipynb`: Notebook principal del proyecto con el análisis completo.
- `README.md`: Descripción del proyecto.
- `.gitignore`: (opcional) Archivos a excluir del control de versiones.

## 🔍 Metodología
1. **EDA y limpieza de datos**
2. **Ingeniería de características**
3. **Balanceo de clases con SMOTE**
4. **Entrenamiento con Logistic Regression, LightGBM y CatBoost**

## 📊 Resultados

| Modelo               | Accuracy | AUC-ROC |
|----------------------|----------|---------|
| Logistic Regression  | 0.93     | 0.98    |
| LightGBM             | **0.95** | **0.97** |
| CatBoost             | 0.88     | 0.95    |
| Dummy                | 0.67     | 0.50    |

✅ El modelo **LightGBM** fue el más eficiente.

## 🧠 Conclusión
El modelo desarrollado permite anticipar qué clientes tienen mayor probabilidad de cancelar el servicio, ayudando a Interconnect a implementar estrategias de retención más efectivas.

## 🛠 Herramientas utilizadas
- Python
- Pandas, NumPy
- Scikit-learn
- LightGBM, CatBoost
- SMOTE (imbalanced-learn)

## 📬 Contacto
**M. Fernanda Corona Ramírez**  
📧 mf.coronarq@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/mfcoronar/)
"""

with open("README.md", "w", encoding="utf-8") as file:
    file.write(contenido)gi