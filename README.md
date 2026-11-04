# Catálogo de Recursos de Educación Física para Educación Primaria (1º a 6º)
**Marco Pedagógico:** LOMLOE (Real Decreto 157/2022) | **Enfoque:** Competencial, Inclusivo (DUA), Lúdico y Vivencial

---

## 🎯 Presentación del Proyecto

Este recurso ha sido diseñado específicamente para maestras y maestros de Educación Física que necesitan disponer en mano de un catálogo estructurado, práctico y de consulta rápida con actividades, juegos y situaciones de aprendizaje para los **6 cursos de la etapa de Primaria**.

El sistema combina:
1. **Fichas individuales en formato Markdown:** Para consulta rápida, edición o integración en programaciones de aula.
2. **Aplicador interactivo e imprimible en HTML (`catalogo_fichas_imprimibles.html`):** Permite filtrar por curso/ciclo, bloque de contenidos o palabra clave, y enviar a imprimir en **A4** (ficha individual o pack completo con un solo clic).
3. **Matriz curricular completa (`00_MATRIZ_CURRICULAR_LOMLOE.md`):** Vinculación de Competencias Clave, Competencias Específicas de EF y Saberes Básicos.
4. **Plantilla modelo (`PLANTILLA_FICHA_EN_BLANCO.md`):** Para mantener el mismo formato y rigor pedagógico al crear nuevas propuestas didácticas.

---

## 📂 Estructura de Carpetas y Ficheros

```
d:\Educación Física Primaria\
│
├── README.md                                    <- Guía general de uso y presentación
├── 00_MATRIZ_CURRICULAR_LOMLOE.md               <- Mapa curricular, competencias y progresión
├── PLANTILLA_FICHA_EN_BLANCO.md                 <- Plantilla editable para crear nuevas fichas
├── catalogo_fichas_imprimibles.html             <- Visor interactivo e impresión profesional A4
│
├── 01_FICHAS_1_CICLO_1_Y_2/                     <- Recursos para 1º y 2º de Primaria
│   ├── Ficha_1C_01_El_Zoologico_en_Movimiento.md       (Bloque C: HMB y cuento motor)
│   ├── Ficha_1C_02_Los_Guardianes_del_Tesoro.md        (Bloque C: Lateralidad y esquema corporal)
│   ├── Ficha_1C_03_El_Viaje_del_Paracaidas_Magico.md   (Bloque D: Cooperación y sincronización)
│   ├── Ficha_1C_04_Cazadores_de_Estrellas_y_Cometas.md (Bloque C: Lanzamiento y óculo-manual)
│   ├── Ficha_1C_05_El_Museo_de_las_Esculturas_Sonoras.md (Bloque E: Expresión corporal y ritmo)
│   └── Ficha_1C_06_El_Bosque_Sensorial_y_Huellas.md    (Bloque F & A: Naturaleza y salud)
│
├── 02_FICHAS_2_CICLO_3_Y_4/                     <- Recursos para 3º y 4º de Primaria
│   ├── Ficha_2C_01_Circuito_Habilidades_Combinadas.md  (Bloque C: HMB combinadas y enlaces)
│   ├── Ficha_2C_02_Juegos_Tradicionales_del_Mundo.md   (Bloque E & D: Cultura motriz - Mbube)
│   ├── Ficha_2C_03_Predeporte_Colpbol_Iniciacion.md    (Bloque C & D: Deporte de golpeo e invasión)
│   ├── Ficha_2C_04_Acrosport_Figuras_Basicas.md        (Bloque E: Circo, figuras y apoyos seguros)
│   ├── Ficha_2C_05_Orientacion_Mapa_Colegio.md         (Bloque F: Croquis escolar y balizas)
│   └── Ficha_2C_06_Calentamiento_y_Salud_Postural.md   (Bloque A & B: Calentamiento y mochilas)
│
└── 03_FICHAS_3_CICLO_5_Y_6/                     <- Recursos para 5º y 6º de Primaria
    ├── Ficha_3C_01_Deporte_Alternativo_Datchball.md    (Bloque C & D: Pelota viva y autoarbitraje)
    ├── Ficha_3C_02_Ultimate_Frisbee_Invasion.md        (Bloque C & D: Disco volador sin contacto)
    ├── Ficha_3C_03_Coreografia_Danza_Urbana.md         (Bloque E: Flashmob, 8 tiempos y beat)
    ├── Ficha_3C_04_Orientacion_Score_Urbano_Natural.md (Bloque F: Estrategia Score y tiempo)
    ├── Ficha_3C_05_Condicion_Fisica_Limpia_Saludable.md(Bloque A: Frecuencia cardíaca y RPE)
    └── Ficha_3C_06_Escape_Room_Motor_Cooperativo.md    (Bloque D & C: Retos motrices y enigmas)
```

---

## 🖨️ ¿Cómo Imprimir las Fichas?

El archivo `catalogo_fichas_imprimibles.html` incluye reglas CSS de impresión profesionales (`@page { size: A4 portrait; }` y salto de página automático por ficha):

1. **Abrir en tu navegador:** Haz doble clic sobre `catalogo_fichas_imprimibles.html` (funciona en Chrome, Edge, Firefox o Safari sin conexión a internet).
2. **Imprimir una ficha individual:** Cada ficha cuenta con un botón gris `🖨️ Imprimir esta ficha`. Al pulsarlo, el visor oculta automáticamente el resto y abre la vista previa de impresión solo para esa ficha (1 página A4).
3. **Imprimir por Ciclo o Bloque:**
   * Usa los desplegables superiores para seleccionar, por ejemplo, **1er Ciclo (1º y 2º)** o **Bloque E (Expresión)**.
   * Pulsa el botón verde superior `🖨️ Imprimir Selección / Todo`.
   * En el diálogo de impresión, selecciona **Guardar como PDF** o tu impresora física. Cada ficha se imprimirá en una hoja A4 independiente sin solapamientos.

---

## 📋 Estructura Homogénea de Cada Ficha

Cada una de las fichas incluye 8 apartados para una lectura ágil en la pista:

| Apartado | Contenido |
| :--- | :--- |
| **Cabecera & Metadatos** | Ciclo, curso recomendado, código, bloque de saberes y competencias (CE LOMLOE y Clave). |
| **Ficha Técnica** | Espacio necesario, duración orientativa, materiales exactos y tipo de agrupación. |
| **Objetivos de Aprendizaje** | Diferenciados en componente Motor, Socioemocional y Cognitivo/Táctico. |
| **Desarrollo y Reglas** | Explicación secuencial, motivadora y sin eliminaciones traumáticas (juego activo continuo). |
| **Diagrama Espacial** | Esquema gráfico con la distribución de los alumnos, materiales y metas en pista. |
| **Medidas DUA (Inclusión)** | Nivel Verde (Apoyo/Simplificación) y Nivel Rojo (Desafío/Extensión). |
| **Preguntas de Debriefing** | 2 preguntas reflexivas para la asamblea final o vuelta a la calma (evaluación formativa). |
| **Seguridad y Prevención** | Puntos críticos para prevenir accidentes, choques o lesiones articulares. |

---

## 💡 Recomendaciones para la Puesta en Práctica

* **Plastificado / Fundas de Anillas:** Se recomienda imprimir las fichas en cartulina A4 o introducirlas en fundas plásticas en una carpeta clasificadora con separadores por ciclos.
* **El Alumnado Protagonista:** En el segundo y tercer ciclo, las fichas pueden entregarse directamente a un "Capitán o Portavoz de Grupo" para que el equipo gestione de forma autónoma la preparación del material y la comprensión de las normas.
