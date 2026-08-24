# ARGOS — Dossier de 12 escenarios completos

**Versión:** 0.1  
**Fecha:** 24 de agosto de 2026  
**Finalidad:** prototipo de entrenamiento; no evaluación profesional ni guía para intervenciones reales  
**Estado de los casos:** borrador investigativo pendiente de revisión por Guardia Civil, especialistas de cada ámbito, asesoría jurídica y comité ético

---

## 1. Cobertura de la primera ola

La selección cruza los cuatro ámbitos con las tres arquitecturas de decisión. De este modo se prueba el motor completo con 12 familias y 48 instancias A–D.

| Ámbito | ARGOS‑UMBRAL | ARGOS‑MENOS‑MALA | ARGOS‑MACRO |
|---|---|---|---|
| Seguridad Ciudadana | SC‑01 Luz en el caserío | SC‑02 Fiesta patronal | SC‑08 Menor en la feria |
| Tráfico | TR‑08 Sentido contrario | TR‑01 Curva sin visibilidad | TR‑04 Niebla en cadena |
| VioGén | VG‑10 La vecina escucha | VG‑01 No quiero denunciar | VG‑03 Tres versiones |
| SEPRONA | SP‑01 Humo en el barranco | SP‑02 Agua turbia | SP‑05 Rapaz inmóvil |

Los escenarios se inspiran en las arquitecturas publicadas de DISPUTE y LUCIFER y en métodos de decisión naturalística, pero sus textos, personajes, señales y alternativas son originales. No se presentan como réplicas ni administraciones de los instrumentos originales.

---

## 2. Reglas comunes de implementación

### 2.1 Estructura de puntuación

La calidad conductual se calcula sobre 80 puntos:

| Código | Dimensión | Máximo |
|---|---|---:|
| PS | Protección y seguridad | 20 |
| LP | Legalidad y proporcionalidad | 15 |
| CS | Conciencia situacional | 15 |
| GI | Gestión de incertidumbre e información | 15 |
| CC | Comunicación, coordinación y desescalada | 15 |
|  | **Calidad total Q** | **80** |

Después se añaden hasta 10 puntos por calibración de confianza y hasta 10 por tiempo. Las tablas usan el formato **PS/LP/CS/GI/CC = Q**. Las cifras son hipótesis de autoría y no baremos validados.

En escenarios con varios nodos, Q es la media ponderada indicada. La calibración compara la confianza declarada con Q/80. El tiempo nunca compensa una decisión de baja calidad y no se premian respuestas anteriores al tiempo mínimo de comprensión.

### 2.2 Presentación móvil

- Lienzo vertical de referencia: 390 × 844 píxeles.
- Entre cuatro y seis viñetas por escenario.
- Audio total objetivo: 25–40 segundos; el subtítulo reproduce literalmente el audio.
- Texto visible por viñeta: máximo 32 palabras, salvo tarjetas de información.
- Controles de al menos 48 × 48 píxeles.
- Alternativa accesible para cualquier interacción de arrastre.
- Aviso sensible previo en VioGén, lesiones, menores o fauna afectada.

### 2.3 Registro común

Todos los casos registran inicio, fin, reproducción de audio, apertura de tarjetas, primera y última selección, cambios, confirmación, confianza y salida. ARGOS‑MENOS‑MALA separa SAT, CT, DT y ComT. ARGOS‑UMBRAL registra la inyección en la que se produce la actuación. ARGOS‑MACRO conserva orden y coste de cada consulta.

### 2.4 Feedback

El feedback nunca muestra “apto/no apto”. Presenta:

1. puntuación provisional y confianza;
2. señales utilizadas y omitidas;
3. riesgos protegidos y costes asumidos;
4. razonamiento de las otras alternativas;
5. principio transferible;
6. acceso a una variante hermana sin efecto clasificatorio.

---

# Seguridad Ciudadana

## 3. SC‑01 — Luz en el caserío

### Ficha

| Campo | Contenido |
|---|---|
| Arquitectura | ARGOS‑UMBRAL, inspirada en la secuencia decisional de DISPUTE |
| Objetivo | Ajustar el momento de intervención cuando la localización, el riesgo inmediato y la fiabilidad de los avisos cambian. |
| Contexto GC | Vivienda rural aislada, cobertura irregular y apoyo demorado. |
| Duración | 135–165 segundos |
| Sensibilidad | Posible violencia en domicilio y presencia de menor; aviso previo. |
| Mecánica | Intervenir ahora o mantener protección y obtener una inyección más. |
| Estado | Puntuación piloto; referencia experta por confirmar. |

### Reparto y activos

- Fondo: camino rural nocturno y caserío visto desde distancia segura.
- Personajes: patrulla no identificable, comunicante telefónico, siluetas interiores no explícitas.
- Sonido: motor detenido, viento suave, radio con interferencia y un golpe amortiguado.
- No se muestran accesos tácticos, armas, matrículas, coordenadas ni procedimientos reservados.

### Guion audiovisual de la variante A

| Tiempo | Viñeta y animación | Audio y subtítulo literal |
|---:|---|---|
| 0–7 s | Mapa estilizado: dos viviendas dispersas con nombres de lugar ficticios. La marca del aviso oscila entre ambas. | **Centro:** “Aviso por gritos en un caserío. La llamada se cortó antes de confirmar la dirección.” |
| 7–14 s | La patrulla se detiene en un cruce; a lo lejos se ve luz en una vivienda. | **Compañera:** “Hay dos casas con nombre parecido. Solo una tiene luz.” |
| 14–20 s | Onda de audio del comunicante, sin imagen de la persona. | **Comunicante:** “Oí una discusión… después un golpe. No sé quién está dentro.” |

### Decisión de umbral

En cada inyección se muestran dos botones: **“Activar intervención prioritaria con lo disponible”** y **“Mantener protección, coordinar y obtener un dato más”**. La primera elección cierra el umbral clasificatorio; la información restante se reserva para el feedback.

| Punto | Nueva información exacta | Ventana | Vector si actúa en este punto |
|---|---|---:|---:|
| U1 | Dirección todavía ambigua, una luz y un único aviso incompleto. | 6–16 s | 14/10/8/7/10 = **49** |
| U2 | Se restablece la llamada: “Es la casa de la parra. Hay un niño; alguien acaba de pedir ayuda”. Coincide con la vivienda iluminada. | 6–18 s | 19/13/14/13/14 = **73** |
| U3 | Otro vecino confirma un vehículo habitual y oye un segundo golpe, pero no puede ver el interior. | 5–16 s | 17/13/13/12/13 = **68** |
| Sin actuar | Se mantiene únicamente coordinación y observación hasta agotar el escenario. | — | 8/8/10/9/11 = **46** |

La referencia provisional es U2. U1 puede resultar prematuro por la dirección ambigua; U3 añade corroboración, pero prolonga la exposición de una posible víctima. El panel podrá ampliar la ventana aceptable a U2–U3 si existe desacuerdo razonado.

### Confianza y feedback

Pregunta: **“Con la información disponible cuando decidiste, ¿qué confianza tienes en que elegiste un momento proporcionado?”** Control 0–100.

Feedback principal:

> La señal decisiva no es el dramatismo aislado del primer aviso, sino la convergencia entre localización, petición de ayuda y presencia de una persona vulnerable. Esperar puede ser una acción deliberada; deja de serlo cuando ya no aporta una reducción proporcional de incertidumbre.

Se muestran las señales **dirección confirmada**, **petición de ayuda**, **menor** y **corroboración**, así como el coste de actuar con una dirección dudosa.

### Variantes B–D

| Variante | Sustitución audiovisual e informativa | Cambio de referencia |
|---|---|---|
| B — Entorno | Lluvia intensa y camino parcialmente bloqueado. Audio nuevo: “El acceso norte no es transitable; la casa se alcanza por el desvío”. U2 añade que la llamada procede de la vivienda correcta. | U2 continúa siendo la referencia; se añade valor a coordinación y planificación de acceso seguro. |
| C — Recursos | Apoyo y cobertura son intermitentes. Audio nuevo: “La siguiente patrulla está lejos; la comunicación puede perderse al bajar al valle”. | U2–U3 se consideran intervalo plausible; actuar antes no elimina la necesidad de coordinación. |
| D — Contradicción | En U3, un segundo comunicante niega haber visto el supuesto objeto peligroso mencionado en una versión inicial. | La contradicción reduce certeza sobre el objeto, no sobre la petición de ayuda. Se penaliza cancelar toda respuesta por esa única rectificación. |

