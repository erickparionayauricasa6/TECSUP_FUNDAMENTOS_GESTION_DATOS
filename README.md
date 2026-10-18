# TECSUP - Fundamentos de Gestión de Datos (2026-II)

Repositorio oficial para el almacenamiento, seguimiento y entrega de las tareas y laboratorios del curso **Fundamentos de Gestión de Datos** en **TECSUP**.

---

## 👤 Información del Estudiante

- **Estudiante:** Erick Pariona Yauricasa
- **Institución:** TECSUP
- **Curso:** Fundamentos de Gestión de Datos
- **Periodo:** 2026-II
- **Enlace del Repositorio:** [https://github.com/erickparionayauricasa6/TECSUP_FUNDAMENTOS_GESTION_DATOS](https://github.com/erickparionayauricasa6/TECSUP_FUNDAMENTOS_GESTION_DATOS)

---

## 📁 Detalle de Tareas y Laboratorios

A continuación se describen los laboratorios y retos desarrollados en este repositorio:

### 🔹 [Semana 02] Laboratorio Dirigido N.° 02: Consultas SQLite para Toma de Decisiones

- **Archivo Notebook:** [`LAB-D2-FGD-2026II-PARIONA_YAURICASA_ERICK.ipynb`](./LAB-D2-FGD-2026II-PARIONA_YAURICASA_ERICK.ipynb)
- **Enlace GitHub:** [Ver Laboratorio 02 en GitHub](https://github.com/erickparionayauricasa6/TECSUP_FUNDAMENTOS_GESTION_DATOS/blob/main/LAB-D2-FGD-2026II-PARIONA_YAURICASA_ERICK.ipynb)
- **Tema:** Consultas SQL con SQLite para responder preguntas de negocio sobre retail.
- **Caso de Estudio:** *TecnoAndina Retail*
- **Contenido y Ejercicios:**
  1. **Actividad 1 - Revisión de conceptos:** Principios de bases de datos relacionales y sintaxis fundamental de SQL.
  2. **Actividad 2 - Desarrollo práctico y ejecución:**
     - **A. Explorar y filtrar:**
       - Ejercicio 1: Reconocimiento de la estructura y tipos de datos de las tablas.
       - Ejercicio 2: Identificación de ventas de alto valor por sede.
       - Ejercicio 3: Filtros de ventas relevantes aplicados a sedes específicas (Piura).
       - Ejercicio 4: Uso de operadores lógicos `OR`, `AND` y `NOT` para exclusiones y alternativas.
     - **B. Ordenar, limitar y distinguir:**
       - Ejercicio 5: Clasificación de registros más altos y más bajos con `ORDER BY` y `LIMIT`.
       - Ejercicio 6: Análisis de las tres mayores ventas generadas por el canal Web.
       - Ejercicio 7: Extracción de valores únicos con `DISTINCT`.
     - **C. Resumir para decidir:**
       - Ejercicio 8: Conteo y acumulados totales (`COUNT`, `SUM`) para la sede Lima.
       - Ejercicio 9: Métricas agregadas de la cadena comercial (`AVG`, `MAX`, `MIN`).
       - Ejercicio 10: Resumen estadístico enfocado en la sede Piura.
  3. **Actividad 3 - Informe analítico comparado:** Tablas y análisis comparativo de rendimiento entre sedes y canales de venta.
  4. **Retos de aplicación y retroalimentación:**
     - **Reto 1:** Detección de los tickets más altos de la categoría Cómputo en la sede Trujillo.
     - **Reto 2:** Volumen y montos de accesorios vendidos exclusivamente por el canal Web.
     - **Reto 3:** Análisis comparativo de ingresos: Celulares frente a Accesorios.
  5. **Conclusiones:** Conclusiones técnicas de rendimiento y recomendaciones de negocio para la toma de decisiones.

---

### 🔹 [Semana 03] Laboratorio Dirigido N.° 03: Joins, Agrupaciones, Subconsultas y Vistas

- **Archivo Notebook:** [`LAB-D3-FGD-2026II-PARIONA_YAURICASA_ERICK.ipynb`](./LAB-D3-FGD-2026II-PARIONA_YAURICASA_ERICK.ipynb)
- **Enlace GitHub:** [Ver Laboratorio 03 en GitHub](https://github.com/erickparionayauricasa6/TECSUP_FUNDAMENTOS_GESTION_DATOS/blob/main/LAB-D3-FGD-2026II-PARIONA_YAURICASA_ERICK.ipynb)
- **Tema:** Relaciones avanzadas entre tablas, agregaciones complejas y reutilización de resultados en SQLite.
- **Caso de Estudio:** *TecnoAndina Retail*
- **Contenido y Ejercicios:**
  1. **A. Relacionar tablas (Joins):**
     - Ejercicio 1: Combinación con `INNER JOIN` y `LEFT JOIN` para identificar clientes con y sin pedidos registrados.
     - Ejercicio 2: Implementación conceptual y práctica de `RIGHT JOIN` y `FULL OUTER JOIN`.
  2. **B. Agrupar y filtrar grupos:**
     - Ejercicio 3: Diferenciación práctica entre filtrado a nivel de fila (`WHERE`) y filtrado a nivel de agregación (`GROUP BY` y `HAVING`).
  3. **C. Consultar y reutilizar resultados:**
     - Ejercicio 4: Uso de subconsultas (subqueries) para identificar pedidos que superan el promedio global por pedido.
     - Ejercicio 5: Creación de vistas (`CREATE VIEW`) para almacenar y reutilizar el resumen de compras por cliente.
  4. **Actividad 3 - Informe analítico comparado:**
     - Identificación y ranking de clientes con mayor monto acumulado de facturación.
  5. **Retos de aplicación y retroalimentación:**
     - **Reto 1:** Segmentación de clientes sin pedidos agrupados por ciudad.
     - **Reto 2:** Cálculo de ingresos totales por categoría aplicando umbrales mínimos mediante cláusula `HAVING`.
     - **Reto 3:** Filtrado de clientes cuyo gasto promedio supere la media general de los clientes.
  6. **Conclusiones:** Conclusiones técnicas sobre normalización y optimización de consultas SQL, junto a reflexiones orientadas a la inteligencia de negocios.

---

## 🛠️ Tecnologías y Herramientas Utilizadas

- **Lenguaje:** Python 3.x
- **Gestor de Base de Datos:** SQLite / `sqlite3`
- **Entorno de Ejecución:** Jupyter Notebook / Visual Studio Code / Google Colab
- **Control de Versiones:** Git & GitHub

---

## 🚀 Instrucciones para Ejecutar Localmente

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/erickparionayauricasa6/TECSUP_FUNDAMENTOS_GESTION_DATOS.git
   cd TECSUP_FUNDAMENTOS_GESTION_DATOS
   ```

2. **Instalar dependencias necesarias (en caso de usar entorno virtual):**
   ```bash
   pip install notebook pandas
   ```

3. **Iniciar Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

4. Abrir y ejecutar las celdas de forma secuencial en cualquiera de los notebooks:
   - `LAB-D2-FGD-2026II-PARIONA_YAURICASA_ERICK.ipynb`
   - `LAB-D3-FGD-2026II-PARIONA_YAURICASA_ERICK.ipynb`
