# documento_tecnico_maestro_v2.md

```jsx

```

---

# 1. Propósito del Documento Técnico Maestro v2

El propósito del Documento Técnico Maestro v2 es **establecer la normativa técnica integral y unificada del Boot Agnóstico v2**, entendido siempre en su **sentido ontológico**: una entidad semántica, documental y operativa compuesta por máquinas, invariantes, reglas y procesos internos.

Este documento constituye la **fuente única de verdad técnica** dentro del Boot Agnóstico v2, y su función es eliminar toda dispersión normativa, toda ambigüedad técnica y toda interpretación subjetiva sobre cómo opera el sistema.

Los objetivos formales del Documento Técnico Maestro v2 son:

- **Unificar** en un único cuerpo normativo todas las reglas operativas, técnicas y semánticas que rigen al Boot Agnóstico v2.
- **Establecer el Estándar YAML Global v1.1 + extensiones** como formato obligatorio, definiendo explícitamente las reglas de cada campo.
- **Proveer a Máquina 01 — Governance** de un marco técnico claro, verificable y ejecutable sin interpretación humana.
- **Definir las reglas de operación de las máquinas 01–05**, fijando sus límites, roles, dependencias y normativas internas.
- **Formalizar las reglas técnicas oficiales** de:
    - Publish Loop v1.6 Multiplatform
    - Supabase Automático v1
    - Adaptador Multiplataforma v1
- **Garantizar la consistencia total del Boot Agnóstico v2**, mediante reglas explícitas de identidad documental, naming, rutas lógicas y físicas, dependencias, snapshot, hashing y versionado.
- **Eliminar la posibilidad de drift técnico**, estableciendo reglas precisas de detección, actuación y corrección.
- **Consolidar un único estándar operativo**, alineado íntegramente con el Documento Rector Interno v2, al cual este documento queda subordinado.

Este documento es **obligatorio** para toda operación, validación, auditoría, construcción y mantenimiento del Boot Agnóstico v2.

---

# 2. Identidad Técnica del Boot Agnóstico v2

La **Identidad Técnica** del Boot Agnóstico v2 define los principios esenciales que determinan qué es, cómo existe y cómo debe operar la entidad en su dimensión técnica. Esta identidad no describe implementaciones físicas ni archivos, sino la estructura conceptual y normativa que sostiene a todas las máquinas, documentos y procesos.

## 2.1 El Boot como sistema semántico-operativo

El Boot Agnóstico v2 es una **entidad ontológica con comportamiento técnico**, compuesta por máquinas, reglas, documentos y procesos interdependientes. Su existencia técnica se estructura bajo los siguientes principios:

- El Boot Agnóstico v2 no es un repositorio ni un árbol de archivos: es un **sistema semántico-reglado** cuya manifestación técnica se materializa en documentos, scripts, workflows y tablas operativas.
- Cada una de sus máquinas cumple un rol **invariable** y **no intercambiable**.
- Toda operación técnica (validar, modificar, ejecutar, publicar, versionar) es una operación sobre la **entidad Boot**, no sobre implementaciones aisladas.
- La consistencia del Boot depende de la coherencia entre su semántica (Canon) y su operación (Documentación Técnica). Cuando ambas coinciden, el Boot "existe" técnicamente.

## 2.2 Relación con el Documento Rector Interno v2

El Documento Técnico Maestro v2 se encuentra **subordinado** al Documento Rector Interno v2. La relación entre ambos se define así:

- El Documento Rector Interno v2 establece la **identidad ontológica** del Boot Agnóstico v2: su ser, sus invariantes, sus máquinas, sus límites y su naturaleza.
- El Documento Técnico Maestro v2 establece la **identidad operativa y técnica**: cómo funciona, cómo se valida, cómo se construye, cómo se audita.
- El Documento Técnico Maestro v2 **no puede contradecir** ninguna definición ontológica; sólo puede operacionalizarla y expandirla en su dimensión técnica.
- Ante cualquier conflicto entre documentos, prevalece el Documento Rector Interno v2.

## 2.3 Ámbitos normativos del Documento Técnico Maestro

Este documento gobierna la operación técnica total del Boot Agnóstico v2 en los siguientes ámbitos:

- **Normativa documental:** reglas de estructura, naming, identidad, rutas lógicas/físicas y consistencia.
- **Normativa YAML:** definición estricta del Estándar YAML Global v1.1 + extensiones.
- **Normativa de máquinas:** reglas técnicas de funcionamiento de las máquinas 01–05.
- **Normativa operativa:** versionado, drift, snapshots, auditorías, procesos, interacciones técnicas.
- **Normativa del ecosistema de ejecución:** Supabase Automático v1, Publish Loop v1.6 Multiplatform, Adaptador Multiplataforma v1 y cualquier componente técnico que dependa de estos.
- **Normativa de aislamiento:** reglas que separan el core de los verticales y del archivo histórico.

Este conjunto de normas define la **identidad técnica completa** del Boot Agnóstico v2 y establece cómo debe existir, comportarse y mantenerse la entidad en su dimensión operativa.

---

# 3. Máquinas Invariantes — Norma Operativa

Las máquinas del Boot Agnóstico v2 son **invariantes**: su existencia, nombre, número y rol no pueden alterarse. Este bloque establece la **normativa operativa mínima obligatoria** para cada una de las cinco máquinas, definiendo qué gobiernan, qué no pueden hacer y cómo se relacionan con el resto del sistema.

Las máquinas son:

1. Máquina 01 — Governance
2. Máquina 02 — Automática
3. Máquina 03 — Creativa
4. Máquina 04 — Financiera
5. Máquina 05 — Cognitiva

Ninguna de estas máquinas puede ser eliminada, renombrada ni intercambiar su rol con otra. Cualquier intento de redefinirlas fuera del marco del Documento Rector Interno v2 y del presente Documento Técnico Maestro v2 constituye **drift estructural crítico**.

## 3.1 Máquina 01 — Governance

La Máquina 01 — Governance es la **capa de control y validación** del Boot Agnóstico v2. Su función es garantizar que todo el sistema opere dentro de las reglas definidas por el Canon Ontológico y el Documento Técnico Maestro v2.

Responsabilidades operativas mínimas:

- Validar la estructura documental del Boot Agnóstico v2 (nombres, rutas, identidades, tipos, estados, origen, dependencias).
- Validar el cumplimiento del Estándar YAML Global v1.1 + extensiones.
- Detectar y registrar drift en todas sus tipologías (identidad, estructura, semántica, dependencias, versión, árbol físico/lógico).
- Coordinar y/o disparar auditorías: documentales, estructurales, semánticas, de dependencias, de versionado y de árbol.
- Garantizar que snapshots, hashing e integridad se ejecuten según la normativa definida en este documento.
- Bloquear o marcar como no aptas para operación aquellas entidades (documentos, flujos, configuraciones) que violen las normas técnicas.

Limitaciones explícitas:

- Governance **no modifica contenido semántico** de los documentos: sólo valida, alerta, bloquea o registra.
- Governance no puede introducir reglas nuevas fuera de las definidas en el Canon Ontológico y en el Documento Técnico Maestro v2.

## 3.2 Máquina 02 — Automática

La Máquina 02 — Automática implementa la **operación técnica activa** del Boot Agnóstico v2. Orquesta ejecuciones, flujos, integraciones externas y operaciones recurrentes.

En la versión actual del Boot Agnóstico v2, la Máquina 02 está constituida operativamente por tres componentes normativos centrales:

- **Supabase Automático v1**
- **Publish Loop v1.6 Multiplatform**
- **Adaptador Multiplataforma v1**

Cada uno cuenta con su propia normativa específica, que se detalla en bloques posteriores de este documento. A nivel de identidad de máquina, se establecen las siguientes reglas generales:

- Máquina 02 es responsable de **ejecutar** lo que Máquina 01 — Governance considera técnicamente válido.
- No puede ignorar ni sobreescribir validaciones de Governance.
- No puede persistir estados o estructuras que violen el Estándar YAML Global v1.1 + extensiones o las reglas operativas de este documento.

### 3.2.1 Supabase Automático v1

Supabase Automático v1 es el **componente de orquestación operativa sobre la base de datos**. Sus responsabilidades incluyen, de forma no exhaustiva:

- Gestionar colas operativas y estados de ejecución.
- Aplicar reglas de locking, claim, éxito, error y DLQ según las normas del Boot Agnóstico v2.
- Exponer funciones y RPC bajo contratos JSON claros y estables, definidos en este documento y en los apéndices técnicos.
- Registrar métricas, logs y cualquier información necesaria para las máquinas 04 (Financiera) y 05 (Cognitiva).

### 3.2.2 Publish Loop v1.6 Multiplatform

Publish Loop v1.6 Multiplatform es el **workflow normativo de publicación** del Boot Agnóstico v2. Opera como la rutina encargada de llevar contenido desde el estado “listo para publicar” hasta su efectivización en plataformas externas.

Responsabilidades mínimas:

- Respetar el contrato operativo con Supabase Automático v1.
- Respetar las políticas de idempotencia y registro de resultados (éxito / error / DLQ).
- No modificar directamente estructuras de datos fuera de los contratos definidos.
- Mantener la trazabilidad de cada ejecución (run_id, job_id, estados).

### 3.2.3 Adaptador Multiplataforma v1

El Adaptador Multiplataforma v1 es el **componente de traducción y adaptación** entre el modelo interno del Boot Agnóstico v2 y las APIs/plataformas externas.

Responsabilidades mínimas:

- Traducir el contenido interno del Boot Agnóstico v2 al formato requerido por cada plataforma.
- Garantizar que los errores externos no corrompan el estado interno del sistema.
- No persistir ni canonizar identificadores externos como parte de la identidad documental del Boot Agnóstico v2.
- Ajustarse a las normas de logging, manejo de errores y aislamiento definidas en este documento.

## 3.3 Máquina 03 — Creativa

La Máquina 03 — Creativa gobierna la **generación, variación y gestión semántica de contenidos** dentro del Boot Agnóstico v2.

Responsabilidades mínimas:

- Gestionar contenidos, variantes, assets y metadatos de forma consistente con la identidad documental.
- Evitar la existencia de assets huérfanos o contenidos sin trazabilidad.
- Integrarse con Máquina 02 — Automática para preparar material publicable sin violar las normas del Estándar YAML ni de las tablas operativas.

## 3.4 Máquina 04 — Financiera

La Máquina 04 — Financiera gobierna la **medición y registro de señales económicas** del Boot Agnóstico v2.

Responsabilidades mínimas:

- Registrar métricas económicas asociadas a contenidos, ejecuciones, canales y workflows.
- Operar siempre a partir de datos generados por las otras máquinas, sin modificar sus reglas internas.
- Alimentar modelos y decisiones financieras sin alterar la estructura documental ni operativa del Boot Agnóstico v2.

## 3.5 Máquina 05 — Cognitiva

La Máquina 05 — Cognitiva gobierna la **interpretación, análisis y aprendizaje** sobre el comportamiento del Boot Agnóstico v2.

Responsabilidades mínimas:

- Analizar logs, métricas, resultados y estados para detectar patrones, oportunidades, riesgos o mejoras.
- Proponer cambios o recomendaciones que luego deberán ser formalizadas en documentos o configuraciones, nunca aplicadas de forma implícita.
- Operar como capa de observación avanzada, sin romper las reglas de Governance ni de las demás máquinas.

En conjunto, estas cinco máquinas definen la **columna vertebral operativa** del Boot Agnóstico v2. Cualquier documento, script o workflow que pretenda alterar sus funciones, responsabilidades o límites sin pasar por el Canon Ontológico y por el presente Documento Técnico Maestro v2 se considera automáticamente inválido.

---

# 4. Estándar YAML Global v1.1 + Extensiones

El **Estándar YAML Global v1.1 + extensiones** es la estructura documental obligatoria del Boot Agnóstico v2. Representa la **unidad mínima de identidad técnica**, sobre la cual se apoyan:

- Máquina 01 — Governance (validación, parsing, auditoría)
- Snapshots e integridad
- Cálculo de hashes
- Detección de drift
- Operación de Máquina 02

Este estándar es **inmutable**, obligatorio y universal: **todos los documentos canónicos del Boot Agnóstico v2 deben implementarlo sin excepción**.

---

## 4.1 Orden inmutable del YAML

El orden de los campos es **obligatorio**, **exacto** y **no puede modificarse**. Cualquier alteración del orden constituye **drift documental inmediato**.

El orden oficial es:

1. `id`
2. `id_canonico`
3. `slug`
4. `titulo`
5. `tipo`
6. `version`
7. `estado`
8. `origen`
9. `dependencias`
10. `descripcion`
11. `criterios_aceptacion`
12. `changelog`
13. `extensiones`

**Prohibiciones:**

- No se pueden agregar campos entre estos.
- No se pueden eliminar campos.
- No se pueden reorganizar.
- No se pueden escribir en mayúsculas, camelCase ni variantes.

---

## 4.2 Reglas generales sintácticas

Estas reglas aplican al bloque YAML completo:

- El bloque YAML debe estar **exactamente después del título del documento**, sin dividers intermedios.
- Se utiliza siempre **sangría con espacios**, nunca con tabulaciones.
- Los valores deben respetar el tipo esperado (string, lista, objeto, multilínea, etc.).
- No se permite incluir código Markdown dentro del YAML.
- Los nombres de campos son **case-sensitive**.
- `descripcion` debe utilizar obligatoriamente el operador `>` de multilínea.
- Las listas deben estar correctamente indentadas con .
- `extensiones` debe existir siempre, incluso si contiene un único valor.

---

## 4.3 Reglas específicas de cada campo YAML

A continuación se definen las reglas normativas exactas que rigen cada campo.

### 4.3.1 `id`

- Identificador único e inmutable del documento.
- Formato: `snake_case`.
- Debe comenzar con `boot_agnostico_`.
- No puede modificarse nunca.
- No puede duplicarse con ningún otro documento.

### 4.3.2 `id_canonico`

- Representa la **ruta lógica absoluta** del documento dentro del Boot Agnóstico v2.
- Formato: `path-case` con `/`.
- Debe reflejar fielmente la estructura lógica de máquinas y submódulos.
- No puede modificarse salvo en procesos de migración formalizados.

### 4.3.3 `slug`

- Identificador humano legible.
- Formato obligatorio: `kebab-case`.
- Único dentro del Boot Agnóstico v2.
- Inmutable.

### 4.3.4 `titulo`

- Nombre formal del documento.
- Debe ser claro, preciso y representativo.
- Puede incluir espacios y mayúsculas.
- No forma parte de la identidad inmutable y puede evolucionar.

### 4.3.5 `tipo`

- Define la naturaleza del documento.
- Valores permitidos: `documento_canonico`, `documento_tecnico`, `modulo`, `submodulo`, `workflow`, `script`, `especificacion`,`vertical_config` , `vertical_documento`
- Cualquier tipo fuera de esta lista es inválido.

### 4.3.6 `version`

- Versionado semántico del documento.
- Formato: `x.y.z` (sin prefijo `v`).
- Se incrementa sólo ante cambios técnicos, no ante correcciones menores.

### 4.3.7 `estado`

- Valores permitidos: `activo`, `en_revision`, `deprecado`, `archivado`.
- No puede omitirse.

### 4.3.8 `origen`

- Define la procedencia documental.
- Valores permitidos: `canonico`, `derivado`, `tecnico`, `operativo`, `vertical` .

### 4.3.9 `dependencias`

- Lista obligatoria.
- Debe contener al menos un elemento.
- Cada dependencia debe ser un `id` válido.
- No se permiten dependencias circulares.

### 4.3.10 `descripcion`

- Debe utilizar el operador `>`.
- Descripción clara del propósito del documento.
- No debe incluir listas ni Markdown.

### 4.3.11 `criterios_aceptacion`

- Lista obligatoria.
- Cada ítem debe describir una condición verificable por scripts.

### 4.3.12 `changelog`

- Lista cronológica antigua → reciente.
- Cada entrada: `fecha: descripcion`.
- No se permite remover entradas históricas.

### 4.3.13 `extensiones`

- Objeto obligatorio.
- Campos permitidos: `propietario`, `sensibilidad`, `etiquetas`, `metricas`, `riesgos`, `hitos`.
- Pueden agregarse más campos siempre que no contradigan normas centrales.