### Revisión necesaria

- Confirmar con personal de Seguridad Ciudadana qué señales permiten diferenciar verificación activa de demora injustificada.
- Revisión jurídica de las alternativas antes de asociarlas a cualquier actuación en domicilio.
- Entrevista cognitiva para asegurar que “intervención prioritaria” no se interpreta como una técnica concreta.

---

## 4. SC‑02 — Fiesta patronal

### Ficha

| Campo | Contenido |
|---|---|
| Arquitectura | ARGOS‑MENOS‑MALA, inspirada en LUCIFER |
| Objetivo | Reasignar la prioridad cuando un conflicto visible compite con riesgos periféricos menos llamativos. |
| Contexto GC | Celebración en municipio pequeño, multitud, recursos sanitarios limitados y coordinación local. |
| Duración | 140–175 segundos |
| Sensibilidad | Altercado, consumo de alcohol y persona indispuesta; aviso leve. |
| Mecánica | Dos elecciones forzadas, nueva información y compromiso final. |

### Reparto y activos

- Fondo: plaza ficticia con escenario musical, salida lateral y puesto sanitario.
- Personajes: dos grupos discutiendo, personal de organización, persona sentada en el suelo.
- Sonido: música amortiguada, público y mensajes breves de radio.
- Las alternativas describen prioridades, no técnicas de control de masas.

### Guion y decisión 1

| Tiempo | Viñeta | Audio y subtítulo literal |
|---:|---|---|
| 0–8 s | Plano alto de la plaza. Un grupo forma un círculo alrededor de dos personas que discuten. | **Centro:** “Dos personas se enfrentan junto al escenario. Hay unas ciento cincuenta personas y una salida lateral estrecha.” |
| 8–16 s | Un organizador señala el conflicto; otra persona pide paso al fondo. | **Organizador:** “La discusión está subiendo de tono. Sanidad está atendiendo otro aviso.” |
| 16–21 s | Aparece el botón **Ya puedo valorar**. | **Compañero:** “Somos la primera patrulla. El apoyo está de camino.” |

Tras pulsar **Ya puedo valorar**, se presentan dos alternativas neutrales:

| Opción inicial | Curso de acción | Vector provisional |
|---|---|---:|
| A | Priorizar contacto y desescalada en el foco de la discusión, solicitando a organización que vigile el resto. | 15/13/12/10/13 = **63** |
| B | Priorizar espacio seguro, salida y visión general antes de entrar en contacto con el foco. | 17/13/14/12/12 = **68** |

La decisión inicial pesa el 30 % de Q. Ambas son defendibles y la interfaz no muestra cuál puntúa más.

### Inyección y decisión 2

| Tiempo | Viñeta | Audio y subtítulo literal |
|---:|---|---|
| +0–8 s | El círculo se abre. Al fondo, una persona cae junto a la salida y varias personas se agachan. | **Asistente:** “¡No responde! La gente está bloqueando la salida.” |
| +8–13 s | Una de las personas del altercado empuja una valla, sin mostrar agresión explícita. | **Compañero:** “Tenemos dos focos y la salida empieza a cerrarse.” |

| Opción final | Curso de acción | Vector provisional |
|---|---|---:|
| A | Mantener la prioridad en el altercado para impedir su escalada y pedir a terceros que liberen la salida. | 15/12/11/9/12 = **59** |
| B | Reconfigurar la prioridad: abrir espacio seguro, activar asistencia y contener ambos focos mediante coordinación. | 19/13/14/13/15 = **74** |

La decisión final pesa el 70 % de Q. Se registra si la persona mantiene o revisa su primera elección y cuánto tarda en comprometerla.

### Telemetría y feedback

- SAT: aparición del botón hasta **Ya puedo valorar**.
- CT1 y CT2: primera selección de cada decisión.
- DT1 y DT2: confirmación.
- ComT: DT menos CT.
- Tiempo eficaz: SAT 5–16 s; CT2 5–18 s. No hay bonificación adicional por bajar de cinco segundos.

Feedback:

> La primera amenaza que atrae la atención no siempre sigue siendo la prioridad. Revisar la decisión cuando aparece una víctima potencial y una salida bloqueada es adaptación, no indecisión. La respuesta más robusta protege a la vez el espacio, la asistencia y la comunicación entre recursos.

### Variantes B–D

| Variante | Cambio jugable | Efecto en las alternativas |
|---|---|---|
| B — Entorno | Lluvia intensa desplaza a la multitud hacia soportales y estrecha todavía más la salida. Audio: “La gente se concentra bajo la cubierta”. | B gana peso en protección y conciencia situacional; A sigue siendo plausible si el foco escala. |
| C — Recursos | El recurso sanitario está ocupado fuera de la plaza. Audio: “La asistencia tardará; el equipo de organización tiene formación básica”. | Se exige un microbriefing claro; ambas opciones pierden puntos de coordinación si delegan sin confirmar. |
| D — Contradicción | La persona inicialmente señalada como agresora estaba intentando separar a otras dos. | Se penaliza mantener una atribución cerrada; el feedback enfatiza conducta observable y actualización, no apariencia o acusación inicial. |

### Revisión necesaria

- Validar que las alternativas sean realistas para una primera patrulla sin codificar tácticas de orden público.
- Comprobar que la persona indispuesta no funcione como pista excesivamente obvia.
- Revisar la equivalencia de densidad y dificultad entre variantes.

---

## 5. SC‑08 — Menor en la feria

### Ficha

| Campo | Contenido |
|---|---|
| Arquitectura | ARGOS‑MACRO |
| Objetivo | Seleccionar información de alto valor, organizar una búsqueda inicial y actualizar la descripción sin cierre prematuro. |
| Contexto GC | Feria de municipio pequeño con varias salidas y coordinación con organización y familia. |
| Duración | 150–180 segundos |
| Sensibilidad | Menor desaparecido; aviso previo no gráfico. |
| Mecánicas | Presupuesto de información, microbriefing y actualización de criterio. |

### Guion audiovisual

| Tiempo | Viñeta | Audio y subtítulo literal |
|---:|---|---|
| 0–7 s | Plano de feria con cuatro zonas identificadas por colores, sin mapa real. | **Centro:** “Un familiar no localiza a un menor desde hace unos seis minutos.” |
| 7–14 s | Familiar junto a un punto de información; se muestran dos descripciones diferentes en bocadillos. | **Familiar:** “Llevaba sudadera azul… creo. Estaba mirando las atracciones pequeñas.” |
| 14–20 s | Animación de cuatro salidas y flujo de personas. | **Organización:** “Hay cuatro salidas. Las cámaras no cubren todo el recinto.” |

### Nodo 1 — Presupuesto de información

La persona puede abrir **dos** tarjetas. Cada apertura consume una ficha visible.

| Tarjeta | Contenido al abrir | Valor pedagógico |
|---|---|---|
| Último punto confirmado | Hora y lugar donde una persona concreta vio al menor por última vez. | Crítico |
| Imagen más reciente | Fotografía tomada esa tarde, con ropa y objeto que porta. | Crítico |
| Antecedente familiar | Se perdió brevemente en otro evento dos años antes. | Bajo; puede anclar. |
| Discusión previa | Hubo una discusión familiar menor antes de llegar. | Distractor sensible. |
| Actividad preferida | Interés actual por un tipo de atracción situada en dos zonas. | Útil, pero no confirma ubicación. |

| Selección | Vector del nodo 1 |
|---|---:|
| Dos críticas | 18/13/15/15/13 = **74** |
| Una crítica y la útil | 16/13/13/12/12 = **66** |
| Una crítica y una de bajo valor | 14/12/11/10/11 = **58** |
| Ninguna crítica | 10/11/8/7/10 = **46** |

### Nodo 2 — Microbriefing

Se ordenan cuatro mensajes; el control accesible permite usar botones **Subir/Bajar**.

