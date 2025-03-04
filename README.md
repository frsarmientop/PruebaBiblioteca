# Test MS Library

## Problema

Una biblioteca pública necesita un sistema que le permita registrar todos los libros disponibles en su colección y calcular el costo de adquirir múltiples copias de un título específico. Para esto, se requiere una API REST que almacene esta información y facilite la consulta de los libros.

### Descripción

Se solicita crear una API REST basada en la definición que se encuentra en el archivo:
[api.yaml](https://github.com/frsarmientop/PruebaBiblioteca/blob/main/api.yaml)

#### Funcionalidad

- GET /books: Lista todos los libros disponibles en el sistema.
- POST /books/{bookID}: Muestra el detalle de un libro específico, incluyendo su disponibilidad y detalles de la edición.
- GET /books/{bookID}/boxprice: Calcula el costo de adquirir múltiples copias de un libro para la biblioteca, multiplicando el precio unitario por la cantidad especificada y ajustando la moneda según la tasa de cambio. Parámetros a usar:
    - Quantity: Cantidad de copias a comprar (valor por defecto: 6).
    - Currency: Moneda en la que se desea pagar. Para la conversión de moneda, se recomienda utilizar la API: https://currencylayer.com.

### Requisitos

- El lenguaje de programación debe ser Go.
- Usar Docker y Docker Compose para los diferentes servicios.
- Se pueden utilizar librerías externas y frameworks.
- Se requiere al menos un 70% de cobertura de código en los tests.
- Se tiene completa libertad para agregar nuevas funcionalidades.

### Entrega

- Enviar el link del repositorio donde se realiza este ejercicio.

¡Éxitos! 📚🚀
