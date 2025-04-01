Web Scraping de Books to Scrape

Este proyecto realiza web scraping en el sitio [Books to Scrape](https://books.toscrape.com/) utilizando Python y la biblioteca **BeautifulSoup**.  
El script extrae títulos de libros con una calificación de **4 o 5 estrellas** y los muestra en la consola.

Tecnologías utilizadas

- Python 3  
- BeautifulSoup  
- Requests
- lxml

 Instalación y uso

1 Clonar el repositorio

```bash
git clone https://github.com/kuota1/primer-scraping.git

2 Crear y activar un entorno virtual (opcional pero recomendado)
bash
Copiar
Editar
python -m venv venv
source venv/bin/activate  # En macOS/Linux
venv\Scripts\activate  # En Windows
3 Instalar las dependencias
bash
Copiar
Editar
pip install -r requirements.txt
4 Ejecutar el script
bash
Copiar
Editar
python scraping_books.py
¿Qué hace este script?
Visita todas las páginas del catálogo de Books to Scrape (50 páginas en total).

Filtra los libros con calificación de 4 o 5 estrellas.

Extrae los títulos y los imprime en la consola.