1. confirmar y difundir internamente la última descripción verificable;
2. asignar cobertura de salidas y último punto confirmado;
3. establecer canal de actualización con organización y familiar;
4. explorar explicaciones no confirmadas.

Orden de referencia: 1–2–3–4. Se acepta 2–1–3–4 con una pérdida mínima. Cualquier orden que sitúe rumores antes de descripción y salidas pierde GI y CC.

| Resultado | Vector del nodo 2 |
|---|---:|
| Orden de referencia | 19/14/15/14/15 = **77** |
| Intercambia los dos primeros | 18/14/14/14/15 = **75** |
| Un crítico queda en tercera posición | 15/13/12/11/12 = **63** |
| Los rumores encabezan | 11/11/9/8/10 = **49** |

### Nodo 3 — Actualización

Viñeta nueva: una fotografía de esa tarde confirma sudadera **verde**, no azul, y una pulsera luminosa. Pregunta: **“¿Qué actualizas primero?”**

| Opción | Respuesta | Vector del nodo 3 |
|---|---|---:|
| A | Sustituir la descripción por la evidencia reciente, conservar la discrepancia y comunicar el cambio a quienes buscan. | 19/14/15/15/15 = **78** |
| B | Mantener ambas descripciones como equivalentes para no descartar ninguna. | 15/13/11/10/12 = **61** |
| C | Mantener “azul” porque procede del familiar y usar la foto solo como apoyo. | 11/11/8/6/9 = **45** |

Pesos: nodo 1, 30 %; nodo 2, 35 %; nodo 3, 35 %.

### Feedback

> Bajo presión, la información más útil es la que reduce el espacio de búsqueda y puede comunicarse. Una descripción nueva no borra el historial: lo corrige y deja constancia de por qué cambió. La rapidez sin un dato verificable puede dispersar recursos.

### Variantes B–D

| Variante | Sustitución | Ajuste |
|---|---|---|
| B — Entorno | Cierre próximo y lluvia; dos salidas concentran el flujo. Audio: “Las atracciones cierran en diez minutos y la gente se dirige al aparcamiento”. | “Flujo de salidas” pasa a ser tarjeta útil de alto valor; el orden debe incorporar el cambio de densidad. |
| C — Recursos | Megafonía averiada y red móvil saturada. | El microbriefing exige un punto físico de actualización y confirmación; mensajes que dependen solo del móvil pierden CC. |
| D — Contradicción | La fotografía muestra ropa distinta y una persona afirma haber visto al menor con un adulto, sin poder describirlo. | Se puntúa actualizar la ropa y tratar el acompañante como hipótesis no confirmada, evitando amplificar una atribución alarmista. |

### Revisión necesaria

- Revisión de protección de menores y lenguaje con especialistas.
- Comprobar que ninguna tarjeta invita a culpabilizar a la familia.
- Ensayar la mecánica con participantes daltónicos: las zonas tendrán nombre e icono además de color.

---

# Tráfico

## 6. TR‑08 — Sentido contrario

### Ficha

| Campo | Contenido |
|---|---|
| Arquitectura | ARGOS‑UMBRAL, inspirada en DISPUTE |
| Objetivo | Escalar una respuesta de protección vial cuando varias fuentes incompletas convergen sin ofrecer identificación perfecta. |
| Contexto GC | Vía interurbana nocturna, enlaces múltiples y avisos móviles. |
| Duración | 130–165 segundos |
| Sensibilidad | Riesgo de colisión; no se muestran impactos. |
| Mecánica | Activar respuesta de riesgo elevado o mantener prealerta y verificar una inyección más. |

### Activos

- Mapa vial ficticio de tres enlaces, sin coordenadas reales.
- Iconos de llamadas y vehículos genéricos; ninguna matrícula completa.
- Sonido de radio, lluvia ligera y tráfico lejano.
- Las respuestas no describen bloqueos, persecuciones ni posiciones operativas concretas.

### Guion audiovisual de la variante A

| Tiempo | Viñeta | Audio y subtítulo literal |
|---:|---|---|
| 0–7 s | Mapa con dos llamadas separadas por varios kilómetros. | **Centro:** “Dos avisos hablan de un turismo claro circulando en dirección incompatible con la vía.” |
| 7–14 s | Las flechas de los comunicantes no coinciden. | **Centro:** “Una persona lo sitúa antes del enlace norte; la otra, después. Ninguna aporta matrícula completa.” |
| 14–20 s | Tráfico moderado; aparecen tres vehículos visualmente parecidos. | **Compañera:** “La descripción es común. Aún no tenemos imagen.” |

### Decisión de umbral

Botones: **“Activar respuesta coordinada de riesgo elevado y protección a usuarios”** o **“Mantener prealerta, proteger lo inmediato y verificar un dato más”**.

| Punto | Nueva información | Ventana | Vector si activa en este punto |
|---|---|---:|---:|
| U1 | Dos llamadas independientes, ubicaciones incompatibles y descripción genérica. | 6–16 s | 15/12/10/8/12 = **57** |
| U2 | Un tercer comunicante describe el mismo sentido anómalo y aporta un punto temporal compatible con la segunda llamada. | 6–18 s | 20/14/14/13/15 = **76** |
| U3 | Una cámara retrasada muestra un vehículo coincidente, pero la imagen tiene varios minutos. | 5–16 s | 18/14/13/12/14 = **71** |
| Sin activar | Conserva únicamente la verificación hasta agotar el escenario. | — | 8/9/9/8/11 = **45** |

Referencia provisional: U2. No exige certeza de matrícula cuando el patrón de fuentes independientes y la cronología convergen. U3 aumenta identificación, pero consume tiempo.

### Confianza y feedback

Pregunta: **“¿Qué confianza tienes en que escalaste la respuesta cuando el riesgo ya justificaba el coste de una falsa alarma?”** 0–100.

> En riesgos de alto impacto, la decisión puede apoyarse en convergencia y compatibilidad temporal sin esperar identificación perfecta. La respuesta debe conservar la incertidumbre: proteger y coordinar no significa afirmar que cada detalle del aviso sea correcto.

### Variantes B–D

| Variante | Cambio exacto | Cambio de referencia |
|---|---|---|
| B — Entorno | Noche, lluvia y entradas múltiples. Una llamada confunde el nombre del enlace, pero acierta un elemento visual único. | U2 continúa como referencia; aumenta el valor de la cronología frente al nombre verbal del lugar. |
| C — Recursos | Las cámaras llegan con retraso y las unidades próximas están ocupadas. | Se puntúa más la comunicación anticipada y la revisión continua; no se premia esperar pasivamente la imagen. |
| D — Contradicción | En U3 se identifica un turismo similar que circula correctamente, pero su cronología no explica dos de los avisos. | Cancelar toda hipótesis obtiene baja GI; la mejor respuesta separa “vehículo descartado” de “riesgo aún no resuelto”. |

### Revisión necesaria

- Validar con Agrupación de Tráfico la plausibilidad de la secuencia sin incluir tácticas sensibles.
- Pilotar si la segunda inyección ofrece suficiente convergencia sin hacer la respuesta obvia.
- Revisar la terminología “dirección incompatible” para comprensión nacional.

---

## 7. TR‑01 — Curva sin visibilidad

### Ficha

| Campo | Contenido |
|---|---|
| Arquitectura | ARGOS‑MENOS‑MALA, inspirada en LUCIFER |
| Objetivo | Equilibrar auxilio inmediato y prevención de un segundo siniestro cuando solo puede iniciarse una prioridad. |
| Contexto GC | Carretera secundaria, noche y visibilidad limitada. |
| Duración | 140–175 segundos |
| Sensibilidad | Persona herida sin imagen gráfica; aviso previo. |
| Mecánica | Dos prioridades forzadas antes y después de una inyección. |

### Guion y decisión 1

| Tiempo | Viñeta | Audio y subtítulo literal |
|---:|---|---|
| 0–8 s | Curva oscura; vehículo accidentado tras la salida y luces de otro coche detenido. | **Centro:** “Siniestro en una curva sin visibilidad. Hay al menos una persona fuera del vehículo.” |
| 8–16 s | Un testigo hace señales desde un punto parcialmente protegido. | **Testigo:** “Respira, pero no me contesta. Siguen pasando coches.” |
| 16–22 s | Aparece **Ya puedo valorar**. | **Compañero:** “La asistencia está avisada. El tramo aún no está protegido.” |

