# 📊 Proyecto: Análisis de una empresa de telecomunicaciones (ConnectaTel)

## 🎯 Objetivo del proyecto
El objetivo principal es analizar el comportamiento de los clientes de ConnectaTel a partir de sus datos de uso (llamadas, mensajes y minutos de llamadas), con el fin de:
- Identificar segmentos de clientes según su nivel de uso y edad.
- Detectar patrones de consumo y outliers relevantes.
- Proponer recomendaciones para mejorar la oferta actual de planes y diseñar nuevos planes adaptados a cada segmento.

---

## 📂 Datasets utilizados
Se trabajó con tres archivos principales:
plans.csv → información de los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra)
users.csv → información de los clientes (edad, ciudad, fecha de registro, plan, churn)
usage.csv → detalle del uso real de los servicios (llamadas y mensajes)


---

## 🔎 Etapas del análisis realizadas
1. **Carga y exploración inicial de datos**  
   - Revisión de valores nulos y outliers.  
   - Análisis de distribuciones y sesgos.

2. **Visualización de datos**  
   - Histogramas y boxplots para llamadas, mensajes y minutos.  
   - Gráficos de barras para variables categóricas (`grupo_uso`, `grupo_edad`).

3. **Segmentación de clientes**  
   - Creación de columnas derivadas:  
     - `grupo_uso` (bajo, medio, alto).  
     - `grupo_edad` (joven, adulto, adulto mayor).  
   - Análisis cruzado de segmentos.

4. **Detección de outliers con método IQR**  
   - Identificación de patrones de uso extremo.  
   - Evaluación de impacto en métricas globales.

5. **Insights y recomendaciones**  
   - Segmentos más valiosos para la empresa.  
   - Propuestas de planes diferenciados por edad y nivel de uso.

---

## ⚙️ Cómo ejecutar el notebook
1. Clona este repositorio en tu máquina local:
   ```bash
   git clone https://github.com/tu_usuario/tu_repositorio.git
