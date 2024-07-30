La solución del desafío está organizado de la siguiente manera:

- El análisis exploratorio de los datos, la limpieza y la preparación se encuentran en los archivos
  '1. EDA and Clean.ipynb' y '2- Data Frame selection & metrics.ipynb'.
- Para el modelamiento se realizó el ajuste de tres modelos, detallados cada uno en los archivos
  '3. Modelo-ARIMA.ipynb', '4. Modelo-Prophet.ipynb' y '5. Modelo-XGBoost.ipynb'.
- Los dataset suministrados son los que se generan en el archivo '2- Data Frame selection & metrics.ipynb'.
- En requirements.txt se encuentran las librerías necesarias para ejecutar los notebooks.
- En la carpeta Prophet y XGBoost se encuentran los modelos entrenados para cada uno de los modelos. Los modelos ARIMA no se guardan en disco.
- La carpeta forecast contiene la librería que se construyó para el ajuste y predicción de ventas con XGBoost. 
Este código es solo una aproximación a lo que podría llegar a ser una librería pero requiere de mayor trabajo y documentación para ser utilizada en producción.