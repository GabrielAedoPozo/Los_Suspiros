# 🌿 Los Suspiros — Web del Hospedaje (Proyecto en Astro)

Este repositorio contiene el código fuente de la página web **Los Suspiros**, un hospedaje rústico.  
El enfoque principal de este README es la **estructura del proyecto, instalación, stack y desarrollo**.

---

# 🚀 Stack Tecnológico

El proyecto está construido con:

- **Astro** — Framework rápido orientado a contenido y componentes.  
- **Tailwind CSS** — Framework CSS utilitario para diseño moderno.  
- **pnpm** — Gestor de paquetes rápido, ligero y eficiente.  
- **Git** — Control de versiones del proyecto.  

---

# ⚙️ Instalación

Clona el repositorio e instala las dependencias usando **pnpm**.

## 1️⃣ Clonar
```bash
git clone https://github.com/usuario/los-suspiros
cd los-suspiros
```

## 2️⃣ Instalar dependencias
```bash
pnpm install
```

## 3️⃣ Servidor de desarrollo
```bash
pnpm dev
```

El proyecto se abrirá en:  
**http://localhost:4321/** (o el puerto que Astro indique).

## 4️⃣ Build de producción
```bash
pnpm build
```

## 5️⃣ Previsualización del build
```bash
pnpm preview
```

---

# 📁 Estructura del Proyecto

```
/
├─ public/               # Archivos estáticos (imágenes, íconos, etc.)
├─ src/
│  ├─ components/        # Componentes reutilizables
│  ├─ layouts/           # Layouts globales
│  ├─ pages/             # Páginas del sitio (rutas)
│  ├─ styles/            # Estilos globales o utilidades
│  └─ assets/            # Recursos internos opcionales
├─ astro.config.mjs      # Configuración principal de Astro
├─ tailwind.config.mjs   # Configuración de Tailwind CSS
├─ package.json          # Scripts y dependencias
├─ tsconfig.json         # Configuración TypeScript (si aplica)
└─ README.md             # Documentación del proyecto
```

---

# 📦 Requerimientos Previos

Asegúrate de tener instalado:

- **Node.js 18+**  
- **pnpm 8+**  
- **Git**

---

# 🧑‍💻 Contribución

1. Crea una rama nueva:
```bash
git checkout -b feature/nueva-funcionalidad
```
2. Commit:
```bash
git commit -m "Agrega nueva funcionalidad"
```
3. Push:
```bash
git push origin feature/nueva-funcionalidad
```
4. Crea un Pull Request.

---

# 📜 Licencia

Este proyecto se distribuye bajo la licencia que elijas (MIT recomendada).  
Puedes modificar libremente los archivos según tus necesidades.

---

Si quieres, te hago una versión **más técnica**, **minimalista**, o incluso adaptada al estándar de **README profesional de GitHub**.
