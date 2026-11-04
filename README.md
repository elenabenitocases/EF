# Catálogo de recursos de educación física para educación primaria (1.º a 6.º)
**Marco pedagógico:** LOMLOE (Real Decreto 157/2022) | **Enfoque:** competencial, inclusivo (DUA), lúdico, cooperativo y vivencial  
**Sitio web público (GitHub Pages):** [https://elenabenitocases.github.io/EF/](https://elenabenitocases.github.io/EF/)

---

## 🎯 Presentación del proyecto

Este recurso ha sido diseñado específicamente para maestras y maestros de educación física que necesitan disponer a mano de un catálogo estructurado, práctico, competencial y de consulta rápida con actividades, juegos y situaciones de aprendizaje para los **seis cursos de la etapa de educación primaria**, complementado con **tres espacios temáticos especializados**.

El sistema combina:
1. **27 fichas didácticas en formato Markdown:** organizadas por ciclos y áreas temáticas, listas para imprimir, editar o integrar en las programaciones de aula.
2. **Rúbricas de evaluación competencial en cada ficha:** con 4 niveles de desempeño (en proceso, básico, conseguido y avanzado) y criterios observables.
3. **Visor web interactivo e imprimible en HTML (`catalogo_fichas_imprimibles.html` / `index.html`):** permite filtrar instantáneamente por botones de pestaña, desplegables por ciclo o bloque de saberes básicos y buscador por palabra clave. Incluye impresión optimizada en formato **A4** (hoja individual o selección completa con salto de página limpio).
4. **Tres espacios temáticos monográficos:**
   * **Espacio de juegos cooperativos:** dinámicas de cohesión de grupo, interdependencia positiva y resolución compartida de retos sin eliminaciones.
   * **Espacio de atletismo escolar:** carreras de relevos y vallas con enfoque Fórmula 1, saltos en progresión y lanzamientos de precisión con vortex.
   * **Espacio de expresión corporal:** mimo, dramatización gestual, teatro de sombras corporales y creación de flashmobs escolares.
5. **Matriz curricular completa (`00_MATRIZ_CURRICULAR_LOMLOE.md`):** vinculación explícita con competencias clave, competencias específicas del área (CE1 a CE5) y saberes básicos.
6. **Plantilla modelo (`PLANTILLA_FICHA_EN_BLANCO.md`):** para incorporar nuevas actividades manteniendo la homogeneidad técnica y evaluativa.

---

## 📂 Estructura de carpetas y ficheros

```
d:\Educación Física Primaria\
│
├── README.md                                    <- Guía general de uso y presentación
├── 00_MATRIZ_CURRICULAR_LOMLOE.md               <- Mapa curricular LOMLOE, competencias y progresión
├── PLANTILLA_FICHA_EN_BLANCO.md                 <- Plantilla editable con rúbrica para nuevas fichas
├── catalogo_fichas_imprimibles.html             <- Visor interactivo e impresión profesional A4 (27 fichas)
├── index.html                                   <- Archivo de inicio para la web pública en GitHub Pages
│
├── 01_FICHAS_1_CICLO_1_Y_2/                     <- Recursos para 1.º y 2.º de primaria (con rúbricas)
│   ├── Ficha_1C_01_El_Zoologico_en_Movimiento.md       (Bloque C: HMB y cuento motor)
│   ├── Ficha_1C_02_Los_Guardianes_del_Tesoro.md        (Bloque C: lateralidad y esquema corporal)
│   ├── Ficha_1C_03_El_Viaje_del_Paracaidas_Magico.md   (Bloque D: cooperación y sincronización)
│   ├── Ficha_1C_04_Cazadores_de_Estrellas_y_Cometas.md (Bloque C: lanzamiento y óculo-manual)
│   ├── Ficha_1C_05_El_Museo_de_las_Esculturas_Sonoras.md (Bloque E: expresión corporal y ritmo)
│   └── Ficha_1C_06_El_Bosque_Sensorial_y_Huellas.md    (Bloque F y A: naturaleza y salud)
│
├── 02_FICHAS_2_CICLO_3_Y_4/                     <- Recursos para 3.º y 4.º de primaria (con rúbricas)
│   ├── Ficha_2C_01_Circuito_Habilidades_Combinadas.md  (Bloque C: HMB combinadas y enlaces)
│   ├── Ficha_2C_02_Juegos_Tradicionales_del_Mundo.md   (Bloque E y D: cultura motriz - Mbube)
│   ├── Ficha_2C_03_Predeporte_Colpbol_Iniciacion.md    (Bloque C y D: deporte de golpeo e invasión)
│   ├── Ficha_2C_04_Acrosport_Figuras_Basicas.md        (Bloque E: circo, figuras y apoyos seguros)
│   ├── Ficha_2C_05_Orientacion_Mapa_Colegio.md         (Bloque F: croquis escolar y balizas)
│   └── Ficha_2C_06_Calentamiento_y_Salud_Postural.md   (Bloque A y B: calentamiento y mochilas)
│
├── 03_FICHAS_3_CICLO_5_Y_6/                     <- Recursos para 5.º y 6.º de primaria (con rúbricas)
│   ├── Ficha_3C_01_Deporte_Alternativo_Datchball.md    (Bloque C y D: pelota viva y autoarbitraje)
│   ├── Ficha_3C_02_Ultimate_Frisbee_Invasion.md        (Bloque C y D: disco volador sin contacto)
│   ├── Ficha_3C_03_Coreografia_Danza_Urbana.md         (Bloque E: flashmob, compás de 8 tiempos)
│   ├── Ficha_3C_04_Orientacion_Score_Urbano_Natural.md (Bloque F: estrategia score y tiempo)
│   ├── Ficha_3C_05_Condicion_Fisica_Limpia_Saludable.md(Bloque A: frecuencia cardíaca y RPE)
│   └── Ficha_3C_06_Escape_Room_Motor_Cooperativo.md    (Bloque D y C: retos motrices y enigmas)
│
├── 04_ESPACIO_JUEGOS_COOPERATIVOS/              <- Espacio monográfico de cooperación
│   ├── Guia_Didactica_Juegos_Cooperativos.md           (Principios pedagógicos y estructura)
│   ├── Rubrica_Evaluacion_Cooperativa.md               (Instrumento de evaluación integral)
│   ├── Ficha_COOP_01_El_Rio_de_Lava_Solidario.md       (Cruce cooperativo sobre colchonetas)
│   ├── Ficha_COOP_02_El_Nudo_Humano_y_la_Red.md        (Resolución motriz y comunicación)
│   └── Ficha_COOP_03_Transporte_Gigante_de_la_Tierra.md(Transporte colectivo con fitball y picas)
│
├── 05_ESPACIO_ATLETISMO_ESCOLAR/                <- Espacio monográfico de atletismo formativo
│   ├── Guia_Didactica_Atletismo_Escolar.md             (Enfoque lúdico del atletismo de base)
│   ├── Rubrica_Evaluacion_Atletismo_Escolar.md         (Rúbrica técnica y socioemocional)
│   ├── Ficha_ATLE_01_Formula_1_Relevos_con_Vallas.md   (Circuito perimetral de velocidad y relevos)
│   ├── Ficha_ATLE_02_Lanzamiento_de_Precision_Vortex.md(Parábola a 45º y protocolo de tiro)
│   └── Ficha_ATLE_03_Saltos_en_Progresion_Multisaltos.md(Batida unipodal y amortiguación articular)
│
└── 06_ESPACIO_EXPRESION_CORPORAL/               <- Espacio monográfico de expresión y danza
    ├── Guia_Didactica_Expresion_Corporal.md            (Progresión de desinhibición a la escena)
    ├── Rubrica_Evaluacion_Expresion_Corporal.md        (Rúbrica de expresión, ritmo y público)
    ├── Ficha_EXPR_01_El_Viaje_de_las_Emociones_y_Mimo.md(Objetos invisibles y pasillo de emociones)
    ├── Ficha_EXPR_02_Teatro_de_Sombras_y_Siluetas.md   (Luz, pantalla blanca y figuras compuestas)
    └── Ficha_EXPR_03_Coreografia_Flashmob_de_Centro.md (Partitura motriz de 32 tiempos)
```

---

## 🖨️ ¿Cómo imprimir las fichas?

El visor `catalogo_fichas_imprimibles.html` (y la web en `index.html`) incluye reglas CSS `@page { size: A4 portrait; }` diseñadas para impresión directa:

1. **Acceso directo en la web:** abre [https://elenabenitocases.github.io/EF/](https://elenabenitocases.github.io/EF/).
2. **Impresión de una ficha suelta:** pulsa el botón `🖨️ Imprimir esta ficha` situado en la cabecera de la ficha elegida. El sistema oculta al instante el resto y abre el cuadro de impresión para obtener esa hoja única en A4.
3. **Impresión por ciclo o temática:**
   * Utiliza los botones de acceso rápido superiores (`🧒 1.er ciclo`, `🏃 2.º ciclo`, `⚽ 3.er ciclo`, `🤝 Juegos cooperativos`, `👟 Atletismo escolar`, `🎭 Expresión corporal`).
   * Pulsa el botón verde superior `🖨️ Imprimir selección / todo`.
   * En el diálogo de la impresora selecciona **Guardar como PDF** o tu dispositivo de impresión. Cada ficha se imprimirá en una página limpia sin cortes de contenido.

---

## 📋 Estructura homogénea de cada ficha

Cada una de las 27 fichas cuenta con nueve apartados estandarizados:

| Apartado | Contenido |
| :--- | :--- |
| **1. Cabecera y metadatos** | Ciclo recomendado, código identificativo, bloque de saberes y competencias (CE LOMLOE y clave). |
| **2. Ficha técnica operativa** | Espacio necesario, duración, material inventariable y tipo de agrupación (sin exclusión). |
| **3. Objetivos de aprendizaje** | Formulados en tres dimensiones: motriz, socioemocional y cognitivo o táctico. |
| **4. Dinámica y reglas** | Secuencia didáctica de fácil explicación en pista, con juego activo y continuo. |
| **5. Disposición espacial** | Diagrama visual en arte ASCII para organizar el espacio y la colocación del material. |
| **6. Medidas DUA e inclusión** | Doble nivel de personalización: verde (apoyo/simplificación) y rojo (desafío/extensión). |
| **7. Preguntas de reflexión (debriefing)** | Dos preguntas orientadas a la asamblea final para favorecer la toma de conciencia del aprendizaje. |
| **8. Seguridad y prevención** | Advertencias preventivas sobre calzado, colisiones o cuidado articular. |
| **9. Rúbrica competencial** | Tabla con descriptores en 4 niveles (en proceso, básico, conseguido y avanzado) para evaluación formativa. |

---

## 💡 Recomendaciones para la puesta en práctica

* **Plastificado y anillas:** para uso diario en el gimnasio o patio se recomienda plastificar las fichas o archivarlas con fundas transparentes en una carpeta clasificadora con pestañas por ciclo y espacio.
* **Roles de liderazgo compartido:** en segundo y tercer ciclo, se sugiere entregar la ficha a un portavoz de equipo para que los propios alumnos autogestionen la distribución del material, lean el diagrama y expliquen la dinámica al grupo.
