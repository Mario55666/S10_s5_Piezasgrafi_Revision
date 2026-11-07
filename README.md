# Distancia funcional de observación · Experiencia concreta (EC)

**Unidad didáctica:** Producción y publicación de piezas gráficas · IDC Diseño y Comunicación
**Tema:** evaluación de la distancia funcional de observación según dimensiones y resolución
**Medio:** gran formato y material publicitario (POP, roll-up, SEG, lona de fachada, valla)
**Modalidad:** individual (equipo opcional) · 1000 XP
**Archivo:** `index.html` (≈ 1,6 MB, sin dependencias en tiempo de ejecución; jsPDF 2.5.1 y AutoTable 3.8.2 incrustados) y la carpeta `descargas/` con los cinco PNG.

Ubicación prevista:

```
tareas/tarea-NN/1__EC_Experiencia concreta/
  index.html
  README.md
  descargas/
    caso1_display_hablador_POP.png
    caso2_rollup_stand_retractil.png
    caso3_grafico_textil_SEG.png
    caso4_banner_lona_fachada.png
    caso5_gigantografia_valla.png
```

`index.html` enlaza los PNG por ruta relativa (`descargas/…`). La carpeta debe quedar junto al HTML en el servidor (en GitHub Pages: `index.html` y `descargas/` en la raíz del repositorio).

---

## 1. Propósito

El estudiante recibe cinco archivos con una ficha que declara sus medidas y su resolución. **No hay explicación previa.**

1. Primero examina cada archivo con una lupa que muestra los píxeles reales.
2. Lo descarga y lo mide en Photoshop.
3. Registra lo que ve y cómo se relaciona con la ficha.
4. Formula una hipótesis de distancia.

La tabla estándar de resolución por distancia solo aparece después de resolver el enigma. En ese momento el estudiante completa la matriz de diagnóstico de la guía de la tarea.

---

## 2. Justificación DUA-Experiencial

| Estación | Fase | Mecánica | Puntaje |
|---|---|---|---|
| 0 · Registro | — | Formulario validado: nombres, apellidos, correo institucional, equipo opcional | 0 |
| 1 · La escena | EC | Cinco piezas con descarga del PNG; 3 zonas por pieza que abren una lupa a 120 × 120 píxeles reales, con control «Ver desde» de 0.3 a 20 m | 150 (10 por zona) |
| 2 · Bitácora | EC | Medición en Photoshop (ancho y alto en cm, PPI, píxeles, modo y perfil) validada contra el archivo; textos «Lo que observo» y «Relación con la ficha» | 150 (30 por pieza: 20/15/10 según intentos + 10 por los textos) |
| 3 · Hipótesis previa | EC → OR | Distancia estimada y justificación por pieza; no se califica | 50 |
| 4 · Enigma | EC → OR | «¿Quién miente?» (contradicción entre declaración y evidencia) + candado de tres ruedas | 75 + 125 |
| 5 · Diagnóstico | CA | Tabla estándar desbloqueada + matriz de la guía: distancia funcional, diagnóstico y justificación por pieza | 350 (70 por fila: 50 o 30 por la distancia + 20) |
| 6 · Puente a OR | OR | Tres preguntas abiertas; habilita el informe | 100 |
| **Total** | | | **1000** |

**Pautas DUA:**
- **Implicación:**
  - caso de taller con archivos reales;
  - XP por estación;
  - enigma con ayuda progresiva;
  - el error no bloquea, y cada fallo indica la acción siguiente.
- **Representación:**
  - la pieza completa y la lupa a píxel real;
  - la ficha en tabla;
  - la tabla estándar con una columna de agudeza visual de 1′;
  - una tabla de peso por resolución;
  - el glosario, que se desbloquea al terminar la bitácora.
- **Acción y expresión:**
  - medición en Photoshop;
  - escritura libre con mínimos de caracteres;
  - selección en la matriz;
  - informe en PDF y en Markdown.

**Sistema de guía:**
- **Cada estación:**
  - recuadro «📘 Cómo se responde esta parte», con los nombres exactos de los botones y las condiciones que valida el código;
  - panel «Te falta (N)», que se actualiza en vivo.
