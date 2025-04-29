# 📊 Proyecto Final SQL - IMDb Análisis de Películas y Directores

Este proyecto es una práctica final de SQL enfocada en el análisis de una base de datos basada en IMDb (Internet Movie Database). Utiliza Python y SQLite para realizar consultas complejas sobre películas y directores.

## 🗂️ Estructura del Proyecto

- **Base de Datos**  
  Archivo `movies.sqlite` (descargable desde este repositorio llamado movies.sqlite)

- **Código**  
  Archivo `.ipynb` o `.py` con las consultas SQL y procesamiento en Python.

- **Tablas utilizadas**
  - `movies`: contiene información de películas como título, presupuesto, ingresos, etc.
  - `directors`: contiene datos de los directores como nombre, género, ID, etc.

## ⚙️ Requisitos

- Python 3.x
- Bibliotecas necesarias:

```bash
pip install pandas numpy seaborn
````

## 🚀 Cómo ejecutarlo

1. Clona este repositorio:

```bash
git clone [https://github.com/IRoma88/SQL_Peliculas.git]
cd SQL_Peliculas.git
````

2. Instala las dependencias necesarias:
```bash
pip install pandas numpy seaborn
````

3. Ejecuta el notebook en Jupyter o Google Colab:
  - En Jupyter Notebook:

     - Abre el archivo .ipynb desde tu entorno Jupyter.

     - Asegúrate de que el archivo movies.sqlite esté en el mismo directorio.

     - Ejecuta las celdas en orden.
       
  - En Google Colab:

     - Sube el archivo movies.sqlite cuando el entorno lo solicite.

     - Ejecuta cada celda paso a paso.
   
  ## 📌 Consultas Incluidas
Mostrar todas las películas.

Consultar todos los directores.

Contar películas totales, directoras y directores por género.

Buscar directores por nombre o patrón.

Ordenar películas por popularidad o presupuesto.

Encontrar las películas con mejor puntuación posterior al año 2000.

Relacionar películas con sus directores.

Identificar al director con más películas y mayor financiamiento total.

## ✅ Verificación Automática
Cada ejercicio incluye una función check() que evalúa si el resultado es correcto. Al final del proyecto, se valida todo con un hash único que te permite verificar si el trabajo fue realizado correctamente.

## 🏁 Resultado
Si todo está correctamente implementado, recibirás un mensaje de felicitación con un token SHA-256 que confirma que puedes pasar al siguiente módulo del curso.

## 📄 Licencia
Este proyecto es solo para fines educativos y de práctica personal.
IMDb es una marca registrada; esta base de datos se utiliza únicamente con fines de aprendizaje.