| Opción inicial | Prioridad | Vector |
|---|---|---:|
| A | Aproximarse primero a valorar a la persona mientras se pide al testigo que mantenga la advertencia. | 16/13/10/9/12 = **60** |
| B | Establecer primero protección del escenario y alerta eficaz, manteniendo contacto verbal con la víctima. | 19/14/15/13/14 = **75** |

La decisión inicial pesa 30 %. La referencia pública de la DGT para emergencias prioriza proteger, alertar y, después, socorrer; el caso introduce presión emocional para comprobar si esa prioridad se mantiene sin desatender a la víctima.

### Inyección y decisión 2

| Tiempo | Viñeta | Audio y subtítulo literal |
|---:|---|---|
| +0–7 s | Se oyen neumáticos aproximándose; la persona herida deja de responder a la voz. | **Testigo:** “Ya no responde. Viene otro vehículo por la curva.” |
| +7–13 s | Un icono confirma que la asistencia todavía tardará. | **Centro:** “Recursos en camino. No hay confirmación de que el tráfico haya reducido la velocidad.” |

| Opción final | Prioridad | Vector |
|---|---|---:|
| A | Iniciar valoración directa inmediata, manteniendo la protección actual con los medios disponibles. | 17/13/11/10/12 = **63** |
| B | Completar una protección mínima eficaz y pasar inmediatamente al auxilio coordinado. | 20/14/15/14/15 = **78** |

La decisión final pesa 70 %. No se instruyen maniobras concretas ni primeros auxilios; el objetivo es el orden de prioridades.

### Telemetría y feedback

- SAT eficaz: 6–18 s.
- CT2 eficaz: 5–16 s.
- Se registra cambio A→B, B→A o mantenimiento.

> La urgencia de la víctima es real, pero una escena que sigue generando riesgo puede producir más víctimas e impedir el auxilio. Proteger, alertar y socorrer no son fases aisladas: la protección mínima debe habilitar, no retrasar indefinidamente, la atención.

