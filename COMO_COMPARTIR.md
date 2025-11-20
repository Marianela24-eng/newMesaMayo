# 📱 Cómo Compartir el Juego con tus Compañeros

Esta guía te ayudará a compartir el juego "Mesa de Mayo" para que tus compañeros puedan jugarlo en sus teléfonos móviles.

## 🌐 Opción 1: GitHub Pages (GRATIS y FÁCIL) ⭐ RECOMENDADO

### Pasos:

1. **Crea una cuenta en GitHub** (si no tienes una):
   - Ve a https://github.com
   - Crea una cuenta gratuita

2. **Crea un nuevo repositorio**:
   - Haz clic en el botón "+" en la esquina superior derecha
   - Selecciona "New repository"
   - Nombra el repositorio (ej: "mesa-mayo-juego")
   - Marca como "Public"
   - NO marques "Initialize with README"
   - Haz clic en "Create repository"

3. **Sube los archivos**:
   - En la página del repositorio, haz clic en "uploading an existing file"
   - Arrastra TODOS estos archivos:
     - `mesa-mayo-completo.html`
     - `bisturi_hojas.png`
     - `tijera_mayo.png`
     - `kelly.png`
     - `ailis.png`
     - `portaguja.png`
     - `gasas.png`
     - `dientes.png`
     - `separador.png`
     - `anillos.png`
     - `musica_fondo.mp3` (si lo tienes)
   - Haz clic en "Commit changes"

4. **Activa GitHub Pages**:
   - Ve a "Settings" (Configuración) en tu repositorio
   - En el menú lateral, busca "Pages"
   - En "Source", selecciona "Deploy from a branch"
   - En "Branch", selecciona "main" y "/ (root)"
   - Haz clic en "Save"
   - Espera 1-2 minutos

5. **Obtén tu URL**:
   - GitHub te dará una URL como: `https://tu-usuario.github.io/mesa-mayo-juego/mesa-mayo-completo.html`
   - **IMPORTANTE**: Renombra `mesa-mayo-completo.html` a `index.html` para que la URL sea más corta
   - La URL final será: `https://tu-usuario.github.io/mesa-mayo-juego/`

6. **Comparte el enlace**:
   - Envía esta URL a tus compañeros
   - Pueden abrirla directamente en sus teléfonos

---

## 🌐 Opción 2: Netlify Drop (MUY FÁCIL, sin registro)

### Pasos:

1. **Ve a Netlify Drop**:
   - Abre https://app.netlify.com/drop en tu navegador

2. **Arrastra la carpeta**:
   - Crea una carpeta con todos los archivos del juego
   - Arrastra toda la carpeta a la página de Netlify Drop
   - Espera a que se suba

3. **Obtén tu URL**:
   - Netlify te dará una URL automáticamente
   - Ejemplo: `https://random-name-123.netlify.app`
   - **IMPORTANTE**: Renombra `mesa-mayo-completo.html` a `index.html` antes de subir

4. **Comparte el enlace**:
   - Envía esta URL a tus compañeros

---

## 🌐 Opción 3: Vercel (GRATIS)

### Pasos:

1. **Instala Vercel CLI** (opcional, también puedes usar la web):
   ```bash
   npm install -g vercel
   ```

2. **O usa la interfaz web**:
   - Ve a https://vercel.com
   - Crea una cuenta
   - Haz clic en "Add New Project"
   - Arrastra tu carpeta con los archivos
   - Vercel detectará automáticamente el proyecto

3. **Obtén tu URL**:
   - Vercel te dará una URL como: `https://mesa-mayo.vercel.app`

---

## 🌐 Opción 4: Usar un Servidor Local (para pruebas rápidas)

### Si todos están en la misma red WiFi:

1. **Usa Python** (si lo tienes instalado):
   ```bash
   # En la carpeta del proyecto
   python -m http.server 8000
   ```

2. **O usa Node.js**:
   ```bash
   npx http-server -p 8000
   ```

3. **Obtén tu IP local**:
   - En Windows: abre CMD y escribe `ipconfig`
   - Busca "IPv4 Address" (ej: 192.168.1.100)
   - En Mac/Linux: escribe `ifconfig` o `ip addr`

4. **Comparte la URL**:
   - `http://TU-IP:8000/mesa-mayo-completo.html`
   - Ejemplo: `http://192.168.1.100:8000/mesa-mayo-completo.html`

---

## ✅ Checklist Antes de Compartir

- [ ] Todas las imágenes están en la misma carpeta que el HTML
- [ ] El archivo HTML se llama `index.html` (o comparte la URL completa)
- [ ] Todas las rutas de imágenes usan `./` (rutas relativas)
- [ ] Probaste el juego en tu propio teléfono antes de compartir
- [ ] Verificaste que las imágenes se cargan correctamente

---

## 🔧 Solución de Problemas

### Las imágenes no se ven:
1. Verifica que todas las imágenes estén en la misma carpeta
2. Verifica que los nombres de archivo coincidan exactamente (mayúsculas/minúsculas)
3. Asegúrate de que las rutas usen `./` (rutas relativas)

### El juego no funciona en móviles:
1. Verifica que estés usando HTTPS (GitHub Pages, Netlify y Vercel lo tienen)
2. Algunos navegadores móviles bloquean contenido mixto (HTTP/HTTPS)

### El juego es muy lento:
1. Optimiza las imágenes (reduce su tamaño)
2. Usa un servicio de hosting rápido (Netlify o Vercel son muy rápidos)

---

## 📱 Cómo Acceder desde el Teléfono

1. **Abre el navegador** en tu teléfono (Chrome, Safari, etc.)
2. **Escribe la URL** que te compartieron
3. **Agrega a pantalla de inicio** (opcional):
   - En Android: Menú → "Agregar a pantalla de inicio"
   - En iPhone: Compartir → "Agregar a pantalla de inicio"

---

## 🎯 Recomendación Final

**Usa GitHub Pages** porque:
- ✅ Es completamente gratis
- ✅ Fácil de configurar
- ✅ URL permanente
- ✅ Funciona perfectamente en móviles
- ✅ No requiere conocimientos técnicos avanzados

---

## 📞 ¿Necesitas Ayuda?

Si tienes problemas, verifica:
1. Que todos los archivos estén subidos
2. Que las rutas de las imágenes sean relativas (`./nombre.png`)
3. Que el archivo HTML se llame `index.html` o compartas la URL completa