- **Estación bloqueada:** muestra la lista de pendientes y el botón «Ir a …».
- **Retroalimentación:** tres filas PISTA · DATO CLAVE · CONTEXTO.
- **Bitácora:**
  - aviso si el texto propone una solución («hay que», «corregir», «ajustar»…); un segundo clic acepta el texto;
  - la relación con la ficha debe citar una medida en cm o los PPI.

---

## 3. Fidelidad a la fuente

### 3.1 Archivos (medidos en los PNG entregados)

| Caso | Pieza | Píxeles | PPI | Medida (cm) | Modo · perfil | Peso |
|---|---|---|---|---|---|---|
| 1 | Display / Hablador POP | 1890 × 2775 | 300 | 16.00 × 23.50 | RGB · sRGB IEC61966-2.1 | 4.7 MB |
| 2 | Roll-up retráctil | 472 × 1181 | 150 | 7.99 × 20.00 | RGB · sRGB IEC61966-2.1 | 0.8 MB |
| 3 | Gráfico textil SEG | 1181 × 866 | 100 | 30.00 × 22.00 | RGB · sRGB IEC61966-2.1 | 1.7 MB |
| 4 | Banner lona fachada | 1141 × 1701 | 72 | 40.25 × 60.01 | RGB · sRGB IEC61966-2.1 | 2.5 MB |
| 5 | Gigantografía / Valla | 2953 × 1261 | 25 | 300.10 × 128.15 | RGB · sRGB IEC61966-2.1 | 4.4 MB |

Los cinco PNG tienen canal alfa y la resolución guardada en el archivo (la del Caso 5 es 24.994 PPI, por eso mide 300.10 cm). La página acepta ±0.06 cm y ±0.5 PPI.

**Diferencias entre la ficha de la guía y los archivos**, usadas en el enigma:
- **Caso 1:** la ficha declara **16 × 23 cm**; el archivo mide **16 × 23.50 cm** (5 mm más de alto). Es la línea de «¿Quién miente?».
- **Caso 2:** la ficha lo indica como «muestra a escala». La pregunta 2 del Puente a OR lo retoma con una medida final de 85 × 200 cm, que es un **valor de ejemplo: confirmar**.

### 3.2 Tabla estándar (guía de la tarea)

| Distancia funcional | Resolución | Límite estricto de agudeza visual (1′) |
|---|---|---|
| Menos de 0.6 m | 300 PPI | 0.29 m |
| 0.6 m a 1.5 m | 150 PPI | 0.58 m |
| 1.5 m a 3.0 m | 100 PPI | 0.87 m |
| 3.0 m a 6.0 m | 72 PPI | 1.21 m |
| Más de 6.0 m | 25 PPI | 3.49 m |

Los rangos y las resoluciones salen de la guía de la tarea (práctica de la industria). La última columna es un cálculo agregado: distancia = 3438 ÷ PPI, en pulgadas. La página explica que la tabla de la industria admite más distancia que el límite estricto porque la pieza se mira completa. Los usos típicos de cada fila son redacción propia a partir de los cinco casos.

### 3.3 Claves del enigma

- **¿Quién miente?:** línea «Caso 1 · alto 23 cm» + evidencia «Photoshop mide 23.50 cm de alto en el Caso 1».
- **Candado de tres ruedas:** **05 · 02 · 28**.
  - Rueda 1: 23.50 − 23 = 0.5 cm = 05 mm.
  - Rueda 2: el único caso con menos de 10 cm de ancho es el Caso 2 (7.99 cm).
  - Rueda 3: 72 ÷ 2.54 = 28.3 → 28 píxeles por cm.
- **Errores que la página detecta y nombra:**
  - rueda 1 con 50 o 00 (diferencia en cm en lugar de mm), o con 23 o 24 (una medida en lugar de la diferencia);
  - rueda 2 con 08 (escribió el ancho en lugar del número del caso);
  - rueda 3 con 72 (PPI en lugar de píxeles por cm) o con 29 (redondeo).
- **Ayuda progresiva:** en el intento 1, una pista general; en el 2, qué dato mirar; en el 3, la operación resuelta.

