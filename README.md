# Proyecto - Urban Routes🚗

### Descripción del Proyecto 📑

Urban Routes es una aplicación web diseñada para solicitar servicios de taxi con características adicionales, como la selección de tarifas, el envío de mensajes al conductor, y la solicitud de artículos adicionales como mantas, pañuelos y helados.

### Tecnologías y Técnicas Utilizadas 🤖

- **Python**: Utilizado para escribir las pruebas automatizadas.
- **Selenium**: Biblioteca de automatización para controlar el navegador web y realizar pruebas de interfaz de usuario.
- **WebDriver**: Controlador utilizado por Selenium para interactuar con diferentes navegadores.

### Instrucciones para Ejecutar las Pruebas 🛠️

1. **Instalar dependencias**: Asegúrate de tener Chrome, ChromeDriver, Python y Selenium instalados. Puedes instalar Selenium usando pip:
   ```sh
   pip install selenium
2. **Ejecuta las pruebas usando Pytest**:
   ```sh
   pytest main.py
   
### Entorno de Pruebas 🖥️

**Sistema Operativo:** Windows 11

**Navegador:** Google Chrome

**Resolución de Pantalla:** 1366 x 768
   
### Estructura del Proyecto 🗂️
- **main.py**: Contiene las definiciones de la página y las pruebas automatizadas.
- **data.py**: Archivo de datos que contiene valores como direcciones, número de teléfono y detalles de la tarjeta.
- **helpers.py**: Archivo de funciones de ayuda, incluyendo la función retrieve_phone_code().

### Funcionalidad Cubierta por las Pruebas 🧪
Las pruebas automatizadas cubren el siguiente flujo de trabajo:

**1.** Configurar la dirección de origen y destino.

**2.** Seleccionar la tarifa Comfort.

**3.** Rellenar el número de teléfono.

**4.** Agregar una tarjeta de crédito.

**5.** Escribir un mensaje para el conductor.

**6.** Solicitar una manta y pañuelos.

**7.** Pedir 2 helados.

**8.** Proceder a buscar un taxi y esperar a que aparezca la información del conductor (opcional).

### Contribuciones 🤝
¡Todas los aportes son bienvenidos! 
Si deseas contribuir al código y generar comunidad, por favor abre un issue o un pull request en GitHub 😎👌🔥