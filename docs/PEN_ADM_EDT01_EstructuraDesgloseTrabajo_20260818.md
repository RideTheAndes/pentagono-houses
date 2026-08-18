# PEN — EDT N.° 01 · Estructura de Desglose de Trabajo (EDT/WBS)

**Proyecto Pentágono (nombre provisional) — 5 viviendas, Vereda La Trinidad, Duitama, Boyacá**

| | |
|---|---|
| **Documento** | PEN_ADM_EDT01_EstructuraDesgloseTrabajo_20260818 |
| **Fecha** | 18 de agosto de 2026 |
| **Versión** | 1.0 — línea base para discusión en la próxima reunión de socios |
| **Insumo** | Acta N.° 01 — Primera reunión de socios (17/08/2026), decisiones D-01 a D-12 y acciones HI-1…HI-15, HE-1…HE-13, S-1…S-14, MM-1…MM-7 |
| **Alcance** | Desde la idea hasta la liquidación del contrato de cuentas en participación y el vencimiento de las garantías posventa |
| **Elaboró** | Gerencia de desarrollo (documento de trabajo) |

---

## 0. CÓMO LEER ESTE DOCUMENTO

### 0.1 Las tres etiquetas

Todo lo que aparece aquí está clasificado con una de estas tres etiquetas. **No las ignore: son la diferencia entre lo que lo puede meter en un problema legal y lo que es solo una opinión mía.**

| Etiqueta | Significado |
|---|---|
| **[RL] Requisito legal** | Lo exige una norma. Si no se cumple, hay sanción, nulidad, negativa de un trámite o responsabilidad personal. No es negociable. |
| **[PM] Práctica de mercado** | No lo exige la ley, pero así se hace en el sector y el mercado (bancos, notarías, compradores, inmobiliarias) lo espera. Apartarse tiene costo comercial, no jurídico. |
| **[RE] Recomendación** | Criterio mío, de gerencia. Puede discutirse y descartarse con argumentos. Lo marco para que ustedes sepan qué están discutiendo. |

### 0.2 Las marcas de verificación

| Marca | Significado |
|---|---|
| **⚠ VERIFICAR** | Dato que **no puedo darles con certeza** y que debe confirmarse ante la entidad que indico. La normativa colombiana cambia, y el POT de Duitama es norma local que solo conoce con precisión la Secretaría de Planeación y la Curaduría Urbana de Duitama. |
| **≈ ORDEN DE MAGNITUD** | Cifra de referencia para dimensionar, **no** para presupuestar. Debe reemplazarse por cotización real antes de tomar decisiones de plata. |
| **🔴 MATA-PROYECTO** | Punto que, si se responde mal, **detiene el proyecto**. No se sigue gastando hasta resolverlo. |

### 0.3 Numeración

`FASE (1) → SUBFASE (1.1) → ACTIVIDAD (1.1.1) → PASO (1.1.1.1)`

Esta numeración es **estable**. Cuando se cargue el tablero de seguimiento en Slack/Drive, cada tarea se referencia por su código (ej.: "3.2.4 sigue abierta"). No se renumera; si algo se agrega después, se agrega al final de su nivel.

### 0.4 Los cuatro roles (según Acta N.° 01)

| Código | Rol | Persona | Alcance |
|---|---|---|---|
| **DAO** | Dirección arquitectónica y de obra | Hugo Ignacio | Diseño, presupuesto, dirección de obra, curaduría, relación con Rosa |
| **JUR** | Jurídico | Hugo Ernesto | Contratos, licencias, PH, escrituración, relación con la contadora |
| **COM** | Marketing, diseño y comercial | Sergio "Checho" | Marca, renders, video, brochure, web, pauta, portales, inmobiliarias |
| **ADM** | Administración y almacén | María Mercedes | Contratistas, almacén, papelería, compras, transporte, control de costos |

**Terceros externos** (se marcan con 🔧 cuando aparecen): topógrafo · geotecnista · calculista (ingeniero civil estructural) · ingeniero eléctrico · ingeniero hidrosanitario · organismo de inspección RETIE · contadora (Lizeth) · abogado especialista en PH · notario · Oficina de Registro de Instrumentos Públicos (ORIP) de Duitama · avaluador inscrito en el RAA · curador urbano · Secretaría de Planeación de Duitama · Corpoboyacá · empresa de acueducto · operador de red eléctrica · asesor de la ARL · profesional en SST con licencia.

### 0.5 Glosario mínimo (términos del oficio que uso adelante)

- **Folio de matrícula inmobiliaria:** la "hoja de vida" de un predio en la Oficina de Registro. Un predio sin folio propio **no se puede vender ni hipotecar por separado**.
- **Englobe / desenglobe:** unir varios predios en uno (englobe) o partir uno en varios (desenglobe). Se hace por escritura pública y se registra.
- **Cabida y linderos:** el área y los límites que dice la escritura. Casi nunca coinciden exactamente con lo que mide el topógrafo; la diferencia se corrige por escritura de aclaración.
- **Curaduría urbana:** particular con función pública que estudia y expide las licencias urbanísticas. En Duitama existe curaduría (el acta menciona al curador y a Jorge Silva).
- **Expensas:** lo que se le paga a la curaduría por estudiar y expedir la licencia. No es un impuesto; es la tarifa del curador.
- **Índice de ocupación:** porcentaje del lote que puede quedar cubierto por construcción (huella).
- **Índice de construcción:** cuántos m² construidos se permiten por cada m² de lote (suma de todos los pisos).
- **Densidad:** cuántas viviendas se permiten por hectárea. **En suelo rural esta es la variable que mata proyectos.**
- **Cesión urbanística:** área del lote que hay que entregarle gratis al municipio (vías, zonas verdes, equipamiento).
- **Aislamiento:** distancia obligatoria entre la construcción y el lindero.
- **UAF (Unidad Agrícola Familiar):** área mínima que la Ley 160 de 1994 exige para partir predios rurales. Partir por debajo de la UAF está prohibido salvo excepciones.
- **Propiedad horizontal (PH):** régimen de la Ley 675 de 2001 que permite que un solo predio tenga varias unidades privadas, cada una con su propio folio, más zonas comunes.
- **Cuentas en participación:** contrato del Código de Comercio (arts. 507 a 514) entre un socio gestor —que da la cara— y uno o varios socios ocultos. **No crea una sociedad ni una persona jurídica nueva.**
- **Fiducia mercantil / patrimonio autónomo:** figura donde el lote y la plata se ponen a nombre de una fiduciaria, blindados frente a los acreedores de todos. Es el estándar del sector para proyectos con dinero de compradores.
- **AIU:** Administración, Imprevistos y Utilidad. Forma de descomponer el precio de un contrato de construcción, relevante para el IVA.
- **RETIE / RETILAP:** reglamentos técnicos obligatorios de instalaciones eléctricas y de iluminación. Sin certificado RETIE **no hay conexión definitiva de energía**.
- **Encargo fiduciario de preventa:** cuenta donde se guarda la plata de los compradores hasta que el proyecto alcanza el punto de equilibrio. Si el proyecto no arranca, la plata se devuelve.

---

## 1. ANTES DE LA EDT: SIETE OBSERVACIONES FRANCAS SOBRE DECISIONES YA TOMADAS

La regla que me dieron es no dar por buena una decisión solo porque ya está tomada. Estas siete son las que, con veinte años de esto, no dejaría pasar.

### 1.A El proyecto se está construyendo sobre un predio que quizá ni siquiera existe jurídicamente 🔴

El acta dice dos cosas que, juntas, son una alarma: *"el englobe original se repartió en cuatro lotes"* y *"el lote aún está englobado con los otros tres"* (impuesto predial). Eso significa que **la repartición pudo haber sido un acuerdo de familia, no una división registrada**. Si es así, hoy Rosa no es dueña de 2.612 m²: es **comunera de un englobe** de más de 14.000 m² junto con Pablo, Óscar y Marta.

Consecuencias si esto se confirma: no hay folio de matrícula propio → no hay certificado de tradición del lote → **la curaduría no recibe la solicitud de licencia**, el notario no escritura, ningún banco le presta al comprador, y no se puede constituir garantía a favor del proyecto. Y regularizarlo exige el consentimiento de **los cuatro comuneros** (partición material o división de la comunidad), más licencia de subdivisión, más escritura, más registro: entre 3 y 9 meses **⚠ VERIFICAR**, y con poder de veto en manos de terceros.

**[RE]** Esta es la **pregunta número uno del proyecto**. Se responde con el certificado de tradición y libertad del folio, que cuesta menos de $25.000 y se saca en línea o en la ORIP de Duitama. **Antes de gastar en renders, en dron, en marca o en contratos, saquen ese certificado.** Es lo primero de la sección 3.

### 1.B La figura elegida (cuentas en participación) es incompatible con lo que el equipo quiere hacer con ella

El acta registra tres cosas simultáneas: (i) la figura es cuentas en participación con Rosa como socia oculta (D-04); (ii) *"Rosa no debe conocer el presupuesto interno"*; (iii) a Rosa se le paga un **precio fijo por m², sin participación en utilidades**.

Esas tres cosas no caben juntas:

- **[RL]** El **Código de Comercio, art. 512**, le da al partícipe inactivo el derecho a **revisar todos los documentos de la participación y a exigir rendición de cuentas al gestor**. Es decir: la figura que eligieron le da a Rosa exactamente el derecho que quieren negarle. Si mañana hay un conflicto, ese artículo es la primera carta que juega su abogado.
- **[RL]** El **Estatuto Tributario, art. 18** (contratos de colaboración empresarial, modificado por la Ley 1819 de 2016) obliga al **gestor a certificar al partícipe oculto la información financiera y fiscal** de la operación, y a cada parte a declarar ingresos, costos y deducciones **según su participación**. Una retribución fija que no depende del resultado no es "participación": es precio. **⚠ VERIFICAR con Lizeth (contadora)** el riesgo de que la DIAN recaracterice la operación como compraventa a plazos y desconozca el tratamiento que se le dé.
- **[RL]** El **art. 510 del Código de Comercio** deja al **gestor como único responsable frente a terceros**. Hugo Ignacio responde con su patrimonio personal por proveedores, contratistas, compradores y accidentes. Rosa no. Eso está bien para Rosa; es durísimo para Hugo Ignacio.

**[RE] La alternativa que yo estructuraría:** lo que el equipo económicamente quiere es **comprar el lote con precio escalonado y pago diferido contra cada venta**. Eso se llama **promesa de compraventa** (o compraventa con precio a plazo e **hipoteca a favor de Rosa** en garantía del saldo), no cuentas en participación. Ventajas: Rosa no adquiere derecho de inspección sobre la contabilidad; el precio fijo escalonado queda perfectamente legítimo; el proyecto obtiene la **titularidad o al menos un derecho oponible**; y el tratamiento tributario de Rosa (probable ganancia ocasional si tiene el lote hace más de dos años) es más limpio que el de una "participación" **⚠ VERIFICAR con Lizeth**. Si la razón para no escriturar es no tener la plata hoy, la respuesta es una **promesa de compraventa con pago contra cada escritura de venta + hipoteca**, no un contrato asociativo.

### 1.C Se va a desarrollar sobre predio ajeno sin ninguna garantía real 🔴

Hoy, si Rosa se retracta, se muere, la embargan, se divorcia, o simplemente se demora, **el proyecto pierde el lote y todo lo invertido**, y no hay nada inscrito en el folio que lo impida. Una cláusula de exclusividad en un contrato privado (D-05) **no es oponible a terceros**: no aparece en el certificado de tradición, y un tercero de buena fe que le compre a Rosa gana.

**[RE]** Antes de gastar el primer millón fuerte (diseños, estudios, expensas), debe existir **una de estas tres**: (a) escritura de compraventa a favor del proyecto con hipoteca a favor de Rosa por el saldo; (b) **fiducia mercantil** con patrimonio autónomo al que Rosa transfiere el lote y que le paga a ella según el esquema pactado; o (c) como mínimo, promesa de compraventa por escritura pública con arras confirmatorias fuertes, más **patrimonio autónomo o encargo fiduciario para la plata de los compradores**. Ver 4.3 y el hito **G-3**.

### 1.D La densidad y el índice de ocupación pueden hacer inviables las 5 unidades 🔴

Cinco viviendas en 2.612 m² equivalen a **≈19 viviendas por hectárea**. Eso es densidad urbana. En suelo rural y rural suburbano del altiplano boyacense las densidades máximas las fija el POT **con base en las determinantes ambientales de la CAR (Corpoboyacá)** y suelen ser **muy inferiores** **⚠ VERIFICAR ante Secretaría de Planeación de Duitama y Corpoboyacá**.

Además, para **parcelaciones de vivienda campestre en suelo rural**, el Decreto 1077 de 2015 (que compiló el Decreto 3600 de 2007) fija un **índice de ocupación máximo del orden del 30% del área del predio, debiendo destinarse el resto a la conservación o recuperación de la vegetación nativa** **⚠ VERIFICAR el artículo y el porcentaje vigente ante la curaduría**. Si esa regla aplica, 2.612 m² dan ≈784 m² de ocupación máxima —lo cual podría alcanzar para las huellas de 5 casas de dos pisos, **pero choca de frente con la idea de vender "lotes individuales de 350 m² cerrados con puerta"**, porque el 70% restante tendría que ser área de conservación, no jardín privado cercado.

**Este punto define el producto entero.** No se sigue diseñando fachadas hasta tener la respuesta (ver 2.1 y el hito **G-1**).

### 1.E "Cinco lotes individuales" puede ser jurídicamente imposible; la PH puede ser el único camino

Partir un predio rural en cinco lotes de 350 m² choca con la **Ley 160 de 1994 (arts. 44 y 45)**, que prohíbe fraccionar predios rurales por debajo de la UAF, **salvo excepciones** —entre ellas los predios destinados a usos distintos al agropecuario que el municipio autorice conforme al POT **⚠ VERIFICAR el alcance exacto de la excepción ante la curaduría**.

**[RE]** El camino que casi siempre resulta viable en el altiplano es **propiedad horizontal (Ley 675 de 2001)** sobre un solo predio: cinco unidades privadas, cada una con **su propio folio de matrícula** (que es lo que el banco del comprador necesita), zonas comunes, y **sin necesidad de subdividir el suelo**. Costo: reglamento de PH, coeficientes, persona jurídica, administración y cuota mensual. Ver 11.1 y 11.2 para la comparación completa de los dos caminos.

### 1.F El proyecto no tiene con qué arrancar y depende al 100% de la preventa 🔴

Costo estimado $1.815 millones. Capital de arranque $40–50 millones. **Eso es el 2,5% del costo.** Sin crédito constructor, la única fuente es la plata de los compradores. Y la plata de los compradores **no se puede recibir legalmente antes de un trámite específico** que el acta no menciona en ninguna parte:

**[RL]** Quien se dedique a la **enajenación de inmuebles destinados a vivienda** debe **radicar documentos ante la autoridad municipal** (Ley 66 de 1968, Decreto 2610 de 1979, art. 71 de la Ley 388 de 1997 y el Decreto 1077 de 2015 en la parte de enajenación de inmuebles destinados a vivienda). **Recibir dinero del público sin ese trámite es una infracción** y expone al gestor a sanciones. **⚠ VERIFICAR ante la Secretaría de Gobierno / Planeación de Duitama** cuál es la dependencia competente y el listado exacto de documentos. Esto está en 8.2 y es un **hito duro** del cronograma comercial.

Consecuencia de gerencia: **la fase de preventa no puede arrancar cuando el equipo quiera, sino cuando exista licencia + radicación municipal.** Todo el flujo de caja del proyecto cuelga de esa fecha.

### 1.G La informalidad laboral es el riesgo peor calibrado del acta

El acta lo dice sin rodeos: *"hoy se contrata informalmente (contratista pone gente, sin seguridad social). Se evaluó cubrirlo con seguros individuales"*. Hay que ser claro:

- **[RL]** La construcción es **clase de riesgo V**, la más alta. Cuando la labor contratada es de riesgo IV o V, **el pago de los aportes a la ARL está a cargo del contratante**, no del contratista (Decreto 723 de 2013, compilado en el Decreto 1072 de 2015) **⚠ VERIFICAR artículo vigente con el asesor de la ARL**.
- **[RL]** El **art. 34 del Código Sustantivo del Trabajo** hace al **beneficiario de la obra solidariamente responsable** con el contratista independiente por salarios, prestaciones e indemnizaciones, **salvo que se trate de labores extrañas a su giro ordinario**. Para un desarrollador inmobiliario, construir **es** el giro ordinario: la solidaridad aplica de lleno.
- **[RL]** Un **seguro de accidentes personales NO reemplaza la ARL**, no cubre prestaciones económicas del sistema, no exonera de la solidaridad laboral, y **no evita la responsabilidad civil ni penal** por un accidente grave o mortal.

**[RE]** El costo de formalizar (aportes sobre la mano de obra + SG-SST) es del orden del **20–30% adicional sobre el valor de la mano de obra** **≈ ORDEN DE MAGNITUD a validar con Lizeth y con la ARL**. El costo de no formalizarlo, en un solo accidente grave, es el patrimonio personal del socio gestor. No es una decisión de presupuesto: es una decisión de si el proyecto es asegurable o no. Ver Fase 9.3.


---

# PARTE I — ESTRUCTURA DE DESGLOSE DE TRABAJO

**Índice de fases**

| # | Fase | Duración típica | Corre en paralelo con |
|---|---|---|---|
| 1 | Gobierno del proyecto y arranque ordenado | 2–4 sem | Todas (es transversal) |
| 2 | Prefactibilidad normativa, técnica y de mercado | 3–6 sem | 3 |
| 3 | Debida diligencia del predio y control del suelo | 4–10 sem (hasta 9 meses si hay que regularizar) | 2 |
| 4 | Estructuración jurídica, societaria y tributaria | 4–8 sem | 5 |
| 5 | Estudios técnicos y diseño | 10–18 sem | 4, 6 |
| 6 | Servicios públicos y gestión ambiental | 6–16 sem | 5 |
| 7 | Licenciamiento urbanístico | 8–20 sem | 8 (preparación), 9 (preparación) |
| 8 | Estructuración comercial y lanzamiento | 8–12 sem hasta lanzar; luego continuo | 7, 9, 10 |
| 9 | Preparación de obra | 4–8 sem | 8 |
| 10 | Ejecución de obra | 40–70 sem | 8, 11 |
| 11 | Titulación: PH o subdivisión, y matrículas | 8–16 sem | 10 |
| 12 | Escrituración, entrega y recaudo final | 4–10 sem por unidad | 10 (últimas unidades), 13 |
| 13 | Posventa y garantías | 1 año (acabados) / 10 años (estabilidad) | 14 |
| 14 | Cierre y liquidación | 6–12 sem | — |

---

## FASE 1 — GOBIERNO DEL PROYECTO Y ARRANQUE ORDENADO

*Objetivo de la fase: que el proyecto tenga reglas, papeles y tablero antes de tener gastos. Es la fase más barata y la que más plata ahorra.*

---

### 1.1 Constitución del equipo y reglas de operación

**Objetivo.** Dejar por escrito quién decide qué, cómo se decide y cómo se remunera cada rol, antes de que haya plata de por medio.

**Actividades.**
- **1.1.1** Acta de constitución del proyecto (*project charter*): objeto, alcance, exclusiones, roles, límites de autonomía de cada socio para comprometer plata. *(El Acta N.° 01 es el borrador; falta convertirla en documento de gobierno.)*
- **1.1.2** Definir la **tarifa/honorario de cada rol** antes del reparto de utilidad (D-09, tema abierto N.° 5 del acta). Cuatro tarifas distintas: dirección arquitectónica y de obra, jurídico, comercial, administración.
- **1.1.3** Definir la **tarifa de alquiler del equipo y herramienta propios** de Hugo Ignacio al proyecto (HI-13), a precio de mercado y con contrato de arrendamiento de bienes muebles.
- **1.1.4** Definir la **regla de rotación y remuneración de labores operativas** (transporte de materiales, manejo del camión) ya acordada en el acta.
- **1.1.5** Definir el **régimen de decisiones**: qué se decide por unanimidad (precio de venta, cambios de producto, endeudamiento), qué por mayoría, qué autonomía tiene cada rol.
- **1.1.6** Definir **política de conflicto de interés y de proveedores** (el acta ya excluye a un proveedor; eso debe quedar documentado con criterio, no como veto personal).

**Entregables verificables.** Acta de constitución firmada por los cuatro · Tabla de honorarios por rol con tarifa y base de cálculo · Contrato de arrendamiento de equipo Hugo Ignacio ↔ proyecto · Matriz de límites de autorización de gasto.

**Responsable.** ADM (María Mercedes) lidera · JUR redacta · los cuatro aprueban.

**Precedencias.** Ninguna. **Se puede y se debe hacer ya.** Paraleliza con 1.2, 1.3 y 2.1.

**Duración.** 2–3 semanas.

**Costos.** Ninguno en efectivo, salvo autenticaciones notariales de firmas **≈ $15.000 por autenticación** (el acta ya lo anota).

**Riesgos.** *Que se arranque sin definir honorarios y se discuta al final, cuando ya hay plata sobre la mesa* → los repartos se pelean cuando hay utilidad, no cuando hay entusiasmo. **Mitigación:** cerrar 1.1.2 antes del primer desembolso significativo. *Que un socio comprometa plata sin autorización* → matriz de límites (1.1.5).

**Marco normativo.** Ninguno específico. **[RE]**

---

### 1.2 Sistema de información, archivo y trazabilidad

**Objetivo.** Que exista un solo lugar donde esté todo y que nada dependa de la memoria de una persona.

**Actividades.**
- **1.2.1** Montar Slack + Google Drive con estructura de canales y carpetas, e inducción a los cuatro socios (S-1, D-11).
- **1.2.2** Definir **nomenclatura de archivos** (ya en uso: `PEN_ÁREA_TipoNN_Nombre_AAAAMMDD`) y hacerla obligatoria.
- **1.2.3** Estructura de carpetas espejo de esta EDT (una carpeta por fase), para que el archivo del proyecto se arme solo a medida que se avanza.
- **1.2.4** Archivo de seguimiento semanal compartido (MM-4).
- **1.2.5** **Libro de obra / bitácora digital** desde el día uno: toda llamada con curaduría, planeación, Corpoboyacá o Rosa se registra con fecha, interlocutor y conclusión. **[RE]** Esto es lo que salva un proyecto cuando cambia el funcionario que atendía el trámite.
- **1.2.6** Tablero de seguimiento con los códigos de esta EDT y las acciones del acta (HI-x, HE-x, S-x, MM-x) mapeadas a subfases.

**Entregables verificables.** Workspace operativo con los 4 vinculados · Documento de nomenclatura · Árbol de carpetas creado · Tablero con tareas cargadas · Bitácora iniciada.

**Responsable.** COM (Sergio) monta · ADM opera y audita semanalmente.

**Precedencias.** Ninguna. Paralelo con todo.

**Duración.** 1–2 semanas para montarlo; permanente para operarlo.

**Costos.** Plan de Slack y Google Workspace (**≈ costo mensual por usuario, a cotizar**) · dominio (se cotiza en 8.4).

**Riesgos.** *Que se monte y no se use, y se vuelva a WhatsApp* → la disciplina se pierde en la semana 3. **Mitigación:** regla dura de que lo que no está en Drive no existe para efectos de pago; MM no tramita cuenta de cobro sin soporte cargado.

**Marco normativo.** Conservación de documentos: ver 14.4 (obligaciones de conservación tributaria y contable). **[RL] parcialmente.**

---

### 1.3 Presupuesto maestro por capítulos (línea base viva)

**Objetivo.** Tener desde el día uno el **listado exhaustivo de capítulos de costo**, aunque los valores estén vacíos, para que ningún costo aparezca por sorpresa (D-08, HI-12).

**Actividades.**
- **1.3.1** Estructurar el presupuesto con los 11 capítulos ya acordados en el acta, **más los capítulos que el acta no contempla y que este documento identifica**: (12) Estructuración jurídica y societaria; (13) Gestión ambiental y permisos de Corpoboyacá; (14) Seguridad y salud en el trabajo y afiliaciones; (15) Propiedad horizontal y titulación; (16) Posventa y garantías; (17) Costos de cierre y liquidación; (18) Impuestos de la operación (ICA, renta, retenciones); (19) Costo financiero del colchón de caja.
- **1.3.2** Definir para cada capítulo: unidad, cantidad, valor unitario, fuente del dato (cotización / referencia / estimado) y **fecha del dato**.
- **1.3.3** Definir la **partida de imprevistos** y su regla de uso. **[PM]** En proyectos pequeños de vivienda el rango habitual es **5%–10% del costo directo**; con socios de dedicación parcial y sin experiencia previa en obra, yo trabajaría con **10%** **[RE]**.
- **1.3.4** Definir el **modelo de flujo de caja mensual** (ingresos por hitos de recaudo vs. egresos por capítulo).
- **1.3.5** Regla de actualización: el presupuesto se recalcula al cerrar diseño, al obtener licencia, al contratar cada capítulo de obra, y mensualmente durante la obra.

**Entregables verificables.** Archivo `PEN_ADM_PPTO01_PresupuestoMaestro` con los 19 capítulos y sus subcapítulos · Modelo de flujo de caja mensual · Registro de supuestos con fecha.

**Responsable.** DAO (estructura técnica) + ADM (control y consolidación) · 🔧 contadora (Lizeth) para los capítulos tributario y financiero.

**Precedencias.** Ninguna para armar la estructura. Los valores se llenan a medida que avanzan 5 (diseño) y 9 (contratación).

**Duración.** 2 semanas la estructura; permanente el llenado.

**Costos.** Honorario de la contadora por el armado del modelo tributario **≈ a cotizar**.

**Riesgos.** *Presupuestar solo lo que se ve (materiales y mano de obra) y olvidar los "costos blandos"* → en proyectos pequeños los costos blandos (diseños, licencias, jurídico, comercial, impuestos, financieros) son típicamente **20%–30% del costo total**, y el acta los estimó en $500.000/m² sobre $2.000.000/m², es decir 20%: **está en el borde bajo del rango, no en el centro** **[RE]**. **Mitigación:** llenar el capítulo blando con cotizaciones reales antes del hito **G-4**.

**Marco normativo.** No aplica.

---

## FASE 2 — PREFACTIBILIDAD NORMATIVA, TÉCNICA Y DE MERCADO

*Objetivo de la fase: saber si el proyecto es legalmente posible, técnicamente construible y comercialmente vendible, gastando lo mínimo. Es la fase donde se mata un mal proyecto barato.*

---

### 2.1 Verificación normativa previa: qué permite el POT en ese lote 🔴

**Objetivo.** Saber, con documento en mano, cuántas viviendas se pueden hacer en ese predio y bajo qué figura.

**Actividades.**
- **2.1.1** Obtener el **concepto de uso del suelo** para el predio ante la Secretaría de Planeación de Duitama. **[RL]** Es el documento que dice qué usos están permitidos.
  - **2.1.1.1** Identificar el predio por cédula catastral y folio de matrícula (depende de 3.1).
  - **2.1.1.2** Radicar solicitud de concepto de uso del suelo con formulario municipal.
  - **2.1.1.3** Pagar el derecho del trámite **⚠ VERIFICAR valor y si existe cobro en Duitama**.
  - **2.1.1.4** Recibir y archivar el concepto **con su número de radicado**.
- **2.1.2** Obtener la **norma urbanística específica** o consulta preliminar ante la Curaduría Urbana de Duitama, que debe responder al menos: clasificación del suelo (rural / rural suburbano / expansión / urbano); **densidad máxima de vivienda**; índice de ocupación e índice de construcción; altura máxima; aislamientos laterales, posterior y frontal; antejardín; ancho mínimo de vía y de andén; **cesiones urbanísticas obligatorias** y si son en sitio o compensadas; áreas mínimas de lote o de unidad privada; exigencias de área de conservación de vegetación nativa.
- **2.1.3** Verificar si el predio está en **suelo suburbano** y, de estarlo, si hay **umbral máximo de suburbanización** ya copado y si aplica **unidad mínima de actuación** **⚠ VERIFICAR ante Planeación**.
- **2.1.4** Verificar afectaciones del POT: vías proyectadas, ronda hídrica, áreas de protección, amenaza y riesgo, retiros a infraestructura (líneas de alta tensión, poliductos), y **afectación por cercanía al Batallón Silva Plazas** — la existencia de zonas de seguridad o servidumbres militares alrededor de instalaciones de la fuerza pública **⚠ VERIFICAR ante Planeación y ante el Batallón**. El acta no menciona este punto y puede ser relevante para alturas o para el uso.
- **2.1.5** Verificar si en Duitama están adoptados y reglamentados el **efecto plusvalía** (Ley 388 de 1997, arts. 73 a 90) y el **impuesto de delineación urbana**. **⚠ VERIFICAR ante la Secretaría de Hacienda de Duitama y su Estatuto Tributario municipal.** El efecto plusvalía se causa cuando el POT cambia la clasificación del suelo, cambia el uso, o autoriza mayor aprovechamiento; si el uso ya estaba permitido antes, normalmente no hay hecho generador, **pero eso se confirma, no se supone**.
- **2.1.6** Determinar **qué licencias aplican al caso** (ver 2.2).
- **2.1.7** Consultar a Jorge Silva / el curador los aislamientos definitivos (HI-4) y la negociación de los "piquitos" faltantes (HI-3). **Advertencia [RE]:** los aislamientos **no se negocian** con el curador; el curador aplica la norma. Lo que sí existe es una lectura técnica de cómo se mide el aislamiento y desde dónde, y eventualmente figuras del POT (empates, retrocesos, patios mancomunados). Ir a "negociar" una norma es la forma más rápida de perder credibilidad ante una curaduría.

**Entregables verificables.** Concepto de uso del suelo con radicado · Norma urbanística específica o acta de consulta preliminar · Ficha normativa del predio de una página, firmada por DAO, con la fuente de cada dato · Bitácora de las reuniones con curaduría y planeación.

**Responsable.** DAO lidera · JUR acompaña · 🔧 curador urbano, Secretaría de Planeación.

**Precedencias.** Requiere 3.1 (identificación registral del predio) para poder radicar. Se puede iniciar la consulta informal antes.

**Duración.** 2–4 semanas (concepto de uso del suelo suele tardar entre 5 y 15 días hábiles **⚠ VERIFICAR término en Duitama**).

**Costos.** Derechos de trámite municipal · certificado de tradición · certificado catastral · desplazamientos. **≈ menos de $1 millón en total.** *Es el gasto más rentable del proyecto.*

**Riesgos.** *Que la densidad máxima permita 2 o 3 viviendas, no 5* → **el proyecto cambia de tamaño o muere**. **Mitigación:** resolverlo ahora, no después de los diseños. *Que el índice de ocupación del 30% en parcelación rural haga inviable el loteo de 350 m² cerrados* → replantear a PH con áreas comunes de conservación (ver 1.E y 11.1). *Que un funcionario dé la respuesta de palabra* → **exigir siempre documento con radicado**; lo verbal no defiende nada.

**Marco normativo.** Ley 388 de 1997 · Decreto 1077 de 2015 (Decreto Único Reglamentario del Sector Vivienda, que compiló el Decreto 3600 de 2007 sobre ordenamiento del suelo rural y el Decreto 1469 de 2010 sobre licencias) · POT/EOT vigente de Duitama y sus modificaciones **⚠ VERIFICAR número de acuerdo y vigencia** · determinantes ambientales de Corpoboyacá. **[RL]**

---

### 2.2 Definición de la ruta de licencias aplicable

**Objetivo.** Saber exactamente qué licencias hay que sacar, en qué orden, y cuál es la consecuencia de cada camino.

**Actividades.**
- **2.2.1** Distinguir las cuatro figuras y determinar cuáles aplican:

| Licencia | Para qué sirve | ¿Aplica aquí? |
|---|---|---|
| **Parcelación** | Dividir un predio **rural** en parcelas, ejecutando las obras de infraestructura (vías, servicios) que permitan destinarlas a usos autorizados —típicamente vivienda campestre. | **Probablemente sí**, si el suelo es rural o rural suburbano y se van a generar unidades con acceso propio. **⚠ VERIFICAR** |
| **Urbanización** | Dividir y dotar de infraestructura predios en **suelo urbano o de expansión**. | **Solo si el predio resultara urbano o de expansión.** **⚠ VERIFICAR** |
| **Subdivisión** | Partir un predio en varios, en sus modalidades rural, urbana y reloteo. | **Sí, si el camino elegido es loteo individual.** Choca con la UAF (ver 1.E). |
| **Construcción** | Levantar la edificación. Modalidades: obra nueva, ampliación, adecuación, modificación, restauración, reforzamiento estructural, demolición, reconstrucción y **cerramiento**. | **Sí, en modalidad obra nueva** para las 5 viviendas. El **cerramiento** del lote también es una modalidad licenciable **⚠ VERIFICAR si el cerramiento perimetral requiere licencia en este caso.** |
| **Intervención y ocupación del espacio público** | Intervenir andenes, vías o zonas públicas (por ejemplo, para el acceso, el andén de 2 m o el cruce de redes). | **Muy probablemente sí**, dado que hay que resolver el acceso por la callejuela y construir andén. **El acta no lo contempla.** |

