# Conversor de Moneda

Este proyecto es una aplicación de escritorio en Java que permite convertir dólares estadounidenses a varias otras monedas. Utiliza la API de ExchangeRate-API para obtener las tasas de cambio actuales.

## Estructura del Proyecto

El proyecto está organizado en los siguientes paquetes y clases:

### Paquete `modelos`

- **ExchangeRateResponse**: Clase que mapea la respuesta JSON de la API de ExchangeRate-API.
- **ExchangeRateConversion**: Clase que extrae el valor de la clave `result` del objeto `ExchangeRateResponse`.
- **SolicitudHTTP**: Clase que maneja la solicitud HTTP a la API y deserializa la respuesta JSON.
- **VerificarInteger**: Clase que verifica si una cadena de texto es un número entero.
- **FrameMenu**: Clase que crea y muestra el menú principal de la aplicación.
- **FrameDinero**: Clase que crea y muestra la interfaz para ingresar la cantidad de dólares a convertir.

### Paquete `main`

- **Main**: Clase principal que inicia la aplicación.

## Uso

### Requisitos

- Java 8 o superior
- Conexión a Internet

### Ejecución

1. Clona el repositorio en tu máquina local.
2. Abre el proyecto en tu IDE favorito (por ejemplo, IntelliJ IDEA).
3. Ejecuta la clase `Main` para iniciar la aplicación.

### Funcionalidades

- **Menú Principal**: Permite seleccionar la moneda a la que se desea convertir dólares.
- **Conversión de Moneda**: Permite ingresar una cantidad de dólares y muestra la cantidad equivalente en la moneda seleccionada.
- **Salir**: Permite cerrar la aplicación.

### Ejemplo de Uso

1. Ejecuta la aplicación.
2. Selecciona una opción del menú para convertir dólares a una moneda específica.
3. Ingresa la cantidad de dólares a convertir.
4. La aplicación mostrará la cantidad equivalente en la moneda seleccionada.


Este `README.md` proporciona una descripción general del proyecto, su estructura, cómo usarlo y ejemplos de código. Puedes ajustarlo según tus necesidades específicas.