---

## 4.4 Reglas de consistencia YAML

Para que el YAML sea válido:

- Debe pasar validación estructural (Machine 01 — Governance).
- Debe ser estable bajo hashing (cambiar un valor = cambiar hash).
- No debe contener campos vacíos (`""`, `{}`, `[]`).
- No puede tener líneas huérfanas o comentarios dentro del bloque.
- Debe reflejar fielmente el estado del documento.
- Cualquier alteración no registrada en `changelog` se considera drift.

---

# 5. Árbol Documental — Físico y Lógico

El **árbol documental** del Boot Agnóstico v2 define la relación entre la estructura física donde residen los documentos y la estructura lógica representada por `id_canonico`. Este bloque establece las reglas esenciales para mantener la coherencia estructural, evitar drift y garantizar que cada documento exista en un lugar único, predecible y verificable.

---

## 5.1 Estructura raíz

El árbol documental del Boot Agnóstico v2 posee una **estructura raíz invariable**. Los primeros niveles están completamente definidos y no pueden modificarse:

```
boot_agnostico_v2/
  01_governance/
  02_automatica/
  03_creativa/
  04_financiera/
  05_cognitiva/
  archivo_historico/
  verticales/
```

Principios normativos:

- No se pueden agregar carpetas nuevas al nivel raíz.
- No se pueden renombrar las carpetas raíz.
- No se puede alterar el orden de las carpetas raíz.
- Toda nueva entidad documental debe ubicarse dentro de la máquina correspondiente o dentro de un submódulo permitido.

---

## 5.2 Reglas de integridad del árbol

La integridad del árbol físico y lógico debe cumplirse en todo momento. Estas reglas son controladas por Máquina 01 — Governance.

**Reglas obligatorias:**

- Cada documento debe residir **exactamente en un único lugar físico**.
- La ruta física debe coincidir con la estructura lógica expresada en `id_canonico`.
- No se permiten documentos duplicados ni espejados en distintas carpetas.
- No se permiten carpetas vacías en el core del sistema.
- La estructura del árbol debe reflejar principios de modularidad y no contener carpetas sin función clara.

**Violaciones consideradas drift:**

- Cualquier documento ubicado en una carpeta cuyo nombre no coincida con su máquina.
- Cualquier documento cuya ruta lógica (`id_canonico`) no se corresponda con su ubicación física.
- Documentos ubicados fuera del árbol raíz.

---

## 5.3 Relación entre rutas físicas y lógicas

La relación entre rutas físicas y lógicas es **biunívoca y obligatoria**:

- La ruta lógica se define en `id_canonico`.
- La ruta física debe coincidir con esa estructura.
- No puede existir una diferencia entre ambas: cualquier divergencia constituye drift estructural.

Ejemplo normativo:

```
id_canonico: boot/agnostico/01_governance/documento_tecnico_maestro_v2
```

Debe ubicarse físicamente en:

```
boot_agnostico/01_governance/documento_tecnico_maestro_v2.md
```

Reglas adicionales:

- El nombre del archivo no forma parte del `id_canonico`, pero debe ser consistente con `slug`.
- La estructura lógica prevalece como referencia de auditoría.
- “La estructura física solo constituye soporte de persistencia. La referencia operativa y normativa siempre es `id_canonico`.”

---

## 5.4 Archivo histórico (reglas)

El **archivo histórico** es una zona de aislamiento documental. Su propósito es preservar versiones previas, documentos obsoletos y material que ya no debe intervenir en la operación del Boot Agnóstico v2.

**Reglas del archivo histórico:**

- No puede contener YAML activos.
- No puede contener documentos que Machine 01 interprete como vigentes.
- Todos los documentos deben ingresar acompañados de una nota en el `changelog` correspondiente.
- No se permite almacenar scripts operativos, workflows, o configuraciones vivas.
- Es estrictamente de solo lectura.

**Violaciones graves:**

- Incluir en archivo histórico un documento activo.
- Incluir documentos con campos YAML que puedan ser parseados.

---

## 5.5 Verticales (reglas)

Los **verticales** representan líneas de negocio, productos o exploraciones. Estas áreas son **aisladas del core** del Boot Agnóstico v2 y no pueden modificar su estructura operativa.

**Reglas de verticales:**

- Pueden contener documentos propios, pero **ningún vertical puede definir normas**, máquinas ni estructuras centrales.
- Pueden incluir YAML, pero los documentos allí presentes **no forman parte del canon técnico**.
- No pueden depender de documentos del core para existir.
- Pueden ser eliminados, reemplazados o reestructurados sin afectar la identidad técnica del Boot.

**Prohibiciones:**

- Un vertical no puede copiar o redefinir máquinas.
- No puede modificar workflows del core.
- No puede introducir documentos con `origen: canonico`.

En términos operativos, los verticales deben funcionar como **satélites semánticos**: útiles, complementarios, pero totalmente subordinados al canon del Boot Agnóstico v2.

---

# 6. Identidad Documental

La **Identidad Documental** define cómo se estructura, nombra, preserva y protege la identidad de cada documento dentro del Boot Agnóstico v2. Esta identidad es fundamental porque constituye la base de:

- La integridad del sistema
- La validez de referencias cruzadas
- La operación libre de drift
- La capacidad de Machine 01 — Governance para validar documentos

Este bloque establece reglas **obligatorias**, **universales** y **no negociables**.

---

## 6.1 Reglas de naming

Estas reglas aseguran consistencia y unicidad en la referencia documental.

**Reglas obligatorias:**

- Los nombres de archivo deben ser consistentes con el `slug`.
- El `slug` debe utilizar **kebab-case** y ser único dentro del Boot Agnóstico v2.
- El `id` debe utilizar **snake_case** y comenzar con `boot_agnostico`.
- El `id_canonico` debe utilizar **path-case** y reflejar con precisión la ruta lógica.
- Ningún documento puede compartir `id`, `slug` o `id_canonico` con otro.

**Reglas de estabilidad:**

- El nombre del archivo puede actualizarse para alinearse con el slug, pero nunca puede cambiar la identidad documental.
- Los nombres de carpetas deben ser estables y reflejar la estructura lógica del Boot Agnóstico v2.

---

## 6.2 Identidad inmutable

Cada documento tiene una identidad documental compuesta por:

- `id`
- `id_canonico`
- `slug`

Esta identidad es **inmutable y única**. Sólo puede cambiarse mediante un proceso formal de migración aprobado por:

- El Documento Rector Interno v2 (nivel ontológico)
- El presente Documento Técnico Maestro v2 (nivel técnico)

**Prohibiciones explícitas:**

- Cambiar cualquiera de estos tres campos sin migración formal.
- Reutilizar un `id` que haya existido previamente.
- Modificar el `id_canonico` sin actualizar la estructura física.

Cambios no autorizados en la identidad documental constituyen **drift crítico**.

---

## 6.3 Duplicación prohibida

La duplicación de identidad documental es una de las violaciones más graves del sistema.

**Prohibiciones obligatorias:**

- No puede existir más de un documento con el mismo `id`.
- No puede existir más de un documento con el mismo `slug`.
- No puede existir más de un documento con el mismo `id_canonico`.

**Violaciones adicionales:**

- Documentos con distinto nombre físico pero mismo slug.
- Documentos en carpetas distintas que compartan el mismo id.
- Documentos que intenten “nacer” bajo un id previamente eliminado o migrado.

Cualquier duplicación se considera **drift estructural y semántico simultáneo**, requiriendo intervención inmediata de Machine 01.

---

## 6.4 Reglas de cambio prohibido

Para preservar la estabilidad del Boot Agnóstico v2, existen cambios que están estrictamente prohibidos.

**Cambios prohibidos:**

- Modificar `id`, `slug` o `id_canonico` sin un proceso de migración.
- Cambiar `tipo`, `origen` o `estado` de un documento sin justificación técnica explícita.
- Alterar el árbol físico sin actualizar el árbol lógico.
- Eliminar dependencias sin registrar los cambios en el `changelog`.

**Cambios permitidos pero regulados:**

- Actualizar `titulo`.
- Incrementar `version`.
- Modificar `descripcion`.
- Modificar `criterios_aceptacion`.