### 3.4 Respuestas esperadas en la matriz (Estación 5)

| Caso | PPI | Distancia funcional | Diagnóstico |
|---|---|---|---|
| 1 | 300 | Menos de 0.6 m | Adecuada para esa distancia |
| 2 | 150 | 0.6 m a 1.5 m | Adecuada para esa distancia |
| 3 | 100 | 1.5 m a 3.0 m | Adecuada para esa distancia |
| 4 | 72 | 3.0 m a 6.0 m | Adecuada para esa distancia |
| 5 | 25 | Más de 6.0 m | Adecuada para esa distancia |

**Justificación de cada fila:**
- 60 caracteres o más;
- debe citar los PPI del archivo y una distancia en metros.

La matriz evalúa los PPI del archivo tal como está, igual que la guía. El efecto de la muestra a escala (Caso 2) queda para la Observación reflexiva.

### 3.5 Lupa

Recuadro de 120 × 120 píxeles del archivo, centrado en cada zona. Su medida en la pieza es 120 ÷ PPI × 25.4 mm:

| Caso | Medida del recuadro |
|---|---|
| 1 | 10.2 mm |
| 2 | 20.3 mm |
| 3 | 30.5 mm |
| 4 | 42.3 mm |
| 5 | 121.9 mm |

**Cómo simula la distancia:**
- Cuando el ojo distingue menos detalles que píxeles hay (detalle mínimo = distancia × 0.29 mm/m), el recuadro se suaviza a esa cantidad de detalles.
- Mientras tanto se dibuja sin suavizado y se ven los píxeles.
- Los hallazgos de cada zona solo describen la medida del recuadro; no nombran defectos.

---

## 4. Evidencia y datos

- **Informe** (Estación 6, después de guardar las tres respuestas):
  - en **PDF** (A4): datos del estudiante, bitácora, textos de observación, matriz de diagnóstico, hipótesis, Puente a OR y puntaje por estación;
  - en **Markdown**, con el mismo contenido.
  - Nombre del archivo: `EC_distancia_funcional_<Apellidos>_<Nombres>.pdf` / `.md`.
- **Guardado local:**
  - `localStorage` con la clave `idc-distancia-funcional-ec-v1`;
  - se guarda 400 ms después de cada cambio y al cerrar la página;
  - al reabrir, ofrece «Continuar» o «Empezar de nuevo».
- **Variables globales:** `window.state` (con `state.student`) y `window.buildMD()`.
- **Envío al panel docente:** al final del `<body>` está `<script src="/envio-resultados.js" data-sub="ec"></script>`.
- **Descargas:**
  - el informe usa la capacidad `downloads` cuando la página corre en claude.ai y la descarga directa del navegador fuera de ella;
  - los PNG se descargan con enlaces directos a `descargas/`.

---

## 5. Verificación realizada

Pruebas en Playwright con Chromium, sirviendo la carpeta por HTTP:

- **Recorrido completo** con errores intencionales:
  - registro vacío;
  - alto del Caso 1 copiado de la ficha (23 cm);
  - texto con una solución;
  - acusación equivocada;
  - combinación 50 · 08 · 72;
  - Caso 5 en el rango 3–6 m.
  - Cada error mostró PISTA · DATO CLAVE · CONTEXTO y permitió reintentar.
  - Puntaje del recorrido con errores: 935 de 1000; sin errores se obtienen 1000.
- **Teclado en las ruedas:** los dígitos entran por la derecha, desde cualquier posición del cursor.
- **Descargas:** del PNG, del informe PDF y del informe Markdown.
- **Recarga:** en una página nueva, «Continuar» recupera las respuestas, los intentos y el puntaje.
- **Conceptos ocultos:** ningún concepto técnico (pixelado, agudeza, sobredimensionado) aparece en las Estaciones 0 y 1, revisando también `aria-label`, `title` y `alt`.
- **Pantallas:** capturas a 1280 px y 375 px, sin desborde horizontal.
- **Sintaxis:** `node --check` del script principal (ES5 dentro de una IIFE).

---

Mg. Mario Quiroz Martínez · Producción y publicación de piezas gráficas · IDC · 2026
