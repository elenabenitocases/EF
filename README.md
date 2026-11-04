# Catálogo de recursos de educación física para educación primaria (1.º a 6.º)
**Marco pedagógico:** LOMLOE (Real Decreto 157/2022) | **Enfoque:** competencial, inclusivo (DUA), lúdico y vivencial

---

## 🎯 Presentación del proyecto

Este recurso ha sido diseñado específicamente para maestras y maestros de educación física que necesitan disponer a mano de un catálogo estructurado, práctico y de consulta rápida con actividades, juegos y situaciones de aprendizaje para los **seis cursos de la etapa de educación primaria**.

El sistema combina:
1. **Fichas individuales en formato Markdown:** para consulta rápida, edición o integración en las programaciones de aula.
2. **Aplicación interactiva e imprimible en HTML (`catalogo_fichas_imprimibles.html` / `index.html`):** permite filtrar por curso o ciclo, bloque de contenidos o palabra clave, y enviar a imprimir en **A4** (ficha individual o catálogo completo con un solo clic).
3. **Matriz curricular completa (`00_MATRIZ_CURRICULAR_LOMLOE.md`):** vinculación de competencias clave, competencias específicas del área de educación física y saberes básicos.
4. **Plantilla modelo (`PLANTILLA_FICHA_EN_BLANCO.md`):** para mantener el mismo formato y rigor pedagógico al crear nuevas propuestas didácticas.

---

## 📂 Estructura de carpetas y ficheros

```
d:\Educación Física Primaria\
│
├── README.md                                    <- Guía general de uso y presentación
├── 00_MATRIZ_CURRICULAR_LOMLOE.md               <- Mapa curricular, competencias y progresión
├── PLANTILLA_FICHA_EN_BLANCO.md                 <- Plantilla editable para crear nuevas fichas
├── catalogo_fichas_imprimibles.html             <- Visor interactivo e impresión profesional A4
├── index.html                                   <- Archivo de inicio para publicación web
│
├── 01_FICHAS_1_CICLO_1_Y_2/                     <- Recursos para 1.º y 2.º de primaria
│   ├── Ficha_1C_01_El_Zoologico_en_Movimiento.md       (Bloque C: HMB y cuento motor)
│   ├── Ficha_1C_02_Los_Guardianes_del_Tesoro.md        (Bloque C: lateralidad y esquema corporal)
│   ├── Ficha_1C_03_El_Viaje_del_Paracaidas_Magico.md   (Bloque D: cooperación y sincronización)
│   ├── Ficha_1C_04_Cazadores_de_Estrellas_y_Cometas.md (Bloque C: lanzamiento y óculo-manual)
│   ├── Ficha_1C_05_El_Museo_de_las_Esculturas_Sonoras.md (Bloque E: expresión corporal y ritmo)
│   └── Ficha_1C_06_El_Bosque_Sensorial_y_Huellas.md    (Bloque F y A: naturaleza y salud)
│
├── 02_FICHAS_2_CICLO_3_Y_4/                     <- Recursos para 3.º y 4.º de primaria
│   ├── Ficha_2C_01_Circuito_Habilidades_Combinadas.md  (Bloque C: HMB combinadas y enlaces)
│   ├── Ficha_2C_02_Juegos_Tradicionales_del_Mundo.md   (Bloque E y D: cultura motriz - Mbube)
│   ├── Ficha_2C_03_Predeporte_Colpbol_Iniciacion.md    (Bloque C y D: deporte de golpeo e invasión)
│   ├── Ficha_2C_04_Acrosport_Figuras_Basicas.md        (Bloque E: circo, figuras y apoyos seguros)
│   ├── Ficha_2C_05_Orientacion_Mapa_Colegio.md         (Bloque F: croquis escolar y balizas)
│   └── Ficha_2C_06_Calentamiento_y_Salud_Postural.md   (Bloque A y B: calentamiento y mochilas)
│
└── 03_FICHAS_3_CICLO_5_Y_6/                     <- Recursos para 5.º y 6.º de primaria
    ├── Ficha_3C_01_Deporte_Alternativo_Datchball.md    (Bloque C y D: pelota viva y autoarbitraje)
    ├── Ficha_3C_02_Ultimate_Frisbee_Invasion.md        (Bloque C y D: disco volador sin contacto)
    ├── Ficha_3C_03_Coreografia_Danza_Urbana.md         (Bloque E: flashmob, compás de 8 tiempos)
    ├── Ficha_3C_04_Orientacion_Score_Urbano_Natural.md (Bloque F: estrategia score y tiempo)
    ├── Ficha_3C_05_Condicion_Fisica_Limpia_Saludable.md(Bloque A: frecuencia cardíaca y RPE)
    └── Ficha_3C_06_Escape_Room_Motor_Cooperativo.md    (Bloque D y C: retos motrices y enigmas)
```

---

## 🖨️ ¿Cómo imprimir las fichas?

El archivo `catalogo_fichas_imprimibles.html` incluye reglas CSS de impresión profesionales (`@page { size: A4 portrait; }` y salto de página automático por ficha):

1. **Abrir en tu navegador:** haz doble clic sobre `catalogo_fichas_imprimibles.html` (o accede mediante la web pública de GitHub Pages).
2. **Imprimir una ficha individual:** cada ficha cuenta con el botón `🖨️ Imprimir esta ficha`. Al pulsarlo, el visor oculta automáticamente el resto y abre la vista previa de impresión solo para esa ficha (1 página A4).
3. **Imprimir por ciclo o bloque:**
   * Usa los desplegables superiores para seleccionar, por ejemplo, **1.er ciclo (1.º y 2.º)** o **Bloque E (Expresión)**.
   * Pulsa el botón `🖨️ Imprimir selección / todo`.
   * En el diálogo de impresión, selecciona **Guardar como PDF** o tu impresora física. Cada ficha se imprimirá en una hoja A4 independiente sin solapamientos.

---

## 📋 Estructura homogénea de cada ficha

Cada una de las fichas incluye ocho apartados para una lectura ágil en la pista:

| Apartado | Contenido |
| :--- | :--- |
| **Cabecera y metadatos** | Ciclo, curso recomendado, código, bloque de saberes y competencias (CE LOMLOE y clave). |
| **Ficha técnica** | Espacio necesario, duración orientativa, materiales exactos y tipo de agrupación. |
| **Objetivos de aprendizaje** | Diferenciados en componente motor, socioemocional y cognitivo o táctico. |
| **Desarrollo y reglas** | Explicación secuencial, motivadora y sin eliminaciones excluyentes (juego activo continuo). |
| **Diagrama espacial** | Esquema gráfico con la distribución del alumnado, materiales y metas en pista. |
| **Medidas DUA (inclusión)** | Nivel verde (apoyo o simplificación) y nivel rojo (desafío o extensión). |
| **Preguntas de reflexión final** | Dos preguntas orientadas a la asamblea final o vuelta a la calma (evaluación formativa). |
| **Seguridad y prevención** | Puntos críticos para prevenir accidentes, choques o lesiones articulares. |

---

## 💡 Recomendaciones para la puesta en práctica

* **Plastificado o fundas de anillas:** se recomienda imprimir las fichas en cartulina A4 o introducirlas en fundas plásticas en una carpeta clasificadora con separadores por ciclos.
* **El alumnado protagonista:** en el segundo y tercer ciclo, las fichas pueden entregarse directamente a un portavoz de equipo para que el grupo gestione de forma autónoma la preparación del material y la comprensión de las normas.
