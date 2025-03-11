# Accesibilidad

---
## 📷 Capturas de Pantalla mala accesibilidad
| Ejemplo 1 | Ejemplo 2 |
|----------------------|------------------|
| ![Formulario de contacto](./ejemplo1MAL/ejemplo1.png) | ![Lista de productos](./ejemplo2MAL/ejemplo2.png) |

---

## 📝 Código con Problemas de Accesibilidad

| Formulario de Contacto | Lista de Productos |
|----------------------|------------------|
| ```html<br>&lt;!DOCTYPE html&gt;<br>&lt;html lang="es"&gt;<br>&lt;head&gt;<br>&lt;meta charset="UTF-8"&gt;<br>&lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt;<br>&lt;title&gt;Formulario de Contacto&lt;/title&gt;<br>&lt;link rel="stylesheet" href="style.css"&gt;<br>&lt;/head&gt;<br>&lt;body&gt;<br><br>&lt;div class="header"&gt;<br>&lt;h3&gt;Bienvenido&lt;/h3&gt;<br>&lt;/div&gt;<br><br>&lt;nav&gt;<br>&lt;a href="#"&gt;Inicio&lt;/a&gt;<br>&lt;a href="#"&gt;Nosotros&lt;/a&gt;<br>&lt;a href="#"&gt;Contacto&lt;/a&gt;<br>&lt;/nav&gt;<br><br>&lt;div class="content"&gt;<br>&lt;h2&gt;Formulario de Contacto&lt;/h2&gt;<br>&lt;form&gt;<br>&lt;div&gt;&lt;input type="text" placeholder="Nombre"&gt;&lt;/div&gt;<br>&lt;div&gt;&lt;input type="email" placeholder="Correo"&gt;&lt;/div&gt;<br>&lt;div&gt;&lt;textarea placeholder="Mensaje"&gt;&lt;/textarea&gt;&lt;/div&gt;<br>&lt;button&gt;Enviar&lt;/button&gt;<br>&lt;/form&gt;<br>&lt;/div&gt;<br><br>&lt;footer&gt;<br>&lt;p&gt;© 2025 Todos los derechos reservados&lt;/p&gt;<br>&lt;/footer&gt;<br><br>&lt;/body&gt;<br>&lt;/html&gt;``` | ```html<br>&lt;!DOCTYPE html&gt;<br>&lt;html lang="es"&gt;<br>&lt;head&gt;<br>&lt;meta charset="UTF-8"&gt;<br>&lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt;<br>&lt;title&gt;Lista de Productos&lt;/title&gt;<br>&lt;link rel="stylesheet" href="style.css"&gt;<br>&lt;/head&gt;<br>&lt;body&gt;<br><br>&lt;header&gt;<br>&lt;h2&gt;Nuestros Productos&lt;/h2&gt;<br>&lt;/header&gt;<br><br>&lt;table&gt;<br>&lt;tr&gt;<br>&lt;td&gt;Producto&lt;/td&gt;<br>&lt;td&gt;Precio&lt;/td&gt;<br>&lt;td&gt;Acción&lt;/td&gt;<br>&lt;/tr&gt;<br>&lt;tr&gt;<br>&lt;td&gt;Computadora&lt;/td&gt;<br>&lt;td&gt;$800&lt;/td&gt;<br>&lt;td&gt;&lt;button&gt;Comprar&lt;/button&gt;&lt;/td&gt;<br>&lt;/tr&gt;<br>&lt;tr&gt;<br>&lt;td&gt;Teléfono&lt;/td&gt;<br>&lt;td&gt;$400&lt;/td&gt;<br>&lt;td&gt;&lt;button&gt;Comprar&lt;/button&gt;&lt;/td&gt;<br>&lt;/tr&gt;<br>&lt;/table&gt;<br><br>&lt;footer&gt;<br>&lt;p&gt;Derechos Reservados &copy; 2025&lt;/p&gt;<br>&lt;/footer&gt;<br><br>&lt;/body&gt;<br>&lt;/html&gt;``` |

