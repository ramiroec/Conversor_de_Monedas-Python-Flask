
# Conversor de Monedas - Python Flask

Este es un proyecto de un conversor de monedas creado utilizando Flask para el backend y HTML, CSS y JavaScript para el frontend. 
Permite convertir diferentes monedas en tiempo real utilizando la API de [ExchangeRate-API](https://www.exchangerate-api.com).

## Autor

**Ramiro Estigarribia Canese**  
GitHub: [ramiroec](https://github.com/ramiroec/Conversor_de_Monedas-Python-Flask)

## Características

- Conversión en tiempo real entre diversas monedas
- Interfaz de usuario sencilla y estilizada
- API de tasas de cambio actualizada automáticamente

## Estructura del Proyecto

```
currency_converter/
│
├── static/
│   ├── styles.css
│
├── templates/
│   ├── index.html
│
├── app.py
├── requirements.txt
└── README.md
```

## Instalación

1. Clona este repositorio en tu máquina local:
    ```
    git clone https://github.com/ramiroec/Conversor_de_Monedas-Python-Flask.git
    ```

2. Navega al directorio del proyecto:
    ```
    cd Conversor_de_Monedas-Python-Flask
    ```

3. Crea un entorno virtual (opcional pero recomendado):
    ```
    python -m venv venv
    source venv/bin/activate  # En Windows usa `venv\Scripts\activate`
    ```

4. Instala las dependencias:
    ```
    pip install -r requirements.txt
    ```

5. Ejecuta la aplicación:
    ```
    python app.py
    ```

6. Abre tu navegador y ve a `http://127.0.0.1:5000/` para acceder a la aplicación.

## API Utilizada

Este proyecto utiliza la API gratuita de [ExchangeRate-API](https://www.exchangerate-api.com). Necesitarás una clave de API para realizar las conversiones de moneda. Puedes reemplazar la clave de API en `app.py` por tu propia clave obtenida en la página de ExchangeRate-API.

```python
API_KEY = 'TU_CLAVE_API'
```

## Contribuciones

¡Las contribuciones son bienvenidas! Si tienes sugerencias, mejoras o encuentras algún error, siéntete libre de abrir un issue o enviar un pull request.

## Licencia

Este proyecto está bajo la licencia MIT.
