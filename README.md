# 🌐 Comexpay – Landing Page Web Estática

Comexpay es un ecosistema digital diseñado para agilizar y facilitar el desarrollo de operaciones de comercio exterior. Esta landing page corporativa presenta la solución integral para los pagos y compensaciones internacionales, adaptándose a las nuevas dinámicas del mercado global.

---

## 📌 Descripción general del proyecto

El proyecto consiste en una interfaz moderna y responsive que sirve como puerta de entrada para los servicios de Comexpay. Permite la captación de clientes a través de formularios de registro e inicio de sesión, integrados con un backend dedicado.

### Características Principales:
- **Gestión de Cuentas**: Registro de usuarios, inicio de sesión y recuperación de contraseña.
- **Servicios Corporativos**: Presentación de Cloud-Pay, Dam-Trust, Pay-Import, Exporta-Pay, Comex-Flow y Safe-X.
- **Interactividad**: Uso de animaciones (AOS, Animate.css) y efectos visuales (Particles.js).
- **Comunicación**: Integración con chat en vivo (Chatwoot) y WhatsApp.
- **Validación Internacional**: Campo de teléfono con detección de país automático (intl-tel-input).
- **Cumplimiento Legal**: Módulos de política de privacidad, tratamiento de datos y consentimiento de cookies.

---

## 🚀 Demo

🔗 **Versión en vivo:**  
[https://comexpay.co/](https://comexpay.co/)

---

## 🛠️ Tecnologías utilizadas

### Frontend
- **HTML5 & CSS3**: Estructura semántica y estilos personalizados.
- **JavaScript (Vanilla)**: Lógica del lado del cliente sin dependencia de frameworks pesados.
- **Bootstrap 5.3**: Sistema de diseño responsive y componentes de interfaz.

### Librerías y Recursos Externos
- **[Axios](https://axios-http.com/)**: Para realizar peticiones HTTP seguras a la API.
- **[Animate.css](https://animate.style/)**: Animaciones de entrada de elementos.
- **[AOS (Animate On Scroll)](https://michalsnik.github.io/aos/)**: Efectos de aparición al hacer scroll.
- **[SweetAlert2](https://sweetalert2.github.io/)**: Ventanas emergentes de confirmación y error elegantes.
- **[intl-tel-input](https://github.com/jackocnr/intl-tel-input)**: Validación y formato de números telefónicos internacionales.
- **[Particles.js](https://vincentgarreau.com/particles.js/)**: Fondo interactivo de partículas en la sección principal.
- **[Google Fonts](https://fonts.google.com/)**: Tipografía Poppins y Proxima Nova.

---

## 📂 Estructura del proyecto

```text
📁 comexpay
│
├── index.html              # Página principal (versión actual)
├── index2.html             # Versión alternativa de la página
├── diagrama.html           # Diagrama de flujo del sistema (interactivo)
│
├── css/
│   ├── style.css           # Estilos base
│   ├── style2.css          # Estilos adicionales para index.html
│   └── fonts/              # Fuentes locales (Poppins, Proxima Nova)
│
├── js/
│   ├── script.js           # Lógica principal, validaciones y llamadas a API
│   └── particles.min.js    # Librería Particles.js
│
├── assets/
│   └── particles.json      # Configuración del efecto de partículas
│
├── img/                    # Activos visuales (SVG, PNG, ICO)
│
├── favicon.ico             # Icono de la pestaña del navegador
├── robots.txt              # Instrucciones para rastreadores web
└── README.md               # Documentación del proyecto
```

---

## 💻 Desarrollo Local

Para ejecutar el proyecto localmente, se recomienda utilizar un servidor web simple para evitar errores de CORS y asegurar que todos los recursos se carguen correctamente.

### Usando Python:
```bash
# Python 3
python -m http.server 8000
```

### Usando VS Code (Live Server):
1. Instala la extensión **Live Server**.
2. Haz clic derecho en `index.html` y selecciona **Open with Live Server**.

---

## ☁️ Despliegue

Al ser un sitio estático, puede desplegarse en cualquier servidor web o plataforma de hosting estático.

### Recomendaciones:
- **Hosting Tradicional**: Subir los archivos vía FTP a un servidor Apache o Nginx. Se recomienda el uso de Apache para manejar adecuadamente redirecciones si fuera necesario.
- **Plataformas Modernas**: Conectar el repositorio a servicios como Netlify, Vercel o GitHub Pages para despliegues automáticos.
- **CORS**: Asegurarse de que el dominio donde se despliega esté autorizado en la configuración de la API de Comexpay (`api.comexpay.co`).

---

## ⚙️ Integración Técnica

El sitio interactúa con la API de Comexpay ubicada en:
`https://api.comexpay.co/api/v1/comexpayRoutes/`

### Endpoints utilizados:
- `/user`: Registro de nuevos usuarios.
- `/login`: Inicio de sesión de usuarios existentes.
- `/recuperar`: Envío de correo para recuperación de contraseña.
- `/admin`: Ruta de acceso para perfiles administrativos.

El flujo de usuario completo (incluyendo el proceso de KYC y la creación de operaciones de importación/exportación) puede visualizarse detalladamente en el archivo `diagrama.html`.

---

## ⚖️ Aviso Legal y Privacidad

El sitio incluye modales integrados para cumplir con las normativas de protección de datos (basado en la Ley 81 de 2019 de Panamá).
- **Tratamiento de datos**: El usuario debe aceptar los términos antes de registrarse.
- **Políticas de Cookies**: El aviso de consentimiento informa al usuario sobre el uso de tecnologías de rastreo para mejorar la experiencia.

---

© 2024 COMEXPAY. Todos los derechos reservados.