- **2.2.2** Determinar si hace falta licencia de parcelación **previa** a la de construcción, o si se pueden tramitar simultáneamente **⚠ VERIFICAR ante la curaduría**. Esto cambia el cronograma en meses.
- **2.2.3** Definir modalidad, **vigencia y prórroga**: **[RL]** la licencia urbanística tiene una vigencia (del orden de 24 meses, prorrogable por una sola vez por 12 meses adicionales, y la prórroga debe solicitarse dentro del plazo previsto antes del vencimiento y habiendo iniciado obra) **⚠ VERIFICAR los términos exactos vigentes en el Decreto 1077 de 2015 con la curaduría**. Consecuencia de dejarla vencer: **hay que volver a tramitarla, pagando expensas de nuevo y sujetándose a la norma vigente en ese momento**, que puede ser peor. Con un horizonte de venta de hasta 3 años, **este riesgo es real y hay que administrarlo activamente** (ver riesgo R-09).
- **2.2.4** Evaluar la **viabilidad de tramitar dos licencias separadas** (D-07: Rosa 3 casas / Jimena 2 casas). Análisis obligatorio: (a) si ambas recaen sobre **el mismo predio**, la curaduría debe poder identificar el área objeto de cada licencia — normalmente exige que el predio esté previamente subdividido o que exista licencia de parcelación que defina las unidades; (b) se pagan **dos juegos de expensas**; (c) se duplican planos, estudios y trámites; (d) el ahorro tributario perseguido es la progresividad del impuesto de renta de personas naturales, **pero el art. 869 del Estatuto Tributario (abuso en materia tributaria) permite a la DIAN recaracterizar operaciones sin propósito económico o comercial aparente distinto del ahorro fiscal** **⚠ VERIFICAR con Lizeth**; (e) Jimena, como titular de licencia sobre predio ajeno, requiere **autorización expresa del propietario**. **[RE] Mi lectura: la ganancia tributaria de este esquema es incierta y el costo administrativo es cierto. Antes de adoptarlo, pidan a Lizeth el cálculo comparado de los dos escenarios con números, no con intuición.**
- **2.2.5** Armar el **listado maestro de requisitos de curaduría y la ruta de radicación** (HE-8).

**Entregables verificables.** Memorando de ruta de licencias, firmado por JUR y DAO, con la respuesta de la curaduría anexada · Listado maestro de requisitos · Cálculo comparado del escenario una licencia vs. dos licencias, elaborado por la contadora.

**Responsable.** JUR lidera · DAO aporta lo técnico · 🔧 curador urbano, contadora.

**Precedencias.** Requiere 2.1. Paraleliza con 3.x.

**Duración.** 2–3 semanas.

**Costos.** Consultas · concepto de la contadora **≈ a cotizar**.

**Riesgos.** *Descubrir a mitad de camino que faltaba la licencia de parcelación* → 4 a 8 meses de retraso. **Mitigación:** consulta preliminar formal por escrito. *Que las dos licencias se conviertan en dos proyectos administrativos y nadie los coordine* → asignar la coordinación a JUR con un solo cronograma.

**Marco normativo.** Ley 388 de 1997 · Decreto 1077 de 2015, Título 6 (licencias urbanísticas) · Ley 810 de 2003 (sanciones urbanísticas) · Estatuto Tributario, art. 869. **[RL]**

---

### 2.3 Prefactibilidad técnica del predio

**Objetivo.** Confirmar que el lote se puede construir sin sorpresas de topografía, suelo, acceso o servicios, **antes** de contratar diseños.

**Actividades.**
- **2.3.1** Visita técnica conjunta al predio con lista de chequeo: pendiente aparente, cortes y llenos previsibles, presencia de agua, vegetación a intervenir, evidencia de humedales o nacimientos, estado de la callejuela de acceso, ancho real de la vía, servidumbres de hecho (pasos de vecinos, mangueras, redes).
- **2.3.2** Vuelos de dron para levantamiento del entorno, accesos y estudio de seguridad (S-6) — sirven también como **registro del estado inicial del predio**, útil ante reclamaciones futuras **[RE]**.
- **2.3.3** Verificar la **existencia y titularidad del acceso**: si la callejuela lateral es vía pública, servidumbre constituida, o paso de hecho. 🔴 **Un predio sin acceso jurídicamente asegurado no es urbanizable ni financiable.** Si el acceso es servidumbre, debe estar **constituida por escritura pública e inscrita en los folios del predio sirviente y dominante**.
- **2.3.4** Evaluar la opción de "correr el acceso al costado más económico" (HI-1) contra: propiedad del suelo por donde correría, costo de obra, y si requiere permiso municipal o acuerdo con vecinos.
- **2.3.5** Verificar cercanía a cauces: distancia a la quebrada más próxima y si el predio está dentro de la faja de protección. **[RL]** La normativa ambiental establece una **faja no inferior a 30 metros a cada lado de los cauces** de ríos, quebradas y arroyos, sean permanentes o no, como área forestal protectora (Decreto 1449 de 1977, compilado en el Decreto 1076 de 2015) **⚠ VERIFICAR alcance y aplicación al caso ante Corpoboyacá**, y el POT puede ampliarla. Esto es exactamente lo que HE-7 debe preguntar.
- **2.3.6** Verificar disponibilidad aparente de servicios: dónde pasa la red de acueducto (veredal o municipal), si hay alcantarillado (probablemente no), dónde está la red de energía más cercana y a qué distancia, si hay red de gas natural.
- **2.3.7** Verificar la **logística de materiales**: 10 km fuera del perímetro urbano; radio de giro para mixer y volqueta en la callejuela; capacidad portante de la vía; posibilidad de entrega en obra sin recargo (MM-6).

**Entregables verificables.** Informe de visita técnica con fotos y lista de chequeo · Ortofoto y modelo del dron · Concepto escrito sobre el acceso · Croquis de distancias a redes.

**Responsable.** DAO lidera · COM (dron) · ADM (logística) · JUR (titularidad del acceso).

**Precedencias.** Ninguna dura. Paraleliza con 2.1 y 3.1.

**Duración.** 1–2 semanas.

**Costos.** Vuelos de dron · desplazamientos · procesamiento de imágenes.

**Riesgos.** *Acceso no asegurado jurídicamente* → mata el proyecto. *Faja de protección de quebrada que reduce el área útil* → puede reducir de 5 a 4 o 3 unidades. **Mitigación:** ambos se resuelven en esta subfase, antes de gastar en diseño.

**Marco normativo.** Decreto 1076 de 2015 (Decreto Único Reglamentario del Sector Ambiente) · Código Civil (servidumbres, arts. 879 y ss.) · POT de Duitama. **[RL]**

---

### 2.4 Prefactibilidad comercial y validación de precio

**Objetivo.** Confirmar que existe un comprador dispuesto a pagar $500 millones por este producto en esta ubicación, antes de comprometerse con el costo.

**Actividades.**
- **2.4.1** **Estudio de comparables serio**, no anecdótico: mínimo 12 inmuebles en oferta y —lo importante— **operaciones efectivamente cerradas** en La Trinidad, Surba, Bonza, Tocogua, San Lorenzo, corredor Duitama–Paipa. Para cada uno: área construida, área de lote, precio pedido, precio cerrado si se consigue, tiempo en el mercado, especificaciones y acabados.
- **2.4.2** Verificar el dato de la casa de reventa de Pantano de Vargas pedida en $800 millones (HI-5): **precio pedido no es precio de mercado**. Lo que importa es a cuánto se cerró y en cuánto tiempo.
- **2.4.3** Visitar el **competidor directo** de 5 casas en Surba/Bonza: precio, especificación, velocidad de ventas, qué incluye (portón automático, cámaras, vías adoquinadas, cerramiento) y **cuánto lleva en el mercado**. Es el mejor termómetro disponible.
- **2.4.4** Medir la **velocidad de absorción** del submercado: cuántas casas campestres de $400–600 millones se venden por mes en el área de influencia de Duitama. **Este número, no el precio, es el que define si el proyecto se vende en 12 meses o en 30.** **⚠ VERIFICAR con inmobiliarias de Duitama, Paipa, Tunja y Villa de Leyva (Osvaldo Martínez, S-10).**
- **2.4.5** Perfilar al comprador objetivo: el que sale de Villa de Leyva por precio (promedio $1.969 millones, piso $900 millones). Definir: origen (Bogotá / Duitama / Sogamoso), uso (segunda vivienda / vivienda permanente / retiro), forma de pago (contado / crédito / venta de otro inmueble), y **qué porcentaje puede pagar de cuota inicial**. Este último dato define el flujo de caja del proyecto.
- **2.4.6** Contrastar el **precio implícito del lote**: se le venden al cliente ~400 m² útiles cobrados como ~500 m² a ≈$150.000/m² (≈$60 millones por casa) mientras a Rosa se le pagan $140.000/m² por 2.612 m². **[RE] Advertencia comercial y legal:** lo que se le vende al comprador debe corresponder **exactamente** a lo que dirá su folio de matrícula o su unidad privada. Cobrar 500 m² y escriturar 400 m² es un problema bajo el **Estatuto del Consumidor (Ley 1480 de 2011, arts. 23 y ss., información y publicidad)**. La forma correcta y perfectamente legítima es **un precio único por la unidad**, sin desagregar $/m² de lote en la publicidad ni en la promesa.
- **2.4.7** Definir la **hipótesis de precio y franja de negociación** ($500 M lista / hasta $520 M según forma de pago), y la **regla de descuento** (mejor precio a mejor forma de pago, nunca al revés).

**Entregables verificables.** Estudio de comparables en hoja de cálculo con fuente y fecha de cada dato · Ficha del competidor de Surba/Bonza · Estimación de absorción mensual del submercado · Perfil de comprador de una página · Tabla de precios y política de descuentos aprobada por los cuatro socios.

**Responsable.** COM lidera · DAO valida lo técnico de los comparables · 🔧 inmobiliarias, avaluador (opcional en esta fase).

**Precedencias.** Ninguna. Paraleliza con 2.1, 2.3, 3.x. **Es la subfase que más se subestima y la que decide si el negocio existe.**

**Duración.** 3–4 semanas.

**Costos.** Desplazamientos · eventual avalúo comercial de referencia **≈ a cotizar con avaluador inscrito en el RAA**.

**Riesgos.** *Confirmar el precio con precios pedidos en portales en vez de cierres reales* → sobreestimación sistemática del 10–20%. **Mitigación:** exigir al menos 3 cierres verificados. *Absorción de 1 casa cada 4–6 meses en el submercado* → el horizonte de 12 meses es irreal y el escalonamiento del pago a Rosa castiga al proyecto. **Mitigación:** modelar el escenario lento en el flujo de caja (ver E).

**Marco normativo.** Ley 1480 de 2011 (Estatuto del Consumidor) para publicidad e información. **[RL]** Lo demás es **[PM]**.


---

## FASE 3 — DEBIDA DILIGENCIA DEL PREDIO Y CONTROL DEL SUELO

*Objetivo de la fase: saber si el lote existe jurídicamente, si Rosa puede disponer de él, y asegurar que no se lo lleve nadie más. **Esta es la fase que el acta tiene más débil y la que más puede costar.***

---

### 3.1 Estudio de títulos 🔴

**Objetivo.** Establecer con certeza quién es el dueño, de qué exactamente, y con qué limitaciones.

**Actividades.**
- **3.1.1** Obtener el **certificado de tradición y libertad** del predio en la ORIP de Duitama.
  - **3.1.1.1** Identificar el número de matrícula inmobiliaria. Si el predio "sigue englobado", el folio será el del englobe mayor.
  - **3.1.1.2** Solicitar el certificado (en línea en la ventanilla de la Superintendencia de Notariado y Registro o presencial). **≈ menos de $25.000.**
  - **3.1.1.3** Determinar la respuesta a la pregunta crítica: **¿existe un folio de matrícula independiente para los 2.612 m² de Rosa, o Rosa figura como copropietaria/comunera de un predio mayor?**
- **3.1.2** **Estudio de títulos de los últimos 20 años** por abogado: cadena de tradición completa, modos de adquisición, sucesiones no liquidadas, particiones, ventas de derechos herenciales o de cuota.
- **3.1.3** Revisar **anotaciones vigentes** que impidan disponer: hipotecas, embargos, demandas civiles registradas, patrimonio de familia inembargable, afectación a vivienda familiar, usufructo, condición resolutoria, prohibiciones de enajenar, medidas de restitución de tierras, procesos agrarios, falsa tradición.
- **3.1.4** Verificar **estado civil y régimen patrimonial de Rosa**: si es casada o convive en unión marital de hecho sin capitulaciones, se requiere la firma del cónyuge o compañero permanente para disponer. **Este es un olvido clásico que revienta una escrituración el mismo día de la firma.**
- **3.1.5** Verificar **capacidad**: que Rosa no esté bajo medida de interdicción o apoyo, y que quien firme tenga poder vigente si actúa por conducto de apoderado.
- **3.1.6** Obtener el **certificado catastral / boletín catastral** y contrastar área catastral vs. área de escritura vs. área topográfica.
- **3.1.7** Obtener **paz y salvo de impuesto predial** y determinar quién ha pagado, cuánto se debe, y cómo se reparte durante la ejecución (HI-8). **[RL]** El predial es carga real: **el que compre responde por lo adeudado**. Si el predio está englobado, el recibo llega a nombre de un solo titular: hay que acordar por escrito el reparto y conservar los soportes.
- **3.1.8** Verificar **servidumbres** activas y pasivas inscritas, y las de hecho detectadas en 2.3.
- **3.1.9** Verificar si hay **posesión de terceros**, arrendatarios, aparceros o mejoras ajenas dentro del predio.

**Entregables verificables.** Certificado de tradición y libertad (vigencia usual exigida por curaduría y notaría: **no mayor a 30 días** **⚠ VERIFICAR**) · Certificado catastral · Paz y salvo predial · **Informe de estudio de títulos firmado por el abogado, con concepto expreso de "apto / no apto / apto condicionado a…"** · Registro civil de matrimonio o declaración de estado civil de Rosa.

**Responsable.** JUR lidera · 🔧 abogado (puede ser el mismo JUR) · ORIP · IGAC o catastro municipal.

**Precedencias.** **Ninguna. Es lo primero que debe hacerse en el proyecto, junto con 2.1.** Todo lo demás depende de esto.

**Duración.** 2–4 semanas. **Si aparece que el predio no está dividido: 3 a 9 meses adicionales** para regularizar (ver 3.2).

**Costos.** Certificados **≈ $50.000–$150.000 en total** · honorarios de estudio de títulos **≈ a cotizar** · impuesto predial pendiente.

**Riesgos.** 🔴 *Que el lote no tenga folio propio* → ver 3.2. *Que aparezca una sucesión ilíquida* → hay que liquidarla antes de escriturar: 6–18 meses. *Que Rosa sea casada y el cónyuge no esté de acuerdo* → mata la operación. **Mitigación única y suficiente: hacer este estudio AHORA, antes de gastar en diseños, renders, marca o dron.**

**Marco normativo.** Ley 1579 de 2012 (Estatuto de Registro de Instrumentos Públicos) · Código Civil (tradición, comunidad, servidumbres, sociedad conyugal) · Ley 258 de 1996 (afectación a vivienda familiar) · Ley 54 de 1990 y Ley 979 de 2005 (unión marital de hecho). **[RL]**

---

### 3.2 Regularización de la división del englobe (contingente) 🔴

**Objetivo.** Si el predio de Rosa no tiene folio propio, obtenerlo. Sin esto **no hay proyecto**.

**Actividades.**
- **3.2.1** Determinar la naturaleza jurídica de la repartición ya hecha entre Pablo, Rosa, Óscar y Marta: ¿escritura de partición registrada? ¿acuerdo privado? ¿comunidad con adjudicación de hecho?
- **3.2.2** Si es comunidad: definir la ruta de **división material** —de común acuerdo (escritura de partición, requiere **la firma de los cuatro**) o judicial (proceso divisorio, mucho más lento).
- **3.2.3** Tramitar la **licencia de subdivisión** en la modalidad que corresponda (rural o urbana) ante la curaduría. **[RL]**
  - **3.2.3.1** Verificar el choque con la **UAF** (Ley 160 de 1994, arts. 44 y 45) y si aplica alguna excepción, en particular la de predios destinados a usos distintos al agropecuario autorizados por el POT **⚠ VERIFICAR ante la curaduría**.
  - **3.2.3.2** Preparar el plano de subdivisión con topógrafo.
  - **3.2.3.3** Radicar, subsanar observaciones, obtener la resolución.
- **3.2.4** Otorgar la **escritura pública de división material / desenglobe** ante notaría.
- **3.2.5** **Registrar** la escritura en la ORIP y obtener la **apertura de los folios de matrícula independientes**.
- **3.2.6** Actualizar el **catastro** (mutación catastral) para que el predial se liquide por separado.

**Entregables verificables.** Escritura de partición registrada · **Folio de matrícula inmobiliaria propio del lote de 2.612 m²** · Resolución de licencia de subdivisión · Certificado catastral actualizado.

**Responsable.** JUR lidera · DAO coordina topografía · 🔧 topógrafo, curador, notario, ORIP, catastro.

**Precedencias.** Requiere 3.1 y 2.1. Bloquea 7 (licencias), 4.3 (garantía real) y 11 (titulación).

**Duración.** **3–9 meses** si hay acuerdo entre los cuatro comuneros. **Indeterminado** si no lo hay. **⚠ VERIFICAR términos reales con la curaduría y la ORIP de Duitama.**

**Costos.** Honorarios de topógrafo · expensas de curaduría por licencia de subdivisión · gastos notariales (tarifa notarial vigente) · **impuesto de registro departamental (Boyacá)** y **derechos de registro de la ORIP** · impuesto de beneficencia si aplica **⚠ VERIFICAR tarifas con notaría y Gobernación de Boyacá**.

**Riesgos.** *Que uno de los cuatro comuneros no firme* (Marta ya "no responde las llamadas", según el acta) → **veto absoluto**. **Mitigación:** verificar el estado registral primero (3.1); si hace falta la firma de todos, conseguir compromisos escritos **antes** de invertir. *Que la UAF impida la subdivisión* → migrar a PH (11.1).

**Marco normativo.** Ley 160 de 1994 · Ley 388 de 1997 · Decreto 1077 de 2015 (licencia de subdivisión) · Ley 1579 de 2012 · Código Civil (división de la comunidad, arts. 2334 y ss.). **[RL]**

---

### 3.3 Levantamiento topográfico y amojonamiento

**Objetivo.** Saber exactamente qué se tiene, dónde están los linderos y cómo es el terreno.

**Actividades.**
- **3.3.1** Contratar topógrafo con **términos de referencia escritos**: levantamiento planialtimétrico con curvas de nivel cada 0,5 m, amarre a coordenadas oficiales (MAGNA-SIRGAS), localización de linderos, árboles, construcciones, redes visibles, cauces, postes, cajas, y el eje de la vía de acceso.
- **3.3.2** **Conciliación de linderos con los vecinos colindantes** (Pablo, Óscar, Marta y quien más colinde), con acta firmada. **[RE]** Esto vale más que cualquier plano: evita el pleito de linderos a mitad de obra.
- **3.3.3** **Amojonamiento físico** (mojones de concreto en cada vértice) y registro fotográfico georreferenciado.
- **3.3.4** Contrastar **cabida real vs. cabida de escritura**. Si difieren, definir con JUR si se requiere **escritura de aclaración de cabida y linderos** antes de licenciar o escriturar.
- **3.3.5** Levantamiento del **perfil de la vía de acceso** y de la rasante, insumo para el diseño vial interno y para decidir el punto de acceso (HI-1).

**Entregables verificables.** Plano topográfico firmado por topógrafo con matrícula profesional, en formato digital editable y PDF · Acta de conciliación de linderos con vecinos · Registro fotográfico del amojonamiento · Memoria de cálculo de áreas.

**Responsable.** DAO contrata y recibe · 🔧 **topógrafo** (obligatorio).

**Precedencias.** Requiere autorización escrita de Rosa (4.1) para intervenir el predio. Bloquea 5.1, 5.2, 3.2.3.2 y toda la fase de diseño.

**Duración.** 1–2 semanas de campo y oficina; 2–3 semanas incluyendo contratación.

**Costos.** Honorarios de topografía · mojones y materiales · transporte. **≈ orden de magnitud a cotizar; es de los renglones más baratos del proyecto y de los que más problemas evita.**

**Riesgos.** *Que la cabida real sea menor que la escriturada* → menos área útil, y el precio pactado con Rosa por m² debería recalcularse sobre el área **real**, no la de escritura. **[RE] El contrato con Rosa debe decir expresamente sobre qué área se liquida: la que arroje el levantamiento topográfico, no la de la escritura.** El acta no lo prevé. *Que el vecino no acepte el lindero* → resolverlo antes de construir el cerramiento, no después.

**Marco normativo.** Resolución del IGAC sobre estándares cartográficos **⚠ VERIFICAR vigente** · Código Civil (deslinde y amojonamiento). **[RL] parcial.**

---

### 3.4 Autorización de Rosa para adelantar trámites y estudios

**Objetivo.** Tener el permiso escrito del propietario para pisar el lote, medirlo, perforarlo y radicar trámites a su nombre. **Sin esto, todo lo que se haga es irregular.**

**Actividades.**
- **3.4.1** Redactar la nota de aceptación / autorización (HE-4) que cubra expresamente: ingreso al predio, levantamiento topográfico, apiques y perforaciones para estudio de suelos, descapote de prueba, radicación de **consultas y trámites ante Planeación, curaduría, Corpoboyacá y empresas de servicios públicos a nombre de la propietaria**, y solicitud de certificados.
- **3.4.2** Incluir la **autorización expresa para que un tercero (Jimena) figure como titular de licencia** sobre el predio, si se mantiene D-07.
- **3.4.3** **Autenticar las firmas ante notario** y, si el trámite lo exige, otorgar **poder especial** por escritura pública o documento autenticado según lo requiera cada entidad **⚠ VERIFICAR qué exige cada entidad**.
- **3.4.4** Definir **vigencia** de la autorización y su carácter **irrevocable durante la vigencia del contrato** (en lo que sea jurídicamente posible), y qué pasa con lo invertido si Rosa la revoca.

**Entregables verificables.** Nota de autorización autenticada · Poder especial si aplica · Constancia de entrega de copia a curaduría y planeación.

**Responsable.** JUR redacta · DAO gestiona con Rosa (HI-6) · 🔧 notario.

**Precedencias.** **Debe ir ANTES del contrato** (D-06) y antes de 3.3, 5.2 y cualquier radicación.

**Duración.** 1 semana.

**Costos.** Autenticaciones **≈ $15.000 c/u** · poder si se requiere.

**Riesgos.** *Autorización redactada de forma genérica que la curaduría no acepte* → devuelven la radicación. **Mitigación:** pedirle a la curaduría el modelo o los requisitos exactos antes de firmarla. *Revocación unilateral* → mitigar con 4.3 (garantía real) lo antes posible.

**Marco normativo.** Decreto 1077 de 2015 (titulares de las licencias: el titular del derecho de dominio, o quien cuente con su autorización) · Código Civil (mandato). **[RL]**

---

### 3.5 Verificación ambiental preliminar del predio

**Objetivo.** Saber si hay una restricción ambiental que reduzca el área útil o exija permisos, antes de diseñar.

**Actividades.**
- **3.5.1** Consulta formal a **Corpoboyacá** sobre el predio: ronda hídrica y faja de protección de la quebrada; áreas de especial importancia ecológica; humedales; nacimientos (la protección de nacimientos suele ser de **100 m a la redonda** **⚠ VERIFICAR ante Corpoboyacá**); presencia en Estructura Ecológica Principal; determinantes ambientales aplicables al suelo rural de Duitama; **densidades máximas que Corpoboyacá fija para suelo rural suburbano**.
- **3.5.2** Verificar si el predio está en zona de **amenaza o riesgo** (remoción en masa, inundación) según el POT y los estudios básicos de riesgo del municipio.
- **3.5.3** Inventario de **árboles a intervenir**: especies, cantidad, diámetro. Si hay tala, se requiere **permiso de aprovechamiento forestal** ante Corpoboyacá. **[RL]**
- **3.5.4** Verificar si se requiere **permiso de ocupación de cauce** (si el acceso o alguna red cruza la quebrada). **[RL]**
- **3.5.5** Definir el esquema de **manejo de aguas lluvias y escorrentía** a nivel de prefactibilidad: hacia dónde drena el predio, si hay que construir cunetas, disipadores o pozos de infiltración, y si se afecta al vecino de abajo. **[RE]** Descargar escorrentía sobre el predio vecino sin obra de manejo es fuente segura de conflicto y de responsabilidad civil.

**Entregables verificables.** Respuesta escrita de Corpoboyacá con radicado · Ficha ambiental del predio · Inventario forestal · Concepto de amenaza y riesgo.

**Responsable.** JUR radica · DAO aporta lo técnico · 🔧 Corpoboyacá, eventualmente ingeniero forestal o ambiental.

**Precedencias.** Paraleliza con 3.1 y 2.1. Bloquea 5.1 (implantación definitiva).

**Duración.** 3–8 semanas (los términos de respuesta de una CAR son variables **⚠ VERIFICAR**).

**Costos.** Derechos de trámite · eventual concepto de profesional ambiental · costo de los permisos si resultan necesarios (los permisos ambientales tienen **tarifa por evaluación y por seguimiento**, liquidada por la CAR).

**Riesgos.** 🔴 *Que la faja de 30 m de la quebrada atraviese el lote* → puede eliminar 1 o 2 unidades. **Mitigación:** confirmarlo antes del hito **G-1**. *Que se tale sin permiso* → sanción ambiental y suspensión de obra. **Mitigación:** ningún corte de árbol sin permiso escrito.

**Marco normativo.** Decreto 1076 de 2015 · Decreto 1449 de 1977 (faja forestal protectora de 30 m, compilado) · Ley 99 de 1993 · Ley 1333 de 2009 (procedimiento sancionatorio ambiental) · determinantes ambientales de Corpoboyacá (que son **norma de superior jerarquía** frente al POT, art. 10 de la Ley 388 de 1997). **[RL]**

---

## FASE 4 — ESTRUCTURACIÓN JURÍDICA, SOCIETARIA Y TRIBUTARIA

*Objetivo de la fase: definir con qué figura se opera, quién responde por qué, cómo entra y sale la plata, y cuánto se le queda a la DIAN y al municipio. **Es la fase que el equipo tiene decidida pero no estructurada.***

---

### 4.1 Acuerdo con la propietaria del lote

**Objetivo.** Asegurar el derecho a desarrollar y vender el lote, en condiciones claras para ambas partes.

**Actividades.**
- **4.1.1** Redactar el contrato (HE-1, HE-2, HE-3) con, como mínimo: identificación exacta del predio (folio, cabida real, linderos), **precio fijo escalonado** ($140.000 / $150.000 / $160.000 por m² según el año), **base de liquidación sobre el área topográfica real**, forma de pago (1/5 por cada casa vendida, contra qué hecho exacto: ¿firma de promesa? ¿escritura? ¿desembolso?), plazo total, exclusividad, prohibición de ofrecer o vender a terceros, parágrafo que excluya expresamente cualquier referencia a porcentajes, obligación de Rosa de mantener el predio libre de gravámenes, obligación de comparecer a las escrituras, autorización permanente de trámites, régimen de terminación e indemnizaciones, y **qué pasa con lo invertido si el contrato termina anticipadamente**.
- **4.1.2** Definir **quién comparece como vendedor** en cada escritura de venta a los compradores. Si el lote sigue a nombre de Rosa, **Rosa debe firmar cada escritura**: eso le da poder de bloqueo sobre cada venta y **le muestra el precio de venta real** —justo lo que el equipo quiere evitar.
- **4.1.3** Definir el tratamiento del **impuesto predial** durante la ejecución y su reparto (el acta asume que lo paga el proyecto; formalizarlo).
- **4.1.4** Definir el **tratamiento tributario del pago a Rosa**: si es precio de compraventa, si hay **retención en la fuente** aplicable y quién la practica; si el ingreso para Rosa es renta ordinaria o ganancia ocasional (depende de si el lote es activo fijo poseído más de dos años). **⚠ VERIFICAR con Lizeth (contadora). [RL]**
- **4.1.5** Someter el contrato a revisión de la contadora antes de firmarlo, no después.

**Entregables verificables.** Contrato firmado y con firmas autenticadas · Concepto tributario escrito de la contadora sobre el esquema de pago a Rosa · Anexo con el plano topográfico y el área de liquidación.

**Responsable.** JUR redacta · DAO negocia con Rosa · 🔧 contadora, notario.

**Precedencias.** Requiere 3.1 (saber qué es lo que se contrata) y 3.4 (autorización previa, D-06). **[RE] Advertencia: el acta ordena firmar el contrato "esta semana" (HE-1, HE-2) sin haber hecho el estudio de títulos. Es al revés: no se firma un contrato sobre un predio cuyo estado registral se desconoce.**

**Duración.** 2–4 semanas.

**Costos.** Honorarios jurídicos · autenticaciones · concepto de la contadora.

**Riesgos.** *Firmar antes del estudio de títulos* → comprometerse con un predio no titulable. *Ambigüedad sobre el hecho que dispara el pago de cada quinta parte* → conflicto seguro. *Que el escalonamiento anual castigue al proyecto si las ventas se demoran* → el costo del lote sube ≈$26 millones por año de demora: **es un incentivo perverso que le traslada al proyecto todo el riesgo de rotación**. **[RE] Mitigación: negociar que el escalonamiento se congele si la demora obedece a causas atribuibles a la propietaria o a trámites, y considerar un tope máximo.**

**Marco normativo.** Código de Comercio, arts. 507 a 514 (cuentas en participación) · Código Civil (compraventa, promesa, arts. 1857 y ss.) · Estatuto Tributario, arts. 18, 300 y ss. **[RL]**

---

### 4.2 Elección y formalización de la figura de operación

**Objetivo.** Decidir con qué vehículo se opera el proyecto, sabiendo qué se gana y qué se arriesga con cada uno.

**Actividades.**
- **4.2.1** Evaluar por escrito las cuatro alternativas reales:

| Figura | Ventaja | Costo / desventaja | Riesgo principal |
|---|---|---|---|
| **Personas naturales + cuentas en participación** *(lo decidido, D-04)* | Cero costo de constitución; simple | El gestor responde **con todo su patrimonio personal**; el partícipe tiene derecho de inspección (C.Co art. 512) | Responsabilidad ilimitada de Hugo Ignacio; recaracterización tributaria |
| **Sociedad (S.A.S.)** | Responsabilidad limitada al aporte; una sola contabilidad; facilita la entrada de terceros y de crédito | Costos de constitución y registro mercantil; renta corporativa + impuesto a los dividendos; contabilidad formal | Doble tributación si no se planea |
| **Fiducia mercantil (patrimonio autónomo)** | **Es el estándar del sector**: blinda el lote y la plata de los compradores frente a acreedores de todos; los bancos y los compradores confían | Comisión fiduciaria y costos de estructuración; exige orden | Costo fijo alto para un proyecto de 5 unidades |
| **Consorcio / unión temporal** | Sencillo | Responsabilidad solidaria de todos frente a terceros | No aporta blindaje |

- **4.2.2** **[RE] Mi recomendación:** para 5 unidades y $1.815 millones, una fiducia completa puede resultar cara, pero **un encargo fiduciario de administración de recursos de preventa sí es proporcionado y resuelve el problema más grave del proyecto** (recibir plata del público sin respaldo). Como mínimo: **cuenta bancaria exclusiva del proyecto**, separada del patrimonio personal del gestor, con firma conjunta de dos socios y conciliación mensual. **⚠ VERIFICAR costos con una fiduciaria (Fiduciaria Bancolombia, Alianza, Corficolombiana u otra) antes de descartar la figura.**
- **4.2.3** Formalizar el contrato de cuentas en participación entre los cuatro socios gestores (el acta define la relación con Rosa, **pero no formaliza la relación entre los cuatro socios entre sí**: eso es un vacío grave). Debe cubrir: aportes de cada uno (trabajo, gestión, equipo, capital), honorarios por rol, reglas de reparto, retiros, incumplimiento, retiro voluntario, muerte o incapacidad de un socio, y solución de controversias.
- **4.2.4** **Inscripción en el registro mercantil** de la Cámara de Comercio de Duitama. **[RL] ⚠ VERIFICAR con la contadora:** el Código de Comercio considera actos mercantiles las empresas de obras o construcciones, y quien ejerce profesionalmente el comercio debe matricularse. Omitirlo genera sanciones y complica la contratación.
- **4.2.5** Apertura de la **cuenta bancaria del proyecto** y definición de firmas.

**Entregables verificables.** Documento de análisis comparado de figuras, firmado por los cuatro · Contrato de cuentas en participación entre los cuatro socios · Certificado de matrícula mercantil · Cuenta bancaria abierta con reglamento de firmas · Cotización de encargo fiduciario.

**Responsable.** JUR lidera · ADM opera lo bancario · 🔧 contadora, fiduciaria, Cámara de Comercio.

**Precedencias.** Requiere 4.1. Bloquea 8.2 (radicación para enajenación) y 8.5 (recibir dinero).

