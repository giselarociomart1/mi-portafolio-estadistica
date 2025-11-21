# 📊 Análisis Estadístico Descriptivo y Probabilidades – Desafío 1  
**Autora:** Gisela Martínez  
---

## 📘 Descripción del proyecto  
Este trabajo forma parte de mi portafolio de estadística aplicada con Python.  
El objetivo es analizar un conjunto de datos salariales ficticio y aplicar conceptos de **estadística descriptiva y probabilidades** para comprender cómo varían los salarios según distintos factores laborales.

El dataset incluye información sobre:
- Año de pago del salario (`work_year`)
- Nivel de experiencia (`experience_level`)
- Tipo de empleo (`employment_type`)
- Puesto de trabajo (`job_title`)
- Salario (en moneda original y en USD)
- País del empleado
- Modalidad de trabajo remoto (`remote_ratio`)
- Tamaño de empresa (`company_size`)

---

## 🎯 Objetivos del análisis
- Realizar **medidas de tendencia central** (media, mediana, moda) por diferentes subgrupos.
- Calcular **medidas de dispersión** (rango, varianza, desvío estándar).
- Implementar **cuartiles**, **percentiles** y **rango intercuartílico (IQR)**.
- Comparar distribuciones salariales según:
  - Nivel de experiencia  
  - Tamaño de la empresa  
  - Modalidad de trabajo remoto  

---

## 🔍 Principales hallazgos

### 1️⃣ **Nivel de experiencia**
- A mayor seniority, mayor salario promedio.
- La diferencia entre categorías es clara y consistente.
- El grupo **EX (ejecutivo/director)** tiene la mayor media y mediana.

### 2️⃣ **Tamaño de empresa**
- Las empresas **L (large)** muestran salarios más altos y dispersos.
- Las empresas **S (small)** tienen salarios más bajos y más homogéneos.
- Las empresas **M (medium)** quedan en un punto medio, como era esperable.

### 3️⃣ **Modalidad de trabajo remoto**
- **Remoto 100%** → salarios más altos (especialmente en roles globales).  
- **Presencial (0%)** → mayor dispersión y más salarios bajos.  
- **Híbrido (50%)** → grupo más heterogéneo; las medidas centrales no lo describen bien.

📌 *Conclusión:* los salarios varían fuertemente según la modalidad laboral porque influyen factores como país, industria y mercado global, especialmente en trabajo remoto.

---

## 🧪 Tecnologías utilizadas
- **Python 3**
- **Pandas** (limpieza y manipulación de datos)
- **NumPy** (cálculos estadísticos)
- **Jupyter Notebook**