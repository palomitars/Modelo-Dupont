# Modelo DuPont - Streamlit App

Esta aplicación desarrollada en Python con Streamlit permite analizar la rentabilidad de negocios utilizando el **modelo DuPont** de forma automática, visual e interactiva.

## 📊 ¿Qué hace esta aplicación?

- Permite subir bases de datos en `.csv` o `.xlsx`
- Calcula los siguientes indicadores financieros por período:
  - **Margen Neto (%)**
  - **Rotación (veces)**
  - **Apalancamiento (veces)**
  - **ROE (%)**
  - **ROA (%)**
  - **Pay Back Capital (veces)**
  - **Pay Back Activos (veces)**
- Muestra el resultado en una tabla:
  - **Columnas = períodos**
  - **Renglones = conceptos**
  - **Valores relativos = 1 decimal con %**
  - **Valores absolutos = 1 decimal**
- Permite descargar el reporte en Excel
- Incluye plantilla base para facilitar el uso

## 📁 Estructura esperada del archivo cargado

El archivo debe incluir las siguientes columnas:

| Periodo | Ventas Netas | Utilidad Neta | Activos Totales | Capital Contable |
|---------|---------------|----------------|------------------|-------------------|
| 2021    | 1000000       | 80000          | 500000           | 250000            |

Puedes descargar una plantilla ejemplo desde la app.

## 🚀 Cómo desplegar esta app en Streamlit Cloud

1. Crea una cuenta en GitHub: https://github.com
2. Crea un nuevo repositorio (ej. `modelo-dupont-finanzas`)
3. Sube los siguientes archivos:
   - `app.py`
   - `requirements.txt`
   - `README.md`
4. Ve a: https://share.streamlit.io
5. Inicia sesión con tu cuenta de GitHub
6. Haz clic en **“New app”**
7. Selecciona:
   - Repositorio
   - Rama (`main` o `master`)
   - Archivo principal: `app.py`
8. Haz clic en **Deploy**

## 🧾 Requisitos (`requirements.txt`)

```txt
streamlit
pandas
numpy
xlsxwriter
```

---

Desarrollado para análisis financiero con fines educativos y profesionales.