**Duración.** 3–4 semanas.

**Costos.** Matrícula mercantil y renovación anual · comisión fiduciaria si se adopta · costos bancarios · honorarios jurídicos.

**Riesgos.** *Que los cuatro socios nunca firmen nada entre ellos* → cuando aparezca la utilidad, no habrá regla escrita. **Mitigación:** 4.2.3 antes de la primera venta. *Mezclar la plata del proyecto con la personal* → imposible controlar costos, imposible defender ante la DIAN, y **es la causa número uno de peleas entre socios**.

**Marco normativo.** Código de Comercio (arts. 10, 19, 20, 507-514) · Ley 1328 y normas de fiducia · Estatuto Tributario art. 18. **[RL]**

---

### 4.3 Aseguramiento del derecho sobre el suelo (garantía real) 🔴

**Objetivo.** Que el proyecto no dependa de la buena voluntad de la propietaria ni sobreviva solo en un contrato privado.

**Actividades.**
- **4.3.1** Definir el **momento** en que se vuelve indispensable pasar de contrato privado a derecho oponible. **[RE] Mi criterio: antes de radicar la licencia y pagar expensas**, es decir, antes del hito **G-4**, porque de ahí en adelante el gasto es fuerte e irrecuperable.
- **4.3.2** Evaluar las tres rutas:
  - **4.3.2.1 Compraventa con precio a plazo + hipoteca de primer grado a favor de Rosa.** El proyecto queda como dueño (puede licenciar, escriturar y vender sin depender de Rosa); Rosa queda garantizada por hipoteca. **Costo:** gastos notariales, impuesto de registro y derechos de registro sobre el valor del acto, y el proyecto asume el predial. **[RE] Es la ruta más limpia si hay con qué pagar la primera cuota.**
  - **4.3.2.2 Fiducia mercantil.** Rosa transfiere el lote a un patrimonio autónomo que le paga según lo pactado y que escritura a los compradores. Blinda a todos. **Costo:** comisión fiduciaria.
  - **4.3.2.3 Promesa de compraventa** por escritura pública, con arras confirmatorias y cláusula penal robusta. **No es oponible a terceros** (no se registra), pero da acción de cumplimiento. Es el mínimo aceptable.
- **4.3.3** Verificar la **capacidad de pago del proyecto** para la ruta elegida contra el flujo de caja (1.3.4).
- **4.3.4** Formalizar, otorgar escritura y **registrar**.

**Entregables verificables.** Escritura pública otorgada y **registrada**, con anotación visible en el certificado de tradición · o certificado de la fiduciaria de constitución del patrimonio autónomo.

**Responsable.** JUR lidera · 🔧 notario, ORIP, fiduciaria.

**Precedencias.** Requiere 3.1, 3.2 (si aplica), 4.1. **Bloquea el hito G-4.**

**Duración.** 3–6 semanas.

**Costos.** Gastos notariales (tarifa notarial vigente, del orden de una fracción del valor del acto, **⚠ VERIFICAR tarifa anual de la Superintendencia de Notariado y Registro**) · **impuesto de registro departamental de Boyacá** (Ley 223 de 1995; tarifas para actos con cuantía sujetos a registro, fijadas por ordenanza **⚠ VERIFICAR**) · **derechos de registro de la ORIP** · **retención en la fuente que practica el notario** cuando el enajenante es persona natural que enajena un activo fijo (Estatuto Tributario, arts. 398 y 399) **⚠ VERIFICAR aplicación al caso con Lizeth**.

**Riesgos.** *Postergarlo "hasta que haya plata"* → es exactamente el error que hace que un proyecto pierda todo lo invertido. **Mitigación:** condicionar el hito G-4 a esta subfase. *Que Rosa exija un pago inicial que el proyecto no tiene* → negociar hipoteca por el 100% del saldo, sin cuota inicial, o fiducia.

**Marco normativo.** Código Civil (compraventa, hipoteca, arts. 2432 y ss.) · Ley 1579 de 2012 · Ley 223 de 1995 (impuesto de registro) · Estatuto Tributario arts. 398-399. **[RL]**

---

### 4.4 Estructuración tributaria de la operación

**Objetivo.** Saber, antes de vender, cuánto de cada $500 millones se va en impuestos y quién los paga. **Este es el punto que el acta reconoce como debilidad ("manejo tributario de las ventas", tema abierto N.° 8).**

**Actividades.**
- **4.4.1** **Renta ordinaria vs. ganancia ocasional.** **[RL]** La distinción es determinante:
  - Un inmueble **construido para la venta** es, para quien lo desarrolla, **inventario (activo movible)**: su venta genera **renta ordinaria**, gravada a la **tarifa progresiva de personas naturales**, que puede llegar a tramos altos.
  - La **ganancia ocasional** aplica a la enajenación de **activos fijos poseídos por más de dos años** (Estatuto Tributario, art. 300), a una tarifa única sustancialmente menor.
  - **Conclusión práctica:** las utilidades del proyecto tributarán como **renta ordinaria** en cabeza de quien figure como vendedor. Quien crea que va a tributar como ganancia ocasional está mal informado. **⚠ VERIFICAR con Lizeth tarifas y tramos vigentes para el año gravable correspondiente.**
- **4.4.2** **Efecto del esquema de dos titulares** (D-07) sobre la carga tributaria: cuantificar el escenario A (un titular, 5 casas) vs. escenario B (dos titulares, 3+2), incluyendo el riesgo del art. 869 del ET.
- **4.4.3** **RUT y responsabilidades**: inscripción o actualización del RUT del socio gestor y de los titulares, con las responsabilidades que correspondan (renta, retención en la fuente, IVA si aplica, facturación electrónica). **[RL]**
- **4.4.4** **Obligación de facturar y facturación electrónica**: determinar si la venta de los inmuebles debe facturarse electrónicamente además de escriturarse, y cómo se soportan los ingresos. **⚠ VERIFICAR con Lizeth; hay doctrina de la DIAN sobre el punto y no debe resolverse por intuición.**
- **4.4.5** **IVA**:
  - **[RL]** La **venta de bienes inmuebles no está gravada con IVA**.
  - **[RL]** En los **contratos de construcción de bien inmueble**, el IVA se causa **sobre los honorarios o la utilidad del constructor**, no sobre el valor total del contrato (Decreto 1372 de 1992, art. 3, y doctrina de la DIAN) **⚠ VERIFICAR vigencia y aplicación con Lizeth**. De ahí la importancia de **pactar los contratos de obra desagregando administración, imprevistos y utilidad (AIU)**: si no se desagrega, se corre el riesgo de que el IVA se liquide sobre una base mayor.
- **4.4.6** **Retención en la fuente**: matriz de retenciones a practicar (pagos a contratistas de obra, servicios, honorarios de diseñadores, arrendamiento del equipo de Hugo Ignacio, comisiones de vendedores e inmobiliarias) y retenciones que le practicarán al proyecto. **⚠ VERIFICAR tarifas vigentes con Lizeth.** También la retención aplicable a la venta de inmuebles y quién la practica (notario / comprador agente retenedor).
- **4.4.7** **ICA de Duitama**: determinar la actividad, el código y la tarifa aplicable a la construcción y a la venta de inmuebles, y el régimen de declaración. **[RL] El ICA se causa donde se ejecuta la actividad: Duitama.** **⚠ VERIFICAR tarifa y periodicidad en el Estatuto Tributario Municipal de Duitama, Secretaría de Hacienda.** También verificar retención de ICA (RETEICA) si el municipio la tiene.
- **4.4.8** **Impuesto predial** durante la ejecución (ver 3.1.7 y 4.1.3), incluida la **actualización del avalúo catastral** cuando se registren las construcciones: el predial sube.
- **4.4.9** **Gastos notariales y de registro en las ventas**: definir quién paga qué. **[PM]** La costumbre generalizada en Colombia es que los **gastos notariales se dividen por mitades entre comprador y vendedor**, y que el **impuesto de registro y los derechos de registro los asume el comprador**; la **retención en la fuente la asume el vendedor**. **[RL] Esto es costumbre, no ley: lo que rige es lo que diga la promesa de compraventa. Debe quedar escrito.**
- **4.4.10** Definir el **calendario tributario del proyecto** y quién lo cumple.

**Entregables verificables.** **Memorando tributario del proyecto firmado por la contadora** (documento único que responde 4.4.1 a 4.4.9) · RUT actualizado · Matriz de retenciones · Calendario tributario.

**Responsable.** JUR coordina · ADM opera · 🔧 **contadora (Lizeth) — indispensable**.

**Precedencias.** Requiere 4.2. Bloquea 8.5 (recibo de dinero) y 10 (pagos a contratistas).

**Duración.** 3–4 semanas.

**Costos.** Honorarios de la contadora (mensuales durante todo el proyecto) · software o servicio de facturación electrónica.

**Riesgos.** 🔴 *Vender cinco casas y descubrir en la declaración de renta que la utilidad después de impuestos es la mitad de la proyectada* → **la utilidad estimada de $685 millones del acta es UTILIDAD ANTES DE IMPUESTOS**. No aparece ninguna provisión tributaria en el modelo económico. **Mitigación: incorporar la provisión de renta e ICA al modelo antes del hito G-2.** *Facturar todo a nombre de una sola persona natural* → concentra la carga en el tramo más alto de la tarifa progresiva.

**Marco normativo.** Estatuto Tributario (arts. 18, 300 y ss., 398-399, 420, 615, 616-1, 869) · Decreto 1372 de 1992 · Estatuto Tributario Municipal de Duitama · Ley 1819 de 2016 y Ley 2277 de 2022 en lo pertinente. **[RL]**

---

### 4.5 Modelos contractuales del proyecto

**Objetivo.** Que ningún peso salga ni entre sin un documento que lo respalde.

**Actividades.**
- **4.5.1** **Contrato marco con contratistas de obra** (HE-9). Contenido mínimo: objeto y alcance por capítulo, modalidad (**precio unitario fijo** o **administración delegada** — **[RE] para este proyecto: precio unitario fijo por capítulo, es la única forma de controlar costo sin dedicación de tiempo completo**), cantidades y precios, forma de pago por **actas parciales de avance**, **retención en garantía del 5–10% liberada contra acta de recibo final** **[PM]**, plazo y multas, **obligación de afiliación a seguridad social y ARL del personal**, obligaciones de SST, prohibición de subcontratar sin autorización, pólizas exigidas, causales de terminación, y **cláusula de indemnidad laboral**.
- **4.5.2** **Pólizas exigibles a contratistas** **[PM]**: cumplimiento, **pago de salarios y prestaciones sociales**, estabilidad y calidad de la obra, y **responsabilidad civil extracontractual**. Definir porcentajes y vigencias. Para contratistas pequeños que no consiguen póliza, alternativa: mayor retención en garantía.
- **4.5.3** **Contratos con diseñadores y consultores**: arquitectónico, estructural, suelos, eléctrico, hidrosanitario, topografía. Deben incluir: alcance, número de entregas y revisiones incluidas, **propiedad intelectual y licencia de uso de los planos a favor del proyecto**, plazos, **responsabilidad profesional**, y obligación de acompañar la subsanación de observaciones de la curaduría **sin costo adicional** (esta cláusula sola ahorra millones).
- **4.5.4** **Contrato de arrendamiento de equipo y herramienta** con Hugo Ignacio (1.1.3).
- **4.5.5** **Papelería operativa** (MM-3, S-13): orden de compra, acta de entrega de materiales, acta parcial de obra, cuenta de cobro, acta de recibo, formato de control de contratistas (MM-1) y de almacén (MM-2).
- **4.5.6** **Contratos comerciales**: vinculación de inmobiliarias, comisión de vendedores, y (más adelante) promesa de compraventa (ver 8.3).

**Entregables verificables.** Carpeta de minutas aprobadas · Formatos de papelería en Drive · Cuadro de pólizas exigidas por tipo de contrato.

**Responsable.** JUR redacta · ADM diseña la papelería con COM · DAO valida los alcances técnicos.

**Precedencias.** Requiere 4.2. Debe estar listo **antes** de 9 (preparación de obra) y **antes** de contratar el primer diseño.

**Duración.** 3–4 semanas.

**Costos.** Honorarios jurídicos · costo de las pólizas (lo asume el contratista, pero se traslada al precio).

**Riesgos.** *Contratar diseños con un correo y un anticipo* → sin contrato no hay a quién reclamarle la subsanación de la curaduría. *No exigir pólizas por "confianza"* → el día del incumplimiento no hay respaldo.

**Marco normativo.** Código Civil y Código de Comercio (contratos) · Ley 1480 de 2011 · CST arts. 34 y 35 (solidaridad). **[RL] parcial / [PM] parcial.**


---

## FASE 5 — ESTUDIOS TÉCNICOS Y DISEÑO

*Objetivo de la fase: convertir la norma y el terreno en un proyecto construible, licenciable y vendible. Aquí es donde el equipo tiene más fortaleza —y donde el acta ya identificó su punto débil: la fachada.*

---

### 5.1 Diseño urbanístico: implantación, loteo y vías internas

**Objetivo.** Definir cómo se acomodan las 5 unidades, el acceso, las vías y las áreas comunes dentro de los 2.612 m², cumpliendo la norma.

**Actividades.**
- **5.1.1** Esquema de implantación probando el acceso por el costado más económico y verificando si caben 5 unidades con acceso (HI-1).
- **5.1.2** Verificar el cumplimiento de **densidad, índice de ocupación, índice de construcción, área mínima de unidad, aislamientos y área de conservación** contra la ficha normativa de 2.1. **Cada número del diseño debe poder señalarse contra un número de la norma.**
- **5.1.3** Diseño de la **vía interna**: ancho de calzada (6 m preliminar), radios de giro, pendientes, tipo de pavimento, **capacidad para el ingreso de un carro de bomberos y de un camión de mudanza** **[PM]**, y cuadro de áreas.
- **5.1.4** Diseño de **andenes (2 m preliminar) y antejardines (3–4 m preliminar)**, y su relación con la vía pública existente.
- **5.1.5** Resolver los **"piquitos" faltantes de aislamiento** en dos de los lotes (HI-3). **[RE] La solución técnica no es "negociar con el curador", es rediseñar: girar la casa, reducir huella, mover el lindero interno o pasar a régimen de PH, donde los aislamientos se miden respecto al lindero del predio matriz y no respecto a linderos internos inexistentes.** Este último punto puede resolver el problema completo y es una razón adicional a favor de la PH.
- **5.1.6** Definir **cesiones urbanísticas obligatorias**: cuánto, dónde, y si se pueden compensar en dinero. **⚠ VERIFICAR ante Planeación.** Restar el área de cesión del área vendible **antes** de calcular el precio.
- **5.1.7** Diseño de **manejo de aguas lluvias y escorrentía** (cunetas, sumideros, entrega final autorizada).
- **5.1.8** Definir la **quinta unidad especial** (2 alcobas) si el área lo impone (HI-2, decisión D-02, tema abierto N.° 1).
- **5.1.9** Cuadro de áreas definitivo: área bruta, áreas de cesión, área de vías, área de conservación, área privada por unidad, área construida por unidad, área vendible.

**Entregables verificables.** Plano de implantación general acotado · **Cuadro de áreas firmado** · Plano de vías, andenes y antejardines · Plano de manejo de aguas lluvias · Cuadro de cumplimiento normativo punto por punto.

**Responsable.** DAO · 🔧 topógrafo (base), ingeniero civil para diseño vial si el POT lo exige.

**Precedencias.** Requiere 2.1 (norma), 3.3 (topografía), 3.5 (restricciones ambientales). **Bloquea todo lo demás del diseño.**

**Duración.** 3–5 semanas.

**Costos.** Horas de DAO (remuneradas según 1.1.2) · eventual apoyo de dibujante · diseño vial.

**Riesgos.** 🔴 *Diseñar 5 unidades y descubrir que la densidad permite 3* → **rehacer todo**. **Mitigación: 2.1 antes de 5.1, sin excepción.** *Olvidar restar las cesiones del área vendible* → el precio por casa queda mal calculado. *Que el "ahorro significativo" de correr el acceso resulte en una vía que no cumple ancho mínimo* → verificar contra norma, no contra costo.

**Marco normativo.** POT de Duitama · Decreto 1077 de 2015 (normas de suelo rural y suburbano) · NSR-10 en lo pertinente a accesos. **[RL]**

---

### 5.2 Estudio geotécnico (estudio de suelos)

**Objetivo.** Saber qué hay debajo, para no descubrirlo con la excavación abierta.

**Actividades.**
- **5.2.1** Contratar geotecnista con términos de referencia escritos. **[RL] El estudio geotécnico es obligatorio conforme al Título H del Reglamento NSR-10** (adoptado por la Ley 400 de 1997 y sus decretos reglamentarios). El alcance —número y profundidad de sondeos— depende de la **categoría de la unidad de construcción** definida por la propia NSR-10. **⚠ VERIFICAR la categoría aplicable y el número mínimo de sondeos con el geotecnista y con la curaduría.**
- **5.2.2** Ejecutar sondeos/apiques distribuidos en el área de las 5 huellas, no solo en un punto.
- **5.2.3** Determinar: perfil estratigráfico, nivel freático, **capacidad portante**, tipo de cimentación recomendada, asentamientos esperados, **potencial expansivo de las arcillas** (frecuente y costoso en el altiplano cundiboyacense), agresividad química del suelo al concreto, y **parámetros sísmicos del sitio (perfil de suelo para NSR-10)**.
- **5.2.4** Recomendaciones de **excavación, taludes, llenos y compactación**, y de **manejo de aguas subsuperficiales**.
- **5.2.5** Recomendaciones para el **sistema de disposición de aguas residuales** si no hay alcantarillado: **prueba de infiltración/percolación** para dimensionar el campo de infiltración del sistema séptico. **[RE] Pídanselo al geotecnista en el mismo contrato: sale mucho más barato que contratarlo aparte después.**

**Entregables verificables.** **Informe de estudio geotécnico firmado por ingeniero civil o geotecnista con matrícula profesional**, con registros de sondeo, ensayos de laboratorio y recomendaciones expresas de cimentación. Es **documento exigido para la licencia de construcción**.

**Responsable.** DAO contrata · 🔧 **geotecnista (obligatorio)**.

**Precedencias.** Requiere 3.4 (autorización de Rosa) y 5.1 (saber dónde van las huellas). Paraleliza con 5.3.

**Duración.** 3–5 semanas (campo 1 semana, laboratorio y informe 2–4).

**Costos.** Honorarios de estudio geotécnico **≈ orden de magnitud a cotizar; para 5 unidades en un predio de 2.612 m² es un renglón menor frente al costo de una cimentación mal diseñada.**

**Riesgos.** 🔴 *Arcillas expansivas o nivel freático alto* → la cimentación puede pasar de zapatas a pilotes o a losa, y **subir el costo de la estructura de forma significativa**. Es la principal fuente de sobrecosto imprevisto en obra pequeña. **Mitigación:** hacerlo antes de fijar el precio de venta y antes del hito **G-3**. *Ahorrar en el estudio con un solo sondeo* → el ahorro es de cientos de miles; el error, de decenas de millones.

**Marco normativo.** Ley 400 de 1997 · Reglamento NSR-10, Título H (estudios geotécnicos) y Título A. **[RL]**

---

### 5.3 Diseño arquitectónico definitivo y proyecto para licencia

**Objetivo.** Tener los planos que se radican en curaduría y con los que se construye y se vende.

**Actividades.**
- **5.3.1** Desarrollar el programa de la casa tipo (~110 m²) ya definido en el acta: porche cubierto, sala con nicho de TV, comedor, cocina abierta con isla-lavaplatos y torre de hornos, barra auxiliar, patio de ropas, 2 alcobas secundarias, alcoba principal con vestier y baño, baño común, y **bodega exterior independiente** (diferenciador de producto).
- **5.3.2** Desarrollar la **unidad especial de 2 alcobas** si aplica (D-02).
- **5.3.3** Verificar cumplimiento de: **iluminación y ventilación natural en todos los espacios habitables**, alturas libres mínimas, dimensiones mínimas de escaleras y pasillos, y las **exigencias de accesibilidad** aplicables **⚠ VERIFICAR alcance para vivienda unifamiliar con la curaduría (NTC 4140 y ss., Ley 361 de 1997)**.
- **5.3.4** Planos técnicos completos para licencia: **localización, plantas acotadas, cortes (mínimo dos), fachadas, cubiertas, planta de cimentación de referencia, cuadro de áreas**, todos **firmados por arquitecto con matrícula profesional vigente**. **[RL]**
- **5.3.5** **Resolver la fachada** (punto crítico 3.4 del acta). Ciclo iterativo diseño ↔ render (HI-15, S-4) con criterio de cierre explícito: **la fachada se cierra cuando el equipo la aprueba por unanimidad y no antes**; después de esa fecha, todo cambio de fachada tiene costo y afecta el cronograma.
- **5.3.6** Definir la **especificación de acabados por unidad** (memoria de especificaciones): pisos, enchapes, carpintería, aparatos sanitarios, griferías, cocina, cubierta, ventanería, pintura. **[RL/PM] Este documento es el que se anexa a la promesa de compraventa y es la única defensa del constructor frente a reclamaciones de posventa.** Debe incluir la cláusula de **sustitución por producto de calidad igual o superior** ante descontinuación.
- **5.3.7** Definir **qué NO incluye la entrega** (lo que más pleitos genera): cortinas, closets adicionales, jardinería, cerramientos internos, aire acondicionado, etc.
- **5.3.8** Coordinar el diseño arquitectónico con estructural, eléctrico e hidrosanitario (**coordinación de especialidades**) antes de imprimir para radicar.

**Entregables verificables.** Juego completo de planos arquitectónicos firmados (digital + impreso) · Memoria de especificaciones de acabados · Renders aprobados de fachada · Acta de cierre de diseño firmada por los cuatro socios.

**Responsable.** DAO lidera · COM aporta renders (S-4, S-5) · 🔧 dibujante/renderista si se externaliza.

**Precedencias.** Requiere 5.1 y 5.2 (para cimentación). Bloquea 5.4, 5.5, 7.1, 8.1 (material comercial definitivo).

**Duración.** 5–8 semanas incluyendo iteraciones de fachada.

**Costos.** Honorarios de diseño arquitectónico (aunque lo haga DAO, **debe costearse y remunerarse**, D-09) · renders y video · impresiones y planos.

**Riesgos.** *Ciclos infinitos de fachada* → el acta ya identifica el riesgo. **Mitigación:** fijar número máximo de iteraciones y fecha de cierre. *Radicar planos con incoherencias entre plantas, cortes y cuadro de áreas* → acta de observaciones de la curaduría y 4–8 semanas perdidas. **Mitigación:** revisión cruzada por un tercero antes de radicar **[RE]**.

**Marco normativo.** Decreto 1077 de 2015 (documentos para licencia) · NSR-10 · Ley 400 de 1997 · Ley 361 de 1997 y normas de accesibilidad **⚠ VERIFICAR alcance** · Ley 1480 de 2011 (lo ofrecido obliga). **[RL]**

---

### 5.4 Diseño estructural y memorias de cálculo

**Objetivo.** Que las casas no se caigan y que la curaduría lo pueda verificar.

**Actividades.**
- **5.4.1** Definir el **sistema estructural**: mampostería confinada, pórticos en concreto, o mixto. **[RL] Para viviendas de uno y dos pisos existe el Título E de la NSR-10 (casas de uno y dos pisos en mampostería confinada), que permite un procedimiento simplificado bajo condiciones estrictas de regularidad, altura y área. ⚠ VERIFICAR con el calculista si las casas cumplen esas condiciones**: si cumplen, el diseño estructural es más económico; si no, se requiere análisis y diseño completos.
- **5.4.2** Contratar al **calculista: ingeniero civil con matrícula profesional vigente**, que es el **responsable idóneo** del diseño estructural. **[RL] Un arquitecto no puede firmar el diseño estructural.**
- **5.4.3** Desarrollar el diseño con base en el estudio geotécnico (5.2) y los planos arquitectónicos (5.3).
- **5.4.4** Producir **planos estructurales y memorias de cálculo firmadas**, incluyendo cimentación, despiece, y especificaciones de materiales (resistencia del concreto, acero).
- **5.4.5** Verificar si aplica la exigencia de **revisión independiente de los diseños estructurales** y de **supervisión técnica independiente** durante la obra. **[RL] ⚠ VERIFICAR con la curaduría:** la Ley 1796 de 2016 y el Título I de la NSR-10 establecen umbrales (por área construida y por número de pisos) a partir de los cuales estas figuras son obligatorias. **Con 5 unidades independientes de ~110 m² es probable que no apliquen, pero el umbral debe confirmarse, no suponerse.**
- **5.4.6** Definir con el calculista el **acompañamiento en obra**: visitas de verificación de acero antes de fundir. **[RE] Contrátenlo desde ya, aunque no sea obligatorio; es barato y evita el error irreversible.**

**Entregables verificables.** Planos estructurales firmados por ingeniero civil con matrícula · **Memorias de cálculo firmadas** · Copia de la matrícula profesional vigente y certificado de vigencia del COPNIA.

**Responsable.** DAO coordina · 🔧 **calculista / ingeniero civil estructural (obligatorio)**.

**Precedencias.** Requiere 5.2 y 5.3. Bloquea 7.1.

**Duración.** 3–5 semanas.

**Costos.** Honorarios de diseño estructural **≈ a cotizar** · acompañamiento en obra.

**Riesgos.** *Calculista sin matrícula vigente o que no acompaña la subsanación* → devolución en curaduría. **Mitigación:** cláusula de 4.5.3. *Diseñar la estructura antes del estudio de suelos* → rediseño completo.

**Marco normativo.** Ley 400 de 1997 · Reglamento NSR-10 (Títulos A, B, C, D, E, H, I) · Ley 1796 de 2016 · Ley 842 de 2003 (ejercicio de la ingeniería). **[RL]**

---

### 5.5 Diseño eléctrico (RETIE / RETILAP)

**Objetivo.** Que la instalación se pueda certificar y conectar. **Sin certificado RETIE no hay energía definitiva, y sin energía no hay entrega.**

**Actividades.**
- **5.5.1** Contratar **ingeniero electricista con matrícula profesional** (HI-11). **[RL]** El acta anota correctamente que *"la curaduría no lo tiene"*: **el diseño eléctrico no se revisa en la licencia de construcción, pero sí es obligatorio para la conexión y para la certificación RETIE**. Omitirlo es un error clásico: el proyecto se entera al final.
- **5.5.2** Diseño de **redes internas de cada vivienda** conforme al **RETIE** (Reglamento Técnico de Instalaciones Eléctricas) y de la **iluminación** conforme al **RETILAP**, incluida la iluminación de las vías y zonas comunes.
- **5.5.3** Diseño de la **acometida y red externa** del proyecto: punto de conexión, transformador si se requiere, medidores individuales, y **protocolo de aprobación del proyecto ante el Operador de Red** (en Boyacá, la empresa distribuidora de energía **⚠ VERIFICAR el operador que atiende la vereda La Trinidad**).
- **5.5.4** Definir el **alcance de la certificación RETIE**: **[RL]** la instalación debe ser inspeccionada y certificada por un **organismo de inspección acreditado ante el ONAC**, y el **dictamen de conformidad es requisito para que el operador de red conecte el servicio**. Hay que presupuestar **una certificación por vivienda** más la de zonas comunes **⚠ VERIFICAR alcance con el organismo de inspección**.
- **5.5.5** Prever **puesta a tierra**, protecciones, y —si el diseño lo justifica— **sistema de protección contra rayos**, frecuente en predios rurales despejados.
- **5.5.6** Prever previsiones de **telecomunicaciones** (fibra, TV) y **domótica básica** si el producto lo va a ofrecer.

**Entregables verificables.** Planos y memorias de diseño eléctrico firmados · Aprobación del proyecto por el operador de red · **Dictamen de inspección RETIE por unidad** (al final de obra) · Certificado de conformidad.

**Responsable.** DAO contrata · 🔧 **ingeniero eléctrico** y **organismo de inspección acreditado ONAC**.

**Precedencias.** Requiere 5.3. Se puede paralelizar con 5.4 y 5.6. La **certificación** ocurre al final de la obra (10.6).

**Duración.** Diseño 3–4 semanas · aprobación del operador de red 4–10 semanas **⚠ VERIFICAR**.

**Costos.** Honorarios de diseño · **derechos de conexión y aportes al operador de red** (pueden ser significativos si hace falta transformador o extensión de red) · **certificación RETIE por vivienda** · medidores.

**Riesgos.** 🔴 *Descubrir en el mes 10 que hace falta un transformador o extender la red 300 m* → costo alto e imprevisto y retraso en la entrega. **Mitigación: consultar la disponibilidad y el punto de conexión en la Fase 6, no en la Fase 10.** *No presupuestar la certificación RETIE* → aparece como sorpresa justo antes de escriturar.

**Marco normativo.** RETIE (Resolución del Ministerio de Minas y Energía y sus modificaciones) **⚠ VERIFICAR resolución vigente** · RETILAP · Ley 143 de 1994 · normas técnicas del operador de red. **[RL]**

---

### 5.6 Diseño hidrosanitario, de aguas lluvias y de gas

**Objetivo.** Que el agua entre, salga y se trate conforme a norma, y que el gas se pueda certificar.

**Actividades.**
- **5.6.1** Contratar **ingeniero hidrosanitario** (HI-11).
- **5.6.2** Diseño de **red interna de agua fría y caliente** conforme a la **NTC 1500 (Código Colombiano de Instalaciones Hidráulicas y Sanitarias)** **⚠ VERIFICAR versión vigente**, con planos de trazado que después alimentan el "libro del propietario" (S-12, punto 7.6 del acta).
- **5.6.3** Diseño de **red de desagües y ventilación**.
- **5.6.4** Diseño del **sistema de tratamiento de aguas residuales domésticas** si no hay alcantarillado: trampa de grasas, tanque séptico, filtro anaerobio y campo de infiltración, dimensionado con la prueba de percolación (5.2.5) y conforme al **RAS (Resolución 0330 de 2017)** **⚠ VERIFICAR vigencia y aplicación**. Decidir si es **una solución por vivienda o una solución colectiva** (esto tiene consecuencias jurídicas: una solución colectiva es bien común de la PH y requiere administración y mantenimiento permanentes).
- **5.6.5** Diseño de **acometida de acueducto** y **tanque de almacenamiento** con autonomía (**[RE] en veredas con acueducto de caudal variable, mínimo 24 horas de autonomía por vivienda**; es además argumento de venta).
- **5.6.6** Diseño de **red de aguas lluvias** y su entrega final autorizada.
- **5.6.7** Diseño de **red interna de gas** conforme a la **NTC 2505**, si se va a ofrecer gas natural o gas propano. **[RL]** La instalación interna debe ser **certificada por un organismo de inspección acreditado** antes de la puesta en servicio. Si no hay red de gas natural, definir la solución (cilindro, tanque estacionario) y sus retiros de seguridad.
- **5.6.8** Definir **reserva y red para protección contra incendio** si la norma lo exige para el conjunto **⚠ VERIFICAR con la curaduría y el cuerpo de bomberos de Duitama**.

**Entregables verificables.** Planos y memorias hidrosanitarias, de aguas lluvias y de gas, firmados · Memoria de dimensionamiento del sistema séptico · **Certificado de conformidad de la instalación de gas** (al final de obra).

**Responsable.** DAO contrata · 🔧 ingeniero hidrosanitario, organismo de inspección de gas, distribuidora de gas.

**Precedencias.** Requiere 5.3 y 6.1 (saber si hay acueducto y alcantarillado). Paraleliza con 5.4 y 5.5.

**Duración.** 3–4 semanas.

**Costos.** Honorarios de diseño · sistemas sépticos (5 unidades o 1 colectivo) · tanques de almacenamiento · certificación de gas · derechos de conexión de acueducto.

**Riesgos.** *Sistema séptico mal dimensionado o mal ubicado* → falla a los 2 años, reclamación de posventa y problema ambiental. *Suelo con baja infiltración* → el campo de infiltración no cabe en los lotes de 350 m² y hay que ir a una solución colectiva o a un sistema compacto, más caro. **Mitigación:** prueba de percolación en 5.2.5, antes de fijar el precio.

**Marco normativo.** NTC 1500 · NTC 2505 · Resolución 0330 de 2017 (RAS) · Decreto 1076 de 2015 (vertimientos) · reglamentación de la CREG para gas. **[RL]**

---

### 5.7 Presupuesto detallado y programación de obra

**Objetivo.** Saber cuánto cuesta exactamente construir lo diseñado, y en cuánto tiempo.