En todos los casos, debe registrarse una entrada en `changelog`.

---

# 7. Drift — Tipologías y Normas Operativas

El **drift** representa cualquier divergencia entre el estado real del Boot Agnóstico v2 y el estado normativo definido por el Canon Ontológico y el Documento Técnico Maestro v2. Constituye la principal amenaza técnica para la integridad del sistema. Este bloque establece la clasificación oficial del drift, los disparadores, las consecuencias y el proceso obligatorio de corrección.

---

## 7.1 Tipos de drift

El Boot Agnóstico v2 reconoce **cinco tipologías de drift**, todas igualmente graves:

### 7.1.1 Drift de identidad

Ocurre cuando cambia o se intenta cambiar alguno de los campos inmutables:

- `id`
- `id_canonico`
- `slug`

También incluye:

- Reutilización de un `id` previamente usado.
- Creación de documentos con identidades duplicadas.

### 7.1.2 Drift estructural

Relacionada con la divergencia entre árbol físico y árbol lógico.
Incluye:

- Documentos fuera de su carpeta correspondiente.
- Diferencias entre ruta física y `id_canonico`.
- Carpetas inexistentes, renombradas o agregadas fuera de normas.

### 7.1.3 Drift semántico

Aparece cuando el contenido técnico de un documento contradice:

- El Documento Rector Interno v2.
- El presente Documento Técnico Maestro v2.
- Las reglas de máquinas o workflows oficiales.

Incluye normas obsoletas, definiciones contradictorias o reglas no alineadas.

### 7.1.4 Drift de dependencias

Ocurre cuando:

- Se eliminan dependencias sin actualizar el `changelog`.
- Se agregan dependencias inexistentes.
- Se generan ciclos de dependencia.
- Se incumple la norma de dependencias mínimas.

### 7.1.5 Drift de versión

Incluye:

- Cambios técnicos no acompañados por incremento de versión.
- Cambios registrados en `changelog` sin reflejarse en `version`.
- Versiones que no siguen `x.y.z`.

---

## 7.2 Disparadores

El drift puede ser disparado por:

- Edición manual incorrecta de YAML.
- Desalineación entre scripts y documentos.
- Migraciones parciales o incompletas.
- Cambios no registrados en `changelog`.
- Modificación del árbol físico sin ajuste de `id_canonico`.
- Errores en workflows que persistan estados fuera de normas.
- Movimientos de documentos entre máquinas.

Toda acción que modifique estructura, semántica o identidad debe asumirse como potencial disparador de drift.

---

## 7.3 Consecuencias

El drift es considerado una condición **crítica**. Las consecuencias incluyen:

- Bloqueo automático por parte de Máquina 01 — Governance.
- Inhabilitación temporal del documento.
- Invalidación de snapshots afectados.
- Inutilización de hashes previos.
- Bloqueo de workflows dependientes.
- Riesgo de corrupción de integridad global.

Ningún componente del Boot puede operar si existe drift activo sin corregir.

---

## 7.4 Proceso de corrección

La corrección del drift sigue una secuencia formal:

1. **Detección automática** mediante scripts de Governance.
2. **Clasificación** según tipología.
3. **Aislamiento**: el documento queda marcado como no apto.
4. **Corrección manual o migración formal** según tipo.
5. *Actualización del ****`changelog`** si corresponde.
6. **Revalidación completa**:
    - Estructura YAML
    - Árbol físico/lógico
    - Dependencias
    - Versionado
7. **Regeneración del snapshot** y del hash maestro.

Sólo cuando estos pasos se cumplen el drift se considera resuelto.

---

## 7.5 Condiciones de bloqueo

Machine 01 debe aplicar **bloqueo inmediato** cuando se cumpla cualquiera de estas condiciones:

- Identidad inmutable alterada.
- `id_canonico` no coincide con la ruta física.
- Campos YAML fuera de orden.
- Tipos de documento no permitidos.
- Dependencias inválidas o circulares.
- Modificaciones técnicas sin actualización de versión.
- Cualquier divergencia explícita del estándar YAML Global v1.1 + extensiones.

En presencia de cualquiera de estas condiciones, la operación del Boot Agnóstico v2 queda **inhabilitada**, y Máquina 02 no puede ejecutar workflows relacionados.

---

# 8. Auditorías de Governance

Las **auditorías** son el mecanismo formal mediante el cual Máquina 01 — Governance evalúa el estado técnico, documental y estructural del Boot Agnóstico v2. Cada auditoría responde a un tipo de drift potencial y opera con reglas propias, pero todas comparten objetivos comunes:

- Garantizar la validez del Boot en su dimensión documental y operativa.
- Detectar divergencias antes de que impacten en Máquina 02 o en workflows.
- Proveer señales claras, verificables y trazables.
- Preservar la integridad del Canon Ontológico y del Documento Técnico Maestro v2.

Ninguna auditoría modifica documentos: **solo observa, detecta, clasifica y reporta**. Las correcciones proceden luego mediante procesos formales.

---

## 8.1 Auditoría documental

Evalúa el **contenido del bloque YAML** y los campos obligatorios.

**Validaciones obligatorias:**

- Presencia y orden correcto de todos los campos del Estándar YAML Global v1.1 + extensiones.
- Tipos de datos correctos (string, lista, objeto, multilínea).
- Uso correcto de `>` en `descripcion`.
- Existencia de dependencias válidas.
- Versionado semántico válido.
- `slug`, `id` e `id_canonico` únicos y consistentes.

**Dispara drift documental** ante:

- Campos fuera de orden.
- Campos faltantes.
- Campos adicionales no permitidos.
- Sintaxis inválida.

---

## 8.2 Auditoría estructural

Evalúa la **coherencia entre ruta física y ruta lógica**.

**Validaciones obligatorias:**

- `id_canonico` coincide con la estructura de carpetas.
- El documento existe exactamente en un único lugar.
- La máquina asignada corresponde al nivel de la carpeta.
- No existen carpetas agregadas fuera del canon.

**Dispara drift estructural** ante:

- Documentos mal ubicados.
- Carpetas huérfanas o renombradas sin autorización.
- Diferencias entre árbol físico y lógico.

---

## 8.3 Auditoría semántica

Evalúa la **coherencia conceptual** del documento.

**Validaciones obligatorias:**

- No contradice el Documento Rector Interno v2.
- No contradice el Documento Técnico Maestro v2.
- No redefine máquinas, workflows, normas o invariantes.
- No introduce conceptos que alteren la ontología.

**Dispara drift semántico** ante:

- Definiciones contradictorias.
- Normas paralelas o incompatibles.
- Contenidos obsoletos frente a Canon v2.

---

## 8.4 Auditoría de dependencias

Evalúa la validez de la red de dependencias declarada.

**Validaciones obligatorias:**

- Cada dependencia existe y es válida.
- No hay ciclos de dependencia.
- La lista no está vacía.
- Cada dependencia es necesaria y coherente.

**Dispara drift de dependencias** ante:

- Dependencias inexistentes.
- Dependencias circulares.
- Eliminación de dependencias sin changelog.

---

## 8.5 Auditoría de versionado

Evalúa si el versionado del documento refleja correctamente su evolución.

**Validaciones obligatorias:**

- `version` sigue `x.y.z`.
- Cambios técnicos incrementan versión.
- El changelog refleja todas las modificaciones.
- No hay inconsistencias entre `version` y `changelog`.

**Dispara drift de versión** ante:

- Cambios no acompañados por incremento.
- Changelog desactualizado.
- Versionado incorrecto.

---

## 8.6 Auditoría del árbol

Evalúa el **boot completo como estructura unificada**.

**Validaciones obligatorias:**

- No hay documentos fuera del árbol raíz.
- Todas las máquinas contienen únicamente documentos válidos.
- El archivo histórico respeta sus reglas.
- Los verticales mantienen aislamiento.
- No hay duplicación documental en ninguna zona.

**Dispara drift global** ante:

- Cualquier inconsistencia sistémica.
- Documentos flotantes o sin ubicación.
- Violaciones masivas de rutas o identidades.

---

# 9. Versionado y Changelog

