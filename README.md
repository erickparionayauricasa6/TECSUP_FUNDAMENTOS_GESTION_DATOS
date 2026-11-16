# TECSUP - Fundamentos de Gestión de Datos (2026-II)

Repositorio oficial para el almacenamiento, seguimiento y entrega de las tareas y laboratorios del curso **Fundamentos de Gestión de Datos** en **TECSUP**.

---

## 👤 Información del Estudiante

- **Estudiante:** Erick Pariona Yauricasa
- **Código:** 1421035
- **Sección:** C24-A
- **Institución:** TECSUP
- **Curso:** Fundamentos de Gestión de Datos
- **Periodo:** 2026-II
- **Docente:** Pilar Rocío Sayán Mejía
- **Enlace del Repositorio:** [https://github.com/erickparionayauricasa6/TECSUP_FUNDAMENTOS_GESTION_DATOS](https://github.com/erickparionayauricasa6/TECSUP_FUNDAMENTOS_GESTION_DATOS)

---

## 📁 Detalle de Tareas y Laboratorios

A continuación se describen los laboratorios desarrollados en este repositorio:

### 🔹 [Semana 02] Laboratorio Dirigido N.° 02: Consultas SQLite para Toma de Decisiones

- **Archivo Notebook:** [`LAB-D2-FGD-2026II-PARIONA_YAURICASA_ERICK.ipynb`](./LAB-D2-FGD-2026II-PARIONA_YAURICASA_ERICK.ipynb)
- **Tema:** Consultas SQL con SQLite para responder preguntas de negocio sobre retail.
- **Caso de Estudio:** *TecnoAndina Retail*
- **Contenido y Ejercicios:**
  1. **Actividad 1 - Revisión de conceptos:** Principios de bases de datos relacionales y sintaxis fundamental de SQL.
  2. **Actividad 2 - Desarrollo práctico y ejecución:**
     - **A. Explorar y filtrar:** Ejercicios 1 al 4 (estructura, tipos, filtros por sede y operadores lógicos).
     - **B. Ordenar, limitar y distinguir:** Ejercicios 5 al 7 (`ORDER BY`, `LIMIT`, canal Web y `DISTINCT`).
     - **C. Resumir para decidir:** Ejercicios 8 al 10 (conteo, sumatorias y métricas agregadas).
  3. **Actividad 3 - Informe analítico comparado:** Tablas y análisis comparativo entre sedes y canales.
  4. **Retos de aplicación y retroalimentación:** Retos 1 al 3 (tickets de cómputo, accesorios web y celulares vs. accesorios).
  5. **Conclusiones:** Conclusiones técnicas de rendimiento y recomendaciones de negocio.

---

### 🔹 [Semana 03] Laboratorio Dirigido N.° 03: Joins, Agrupaciones, Subconsultas y Vistas

- **Archivo Notebook:** [`LAB-D3-FGD-2026II-PARIONA_YAURICASA_ERICK.ipynb`](./LAB-D3-FGD-2026II-PARIONA_YAURICASA_ERICK.ipynb)
- **Tema:** Relaciones avanzadas entre tablas, agregaciones complejas y reutilización de resultados en SQLite.
- **Caso de Estudio:** *TecnoAndina Retail*
- **Contenido y Ejercicios:**
  1. **A. Relacionar tablas (Joins):** `INNER JOIN`, `LEFT JOIN`, `RIGHT JOIN` y `FULL OUTER JOIN`.
  2. **B. Agrupar y filtrar grupos:** Filtrado a nivel de fila (`WHERE`) vs. a nivel de agregación (`GROUP BY` y `HAVING`).
  3. **C. Consultar y reutilizar resultados:** Subconsultas y vistas (`CREATE VIEW`) para resúmenes de clientes.
  4. **Actividad 3 - Informe analítico comparado:** Ranking de clientes por facturación.
  5. **Retos de aplicación y retroalimentación:** Retos 1 al 3 (clientes sin pedidos, ingresos con umbral y gasto sobre la media).
  6. **Conclusiones:** Reflexiones sobre normalización y optimización de consultas SQL.

---

### 🔹 [Semana 06] Laboratorio Dirigido N.° 06: Regresión Lineal y Preparación de Datos con scikit-learn

- **Archivo Notebook:** [`LAB-D6-FGD-2026II-PARIONA_YAURICASA_ERICK.ipynb`](./LAB-D6-FGD-2026II-PARIONA_YAURICASA_ERICK.ipynb)
- **Tema:** Limpieza de datos en SQLite, diagnóstico de calidad, partición 80/20 y modelos de regresión lineal simple y múltiple.
- **Caso de Estudio:** *AutoFlota Andina* (Dataset Auto MPG de UCI).
- **Contenido y Ejercicios:**
  1. **Actividad 1 - Revisión de conceptos:** Calidad de datos, imputación por mediana, valores atípicos (regla del IQR), partición train/test y métricas R², MAE, MSE y RMSE.
  2. **Actividad 2 - Desarrollo práctico y ejecución:**
     - **A. Diagnóstico y limpieza:** Tratamiento de faltantes en potencia e inconsistencias en origen y año en SQLite.
     - **B. Regresión lineal simple y múltiple:** Ajuste con `scikit-learn` y evaluación de pendientes e intercepto.
     - **C. Evaluación de métricas:** Comparación de residuos y capacidad predictiva.
  3. **Actividad 3 - Predicción para la flota:** Estimación de consumo para vehículos candidatos de compra.
  4. **Retos de aplicación y retroalimentación:** Retos 1 al 3 (predictores individuales, combinaciones multivariadas e impacto de imputar vs. eliminar).
  5. **Conclusiones:** Hallazgos predictivos y recomendaciones operativas de combustible.

---

### 🔹 [Semana 07] Laboratorio Dirigido N.° 07: Aprendizaje No Supervisado: Clustering con K-Means

- **Archivo Notebook:** [`LAB-D7-FGD-2026II-PARIONA_YAURICASA_ERICK.ipynb`](./LAB-D7-FGD-2026II-PARIONA_YAURICASA_ERICK.ipynb)
- **Tema:** Segmentación de vehículos con K-Means, método del codo, análisis de siluetas, perfiles de negocio y registro en SQLite.
- **Caso de Estudio:** *AutoFlota Andina* (Dataset Auto MPG de UCI).
- **Contenido y Ejercicios:**
  1. **Actividad 1 - Revisión de conceptos:** Aprendizaje no supervisado vs. supervisado, escalado con `StandardScaler`, centroides, inercia (WCSS), coeficiente de silueta y fases de CRISP-DM.
  2. **Actividad 2 - Desarrollo práctico y ejecución:**
     - **A. Preparar variables y ajustar K-Means:** Estandarización de peso, potencia, aceleración y mpg.
     - **B. Elegir k e interpretar segmentos:** Curva del codo, siluetas (k=2 a 8), visualización 2D/3D con centroides.
     - **C. Registrar segmentos en SQLite:** Persistencia de la columna `nombre_segmento` en la tabla `autos_limpio`.
  3. **Actividad 3 - Usar los segmentos en la decisión:** Asignación de candidatos de compra a perfiles operativos (Livianos/eficientes, Intermedios, Pesados/potentes).
  4. **Retos de aplicación y retroalimentación:**
     - **Reto 1:** Consecuencias de no escalar variables (falsa silueta alta de 0.592).
     - **Reto 2:** Comparativa k=3 vs. k=4 y principio de parsimonia.
     - **Reto 3:** Estabilidad de conglomerados y evaluación de concordancia con ARI (ARI = 1.0).
  5. **Conclusiones:** Tres conclusiones metodológicas, técnicas y de despliegue operacional.

---

## 🛠️ Tecnologías y Herramientas Utilizadas

- **Lenguaje:** Python 3.x
- **Librerías:** pandas, numpy, scikit-learn, matplotlib, seaborn, sqlite3
- **Gestor de Base de Datos:** SQLite
- **Entorno de Ejecución:** Jupyter Notebook / Visual Studio Code / Google Colab
- **Control de Versiones:** Git & GitHub

---

## 🚀 Instrucciones para Ejecutar Localmente

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/erickparionayauricasa6/TECSUP_FUNDAMENTOS_GESTION_DATOS.git
   cd TECSUP_FUNDAMENTOS_GESTION_DATOS
   ```

2. **Instalar dependencias necesarias:**
   ```bash
   pip install notebook pandas numpy scikit-learn matplotlib seaborn
   ```

3. **Iniciar Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

4. Abrir y ejecutar las celdas de forma secuencial en cualquiera de los cuadernos desarrollados.