**Actividades.**
- **5.7.1** **Presupuesto por capítulos y APU** (análisis de precios unitarios): preliminares, cimentación, estructura, mampostería, cubierta, pañetes, instalaciones hidrosanitarias, instalaciones eléctricas, instalaciones de gas, pisos, enchapes, carpintería en madera, carpintería metálica, ventanería, aparatos sanitarios, cocina, pintura, obras exteriores, urbanismo interno, cerramiento, jardinería, aseo y entrega.
- **5.7.2** **Cotizar con proveedores reales de Duitama y Sogamoso**, no con precios de referencia de Bogotá. Incluir **el flete y el transporte a 10 km fuera del perímetro urbano** en cada precio unitario (MM-6).
- **5.7.3** Contrastar con la hipótesis del acta (~$2.000.000/m² de costo directo). **[RE] Advertencia: $2.000.000/m² para vivienda campestre con la especificación descrita (cocina con isla y torre de hornos, vestier, dos baños y medio, bodega exterior, porche) es una cifra ajustada. Debe validarse con APU reales antes del hito G-2, no después.**
- **5.7.4** **Programación de obra** (cronograma de barras) para el escenario elegido: 5 casas simultáneas, o por frentes (3+2), o secuencial. **[RE] Con capital de $40–50 millones y sin crédito, la única programación financiable es por frentes, arrancando con las unidades vendidas.**
- **5.7.5** **Curva S de inversión** derivada de la programación, insumo del flujo de caja (1.3.4).
- **5.7.6** Definir **cantidades de obra por unidad** para poder contratar a precio unitario fijo.

**Entregables verificables.** Presupuesto detallado con APU y fuente de cada precio · Programación de obra · Curva S · Listado de cantidades por capítulo.

**Responsable.** DAO elabora (HI-12) · ADM consolida y controla · 🔧 eventual apoyo de presupuestador.

**Precedencias.** Requiere 5.3, 5.4, 5.5, 5.6. **Es condición del hito G-2 (fijación del precio de venta).**

**Duración.** 3–4 semanas.

**Costos.** Horas de DAO y ADM · eventual software de presupuesto.

**Riesgos.** 🔴 *Fijar el precio de venta con un costo estimado y descubrir después que el costo real es 15% mayor* → la utilidad de $685 millones se convierte en $400 millones o menos. **Mitigación: no fijar precio de lista definitivo antes de tener 5.7.1 con cotizaciones reales.** *Presupuestar sin imprevistos* → ver 1.3.3.

**Marco normativo.** No aplica.

---

## FASE 6 — SERVICIOS PÚBLICOS Y GESTIÓN AMBIENTAL

*Objetivo de la fase: conseguir los papeles sin los cuales la curaduría no recibe la solicitud y el proyecto no se puede habitar. **Esta es la fase que más proyectos rurales retrasa en Boyacá.***

---

### 6.1 Disponibilidad de agua potable

**Objetivo.** Obtener por escrito que hay agua para 5 viviendas.

**Actividades.**
- **6.1.1** Determinar **quién presta el servicio** en la vereda La Trinidad: la empresa municipal de acueducto y alcantarillado de Duitama, o un **acueducto veredal** (asociación de suscriptores). **⚠ VERIFICAR.** El acta menciona la gestión con "Pedro (acueducto)" (HI-7).
- **6.1.2** Solicitar formalmente la **carta o certificado de disponibilidad inmediata del servicio de acueducto para 5 unidades de vivienda**. **[RL] Este es el documento que la curaduría exige.**
  - **6.1.2.1** Radicar solicitud escrita con identificación del predio, número de unidades y consumo estimado.
  - **6.1.2.2** Pagar el estudio de factibilidad si lo cobran.
  - **6.1.2.3** Obtener el documento **con número de radicado y vigencia expresa** (las cartas de disponibilidad **caducan**: verificar su vigencia y que siga vigente al momento de radicar la licencia).
- **6.1.3** Si el prestador es un **acueducto veredal**: verificar que tenga **concesión de aguas vigente ante Corpoboyacá** y **caudal concesionado suficiente** para 5 suscriptores adicionales. **[RL] 🔴 Un acueducto veredal sin concesión, o con concesión copada, no puede expedir una disponibilidad válida, y ese es un motivo frecuente de negación de licencias en suelo rural.** ⚠ VERIFICAR ante Corpoboyacá.
- **6.1.4** Verificar el **régimen de aportes de conexión, matrícula por unidad y costo de medidores**.
- **6.1.5** Si no hay disponibilidad: evaluar **concesión de aguas propia** (pozo profundo o captación superficial) ante Corpoboyacá — trámite largo, costoso e incierto. **[RE] Si el proyecto llega a depender de una concesión propia, cambia por completo su perfil de riesgo y su cronograma.**

**Entregables verificables.** **Carta de disponibilidad de acueducto** con radicado y vigencia · Copia de la concesión de aguas del prestador · Cotización de aportes de conexión y matrículas.

**Responsable.** DAO gestiona (HI-7) · JUR formaliza · 🔧 empresa de acueducto o junta del acueducto veredal, Corpoboyacá.

**Precedencias.** Requiere 3.1 (identificación del predio). **Bloquea 7.1 (radicación de licencia).** Paraleliza con toda la Fase 5.

**Duración.** 3–8 semanas **⚠ VERIFICAR términos**. Con acueducto veredal puede depender de una asamblea, lo que agrega semanas.

**Costos.** Estudio de factibilidad · aportes de conexión · matrículas por unidad · medidores · red de distribución interna.

**Riesgos.** 🔴 *Que no haya disponibilidad para 5 unidades* → mata o reduce el proyecto. Es **la segunda pregunta más importante del proyecto**, después del folio de matrícula. *Que la carta se venza antes de radicar la licencia* → hay que volver a pedirla. **Mitigación:** sincronizar 6.1 con 7.1 y no pedirla demasiado pronto.

**Marco normativo.** Ley 142 de 1994 (servicios públicos domiciliarios) · Decreto 1077 de 2015 (disponibilidad de servicios como requisito de licencia) · Decreto 1076 de 2015 (concesión de aguas). **[RL]**

---

### 6.2 Alcantarillado o solución individual de saneamiento

**Objetivo.** Definir y legalizar a dónde van las aguas residuales.

**Actividades.**
- **6.2.1** Verificar la existencia de **red de alcantarillado** en la vereda. Si existe: solicitar **disponibilidad de alcantarillado** en los mismos términos de 6.1.2.
- **6.2.2** Si no existe (escenario probable): definir la **solución individual o colectiva de tratamiento** (5.6.4).
- **6.2.3** Tramitar ante **Corpoboyacá** lo que corresponda para el **vertimiento**. **[RL] ⚠ VERIFICAR con Corpoboyacá cuál de estas dos rutas aplica:** para vertimientos de aguas residuales domésticas de viviendas unifamiliares existe un régimen simplificado (registro de la solución individual de saneamiento) introducido por el **Decreto 050 de 2018**, que modificó el Decreto 1076 de 2015; para otros casos se requiere **permiso de vertimientos** con evaluación ambiental del vertimiento y plan de gestión del riesgo. **La diferencia entre una ruta y otra son meses y millones.**
- **6.2.4** Preparar la documentación técnica: memoria de diseño del sistema, prueba de percolación, planos, caracterización esperada del vertimiento conforme a la **Resolución 0631 de 2015** si aplica.
- **6.2.5** Definir el **régimen de mantenimiento** del sistema (quién, cada cuánto, con qué costo) y trasladarlo al manual del propietario y al reglamento de PH.

**Entregables verificables.** Disponibilidad de alcantarillado **o** acto administrativo de Corpoboyacá (permiso de vertimientos o constancia de registro) con radicado · Memoria de diseño del sistema · Protocolo de mantenimiento.

**Responsable.** JUR radica · DAO aporta lo técnico · 🔧 ingeniero hidrosanitario/ambiental, Corpoboyacá.

**Precedencias.** Requiere 5.2.5 y 5.6.4. **Puede bloquear 7.1** si la curaduría lo exige como parte de la disponibilidad de servicios **⚠ VERIFICAR**.

**Duración.** 6–16 semanas si se requiere permiso de vertimientos; menos si aplica el régimen de registro **⚠ VERIFICAR**.

**Costos.** Tarifa de evaluación y de seguimiento de la autoridad ambiental · diseño · construcción del sistema · mantenimiento periódico.

**Riesgos.** *Construir y vender con un sistema séptico no legalizado* → sanción ambiental que recae sobre el propietario final y sobre el constructor, y **problema en la escrituración si el comprador hace debida diligencia**. *Suelo con mala infiltración* → sistema compacto de tratamiento, mucho más caro.

**Marco normativo.** Decreto 1076 de 2015 · Decreto 050 de 2018 · Resolución 0631 de 2015 · Resolución 0330 de 2017 (RAS) · Ley 1333 de 2009. **[RL]**

---

### 6.3 Energía eléctrica

**Objetivo.** Asegurar el punto de conexión y su costo antes de diseñar y de prometer entregas.

**Actividades.**
- **6.3.1** Solicitar al **operador de red** el **punto de conexión y la disponibilidad de servicio** para 5 viviendas más zonas comunes. **[RL]**
- **6.3.2** Determinar si se requiere **transformador propio**, extensión de red en media tensión, o postería adicional, y **quién asume ese costo**. **[PM] Normalmente lo asume el urbanizador y se entrega la red al operador.**
- **6.3.3** Someter el **proyecto eléctrico a aprobación del operador de red** (5.5.3).
- **6.3.4** Definir **medidores individuales** y el trámite de matrícula de cada uno.
- **6.3.5** Tramitar el **servicio provisional de obra** (ver 9.5).

**Entregables verificables.** Carta de disponibilidad de energía · Aprobación del proyecto eléctrico · Presupuesto de conexión aprobado.

**Responsable.** DAO gestiona · 🔧 operador de red, ingeniero eléctrico.

**Precedencias.** Paraleliza con 6.1. Bloquea 7.1 (si la curaduría la exige) y 10.6.

**Duración.** 4–10 semanas **⚠ VERIFICAR**.

**Costos.** Estudio de conexión · transformador y red · medidores · derechos de conexión.

**Riesgos.** *Costo de conexión no presupuestado* → puede ser un renglón de varias decenas de millones en suelo rural. **Mitigación:** pedir el presupuesto de conexión **antes** del hito G-2.

**Marco normativo.** Ley 143 de 1994 · Ley 142 de 1994 · RETIE · reglamentación CREG. **[RL]**

---

### 6.4 Gas y otros servicios

**Objetivo.** Definir la solución de gas y las previsiones de telecomunicaciones y recolección de residuos.

**Actividades.**
- **6.4.1** Verificar si existe **red de gas natural domiciliario** en la vereda y quién es el distribuidor **⚠ VERIFICAR**. Solicitar disponibilidad.
- **6.4.2** Si no hay red: definir solución (tanque estacionario individual o cilindros), sus **retiros de seguridad** y su impacto en el diseño y en el precio.
- **6.4.3** Verificar **recolección de residuos sólidos**: si el prestador municipal cubre la vereda; si no, definir la solución y su costo, que será carga de la PH.
- **6.4.4** Verificar disponibilidad de **internet y telefonía** (argumento comercial relevante para el comprador que trabaja desde casa, que es exactamente el perfil objetivo).
- **6.4.5** Alumbrado de la vía interna: definir si es privado (bien común de la PH) o público, y quién paga el consumo.

**Entregables verificables.** Cartas de disponibilidad o constancias de no disponibilidad · Solución técnica documentada para cada servicio faltante.

**Responsable.** DAO · ADM (residuos) · COM (relevancia comercial de internet).

**Precedencias.** Paraleliza con 6.1–6.3.

**Duración.** 2–4 semanas.

**Costos.** Derechos de conexión de gas · tanques estacionarios · alumbrado.

**Riesgos.** *Prometer gas natural en el brochure sin red disponible* → publicidad engañosa (Ley 1480 de 2011) y reclamación de posventa. **Mitigación:** el material comercial solo dice lo que está documentado (ver 8.1.5).

**Marco normativo.** Ley 142 de 1994 · NTC 2505 · reglamentación CREG. **[RL]**

---

### 6.5 Permisos ambientales específicos

**Objetivo.** Obtener los permisos que el diseño definitivo haga necesarios.

**Actividades.**
- **6.5.1** **Permiso de aprovechamiento forestal** ante Corpoboyacá si hay tala de árboles (3.5.3). **[RL]** Incluye normalmente **compensación** (siembra de individuos de reemplazo), que es costo y obligación de seguimiento.
- **6.5.2** **Permiso de ocupación de cauce** si alguna obra cruza la quebrada. **[RL]**
- **6.5.3** **Concesión de aguas** si se capta agua directamente (6.1.5). **[RL]**
- **6.5.4** **Permiso de vertimientos o registro** (6.2.3). **[RL]**
- **6.5.5** **Manejo de escombros (RCD)**: definir el gestor autorizado y el sitio de disposición final. **[RL]** La disposición de residuos de construcción y demolición está reglamentada y el generador es responsable. **⚠ VERIFICAR la resolución vigente y los gestores autorizados en Duitama.**
- **6.5.6** Definir el **plan de manejo ambiental de obra**: control de material particulado, ruido en horarios permitidos, manejo de aguas de obra, sanitarios portátiles.

**Entregables verificables.** Actos administrativos de cada permiso con radicado · Contrato con gestor autorizado de RCD · Plan de manejo ambiental de obra.

**Responsable.** JUR radica · DAO técnico · ADM opera en obra · 🔧 Corpoboyacá, gestor de RCD.

**Precedencias.** Requiere 5.1 y 5.6 definitivos. Algunos permisos **bloquean el inicio de obra**.

**Duración.** 6–20 semanas según el permiso **⚠ VERIFICAR con Corpoboyacá**.

**Costos.** Tarifas de evaluación y seguimiento · compensaciones forestales · gestión de RCD.

**Riesgos.** *Talar primero y pedir permiso después* → sanción de la Ley 1333 de 2009, que incluye multas y suspensión, y **la sanción recae sobre el propietario del predio (Rosa) además del ejecutor**. **Mitigación:** ningún corte sin acto administrativo en mano.

**Marco normativo.** Decreto 1076 de 2015 · Ley 99 de 1993 · Ley 1333 de 2009 · normativa de RCD **⚠ VERIFICAR**. **[RL]**


---

## FASE 7 — LICENCIAMIENTO URBANÍSTICO

*Objetivo de la fase: obtener las licencias en firme. **Hasta que la licencia no esté ejecutoriada, no hay proyecto: hay una idea con planos.***

---

### 7.1 Preparación y radicación de la solicitud de licencia

**Objetivo.** Radicar completo y en legal forma, para no perder meses en subsanaciones.

**Actividades.**
- **7.1.1** Armar la **lista de chequeo documental** definitiva con la curaduría (HE-8). **[RL] El listado exacto lo fija el Decreto 1077 de 2015 y la curaduría lo aplica; ⚠ VERIFICAR el listado vigente.** Típicamente incluye:
  - **7.1.1.1** Formulario Único Nacional para la solicitud de licencias, diligenciado y firmado por el titular.
  - **7.1.1.2** **Certificado de tradición y libertad** con expedición reciente (usualmente no mayor a un mes).
  - **7.1.1.3** Copia del documento de identidad del titular; poder debidamente otorgado si actúa por apoderado; **autorización del propietario** si el solicitante no es el dueño (3.4).
  - **7.1.1.4** Copia del **recibo de pago del impuesto predial** del último período.
  - **7.1.1.5** **Plano de localización e identificación del predio**.
  - **7.1.1.6** **Relación de la dirección de los vecinos colindantes** (Pablo, Óscar, Marta y demás).
  - **7.1.1.7** **Planos arquitectónicos** firmados por arquitecto con matrícula vigente.
  - **7.1.1.8** **Planos estructurales, memorias de cálculo y estudio geotécnico**, firmados por ingeniero civil con matrícula vigente.
  - **7.1.1.9** **Certificados de disponibilidad de servicios públicos** (Fase 6).
  - **7.1.1.10** **Copia de las matrículas profesionales y certificados de vigencia (COPNIA / CPNAA)** de los profesionales que firman.
  - **7.1.1.11** Constancia de **pago de expensas**.
- **7.1.2** Liquidar las **expensas de curaduría**. **[RL]** Las expensas se liquidan conforme a la fórmula reglamentaria (cargo fijo + cargo variable en función, entre otros, del valor del proyecto, el uso, el estrato y el salario mínimo). **⚠ VERIFICAR la liquidación exacta con la curaduría de Duitama: es la única que puede darla.** **≈ ORDEN DE MAGNITUD: en proyectos de vivienda pequeños las expensas suelen representar entre el 0,5% y el 1,5% del presupuesto de obra — dato a validar, no a presupuestar.**
- **7.1.3** Verificar si aplica el **impuesto de delineación urbana** en Duitama y liquidarlo (2.1.5). **[RL] ⚠ VERIFICAR.**
- **7.1.4** Verificar si se causa **participación en plusvalía** y, de causarse, su liquidación y forma de pago. **[RL] ⚠ VERIFICAR ante la Secretaría de Hacienda.**
- **7.1.5** Radicar y obtener el **número de radicación**. **[RL] Desde la radicación en legal forma corren los términos legales del trámite.**
- **7.1.6** Si se mantiene D-07 (dos licencias): radicar **dos expedientes coordinados**, con la misma base topográfica, el mismo urbanismo y áreas claramente delimitadas.

**Entregables verificables.** **Radicado de la solicitud** (número y fecha) · Recibo de pago de expensas · Copia completa del expediente radicado, archivada en Drive.

**Responsable.** JUR lidera · DAO aporta lo técnico · 🔧 curador urbano, arquitecto, calculista, geotecnista.

**Precedencias.** Requiere **todo**: 3.1/3.2 (folio), 3.4 (autorización), 5.3, 5.4, 5.2, 6.1, 6.3. **Es el cuello de botella del proyecto.**

**Duración.** 2–3 semanas de preparación documental.

**Costos.** **Expensas de curaduría** (el desembolso individual más grande de la etapa previa a obra) · impuesto de delineación si aplica · plusvalía si aplica · certificados · impresiones.

**Riesgos.** *Radicar incompleto para "ganar tiempo"* → no se radica en legal forma y no corren términos: se pierde tiempo, no se gana. *Certificado de tradición vencido al momento de la radicación* → devolución.

**Marco normativo.** Ley 388 de 1997 · Decreto 1077 de 2015, Título 6 · Ley 810 de 2003 · Estatuto Tributario Municipal de Duitama. **[RL]**

---

### 7.2 Trámite, citación a vecinos y subsanación

**Objetivo.** Llevar el expediente hasta la resolución, sin sorpresas.

**Actividades.**
- **7.2.1** **Citación a los vecinos colindantes y publicación**. **[RL]** El trámite de licencias contempla la comunicación a vecinos colindantes y la publicación (valla o aviso en el predio), para que los terceros interesados puedan constituirse en parte. **⚠ VERIFICAR el procedimiento y los términos exactos con la curaduría.** **[RE] Dado que los colindantes son familiares (Pablo, Óscar, Marta) y que el acta reporta que Marta no responde llamadas, este paso merece manejo personal previo: es preferible una conversación antes de que llegue la citación.**
- **7.2.2** Atender el **acta de observaciones** de la curaduría dentro del plazo, con la participación de los diseñadores (cláusula de 4.5.3).
- **7.2.3** Gestionar prórrogas de plazo para subsanar, si se requieren.
- **7.2.4** Obtener la **resolución de licencia** y verificar su **ejecutoria** (firmeza). **[RL] Una licencia no ejecutoriada no habilita a iniciar obra.**
- **7.2.5** Revisar la resolución línea por línea: modalidad, vigencia, áreas aprobadas, condicionamientos, obligaciones de cesión, obligaciones ambientales.
- **7.2.6** **Instalar la valla informativa de la licencia** en el predio. **[RL]** Es obligación del titular y su omisión es infracción urbanística.
- **7.2.7** Registrar en el tablero la **fecha de vencimiento de la licencia** y la **fecha límite para solicitar prórroga**, con alarma. **[RE] Este es el control más olvidado y el más caro de olvidar.**

**Entregables verificables.** **Resolución de licencia** · Constancia de ejecutoria · Constancia de citación a vecinos · Fotografía de la valla instalada · Ficha de control de vigencia y prórroga.

**Responsable.** JUR lidera · DAO subsana lo técnico.

**Precedencias.** Requiere 7.1.

**Duración.** **8–16 semanas** en el escenario normal, incluyendo una ronda de observaciones. **⚠ VERIFICAR los términos legales exactos con la curaduría de Duitama** (el trámite tiene plazos reglados, con suspensión del término mientras el solicitante subsana). Si hay oposición de vecinos o el expediente es complejo, puede extenderse.

**Costos.** Subsanaciones · valla informativa · eventuales expensas adicionales por modificación.

**Riesgos.** 🔴 *Negación de la licencia por densidad, uso o servicios* → el proyecto se detiene. **Mitigación:** 2.1 y 6.1 bien hechos hacen improbable la negación. *Oposición de un vecino familiar* → manejo previo. *Dejar vencer la licencia mientras se venden las casas* → con horizonte de hasta 3 años, este riesgo es alto: **iniciar obra dentro de la vigencia protege el derecho a la prórroga**.

**Marco normativo.** Ley 388 de 1997 · Decreto 1077 de 2015 · Ley 1437 de 2011 (CPACA, procedimiento administrativo) · Ley 810 de 2003 (sanciones urbanísticas). **[RL]**

---

### 7.3 Licencia de intervención y ocupación del espacio público (si aplica)

**Objetivo.** Poder intervenir legalmente la vía, el andén y el espacio público para el acceso y las redes.

**Actividades.**
- **7.3.1** Determinar si la intervención del acceso, el andén de 2 m, el cruce de redes o la conexión vial requieren esta licencia. **[RL] ⚠ VERIFICAR con Planeación y la curaduría.**
- **7.3.2** Radicar la solicitud con los diseños correspondientes.
- **7.3.3** Coordinar con la **empresa de servicios públicos** el permiso de rotura de vía si hay que cruzar la calzada.
- **7.3.4** Obtener la licencia o el permiso y ejecutar dentro de su vigencia.

**Entregables verificables.** Licencia o permiso de intervención del espacio público · Permiso de rotura de vía.

**Responsable.** JUR · DAO · 🔧 Secretaría de Infraestructura / Planeación de Duitama.

**Precedencias.** Requiere 5.1. Bloquea las obras de acceso (10.2).

**Duración.** 4–8 semanas **⚠ VERIFICAR**.

**Costos.** Derechos de trámite · pólizas que exija el municipio · reposición del pavimento.

**Riesgos.** *Intervenir el espacio público sin permiso* → sanción urbanística y orden de restitución.

**Marco normativo.** Decreto 1077 de 2015 (licencia de intervención y ocupación del espacio público) · Ley 9 de 1989 · normas municipales. **[RL]**

---

## FASE 8 — ESTRUCTURACIÓN COMERCIAL Y LANZAMIENTO

*Objetivo de la fase: convertir el proyecto en un producto vendible y **legalmente comercializable**. Esta fase tiene una frontera legal que el acta no identifica y que hay que respetar: **cuándo se puede promocionar y cuándo se puede recibir plata.***

---

### 8.1 Marca, identidad y piezas de comunicación

**Objetivo.** Tener el material con el que se vende, alineado con lo que la licencia aprobó.

**Actividades.**
- **8.1.1** Nombre definitivo y concepto de marca; 3 opciones (S-3, tema abierto N.° 4). Verificar **disponibilidad del nombre**: dominio, redes, y **antecedentes marcarios ante la SIC** si se va a registrar la marca. **[RE] Registrar la marca solo tiene sentido si la visión de largo plazo (7.7 del acta: empresa de desarrollo inmobiliario) se materializa; para un proyecto único no es prioritario.**
- **8.1.2** Logo e identidad visual; manual básico de marca.
- **8.1.3** **Renders exteriores de fachada (prioridad 1)** iterando con los sketches de DAO (S-4, HI-15).
- **8.1.4** Renders interiores y video recorrido / animación (S-5).
- **8.1.5** **Brochure, ficha comercial, planos comerciales y tabla de precios** (S-7). **[RL] Regla dura: toda afirmación del material comercial debe estar respaldada por un documento del proyecto** (licencia, disponibilidad de servicios, especificación de acabados). Lo que se anuncia obliga (Ley 1480 de 2011, arts. 29 a 33). **Y los renders deben llevar la leyenda de que las imágenes son ilustrativas y que la entrega se rige por la especificación de acabados anexa a la promesa.**
- **8.1.6** Fotografía profesional por avance de obra (insumo del "libro del propietario", S-12).
- **8.1.7** Material físico: valla en el lote, pendones, brochure impreso, tarjetas, señalización interna.
- **8.1.8** Material de presentación para vendedores y **guion de venta** con las objeciones previstas (acceso destapado, distancia al perímetro urbano, sistema séptico, acueducto veredal) y su respuesta documentada.

**Entregables verificables.** Manual de marca · Renders aprobados · Brochure y ficha comercial versionados · Tabla de precios firmada · Valla instalada · Carpeta de vendedores.

**Responsable.** COM lidera · DAO valida coherencia técnica de cada pieza · JUR revisa las leyendas legales.

**Precedencias.** Los renders requieren 5.3 (fachada cerrada). El brochure y la tabla de precios requieren **7.2 (licencia)** y **5.7 (costo real)**.

**Duración.** 6–10 semanas, en paralelo con el trámite de licencia.

**Costos.** Diseño gráfico · renders y video (si se externalizan) · impresión · valla · fotografía.

**Riesgos.** *Producir el brochure antes de la licencia y tener que rehacerlo* → costo y credibilidad. *Prometer especificaciones que después no se cumplen* → reclamación bajo el Estatuto del Consumidor. **Mitigación:** el material comercial se congela cuando se congela la especificación de acabados (5.3.6).

**Marco normativo.** Ley 1480 de 2011 (Estatuto del Consumidor) · Decisión Andina 486 de 2000 (propiedad industrial) si se registra la marca. **[RL]**

---

### 8.2 Habilitación legal para enajenar vivienda 🔴

**Objetivo.** Poder recibir dinero del público sin cometer una infracción. **Esta subfase no está en el acta y es la que gobierna todo el flujo de caja del proyecto.**

**Actividades.**
- **8.2.1** Determinar ante qué dependencia del municipio de Duitama se hace la **radicación de documentos para la enajenación de inmuebles destinados a vivienda**. **[RL] ⚠ VERIFICAR: la vigilancia de esta actividad está a cargo de los municipios (art. 71 de la Ley 388 de 1997), sobre la base de la Ley 66 de 1968 y el Decreto 2610 de 1979, hoy desarrollados en el Decreto 1077 de 2015.**
- **8.2.2** Armar el expediente que exija el municipio, que típicamente comprende: folio de matrícula del predio, licencia urbanística, planos aprobados, **presupuesto financiero del proyecto**, modelo del contrato que se usará con los compradores, información del enajenante, y constancia sobre el manejo de los recursos. **⚠ VERIFICAR el listado exacto ante Duitama.**
- **8.2.3** Radicar y obtener la **constancia o acto que habilita la enajenación**.
- **8.2.4** Definir el **mecanismo de manejo de los dineros recibidos antes de la escrituración**. **[RE] Tres opciones, de mejor a peor:**
  - **(a) Encargo fiduciario de preventa** con condición de **punto de equilibrio**: la plata solo se libera cuando el proyecto alcanza las ventas y la licencia necesarias. Es el estándar del sector y el mejor argumento de venta frente a un comprador que le va a entregar $150 millones a una persona natural.
  - **(b) Cuenta bancaria exclusiva del proyecto** con firmas conjuntas, conciliación mensual y reporte al comprador.
  - **(c) Cuenta personal del socio gestor.** **Esta opción no debería considerarse:** mezcla patrimonios, es indefendible ante la DIAN, ante un comprador que reclame y ante los propios socios.
- **8.2.5** Definir el **punto de equilibrio del proyecto**: cuántas unidades vendidas y con qué recaudo se requieren para iniciar obra sin riesgo de quedarse a mitad. **[RE] Con costo de $1.815 millones y capital propio de $40–50 millones, yo no iniciaría obra con menos de 2 unidades vendidas con cuota inicial efectivamente recaudada, y presupuestaría el arranque solo de esas dos.**

**Entregables verificables.** **Constancia municipal de radicación para enajenación** · Contrato de encargo fiduciario o reglamento de la cuenta del proyecto · Documento de punto de equilibrio aprobado por los cuatro socios.

**Responsable.** JUR lidera · ADM opera lo financiero · 🔧 municipio, fiduciaria, banco.

**Precedencias.** Requiere **7.2 (licencia)** y 4.2. **Bloquea 8.5 (recibir dinero).**

**Duración.** 3–6 semanas **⚠ VERIFICAR**.

**Costos.** Derechos de trámite · comisión fiduciaria si se adopta encargo · costos bancarios.

**Riesgos.** 🔴 *Recibir separaciones y cuotas iniciales antes de esta radicación* → **infracción administrativa, exposición a sanción y a la obligación de devolver**, y una posición jurídica pésima si un comprador se arrepiente. *No tener punto de equilibrio definido* → arrancar obra con una sola venta y quedarse sin caja en el mes 6, que es exactamente cómo mueren los proyectos pequeños.

**Marco normativo.** Ley 66 de 1968 · Decreto 2610 de 1979 · Ley 388 de 1997, art. 71 · Decreto 1077 de 2015 (enajenación de inmuebles destinados a vivienda). **[RL]**

---

### 8.3 Documentos de vinculación del comprador

**Objetivo.** Que cada peso que entre esté respaldado por un contrato que proteja a las dos partes.

**Actividades.**
- **8.3.1** **Contrato de separación / vinculación** (para los ~$5 millones iniciales): objeto, plazo de vigencia de la separación, **condiciones de devolución**, imputación al precio, y qué pasa si el comprador no firma la promesa.
- **8.3.2** **Promesa de compraventa** (HE-11). **[RL] Contenido mínimo:**
  - **8.3.2.1** Identificación plena de las partes y del inmueble (**folio de matrícula, cabida, linderos, número de unidad privada y coeficiente si hay PH**).
  - **8.3.2.2** Precio, forma de pago detallada (separación $5 millones, 30% dentro de los primeros 30 días, saldo en cuotas atadas al avance de obra) y **destino de los dineros**.
  - **8.3.2.3** **Fecha, hora y notaría determinadas para el otorgamiento de la escritura** — es requisito de validez de la promesa en el derecho colombiano (Ley 153 de 1887, art. 89). **Una promesa sin fecha, hora y notaría precisas es ineficaz.** Este es el error más frecuente en promesas artesanales.
  - **8.3.2.4** **Plazo y condiciones de entrega material**, con la especificación de acabados **anexa y firmada**.
  - **8.3.2.5** **Arras** (definir si son confirmatorias o de retractación: la diferencia es enorme y hay que ser explícito) y **cláusula penal**.
  - **8.3.2.6** **Condiciones resolutorias**: qué pasa si no se obtiene la PH, si el comprador no obtiene el crédito, si hay fuerza mayor, si el proyecto no alcanza el punto de equilibrio. **[RE] Incluir siempre la condición de crédito: si el banco niega el crédito del comprador por causas no imputables a él, se devuelve lo pagado descontando un porcentaje pactado. Sin esa cláusula el proyecto termina en pleito.**
  - **8.3.2.7** Régimen de **gastos notariales, de registro e impuestos**, y quién paga qué (4.4.9).
  - **8.3.2.8** Cláusula de **cesión** del contrato y sus condiciones.
  - **8.3.2.9** Manifestación sobre el **régimen de PH** y aceptación anticipada del reglamento.
- **8.3.3** **Contrato de vinculación de inmobiliarias**: comisión (referencia del acta: 2–3% por venta), **exclusividad o no**, duración, qué gastos asume cada parte, **quién es el dueño del cliente**, y regla anti-doble comisión. **[PM] La exclusividad se concede solo a cambio de compromisos verificables de inversión y de tiempo; de lo contrario, régimen abierto con regla clara de registro de clientes.**
- **8.3.4** **Contrato de vendedores propios** y esquema de bonificaciones.
- **8.3.5** Protocolo de **habeas data** para la base de datos de interesados. **[RL] La captación de datos por la landing y por la pauta obliga a tener política de tratamiento de datos personales y a registrar la base ante la SIC cuando corresponda. ⚠ VERIFICAR el umbral de registro vigente.**

**Entregables verificables.** Minutas aprobadas de separación, promesa, contrato con inmobiliarias y contrato de vendedores · Política de tratamiento de datos publicada · Anexo de especificaciones firmado.

**Responsable.** JUR redacta · COM aporta lo comercial · ADM controla la ejecución de pagos.

**Precedencias.** Requiere 4.4 (tributario), 5.3.6 (especificaciones), 7.2 (licencia), 8.2. **Debe existir ANTES de la primera separación.**

**Duración.** 3–4 semanas.

**Costos.** Honorarios jurídicos · autenticaciones · eventual registro de base de datos.

**Riesgos.** *Recibir separaciones con un recibo de caja y sin contrato* → cuando el comprador pida su plata de vuelta, no hay regla. *Promesa sin fecha, hora y notaría* → ineficaz. *Prometer entrega en una fecha que la obra no puede cumplir* → cláusula penal en contra del proyecto.

**Marco normativo.** Ley 153 de 1887, art. 89 (requisitos de la promesa) · Código Civil (arras, cláusula penal, condición resolutoria) · Ley 1480 de 2011 · Ley 1581 de 2012 (habeas data). **[RL]**

---

### 8.4 Plataforma digital y pauta

**Objetivo.** Generar demanda medible al menor costo por interesado calificado.