Fuente pública de apoyo: [DGT, respuesta PAS](https://www.dgt.es/muevete-con-seguridad/que-hacer-ante-un-accidente-de-trafico/).

### Variantes B–D

| Variante | Cambio jugable | Ajuste |
|---|---|---|
| B — Entorno | Niebla y calzada mojada reducen más la anticipación. | B obtiene el máximo de PS y CS; A conserva valor si ya existe protección verificable. |
| C — Recursos | Asistencia y mantenimiento tienen demora prolongada, pero llega otra patrulla en breve. | La coordinación y división de prioridades gana peso; una opción que no actualice a la unidad entrante pierde CC. |
| D — Contradicción | Un ocupante que se creía ausente puede haberse alejado o haber salido despedido. | Tras proteger la escena se abre una microdecisión de búsqueda visual versus atención focal; el feedback evita cerrar el número de víctimas prematuramente. |

### Revisión necesaria

- Revisión por personal de Tráfico y emergencias.
- Sustituir cualquier detalle que pueda contradecir normativa o equipamiento vigente.
- Ensayar el caso sin audio para asegurar equivalencia mediante subtítulos y señales visuales.

---

## 8. TR‑04 — Niebla en cadena

### Ficha

| Campo | Contenido |
|---|---|
| Arquitectura | ARGOS‑MACRO |
| Objetivo | Construir y actualizar una imagen operativa cuando los avisos describen partes distintas de un incidente múltiple. |
| Contexto GC | Colisiones en vía interurbana con niebla, comunicaciones saturadas y accesos limitados. |
| Duración | 155–180 segundos |
| Sensibilidad | Siniestro múltiple, sin representación de lesiones. |
| Mecánicas | Distribución de hipótesis, microbriefing y actualización. |

### Guion audiovisual

| Tiempo | Viñeta | Audio y subtítulo literal |
|---:|---|---|
| 0–7 s | Calzada cubierta por niebla; se ven luces detenidas a distintas distancias. | **Centro:** “Recibimos cuatro llamadas por colisiones en el mismo tramo. Hablan de dos, cuatro y hasta seis vehículos.” |
| 7–15 s | Mapa lineal con dos accesos y tres marcas no confirmadas. | **Centro:** “Dos llamadas podrían describir el mismo punto. Otra sitúa un golpe más adelante.” |
| 15–21 s | Indicador de visibilidad baja y canal saturado. | **Compañera:** “No podemos ver el final del incidente desde aquí.” |

### Nodo 1 — Hipótesis operativas

El participante reparte 100 puntos entre tres modelos. No se busca adivinar un número exacto, sino expresar incertidumbre.

- H1: un único núcleo y llamadas duplicadas;
- H2: dos núcleos próximos;
- H3: una secuencia extendida con vehículos fuera de la vista.

Referencia provisional inicial: H1 25, H2 50, H3 25. Se calcula distancia absoluta respecto de la distribución de referencia, pero ninguna hipótesis puede recibir cero sin justificación. La puntuación del nodo se transforma entre **42 y 76 Q** según calibración y apertura a alternativas.

### Nodo 2 — Microbriefing

Se eligen **tres** de seis elementos para un primer mensaje coordinador:

| Elemento | Clasificación |
|---|---|
| tramo y accesos confirmados | Crítico |
| visibilidad y riesgo de nuevas colisiones | Crítico |
| rango provisional de vehículos/personas, indicando incertidumbre | Crítico |
| color del primer vehículo visible | Bajo valor |
| interpretación cerrada de que todas las llamadas duplican el mismo hecho | Riesgo de cierre |
| identidad de un comunicante no implicado | Irrelevante para la primera coordinación |

Tres críticos: 19/14/15/15/15 = **78**. Dos críticos: **66**. Un crítico: **52**. Ninguno: **38**.

### Nodo 3 — Nueva evidencia

Viñeta: una llamada posterior comunica un vehículo fuera de la calzada, varios cientos de metros después del núcleo visible. El participante vuelve a distribuir 100 puntos.

Referencia provisional: H1 10, H2 35, H3 55. La mejor respuesta aumenta H3 sin convertir el nuevo aviso en certeza absoluta. Después elige una prioridad:

| Opción | Prioridad | Vector |
|---|---|---:|
| A | Actualizar el mensaje, ampliar la imagen del incidente y conservar verificación de ambos núcleos. | 20/14/15/15/15 = **79** |
| B | Mantener el plan inicial hasta comprobar visualmente el nuevo aviso. | 13/12/9/8/11 = **53** |
| C | Sustituir todo el modelo anterior por un único siniestro extendido. | 15/12/11/9/11 = **58** |

Pesos: hipótesis inicial 25 %, briefing 35 %, actualización y prioridad 40 %.

### Feedback

> Las cifras contradictorias pueden ser vistas parciales de un mismo sistema. Una imagen útil conserva rangos, fuentes y límites. Actualizar no significa aceptar sin reservas el último dato, sino cambiar el peso de las hipótesis y comunicar qué sigue sin confirmarse.

### Variantes B–D

| Variante | Cambio exacto | Ajuste |
|---|---|---|
| B — Entorno | Aparece mercancía dispersa y la visibilidad cae por momentos. | Se añade “peligro secundario no identificado” como elemento crítico del briefing; no se exige identificar la carga. |
| C — Recursos | Canal saturado: solo se permite un mensaje inicial de 20 segundos y un segundo mensaje posterior. | Se puntúa concisión, incertidumbre explícita y orden; detalles de bajo valor consumen presupuesto. |
| D — Contradicción | Una llamada que parecía duplicada procede en realidad de un vehículo fuera de la calzada. | La distribución final debe aumentar H3; el feedback muestra cómo una fuente aparentemente redundante puede ser decisiva. |

### Revisión necesaria

- Calibrar distribuciones de referencia con panel; no imponer falsos porcentajes de precisión.
- Validar que la tarea probabilística sea comprensible en menos de 25 segundos.
- Revisar lenguaje con Tráfico y coordinación de emergencias.

---

# VioGén

Los tres casos siguientes entrenan percepción y gestión de incertidumbre. No sustituyen la valoración policial del riesgo, el Sistema VioGén 2 ni los protocolos aplicables. Las alternativas definitivas deberán revisarse contra el Protocolo 2025 y cualquier actualización posterior.

## 9. VG‑10 — La vecina escucha

### Ficha

| Campo | Contenido |
|---|---|
| Arquitectura | ARGOS‑UMBRAL, inspirada en DISPUTE |
| Objetivo | Ajustar el umbral de respuesta ante indicios acústicos ambiguos, ausencia de respuesta y corroboración progresiva. |
| Contexto GC | Edificio en núcleo pequeño, primera patrulla y fuentes vecinales con acceso parcial. |
| Duración | 135–165 segundos |
| Sensibilidad | Posible violencia de género y menor; aviso sensible obligatorio. |
| Mecánica | Activar respuesta inmediata conforme al marco aplicable o continuar verificación protegida. |

### Reparto y activos

- Fondo: rellano genérico con tres puertas identificadas por símbolos ficticios.
- Personajes: dos vecinas mostradas por avatar, ocupantes nunca representados de forma explícita.
- Sonido: ascensor, televisión lejana, golpe amortiguado y llanto breve no realista.
- No se representa entrada en domicilio ni se instruyen técnicas de intervención.

### Guion audiovisual de la variante A

| Tiempo | Viñeta | Audio y subtítulo literal |
|---:|---|---|
| 0–7 s | Plano exterior del edificio y marcador del aviso. | **Centro:** “Una vecina comunica golpes y una discusión en la vivienda contigua. Después ha quedado en silencio.” |
| 7–14 s | Rellano; la puerta señalada no responde. | **Compañera:** “No responde nadie. Se oye una televisión, pero no sabemos de qué vivienda procede.” |
| 14–20 s | La primera comunicante habla desde su puerta. | **Vecina 1:** “Creo que era ahí. En este edificio el sonido se mueve mucho.” |

### Decisión de umbral

Botones: **“Activar respuesta inmediata conforme al marco aplicable”** o **“Mantener protección y obtener una comprobación más”**.

| Punto | Nueva información | Ventana | Vector si activa en este punto |
|---|---|---:|---:|
| U1 | Un único testimonio, acústica confusa, silencio y puerta sin respuesta. | 6–16 s | 14/10/9/8/11 = **52** |
| U2 | Una segunda vecina identifica la misma vivienda y refiere haber oído “para” y después a un menor llorando. | 6–18 s | 20/14/14/13/15 = **76** |
| U3 | Se establece una llamada no privada con una ocupante; dice estar bien, pero otra voz responde por ella y la comunicación termina. | 5–16 s | 19/14/14/13/14 = **74** |
| Sin activar | Continúa la verificación hasta agotar el escenario sin cambiar el nivel de respuesta. | — | 7/8/9/8/10 = **42** |

Referencia provisional: U2–U3. El panel debe decidir si ambas forman una ventana aceptable o si U2 es el punto preferente. La respuesta de una posible víctima en una comunicación no privada no se trata automáticamente como evidencia tranquilizadora.

### Confianza y feedback

> La incertidumbre acústica aconseja no confundir una primera impresión con certeza. Cuando aparecen corroboración independiente, una petición de cese y un menor, seguir acumulando datos puede aumentar el coste de la demora. Una manifestación obtenida sin privacidad debe interpretarse dentro del contexto, no aisladamente.

La persona declara confianza 0–100 y selecciona qué señal cambió su umbral: corroboración, menor, ausencia de respuesta, llamada no privada o ninguna.

### Variantes B–D

| Variante | Cambio exacto | Referencia provisional |
|---|---|---|
| B — Entorno | Edificio con acústica especialmente confusa; U2 identifica la planta, pero no la puerta. U3 aporta el número correcto mediante una segunda fuente. | U3; actuar sobre una puerta no confirmada pierde LP y GI. |
| C — Recursos | No se restablece la llamada y el titular no está localizable; apoyo especializado no inmediato. | U2–U3; la falta de recurso no convierte la espera en solución. Se puntúa coordinación proporcional. |
| D — Contradicción | La segunda vecina sitúa inicialmente el ruido en otra vivienda; una señal posterior corrige la localización y explica la confusión. | U3; se premia revisar la dirección sin descartar el riesgo global. |

### Revisión necesaria

- Revisión VioGén, jurídica, de protección de menores y de sensibilidad.
- Entrevistas cognitivas para detectar interpretaciones culpabilizadoras o estereotipos.
- No publicar puntuación experta hasta verificar cada alternativa con Protocolo 2025.

---

## 10. VG‑01 — No quiero denunciar

### Ficha

| Campo | Contenido |
|---|---|
| Arquitectura | ARGOS‑MENOS‑MALA, inspirada en LUCIFER |
| Objetivo | Equilibrar autonomía, vínculo y protección cuando una revelación parcial contiene indicadores de posible escalada. |
| Contexto GC | Consulta sanitaria en municipio rural y acceso demorado a recursos especializados. |
| Duración | 145–180 segundos |
| Sensibilidad | Violencia de género, control coercitivo y menor; aviso y salida rápida disponibles. |
| Mecánica | Dos cursos de acción imperfectos antes y después de una nueva revelación. |

### Guion y decisión 1

| Tiempo | Viñeta | Audio y subtítulo literal |
|---:|---|---|
| 0–8 s | Sala privada de un centro sanitario ficticio; no se muestran lesiones. | **Profesional sanitaria:** “Ha pedido hablar sin acompañante. Dice que su expareja controla sus mensajes y aparece sin avisar.” |
| 8–16 s | Bocadillo de texto de la mujer, sin voz dramatizada. | **Texto:** “No quiero denunciar. Solo quiero saber cómo hacer para que pare.” |
| 16–22 s | Iconos: vivienda aislada, menor con familiar y cierre del centro en 15 minutos. | **Compañera:** “Su hijo está hoy con un familiar. Ella teme que cualquier paso empeore la situación.” |

| Opción inicial | Curso de acción | Vector |
|---|---|---:|
| A | Iniciar ahora una respuesta protectora estructurada, explicando límites, pasos y opciones con claridad. | 18/14/12/12/13 = **69** |
| B | Priorizar conversación privada, plan de seguridad inmediato y vínculo antes de iniciar otros pasos. | 16/13/14/13/15 = **71** |

La decisión inicial pesa 30 %. En esta fase ambas alternativas protegen valores legítimos y la referencia puede ser un intervalo, no una única opción.

### Inyección y decisión 2

| Tiempo | Viñeta | Audio y subtítulo literal |
|---:|---|---|
| +0–8 s | La mujer entrega voluntariamente una captura; se ocultan nombres y direcciones. | **Texto:** “Sabe dónde estoy viviendo. Anoche dijo que iría aunque yo no quisiera.” |
| +8–14 s | Aparece un icono de llave y otro de ubicación, ambos marcados como información no verificada. | **Profesional sanitaria:** “Cree que conserva una llave y que conoce la ubicación temporal del menor.” |

| Opción final | Curso de acción | Vector |
|---|---|---:|
| A | Activar sin demora la respuesta y valoración estructuradas, manteniendo información clara, privacidad y participación de la mujer. | 20/15/14/14/15 = **78** |
| B | Prolongar el trabajo de vínculo antes de activar la respuesta, con medidas inmediatas limitadas y contacto posterior acordado. | 15/12/12/10/15 = **64** |

La decisión final pesa 70 %. La opción A no se redactará como imposición automática: debe incluir comunicación, dignidad y participación. La B conserva un valor relacional, pero asume más riesgo temporal tras la nueva información.

### Telemetría y feedback

- SAT 6–18 s; CT2 6–20 s.
- Cambio de elección y justificación elegida: seguridad, autonomía, menor, información no verificada o disponibilidad de recursos.
- Confianza 0–100 y dificultad 1–5.

> Respetar la autonomía no equivale a trasladar toda la carga de protección a la posible víctima. Cuando aparecen señales de localización, acceso y escalada, una respuesta estructurada puede ser compatible con explicar, escuchar y conservar su participación. El dato nuevo cambia el balance, aunque todavía requiera verificación.

Referencia pública: [Ministerio del Interior, VioGén 2 y Protocolo 2025](https://www.interior.gob.es/opencms/eu/detalle/articulo/Interior-disena-un-nuevo-modelo-de-respuesta-policial-a-la-violencia-de-genero/).

### Variantes B–D

| Variante | Cambio jugable | Ajuste |
|---|---|---|
| B — Entorno | Vivienda temporal en núcleo aislado y transporte limitado. | La continuidad de contacto y la accesibilidad real de recursos ganan peso en CC y PS. |
| C — Recursos | El recurso especializado no está disponible de inmediato; sí existe coordinación remota. | Se penaliza presentar “no hay especialista” como razón para no iniciar protección; se premia explicar límites sin prometer resultados. |
| D — Contradicción | No hay lesión visible y un mensaje reciente parece conciliador, pero revela conocimiento de una ubicación no compartida. | Se puntúa el patrón y el contexto, no la apariencia aislada del mensaje o la presencia de lesión. |

### Revisión necesaria

- Revisión obligatoria por especialistas VioGén y personas con perspectiva de víctima.
- Confirmar que las opciones no sugieren que la actuación dependa exclusivamente de formalizar denuncia.
- Comprobar accesibilidad emocional y funcionamiento del botón para abandonar el caso.

---

## 11. VG‑03 — Tres versiones

### Ficha

| Campo | Contenido |
|---|---|
| Arquitectura | ARGOS‑MACRO |
| Objetivo | Mantener hipótesis temporales abiertas, separar fuentes y actualizar una secuencia sin decidir credibilidad por estereotipos. |
| Contexto GC | Intervención en domicilio con relatos incompatibles y evidencia digital parcial. |
| Duración | 155–180 segundos |
| Sensibilidad | Posible violencia de género; no se muestran agresiones ni lesiones. |
| Mecánicas | Presupuesto de información, línea temporal y actualización de hipótesis. |

### Guion audiovisual

| Tiempo | Viñeta | Audio y subtítulo literal |
|---:|---|---|
| 0–7 s | Tres tarjetas neutrales: persona A, persona B y testigo C. | **Centro:** “Tres personas describen de forma distinta lo ocurrido durante la última hora.” |
| 7–15 s | Línea temporal con tres huecos. | **Persona A:** “La discusión empezó cuando volvió.” **Persona B:** “Yo ya estaba dentro.” |
| 15–22 s | El testigo señala el rellano, sin gesto acusatorio. | **Testigo C:** “Oí un golpe después de ver salir a alguien. No sé quién volvió a entrar.” |

### Nodo 1 — Dos consultas

| Tarjeta | Contenido | Valor |
|---|---|---|
| Conversación separada y condiciones de privacidad | Permite obtener secuencias sin influencia mutua y detectar necesidades inmediatas. | Crítico |
| Estado y seguridad actuales de todas las personas | Necesidades urgentes, menores, asistencia y posibilidad de separar el riesgo presente del relato histórico. | Crítico |
| Mensajes con hora visible | Aporta hitos, pero la hora del dispositivo puede no ser fiable. | Útil con cautela |
| Historial de conflictos vecinales del testigo | Puede sesgar y tiene baja utilidad inicial. | Bajo |
| Opinión del propietario sobre “quién suele decir la verdad” | Irrelevante y sesgada. | Distractor |

Dos críticas: **76 Q**. Una crítica y mensajes: **68 Q**. Una crítica y bajo valor: **57 Q**. Sin críticas: **40 Q**.

### Nodo 2 — Línea temporal

Se arrastran cinco hechos a tres zonas: **confirmado**, **declarado/no confirmado** y **desconocido**.

| Hecho | Clasificación provisional de referencia |
|---|---|
| Hora de la llamada registrada | Confirmado |
| Momento exacto del golpe | Declarado/no confirmado |
| Quién estaba dentro al comienzo | Declarado/no confirmado |
| Si alguien salió y volvió | Desconocido |
| Presencia actual de un menor comprobada visualmente | Confirmado |

Cada clasificación correcta aporta 20 % del nodo. Convertir un relato en hecho confirmado resta GI aunque coincida después con la evidencia.

### Nodo 3 — Evidencia que no encaja

Una captura voluntariamente aportada muestra un mensaje enviado antes de la hora declarada, pero el dispositivo tiene una diferencia horaria de 12 minutos respecto al registro de la llamada.

Pregunta: **“¿Cómo actualizas la secuencia?”**

| Opción | Actualización | Vector |
|---|---|---:|
| A | Conservar el mensaje como indicio, verificar el desfase y revisar qué relatos dependen de la hora exacta. | 18/15/15/15/14 = **77** |
| B | Usar la hora de la captura para decidir qué versión es correcta. | 11/10/9/6/10 = **46** |
| C | Descartar todos los relatos porque ninguno coincide por completo. | 9/9/8/7/9 = **42** |
| D | Ignorar la captura y mantener la primera secuencia. | 11/11/8/6/10 = **46** |

Pesos: consultas 30 %, línea temporal 35 %, actualización 35 %.

### Feedback

> Una contradicción no convierte automáticamente un relato en falso ni otro en verdadero. La tarea es separar fuente, hecho, interpretación y hora; comprobar seguridad actual; y actualizar solo aquello que el dato nuevo realmente puede cambiar.

### Variantes B–D

| Variante | Cambio exacto | Ajuste |
|---|---|---|
| B — Entorno | Varias habitaciones y familiares presentes dificultan privacidad. | La consulta sobre condiciones separadas se mantiene crítica; se añade coordinación del espacio como parte de CC. |
| C — Recursos | El testigo debe marcharse pronto y la conexión para verificar mensajes es inestable. | Se puntúa conservar información esencial y marcar lo no verificado, sin transformar urgencia en certeza. |
| D — Contradicción | Los mensajes contradicen parcialmente a las tres versiones y muestran que hubo dos discusiones distintas. | La respuesta de referencia divide la línea temporal en dos episodios y evita forzar un único relato total. |

### Revisión necesaria

- Validación por especialistas VioGén, jurídica y de entrevista.
- Análisis de sesgo: género, edad, nacionalidad, forma de hablar y emocionalidad no deben funcionar como pistas de credibilidad.
- Probar que la mecánica evalúa organización de evidencia, no conocimientos forenses especializados.

---

# SEPRONA

## 12. SP‑01 — Humo en el barranco

### Ficha

| Campo | Contenido |
|---|---|
| Arquitectura | ARGOS‑UMBRAL, inspirada en DISPUTE |
| Objetivo | Ajustar el momento de escalada cuando un indicio ambiental pequeño puede evolucionar hacia riesgo para personas y entorno. |
| Contexto GC | Barranco rural, viento variable, medios de extinción demorados y posible senderista. |
| Duración | 135–165 segundos |
| Sensibilidad | Incendio incipiente; no se muestran personas heridas ni fuego intenso. |
| Mecánica | Escalar protección y coordinación o mantener observación y verificación. |

### Activos y guion

- Fondo: ladera y barranco ficticios; vegetación genérica, sin revelar ubicación real.
- Capas: humo tenue, flecha de viento y sendero.
- Sonido: viento, aves y comunicación de centro.

| Tiempo | Viñeta | Audio y subtítulo literal |
|---:|---|---|
| 0–7 s | Columna pequeña de humo detrás de una loma. | **Centro:** “Aviso por humo en un barranco. El comunicante ya no tiene visión directa del punto.” |
| 7–14 s | El viento cambia y el humo desaparece unos segundos. | **Compañera:** “Puede ser una quema ya apagada, polvo o un foco pequeño. No vemos llama.” |
| 14–20 s | Mapa ficticio del sendero y dos accesos. | **Centro:** “Consta una ruta frecuentada, pero hoy no hay actividad organizada comunicada.” |

### Decisión de umbral

Botones: **“Escalar protección y coordinación por posible incendio”** o **“Mantener vigilancia segura y obtener una comprobación más”**.

| Punto | Nueva información | Ventana | Vector si escala |
|---|---|---:|---:|
| U1 | Humo pequeño, sin llama ni localización exacta. | 6–16 s | 14/12/10/9/12 = **57** |
| U2 | El viento aumenta; un vehículo vacío está en el inicio del sendero y el humo reaparece más oscuro. | 6–18 s | 20/14/14/13/15 = **76** |
| U3 | Un segundo aviso sitúa otro penacho próximo, sin confirmar si es el mismo foco visto desde otro ángulo. | 5–16 s | 18/14/14/12/14 = **72** |
| Sin escalar | Mantiene observación hasta agotar el escenario. | — | 8/9/10/9/10 = **46** |

Referencia provisional: U2. La presencia del vehículo no confirma una persona en riesgo, pero aumenta el coste potencial de la demora cuando converge con la evolución del humo y el viento.

### Feedback

> Una señal aislada puede admitir explicaciones inocuas. La escalada se vuelve más defendible cuando cambian simultáneamente evolución, exposición y capacidad de respuesta. Comunicar “posible persona” conserva la incertidumbre; comunicar “persona atrapada” la convertiría indebidamente en hecho.

Confianza 0–100 y pregunta adicional: **“¿Qué combinación cambió tu decisión?”** humo, viento, vehículo/sendero, segundo foco o ninguna.

### Variantes B–D

| Variante | Cambio exacto | Referencia |
|---|---|---|
| B — Entorno | El viento aumenta y cambia hacia viviendas dispersas. | U2; sube PS y CC de una escalada que mencione la nueva exposición. |
| C — Recursos | Los medios de extinción están demorados y la cobertura se pierde dentro del barranco. | U2; se valora coordinación temprana y planificación, sin convertir al participante en especialista de extinción. |
| D — Contradicción | Aparece un segundo penacho que podría ser polvo de una pista; una imagen posterior muestra que los fenómenos tienen colores y evolución distintos. | Se premia separar focos e hipótesis en lugar de fusionarlos o descartar ambos. |

### Revisión necesaria

- Revisión conjunta por SEPRONA, especialistas en incendios y emergencias.
- No puntuar técnicas de extinción ni aproximación que queden fuera del objetivo decisional.
- Calibrar si U2 aporta suficiente evidencia para una respuesta nacionalmente plausible.

---

## 13. SP‑02 — Agua turbia

### Ficha

| Campo | Contenido |
|---|---|
| Arquitectura | ARGOS‑MENOS‑MALA, inspirada en LUCIFER |
| Objetivo | Equilibrar medidas preventivas tempranas y verificación focal cuando una posible contaminación tiene costes asimétricos. |
| Contexto GC | Cauce rural, mortandad de peces, testimonios interesados y técnico distante. |
| Duración | 145–180 segundos |
| Sensibilidad | Fauna muerta sin imágenes realistas; aviso previo leve. |
| Mecánica | Dos alternativas imperfectas antes y después de conocer una exposición potencial. |

### Guion y decisión 1

| Tiempo | Viñeta | Audio y subtítulo literal |
|---:|---|---|
| 0–8 s | Cauce estilizado con agua turbia y tres peces representados como iconos. | **Centro:** “Aviso por peces muertos y agua turbia en un tramo de arroyo.” |
| 8–16 s | Dos fuentes: agricultor y senderista; flechas de lluvia reciente. | **Agricultor:** “Ha llovido fuerte; el agua baja así muchas veces.” **Senderista:** “Hay olor extraño.” |
| 16–22 s | Mapa ficticio con tres posibles aportes aguas arriba. | **Compañera:** “No sabemos si el origen es natural, accidental o deliberado. El técnico tardará.” |

| Opción inicial | Curso de acción | Vector |
|---|---|---:|
| A | Impulsar medidas preventivas amplias y coordinación inmediata, comunicando que el origen no está confirmado. | 18/13/12/11/14 = **68** |
| B | Aplicar protección limitada al punto y priorizar verificación del origen antes de ampliar medidas. | 16/14/14/14/12 = **70** |

La elección inicial pesa 30 %. B reduce coste de falsa alarma; A protege antes frente a un daño que podría extenderse.

### Inyección y decisión 2

| Tiempo | Viñeta | Audio y subtítulo literal |
|---:|---|---|
| +0–8 s | El mapa muestra una captación de uso local aguas abajo, marcada “situación por verificar”. | **Centro:** “Un ayuntamiento informa de una captación aguas abajo. No confirma si está activa hoy.” |
| +8–14 s | Llega una fotografía de otro punto afectado aguas arriba. | **Compañera:** “Hay otra mortandad antes de este tramo. El origen puede estar más extendido.” |

| Opción final | Curso de acción | Vector |
|---|---|---:|
| A | Ampliar protección y coordinación preventiva de forma proporcionada, conservando muestreo y verificación del origen. | 20/14/15/14/15 = **78** |
| B | Mantener el alcance inicial hasta confirmar actividad de la captación y naturaleza de la sustancia. | 14/13/12/11/12 = **62** |

La decisión final pesa 70 %. “Ampliar” no contiene instrucciones sobre cierres, comunicaciones públicas o toma de muestras; esas medidas deben definirse con personal competente.

### Telemetría y feedback

- SAT 6–18 s; CT2 6–20 s; cambios y ComT.
- Confianza 0–100 y dificultad 1–5.

> Las medidas preventivas tienen costes, pero el balance cambia cuando aparece una vía plausible de exposición y un segundo punto afectado. La respuesta sólida protege sin presentar como hecho la toxicidad, la actividad de la captación o la autoría.

Referencia institucional de contexto: la Guardia Civil describe el análisis de aguas contaminadas y vertidos como uno de los apoyos científicos a investigaciones del SEPRONA en su página de [Criminalística](https://web.guardiacivil.es/es/institucional/conocenos/especialidades/InvestigacionCientifica/index.html).

### Variantes B–D

| Variante | Cambio jugable | Ajuste |
|---|---|---|
| B — Entorno | Lluvia reciente aumenta turbidez y caudal. | La turbidez pierde valor diagnóstico; la distribución de fauna afectada gana GI. |
| C — Recursos | Técnico y laboratorio están distantes; existe coordinación telefónica y material de protección limitado. | Se valora preservar opciones y comunicar límites; se penaliza improvisar una identificación. |
| D — Contradicción | Aparece otro punto afectado aguas arriba, pero una instalación inicialmente señalada queda aguas abajo de ambos. | Se premia revisar la hipótesis causal y evitar atribución prematura a la instalación visible. |

### Revisión necesaria

- Revisión SEPRONA, ambiental, sanitaria y jurídica.
- Confirmar que ninguna alternativa sugiera manipulación de sustancias o fauna sin medios adecuados.
- Panel separado para plausibilidad de daños, atribución y proporcionalidad de medidas.

---

## 14. SP‑05 — Rapaz inmóvil

### Ficha

| Campo | Contenido |
|---|---|
| Arquitectura | ARGOS‑MACRO |
| Objetivo | Priorizar información segura, mantener varias causas y actualizar la hipótesis sin destruir evidencia ni aumentar exposición. |
| Contexto GC | Zona cinegética rural, varias aves afectadas y apoyo científico demorado. |
| Duración | 150–180 segundos |
| Sensibilidad | Fauna afectada; iconografía no realista y aviso previo. |
| Mecánicas | Presupuesto de información, hipótesis y orden de prioridades. |

### Guion audiovisual

| Tiempo | Viñeta | Audio y subtítulo literal |
|---:|---|---|
| 0–7 s | Silueta de rapaz inmóvil junto a una pista, representada sin detalle. | **Centro:** “Un senderista localiza una rapaz inmóvil junto a una pista.” |
| 7–14 s | Aparecen otros dos marcadores próximos. | **Senderista:** “He visto otra más adelante. No las he tocado.” |
| 14–21 s | Iconos de zona cinegética, tendido y explotación agrícola. | **Compañera:** “Puede ser enfermedad, trauma, exposición accidental o una sustancia. Hay varias fuentes posibles.” |

### Nodo 1 — Presupuesto de información

Se eligen dos tarjetas:

| Tarjeta | Contenido | Valor |
|---|---|---|
| Patrón espacial y estado observado a distancia | Número, separación y signos visibles sin manipular. | Crítico |
| Riesgo de acceso de personas o animales domésticos | Senderos, viviendas y tránsito inmediato. | Crítico |
| Fotografía y ubicación original del comunicante | Aporta referencia temporal y preserva contexto. | Útil alto |
| Opinión de un titular cinegético sobre la causa | Fuente interesada; útil después, no diagnóstica. | Bajo inicial |
| Rumor local sobre conflictos entre fincas | Distractor atribucional. | Muy bajo |

Dos críticas: **77 Q**. Una crítica y útil alta: **70 Q**. Una crítica y bajo valor: **57 Q**. Sin críticas: **40 Q**.

### Nodo 2 — Distribución de hipótesis

El participante reparte 100 puntos:

- H1: exposición a sustancia tóxica o contaminación secundaria;
- H2: proceso infeccioso o natural;
- H3: trauma, colisión o electrocución;
- H4: otra causa todavía no representada.

Referencia inicial del prototipo: 35/25/25/15. Se premia reservar probabilidad para alternativas y no atribuir autoría. El nodo oscila entre 42 y 76 Q según distancia a la referencia y ausencia de cierre extremo.

### Nodo 3 — Cebo sospechoso

Viñeta: a varios metros aparece un objeto compatible con cebo, pero no puede conocerse su antigüedad ni relación con las aves.

Primero se redistribuyen hipótesis. Referencia: 60/15/15/10. Después se ordenan prioridades:

1. proteger a personas y animales de una posible exposición;
2. preservar escena, ubicación y trazabilidad sin manipulación innecesaria;
3. coordinar apoyo especializado y comunicar incertidumbres;
4. formular y contrastar hipótesis de origen y autoría.

| Orden | Vector |
|---|---:|
| 1–2–3–4 | 20/15/15/15/15 = **80** |
| 2–1–3–4 | 19/15/14/15/15 = **78** |
| Investigación de autoría antes de protección | 11/11/9/9/10 = **50** |
| Manipulación o conclusión causal inmediata | 8/8/7/5/8 = **36** |

Pesos: información 30 %, hipótesis 30 %, actualización/prioridades 40 %.

### Feedback

> Un objeto sospechoso aumenta una hipótesis, pero no demuestra relación causal ni autoría. La prioridad es reducir exposición, conservar contexto y facilitar una comprobación especializada. La buena actualización cambia probabilidades sin borrar alternativas todavía posibles.

### Variantes B–D

| Variante | Cambio exacto | Ajuste |
|---|---|---|
| B — Entorno | Hay animales domésticos y un sendero próximo. | “Riesgo de acceso” se vuelve crítica; protección encabeza necesariamente el orden. |
| C — Recursos | El laboratorio no puede recoger de inmediato y se pierde cobertura en la zona. | Se puntúa preservar trazabilidad y acordar coordinación, no improvisar análisis. |
| D — Contradicción | El objeto sospechoso parece reciente, pero una fotografía anterior muestra una de las aves ya afectada antes de que apareciera. | La distribución final reduce la relación causal directa y considera más de un proceso o episodio. |

### Revisión necesaria

- Revisión SEPRONA, veterinaria, toxicología y cadena de custodia.
- Sustituir cualquier instrucción que pueda fomentar contacto físico con fauna o sustancias.
- Pilotar si el control probabilístico añade comprensión o carga innecesaria.

---

## 15. Matriz de producción audiovisual

Los 12 casos pueden producirse con una biblioteca común y capas variables:

| Lote | Fondos | Personajes/avatares | Objetos/capas | Audio ambiente |
|---|---:|---:|---:|---:|
| Seguridad Ciudadana | 3 | 9 | 14 | 3 |
| Tráfico | 3 | 6 | 16 | 3 |
| VioGén | 3 | 8 | 12 | 2 |
| SEPRONA | 3 | 5 | 18 | 3 |
| **Total sin deduplicar** | **12** | **28** | **60** | **11** |

Fondos rurales, mapas, radio, climatología y componentes de interfaz son reutilizables. Las variantes B–D se implementan mediante capas de clima, recursos, nueva fuente y evidencia contradictoria, no creando 48 vídeos independientes.

### Primera priorización de producción

1. SC‑01, TR‑01, VG‑01 y SP‑02 para probar una familia por ámbito.
2. SC‑02, TR‑08, VG‑10 y SP‑01 para completar las arquitecturas DISPUTE/LUCIFER.
3. SC‑08, TR‑04, VG‑03 y SP‑05 para incorporar mecánicas macrocognitivas más complejas.

---

## 16. Campos de contenido y telemetría

Cada instancia A–D se almacenará con:

- `scenario_family_id`, `variant_id` y versión inmutable;
- `domain`, `ndm_architecture`, objetivo y sensibilidad;
- procedencia científica y estado de derechos;
- viñetas, audio, subtítulos y descripción alternativa;
- nodos, opciones, reglas de salto y pesos;
- vector PS/LP/CS/GI/CC por resultado;
- ventanas de comprensión y respuesta;
- referencia experta, intervalo aceptable y desacuerdo;
- estado de revisión jurídica, operativa, ética y de accesibilidad;
- SAT, CT, DT, ComT, umbral, consultas, orden, cambios y confianza;
- fórmula y versión de puntuación.

Las respuestas clasificatorias conservan siempre la versión publicada. Un cambio de texto, audio, alternativa o puntuación crea una versión nueva.

---

## 17. Criterios para considerar un escenario listo

Un caso no pasa de borrador a piloto hasta cumplir todos los puntos:

1. objetivo único observable;
2. duración mediana de 120–180 segundos en prueba de usabilidad;
3. comprensión del enunciado por al menos el 90 % de la muestra cognitiva;
4. alternativas plausibles y redactadas con longitud y tono equivalentes;
5. ausencia de una pista estética o lingüística que revele la opción de mayor puntuación;
6. revisión de pertinencia por el ámbito correspondiente;
7. revisión jurídica y normativa fechada;
8. revisión de sesgos, dignidad y sensibilidad;
9. audio, subtítulos y alternativa no auditiva equivalentes;
10. referencia experta expresada como distribución cuando exista desacuerdo;
11. funcionamiento offline y recuperación tras cierre accidental;
12. prueba de equivalencia inicial entre variantes antes de compararlas en ranking.

### Panel y piloto

- 5–7 revisores por familia cuando sea posible, con valoración independiente previa.
- Selección por conocimiento relevante, no solo por años de experiencia.
- Entrevistas cognitivas con 8–12 participantes repartidos entre alumnado y agentes en activo.
- Piloto de dificultad y tiempos con 20–30 participantes antes de fijar puntuaciones.
- Retirada inmediata si una actualización normativa invalida el feedback.

---

## 18. Fuentes de construcción

- Tejeiro et al. (2023), [DISPUTE y momento de acción](https://doi.org/10.1016/j.paid.2023.112398).
- Shortland, Thompson y Alison (2020), [LUCIFER](https://doi.org/10.3389/fpsyg.2020.01817).
- van den Heuvel, Alison y Power (2014), [estrategias frente a incertidumbre](https://doi.org/10.1007/s10111-012-0241-8).
- Harris et al. (2017), [decisión policial naturalística bajo amenaza](https://doi.org/10.1080/00140139.2016.1260165).
- Bennell et al. (2021), [desarrollo de escenarios críticos basado en evidencia](https://doi.org/10.1108/PIJPSM-02-2020-0017).
- Guardia Civil, [Seguridad Ciudadana](https://web.guardiacivil.es/es/institucional/conocenos/especialidades/Seguridad_Ciudadana/).
- Ministerio del Interior, [VioGén 2 y Protocolo 2025](https://www.interior.gob.es/opencms/eu/detalle/articulo/Interior-disena-un-nuevo-modelo-de-respuesta-policial-a-la-violencia-de-genero/).
- DGT, [respuesta PAS ante un siniestro](https://www.dgt.es/muevete-con-seguridad/que-hacer-ante-un-accidente-de-trafico/).
- Guardia Civil, [apoyo de Criminalística a investigaciones ambientales](https://web.guardiacivil.es/es/institucional/conocenos/especialidades/InvestigacionCientifica/index.html).

---

## 19. Resultado de esta fase

El dossier deja especificadas 12 familias, una variante A íntegramente guionizada y tres variaciones funcionales por familia: **48 instancias jugables**. Las cifras de puntuación, ventanas temporales y referencias son deliberadamente provisionales. Pueden implementarse en el prototipo para probar interacción, pero no utilizarse como baremo de investigación hasta completar la validación descrita.
