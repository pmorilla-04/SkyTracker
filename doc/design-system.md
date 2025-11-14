# 🎿 Ski Tracker App – Sistema de Diseño

## 🎨 1. Paleta de Colores

**Tema general:** fresco, claro y deportivo — que recuerde a la nieve, el frío y el aire de montaña.

| Tipo | Color | Uso principal | HEX |
|-------|--------|---------------|------|
| **Color principal** | 🩵 Azul hielo | Fondo y elementos dominantes | `#D9F1FF` |
| **Color secundario** | 🔵 Azul oscuro | Botones, títulos, destacados | `#003366` |
| **Color de acento** | 🟠 Naranja nieve | Botones principales y acentos visuales | `#FF7B00` |
| **Color neutro claro** | ⚪ Blanco puro | Fondos, tarjetas, espacios | `#FFFFFF` |
| **Color neutro oscuro** | ⚫ Gris oscuro | Texto principal | `#2C2C2C` |
| **Color verde** | 🟢 Verde nieve | Mensajes de éxito o confirmación | `#3CB371` |
| **Color rojo** | 🔴 Rojo suave | Errores o avisos | `#E63946` |

💡 Esta combinación transmite sensación de aire fresco y deportividad sin sobrecargar el diseño.

---

## ✍️ 2. Tipografía

**Fuente principal:** [Poppins](https://fonts.google.com/specimen/Poppins)  
→ Moderna, legible y con un toque deportivo.

**Fuente alternativa:** [Roboto](https://fonts.google.com/specimen/Roboto)  
→ Ideal para textos largos o contenido secundario.

### Jerarquía de texto

| Elemento | Tamaño | Peso | Ejemplo |
|----------|------|-----|----------|
| **Títulos principales (h1)** | 28–32px | 600 | Ski Tracker App |
| **Subtítulos (h2, h3)** | 20–24px | 500 | Mis jornadas |
| **Texto base** | 16px | 400 | Añade una nueva jornada de esquí... |
| **Botones / Labels** | 14–16px | 600 | Guardar jornada |

---

## 🧩 3. Componentes Principales

### 🔘 Botones

| Tipo | Colores | Estilo |
|--------|---------|--------|
| **Primario** | Fondo azul oscuro `#003366`, texto blanco `#FFFFFF` | Para acciones principales |
| **Secundario** | Fondo blanco `#FFFFFF`, borde azul `2px solid #003366` | Para acciones secundarias |
| **Acción destacada** | Fondo naranja `#FF7B00`, texto blanco `#FFFFFF` | Para acciones especiales |

🧠 *Efecto hover:* aclarar ligeramente el color o añadir una sombra suave.

---

### 📋 Tarjetas de Jornada
- **Fondo:** blanco `#FFFFFF`  
- **Borde:** suave `#E8E8E8`  
- **Contenido:** título (nombre de la estación), fecha, valoración (⭐️), foto pequeña  
- **Estilo:** sombra suave y esquinas redondeadas (`border-radius: 12px`)  

---

### 📈 Gráficos
- Colores principales: tonos azules y naranjas  
- Librerías sugeridas: **Chart.js** o **Google Charts**  
- Visualizaciones: horas totales esquiadas, días por mes, media de valoración  

---

## 🌌 4. Estilo General

- **Estética:** minimalista, clara y con mucho espacio en blanco  
- **Iconografía:** iconos simples y lineales (Lucide, Material Icons o Font Awesome)  
- **Sombras:** para dar profundidad (`box-shadow: 0 4px 10px rgba(0,0,0,0.1)`)  
- **Esquinas redondeadas:** `border-radius: 12px` o `16px`  
- **Interacciones:** animaciones suaves con `transition: 0.3s ease`  

---

## 📱 5. Diseño Responsive

- **Móvil:** diseño de una sola columna  
- **Tablet:** 2 columnas para tarjetas y gráficos  
- **Escritorio:** 3 columnas con más espacio y menús laterales  
- **Barra inferior fija:** con iconos para navegación  
  - 🏠 Inicio  
  - ➕ Nueva jornada  
  - 📈 Estadísticas  
  - 👤 Perfil  

---

### 🔗 Referencias Visuales
- Pantones inspirados en la nieve y el cielo: **Ice Blue**, **Deep Navy**, **Warm Orange**  
- Inspiración UI: apps deportivas (Strava, Komoot, Ski Tracks)

---