**Actividades.**
- **8.4.1** Landing page o sitio web del proyecto, con sección **"¿Tienes un lote?"** para captar futuros proyectos (S-8, visión 7.7).
- **8.4.2** Dominio y alojamiento.
- **8.4.3** Campañas en redes sociales y en buscadores; **remarketing** a visitantes (S-9).
- **8.4.4** **Portales inmobiliarios**: publicación por inmueble, destacados y renovaciones. **⚠ VERIFICAR tarifas vigentes de los portales; se cotizan por publicación y por período.**
- **8.4.5** Producción y gestión de contenido (avance de obra como contenido: es lo que mejor funciona en vivienda).
- **8.4.6** **Definir los indicadores**: costo por lead, leads por semana, tasa de visita, tasa de cierre, y **costo de adquisición por venta**. **[RE] Sin estos cuatro números, el presupuesto de marketing es un gasto, no una inversión.**
- **8.4.7** Presentar el **presupuesto de marketing como capítulo independiente** (S-11, D-10).

**Entregables verificables.** Sitio publicado · Cuentas de pauta configuradas · Publicaciones en portales activas · Tablero de indicadores comerciales semanal.

**Responsable.** COM.

**Precedencias.** Requiere 8.1. **La pauta que invite a "separar" o a "comprar" requiere 8.2.** Antes de eso solo se puede hacer comunicación de expectativa **[RL] — ver 8.5**.

**Duración.** 4–6 semanas para montar; permanente después.

**Costos.** Dominio y hosting · pauta mensual · portales · producción de contenido.

**Riesgos.** *Prender la pauta antes de tener licencia y con qué responder* → se quema el mercado y se generan leads que no se pueden atender. *Medir "me gusta" en vez de costo por venta* → se gasta sin saber si funciona.

**Marco normativo.** Ley 1480 de 2011 · Ley 1581 de 2012. **[RL] parcial.**

---

### 8.5 Frontera legal de la comercialización: qué se puede hacer y cuándo 🔴

**Objetivo.** Que nadie del equipo cometa, por entusiasmo, una infracción que ponga en riesgo el proyecto.

**Regla operativa (tabla de semáforo):**

| Momento | Se PUEDE | NO se puede |
|---|---|---|
| **Antes de la licencia** | Comunicación de expectativa: "próximamente", marca, ubicación, concepto. Levantar base de datos de interesados con habeas data. Sondeo de precio. | Ofrecer unidades determinadas · publicar precios como oferta en firme · **recibir dinero de cualquier naturaleza** · firmar separaciones o promesas |
| **Con licencia ejecutoriada, sin radicación municipal (8.2)** | Publicar el proyecto, sus planos aprobados y sus especificaciones. Recibir manifestaciones de interés **sin dinero**. | **Recibir dinero del público** (separaciones, cuotas iniciales) |
| **Con licencia + radicación municipal (8.2) + minutas (8.3) + mecanismo de manejo de recursos (8.2.4)** | Separaciones, promesas de compraventa y recaudo conforme al esquema pactado | Prometer fechas de entrega que la programación de obra no soporte |
| **Con PH constituida y folios abiertos (Fase 11)** | Escriturar y radicar créditos hipotecarios de los compradores | — |

**Actividades.**
- **8.5.1** Socializar esta tabla con los cuatro socios y con toda inmobiliaria vinculada, **por escrito**.
- **8.5.2** Incluir en el contrato con inmobiliarias la **prohibición expresa de recibir dinero** a nombre del proyecto.
- **8.5.3** Definir un **único canal de recaudo**: la cuenta del proyecto o el encargo fiduciario. Ningún socio recibe plata en efectivo ni en su cuenta personal. **[RE] Sin excepciones, ni siquiera "por esta vez".**

**Entregables verificables.** Documento de política comercial firmado por los cuatro · Cláusula incorporada en los contratos con inmobiliarias.

**Responsable.** JUR emite · COM cumple y hace cumplir · ADM controla el recaudo.

**Precedencias.** Requiere 8.2 y 8.3.

**Duración.** 1 semana.

**Costos.** Ninguno.

**Riesgos.** 🔴 *Un vendedor entusiasta que recibe una separación en efectivo antes de tiempo* → responsabilidad del gestor. **Mitigación:** política escrita y un solo canal de recaudo.

**Marco normativo.** Ley 66 de 1968 · Decreto 2610 de 1979 · Ley 388 de 1997, art. 71 · Decreto 1077 de 2015 · Ley 1480 de 2011. **[RL]**

---

### 8.6 Canales, alianzas y operación comercial

**Objetivo.** Poner el producto donde está el comprador.

**Actividades.**
- **8.6.1** Contactar a Osvaldo Martínez (Villa de Leyva) y mapear inmobiliarias de Villa de Leyva, Tunja, Sáchica, Paipa, Sogamoso y Bogotá (S-10).
- **8.6.2** Inmobiliarias de Bogotá especializadas en el corredor de Boyacá.
- **8.6.3** Definir **sala de ventas**: por ahora la oficina; evaluar **casa modelo** si el proyecto lo justifica. **[RE] La casa modelo es el mejor acelerador de ventas en vivienda campestre, pero inmoviliza una unidad y su costo. Con 5 unidades, evaluarlo solo si la absorción se estanca; alternativa intermedia: terminar primero una casa completa y venderla al final.**
- **8.6.4** Protocolo de atención al interesado: tiempo máximo de respuesta, visitas al lote, material que se entrega, registro en CRM.
- **8.6.5** Comité comercial semanal con los cuatro indicadores de 8.4.6.
- **8.6.6** Definir la **política de cuota inicial mínima** (tema abierto N.° 7 del acta). **[RE] Con este esquema de financiación, la cuota inicial mínima debería cubrir al menos el costo directo de construir la unidad hasta obra gris; por debajo de eso, el proyecto está financiando al comprador con plata que no tiene.**

**Entregables verificables.** Mapa de canales con contactos y condiciones · Contratos firmados con inmobiliarias · CRM operativo · Acta semanal del comité comercial.

**Responsable.** COM lidera · DAO acompaña visitas técnicas · ADM controla comisiones.

**Precedencias.** Requiere 8.1, 8.3, 8.5.

**Duración.** 4–6 semanas para montar; permanente después.

**Costos.** Comisiones (2–3% + gastos de atención) · CRM · desplazamientos · casa modelo si se decide.

**Riesgos.** *Depender de un solo canal* → si la inmobiliaria no trae clientes, no hay plan B. *Comisiones no presupuestadas al ceder exclusividad* → controlar contra 4.5.6.

**Marco normativo.** Código de Comercio (corretaje, arts. 1340 y ss.) · Ley 1480 de 2011. **[PM] / [RL] parcial.**

---

## FASE 9 — PREPARACIÓN DE OBRA

*Objetivo de la fase: que el día que se dé la orden de inicio, todo esté contratado, afiliado, asegurado y controlado. **Es la fase que separa una obra de un desorden costoso.***

---

### 9.1 Contratación de obra

**Objetivo.** Cerrar precios y responsabilidades antes de mover tierra.

**Actividades.**
- **9.1.1** Definir la **estrategia de contratación**: por capítulos con varios contratistas, o un contratista general. **[RE] Con socios de dedicación parcial, un contratista general con precio cerrado por unidad reduce la carga de gestión, aunque cueste más. Contratar por capítulos exige presencia diaria que este equipo no tiene.** Esto merece una decisión explícita, no una deriva.
- **9.1.2** Preparar **pliegos de invitación** por capítulo con cantidades, especificaciones y condiciones (usando 5.7.6).
- **9.1.3** Invitar mínimo **tres oferentes por capítulo** y elaborar **cuadro comparativo** normalizado (misma cantidad, misma especificación).
- **9.1.4** Verificar a cada contratista: RUT, matrícula mercantil si aplica, experiencia verificable, **capacidad de afiliar a su personal**, referencias, y estado de la seguridad social.
- **9.1.5** Suscribir contratos con el modelo de 4.5.1 y exigir **pólizas** (4.5.2).
- **9.1.6** Definir el **cronograma de pagos por actas parciales** y su articulación con el flujo de caja del recaudo. **[RE] Regla: el proyecto nunca debe pagar avance de obra por encima del recaudo acumulado. Esa sola regla evita la quiebra de un proyecto sin crédito.**
- **9.1.7** Referencia del acta: ~$300.000/m² de mano de obra a contratista que pone su gente. **Validar contra el mercado de Duitama en 2026 y contra el escenario de mano de obra formalizada (9.3), que es más cara.**

**Entregables verificables.** Cuadros comparativos por capítulo · Contratos firmados · Pólizas expedidas y vigentes · Cronograma de pagos.

**Responsable.** ADM lidera el proceso · DAO define alcances técnicos · JUR revisa contratos.

**Precedencias.** Requiere 5.7, 4.5, 7.2 (licencia) y 8.2 (punto de equilibrio). **No se contrata obra antes de tener licencia y punto de equilibrio.**

**Duración.** 4–6 semanas.

**Costos.** Costo de la obra contratada · pólizas · tiempo de gestión.

**Riesgos.** *Contratar al primero que cotice* → sobreprecio invisible. *Contratistas sin capacidad de formalizar* → traslada el riesgo laboral al proyecto (ver 9.3). *Anticipos sin amparo* → el anticipo debe estar cubierto por póliza o ser mínimo.

**Marco normativo.** Código Civil y Código de Comercio · CST art. 34. **[RL] parcial.**

---

### 9.2 Organización de obra, almacén y control de costos

**Objetivo.** Que se sepa, todas las semanas, cuánto se ha gastado y contra qué.

**Actividades.**
- **9.2.1** Implementar el **formato de control de contratistas** (MM-1): contratado, ejecutado, facturado, pagado, saldo, retenciones.
- **9.2.2** Implementar el **control de almacén** (MM-2): entradas, salidas, existencias, responsable, herramienta y equipo. **[RE] En obras pequeñas la fuga de material es del orden del 3% al 8% del costo de materiales. Un almacén con control cuesta menos que la fuga.**
- **9.2.3** Definir el **circuito de compra**: requisición → cotizaciones → orden de compra → recibo en obra → entrada a almacén → cuenta por pagar. Sin orden de compra no hay pago.
- **9.2.4** **Cierre de costos mensual** contra presupuesto, con explicación de desviaciones por capítulo.
- **9.2.5** Instalar **campamento, almacén cerrado, sanitarios de obra y cerramiento provisional**.
- **9.2.6** Definir **vigilancia** del predio y de los materiales. **[RE] En predios rurales aislados esta partida se olvida y termina costando más que el vigilante.**
- **9.2.7** Definir el **régimen de bitácora de obra**: registro diario firmado por el residente.

**Entregables verificables.** Formatos operativos en uso · Informe mensual de costos · Bitácora de obra · Inventario de almacén.

**Responsable.** ADM lidera · DAO valida avances técnicos.

**Precedencias.** Requiere 4.5.5 y 9.1.

**Duración.** 3–4 semanas para montar; permanente después.

**Costos.** Campamento y almacén · vigilancia · papelería · tiempo de ADM.

**Riesgos.** *Control de costos mensual que llega dos meses tarde* → se descubre la desviación cuando ya no hay margen de maniobra. **Mitigación:** cierre mensual con fecha fija.

**Marco normativo.** No aplica directamente.

---

### 9.3 Seguridad y salud en el trabajo (SST) y formalización laboral 🔴

**Objetivo.** Que nadie se accidente, y que si algo pasa, el proyecto y sus socios estén cubiertos. **Es el frente peor resuelto del acta.**

**Actividades.**
- **9.3.1** Decidir el **modelo de vinculación** (tema abierto N.° 6, HE-10). Las opciones reales son:
  - **(a) Contratistas formales** que afilian a su personal y lo acreditan mes a mes. **[RE] Es la opción recomendada.** Cuesta más en el precio unitario y menos en riesgo.
  - **(b) Vinculación directa** por el proyecto con contrato de obra o labor, afiliación a salud, pensión, ARL, caja de compensación, parafiscales y prestaciones. Más control, más carga administrativa.
  - **(c) Contratación informal con seguros de accidentes personales.** **No es una opción: no cumple la ley, no cubre las prestaciones del sistema, no evita la solidaridad del art. 34 del CST, y no protege frente a la responsabilidad civil ni penal por un accidente.** Decirlo con todas las letras es parte de mi trabajo.
- **9.3.2** **Afiliación a la ARL antes del inicio de labores**. **[RL]** La construcción es **clase de riesgo V**. **⚠ VERIFICAR con la ARL:** cuando la labor contratada es de riesgo IV o V, **el pago de los aportes a riesgos laborales del contratista independiente corresponde al contratante** (Decreto 723 de 2013, compilado en el Decreto 1072 de 2015).
- **9.3.3** Implementar el **Sistema de Gestión de SST**. **[RL]** Decreto 1072 de 2015 y **Resolución 0312 de 2019**, que gradúa los estándares mínimos según número de trabajadores y clase de riesgo. **⚠ VERIFICAR con el asesor de la ARL qué estándares aplican a una obra de esta escala en riesgo V** —la clase de riesgo eleva las exigencias aun con pocos trabajadores. Como mínimo: política de SST, matriz de identificación de peligros y valoración de riesgos, plan de trabajo anual, capacitación, exámenes médicos ocupacionales de ingreso y retiro, entrega y registro de EPP, plan de emergencias, investigación de incidentes y accidentes, y **designación de un responsable del SG-SST con la formación exigida**.
- **9.3.4** **Trabajo seguro en alturas**: **[RL]** aplica a tareas con riesgo de caída (el umbral normativo es del orden de **2 metros** **⚠ VERIFICAR resolución vigente — la Resolución 4272 de 2021 sustituyó a la Resolución 1409 de 2012**). Exige **certificación del personal**, coordinador de alturas, permisos de trabajo, líneas de vida y equipos certificados. **En una obra de dos pisos con cubierta, esto aplica de lleno.**
- **9.3.5** Otros frentes específicos: espacios confinados (tanques sépticos), excavaciones (taludes y entibados), riesgo eléctrico, izaje de cargas, andamios certificados.
- **9.3.6** **Reporte de accidentes** dentro de los términos legales y **matriz legal de SST** actualizada.
- **9.3.7** Cuantificar el **costo real de la formalización** frente al riesgo que cubre y llevarlo al presupuesto (capítulo 14 de 1.3.1).
- **9.3.8** Contratar **póliza de responsabilidad civil extracontractual** del proyecto. **[RE] Indispensable en obra: cubre daños a terceros y a predios vecinos, que en un lote con colindantes familiares es un escenario perfectamente posible.**

**Entregables verificables.** Planillas de afiliación y pago de seguridad social mes a mes de **todo** el personal en obra · Documento del SG-SST · Certificados de trabajo en alturas · Matriz de peligros · Registro de entrega de EPP · Póliza de RCE vigente · Exámenes ocupacionales.

**Responsable.** ADM lidera el control documental · DAO controla en obra · JUR define el modelo (HE-10) · 🔧 **asesor de la ARL** y **profesional con licencia en SST**.

**Precedencias.** Requiere 9.1. **Bloquea el inicio de obra: nadie entra al predio sin afiliación vigente.**

**Duración.** 3–4 semanas para montar; permanente después.

**Costos.** Aportes a seguridad social y ARL · asesoría en SST · EPP · exámenes médicos · capacitación en alturas · pólizas. **≈ ORDEN DE MAGNITUD: 20%–30% adicional sobre el valor de la mano de obra, a validar con Lizeth y la ARL.**

**Riesgos.** 🔴 *Un accidente grave o mortal con personal no afiliado* → responsabilidad del contratante por las prestaciones que debió cubrir el sistema, **solidaridad laboral (CST art. 34)**, responsabilidad civil, e investigación penal por lesiones u homicidio culposo. **Para un socio gestor que responde con su patrimonio personal (C.Co art. 510), esto es la ruina.** **Mitigación: la única mitigación real es la formalización. Un seguro de accidentes personales es un complemento, nunca un sustituto.**

**Marco normativo.** Código Sustantivo del Trabajo, arts. 34 y 35 · Ley 1562 de 2012 · Decreto 1072 de 2015 (Libro 2, Parte 2, Título 4) · Decreto 723 de 2013 · Resolución 0312 de 2019 · Resolución 4272 de 2021 **⚠ VERIFICAR vigencia** · Código Civil arts. 2341 y ss. (responsabilidad civil) · Código Penal (lesiones y homicidio culposo). **[RL]**

---

### 9.4 Logística, transporte y proveedores

**Objetivo.** Que el material llegue a tiempo y al menor costo, a 10 km del perímetro urbano.

**Actividades.**
- **9.4.1** **Decidir camioneta vs. fletes** (MM-5, tema abierto N.° 3) con números reales: costo de adquisición (referencia del acta: $10–15 millones estimados vs. $25 millones de mercado según John Martínez **⚠ VERIFICAR**), impuestos, SOAT, revisión técnico-mecánica, seguro, combustible, mantenimiento, conductor y su afiliación, parqueadero, depreciación y valor de reventa; contra el costo total de fletes proyectado por la programación de obra (5.7.4). **[RE] Regla de decisión: comprar solo si el costo total de propiedad durante la obra es menor que el flete proyectado más un 20% de margen, y si hay quien lo conduzca con licencia vigente. La valorización de un vehículo de carga usado no es un argumento: los vehículos se deprecian.**
- **9.4.2** Negociar con ferreterías la **entrega en obra sin recargo** (MM-6) y cerrar **acuerdos de precio por volumen con vigencia**.
- **9.4.3** Levantar la lista de **proveedores confiables de volqueta y materiales** (MM-7), con la exclusión ya decidida y con **control de volumen recibido** (el acta reporta antecedentes de cobrar 6 m³ y entregar 5: la contramedida es **medir y firmar el recibo en obra**, no cambiar de proveedor).
- **9.4.4** Definir **plan de compras por capítulo** anticipando los materiales de plazo largo (ventanería, carpintería, aparatos).
- **9.4.5** Evaluar **acopio vs. compra justo a tiempo** contra el costo financiero y el riesgo de robo.
- **9.4.6** Definir el **alquiler de equipo**: mezcladora, rana, andamios, formaleta, y el contrato con Hugo Ignacio (1.1.3). Referencia del acta: ~$200.000 por viaje de transporte primario de equipos **⚠ VERIFICAR**.

**Entregables verificables.** Análisis camioneta vs. fletes con números · Acuerdos de precio y entrega firmados con proveedores · Plan de compras · Contrato de alquiler de equipo.

**Responsable.** ADM lidera · DAO define necesidades técnicas.

**Precedencias.** Requiere 5.7.

**Duración.** 3–4 semanas.

**Costos.** Vehículo o fletes · alquileres de equipo · acopio.

**Riesgos.** *Comprar el vehículo antes de tener obra* → inmoviliza capital escaso que se necesita para arrancar. *Depender de un solo proveedor de concreto o volqueta* → parálisis de obra.

**Marco normativo.** No aplica.

---

### 9.5 Servicios provisionales y actas de vecindad

**Objetivo.** Tener agua y energía para construir, y una prueba del estado previo de lo ajeno.

**Actividades.**
- **9.5.1** Tramitar **servicio provisional de energía de obra** ante el operador de red. **[RL]** Requiere un **certificado RETIE del provisional** **⚠ VERIFICAR con el operador**.
- **9.5.2** Tramitar **agua provisional de obra** (acueducto o suministro por carrotanque) y prever almacenamiento.
- **9.5.3** **Actas de vecindad**: registro fotográfico y acta firmada del estado previo de los predios vecinos, la vía de acceso y las construcciones colindantes, **antes de mover tierra**. **[RE] Esta acta cuesta una tarde y ahorra pleitos por grietas que ya existían.**
- **9.5.4** Instalar **cerramiento provisional, señalización y valla de obra**.
- **9.5.5** Notificar el inicio de obra a los vecinos y acordar horarios.

**Entregables verificables.** Contratos de servicios provisionales · Certificado RETIE del provisional · **Actas de vecindad firmadas con registro fotográfico fechado** · Fotografía de la valla de obra.

**Responsable.** ADM tramita · DAO ejecuta en sitio · JUR redacta las actas de vecindad.

**Precedencias.** Requiere 7.2 y 6.3. **Última subfase antes del inicio de obra.**

**Duración.** 2–4 semanas.

**Costos.** Derechos de conexión provisional · consumo de obra · certificación RETIE provisional · cerramiento y valla.

**Riesgos.** *Arrancar sin agua o sin energía y trabajar con planta eléctrica* → sobrecosto operativo permanente. *Reclamación de un vecino por daños preexistentes* → sin acta de vecindad, el proyecto paga.

**Marco normativo.** RETIE · Ley 142 de 1994 · Decreto 1077 de 2015 (valla informativa). **[RL]**


---

## FASE 10 — EJECUCIÓN DE OBRA

*Objetivo de la fase: construir lo diseñado, dentro del presupuesto y del plazo, sin accidentes y sin quedarse sin caja.*

---

### 10.1 Preliminares y movimiento de tierras

**Objetivo.** Dejar el terreno listo y replanteado.

**Actividades.**
- **10.1.1** **Localización y replanteo** con topógrafo, amarrado a los mojones de 3.3.3. **[RE] El replanteo lo hace el topógrafo, no el maestro. Un error de replanteo en un lote con aislamientos ajustados puede invalidar la licencia.**
- **10.1.2** Descapote, limpieza y retiro de material vegetal (con el permiso forestal de 6.5.1 si hay tala).
- **10.1.3** Cortes, llenos y conformación de plataformas según el estudio geotécnico.
- **10.1.4** Manejo de aguas durante la obra y protección de taludes.
- **10.1.5** Disposición de material sobrante con **gestor autorizado de RCD** (6.5.5).
- **10.1.6** Verificación de aislamientos y retiros **en sitio**, con acta firmada, **antes de fundir cimientos**. 🔴

**Entregables verificables.** Acta de replanteo firmada por topógrafo y DAO · Registro fotográfico · Certificados de disposición de RCD · Acta de verificación de aislamientos.

**Responsable.** DAO dirige · ADM controla · 🔧 topógrafo.

**Precedencias.** Requiere 9.5 y la orden de inicio (hito **G-5**).

**Duración.** 3–5 semanas.

**Costos.** Maquinaria · transporte de material · disposición de RCD · topografía.

**Riesgos.** *Construir invadiendo el aislamiento* → infracción urbanística (Ley 810 de 2003), orden de demolición y multa, y **la licencia no ampara lo construido en contravención**. **Mitigación:** 10.1.6 con acta.

**Marco normativo.** NSR-10 Título H · Ley 810 de 2003 · normativa de RCD. **[RL]**

---

### 10.2 Urbanismo interno y obras de acceso

**Objetivo.** Dejar las vías, redes y el acceso funcionando antes de que lleguen los compradores a ver.

**Actividades.**
- **10.2.1** Construcción de la **vía interna**, andenes y antejardines.
- **10.2.2** Obras del **acceso** desde la callejuela, con la licencia de intervención del espacio público (7.3) si aplica.
- **10.2.3** **Redes hidrosanitarias externas**, sistema de tratamiento y campos de infiltración.
- **10.2.4** **Redes eléctricas externas**, postería, transformador y acometidas.
- **10.2.5** Redes de gas si aplica.
- **10.2.6** **Cerramiento perimetral** del predio y de cada unidad, con puerta (el acta lo define como valor agregado del producto). Verificar si el cerramiento requiere licencia en modalidad de cerramiento (2.2.1).
- **10.2.7** **Ejecución de las cesiones urbanísticas** y su entrega al municipio, si las hay. **[RL]** La entrega de cesiones se formaliza por **escritura pública** y es requisito para el recibo de obras **⚠ VERIFICAR alcance en Duitama**.
- **10.2.8** Alumbrado, señalización y jardinería de zonas comunes.

**Entregables verificables.** Actas parciales de obra de urbanismo · Actas de recibo de redes por parte de las empresas de servicios · Escritura de cesión si aplica · Registro fotográfico.

**Responsable.** DAO dirige · ADM controla costos · 🔧 empresas de servicios públicos, municipio.

**Precedencias.** Requiere 10.1. **Puede y debe adelantarse a la terminación de las casas: es lo que hace vendible el proyecto.** **[RE] En proyectos pequeños, terminar primero el acceso, la vía y el cerramiento cambia radicalmente la percepción del comprador que llega a ver el lote.**

**Duración.** 10–16 semanas.

**Costos.** Vía y andenes · redes externas · transformador · cerramiento · jardinería · cesiones.

**Riesgos.** *Dejar el urbanismo para el final* → se vende sobre barro. *Redes que la empresa de servicios no recibe por no cumplir su norma técnica* → hay que rehacerlas. **Mitigación:** aprobación previa del proyecto por cada empresa (6.3.3).

**Marco normativo.** Decreto 1077 de 2015 · normas técnicas de los prestadores · POT. **[RL]**

---

### 10.3 Cimentación y estructura

**Objetivo.** Construir la parte que no se puede corregir después.

**Actividades.**
- **10.3.1** Excavación de cimientos y verificación del **suelo de fundación contra lo previsto en el estudio geotécnico**. Si difiere, **parar y consultar al geotecnista y al calculista**. 🔴
- **10.3.2** Cimentación: acero, formaleta y concreto, con **acta de revisión de acero firmada por el calculista antes de cada fundida** (5.4.6).
- **10.3.3** Estructura: columnas, vigas, entrepiso, escaleras.
- **10.3.4** **Ensayos de laboratorio del concreto** (cilindros) por cada fundida significativa. **[RL] Los ensayos de calidad de materiales son exigencia de la NSR-10.** Los resultados se archivan: son la prueba de la calidad de la obra frente a la garantía decenal.
- **10.3.5** Control de calidad del acero (certificados de siderúrgica).
- **10.3.6** Mampostería estructural o de cierre, según el sistema.
- **10.3.7** Cubierta y su impermeabilización.

**Entregables verificables.** Actas de revisión de acero firmadas · **Resultados de ensayos de resistencia del concreto** · Certificados de materiales · Bitácora de obra · Actas parciales.

**Responsable.** DAO dirige · 🔧 calculista (revisión), laboratorio de materiales.

**Precedencias.** Requiere 10.1.

**Duración.** 12–20 semanas según el número de frentes simultáneos.

**Costos.** Concreto, acero, formaleta, mano de obra · ensayos de laboratorio · equipo.

**Riesgos.** 🔴 *Fundir sin revisión de acero* → defecto estructural irreversible que aparece 5 años después, cubierto por la **garantía de estabilidad de 10 años**. **Mitigación:** ninguna fundida sin acta. *Suelo de fundación distinto al previsto* → parar y rediseñar; nunca "seguir porque ya está la mezcla pedida".

**Marco normativo.** NSR-10 (Títulos A, B, C, D, E) · Ley 400 de 1997. **[RL]**

---

### 10.4 Instalaciones

**Objetivo.** Dejar embebido lo que después no se puede tocar.

**Actividades.**
- **10.4.1** Instalaciones hidrosanitarias: redes de agua fría y caliente, desagües y ventilaciones, según planos (5.6).
- **10.4.2** **Pruebas de presión y de estanqueidad antes de tapar**, con registro. 🔴 **[RE] Ninguna red se cubre sin prueba registrada y fotografiada.**
- **10.4.3** Instalaciones eléctricas: tuberías, cajas, alambrado, tableros, puesta a tierra, según RETIE.
- **10.4.4** Instalación de gas según NTC 2505.
- **10.4.5** **Registro fotográfico georreferenciado de todos los trazados antes de tapar**, insumo directo del **"libro del propietario"** (S-12, punto 7.6 del acta). **[RE] Esta es la pieza que convierte una idea de marketing en un diferenciador real: no se puede fabricar después.**
- **10.4.6** Previsiones de telecomunicaciones.

**Entregables verificables.** Planos *as built* de instalaciones · Registros de pruebas de presión · Registro fotográfico de trazados por vivienda · Actas parciales.

**Responsable.** DAO dirige · COM recopila el material fotográfico para el libro · 🔧 instaladores certificados.

**Precedencias.** Requiere 10.3.

**Duración.** 6–10 semanas.

**Costos.** Materiales e instalación · pruebas.

**Riesgos.** *Tapar sin probar* → fuga detectada con el piso puesto: se rompe acabado nuevo y se paga dos veces. *No registrar trazados* → cada reparación futura implica romper a ciegas, y se pierde el diferenciador comercial prometido.

**Marco normativo.** RETIE · NTC 1500 · NTC 2505. **[RL]**

---

### 10.5 Acabados

**Objetivo.** Entregar exactamente lo que dice la especificación anexa a la promesa.

**Actividades.**
- **10.5.1** Pañetes, estucos y pinturas.
- **10.5.2** Pisos y enchapes.
- **10.5.3** Carpintería en madera (cocina con isla y torre de hornos, vestier, closets, barra auxiliar) y carpintería metálica.
- **10.5.4** Ventanería y vidrios.
- **10.5.5** Aparatos sanitarios, griferías y accesorios.
- **10.5.6** Mesones, lavadero, mueble de patio de ropas.
- **10.5.7** Porche, baranda y mueble de recibo.
- **10.5.8** **Bodega exterior independiente** de cada unidad (diferenciador del producto).
- **10.5.9** **Control de conformidad contra la memoria de especificaciones (5.3.6)**, referencia por referencia. **[RE] Cualquier sustitución se documenta y se comunica al comprador por escrito antes de instalarla.**
- **10.5.10** Aseo final y protección de acabados hasta la entrega.

**Entregables verificables.** Lista de chequeo de especificaciones firmada por unidad · Actas parciales · Registro fotográfico de avance (contenido para 8.4.5).

**Responsable.** DAO dirige · ADM controla almacén y costos.

**Precedencias.** Requiere 10.4.

**Duración.** 10–16 semanas.

**Costos.** El capítulo más grande después de estructura · alta sensibilidad a la variación de precios.

**Riesgos.** *Cambiar acabados sin avisar al comprador* → reclamación fundada bajo la Ley 1480 de 2011. *Acabados no presupuestados que el comprador da por incluidos* → por eso existe 5.3.7 (lo que NO incluye).

**Marco normativo.** Ley 1480 de 2011. **[RL]**

---

### 10.6 Certificaciones técnicas y conexión definitiva de servicios

**Objetivo.** Que la casa se pueda habitar legalmente y con servicios definitivos. **Sin esto no hay entrega ni escritura útil.**

**Actividades.**
- **10.6.1** **Certificación RETIE por unidad** por organismo de inspección acreditado ante el ONAC, y **dictamen de conformidad**. **[RL]**
- **10.6.2** **Certificación de la instalación de gas** por organismo acreditado. **[RL]**
- **10.6.3** **Conexión definitiva y matrícula de servicios** por unidad: energía, acueducto, gas. Definir a nombre de quién quedan hasta la venta y quién paga los consumos.
- **10.6.4** Recibo de las redes por parte de las empresas prestadoras.
- **10.6.5** Legalización final del sistema de tratamiento de aguas residuales ante Corpoboyacá (6.2.3).
- **10.6.6** Verificar si Duitama exige algún **certificado de permiso de ocupación** o recibo de obra al terminar. **[RL] ⚠ VERIFICAR ante la curaduría y Planeación:** en algunos municipios se expide un certificado de permiso de ocupación de la edificación, exigible antes de habitar.
- **10.6.7** Elaborar los **planos *as built*** definitivos.

**Entregables verificables.** Dictámenes RETIE por vivienda · Certificados de gas · Matrículas de servicios · Actas de recibo de redes · Certificado de permiso de ocupación si aplica · Planos *as built*.

**Responsable.** DAO coordina · ADM tramita · 🔧 organismos de inspección, empresas de servicios, curaduría.

**Precedencias.** Requiere 10.4 y 10.5. **Bloquea la entrega (12.3).**

**Duración.** 4–8 semanas.

**Costos.** Certificaciones por unidad · derechos de conexión y matrículas · medidores.

**Riesgos.** 🔴 *Casas terminadas sin energía definitiva* → no se pueden entregar, el comprador no paga el saldo y el banco no desembolsa. **Es un escenario real y frecuente.** **Mitigación:** iniciar 6.3 en la Fase 6, no en la Fase 10.

**Marco normativo.** RETIE · NTC 2505 · Ley 142 de 1994 · Decreto 1077 de 2015. **[RL]**

---

### 10.7 Control de avance, calidad y flujo de caja durante la obra

**Objetivo.** Detectar la desviación cuando todavía se puede corregir.

**Actividades.**
- **10.7.1** **Comité de obra semanal**: avance físico vs. programado, avance financiero vs. presupuesto, frentes críticos, decisiones pendientes.
- **10.7.2** **Corte mensual de obra**: acta de avance por contratista, cantidades ejecutadas, retenciones, pagos.
- **10.7.3** **Actualización mensual del flujo de caja** con el recaudo real de ventas. **[RE] Indicador de alarma: si el recaudo acumulado cae por debajo del compromiso de pago de los 60 días siguientes, se frena obra ANTES de quedarse sin caja, no después.**
- **10.7.4** **Control de cambios**: todo cambio de diseño se cotiza, se aprueba por escrito y se incorpora al presupuesto antes de ejecutarse. 🔴
- **10.7.5** Verificar que los cambios no impliquen **modificación de la licencia**. **[RL] Cambios que alteren áreas, volumetría o el proyecto aprobado exigen licencia de modificación.**
- **10.7.6** Informe mensual a los socios y actualización del tablero.
- **10.7.7** Control de **vigencia de la licencia** y de las pólizas.

