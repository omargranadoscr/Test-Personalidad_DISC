# Test de Personalidad – DISC (Single-file)
**Build:** v48 · **App:** v3.7 - 16/8/25

## Historial de versiones (changelog)
### 1.0
- MVP de cuestionario en una sola página (React + Tailwind + Babel UMD).
- 15 filas (W, X, Y, Z) con selección 4–3–2–1 (sin repetir en la fila).
- Botón “Confirmar y siguiente” deshabilitado hasta completar la fila.
- Barra de progreso básica.

### 1.1
- Copys iniciales mejorados para explicar: 4 = me describe la mayoría de las veces…
- Título en azul Navy para mayor contraste.

### 2.0
- UI móvil-first (badges W/X/Y/Z, tarjetas y selects más grandes).
- “Borrar selección actual” por fila.
- Botones accesibles (estados hover/disabled).

### 2.1
- Lectura espiritual inicial (mensaje por estilo) y **separación** visual de bloques.
- Generación de **PDF** con resultados.
- Instrucciones reunidas en líneas claras (no párrafos largos).

### 2.2
- Ajustes tipográficos, espaciados y dark-friendly en los **resultados**.
- Mensaje pastoral centrado: “**Mensaje pastoral para recordar**”.

### 2.3
- **Renombrado de estilos**: Sereno → **Estable**; Cumplidor → **Conforme** (en el sentido de conformidad técnica/calidad/precisión; no “conformarse al mundo”).  
- Afinado de textos pastorales para reducir ambigüedad y enfatizar “concienzudo/calidad”.

### 3.0
- Flujo de **edición desde resultados**: selector para “Editar: [pregunta]” sin reiniciar todo.
- “Recalcular resultados” solo si el test está al 100%.
- Aviso de **preguntas incompletas** con saltos rápidos a la primera pendiente.
- Persistencia en **localStorage** (estado versionado).

### 3.1
- Corrección de errores: comillas escapadas en JSX y variable `theme` no definida en `useEffect`.

### 3.2
- Modo **Auto** (claro/oscuro) según sistema.  
- Título centrado y contraste mejorado; botones dark-friendly.

### 3.5
- Footer con número de versión visible; layout `min-h-screen` para fijar el pie al fondo.

### 3.6
- Ajustes de accesibilidad y microcopias (Ej.: “Borrar selección actual”).  
- Pack listo para GitHub Pages (HTML + README + ZIP).

### 3.7
- **Dark mode a nivel raíz**: la clase `dark` ahora se aplica en `<html>` (todo el sitio se oscurece, incluidas instrucciones y fondo).
- Correcciones menores en combinaciones del mensaje pastoral.
- Iconos y `site.webmanifest` para iOS/Android/Favicon.  
- Footer actualizado: **v3.7 - 16/8/25**.

---

## Publicar en GitHub Pages
1. En tu repo → **Code → Add file → Upload files**.
2. Sube `index.html` (este build) y `README.md`.  
3. Sube los iconos y `site.webmanifest` a la raíz del repo.  
4. Abre: `https://<usuario>.github.io/<repo>/?v=3.7-icon`.

## Créditos
- React 18 UMD, TailwindCDN, jsPDF + autotable.
- Elaborado junto a Omar, con enfoque pastoral y claridad pedagógica.
