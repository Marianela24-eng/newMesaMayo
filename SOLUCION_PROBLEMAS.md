# 🔧 Solución de Problemas - GitHub Pages en Blanco

## Problema: La página sale en blanco en https://marianela24-eng.github.io/juego/

### ✅ Checklist de Verificación:

1. **Verifica que el archivo se llame `index.html`** (no `mesa-mayo-completo.html`)
2. **Verifica que TODAS las imágenes estén subidas** en la misma carpeta
3. **Verifica las rutas de las imágenes** - deben ser relativas sin `./` o con `/` al inicio

### 🔍 Pasos para Solucionar:

#### Paso 1: Verificar que el archivo se llame `index.html`

En GitHub, ve a tu repositorio y verifica que el archivo principal se llame exactamente `index.html` (todo en minúsculas).

#### Paso 2: Verificar que todas las imágenes estén subidas

Asegúrate de que estas imágenes estén en la raíz del repositorio:
- `bisturi_hojas.png`
- `tijera_mayo.png`
- `kelly.png`
- `ailis.png`
- `portaguja.png`
- `gasas.png`
- `dientes.png`
- `separador.png`
- `anillos.png`

#### Paso 3: Corregir las rutas de las imágenes

Las rutas deben ser así (sin `./`):
```javascript
image: 'bisturi_hojas.png',  // ✅ Correcto
// NO: image: './bisturi_hojas.png',  // ❌ Puede causar problemas
```

#### Paso 4: Verificar la consola del navegador

1. Abre https://marianela24-eng.github.io/juego/
2. Presiona `F12` para abrir las herramientas de desarrollador
3. Ve a la pestaña "Console"
4. Busca errores en rojo
5. Ve a la pestaña "Network" y recarga la página
6. Verifica qué archivos no se están cargando

#### Paso 5: Verificar GitHub Pages está activado

1. Ve a tu repositorio en GitHub
2. Click en "Settings"
3. Click en "Pages" en el menú lateral
4. Verifica que esté configurado:
   - Source: "Deploy from a branch"
   - Branch: "main" (o "master")
   - Folder: "/ (root)"
5. Si no está activado, actívalo y espera 1-2 minutos

### 🚨 Errores Comunes:

#### Error 1: "Failed to load resource"
- **Causa**: Las imágenes no están en el repositorio o tienen nombres incorrectos
- **Solución**: Sube todas las imágenes con los nombres exactos

#### Error 2: "React is not defined"
- **Causa**: Los CDN de React no se están cargando
- **Solución**: Verifica tu conexión a internet o usa versiones locales

#### Error 3: Página completamente en blanco
- **Causa**: Error de JavaScript que detiene la ejecución
- **Solución**: Revisa la consola del navegador para ver el error específico

### 📝 Archivo Corregido

He creado un archivo `index.html` corregido con:
- ✅ Rutas de imágenes sin `./`
- ✅ Manejo de errores mejorado
- ✅ Logs en consola para debugging

### 🔄 Cómo Actualizar:

1. Descarga el archivo `index.html` corregido
2. Reemplázalo en tu repositorio
3. Sube TODAS las imágenes (si no las has subido)
4. Espera 1-2 minutos
5. Recarga la página con `Ctrl + F5` (forzar recarga)

### 📞 Si Aún No Funciona:

1. Abre la consola del navegador (F12)
2. Copia TODOS los errores que aparezcan
3. Verifica en la pestaña "Network" qué archivos dan error 404
4. Asegúrate de que todos los archivos estén en la raíz del repositorio