**Entregables verificables.** Actas de comité semanal · Cortes mensuales · Flujo de caja actualizado · Registro de control de cambios · Informe mensual a socios.

**Responsable.** DAO (técnico) + ADM (financiero) conjuntamente.

**Precedencias.** Transversal a toda la Fase 10.

**Duración.** Toda la obra.

**Costos.** Tiempo de gestión.

**Riesgos.** 🔴 *Iliquidez en la mitad de la obra* → es **el riesgo número uno de este proyecto** (ver R-02 y la curva de inversión en E). *Cambios "de palabra" en obra* → sobrecosto invisible que aparece en la liquidación.

**Marco normativo.** Decreto 1077 de 2015 (licencia de modificación). **[RL] parcial.**

---

## FASE 11 — TITULACIÓN: PROPIEDAD HORIZONTAL O SUBDIVISIÓN

*Objetivo de la fase: que cada casa tenga su propio folio de matrícula, que es lo que permite venderla y lo que el banco del comprador exige.*

---

### 11.1 Decisión estructural: PH vs. loteo independiente 🔴

**Objetivo.** Elegir el camino de titulación con pleno conocimiento de sus consecuencias.

**Comparación:**

| Criterio | **Propiedad horizontal (Ley 675 de 2001)** | **Loteo / subdivisión independiente** |
|---|---|---|
| **Viabilidad jurídica en suelo rural** | No requiere subdividir el suelo → **esquiva el problema de la UAF** | Requiere licencia de subdivisión y **choca con la UAF y con el área mínima de predio del POT** ⚠ |
| **Folio del comprador** | Cada unidad privada tiene **folio propio** | Cada lote tiene folio propio |
| **Crédito hipotecario** | Perfectamente hipotecable; los bancos están acostumbrados | Hipotecable |
| **Vía interna y zonas comunes** | Quedan como **bien común** de la copropiedad, sin cederse al municipio | Deben resolverse como vía pública (con cesión) o servidumbre |
| **Aislamientos internos** | Se miden respecto al predio matriz → **resuelve el problema de los "piquitos"** (5.1.5) | Se miden respecto a cada lindero de lote → **es donde nace el problema** |
| **Área de conservación exigida en parcelación rural** | Puede acomodarse como **zona común verde** | Difícil de acomodar dentro de lotes privados |
| **Costos** | Reglamento de PH, escritura, registro, **persona jurídica, administrador, cuota de administración, seguro de áreas comunes** | Menos costos recurrentes |
| **Percepción del comprador** | Seguridad y control de entorno; pero le molesta la cuota de administración | "Es mío y no le pago a nadie" |
| **Mantenimiento de vía y sistema séptico colectivo** | Hay quien responda (la copropiedad) | **Nadie responde** → se deteriora y genera conflicto entre vecinos |

**[RE] Mi recomendación: propiedad horizontal.** No por preferencia, sino porque **resuelve simultáneamente** el problema de la UAF, el de los aislamientos internos, el del área de conservación, el de la titularidad de la vía interna y el del mantenimiento del sistema de tratamiento. El costo recurrente de la administración en un conjunto de 5 casas es bajo y se puede estructurar de forma simple. **Esta decisión debe tomarse en el hito G-3, antes de radicar la licencia**, porque cambia el diseño y la licencia misma.

**Actividades.**
- **11.1.1** Consultar formalmente a la curaduría cuál de las dos rutas es viable en este predio. **⚠ VERIFICAR.**
- **11.1.2** Cuantificar el costo de cada ruta (constitución, registro, administración).
- **11.1.3** Sondear con inmobiliarias la reacción del comprador objetivo a la cuota de administración.
- **11.1.4** Decidir y documentar la decisión.

**Entregables verificables.** Concepto escrito de la curaduría · Cuadro comparativo de costos · Acta de decisión firmada por los cuatro socios.

**Responsable.** JUR lidera · DAO técnico · COM aporta lectura de mercado.

**Precedencias.** Requiere 2.1, 2.2. **Debe resolverse ANTES de 7.1.**

**Duración.** 2–3 semanas.

**Costos.** Consultas jurídicas.

**Riesgos.** 🔴 *Radicar licencia bajo un esquema y cambiar después* → licencia de modificación, expensas nuevas, meses perdidos.

**Marco normativo.** Ley 675 de 2001 · Ley 160 de 1994 · Decreto 1077 de 2015 · POT de Duitama. **[RL]**

---

### 11.2 Constitución del régimen de propiedad horizontal (si se elige PH)

**Objetivo.** Crear jurídicamente las 5 unidades privadas y la copropiedad.

**Actividades.**
- **11.2.1** Elaborar el **reglamento de propiedad horizontal** (HE-12). **[RL] Contenido mínimo según la Ley 675 de 2001:** identificación del inmueble, descripción de los **bienes privados** con sus linderos y áreas, descripción de los **bienes comunes** (vía interna, zonas verdes, sistema de tratamiento, cerramiento, redes, tanques), **coeficientes de copropiedad** con su método de cálculo, destinación de cada bien, órganos de administración, régimen de solución de conflictos.
- **11.2.2** Definir la **destinación** del inmueble: vivienda. Verificar coherencia con la licencia y el POT.
- **11.2.3** Calcular **coeficientes de copropiedad** conforme a la ley (con base en el área privada y los factores que la propia ley establece). **[RL] Los coeficientes determinan el voto en asamblea y la cuota de administración: un error aquí se corrige solo con reforma del reglamento, que exige mayoría calificada.**
- **11.2.4** Definir **bienes comunes esenciales vs. no esenciales** y, si aplica, **bienes comunes de uso exclusivo** (por ejemplo, el antejardín de cada unidad).
- **11.2.5** Otorgar la **escritura pública de constitución del régimen de PH** y **registrarla**. **[RL]**
- **11.2.6** Obtener la **apertura del folio de matrícula de cada unidad privada** y del folio de la copropiedad.
- **11.2.7** Inscribir la **persona jurídica de la copropiedad** ante la Alcaldía de Duitama y obtener su certificado de existencia y representación. **[RL] ⚠ VERIFICAR la dependencia competente.**
- **11.2.8** Obtener **RUT y NIT** de la persona jurídica de la copropiedad y abrir su cuenta bancaria.
- **11.2.9** Definir el **presupuesto de administración del primer año** y la cuota mensual. **[RE] Calcúlenlo con realismo y comuníquenlo desde la primera visita comercial: una cuota "sorpresa" en la escrituración daña la venta.**

**Entregables verificables.** **Escritura de constitución de PH registrada** · **Folios de matrícula individuales de las 5 unidades** · Certificado de existencia y representación de la copropiedad · NIT · Presupuesto y cuota de administración.

**Responsable.** JUR lidera · 🔧 **abogado especialista en PH**, notario, ORIP, alcaldía, contadora.

**Precedencias.** Requiere 7.2 (licencia) y, en la práctica, la obra suficientemente avanzada para describir con precisión las áreas privadas **⚠ VERIFICAR el momento exacto con el notario y la ORIP**. **Bloquea 12.1 (escrituración).**

**Duración.** 6–12 semanas incluyendo registro.

**Costos.** Honorarios de elaboración del reglamento · **gastos notariales** · **impuesto de registro y derechos de registro** · apertura de folios · costos de constitución de la persona jurídica.

**Riesgos.** *Coeficientes mal calculados* → conflicto permanente y reforma costosa. *Constituir la PH tarde* → **la escrituración se atrasa y con ella el desembolso de los créditos: es un cuello de botella clásico al final del proyecto**. **Mitigación:** iniciar 11.2 cuando la obra vaya en 60–70%, no al terminar.

**Marco normativo.** Ley 675 de 2001 · Ley 1579 de 2012 · Ley 223 de 1995. **[RL]**

---

### 11.3 Ruta alternativa: subdivisión y apertura de folios independientes

**Objetivo.** Si se elige loteo, obtener los folios sin PH.

**Actividades.**
- **11.3.1** Tramitar la **licencia de subdivisión** (o que las unidades queden definidas en la licencia de parcelación).
- **11.3.2** Resolver jurídicamente la **vía interna**: cesión al municipio o servidumbre de tránsito constituida a favor de todos los lotes. **[RL] Un lote interior sin acceso constituido no es vendible ni financiable.**
- **11.3.3** Resolver la **titularidad y el mantenimiento del sistema de tratamiento colectivo**, si lo hay.
- **11.3.4** Otorgar escritura de **desenglobe** y registrarla.
- **11.3.5** Obtener los **folios independientes** y la actualización catastral.

**Entregables verificables.** Licencia de subdivisión · Escritura de desenglobe registrada · Folios independientes · Escritura de servidumbre si aplica.

**Responsable.** JUR · 🔧 topógrafo, curador, notario, ORIP.

**Precedencias.** Requiere 11.1 (decisión) y 7.2.

**Duración.** 8–16 semanas.

**Costos.** Expensas · notaría · registro · topografía.

**Riesgos.** 🔴 *Negación por UAF o por área mínima de predio* → hay que migrar a PH con la obra ya avanzada. **Mitigación:** resolver en 11.1, antes de licenciar.

**Marco normativo.** Ley 160 de 1994 · Decreto 1077 de 2015 · Ley 1579 de 2012 · Código Civil (servidumbres). **[RL]**

---

## FASE 12 — ESCRITURACIÓN, ENTREGA Y RECAUDO FINAL

*Objetivo de la fase: convertir promesas en escrituras y escrituras en plata en la cuenta.*

---

### 12.1 Escrituración

**Objetivo.** Transferir la propiedad y cobrar el saldo.

**Actividades.**
- **12.1.1** Elaborar la **minuta de compraventa** por unidad (HE-13), con: identificación del folio individual, coeficiente de copropiedad, linderos, precio, forma de pago, entrega, y las declaraciones de ley.
- **12.1.2** Reunir los documentos que exige la notaría: certificado de tradición reciente, **paz y salvo de impuesto predial**, paz y salvo de valorización si aplica, **paz y salvo de administración** de la PH, licencia, certificado de existencia de la copropiedad, y los documentos de identidad y estado civil de las partes. **[RL]**
- **12.1.3** Coordinar la **comparecencia de Rosa** como propietaria, si el lote no se transfirió antes al proyecto (4.3). **[RE] Este es el momento donde el esquema "Rosa no ve los números" se rompe: en la escritura queda el precio de venta. Es una razón más para resolver 4.3 antes.**
- **12.1.4** Otorgar la escritura y pagar: **gastos notariales, retención en la fuente, impuesto de registro y derechos de registro** (4.4.9).
- **12.1.5** **Registrar la escritura** en la ORIP y obtener el **certificado de tradición con la anotación de la venta**.
- **12.1.6** Gestionar el **desembolso del crédito hipotecario** del comprador, cuando aplique:
  - **12.1.6.1** Verificar que el comprador tenga aprobado el crédito **antes** de fijar fecha de escrituración.
  - **12.1.6.2** **Avalúo comercial** por **avaluador inscrito en el Registro Abierto de Avaluadores (RAA)**, exigido por el banco. **[RL]** Ley 1673 de 2013.
  - **12.1.6.3** Estudio de títulos del banco.
  - **12.1.6.4** Escritura con **hipoteca a favor del banco** en el mismo acto.
  - **12.1.6.5** Registro y **desembolso** contra certificado de tradición registrado. **[PM] Entre la firma y el desembolso pasan típicamente de 2 a 6 semanas: eso debe estar en el flujo de caja.**
- **12.1.7** Liquidar y pagar a Rosa **la quinta parte que corresponda** por cada casa vendida (4.1.1), con soporte y retención si aplica.
- **12.1.8** Liquidar y pagar las **comisiones** de vendedores e inmobiliarias, con retención en la fuente.

**Entregables verificables.** Escritura registrada por unidad · Certificado de tradición con la anotación · Comprobante de desembolso · Comprobante de pago a Rosa · Liquidación de comisiones.

**Responsable.** JUR lidera · ADM controla el recaudo · 🔧 notario, ORIP, banco, avaluador.

**Precedencias.** Requiere 11.2 o 11.3 (folios) y 10.6 (servicios) y, en la práctica, la casa terminada.

**Duración.** 4–10 semanas por unidad, contadas desde el cumplimiento de las condiciones.

**Costos.** Notariales · registro · retenciones · avalúo (usualmente lo paga el comprador **[PM]**) · comisiones.

**Riesgos.** 🔴 *Que el crédito del comprador se caiga después de meses de obra* → la unidad vuelve al inventario con la caja ya gastada. **Mitigación:** condición resolutoria de crédito en la promesa (8.3.2.6) y **verificación de precalificación crediticia antes de firmar promesa** **[RE]**. *Predial o administración en mora* → la notaría no autoriza.

**Marco normativo.** Código Civil · Ley 1579 de 2012 · Ley 675 de 2001 · Ley 1673 de 2013 · Estatuto Tributario arts. 398-399 · Ley 223 de 1995. **[RL]**

---

### 12.2 Preparación de la entrega

**Objetivo.** Entregar sin sorpresas y con constancia de lo entregado.

**Actividades.**
- **12.2.1** **Prelistado interno de pendientes** por unidad, ejecutado por DAO **antes** de que el comprador visite. **[RE] La entrega se prepara: nunca se entrega sin haber hecho antes el recorrido interno y corregido lo evidente.**
- **12.2.2** Aseo profundo, verificación de funcionamiento de todos los puntos hidráulicos, eléctricos, de gas, puertas, ventanas y cerraduras.
- **12.2.3** Preparar la **carpeta de entrega**: manual del propietario, planos *as built*, certificados RETIE y de gas, garantías de equipos y de fabricantes, especificación de acabados entregada, y el **"libro del propietario"** (S-12) con el registro fotográfico del proceso y los trazados.
- **12.2.4** Preparar el **inventario de entrega** por espacio y elemento.
- **12.2.5** Preparar la **entrega de llaves y de códigos**.

**Entregables verificables.** Lista de pendientes cerrada · Carpeta de entrega completa por unidad · Libro del propietario impreso.

**Responsable.** DAO prepara · COM produce el libro · ADM consolida la carpeta.

**Precedencias.** Requiere 10.5 y 10.6.

**Duración.** 1–2 semanas por unidad.

**Costos.** Aseo · impresión del libro y manuales · corrección de pendientes.

**Riesgos.** *Entregar con pendientes visibles* → arranca la relación de posventa en conflicto y el comprador retiene el saldo.

**Marco normativo.** Ley 1480 de 2011 (información al consumidor). **[RL] parcial.**

---

### 12.3 Acta de entrega y recibo

**Objetivo.** Dejar constancia de qué se entregó, en qué estado y con qué pendientes.

**Actividades.**
- **12.3.1** Recorrido de entrega con el comprador, espacio por espacio.
- **12.3.2** Suscribir el **acta de entrega** con: fecha, inventario, lectura de contadores de servicios, **listado de pendientes con fecha comprometida de solución**, entrega de llaves, y entrega de la carpeta documental.
- **12.3.3** Informar por escrito el **inicio de los plazos de garantía** (13.1).
- **12.3.4** Entregar el **manual del propietario** con las instrucciones de uso y mantenimiento, incluido el **mantenimiento del sistema séptico** y las **conductas que anulan la garantía** (por ejemplo, modificaciones estructurales o intervención de redes por terceros). **[RE] Este documento es la mejor defensa del constructor en posventa.**
- **12.3.5** Traspasar las **matrículas de servicios públicos** al comprador.
- **12.3.6** Vincular al comprador a la **copropiedad**: entrega del reglamento, cuota de administración, y datos de contacto.

**Entregables verificables.** **Acta de entrega firmada** con inventario y lecturas · Constancia de entrega del manual y del libro · Traspaso de servicios.

**Responsable.** DAO entrega · ADM documenta · JUR revisa el acta.

**Precedencias.** Requiere 12.1 y 12.2.

**Duración.** 1 día por unidad; 1–3 semanas para cerrar pendientes.

**Costos.** Corrección de pendientes.

**Riesgos.** *Entregar sin acta* → después no hay cómo probar en qué estado se entregó y toda reclamación es del constructor. *Pendientes sin fecha* → reclamación indefinida.

**Marco normativo.** Ley 1480 de 2011 · Código Civil. **[RL]**

---

### 12.4 Entrega de zonas comunes y constitución de la administración (si hay PH)

**Objetivo.** Traspasar la copropiedad a sus dueños en orden.

**Actividades.**
- **12.4.1** Convocar la **asamblea de constitución** de la copropiedad. **[RL]** Ley 675 de 2001.
- **12.4.2** Elegir **administrador** (o designarlo según el reglamento mientras el constructor conserva la mayoría de coeficientes) y, si aplica, consejo de administración.
- **12.4.3** **Entregar las zonas comunes** con acta e inventario: vía, zonas verdes, cerramiento, sistema de tratamiento, redes, tanques, alumbrado, portón.
- **12.4.4** Entregar la **documentación técnica de las zonas comunes**: planos *as built*, manuales de equipos, garantías, protocolo de mantenimiento del sistema séptico.
- **12.4.5** Aprobar el **presupuesto y la cuota de administración** del primer período.
- **12.4.6** Contratar el **seguro obligatorio de las áreas comunes**. **[RL] La Ley 675 de 2001 obliga a asegurar los bienes comunes contra incendio y terremoto. ⚠ VERIFICAR alcance exacto.**
- **12.4.7** Entregar los **fondos** que correspondan (fondo de imprevistos).

**Entregables verificables.** Acta de asamblea de constitución · **Acta de entrega de zonas comunes con inventario** · Póliza de áreas comunes · Presupuesto aprobado.

**Responsable.** JUR lidera · DAO entrega lo técnico · ADM entrega lo contable.

**Precedencias.** Requiere 11.2 y 10.2. **[PM] Se hace cuando se han entregado al menos la mayoría de las unidades.**

**Duración.** 3–5 semanas.

**Costos.** Seguro de áreas comunes · fondo de imprevistos · honorarios del administrador.

**Riesgos.** *No entregar formalmente las zonas comunes* → el constructor sigue siendo responsable de hecho, indefinidamente. *Cuota de administración irreal* → la copropiedad se desfinancia y el proyecto queda con la mala fama.

**Marco normativo.** Ley 675 de 2001. **[RL]**

---

## FASE 13 — POSVENTA Y GARANTÍAS

*Objetivo de la fase: atender lo que falle, dentro de lo que la ley obliga, sin regalar y sin pelear. **El acta no la contempla y es una obligación de años.***

---

### 13.1 Régimen de garantías y provisión

**Objetivo.** Saber exactamente qué se debe y por cuánto tiempo, y tener con qué responder.

**Actividades.**
- **13.1.1** Documentar los plazos de garantía. **[RL]**
  - **Garantía de estabilidad de la obra: 10 años**, y **garantía de acabados: 1 año**, conforme al **art. 8 de la Ley 1480 de 2011 (Estatuto del Consumidor)**.
  - Adicionalmente, el **artículo 2060, numeral 3, del Código Civil** hace responder al empresario por la **ruina del edificio dentro de los 10 años siguientes** a la entrega.
  - **⚠ VERIFICAR** con JUR el texto vigente y las precisiones jurisprudenciales.
- **13.1.2** Verificar si aplica la obligación de constituir **amparo o póliza decenal de estabilidad** para vivienda nueva. **[RL] La Ley 1796 de 2016 estableció esa obligación con umbrales por área construida. ⚠ VERIFICAR con la curaduría y con una aseguradora si un conjunto de 5 viviendas de ~110 m² (≈550 m² totales) queda por debajo del umbral.** **[RE] Aun si no es obligatoria, cotizarla: es un argumento de venta poderoso frente a un comprador que le compra a personas naturales y no a una constructora conocida.**
- **13.1.3** **Constituir la provisión de posventa** en el presupuesto. **[RE] Referencia habitual del sector: 0,5% a 1,5% del valor de la obra. Debe reservarse ANTES de repartir utilidades, no después.** Este es un punto que el acta no contempla y que rompe repartos: se reparte la utilidad y a los seis meses hay que pagar una reparación con plata de nadie.
- **13.1.4** Definir qué **NO cubre la garantía**: desgaste normal, uso indebido, falta de mantenimiento, modificaciones del propietario, intervención de terceros. Debe estar en el manual del propietario (12.3.4).
- **13.1.5** Trasladar a los contratistas la **garantía de sus capítulos** mediante retención en garantía y póliza de estabilidad (4.5.1, 4.5.2), con **vigencia alineada** a la garantía que el proyecto le debe al comprador.

**Entregables verificables.** Documento de régimen de garantías · Provisión de posventa constituida en cuenta separada · Pólizas de contratistas vigentes · Cotización de póliza decenal.

**Responsable.** JUR define · ADM provisiona · DAO ejecuta las reparaciones.

**Precedencias.** Requiere 12.3. **Corre en paralelo con 14 (cierre).**

**Duración.** 1 año (acabados) y 10 años (estabilidad).

**Costos.** Provisión de posventa · pólizas · costo de las reparaciones.

**Riesgos.** 🔴 *Repartir toda la utilidad y quedar sin provisión* → las reparaciones salen del bolsillo de quien esté disponible, y ahí empieza el conflicto entre socios. *Pólizas de contratistas que vencen antes que la garantía del comprador* → el proyecto queda solo frente a la reclamación.

**Marco normativo.** Ley 1480 de 2011, art. 8 · Código Civil, art. 2060 · Ley 1796 de 2016 · Ley 400 de 1997. **[RL]**

---

### 13.2 Protocolo de atención de reclamaciones

**Objetivo.** Responder rápido y dejar constancia, que es lo que evita que una reclamación se vuelva una demanda.

**Actividades.**
- **13.2.1** Definir el **canal único** de recepción (correo o formulario) y el **formato de reclamación**.
- **13.2.2** Definir **tiempos de respuesta**: acuse en 48 horas, visita técnica en 8 días hábiles, respuesta de fondo en 15 días hábiles **[RE] — o los que fije la ley si son menores ⚠ VERIFICAR**.
- **13.2.3** **Visita de diagnóstico** con acta: causa, si está o no cubierta, y decisión.
- **13.2.4** Ejecución de la reparación y **acta de conformidad firmada por el propietario**.
- **13.2.5** **Registro estadístico de reclamaciones** por tipo, para corregir el proceso constructivo y para negociar con contratistas. **[RE] En un proyecto que aspira a ser piloto de una empresa (punto 7.7 del acta), este registro es el activo más valioso que dejará esta obra.**
- **13.2.6** Definir qué se hace ante una reclamación **no cubierta** pero comercialmente sensible: criterio escrito de "gesto comercial", con tope y con aprobación.
- **13.2.7** Definir la **ruta de conflicto**: conciliación antes que demanda; y tener presente la competencia de la **Superintendencia de Industria y Comercio** en materia de protección al consumidor. **[RL]**

**Entregables verificables.** Protocolo escrito · Formato de reclamación · Bitácora de reclamaciones con estado · Actas de conformidad.

**Responsable.** ADM recibe y hace seguimiento · DAO diagnostica y repara · JUR interviene si escala.

**Precedencias.** Requiere 12.3.

**Duración.** Permanente durante los plazos de garantía.

**Costos.** Reparaciones · tiempo · eventual conciliación.

**Riesgos.** *No responder* → el silencio convierte un problema de $2 millones en una demanda con costas. *Reparar sin acta* → se repara dos veces.

**Marco normativo.** Ley 1480 de 2011 · normas de la SIC. **[RL]**

---

### 13.3 Acompañamiento a la copropiedad en el primer año

**Objetivo.** Que el conjunto arranque bien y no se vuelva el problema del constructor.

**Actividades.**
- **13.3.1** Acompañar la primera asamblea ordinaria y la aprobación del presupuesto.
- **13.3.2** Capacitar al administrador y a los propietarios en el **mantenimiento del sistema de tratamiento**, del tanque, de la vía y del cerramiento.
- **13.3.3** Entregar el **cronograma de mantenimiento preventivo** de los bienes comunes.
- **13.3.4** Cerrar formalmente el acompañamiento con acta al cumplir el año.

**Entregables verificables.** Actas de asamblea · Cronograma de mantenimiento entregado · Acta de cierre del acompañamiento.

**Responsable.** DAO y ADM.

**Precedencias.** Requiere 12.4.

**Duración.** 12 meses.

**Costos.** Tiempo.

**Riesgos.** *Copropiedad sin mantenimiento del sistema séptico* → falla ambiental que el propietario le reclamará al constructor aunque la causa sea la falta de mantenimiento. **Mitigación:** capacitación documentada y cronograma entregado con firma.

**Marco normativo.** Ley 675 de 2001. **[RL] parcial.**

---

## FASE 14 — CIERRE Y LIQUIDACIÓN

*Objetivo de la fase: cerrar el proyecto de forma que nadie quede con deudas ocultas ni con expectativas incumplidas.*

---

### 14.1 Liquidación de contratos con contratistas y proveedores

**Objetivo.** Cerrar cada contrato con paz y salvo, sin cabos sueltos laborales.

**Actividades.**
- **14.1.1** **Acta de liquidación** por contrato: cantidades finales, pagos, retenciones, saldos, obras adicionales aprobadas.
- **14.1.2** Exigir **paz y salvo de seguridad social y prestaciones** del personal de cada contratista. **[RL] Es la única defensa práctica frente a la solidaridad del art. 34 del CST.** 🔴
- **14.1.3** **Liberación de las retenciones en garantía** contra acta de recibo final y vigencia de pólizas de estabilidad.
- **14.1.4** Verificar que las **pólizas de estabilidad y calidad** de los contratistas queden vigentes por el plazo pactado.
- **14.1.5** Paz y salvo de proveedores y cierre de cuentas por pagar.

**Entregables verificables.** Actas de liquidación firmadas · Paz y salvos laborales y de seguridad social · Pólizas vigentes archivadas.

**Responsable.** ADM lidera · JUR revisa · DAO certifica el recibo técnico.

**Precedencias.** Requiere 10 y 12.3.

**Duración.** 4–6 semanas.

**Costos.** Saldos por pagar.

**Riesgos.** 🔴 *Liquidar sin paz y salvo laboral* → una demanda laboral dos años después, contra el socio gestor, con solidaridad. **Mitigación:** no liberar la retención sin paz y salvo.

**Marco normativo.** CST arts. 34 y 35 · Código Civil. **[RL]**

---

### 14.2 Cierre contable y tributario

**Objetivo.** Saber cuánto se ganó de verdad y pagarle a la DIAN y al municipio lo que corresponde.

**Actividades.**
- **14.2.1** **Cierre contable del proyecto**: consolidación de ingresos, costos y gastos por capítulo, contra el presupuesto maestro (1.3).
- **14.2.2** **Determinar la utilidad real antes de impuestos** y compararla con la proyección de $685 millones del acta.
- **14.2.3** **Liquidar y pagar impuestos**: renta de cada titular, ICA de Duitama, retenciones practicadas y por practicar, IVA si aplica.
- **14.2.4** **Certificación del gestor a los partícipes** de la información financiera y fiscal, si se mantiene la figura de cuentas en participación. **[RL] Estatuto Tributario, art. 18.**
- **14.2.5** Conciliación final con **Rosa**: liquidación total del pago por m², paz y salvo mutuo.
- **14.2.6** Cierre de la **cuenta bancaria del proyecto** o del encargo fiduciario.

**Entregables verificables.** Estado de resultados del proyecto · Declaraciones presentadas y pagadas · **Paz y salvo mutuo con Rosa** · Certificaciones del art. 18 del ET.

**Responsable.** ADM consolida · 🔧 **contadora (Lizeth)** · JUR formaliza los paz y salvos.

**Precedencias.** Requiere 12.1 (todas las escrituras) y 14.1.

**Duración.** 4–8 semanas, más los tiempos del calendario tributario.

**Costos.** Honorarios contables · **impuestos** (el renglón más grande de esta fase).

**Riesgos.** 🔴 *Descubrir la carga tributaria al final* → ver 4.4. **La provisión de impuestos debe estar hecha desde la primera venta, no en el cierre.**

**Marco normativo.** Estatuto Tributario · Estatuto Tributario Municipal de Duitama. **[RL]**

---

### 14.3 Liquidación del contrato de cuentas en participación y reparto

**Objetivo.** Repartir lo que quedó, según reglas escritas desde el principio.

**Actividades.**
- **14.3.1** Liquidar el contrato con Rosa (o con la partícipe oculta que corresponda), con **rendición de cuentas** si la figura lo exige. **[RL] C.Co arts. 512 y ss.**
- **14.3.2** Liquidar el contrato entre los cuatro socios gestores (4.2.3).
- **14.3.3** **Orden de aplicación de los recursos** (esto debe estar escrito **desde el inicio**, no discutirse aquí):
  1. Pagos a terceros y contratistas.
  2. Impuestos y retenciones.
  3. **Provisión de posventa** (13.1.3).
  4. Pago del lote a Rosa.
  5. **Honorarios de cada socio por su rol** (D-09, 1.1.2) y alquiler del equipo.
  6. Reintegro del capital aportado.
  7. **Utilidad a repartir.**
- **14.3.4** Documentar el reparto con **actas y soportes de pago**, y practicar las retenciones que correspondan.
- **14.3.5** **Acta final de liquidación** firmada por todos, con declaración de paz y salvo mutuo y renuncia a reclamaciones futuras derivadas de la gestión, salvo las obligaciones de garantía.

**Entregables verificables.** Acta de liquidación del contrato con Rosa · Acta de liquidación entre socios · Comprobantes de pago del reparto · Acta final de paz y salvo.

**Responsable.** JUR redacta · ADM liquida · 🔧 contadora.

**Precedencias.** Requiere 14.2 y **la constitución previa de la provisión de posventa**.

**Duración.** 2–4 semanas.

**Costos.** Retenciones sobre los pagos · honorarios.

**Riesgos.** 🔴 *Repartir sin provisionar posventa e impuestos* → el proyecto reparte plata que no es suya. **Es el error de cierre más común y el que rompe sociedades.** *Reparto sin reglas escritas* → conflicto en el momento de mayor tensión.

**Marco normativo.** Código de Comercio, arts. 507 a 514 · Estatuto Tributario. **[RL]**

---

### 14.4 Archivo del proyecto y conservación documental

**Objetivo.** Poder demostrar, años después, qué se hizo y cómo.

**Actividades.**
- **14.4.1** Consolidar el **archivo digital y físico** con la estructura de esta EDT.
- **14.4.2** Definir **qué se conserva y por cuánto tiempo**:

| Documento | Plazo mínimo | Por qué |
|---|---|---|
| **Planos aprobados, licencia, memorias de cálculo, estudio de suelos, ensayos de concreto, *as built*** | **Mínimo 10 años** después de la entrega | Es la prueba en un reclamo por **garantía de estabilidad de 10 años** (Ley 1480 art. 8; C.C. art. 2060). **Sin esto, el constructor pierde por falta de prueba.** |
| **Actas de entrega, inventarios, manuales, actas de posventa** | 10 años | Prueba del estado de entrega |
| **Contratos, actas de liquidación, paz y salvos laborales, planillas de seguridad social** | **Al menos 10 años** ⚠ VERIFICAR el término de prescripción laboral aplicable con JUR | Defensa frente a reclamaciones laborales y de solidaridad |
| **Soportes contables y tributarios** | El plazo de firmeza de las declaraciones y conservación que fije el Estatuto Tributario ⚠ VERIFICAR con Lizeth | Defensa en una fiscalización de la DIAN |
| **Escrituras, folios, reglamento de PH** | Permanente | Título |
| **Registro fotográfico y libro del propietario** | Permanente | Activo comercial para el siguiente proyecto |

- **14.4.3** Entregar copia del archivo técnico a la **copropiedad** (planos *as built*, manuales, garantías).
- **14.4.4** **Lecciones aprendidas**: documento con lo que salió bien, lo que salió mal, precios reales por capítulo, rendimientos reales, y tiempos reales de cada trámite. **[RE] Este documento es el que convierte este proyecto en el piloto de una empresa (visión 7.7 del acta). Sin él, el siguiente proyecto vuelve a empezar de cero.**
- **14.4.5** Base de datos comercial depurada, con habeas data vigente, para el siguiente proyecto.

**Entregables verificables.** Archivo consolidado e indexado · Documento de lecciones aprendidas con precios y tiempos reales · Copia entregada a la copropiedad con acta.

**Responsable.** ADM lidera · todos aportan.

**Precedencias.** Requiere 14.3.

**Duración.** 2–3 semanas.

**Costos.** Almacenamiento en la nube · impresión y encuadernación.

**Riesgos.** *Perder el archivo cuando alguien deja de pagar el Drive* → definir titularidad y respaldo. *No conservar los ensayos de concreto* → indefensión en un reclamo de estabilidad a los 7 años.

**Marco normativo.** Estatuto Tributario (conservación de soportes) · CST (prescripción) · Ley 1480 de 2011 · Ley 1581 de 2012 (habeas data). **[RL]**


---

# PARTE II — HITOS DE DECISIÓN (GO / NO-GO)

Un hito de decisión no es una reunión de avance. Es un punto donde el equipo **se detiene, pone información sobre la mesa y decide si sigue, si cambia o si para**. La regla es simple: **no se pasa al siguiente hito sin haber cerrado el anterior por escrito.**

