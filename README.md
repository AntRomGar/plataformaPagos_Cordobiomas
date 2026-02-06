# Plataforma de Pago Simulada

> [!IMPORTANT]
> Este proyecto **no es un sistema de pago real**. No utiliza pasarelas oficiales, no recopila ni almacena datos personales ni bancarios, y su uso es exclusivamente educativo y demostrativo.



## Descripción general

Esta plataforma simula un flujo completo de pago online con fines educativos:

- Selección de un producto
- Elección de método de pago simulado
- Simulación de pago exitoso o fallido
- Generación de credenciales de acceso ficticias

> [!NOTE]
> Todo el proyecto funciona completamente en el lado del cliente, sin bases de datos ni APIs de pago reales.

---

## Tecnologías utilizadas

- HTML5
- CSS3
- JavaScript (Vanilla JS)

---

## Estructura del proyecto
<br>
/ </br>
├── index.html # Página principal y selección del método de pago </br>
├── payment.html # Simulación de pasarela de pago </br>
├── credenciales.html # Generación de credenciales ficticias </br>
└── src/ </br>
└── assets # Imágenes e iconos utilizados en la interfaz </br>
</br>
</br>

---

## Funcionamiento de la plataforma

### 1. Página principal (`index.html`)

- Muestra un producto simulado con precio.
- Al pulsar **PAGAR**, se abre un modal para elegir método de pago:
  - PayPal (simulación visual)
  - Bizum (simulación visual)
- La selección redirige a `payment.html` con parámetros en la URL: método, producto e importe.

---

### 2. Pasarela de pago simulada (`payment.html`)

#### PayPal
- Interfaz simplificada con confirmación de pago.

#### Bizum
- Interfaz visual inspirada en la pasarela real.
- Introducción de teléfono ficticio.
- Cuenta atrás simulando validación bancaria.
- Resultado del pago aleatorio (éxito o error).
- Reintento disponible en caso de error.

> [!WARNING]
> No se realizan transacciones reales. Todo es una simulación visual y funcional.

---

### 3. Generación de credenciales (`credenciales.html`)

- Se generan credenciales aleatorias (usuario y contraseña).
- Solo existen en la sesión del navegador y no se almacenan ni envían a servidores.

> [!NOTE]
> Esto simula el acceso posterior a una plataforma privada de forma educativa.

---

## Seguridad y privacidad

> [!IMPORTANT]
> Medidas implementadas:
> - No se recopilan datos personales
> - No se almacenan contraseñas
> - No se procesan datos bancarios
> - No se usan cookies
> - Funcionamiento 100% en el lado del cliente

> [!CAUTION]
> Limitaciones: no cumple funciones comerciales ni financieras reales.

---

## Alojamiento

> [!WARNING]
> Inicialmente se utilizó hosting público, pero por restricciones de TOS fue necesario moverlo a un dominio propio.

- Subdominio del proyecto: (retirada de github para mantener privacidad)
- Copia archivada (Internet Archive – Wayback Machine): [https://web.archive.org/web/20260206002650/](https://web.archive.org/web/20260206002650/https://cordobiomas.antoniorg.es/)

---

## Licencia y uso

> [!NOTE]
> Este proyecto **no cuenta con licencia de software explícita**.  
> Todo el contenido está protegido por derechos de autor.  
> Uso permitido únicamente con fines educativos.  
> No se permite modificación, redistribución o explotación comercial sin consentimiento expreso del autor.

---

## Autor

- Proyecto desarrollado por **Antonio** como parte de un **Grado Superior**.

---

## Estado del proyecto

- Finalizado
- Uso exclusivamente académico
- Entorno de simulación
