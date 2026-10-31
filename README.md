# Portfolio · Sara Valero Maza

Portfolio personal de **Sara Valero Maza**, Técnica Superior en Desarrollo de Aplicaciones Web (DAW) y desarrolladora web fullstack en Almería, disponible para prácticas.

🔗 **Ver en vivo:** [saravaleromaza.github.io/portfolio](https://saravaleromaza.github.io/portfolio/)

## ✨ Características

- **Una página principal** con cuatro secciones: Sobre mí, Proyectos, Habilidades y Contacto.
- **Una página de detalle por proyecto**: qué hace, qué aprendí, cómo ejecutarlo y galería de capturas con visor ampliado.
- **Modo claro y oscuro**: respeta la preferencia del sistema y se puede cambiar con un interruptor.
- **Diseño responsive**, pensado primero para móvil y adaptado a tablet y escritorio.
- **Tarjeta de contacto** que se voltea y muestra el correo con un botón para escribir.
- **Animaciones suaves** al hacer scroll, que se desactivan si el usuario prefiere menos movimiento.
- **Accesibilidad**: enlace "Saltar al contenido", HTML semántico, buen contraste, navegación con teclado y textos descriptivos para lectores de pantalla.

## 🧩 Un portfolio sin JavaScript

Quise que todo funcionara solo con **HTML5 y CSS3**, para practicar lo que CSS ya puede hacer por sí solo:

| Funcionalidad | Técnica |
|---|---|
| Modo claro / oscuro | Checkbox oculto + `:has()` + `prefers-color-scheme` |
| Tarjeta de email con giro | Selector `:target` + `transform: rotateY()` |
| Visor de capturas | Selector `:target` sobre cada imagen |
| Aparición al hacer scroll | `animation-timeline: view()` dentro de `@supports` |
| Tarjeta de proyecto clicable | Pseudo-elemento `::after` que cubre toda la tarjeta |
| Imágenes de vista previa | Variables CSS (`--preview`, `--shot`) |
| Menos movimiento | `@media (prefers-reduced-motion)` |

## 🛠️ Tecnologías

- HTML5 semántico
- CSS3: variables, Grid, Flexbox, `clamp()`, `:has()`, `:target`
- Git y GitHub para el control de versiones, usados desde la consola
- GitHub Pages para el despliegue

## 📁 Estructura

```text
portfolio/
├── index.html                  # Página principal
├── styles.css                  # Estilos de todo el sitio
├── biblioteca-java.html        # Páginas de detalle de cada proyecto
├── formulario-php.html
├── el-sabor-de-la-abuela.html
├── gestor-de-tareas.html
├── servidor-apache.html
├── img-proyectos/              # Capturas de los proyectos
├── favicon/                    # Iconos del sitio
└── README.md
```

## 🚀 Ejecutarlo en local

No necesita instalación ni dependencias.

```bash
git clone https://github.com/saravaleromaza/portfolio.git
cd portfolio
```

Después, abre `index.html` en el navegador o, si usas VS Code, sírvelo con la extensión **Live Server** (clic derecho en `index.html` → *Open with Live Server*).

## 🌐 Despliegue

El sitio se publica con **GitHub Pages** desde la rama `main` (carpeta raíz). Cada `git push` actualiza la web en uno o dos minutos.

```bash
git add .
git commit -m "Describe el cambio"
git push
```

> Las rutas en GitHub Pages distinguen mayúsculas de minúsculas, así que los nombres de archivo van en minúsculas y sin espacios ni `ñ`.

## 📂 Proyectos destacados

| Proyecto | Tecnologías |
|---|---|
| [biblioteca-java](https://github.com/saravaleromaza/biblioteca-java) | Java |
| [formulario-php](https://github.com/saravaleromaza/formulario-php) | PHP, HTML |
| [el-sabor-de-la-abuela](https://github.com/saravaleromaza/el-sabor-de-la-abuela) | HTML, CSS |
| [gestor-de-tareas](https://github.com/saravaleromaza/to-do-CLI) | JavaScript |
| Servidor web con Apache | Apache, Ubuntu Server, HTML |

## 📬 Contacto

- 💼 [LinkedIn](https://www.linkedin.com/in/saravaleromaza)
- 🐙 [GitHub](https://github.com/saravaleromaza)

---

© 2026 Sara Valero Maza