---

## G-0 · ¿Arrancamos siquiera a estudiar? — *Semana 0*

**Qué debe estar sobre la mesa:** el Acta N.° 01, esta EDT, y el compromiso de los cuatro socios de gastar entre **$3 y $8 millones** en la fase de estudios previos, con la conciencia de que **esa plata puede perderse** si el resultado es negativo.

**Decisión:** ¿estamos dispuestos a gastar el presupuesto de prefactibilidad sabiendo que puede no haber proyecto?

**Si no:** no se arranca. Es una decisión legítima y barata.

---

## G-1 · ¿El proyecto es legalmente posible? 🔴 — *Semana 6–10*

**Qué debe estar sobre la mesa:**
1. **Certificado de tradición y libertad** del predio (3.1.1) → ¿hay folio propio o Rosa es comunera?
2. **Estudio de títulos** con concepto de "apto / no apto / apto condicionado" (3.1.2).
3. **Concepto de uso del suelo** y **norma urbanística específica** (2.1.1, 2.1.2) → densidad máxima, índice de ocupación, área mínima, aislamientos, cesiones.
4. **Respuesta de Corpoboyacá** sobre ronda hídrica y determinantes ambientales (3.5.1).
5. **Carta de disponibilidad de acueducto** o, al menos, concepto verbal documentado del prestador (6.1).
6. **Concepto sobre acceso** jurídicamente asegurado (2.3.3).
7. **Ruta de licencias** definida (2.2).

**Preguntas de la decisión:** ¿Cuántas unidades permite realmente la norma? ¿El predio es titulable? ¿Hay agua? ¿Hay acceso? ¿Hay restricción ambiental que reduzca el área?

**Si la respuesta es "3 unidades":** el modelo económico cambia por completo y hay que rehacerlo antes de seguir.
**Si no hay folio propio y Marta no firma:** **NO-GO**, o el proyecto queda suspendido hasta resolverlo, sin gastar más.

**Costo hundido si se para aquí: $3–8 millones. Es el mejor dinero que este equipo puede gastar.**

---

## G-2 · ¿El negocio da? 🔴 — *Semana 14–20*

**Qué debe estar sobre la mesa:**
1. **Presupuesto detallado con APU y cotizaciones reales** (5.7.1) — no la hipótesis de $2.000.000/m².
2. **Estudio de suelos** y su impacto en la cimentación (5.2).
3. **Presupuesto de conexión de energía y de agua** (6.1.4, 6.3.2).
4. **Estudio de comparables con cierres verificados** y **velocidad de absorción** del submercado (2.4).
5. **Memorando tributario de la contadora** con la provisión de renta e ICA (4.4).
6. **Modelo de flujo de caja** con escenario base y **escenario lento** (venta en 24–30 meses en vez de 12).
7. Costo total del capítulo blando (diseños, licencias, jurídico, marketing) cotizado, no estimado.

**Preguntas de la decisión:** ¿Cuál es la utilidad **después de impuestos** y **después de remunerar el trabajo de los socios**? ¿Aguanta el escenario lento? ¿Cuál es el margen sobre ventas?

**[RE] Criterio de referencia:** un proyecto de vivienda de esta escala, con este nivel de riesgo (predio ajeno, sin crédito, socios de dedicación parcial), **debería mostrar un margen sobre ventas de al menos 20–25% después de impuestos y después de remunerar el trabajo** para justificar el riesgo. Si el margen queda por debajo del 15%, **el proyecto no compensa el riesgo personal que asume el socio gestor** y hay que rediseñar el negocio, no seguirlo.

---

## G-3 · ¿Aseguramos el suelo y cerramos el producto? 🔴 — *Semana 20–26*

**Qué debe estar sobre la mesa:**
1. **Decisión PH vs. loteo** con concepto de la curaduría (11.1).
2. **Diseño arquitectónico cerrado** incluida la fachada (5.3), y decidido si son 5 casas iguales o 4+1 (tema abierto N.° 1).
3. **Contrato con Rosa firmado** y, sobre todo, **el mecanismo de aseguramiento del suelo definido y en trámite** (4.3): escritura + hipoteca, fiducia, o promesa por escritura pública.
4. **Precio de venta definitivo** y franja de negociación (tema abierto N.° 2).
5. **Honorarios de cada socio definidos** (tema abierto N.° 5).
6. **Modelo laboral decidido** (tema abierto N.° 6) con su costo incorporado al presupuesto.

**Pregunta de la decisión:** ¿tenemos derecho oponible sobre el lote, producto cerrado y precio definido?

**[RE] Regla dura: no se radica licencia ni se pagan expensas sin haber cerrado G-3.** Pagar expensas sobre un predio que no se controla es regalar plata.

---

## G-4 · ¿Radicamos y pagamos expensas? — *Semana 26–30*

**Qué debe estar sobre la mesa:** el expediente completo de 7.1, la liquidación de expensas, y la caja disponible.

**Pregunta:** ¿tenemos con qué pagar expensas, impuesto de delineación y plusvalía si aplica, **sin comprometer el capital que se necesita para arrancar obra**?

**Este es el primer desembolso grande e irrecuperable.**

---

## G-5 · PUNTO DE NO RETORNO FINANCIERO 🔴🔴 — *Orden de inicio de obra*

**Este es el punto que hay que tener perfectamente identificado. A partir de aquí, el proyecto no se puede parar sin pérdida grave.**

**Por qué es el punto de no retorno, y no la licencia:**
- Hasta antes de la orden de inicio, lo gastado son estudios, diseños, licencias y marketing: **entre el 8% y el 15% del costo total**. Doloroso, pero absorbible.
- Desde la orden de inicio, el proyecto adquiere **tres compromisos simultáneos que no se pueden deshacer**: (i) contratos de obra con plazos y multas; (ii) **promesas de compraventa con compradores que ya entregaron dinero** y que tienen derecho a la entrega o a la devolución con cláusula penal; (iii) **una obra a medio hacer, que vale menos que la suma de lo invertido en ella** —una estructura sin acabados en un lote rural no tiene mercado.
- Y hay un cuarto: **el escalonamiento del pago a Rosa sigue corriendo** aunque la obra esté parada.

**Qué debe estar sobre la mesa antes de dar la orden de inicio:**
1. **Licencia ejecutoriada** (7.2.4) y valla instalada.
2. **Radicación municipal para enajenación de vivienda** (8.2.3).
3. **Punto de equilibrio alcanzado**: **[RE] mínimo 2 unidades vendidas con la cuota inicial efectivamente recaudada en la cuenta del proyecto**, no prometida.
4. **Flujo de caja que demuestre** que con el recaudo comprometido más el capital propio se llega a **obra gris de las unidades vendidas**, aun si no se vende ninguna más en 6 meses.
5. **Contratos de obra firmados con precios cerrados** (9.1).
6. **Personal afiliado a seguridad social y ARL, y SG-SST implementado** (9.3).
7. **Suelo asegurado** (4.3), efectivamente registrado.
8. **Pólizas vigentes**, incluida la de responsabilidad civil extracontractual.

**Si alguno de los ocho falta: no se da la orden de inicio.** Sin excepción, y sin importar la presión de un comprador entusiasta.

---

## G-6 · ¿Seguimos con la segunda etapa (unidades 3, 4 y 5)? — *Obra gris de las primeras unidades*

**Qué debe estar sobre la mesa:** costo real por m² ejecutado vs. presupuestado; velocidad de ventas real vs. proyectada; caja disponible; estado de la licencia y su vencimiento.

**Decisión:** ¿se arranca el segundo frente, o se termina y entrega el primero y se espera?

**[RE] Esta es la válvula de seguridad del proyecto y por eso recomiendo la construcción por frentes.** Un proyecto de 5 unidades construido por frentes puede detenerse ordenadamente; uno construido de golpe, no.

---

## G-7 · ¿Se ajusta el precio? — *Cada 3 meses durante la comercialización*

**Qué debe estar sobre la mesa:** leads, visitas, ofertas recibidas, ofertas rechazadas y por qué, precio de la competencia, y **el costo de tener la unidad parada** (predial, vigilancia, deterioro, **escalonamiento del pago a Rosa**, costo de oportunidad).

**[RE] Regla: si a los 6 meses de lanzamiento no hay al menos una venta, el problema no es el mercado, es el precio o el producto. Bajar $20 millones a tiempo cuesta menos que esperar un año.**

---

## G-8 · ¿Se reparte utilidad? — *Cierre*

**Qué debe estar sobre la mesa:** todas las escrituras registradas; impuestos liquidados y provisionados; **provisión de posventa constituida**; paz y salvos laborales de todos los contratistas; liquidación con Rosa.

**[RE] Regla: no se reparte un peso antes de que estén los cuatro.**

---

# PARTE III — ENTREGABLES ADICIONALES

---

## A. RUTA CRÍTICA

**Ruta crítica** = la cadena de actividades donde **un día de retraso es un día de retraso de todo el proyecto**. Todo lo demás tiene holgura.

### A.1 La cadena crítica del proyecto

```
3.1 Estudio de títulos / folio de matrícula
        ↓  (si no hay folio propio)
3.2 Regularización de la división del englobe        ← el mayor riesgo de plazo (3–9 meses)
        ↓
2.1 Concepto de uso del suelo y norma urbanística
        ↓
5.1 Diseño de implantación (densidad, ocupación, aislamientos)
        ↓
5.2 Estudio de suelos  →  5.3 Diseño arquitectónico definitivo  →  5.4 Diseño estructural
        ↓                                    ↓
6.1 Disponibilidad de acueducto  ←──── (paralelo, pero BLOQUEA la radicación)
        ↓
11.1 Decisión PH vs. loteo                            ← si se decide tarde, se rehace la licencia
        ↓
7.1 Radicación de licencia  →  7.2 Trámite y resolución  →  ejecutoria
        ↓
8.2 Radicación municipal para enajenación de vivienda  ← BLOQUEA todo el recaudo
        ↓
8.3 Minutas + 8.5 política comercial  →  primera venta con recaudo
        ↓
G-5 Orden de inicio de obra
        ↓
10.1 Preliminares → 10.3 Estructura → 10.4 Instalaciones → 10.5 Acabados
        ↓
10.6 Certificación RETIE y conexión definitiva de servicios   ← cuello de botella típico
        ↓
11.2 Constitución de la PH y apertura de folios individuales  ← el otro cuello de botella
        ↓
12.1 PRIMERA ESCRITURA
```

### A.2 Las siete actividades que, si se atrasan, atrasan todo

| # | Actividad | Por qué es crítica | Holgura real |
|---|---|---|---|
| 1 | **3.1 / 3.2 Folio de matrícula del predio** | Sin folio no hay licencia, ni escritura, ni crédito, ni garantía | **Cero** |
| 2 | **2.1 Norma urbanística (densidad)** | Define cuántas unidades hay; todo el diseño depende de esto | **Cero** |
| 3 | **6.1 Disponibilidad de acueducto** | Requisito de radicación; en acueducto veredal puede depender de una asamblea | **Cero** |
| 4 | **7.2 Resolución de licencia** | Es el permiso para todo | **Cero** |
| 5 | **8.2 Radicación municipal para enajenar** | Es el permiso para **recibir plata**, que es la única fuente de financiación | **Cero** |
| 6 | **11.2 Constitución de PH y apertura de folios** | Sin folio individual no hay escritura ni desembolso de crédito | **Cero — y se subestima siempre** |
| 7 | **10.6 Certificación RETIE y conexión de servicios** | Sin energía definitiva no hay entrega ni pago del saldo | **Cero — y se descubre tarde** |

**[RE] Los números 6 y 7 son los que arruinan el cierre de los proyectos pequeños.** Todo el mundo cuida la licencia y nadie cuida los folios y el RETIE, que aparecen justo cuando ya no hay caja y los compradores esperan.

### A.3 Secuencia mínima desde hoy hasta la primera escritura

**Escenario optimista (el predio SÍ tiene folio propio):**

| Paso | Actividad | Semanas | Acumulado |
|---|---|---|---|
| 1 | Certificado de tradición + estudio de títulos + concepto de uso del suelo + autorización de Rosa | 4 | **S4** |
| 2 | Norma urbanística + consulta ambiental + solicitud de disponibilidad de agua y energía | 4 | **S8** |
| 3 | Topografía + estudio de suelos (en paralelo) | 4 | **S12** |
| 4 | Diseño de implantación + arquitectónico + decisión PH | 6 | **S18** |
| 5 | Diseño estructural + eléctrico + hidrosanitario (en paralelo) + presupuesto detallado | 5 | **S23** |
| 6 | Aseguramiento del suelo (escritura/fiducia) + contrato con Rosa | 4 | **S27** |
| 7 | Preparación y radicación de licencia | 3 | **S30** |
| 8 | Trámite de licencia hasta ejecutoria | 12 | **S42** |
| 9 | Radicación municipal para enajenar + minutas + lanzamiento comercial | 6 | **S48** |
| 10 | Primera venta con cuota inicial recaudada (punto de equilibrio) | 8–16 | **S56–S64** |
| 11 | Obra de la primera unidad hasta certificaciones | 40–50 | **S96–S114** |
| 12 | Constitución de PH y apertura de folios (adelantada en paralelo desde S85) | 0–4 | **S100–S118** |
| 13 | Escrituración y desembolso | 4–6 | **S104–S124** |

**Primera escritura: entre el mes 24 y el mes 29 desde hoy.**

**Escenario con regularización del englobe:** sumar **12 a 36 semanas** al paso 1 → **primera escritura entre el mes 27 y el mes 38**.

**[RE] Confrontación con el acta:** el horizonte del acta es *"vender la totalidad en 12 meses"*. **Eso no es alcanzable ni en el escenario optimista**, porque en 12 meses el proyecto apenas estará radicando o iniciando obra. Lo alcanzable en 12 meses es **vender sobre planos**, no escriturar. **El contrato con Rosa debe redactarse contra el calendario real, no contra el deseado**, porque el escalonamiento de $140.000 → $150.000 → $160.000 por m² se activa por el paso del tiempo y **el proyecto va a caer, con alta probabilidad, en el segundo y tercer año**. Eso son **$52 millones adicionales** de costo del lote que el modelo económico del acta no contempla.

---

## B. CRONOGRAMA MAESTRO POR FASES

### B.1 Vista de barras (meses desde el arranque)

Convención: `█` = actividad principal · `▒` = actividad de baja intensidad o seguimiento · `·` = sin actividad

```
FASE                              M1  M2  M3  M4  M5  M6  M7  M8  M9 M10 M11 M12 M13 M14 M15 M16 M17 M18 M19 M20 M21 M22 M23 M24 M25 M26 M27 M28 M29 M30 M31 M32 M33 M34 M35 M36
1 Gobierno y arranque             █   █   ▒   ▒   ▒   ▒   ▒   ▒   ▒   ▒   ▒   ▒   ▒   ▒   ▒   ▒   ▒   ▒   ▒   ▒   ▒   ▒   ▒   ▒   ▒   ▒   ▒   ▒   ▒   ▒   ▒   ▒   ▒   ▒   ▒   ▒
2 Prefactibilidad                 █   █   █   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·
3 Debida diligencia del predio    █   █   █   ▒   ▒   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·
4 Estructuración jurídica/tribut. ·   █   █   █   █   ▒   ▒   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·
5 Estudios técnicos y diseño      ·   ·   █   █   █   █   █   ▒   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·
6 Servicios públicos y ambiental  ·   ·   █   █   █   █   ▒   ▒   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·
7 Licenciamiento                  ·   ·   ·   ·   ·   ·   █   █   █   █   █   ▒   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·
8 Comercial y lanzamiento         ·   ·   ▒   ▒   ▒   █   █   █   █   █   █   █   █   █   █   █   █   █   █   █   █   █   █   █   █   █   ▒   ▒   ▒   ·   ·   ·   ·   ·   ·   ·
9 Preparación de obra             ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   █   █   █   ▒   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·
10 Ejecución de obra              ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   █   █   █   █   █   █   █   █   █   █   █   █   █   █   ▒   ·   ·   ·   ·   ·   ·   ·   ·
11 Titulación (PH y folios)       ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ▒   ▒   █   █   █   ▒   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·
12 Escrituración y entrega        ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   █   █   █   █   █   █   █   ▒   ·   ·   ·   ·   ·
13 Posventa y garantías           ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   █   █   █   █   █   █   █   █   █   █   █   █
14 Cierre y liquidación           ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   ·   █   █   █   ·   ·   ·
```

**Hitos sobre la línea de tiempo:**

| Hito | Mes |
|---|---|
| **G-0** Arranque | M1 |
| **G-1** Viabilidad legal | M2–M3 |
| **G-2** Viabilidad del negocio | M4–M5 |
| **G-3** Suelo asegurado + producto cerrado | M5–M7 |
| **G-4** Radicación de licencia | M7 |
| Licencia ejecutoriada | M11 |
| Habilitación para enajenar (8.2) | M12 |
| **G-5 PUNTO DE NO RETORNO — orden de inicio de obra** | **M13–M16** |
| **G-6** Decisión de segundo frente | M19–M21 |
| Primera escritura | **M24–M29** |
| Última escritura (escenario base) | M30 |
| **G-8** Reparto de utilidad | M31–M33 |
| Vencimiento garantía de acabados (1 año desde cada entrega) | M36–M42 |
| Vencimiento garantía de estabilidad (10 años) | **M144+** |

### B.2 Qué corre en paralelo (y qué no puede)

**Sí corre en paralelo:**
- Fases 2 y 3 (prefactibilidad y debida diligencia) — **deben** correr juntas.
- Fase 4 (jurídico/tributario) con Fase 5 (diseño).
- Fase 6 (servicios) con Fase 5 (diseño) — **crítico: si se dejan los servicios para después del diseño, se pierden 2 meses**.
- Diseño estructural, eléctrico e hidrosanitario entre sí, una vez cerrado el arquitectónico.
- Fase 8 (preparación comercial) con Fase 7 (licenciamiento) — **la marca y los renders se hacen mientras la curaduría estudia**.
- Fase 11 (PH) con el 60–70% de la Fase 10 (obra) — **esto es lo que evita el cuello de botella del cierre**.
- Fase 13 (posventa) con Fase 12 y 14.

**NO puede correr en paralelo:**
- Diseño arquitectónico definitivo antes de tener la norma (2.1).
- Diseño estructural antes del estudio de suelos (5.2).
- Radicación de licencia antes de las disponibilidades de servicios (6.1, 6.3).
- Recibir dinero antes de la radicación municipal (8.2).
- Iniciar obra antes de licencia ejecutoriada, punto de equilibrio y afiliaciones (G-5).
- Escriturar antes de tener folio individual (11.2/11.3) y servicios definitivos (10.6).

### B.3 Versión para hoja de cálculo (CSV)

Copiar el bloque siguiente en un archivo `.csv` y abrirlo en Excel o Google Sheets:

```csv
Fase;Subfase;Codigo;Actividad;Responsable;Tercero_externo;Mes_inicio;Mes_fin;Duracion_semanas_min;Duracion_semanas_max;Precedencia;Hito;Critica
1;Gobierno;1.1;Constitucion del equipo y reglas;ADM;;1;1;2;3;-;;No
1;Gobierno;1.2;Sistema de informacion y archivo;COM;;1;1;1;2;-;;No
1;Gobierno;1.3;Presupuesto maestro por capitulos;DAO+ADM;Contadora;1;2;2;2;-;;No
2;Prefactibilidad;2.1;Verificacion normativa POT;DAO;Curador/Planeacion;1;2;2;4;3.1;G-1;SI
2;Prefactibilidad;2.2;Ruta de licencias;JUR;Curador;2;3;2;3;2.1;;SI
2;Prefactibilidad;2.3;Prefactibilidad tecnica del predio;DAO;;1;2;1;2;-;;No
2;Prefactibilidad;2.4;Prefactibilidad comercial y precio;COM;Inmobiliarias;1;3;3;4;-;G-2;No
3;Debida diligencia;3.1;Estudio de titulos;JUR;ORIP/Abogado;1;2;2;4;-;G-1;SI
3;Debida diligencia;3.2;Regularizacion del englobe (contingente);JUR;Curador/Notario/ORIP;2;8;12;36;3.1;G-1;SI
3;Debida diligencia;3.3;Topografia y amojonamiento;DAO;Topografo;3;3;1;2;3.4;;SI
3;Debida diligencia;3.4;Autorizacion de Rosa;JUR;Notario;1;1;1;1;-;;SI
3;Debida diligencia;3.5;Verificacion ambiental preliminar;JUR;Corpoboyaca;2;4;3;8;-;G-1;SI
4;Juridico;4.1;Acuerdo con la propietaria;JUR;Contadora/Notario;2;3;2;4;3.1;G-3;SI
4;Juridico;4.2;Figura de operacion;JUR;Contadora/Camara;3;4;3;4;4.1;;No
4;Juridico;4.3;Aseguramiento del suelo (garantia real);JUR;Notario/ORIP/Fiduciaria;4;6;3;6;4.1;G-3;SI
4;Juridico;4.4;Estructuracion tributaria;JUR+ADM;Contadora;3;4;3;4;4.2;G-2;No
4;Juridico;4.5;Modelos contractuales;JUR;;4;5;3;4;4.2;;No
5;Diseno;5.1;Implantacion loteo y vias;DAO;;3;4;3;5;2.1+3.3+3.5;;SI
5;Diseno;5.2;Estudio geotecnico;DAO;Geotecnista;4;5;3;5;3.4+5.1;G-2;SI
5;Diseno;5.3;Diseno arquitectonico definitivo;DAO;;4;6;5;8;5.1+5.2;G-3;SI
5;Diseno;5.4;Diseno estructural;DAO;Calculista;6;7;3;5;5.2+5.3;;SI
5;Diseno;5.5;Diseno electrico RETIE;DAO;Ing electrico;6;7;3;4;5.3;;No
5;Diseno;5.6;Diseno hidrosanitario y gas;DAO;Ing hidrosanitario;6;7;3;4;5.3+6.1;;No
5;Diseno;5.7;Presupuesto detallado y programacion;DAO+ADM;;7;7;3;4;5.3+5.4+5.5+5.6;G-2;SI
6;Servicios;6.1;Disponibilidad de acueducto;DAO;Acueducto/Corpoboyaca;3;5;3;8;3.1;G-1;SI
6;Servicios;6.2;Alcantarillado o solucion individual;JUR;Corpoboyaca;4;7;6;16;5.2+5.6;;SI
6;Servicios;6.3;Energia electrica;DAO;Operador de red;3;5;4;10;3.1;;SI
6;Servicios;6.4;Gas y otros servicios;DAO;Distribuidora;4;5;2;4;-;;No
6;Servicios;6.5;Permisos ambientales especificos;JUR;Corpoboyaca;5;8;6;20;5.1+5.6;;No
7;Licencias;7.1;Preparacion y radicacion;JUR;Curador;7;7;2;3;5.3+5.4+6.1+6.3+11.1;G-4;SI
7;Licencias;7.2;Tramite y resolucion;JUR;Curador;8;11;8;16;7.1;;SI
7;Licencias;7.3;Licencia de espacio publico;JUR;Planeacion;8;9;4;8;5.1;;No
8;Comercial;8.1;Marca identidad y piezas;COM;;6;9;6;10;5.3;;No
8;Comercial;8.2;Habilitacion legal para enajenar;JUR;Municipio;11;12;3;6;7.2+4.2;G-5;SI
8;Comercial;8.3;Documentos de vinculacion;JUR;;10;12;3;4;4.4+5.3+7.2;;SI
8;Comercial;8.4;Plataforma digital y pauta;COM;;9;11;4;6;8.1;;No
8;Comercial;8.5;Frontera legal de comercializacion;JUR;;12;12;1;1;8.2+8.3;;No
8;Comercial;8.6;Canales y operacion comercial;COM;Inmobiliarias;10;26;4;6;8.1+8.3+8.5;;No
9;Preparacion obra;9.1;Contratacion de obra;ADM;Contratistas;11;12;4;6;5.7+7.2+8.2;;SI
9;Preparacion obra;9.2;Organizacion almacen y control;ADM;;12;13;3;4;9.1;;No
9;Preparacion obra;9.3;SST y formalizacion laboral;ADM+JUR;ARL/Prof SST;11;13;3;4;9.1;G-5;SI
9;Preparacion obra;9.4;Logistica transporte proveedores;ADM;;11;12;3;4;5.7;;No
9;Preparacion obra;9.5;Servicios provisionales y actas vecindad;ADM;Operador de red;12;13;2;4;7.2+6.3;;SI
10;Obra;10.1;Preliminares y movimiento de tierras;DAO;Topografo;14;15;3;5;G-5;;SI
10;Obra;10.2;Urbanismo interno y accesos;DAO;;15;19;10;16;10.1+7.3;;No
10;Obra;10.3;Cimentacion y estructura;DAO;Calculista/Laboratorio;15;20;12;20;10.1;;SI
10;Obra;10.4;Instalaciones;DAO;;19;22;6;10;10.3;;SI
10;Obra;10.5;Acabados;DAO;;21;26;10;16;10.4;;SI
10;Obra;10.6;Certificaciones y conexion definitiva;DAO;Organismo ONAC/Empresas;25;27;4;8;10.4+10.5;;SI
10;Obra;10.7;Control de avance y flujo de caja;DAO+ADM;;14;27;-;-;transversal;G-6;SI
11;Titulacion;11.1;Decision PH vs loteo;JUR;Curador;5;6;2;3;2.1+2.2;G-3;SI
11;Titulacion;11.2;Constitucion de PH;JUR;Abogado PH/Notario/ORIP;20;24;6;12;7.2+10.3;;SI
11;Titulacion;11.3;Ruta alternativa subdivision;JUR;Curador/Notario/ORIP;20;24;8;16;11.1;;SI
12;Cierre comercial;12.1;Escrituracion;JUR;Notario/Banco/Avaluador;24;30;4;10;11.2+10.6;;SI
12;Cierre comercial;12.2;Preparacion de la entrega;DAO;;24;30;1;2;10.5+10.6;;No
12;Cierre comercial;12.3;Acta de entrega y recibo;DAO+ADM;;24;30;1;3;12.1+12.2;;SI
12;Cierre comercial;12.4;Entrega zonas comunes y administracion;JUR;;28;30;3;5;11.2+10.2;;No
13;Posventa;13.1;Regimen de garantias y provision;JUR+ADM;Aseguradora;25;36;-;-;12.3;;No
13;Posventa;13.2;Protocolo de reclamaciones;ADM+DAO;;25;36;-;-;12.3;;No
13;Posventa;13.3;Acompanamiento a la copropiedad;DAO+ADM;;28;40;-;-;12.4;;No
14;Cierre;14.1;Liquidacion de contratistas;ADM;;31;32;4;6;10+12.3;;No
14;Cierre;14.2;Cierre contable y tributario;ADM;Contadora;31;33;4;8;12.1+14.1;;SI
14;Cierre;14.3;Liquidacion de cuentas en participacion;JUR;Contadora;33;33;2;4;14.2;G-8;SI
14;Cierre;14.4;Archivo y leccciones aprendidas;ADM;;33;33;2;3;14.3;;No
```

**Nota de uso:** el separador es punto y coma (`;`) para que Excel en configuración regional colombiana lo abra directo en columnas. Los meses son **relativos al arranque**, no fechas de calendario: cuando se defina la fecha de inicio real, se convierten con una fórmula.


---

## C. MATRIZ RACI DE LAS SUBFASES PRINCIPALES

**Convención:**
- **R = Responsable** (hace el trabajo). Puede haber más de uno.
- **A = Aprobador** (rinde cuentas y firma). **Uno solo por subfase.**
- **C = Consultado** (aporta antes de decidir, hay diálogo).
- **I = Informado** (se le avisa después).
- **X = Tercero externo indispensable.**

| Cód. | Subfase | DAO (Hugo Ignacio) | JUR (Hugo Ernesto) | COM (Sergio) | ADM (María Mercedes) | Tercero externo |
|---|---|:--:|:--:|:--:|:--:|---|
| 1.1 | Constitución del equipo y reglas | C | R | C | **A**/R | — |
| 1.2 | Sistema de información y archivo | I | I | **A**/R | R | — |
| 1.3 | Presupuesto maestro | **A**/R | C | I | R | X Contadora |
| 2.1 | Verificación normativa POT 🔴 | **A**/R | C | I | I | X Curador, Planeación |
| 2.2 | Ruta de licencias | C | **A**/R | I | I | X Curador, Contadora |
| 2.3 | Prefactibilidad técnica del predio | **A**/R | C | R (dron) | C | — |
| 2.4 | Prefactibilidad comercial y precio | C | I | **A**/R | I | X Inmobiliarias, Avaluador |
| 3.1 | Estudio de títulos 🔴 | I | **A**/R | I | I | X ORIP, Abogado |
| 3.2 | Regularización del englobe 🔴 | C | **A**/R | I | I | X Topógrafo, Curador, Notario |
| 3.3 | Topografía y amojonamiento | **A**/R | C | I | C | X **Topógrafo** |
| 3.4 | Autorización de Rosa | R | **A**/R | I | I | X Notario |
| 3.5 | Verificación ambiental preliminar | R | **A**/R | I | I | X Corpoboyacá |
| 4.1 | Acuerdo con la propietaria | R | **A**/R | I | C | X Contadora, Notario |
| 4.2 | Figura de operación | C | **A**/R | I | R | X Contadora, Cámara de Comercio |
| 4.3 | Aseguramiento del suelo 🔴 | C | **A**/R | I | C | X Notario, ORIP, Fiduciaria |
| 4.4 | Estructuración tributaria | C | R | I | **A**/R | X **Contadora** |
| 4.5 | Modelos contractuales | C | **A**/R | C | R | — |
| 5.1 | Implantación, loteo y vías | **A**/R | C | C | I | X Topógrafo |
| 5.2 | Estudio geotécnico | **A**/R | I | I | C | X **Geotecnista** |
| 5.3 | Diseño arquitectónico definitivo | **A**/R | I | R (renders) | I | — |
| 5.4 | Diseño estructural | **A**/R | I | I | I | X **Calculista** |
| 5.5 | Diseño eléctrico RETIE | **A**/R | I | I | C | X Ing. eléctrico, ONAC |
| 5.6 | Diseño hidrosanitario y gas | **A**/R | I | I | C | X Ing. hidrosanitario |
| 5.7 | Presupuesto detallado y programación | **A**/R | I | C | R | — |
| 6.1 | Disponibilidad de acueducto 🔴 | **A**/R | C | I | I | X Acueducto, Corpoboyacá |
| 6.2 | Alcantarillado o solución individual | R | **A**/R | I | I | X Corpoboyacá |
| 6.3 | Energía eléctrica | **A**/R | I | I | C | X Operador de red |
| 6.4 | Gas y otros servicios | **A**/R | I | C | R | X Distribuidora |
| 6.5 | Permisos ambientales específicos | R | **A**/R | I | C | X Corpoboyacá, Gestor RCD |
| 7.1 | Radicación de licencia | R | **A**/R | I | C | X Curador |
| 7.2 | Trámite y resolución | R | **A**/R | I | I | X Curador |
| 7.3 | Licencia de espacio público | R | **A**/R | I | I | X Planeación |
| 8.1 | Marca, identidad y piezas | C | C | **A**/R | I | X Renderista si se externaliza |
| 8.2 | Habilitación para enajenar 🔴 | I | **A**/R | C | R | X Municipio, Fiduciaria |
| 8.3 | Documentos de vinculación | C | **A**/R | C | C | — |
| 8.4 | Plataforma digital y pauta | I | C | **A**/R | C | — |
| 8.5 | Frontera legal de comercialización | I | **A**/R | R | C | — |
| 8.6 | Canales y operación comercial | C | C | **A**/R | R (comisiones) | X Inmobiliarias |
| 9.1 | Contratación de obra | R | C | I | **A**/R | — |
| 9.2 | Organización, almacén y control | C | I | I | **A**/R | — |
| 9.3 | SST y formalización laboral 🔴 | R | C | I | **A**/R | X **ARL, profesional SST** |
| 9.4 | Logística y proveedores | C | I | I | **A**/R | — |
| 9.5 | Servicios provisionales y actas de vecindad | R | C | I | **A**/R | X Operador de red |
| 10.1 | Preliminares y tierras | **A**/R | I | I | C | X Topógrafo |
| 10.2 | Urbanismo interno y accesos | **A**/R | C | I | R | X Empresas de servicios |
| 10.3 | Cimentación y estructura | **A**/R | I | I | R | X Calculista, Laboratorio |
| 10.4 | Instalaciones | **A**/R | I | C (fotos libro) | R | — |
| 10.5 | Acabados | **A**/R | I | C | R | — |
| 10.6 | Certificaciones y conexión definitiva | **A**/R | C | I | R | X Organismos ONAC, Empresas |
| 10.7 | Control de avance y flujo de caja | R | I | C | **A**/R | — |
| 11.1 | Decisión PH vs. loteo 🔴 | C | **A**/R | C | I | X Curador |
| 11.2 | Constitución de PH | C | **A**/R | I | C | X Abogado PH, Notario, ORIP |
| 11.3 | Subdivisión (ruta alterna) | C | **A**/R | I | I | X Topógrafo, Curador, Notario |
| 12.1 | Escrituración | C | **A**/R | C | R | X Notario, Banco, Avaluador |
| 12.2 | Preparación de la entrega | **A**/R | I | R (libro) | R | — |
| 12.3 | Acta de entrega y recibo | **A**/R | C | I | R | — |
| 12.4 | Entrega de zonas comunes y administración | R | **A**/R | I | R | — |
| 13.1 | Régimen de garantías y provisión | C | **A**/R | I | R | X Aseguradora |
| 13.2 | Protocolo de reclamaciones | R | C | I | **A**/R | — |
| 13.3 | Acompañamiento a la copropiedad | **A**/R | C | I | R | — |
| 14.1 | Liquidación de contratistas | C | C | I | **A**/R | — |
| 14.2 | Cierre contable y tributario | I | C | I | **A**/R | X **Contadora** |
| 14.3 | Liquidación y reparto | C | **A**/R | I | R | X Contadora |
| 14.4 | Archivo y lecciones aprendidas | R | R | R | **A**/R | — |