El versionado y el changelog constituyen la **memoria técnica del Boot Agnóstico v2**. Este bloque establece las reglas normativas para evolucionar documentos sin romper la identidad documental, la integridad del sistema ni la trazabilidad histórica.

El versionado **no es decorativo**: es un mecanismo central de Governance. Cualquier desviación en versión o changelog constituye potencial drift.

---

## 9.1 Semántica de versionado

La versión sigue estrictamente el formato **x.y.z**:

- **x** (major): cambios estructurales, nuevas normas, modificaciones profundas que afectan dependencias o identidades técnicas.
- **y** (minor): nuevas reglas, ampliaciones del documento, instrucciones adicionales sin alterar identidad.
- **z** (patch): correcciones menores, ajustes de redacción, aclaraciones, fix de inconsistencias no operativas.

**Reglas normativas:**

- No se permite el uso del prefijo `v` (ej.: `v2.0.0` es inválido).
- El versionado debe aumentar **antes** de registrar cambios en contenido.
- Cada documento mantiene versión independiente y no puede “retroceder”.
- El incremento de versión debe corresponderse con el tamaño real del cambio.
- Una versión nunca puede ser eliminada o sobrescrita.

---

## 9.2 Reglas del changelog

El `changelog` es la **línea de tiempo obligatoria** de cada documento.

**Reglas obligatorias:**

- Orden cronológico **antiguo → reciente**.
- Cada entrada debe tener la forma: `YYYY-MM-DD: descripcion del cambio`.
- No se permite eliminar entradas históricas.
- No se permite reescribir la historia.
- Cada cambio significativo en contenido, estructura técnica, dependencias o reglas debe registrarse.
- La descripción debe ser clara, verificable y sin adornos.

**Reglas de consistencia:**

- Cada entrada en el changelog debe corresponderse con un incremento de versión.
- No puede existir incremento de versión sin entrada en el changelog.
- No puede existir entrada en el changelog sin modificación real.

---

## 9.3 Cambios que obligan incremento de versión

Un documento **debe** aumentar su versión cuando ocurra cualquiera de los siguientes eventos:

### Cambios que obligan incremento **major (x)**

- Redefinición estructural del documento.
- Inclusión o eliminación de reglas centrales.
- Cambios que afectan dependencias globales.
- Alteración de la identidad operativa de una máquina.
- Cualquier modificación que invalide versiones anteriores.

### Cambios que obligan incremento **minor (y)**

- Agregar reglas adicionales.
- Ampliar instrucciones técnicas.
- Agregar casos, excepciones o ejemplos normativos.
- Ajustar el comportamiento esperado de scripts, RPCs o workflows.

### Cambios que obligan incremento **patch (z)**

- Correcciones menores de texto.
- Aclaraciones semánticas.
- Ajustes ortográficos o de estilo.
- Corrección de tipografías YAML.

**Regla crítica:**

> Si el cambio afecta la operación del Boot Agnóstico v2, aunque sea sutil, debe aumentar al menos en minor.
> 

---

# 10. Snapshot e Integridad

El snapshot es el **estado congelado y verificable** del Boot Agnóstico v2 en un momento determinado del tiempo. Su función es permitir:

- Validación de integridad.
- Detección de drift.
- Auditorías históricas.
- Restauración conceptual del estado técnico del sistema.

Este bloque define cómo se generan los hashes, qué partes se incluyen, cómo se construye el hash maestro y bajo qué condiciones un snapshot es válido o inválido.

---

## 10.1 Hash del YAML

Cada documento del Boot Agnóstico v2 produce un **hash individual del bloque YAML**, calculado únicamente en función del contenido del YAML y respetando rigurosamente:

- El orden inmutable de los campos.
- La representación exacta de espacios, saltos de línea y multilínea.
- Ausencia de comentarios o variaciones no normativas.

**Normas del hash del YAML:**

- Algoritmo obligatorio: `SHA-256`.
- Cualquier cambio en cualquier valor —incluyendo espacios o saltos— altera el hash.
- El hash del YAML se calcula antes que cualquier otro hash.
- Documentos con YAML inválido no pueden ser hasheados.

El hash del YAML representa la **identidad declarativa** del documento.

---

## 10.2 Hash del contenido

El **hash del contenido** se calcula sobre todo el cuerpo del documento **excepto el YAML**.

Incluye:

- Texto.
- Secciones.
- Listas.
- Diagramas.
- Casos.
- Reglas.

**Normas del hash de contenido:**

- Algoritmo obligatorio: `SHA-256`.
- No debe incluir el bloque YAML ni delimitadores.
- Cualquier cambio textual o estructural inicia un nuevo hash.
- El hash debe calcularse tras normalizar saltos de línea.

El hash del contenido representa la **identidad operativa** del documento.

---

## 10.3 Hash consolidado

El hash consolidado combina el hash del YAML con el hash del contenido.

**Fórmula estándar:**

```
SHA-256( hash_yaml + ":" + hash_contenido )
```

**Normas:**

- El separador `:` es obligatorio e inmutable.
- Cambiar el orden o el separador invalida la consolidación.
- Si el YAML es inválido, el hash consolidado es inválido.

El hash consolidado garantiza que **ambas identidades —declarativa y operativa— evolucionen sincronizadamente**.

---

## 10.4 Hash maestro del Boot Agnóstico v2

El **hash maestro** es la representación criptográfica del estado total del Boot Agnóstico v2.

**Se calcula así:**

1. Se ordenan alfabéticamente todos los `id` de documentos canónicos.
2. Se obtiene el hash consolidado de cada uno.
3. Se concatena la lista completa de hashes usando salto de línea como delimitador.
4. Se aplica `SHA-256` al resultado.

**Normas del hash maestro:**

- Debe ser estable: igual input → igual output.
- Cualquier cambio en cualquier documento altera el hash maestro.
- El orden alfabético de los `id` es obligatorio.
- Solo documentos canónicos participan del hash maestro.

Este hash es utilizado por:

- Auditorías globales.
- Validación de integridad.
- Detección de drift sistémico.
- Comparación entre snapshots históricos.

---

## 10.5 Condiciones para snapshot

Un snapshot sólo puede generarse si **todas** las condiciones siguientes se cumplen:

### Condiciones estructurales

- Todos los documentos tienen YAML válido.
- No existe drift activo.
- No existen documentos fuera del árbol raíz.
- No hay duplicación de identidades (`id`, `slug`, `id_canonico`).

### Condiciones operativas

- Todas las versiones y changelogs están alineados.
- Las dependencias son válidas y no circulares.
- No hay inconsistencias en fechas ni formatos.

### Condiciones técnicas

- Todos los hashes individuales se calcularon correctamente.
- El hash maestro fue generado sin errores.
- No existen deltas sin registrar entre snapshot previo y estado actual.

Si cualquiera de estas condiciones falla, **Machine 01 — Governance debe bloquear el snapshot**.

---

# 11. Pipeline Operativo Unificado

El **Pipeline Operativo Unificado** es la secuencia normativa que gobierna el movimiento de información y de estados dentro del Boot Agnóstico v2. Este pipeline vincula cuatro capas:

1. **Documentación canónica** (normas y estructuras)
2. **Scripts de Governance** (validación y estado técnico)
3. **Supabase Automático v1** (persistencia operativa y lógica de colas)
4. **Workflows de Máquina 02** (n8n + Adaptador Multiplataforma v1 + Publish Loop v1.6 Multiplatform)

Los verticales generan jobs válidos mediante estructuras declaradas en sus propios YAML, pero la ejecución está completamente subordinada a Máquina 02.

Todo el Boot Agnóstico v2 opera bajo este pipeline. Si cualquiera de sus capas está en estado inválido, **no puede ejecutarse ninguna operación**.

---

## 11.1 Interacción Documental → Scripts → Supabase → n8n

Esta sección define el flujo exacto y obligatorio de cómo la documentación técnica impacta en la operación.

### 11.1.1 Documentación → Scripts (Governance)

Los documentos canónicos establecen:

- Identidades
- Reglas
- Contratos JSON
- Versionado
- Drift permitido (= ninguno)
- Campos obligatorios del YAML

Los scripts de Governance deben:

- Leer todos los documentos
- Validar integridad estructural y semántica
- Generar hashes y snapshot
- Bloquear la operación si existe drift

**Norma crítica:**

