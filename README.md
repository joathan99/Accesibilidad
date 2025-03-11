# Accesibilidad

---
## 📷 Capturas de Pantalla mala accesibilidad
| Ejemplo 1 | Ejemplo 2 |
|----------------------|------------------|
| ![Formulario de contacto](ejemplop1.png) | ![Lista de productos](ejemplo2.png) |

---

## Ejemplo 1: Formulario de Contacto (Codigo con errores)
```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulario de Contacto</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="header"> <!-- Falta de semántica -->
        <h3>Bienvenido</h3> <!-- No debería ser un h3 sin un h1 antes -->
    </div>

    <nav> <!-- Mala visibilidad de enlaces -->
        <a href="#">Inicio</a>
        <a href="#">Nosotros</a>
        <a href="#">Contacto</a>
    </nav>

    <div class="content">
        <h2>Formulario de Contacto</h2>

        <form>
            <div>
                <input type="text" placeholder="Nombre"> <!-- No tiene label asociada -->
            </div>
            <div>
                <input type="email" placeholder="Correo"> <!-- No tiene label asociada -->
            </div>
            <div>
                <textarea placeholder="Mensaje"></textarea> <!-- No tiene label asociada -->
            </div>
            <button>Enviar</button> <!-- Falta descripción clara -->
        </form>
    </div>

    <footer>
        <p>© 2025 Todos los derechos reservados</p> <!-- Texto de bajo contraste -->
    </footer>

</body>
</html>
```