### C.1 Lectura de la matriz — tres alertas de carga

1. **DAO (Hugo Ignacio) es aprobador de 22 subfases y responsable en 35.** Es, de lejos, el cuello de botella humano del proyecto. Y es la persona que además tiene su trabajo regular. **[RE] Hay que descargarlo: la topografía, el presupuesto detallado y el control de obra pueden delegarse parcialmente en un residente de obra remunerado, y ese costo debe estar en el presupuesto desde hoy.**
2. **JUR (Hugo Ernesto) es aprobador de 21 subfases**, muchas de ellas críticas y simultáneas en los meses 1 a 7 (títulos, ambiental, contrato con Rosa, figura societaria, tributario, licencias). **[RE] Los meses 1–7 son el pico de carga jurídica; conviene apoyarse en un abogado externo para el estudio de títulos y el reglamento de PH.**
3. **COM (Sergio) tiene poca carga en los meses 1–5 y mucha del 6 en adelante.** **[RE] Aprovechar los primeros meses para que COM lidere 2.4 (prefactibilidad comercial), que es una subfase decisiva y hoy no tiene doliente claro en el acta.**
4. **ADM (María Mercedes) es la única aprobadora del control de costos, del recaudo, del almacén y del cierre.** Es el rol de control interno del proyecto. **[RE] Ninguna de esas cuatro cosas debe pasar a manos de quien ejecuta el gasto. Sepárenlas siempre.**

---

## D. MATRIZ DE RIESGOS PRIORIZADA

**Escalas:** Probabilidad y Alto/Medio/Bajo · **Exposición** = combinación de ambas · Ordenada de mayor a menor exposición.

| # | Riesgo | Prob. | Impacto | Señal temprana de alerta | Plan de respuesta |
|---|---|:--:|:--:|---|---|
| **R-01** | **El lote no tiene folio de matrícula propio; Rosa es comunera del englobe** | **Alta** | **Crítico** | El recibo de predial llega a nombre de otro o del englobe (ya está ocurriendo, según el acta) | **Sacar el certificado de tradición esta semana** (3.1.1). Si se confirma: suspender todo gasto, obtener compromiso escrito de los cuatro comuneros, y evaluar el plazo real de regularización. Si Marta no responde, **NO-GO temporal**. |
| **R-02** | **Iliquidez: se acaba la caja con la obra a medias** | **Alta** | **Crítico** | El recaudo mensual cae por debajo del compromiso de pago de los 60 días siguientes; se empieza a pagar a contratistas con retraso | Punto de equilibrio duro antes de iniciar (G-5); **construcción por frentes**; regla de "no pagar avance por encima del recaudo" (9.1.6); línea de crédito personal precomprometida como respaldo; **frenar obra ordenadamente antes de quedar en cero, no después** |
| **R-03** | **Densidad o índice de ocupación no permiten 5 unidades** | **Media-Alta** | **Crítico** | La norma urbanística menciona densidades por hectárea muy inferiores a 19 viv/ha o exige 70% en cobertura vegetal | Resolver en G-1. Escenarios de 4 y de 3 unidades ya modelados económicamente **antes** de recibir la respuesta, para poder decidir en la misma semana |
| **R-04** | **Accidente laboral grave con personal no afiliado** | **Media** | **Crítico** | Personal en obra sin planilla del mes; trabajo en cubierta sin arnés; ausencia de EPP | **Formalización (9.3.1 opción a o b)**; ninguna persona entra al predio sin afiliación vigente verificada por ADM; póliza de RCE; SG-SST implementado; capacitación en alturas |
| **R-05** | **Rosa se retracta, muere, es embargada o cambia condiciones** | **Media** | **Crítico** | Demoras en responder, consultas a terceros sobre el lote, aparición de un tercero interesado | **Aseguramiento del suelo con garantía real antes de G-4** (4.3). Mientras no exista, **limitar el gasto acumulado a lo que se esté dispuesto a perder** |
| **R-06** | **La absorción del mercado es de 1 casa cada 5–6 meses, no 5 en 12 meses** | **Alta** | **Alto** | Menos de 8 leads calificados al mes; ninguna oferta a los 4 meses de lanzamiento | Modelar el escenario lento desde G-2; **construcción por frentes**; revisión de precio cada 3 meses (G-7); ampliar canales (Bogotá, Villa de Leyva, Tunja); negociar tope al escalonamiento con Rosa |
| **R-07** | **Costo real de construcción supera el estimado de $2.000.000/m²** | **Alta** | **Alto** | Las primeras cotizaciones por capítulo superan el APU en más de 10%; el acero o el concreto suben | Presupuesto con cotizaciones reales antes de fijar precio (G-2); **imprevistos al 10%**; contratos a precio unitario fijo; compras de materiales de mayor incidencia con precio cerrado y vigencia |
| **R-08** | **No hay disponibilidad de agua para 5 unidades** | **Media** | **Crítico** | El acueducto veredal no tiene concesión vigente o su caudal está copado | Verificar la concesión del prestador ante Corpoboyacá **antes** de diseñar (6.1.3). Si no hay: replantear número de unidades o evaluar concesión propia con su costo y plazo |
| **R-09** | **La licencia se vence antes de terminar de vender** | **Media-Alta** | **Alto** | Han pasado 18 meses de la ejecutoria y hay unidades sin iniciar | **Iniciar obra dentro de la vigencia** protege el derecho a prórroga; alarma en el tablero a 6 y a 3 meses del vencimiento; solicitar prórroga dentro del plazo reglamentario |
| **R-10** | **Recaracterización tributaria del contrato con Rosa o del esquema de dos licencias** | **Media** | **Alto** | La contadora no puede sustentar por escrito el tratamiento | Concepto escrito de la contadora **antes** de firmar (4.1.5); si no hay sustento sólido, migrar a promesa de compraventa (1.B) |
| **R-11** | **Carga tributaria no provisionada devora la utilidad** | **Alta** | **Alto** | El modelo económico muestra utilidad sin línea de impuestos (situación actual del acta) | Provisión de renta e ICA desde la primera venta (4.4); no repartir hasta liquidar (G-8) |
| **R-12** | **Cuello de botella de titulación: PH constituida tarde** | **Media-Alta** | **Alto** | Casas terminadas y aún sin folios individuales | Iniciar 11.2 cuando la obra vaya en 60–70%; abogado especialista contratado con anticipación |
| **R-13** | **Sin certificación RETIE o sin conexión definitiva al terminar** | **Media** | **Alto** | No hay respuesta del operador de red al mes 8; no se ha cotizado el transformador | Iniciar 6.3 en la Fase 6; presupuestar certificación por unidad; contratar el organismo de inspección con anticipación |
| **R-14** | **Socios de dedicación parcial: el proyecto se detiene por falta de tiempo** | **Alta** | **Medio-Alto** | Tareas del tablero que llevan 3 semanas sin avanzar; reuniones que se aplazan | Comité semanal con hora fija e inamovible; **residente de obra remunerado** desde el inicio de la Fase 10; delegar a terceros lo que no exija criterio de socio |
| **R-15** | **Estudio de suelos revela cimentación costosa (arcillas expansivas, nivel freático)** | **Media** | **Alto** | Evidencia de humedad, vegetación de zona húmeda, grietas en construcciones vecinas | Estudio geotécnico completo antes de G-2; incluir el sobrecosto en el escenario pesimista del modelo |
| **R-16** | **Faja de protección de la quebrada reduce el área útil** | **Media** | **Alto** | Corpoboyacá menciona ronda hídrica o el POT marca área de protección | Consulta a Corpoboyacá en G-1; rediseño de implantación con 4 unidades como plan B |
| **R-17** | **Un comprador pierde el crédito hipotecario tras meses de obra** | **Media** | **Alto** | El comprador no entrega documentos al banco; su score cambia | **Precalificación crediticia antes de firmar promesa** (12.1.6.1); condición resolutoria en la promesa; no comprometer el 100% de la caja a una sola venta |
| **R-18** | **Reclamación de posventa sin provisión** | **Media** | **Medio-Alto** | Se reparte utilidad sin haber constituido la provisión | Provisión de posventa **antes** del reparto (13.1.3, G-8); retenciones en garantía y pólizas de contratistas alineadas |
| **R-19** | **Conflicto entre los cuatro socios por honorarios o reparto** | **Media** | **Alto** | Comentarios sobre "quién trabajó más"; tareas que nadie asume | Definir honorarios **antes** de que haya plata (1.1.2); contrato entre socios (4.2.3); orden de aplicación de recursos escrito (14.3.3) |
| **R-20** | **Oposición de vecinos colindantes (familiares) al trámite de licencia** | **Media** | **Medio** | Marta no responde llamadas (ya está ocurriendo); molestia por el acceso o por linderos | Acta de conciliación de linderos antes de radicar (3.3.2); conversación previa a la citación formal (7.2.1) |
| **R-21** | **Un socio recibe dinero de un comprador antes de la habilitación municipal** | **Media** | **Alto** | Un interesado "quiere separar ya" y no está el mecanismo listo | Política comercial escrita y firmada (8.5); un solo canal de recaudo; **decir que no** y ofrecer una carta de intención sin dinero |
| **R-22** | **Robo de materiales o herramienta en obra rural** | **Media-Alta** | **Medio** | Faltantes recurrentes en el inventario de almacén | Almacén cerrado con control de entradas y salidas (9.2.2); vigilancia presupuestada; compras justo a tiempo de material de alto valor |
| **R-23** | **Producto único en un mercado de rotación lenta** | **Alta** | **Medio-Alto** | Todos los interesados piden "algo más pequeño" o "algo más grande" | Diseñar la quinta unidad de 2 alcobas como **producto de entrada** deliberado, no como accidente del área (D-02); flexibilidad de acabados para ajustar precio sin destruir margen |
| **R-24** | **Fachada sin resolver retrasa el material comercial y la licencia** | **Media** | **Medio** | Tercera iteración de render sin acuerdo | Fecha de cierre de fachada con decisión por mayoría; contratar renderista externo si la iteración interna se estanca |
| **R-25** | **Compra del vehículo inmoviliza capital de arranque** | **Media** | **Medio** | Se avanza en la compra antes de tener obra contratada | Decisión con números (9.4.1); no comprar antes de G-5; arrancar con fletes y reevaluar al tercer mes de obra |
| **R-26** | **Sanción ambiental por tala o vertimiento sin permiso** | **Baja-Media** | **Alto** | Se programa descapote con árboles en el frente sin permiso en mano | Ningún corte sin acto administrativo; permiso de vertimiento o registro antes de operar el sistema séptico |
| **R-27** | **Publicidad que promete lo que no se entrega** | **Media** | **Medio** | El brochure menciona gas natural, adoquinado o portón automático sin respaldo documental | Regla de 8.1.5: toda afirmación con documento de respaldo; leyenda de imágenes ilustrativas; especificación de acabados anexa a la promesa |

### D.1 Los cinco riesgos estructurales de ESTE esquema

Los pidieron expresamente. Van juntos porque se refuerzan entre sí:

1. **Desarrollar sobre predio ajeno (R-01, R-05).** No es un riesgo aislado: es el que hace que **todos los demás gastos sean irrecuperables**. Mientras no haya garantía real, cada peso invertido es un peso apostado a la buena voluntad de un tercero.
2. **Ausencia de crédito constructor (R-02).** Convierte al proyecto en **rehén de la velocidad de ventas**, que es la variable que menos controla. Y como la venta requiere licencia + habilitación municipal, el proyecto tiene que gastar entre 10 y 14 meses **antes** de poder recibir el primer peso.
3. **Informalidad laboral (R-04).** Es el único riesgo del listado que puede **destruir el patrimonio personal** del socio gestor, no solo el proyecto. Y es el más barato de mitigar en términos relativos.
4. **Socios de dedicación parcial (R-14).** No hace fracasar el proyecto; lo hace **lento**, y la lentitud en este esquema cuesta dinero de forma directa: escalonamiento del pago a Rosa, vencimiento de licencia, costo del capital, deterioro de lo construido.
5. **Un solo producto en mercado de rotación lenta (R-06, R-23).** Cinco casas prácticamente iguales, a un solo precio, en un submercado que absorbe pocas unidades al año. **No hay diversificación posible dentro del proyecto**; la única palanca es el precio, y bajarlo consume directamente la utilidad.

**Los cinco combinados producen el escenario que hay que evitar a toda costa:** obra iniciada con una sola venta, sobre predio ajeno, con mano de obra informal y socios sin tiempo, en un mercado que no absorbe. **La EDT está diseñada para que ese escenario sea imposible si se respetan los hitos G-1, G-3 y G-5.**

---

## E. CURVA DE INVERSIÓN Y MÁXIMA EXPOSICIÓN DE CAJA

> **Advertencia [RE]:** los porcentajes siguientes son **estructura típica de un proyecto de vivienda de esta escala**, aplicados al costo total estimado del acta ($1.815 millones). Son **≈ ORDEN DE MAGNITUD a validar** con el presupuesto real de 5.7. **La estructura de la curva —dónde está el pico— sí es robusta y no cambia con los números.**

### E.1 Distribución del gasto por fase

| Fase | Concepto | % del costo total | ≈ Valor sobre $1.815 M | Acumulado |
|---|---|---:|---:|---:|
| 1–3 | Gobierno, prefactibilidad y debida diligencia | **0,3%** | ≈ $5 M | 0,3% |
| 3.2 | Regularización del englobe *(si aplica)* | **0,5%** | ≈ $9 M | 0,8% |
| 4 | Estructuración jurídica y tributaria | **0,6%** | ≈ $11 M | 1,4% |
| 5 | Estudios técnicos y diseño | **2,5%** | ≈ $45 M | 3,9% |
| 6 | Servicios públicos y ambiental (trámites y conexiones) | **2,0%** | ≈ $36 M | 5,9% |
| 7 | Licencias, expensas e impuestos de trámite | **1,5%** | ≈ $27 M | 7,4% |
| — | **Pago del lote a Rosa** (escalonado, contra cada venta) | **20,1%** | ≈ $366 M (año 1) a $418 M (año 3) | — |
| 8 | Comercial: marca, renders, web, pauta, portales, material | **2,0%** | ≈ $36 M | — |
| 8 | Comisiones de venta (2–3%) | **2,5%** | ≈ $45 M | — |
| 9 | Preparación de obra, SST, pólizas, provisionales | **1,5%** | ≈ $27 M | — |
| 10 | **Obra: urbanismo, estructura, instalaciones, acabados** | **52,0%** | ≈ $944 M | — |
| 10 | Administración de obra e imprevistos | **6,0%** | ≈ $109 M | — |
| 11 | Titulación: PH, notaría, registro, folios | **1,5%** | ≈ $27 M | — |
| 12 | Escrituración, entrega, gastos notariales del vendedor | **1,5%** | ≈ $27 M | — |
| 13 | Provisión de posventa | **1,0%** | ≈ $18 M | — |
| 14 | Cierre, contabilidad y liquidación | **0,5%** | ≈ $9 M | — |
| — | **Honorarios de los socios por su rol** | **4,0%** | ≈ $73 M | — |
| — | **TOTAL** | **100%** | **≈ $1.815 M** | |

> **⚠ Nota importante:** en este cuadro **no está la provisión de impuesto de renta ni el ICA**, porque el acta tampoco los contempla. **No son costo del proyecto en sentido contable, pero sí salen de la caja y de la utilidad.** Ver 4.4 y R-11. Si la utilidad antes de impuestos es ≈$685 millones, la carga tributaria sobre ella —a tarifas de renta de personas naturales— **no es un renglón menor y hay que cuantificarlo con Lizeth antes de G-2**.

### E.2 Curva acumulada de egresos (% del costo total)

```
100% |                                                              ██████████
     |                                                        ██████
 90% |                                                  ██████
     |                                            ██████
 80% |                                      ██████
     |                                ██████
 70% |                          ██████
     |                     █████
 60% |                 ████
     |             ████
 50% |          ███
     |        ██
 40% |      ██
     |     ██
 30% |    ██
     |   ██
 20% |  ██
     | ██                          ← el pago del lote entra escalonado, contra cada venta
 10% | █
     |█
  0% +--------------------------------------------------------------------
      M1   M4   M7  M10  M13  M16  M19  M22  M25  M28  M31
      |         |         |              |              |
      G-1      G-4       G-5           1ª escritura    cierre
              (7,4%)   (~11%)          (~85%)
```

### E.3 Los tres momentos que importan

**1. Antes de G-5 (orden de inicio de obra) se ha gastado ≈ 11% del costo total (≈ $200 millones).**
Es lo que se pierde si el proyecto se aborta ahí. **Es mucho más de lo que el equipo tiene** ($40–50 millones): significa que **buena parte de ese 11% tiene que financiarse con recaudo de preventa o con aportes adicionales de los socios**. Este es el hueco de financiación que el modelo del acta no muestra.

**2. PUNTO DE MÁXIMA EXPOSICIÓN DE CAJA: entre el mes 19 y el mes 24.**

Es el momento en que coinciden:
- La obra en su pico de consumo (estructura terminada, instalaciones y acabados en curso simultáneamente): **acumulado de egresos ≈ 60–70%**.
- Ninguna escritura firmada todavía → **ningún desembolso de crédito hipotecario recibido**.
- Los ingresos acumulados son solo separaciones y cuotas iniciales: **≈ 35–45% del precio de las unidades vendidas**.
- Y los compromisos futuros ya están firmados (contratos de obra, promesas con fecha de entrega).

**La exposición máxima —lo que el proyecto debe y no ha cobrado— se alcanza ahí, y en un escenario de 2 unidades vendidas puede ubicarse en el orden de $250 a $400 millones ≈ ORDEN DE MAGNITUD, según cuántas unidades se estén construyendo simultáneamente.**

**[RE] De ahí sale la regla más importante de gestión financiera de este proyecto: no construir más unidades de las que el recaudo ya comprometido pueda terminar hasta obra gris.** Construir las 5 al tiempo multiplica la exposición sin acelerar las ventas.

**3. El alivio llega con la primera escritura (M24–M29), no con la primera venta (M13–M16).**
Entre la primera venta y la primera escritura pasan **10 a 14 meses** en los que el proyecto solo recibe cuotas parciales. **El equipo debe interiorizar esto: vender no es cobrar.**

### E.4 Colchón de caja (tema abierto N.° 5 del acta)

**[RE] Cómo calcularlo, ya que el acta lo dejó abierto:**

El colchón mínimo debe cubrir, en cualquier momento, **la suma de los compromisos de pago de los siguientes 60 días** menos el recaudo contractualmente exigible en ese mismo período, con un margen del 20%.

En la práctica, para este proyecto:
- **Colchón de arranque (antes de G-5):** el necesario para llevar **una unidad hasta obra gris sin recibir un peso más** ≈ **$120–180 millones ≈ ORDEN DE MAGNITUD a calcular con 5.7**. Eso, y no $40–50 millones, es el verdadero requisito de arranque.
- **Colchón operativo (durante obra):** dos meses de nómina de contratistas y compras comprometidas.

**Si el equipo no puede constituir ese colchón, las alternativas honestas son tres:** (a) construir una sola unidad primero y venderla terminada; (b) conseguir un socio capitalista o crédito; (c) reducir el alcance a 3 unidades. **Arrancar las 5 con $40–50 millones no es una de ellas.**

---

## F. LISTA DE VERIFICACIÓN PREVIA — LAS 15 PREGUNTAS

*Ordenadas por capacidad de matar el proyecto. Las siete primeras deben responderse **antes de gastar el primer peso significativo**. Si alguna se responde mal, el proyecto no debería seguir tal como está planteado.*

| # | Pregunta | Respuesta que MATA el proyecto | Dónde se responde | Subfase |
|---|---|---|---|---|
| **1** | **¿Existe un folio de matrícula inmobiliaria independiente para los 2.612 m² de Rosa, y ella figura como titular del derecho de dominio, sin gravámenes ni limitaciones?** | "No: el predio sigue englobado y Rosa es comunera junto con Pablo, Óscar y Marta" — y alguno de ellos no coopera | Certificado de tradición y libertad, ORIP de Duitama | 3.1 |
| **2** | **¿Cuántas viviendas permite el POT en ese predio (densidad máxima), y cuál es el índice de ocupación aplicable?** | "Menos de 5" o "el 70% del predio debe quedar en cobertura vegetal" | Secretaría de Planeación de Duitama y Curaduría Urbana, por escrito | 2.1 |
| **3** | **¿Hay disponibilidad de agua potable para 5 viviendas, certificada por un prestador con concesión vigente?** | "El acueducto veredal no tiene concesión vigente" o "no hay caudal para 5 suscriptores más" | Prestador del servicio + Corpoboyacá | 6.1 |
| **4** | **¿El predio tiene acceso jurídicamente asegurado —vía pública o servidumbre inscrita— y no un paso de hecho?** | "Es un paso de hecho por el lote del vecino" | Certificado de tradición + Planeación + escritura de servidumbre | 2.3.3 |
| **5** | **¿El predio está afectado por ronda hídrica, área de protección o amenaza que reduzca el área útil?** | "Sí, la faja de protección de la quebrada cruza el predio" | Corpoboyacá + POT | 3.5 |
| **6** | **¿Qué garantía real vamos a tener sobre el lote antes de gastar en licencias y obra, y estamos dispuestos a constituirla?** | "Ninguna; confiamos en el contrato privado" | Decisión interna + notaría + ORIP | 4.3 |
| **7** | **¿Con qué plata se llega desde hoy hasta la primera venta con recaudo (mes 13–16), sabiendo que en ese punto se habrá gastado ≈11% del costo total?** | "Con los $40–50 millones que tenemos" | Flujo de caja del proyecto | 1.3.4 / E.3 |
| **8** | **¿Cuál es la utilidad DESPUÉS de impuestos y DESPUÉS de remunerar el trabajo de los cuatro socios?** | "No la hemos calculado" o "menos del 15% sobre ventas" | Contadora (Lizeth) + presupuesto detallado | 4.4 / 5.7 |
| **9** | **¿Cuántas casas campestres de $400–600 millones se venden efectivamente al año en el área de influencia de Duitama?** | "Menos de 3 al año" → el horizonte de 12 meses es fantasía y el escalonamiento con Rosa se vuelve muy caro | Inmobiliarias de Duitama, Paipa, Tunja, Villa de Leyva | 2.4.4 |
| **10** | **¿El costo directo de $2.000.000/m² resiste una cotización real por capítulo, con la especificación descrita y el flete a 10 km?** | "No: está entre 15% y 30% por debajo" | Cotizaciones de proveedores y contratistas de Duitama | 5.7 |
| **11** | **¿Vamos a formalizar la mano de obra, y ese costo está en el presupuesto?** | "No; vamos con seguros individuales" → riesgo patrimonial personal del socio gestor | Decisión interna + ARL + contadora | 9.3 |
| **12** | **¿Bajo qué figura se titula: PH o loteo independiente, y la curaduría confirma que esa figura es viable en este predio?** | "Loteo", si la UAF o el área mínima de predio lo impiden | Curaduría Urbana de Duitama | 11.1 |
| **13** | **¿Sabemos qué trámite municipal habilita para recibir dinero del público, y cuánto tarda?** | "No sabíamos que existía" → se recibe plata sin habilitación y se comete una infracción | Secretaría de Gobierno / Planeación de Duitama | 8.2 |
| **14** | **¿Están definidos por escrito los honorarios de cada socio y el orden de aplicación de los recursos antes del reparto?** | "Eso lo arreglamos al final" | Acuerdo interno de los cuatro | 1.1.2 / 14.3.3 |
| **15** | **¿Quién dedica tiempo suficiente al proyecto en obra, y ese tiempo está pagado?** | "Nos turnamos como podamos" → el proyecto se hace lento y la lentitud cuesta plata directa | Decisión interna + presupuesto de residente de obra | 1.1.2 / R-14 |

**[RE] Cómo usar esta lista:** llévenla impresa a la próxima reunión, pongan una columna de "respuesta", una de "fuente" y una de "fecha", y **no permitan respuestas verbales ni supuestos**. Las preguntas 1, 2 y 3 se pueden responder en **dos semanas y por menos de $1 millón**. Es la mejor relación costo-beneficio de todo el proyecto.

---

## G. LO QUE FALTA — INFORMACIÓN A CONSEGUIR

*Esto es lo que este plan no puede darles y que convierte un documento genérico en el plan específico de este proyecto. Está ordenado por urgencia.*

### G.1 Urgente — esta semana

| # | Dato que falta | Dónde se consigue | Costo aprox. | Quién |
|---|---|---|---|---|
| 1 | **Certificado de tradición y libertad** del predio, y número de matrícula | ORIP de Duitama o ventanilla en línea de la Superintendencia de Notariado y Registro | < $25.000 | JUR |
| 2 | **Cédula catastral y boletín catastral**; estado del predial | Catastro / Secretaría de Hacienda de Duitama | Bajo | JUR / ADM |
| 3 | **Estado civil y régimen patrimonial de Rosa** | Registro civil / declaración | — | JUR |
| 4 | **Clasificación del suelo del predio en el POT** y número/fecha del acuerdo del POT vigente y sus modificaciones | Secretaría de Planeación de Duitama | Bajo | DAO |
| 5 | **Concepto de uso del suelo** | Secretaría de Planeación de Duitama | Bajo | DAO |
| 6 | Confirmación de que el **acceso** es vía pública o servidumbre inscrita | Certificado de tradición + Planeación | — | JUR |

### G.2 Muy pronto — próximas 4 semanas

| # | Dato que falta | Dónde se consigue | Quién |
|---|---|---|---|
| 7 | **Densidad máxima de vivienda, índice de ocupación e índice de construcción** aplicables; **área mínima de unidad**; **cesiones obligatorias**; aislamientos definitivos | Curaduría Urbana de Duitama (norma urbanística específica) y Secretaría de Planeación | DAO |
| 8 | Si aplica el **índice de ocupación del 30%** y el área de conservación de vegetación nativa en parcelación rural | Curaduría Urbana | DAO |
| 9 | **Qué licencias aplican** (parcelación / subdivisión / construcción / espacio público) y si se tramitan en serie o en paralelo | Curaduría Urbana | JUR |
| 10 | **Términos legales reales** del trámite de licencia y de sus prórrogas, y **liquidación estimada de expensas** | Curaduría Urbana de Duitama | JUR |
| 11 | Si en Duitama están adoptados el **efecto plusvalía** y el **impuesto de delineación urbana**, y sus tarifas | Secretaría de Hacienda de Duitama / Estatuto Tributario Municipal | JUR |
| 12 | **Determinantes ambientales**, ronda hídrica, densidad máxima en suelo rural y régimen de vertimientos aplicable | Corpoboyacá | JUR |
| 13 | **Disponibilidad de acueducto** y **concesión de aguas vigente del prestador** | Prestador (Pedro / acueducto veredal o empresa municipal) + Corpoboyacá | DAO |
| 14 | **Punto de conexión, disponibilidad y presupuesto de conexión de energía** | Operador de red que atiende la vereda | DAO |
| 15 | **Dependencia y requisitos de la radicación municipal para enajenación de inmuebles destinados a vivienda** | Secretaría de Gobierno / Planeación de Duitama | JUR |
| 16 | **Concepto tributario escrito** sobre: renta ordinaria vs. ganancia ocasional, esquema de dos titulares, tratamiento del pago a Rosa, obligación de facturar, ICA de Duitama, retenciones | **Lizeth (contadora)** | JUR / ADM |
| 17 | **Costo real de la formalización laboral** y clase de riesgo aplicable | ARL + contadora | ADM |

### G.3 Necesario antes de fijar precio (G-2)

| # | Dato que falta | Dónde se consigue | Quién |
|---|---|---|---|
| 18 | **Estudio de suelos** con capacidad portante, tipo de cimentación y prueba de percolación | Geotecnista | DAO |
| 19 | **Cotizaciones reales por capítulo** con proveedores de Duitama y Sogamoso, incluido el flete | Proveedores y contratistas locales | DAO / ADM |
| 20 | **Precios de cierre verificados** (no precios pedidos) de al menos 3 operaciones comparables en el área | Inmobiliarias, notarías, avaluador | COM |
| 21 | **Velocidad de absorción** del submercado de casas campestres $400–600 M | Inmobiliarias de Duitama, Paipa, Tunja, Villa de Leyva (Osvaldo Martínez) | COM |
| 22 | **Ficha completa del competidor de Surba/Bonza**: precio, especificación, tiempo en el mercado, unidades vendidas | Visita comercial | COM |
| 23 | **Verificación de la casa de reventa de Pantano de Vargas**: precio pedido vs. condiciones reales | Visita HI-5 + inmobiliaria | DAO / COM |
| 24 | **Cotización de honorarios**: calculista, eléctrico, hidrosanitario, topógrafo, abogado de PH | Profesionales locales | DAO / JUR |
| 25 | **Cotización de encargo fiduciario de preventa** | Fiduciarias | JUR |
| 26 | **Cotización de póliza decenal de estabilidad y de RCE** | Aseguradoras / corredor | JUR |
| 27 | **Números reales de camioneta vs. fletes** | Concesionarios, transportadores, John Martínez | ADM |

### G.4 Datos internos que solo el equipo puede definir

| # | Decisión pendiente | Referencia del acta |
|---|---|---|
| 28 | Honorario/tarifa de cada socio por su rol | Tema abierto N.° 5 |
| 29 | 5 casas iguales o 4 + 1 de 2 alcobas | Tema abierto N.° 1 (depende de HI-1, HI-2) |
| 30 | Precio final y franja de negociación | Tema abierto N.° 2 |
| 31 | Modelo de vinculación laboral | Tema abierto N.° 6 |
| 32 | Monto del colchón de caja y cuota inicial mínima | Tema abierto N.° 7 |
| 33 | Compra de camioneta | Tema abierto N.° 3 |
| 34 | Nombre definitivo | Tema abierto N.° 4 |
| 35 | **Cuánto está dispuesto a perder cada socio si el proyecto se detiene en G-1** | *No está en el acta y debería estar* |
| 36 | **Tarifa de alquiler del equipo de Hugo Ignacio** | HI-13 |
| 37 | **Quién es el residente de obra y cuánto se le paga** | *No está en el acta y es indispensable* |

### G.5 Lo que este documento NO puede darles

Con la franqueza que corresponde:

1. **El contenido exacto del POT de Duitama.** Es norma local. Todo lo que digo sobre densidad, ocupación, aislamientos y cesiones son **categorías correctas con valores desconocidos**. Los valores los da la curaduría y la Secretaría de Planeación, por escrito.
2. **Los términos y tarifas reales de los trámites en Duitama y en Corpoboyacá.** Los rangos que doy son de experiencia general; la realidad de cada entidad varía y cambia con la carga de trabajo y con los cambios de funcionarios.
3. **El texto vigente de las normas que cito.** La normativa colombiana se modifica con frecuencia; señalé la norma y el tema, pero **cada artículo debe verificarse en su versión vigente** con JUR y con la contadora antes de tomar una decisión basada en él.
4. **Las cifras tributarias.** Tarifas de renta, retenciones, ICA de Duitama y umbrales cambian por reformas. Todo lo tributario es **de Lizeth**, no mío.
5. **El precio al que realmente se venden las casas en La Trinidad.** Eso solo lo sabe quien haya cerrado operaciones ahí. Los portales muestran lo que la gente pide, no lo que recibe.

---

# CIERRE

Tres frases para llevarse:

1. **Antes de gastar un peso más en diseño, marca o renders, saquen el certificado de tradición y pregunten en Planeación cuántas viviendas permite el POT en ese lote.** Cuesta menos de un millón y define si hay proyecto.
2. **El punto de no retorno no es la licencia: es la orden de inicio de obra (G-5), y tiene ocho requisitos.** Ninguno es opcional.
3. **La utilidad de $685 millones del acta es antes de impuestos, antes de remunerar el trabajo de los cuatro socios, antes de la provisión de posventa y sin el sobrecosto del escalonamiento con Rosa si el proyecto se pasa del primer año.** Rehacer ese número con esas cuatro líneas es la tarea más importante antes de la próxima reunión.

---

*Documento de trabajo. No reemplaza la consulta a la Curaduría Urbana de Duitama, a la Secretaría de Planeación de Duitama, a Corpoboyacá ni a la contadora del proyecto. Su función es que esas conversaciones ocurran sabiendo qué preguntar.*