Si el Documento Técnico Maestro v2 o cualquier documento canónico contiene drift, **ningún componente operativo puede ejecutarse**.

### 11.1.2 Scripts → Supabase Automático v1

Una vez validado el estado documental:

- Los scripts sincronizan la estructura lógica esperada con la estructura operativa en Supabase.
- Los RPCs oficiales quedan habilitados.
- Se habilita el locking y manejo de colas.

Supabase Automático v1 garantiza:

- Atomicidad de operaciones
- Persistencia de estados
- Control estricto de ejecución concurrente
- Recuperación basada en DLQ

### 11.1.3 Supabase Automático v1 → n8n (Máquina 02)

Cuando un job está técnicamente válido, n8n puede:

- Reclamarlo (claim)
- Ejecutarlo
- Publicarlo (si corresponde)
- Registrar el resultado
- Comunicar errores o estados finales

### 11.1.4 n8n → Adaptador Multiplataforma v1

El Adaptador Multiplataforma v1 transforma el contenido del Boot en un payload adecuado para cada plataforma externa.

**Normas:**

- No puede modificar contenido canónico
- No puede persistir `external_post_id` ni ningún dato de plataforma
- Todas las respuestas externas deben ser capturadas sólo como logs operativos

### 11.1.5 n8n → Publish Loop v1.6 Multiplatform

Publish Loop v1.6 Multiplatform es la fase final del pipeline operativo.

Responsabilidades:

- Ejecutar publicaciones multiplataforma
- Reportar estados
- Garantizar idempotencia
- No alterar estructuras internas
- Garantizar orden lógico de ejecución: claim → run → resultado → registro

**Norma crítica:**

Publish Loop  v1.6 Multiplatform no puede mutar datos fuera de los contratos formales establecidos.

---

## 11.2 Reglas de Publicación

### 11.2.1 Contratos obligatorios

- Todo job debe poseer `job_id`, `run_id`, estado `pending` y timestamps válidos en formato **ISO 8601**.
- Debe adquirirse lock mediante `acquire_lock_json`.
- El payload debe ser validado por el Adaptador Multiplataforma v1.
- Publish Loop v1.6 Multiplatform solo opera sobre jobs `claimed`.
- Todo job debe finalizar explícitamente.

### 11.2.2 Reglas de idempotencia

- Un mismo job no puede generar múltiples publicaciones.
- Reintentos producen resultados equivalentes.
- Si la plataforma indica publicación previa, se registra conflicto.
- El Adaptador Multiplataforma v1 no introduce mutaciones internas.

### 11.2.3 Reglas de recuperación

- Todo error debe ser registrado con trazabilidad completa.
- **Fallas temporales:** fallas externas, de red o de disponibilidad → permiten reintento.
- **Fallas irreversibles:** payload inválido, contratos rotos, contenido no publicable → DLQ obligatorio.
- No puede avanzarse un job fallido sin registro de causa.

### 11.2.4 Reglas de validación previo a publicar

- Validación semántica del contenido.
- Validación técnica del payload.
- Job en estado `claimed`.
- Debe estar ausente todo drift activo.
- Todos los parámetros específicos de plataforma deben estar completos.

## 11.3 Reglas de Logs y Auditoría

### 11.3.1 Logs obligatorios

- Log de ejecución: timestamps de inicio y fin.
- Log del Adaptador Multiplataforma v1: payload enviado y respuesta recibida, **previamente anonimizados** para eliminar cualquier dato sensible o no persistible.
- Log de error: mensaje técnico y contexto.
- Log de métricas: locks, reintentos, totales procesados.

### 11.3.2 Prohibiciones de logging

- Prohibido registrar credenciales o datos sensibles.
- Prohibido persistir identificadores externos.
- Prohibido modificar logs existentes.
- Prohibido registrar contenido canónico en logs.

### 11.3.3 Auditoría de ejecución

- Reconstrucción cronológica completa del run.
- Verificación de contratos obligatorios.
- Confirmación de idempotencia.
- Validación del Adaptador Multiplataforma v1.
- Verificación de estado final del job.

---

# 12. Reglas de Verticales y Aislamiento

## 12.1 Naturaleza de los verticales

Los **verticales** son líneas de contenido, productos, experimentos o unidades operativas que viven **por fuera del canon central del Boot Agnóstico v2**. Representan espacios donde el usuario puede:

- Crear contenido independiente.
- Probar modelos de negocio.
- Ejecutar estrategias específicas.
- Operar sin afectar al núcleo técnico del Boot.

**Naturaleza fundamental:**

- Son **subordinados** al Canon v2.
- No tienen capacidad normativa.
- No pueden crear máquinas, reglas o estructuras centrales.
- Pueden existir, mutar o desaparecer sin impacto en las máquinas ni en el sistema documental.
- Funcionan como **satélites operativos**, nunca como fuentes de autoridad.

Los verticales pueden tener contenido técnico, creativo, financiero o de cualquier tipo, siempre que **no interfieran con el Boot ni con Máquina 01 — Governance**.

**Regla operativa crítica:**

> Los verticales solo pueden publicar contenido utilizando exclusivamente el pipeline formal (Supabase Automático v1 → Adaptador Multiplataforma v1 → Publish Loop v1.6 Multiplatform). Ningún vertical puede ejecutar publicaciones directas o mutaciones externas al pipeline.
> 

## 12.2 Reglas de aislamiento

El aislamiento garantiza que los verticales no contaminen ni modifiquen el Boot Agnóstico v2.

**Reglas obligatorias de aislamiento:**

- Ningún vertical puede influir en la identidad documental (`id`, `slug`, `id_canonico`).
- Ningún vertical puede introducir reglas canónicas.
- Ningún vertical puede modificar o extender el Estándar YAML Global v1.1 + Extensiones.
- Ningún vertical puede interactuar con Máquina 01 — Governance fuera de canales formales.
- Ningún documento dentro de un vertical puede tener `origen: canonico`.
- Los verticales no pueden definir dependencias del core.
- “Los verticales pueden contener YAML, pero dichos YAMLs nunca pueden tener `origen: canonico` ni definir normas centrales del Boot. Su función es exclusivamente operativa.”
- “Todo documento YAML dentro de verticales debe tener `origen: vertical` o `origen: operativo`.”
- Los verticales deben vivir siempre dentro de la carpeta `verticales/`.

**Regla crítica:**

> Si un vertical necesita capacidades del core (por ejemplo, publicar contenido), debe hacerlo únicamente a través del pipeline formal y nunca mediante mutaciones directas.
> 

## 12.3 Prohibiciones

Estas prohibiciones existen para mantener la consistencia del sistema.

**Prohibiciones absolutas:**

- Crear máquinas dentro de un vertical.
- Redefinir el comportamiento de Máquina 02 — Automática o sus workflows.
- Alterar contratos JSON de Supabase Automático v1.
- Alterar el funcionamiento del Adaptador Multiplataforma v1.
- Redefinir o extender Publish Loop v1.6 Multiplatform.
- Copiar o reescribir documentos canónicos.
- Generar identificadores o nombres que colisionen con los del Boot.

**Prohibiciones operativas:**

- Publicar contenido saltándose el pipeline de publicación.
- Usar los verticales como almacenamiento de estados operativos.
- Registrar logs dentro de verticales.
- Ejecutar lógica de negocio que dependa de datos internos del Boot.

**Prohibición estructural:**

> Ningún vertical puede vivir fuera de verticales/, ni moverse al árbol central sin una migración formal, aprobada en un documento canónico.
> 

---

# 13. Apéndices Técnicos

Los apéndices técnicos **no** deben contener definiciones operativas ni contratos completos de las máquinas (Publish Loop v1.6 Multiplatform, Adaptador Multiplataforma v1, Supabase Automático v1). Dichos detalles pertenecen exclusivamente a sus respectivos **manuales técnicos**, que son los documentos fuente de verdad para cada módulo operativo.

Este documento maestro solo define el **marco normativo mínimo** que evita drift entre el Canon v2 y los manuales técnicos.

## 13.1 Marco normativo mínimo sobre contratos operativos

**Reglas obligatorias:**

