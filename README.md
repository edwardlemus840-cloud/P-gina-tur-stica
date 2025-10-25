# WayGO - Página Turística de El Salvador

Sitio web turístico que muestra lugares emblemáticos y restaurantes de El Salvador.

## 🌟 Características

- **Lugares Turísticos**: Playas, volcanes, parques y sitios arqueológicos
- **Restaurantes**: Selección de los mejores restaurantes del país
- **Diseño Responsivo**: Adaptado para dispositivos móviles y desktop

## 📁 Estructura del Proyecto

```
proyecto/
├── index.html              # Página principal
├── lugares.html            # Página de lugares turísticos
├── restaurantes.html       # Página de restaurantes
├── img/                    # Imágenes de lugares turísticos
├── img2/                   # Imágenes de restaurantes
├── server.js               # Servidor Express para producción
└── package.json            # Dependencias del proyecto
```

## 🚀 Despliegue en Render

### Pasos para desplegar:

1. **Subir código a GitHub** (ya completado)
   - Repositorio: https://github.com/edwardlemus840-cloud/P-gina-tur-stica.git

2. **Crear cuenta en Render**
   - Ve a [render.com](https://render.com) y crea una cuenta gratuita

3. **Crear nuevo Web Service**
   - Click en "New +" → "Web Service"
   - Conecta tu repositorio de GitHub
   - Selecciona el repositorio `P-gina-tur-stica`

4. **Configuración del servicio**
   - **Name**: waygo-turismo (o el nombre que prefieras)
   - **Environment**: Node
   - **Build Command**: `npm install`
   - **Start Command**: `npm start`
   - **Plan**: Free

5. **Deploy**
   - Click en "Create Web Service"
   - Render automáticamente construirá y desplegará tu sitio

## 💻 Desarrollo Local

Para ejecutar localmente:

```bash
# Instalar dependencias
npm install

# Iniciar servidor
npm start
```

El sitio estará disponible en `http://localhost:3000`

## 📝 Tecnologías

- HTML5
- CSS3
- JavaScript
- Node.js + Express (para servidor)

## 📄 Licencia

MIT

---

**Desarrollado con ❤️ para promover el turismo en El Salvador**
