# 🧼 ETL: Limpieza y Normalización de Correos / Email Cleaning and Normalization

Este script permite limpiar y normalizar correos electrónicos en bases de datos. Ideal para profesionales en CRM, marketing y abastecimiento.

This script helps clean and normalize email addresses in databases. Perfect for CRM, marketing, and sourcing professionals.

## ✨ Beneficios / Benefits

- ⏳ **Ahorra tiempo / Saves time:** Automatiza la depuración de correos inválidos / Automates email cleanup  
- 🚫 **Evita errores / Prevents errors:** Mejora campañas de email y sistemas CRM / Improves email campaigns and CRM systems  
- 🖱️ **Fácil de usar / Easy to use:** Solo necesitas Python con `pandas` / Just needs Python and `pandas` installed

## ⚙️ Cómo usarlo / How to use it

1. Clona o descarga este repositorio / Clone or download this repository  
2. Instala Python y `pandas` / Install Python and `pandas`  
3. Ejecuta el script y proporciona la ruta de tu archivo CSV / Run the script and provide the path to your CSV file  
4. El archivo debe tener las columnas `RUT`, `NOMBRE` y `CORREO` / Your file must contain `RUT`, `NAME`, and `EMAIL` columns  
5. Obtendrás un archivo Excel limpio / You'll get a clean Excel file ready to use  

## 📂 Entrada / Entrada

- **Entrada / Input:** CSV con `RUT`, `NOMBRE`, `CORREO` (`;` como separador, codificación `latin1`)  
- **Salida / Output:** Excel con sufijo `_LIMPIO.xlsx` / Excel file with `_CLEAN.xlsx` suffix

## 🧠 ¿Qué hace el script? / What does the script do?

- Elimina correos inválidos como “sincorreo” / Removes invalid entries like “noemail”  
- Corrige múltiples signos `@` / Fixes multiple `@` signs  
- Normaliza dominios (`gmail.com`, `outlook.com`, etc.) / Normalizes domains (`gmail.com`, `outlook.com`, etc.)  
- Elimina duplicados por `RUT` / Removes duplicates based on `RUT`

## 🤝 Contribuye / Contribute

Este recurso es abierto para mejorar la calidad de tus datos.  
This is an open resource to help improve data quality.

- Si te sirve, compártelo / If you find it useful, share it  
- ¿Mejoras? Abre un *issue* o haz un *pull request* / Got improvements? Open an *issue* or submit a *pull request*