- Los contratos JSON completos de Supabase Automático v1 deben vivir exclusivamente en el documento técnico correspondiente.
- Las transformaciones y validaciones del Adaptador Multiplataforma v1 deben documentarse únicamente en su manual técnico.
- Las reglas de ejecución, idempotencia y estados finales del Publish Loop v1.6 Multiplatform pertenecen exclusivamente a su manual.
- Ningún contrato operativo puede escribirse o redefinirse dentro del Canon v2.
- El Canon solo puede establecer **normas generales**, nunca estructuras completas.

## 13.2 Norma de nomenclatura de RPCs

Todos los RPC del Boot Agnóstico v2 deben comenzar obligatoriamente con el prefijo `automatico_`.

**Reglas:**

- El patrón es: `automatico_<accion>_<dominio>`.
- La ausencia de prefijo invalida el RPC.
- Todo RPC debe vivir únicamente dentro de Supabase Automático v1.
- Governance debe rechazar cualquier RPC no conforme.

## 13.3 Regla de separación documental

**Prohibición absoluta:**

> Ningún documento canónico puede incluir contratos JSON completos, estructuras operativas o definiciones técnicas exhaustivas. Los verticales tampoco pueden definir contratos JSON ni estructuras operativas internas; deben usar exclusivamente los manuales técnicos del core.
> 

**Regla de localización de contratos:**

> Los contratos operativos completos solo pueden existir dentro de los manuales técnicos de cada workflow operativo del Boot Agnóstico v2.
> 
> 
> Esto incluye tanto los workflows actuales (Supabase Automático v1, Adaptador Multiplataforma v1, Publish Loop v1.6 Multiplatform) como cualquier workflow futuro que se incorpore a Máquina 02.
> 

**Regla estructural:**

> El Canon v2 define la semántica. Los manuales técnicos definen la implementación.
> 

---

# 14. Normas de Migración Documental

Las normas de migración documental definen **cuándo, cómo y bajo qué condiciones** un documento canónico del Boot Agnóstico v2 puede ser modificado, reemplazado o reubicado dentro del árbol. Estas reglas existen para garantizar que toda mutación documental preserve la integridad histórica, estructural y semántica del sistema.

La migración es siempre un proceso **formal**, **auditado** y **regulado por Máquina 01 — Governance**. Ningún cambio en un documento canónico puede realizarse sin encuadrarse estrictamente dentro de uno de los tres tipos de migración que se describen a continuación.

## 14.1 Migración menor (minor)

Las migraciones **menores** modifican partes no estructurales del documento o del árbol sin alterar identidades, rutas, contratos ni semántica normativa del Boot Agnóstico v2.

**Criterios:**

- Ajustes editoriales.
- Correcciones ortográficas o de formato.
- Ampliación descriptiva sin impacto estructural.
- Incorporación de ejemplos no normativos.
- Modificaciones que no afectan dependencias.

**Normas:**

- No requieren nuevo `id_canonico`.
- Requieren actualización del `changelog`.
- Deben generar snapshot nuevo.
- No deben afectar scripts ni workflows.
- **Validación requerida:** la migración menor puede ser aprobada automáticamente por los scripts de Máquina 01 — Governance, siempre que no exista drift activo.

---

## 14.2 Migración mayor (major)

Las migraciones **mayores** modifican estructura, reglas o identidades fundamentales sin romper continuidad con el Canon v2.

**Criterios:**

- Cambios en la estructura del documento.
- Modificación de reglas técnicas.
- Ajustes al Estándar YAML Global v1.1 + Extensiones.
- Reubicación dentro del árbol documental.
- Cambios que afectan dependencias internas.

**Normas:**

- Mantienen el `id` y `id_canonico` si la naturaleza del documento no cambia.
- Deben registrarse explícitamente en `changelog`.
- Requieren validación de Máquina 01 — Governance.
- Requieren snapshot obligatorio.

---

## 14.3 Migración extraordinaria

La migración **extraordinaria** redefine por completo la naturaleza de un documento o su rol dentro del Boot Agnóstico v2.

**Criterios:**

- Cambio total de propósito o función.
- Sustitución completa por un nuevo documento.
- Cambios que alteran identidades (`id`, `id_canonico`, `slug`).
- Fusión o división de documentos canónicos.
- Reorganización profunda del árbol documental.

**Normas:**

- Requiere creación de un **nuevo documento** con nuevo `id` y `id_canonico`.
- El documento anterior debe moverse al **Archivo Histórico Documental**.
- Debe registrarse una entrada mayor en el `changelog`.
- Requiere validación explícita de Máquina 01 — Governance.
- Requiere snapshot completo para marcar el cambio irreversible.

---

# 15. Reglas de Seguridad Operativa

## 15.1 Manejo de credenciales

La seguridad de credenciales define los límites absolutos de interacción entre el Boot Agnóstico v2, sus máquinas y los servicios externos. Estas reglas son obligatorias y no negociables.

**Reglas obligatorias:**

- Todas las credenciales deben almacenarse exclusivamente en entornos seguros (variables de entorno, vaults externos o infraestructura cifrada).
- Ninguna credencial puede escribirse, copiarse o pegarse en documentos del Boot.
- Los scripts no pueden exponer credenciales ni incluirlas en logs.
- Las credenciales deben rotarse según la política establecida para cada servicio.
- Toda interacción con servicios externos debe utilizar únicamente credenciales declaradas en el entorno seguro.
- En **n8n**, todas las credenciales deben configurarse **exclusivamente mediante Environment Variables**; queda prohibido introducirlas en nodos, campos visibles o configuraciones internas.

**Regla crítica:**

> Ninguna credencial puede vivir en GitHub, n8n, Supabase ni dentro del árbol documental del Boot.
> 

---

## 15.2 Manejo de errores críticos

La gestión de errores críticos determina cómo se preserva la estabilidad del Boot Agnóstico v2 cuando ocurre una falla grave.

**Reglas obligatorias:**

- Todo error crítico debe abortar inmediatamente la operación en curso.
- Los errores críticos deben registrarse con contexto técnico y trazabilidad.
- Un error crítico en Governance bloquea la operación completa hasta su resolución.
- Un error crítico en Publish Loop v1.6 Multiplatform obliga al job a pasar a DLQ si la falla es irrecuperable.
- Las fallas en Supabase Automático v1 deben activar mecanismos de retry solo cuando sean externas o temporales.

**Norma estructural:**

> Si un error crítico implica drift o violación de contrato, el sistema debe bloquearse preventivamente.
> 

---

## 15.3 Condiciones de bloqueo operativo

Estas condiciones definen cuándo el Boot Agnóstico v2 debe dejar de operar completamente para evitar contaminación o daño estructural.

**Causas de bloqueo:**

- Existencia de drift documental detectado por Governance.
- Snapshot desactualizado para un documento canónico.
- Inconsistencia entre árboles físico y lógico.
- Violación de contratos JSON en Supabase Automático v1.
- Error crítico en Publish Loop v1.6 Multiplatform.
- Fallo repetido en la adquisición de lock.
- Detectar un vertical interfiriendo con el Boot.

**Normas del estado de bloqueo:**

- Ningún job puede ser reclamado mientras el sistema esté bloqueado.
- Ninguna publicación puede ejecutarse.
- Ningún documento canónico puede modificarse hasta resolver la causa.
- Debe generarse un log especial de bloqueo para auditoría.

**Condición final:**

> El bloqueo solo puede levantarse mediante validación formal de Máquina 01 — Governance y un snapshot actualizado.
> 

---

# 16. Archivo Histórico Documental

## 16.1 Reglas de ingreso

El Archivo Histórico Documental conserva versiones obsoletas, migradas o sustituidas de documentos canónicos del Boot Agnóstico v2. Su función es mantener trazabilidad sin afectar la operación.

**Reglas obligatorias de ingreso:**

- Solo ingresan documentos que hayan sido reemplazados mediante una migración extraordinaria.
- Deben ingresar con su `id`, `id_canonico` y `slug` originales sin alteraciones.
- Deben conservar el `changelog` completo previo a la migración.
- El documento nuevo debe referenciar explícitamente que el anterior fue movido al Archivo Histórico.
- El movimiento debe registrarse en snapshot.
- Debe registrarse el **hash previo** y el **hash posterior** amiento para garantizar trazabilidad total.

**Restricción crítica:**

