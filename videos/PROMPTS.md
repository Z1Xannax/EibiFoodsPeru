# 🎬 Prompts para los videos de Ebi Foods (vertical 9:16 · 4–5s · loop)

Generar en la **web de Higgsfield** (modelo tipo Kling/imagen-a-video). Donde se indica
**imagen de inicio**, sube esa foto como *start frame* para que el video salga idéntico al
producto real. Descarga cada video y guárdalo en esta carpeta `/videos` con el **nombre exacto**
de la columna "Archivo" — el sitio lo detecta automáticamente.

| # | Archivo | Imagen de inicio | Prompt (EN, optimizado para image-to-video) |
|---|---------|------------------|---------------------------------------------|
| 1 | `hamburguesa.mp4` | `assets/producto-burger.jpg` | Cinematic macro food video of a grilled langostino (prawn) burger on a rustic wooden board: brioche bun, fresh green lettuce, ripe tomato and red onion rings, juicy grilled prawn patty with char grill marks, gentle steam rising, glossy glaze, shallow depth of field, slow push-in, warm appetizing lighting, premium 4K food commercial, vertical 9:16 |
| 2 | `alino.mp4` | `assets/producto-alino.jpg` | Cinematic macro of two golden grilled prawn patties on a ceramic plate next to a creamy golden sauce in a small bowl and a colorful beet-and-pomegranate salad, soft natural daylight, fresh and healthy, subtle steam, slow elegant camera reveal, ultra appetizing, vertical 9:16 |
| 3 | `parrilla.mp4` | *(sin foto — texto a video)* | Cinematic close-up of langostino prawn patties grilling on a hot grill with visible dark char grill marks, light smoke and sizzling, a basting brush stroke, glowing embers, dramatic warm grill lighting, slow motion, mouthwatering, vertical 9:16 |

## Especificaciones
- **Orientación:** VERTICAL 9:16 (1080×1920; 4K opcional)
- **Formato:** `.mp4` (H.264) · **sin audio** (se reproducen en mudo y en bucle)
- **Duración:** 4–5 s · movimiento apetitoso (vapor, brillo, primer plano, push-in lento)
- **Peso:** idealmente < 6 MB para que cargue rápido en celular

## Notas
- `hamburguesa.mp4` y `alino.mp4` muestran la **foto real como poster** mientras el video no exista,
  así que esos dos ya se ven bien aunque falte el video.
- `parrilla.mp4` muestra la escena 3D animada de respaldo hasta que subas el video.
- ¿Cambiar, agregar o quitar un producto/receta? Edita el arreglo `PRODUCTOS` al inicio del
  `<script>` en `menu.html` (en `index.html` las 3 tarjetas destacadas están en el HTML).
