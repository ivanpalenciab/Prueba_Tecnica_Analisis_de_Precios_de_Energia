# 📊 Prueba Técnica: Análisis de Precios de Energía

## Descripción  
Este proyecto es un sistema de análisis de datos que obtiene información sobre precios de energía desde una API, procesa los datos y los almacena en una base de datos SQLite. Está desarrollado en **Python** utilizando **Jupyter Notebook** y varias bibliotecas de análisis y visualización de datos.  

## 🔍 Funcionalidades  
- Obtener datos de precios energéticos desde una API externa.  
- Procesar y limpiar datos temporales.  
- Imputar valores faltantes.  
- Calcular métricas estadísticas:  
  - **Precio promedio diario**  
  - **Promedio móvil de los últimos 7 días**  
- Visualizar tendencias de precios.  
- Almacenar los resultados procesados en una base de datos SQLite utilizando **SQLAlchemy**.  

## 📡 API Utilizada  
Los datos se obtienen de la siguiente API:  
https://l2h237eh53.execute-api.us-east-1.amazonaws.com/dev/precios?start_date=2024-03-15&end_date=2024-04-14

El conjunto de datos contiene registros desde el **15 de marzo de 2024** hasta el **14 de abril de 2024**.  

## 🛠 Tecnologías Utilizadas  
- **Python**  
- **Jupyter Notebook** 
- **requests** → obtención de datos desde la api
- **Pandas** → Manipulación y limpieza de datos  
- **Matplotlib** → Visualización de datos  
- **SQLAlchemy** → Conexión y gestión de la base de datos SQLite 

**Contacto:** ivanpalenciab@gmail.com 
**Telefono:** 3004434221