> Ningún documento puede ingresar al Archivo Histórico sin una migración formal validada por Máquina 01 — Governance.
> 

---

## 16.2 Reglas de preservación

Las reglas de preservación aseguran que los documentos archivados mantengan integridad, trazabilidad y valor referencial.

**Reglas obligatorias:**

- Los documentos archivados no pueden ser editados bajo ninguna circunstancia.
- Deben conservar su estructura y contenido original.
- Deben mantenerse siempre accesibles para auditorías.
- Su ubicación debe ser estable y permanente dentro de `archivo_historico/`.
- No pueden reactivarse salvo mediante un proceso formal de reconstrucción.

**Regla estructural:**

> El Archivo Histórico no es un espacio operativo: solo conserva y registra, nunca ejecuta ni influye.
> 

---

## 16.3 Registros obligatorios

Todo documento incluido en el Archivo Histórico debe acompañarse de registros formales que permitan reconstruir su historia.

**Registros mínimos obligatorios:**

- Fecha exacta de ingreso al archivo.
- Motivo de migración extraordinaria.
- Identidad del documento que lo reemplazó (nuevo `id` y `id_canonico`).
- Hash consolidado previo a su archivado.
- Registro del snapshot que certificó el cierre.

**Regla crítica:**

> Ningún documento puede eliminarse del Archivo Histórico: la historia del Boot Agnóstico v2 es inmutable.
> 

---

# 17. Mecanismo de Deprecación

## 17.1 Señalización de documentos obsoletos

El proceso de deprecación comienza con la detección formal de que un documento ha dejado de cumplir su propósito, ha sido superado por una versión nueva o ya no es coherente con el Canon v2.

**Reglas de señalización:**

- La señalización debe quedar documentada explícitamente dentro del `changelog` del documento.
- Debe agregarse un bloque de advertencia al inicio del documento indicando su estado de obsolescencia, utilizando el **template estándar de advertencia de obsolescencia** definido por el Canon v2:

```
> ⚠️ **DOCUMENTO OBSOLETO**
> Este documento ha sido marcado como obsoleto por Máquina 01 — Governance. No debe utilizarse como referencia normativa ni técnica.
```

- La señalización solo puede ser realizada por Máquina 01 — Governance.
- La obsolescencia no autoriza edición: el documento mantiene su integridad original.

**Condición crítica:**

> Un documento marcado como obsoleto no puede ser utilizado como referencia normativa ni técnica para ningún proceso operativo del Boot Agnóstico v2.
> 

---

## 17.2 Secuencia formal de deprecación

La secuencia de deprecación garantiza una transición ordenada y trazable cuando un documento queda fuera de uso.

**Secuencia obligatoria:**

1. **Señalización formal:** marcada en `changelog` + advertencia en el encabezado.
2. **Generación de snapshot:** se registra el estado final del documento antes de ser sustituido.
3. **Registro de reemplazo:** se documenta en la nueva versión qué documento está siendo deprecado.
4. **Migración extraordinaria (solo si corresponde):** si el documento será sustituido completamente.
5. **Movimiento al Archivo Histórico:** si la deprecación implica obsolescencia total.

**Condición operativa:**

> Ningún proceso del Boot puede referenciar un documento en estado de deprecación activa; solo se permite la referencia histórica.
> 

---

## 17.3 Prohibiciones

Para mantener la integridad documental y operativa del Boot Agnóstico v2, se establecen las siguientes prohibiciones durante el proceso de deprecación:

**Prohibiciones absolutas:**

- Editar un documento una vez marcado como obsoleto.
- Revertir manualmente la deprecación sin una migración extraordinaria.
- Eliminar documentos obsoletos del árbol.
- Utilizar documentos obsoletos como fuente normativa.
- Crear dependencias nuevas que apunten a documentos en deprecación.

**Prohibición estructural:**

> La deprecación nunca puede alterar la historia documental: ningún documento deprecado puede ser modificado, eliminado o renombrado.
> 

---

# 18. Integración con Machine 05 — Cognitiva

## 18.1 Límites de lectura

Machine 05 — Cognitiva puede **leer** el Boot Agnóstico v2 únicamente bajo reglas estrictas que preservan integridad, seguridad y estabilidad del sistema.

**Reglas de lectura:**

- Puede leer únicamente documentos canónicos **ya validados** y sin drift activo.
- No puede acceder a credenciales, variables de entorno ni información sensible.
- No puede interpretar documentos marcados como obsoletos o en deprecación.
- Debe respetar estructuras, jerarquías y semántica del árbol lógico.
- No puede inferir ni reconstruir información eliminada o archivada.
- **No puede acceder, leer ni inferir estructuras internas de Supabase o de sus tablas operativas; su lectura se limita estrictamente al árbol documental.**

**Regla crítica:**

> Machine 05 — Cognitiva solo puede operar con contenido estable, íntegro y validado por Máquina 01 — Governance.
> 

---

## 18.2 Límites de escritura

Machine 05 — Cognitiva **no tiene autorización para escribir**, modificar o mutar ningún documento del Boot Agnóstico v2.

**Prohibiciones absolutas de escritura:**

- No puede crear documentos.
- No puede modificar documentos.
- No puede sugerir o forzar migraciones.
- No puede alterar identidades (`id`, `slug`, `id_canonico`).
- No puede generar YAMLs ni editar campos.

**Excepciones controladas:**

- Puede redactar borradores **fuera del árbol documental**, bajo solicitud explícita del usuario.
- Puede proponer correcciones semánticas siempre que no implique mutación directa.

**Regla estructural:**

> Ninguna acción de Machine 05 puede modificar el Canon v2 ni sus documentos asociados.
> 

---

## 18.3 Observabilidad

Machine 05 — Cognitiva contribuye a la observabilidad del sistema mediante análisis, alertas semánticas y sugerencias no mutantes.

**Funciones permitidas:**

- Detectar posibles incoherencias en borradores.
- Analizar patrones del árbol documental sin modificarlo.
- Identificar riesgos semánticos o estructurales.
- Sugerir puntos de auditoría a Máquina 01 — Governance.

**Funciones prohibidas:**

- Generar acciones automáticas dentro del árbol documental.
- Alterar workflows o estados operativos.
- Emitir comandos de migración o deprecation.

**Regla crítica:**

> La observabilidad de Machine 05 nunca puede reemplazar ni interferir con la responsabilidad formal de Máquina 01 — Governance.
> 

---

# 19. Conclusión Operativa

## 19.1 Estado final del documento

El presente documento queda establecido como **norma maestra**, **fundacional** y **regente** del Boot Agnóstico v2. Su función es definir, unificar y consolidar toda la semántica estructural, técnica y operativa que gobierna:

- El árbol documental.
- Las máquinas invariantes.
- Las reglas del Estándar YAML Global v1.1 + Extensiones.
- El pipeline operativo entre Documentación → Scripts → Supabase Automático v1 → n8n.
- Los contratos del Adaptador Multiplataforma v1 y Publish Loop v1.6 Multiplatform.
- Las normas de seguridad, migración, deprecación y archivo histórico.

**Este documento prevalece sobre cualquier otro documento canónico en caso de conflicto semántico o normativo.**

Queda, a partir de este punto, en estado **estable**, **validado** y **bajo gobernanza estricta**, sujeto solo a cambios mediante migración mayor o extraordinaria.

---

## 19.2 Condición de cierre

El documento se considera **formalmente cerrado** cuando:

- Su `id`, `id_canonico`, `slug`, `version`, `estado` y `origen` se encuentran correctamente definidos y validados contra el **Estándar YAML Global v1.1 + Extensiones**.
- El `changelog` incluye la entrada correspondiente a su creación o migración, sin omisiones.
- El snapshot consolidado ha sido generado, firmado y registrado por Máquina 01 — Governance.
- No existe drift documental asociado al documento ni al árbol donde reside.
- Se ha verificado su consistencia estructural, semántica y técnica contra el Canon v2.
- Se ha confirmado que el documento no genera colisiones de identidad con otros documentos canónicos.

**Regla final:**

> Un documento solo puede considerarse activo y operativo dentro del Boot Agnóstico v2 cuando cumple esta condición de cierre. Caso contrario, su uso operativo queda estrictamente prohibido.
>