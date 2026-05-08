# Mini-Landing Page

Una landing page minimalista que incluye un formulario de inicio de sesión y una vista de perfil de bienvenida. Este proyecto fue diseñado como una práctica de maquetación web utilizando **Tailwind CSS**.

## 🚀 Características

- **Formulario de Login:** Diseño limpio con campos de correo, contraseña y opción de recordar sesión.
- **Vista de Perfil:** Página de bienvenida con imagen de perfil estilizada y degradados.
- **Diseño Responsivo:** Centrado y adaptable a diferentes tamaños de pantalla mediante Flexbox.
- **Personalización:** Uso de configuración extendida de Tailwind para colores personalizados (`Rosa`, `borde`).

## 🛠️ Tecnologías

- **HTML5:** Estructura semántica.
- **Tailwind CSS:** Estilizado rápido mediante clases de utilidad (vía CDN para desarrollo rápido).
- **JavaScript:** Configuración dinámica de temas de Tailwind.

## 📂 Estructura del Proyecto

```
mini-landing/
├── assets/             # Imágenes y recursos estáticos (Logo, Foto de perfil)
├── index.html          # Página de inicio de sesión (Login)
├── login.html          # Página de bienvenida (Perfil)
├── tailwind.config.js  # Configuración personalizada de Tailwind
└── README.md           # Documentación del proyecto
```

## 🔧 Instalación y Uso

1. **Clona el repositorio:**
   ```bash
   git clone <url-del-repositorio>
   ```

2. **Abre el proyecto:**
   Simplemente abre el archivo `index.html` en tu navegador preferido. No requiere de un servidor de desarrollo complejo ya que utiliza Tailwind vía CDN.

## ✒️ Personalización

Los colores principales se pueden modificar en el bloque de configuración dentro de los archivos HTML o en `tailwind.config.js`:

```javascript
colors: { 
  Rosa: "#F195E0",
  borde: "#CD95E1"
}
```

---
Desarrollado como proyecto de práctica en 2026.
