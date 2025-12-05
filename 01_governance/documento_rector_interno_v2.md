# documento\_rector\_interno\_v2.md

```yaml
id: boot_agnostico_01_governance_documento_rector_interno_v2
id_canonico: boot/agnostico/01_governance/documento_rector_interno_v2
slug: documento_rector_interno_v2
titulo: Documento Rector Interno v2
tipo: documento_canonico
version: 2.0.0
estado: activo
origen: canonico
dependencias:
  - documento_tecnico_reinicio_total_v2.md
descripcion: >
  Documento rector que establece la identidad, semántica, arquitectura y reglas superiores del Boot Agnóstico v2. Posee jerarquía máxima y regula la coherencia estructural del sistema.
criterios_aceptacion:
  - Debe definir identidad ontológica, máquinas invariantes y reglas superiores.
  - No debe contener contradicciones con el Canon v2.
  - Debe ser único, inmutable y poseer jerarquía máxima documental.
changelog:
  - 2025-12-03: Creación del documento rector bajo Canon v2.
extensiones:
  propietario: governance
  sensibilidad: alta
  etiquetas:
    - canon
    - rector
    - governance
  riesgos:
    - alteración indebida puede comprometer la coherencia total del Boot.
  metrica_relevancia: alta
```
---

## 1. Propósito

Este documento establece la identidad, las reglas estructurales, la semántica, la arquitectura y los invariantes que definen al Boot Agnóstico v2. Posee jerarquía superior sobre cualquier documento operacional, técnico o auxiliar que exista o se genere en el sistema.

## 2. Identidad Ontológica del Sistema

La identidad ontológica oficial del sistema es **Boot Agnóstico v2**. Esta identidad es única, inmutable y superior a cualquier representación física o lógica.

El Boot Agnóstico v2 es un sistema modular compuesto por máquinas semánticas cooperantes.\
No es una colección de archivos; es una estructura conceptual regida por reglas estrictas de coherencia, consistencia y no-drift.

## 3. Máquinas Fundamentales (Invariantes)

El sistema está compuesto exclusivamente por cinco máquinas:

- **Máquina 01 — Governance**\
  Validación del canon, estructura, drift, hashing, snapshot.
- **Máquina 02 — Automática**\
  Ejecución, flujos, automatización, orquestación.
- **Máquina 03 — Creativa**\
  Semántica de contenido, variación, plantillas, estructura creativa.
- **Máquina 04 — Financiera**\
  Señales económicas, retorno, análisis monetario.
- **Máquina 05 — Cognitiva**\
  Análisis extendido, inferencias, patrones.

Estas máquinas no pueden eliminarse, redefinirse, renombrarse ni extenderse en cantidad bajo ninguna circunstancia.

## 4. Reglas Documentales Fundamentales

Todo documento formal del Boot debe cumplir:

**Prohibición adicional:** Ningún documento puede incluir bloques YAML de ejemplo, demostración o ilustración que puedan ser interpretados por los scripts como YAML real. Todo contenido YAML debe corresponder exclusivamente a documentos canónicos válidos.

1. Alineación total a este Documento Rector.
2. Uso obligatorio del Estándar YAML Global v1.1 + extensiones.
3. Identidad inmutable definida por su `id`.
4. `id_canonico` debe reflejar su ruta lógica exacta.
5. Prohibición absoluta de documentos ambiguos, duplicados o sin intención semántica real. Todo documento debe declarar y cumplir una intención semántica explícita acorde a su rol dentro del canon.
6. Prohibición absoluta de drift: semántico, físico, lógico, documental o estructural.
7. Todo cambio significativo debe registrarse en su `changelog`.

## 5. Semántica del Árbol Documental

El árbol físico (filesystem) y el árbol lógico (`id_canonico`) deben ser coherentes pero no idénticos.\
El árbol físico vive en GitHub; el árbol lógico vive en la semántica del Boot.\
La divergencia no está permitida.

## 6. Jerarquía Documental

**Aclaración:** El README raíz no posee jerarquía normativa dentro del canon y no forma parte de esta estructura.

1. **Documento Rector Interno v2** (este documento)
2. **Documento Técnico de Reinicio Total v2**
3. Documentos y manuales técnicos por máquina
4. Documentos auxiliares
5. verticales
6. Archivo histórico (no operativo)

## 7. Regla de No-Contaminación

El archivo histórico no puede contener YAML, ni documentos parseables por los scripts de Governance. Su función es estrictamente referencial y no operativa.

No puede coexistir en el repositorio ningún documento, estructura, contenido o fragmento proveniente de la Era Notion o del Canon v1.\
El Boot Agnóstico v2 se construye exclusivamente con documentos nuevos, reescritos según el Canon v2.

## 8. Drift — Definición y Prohibición

Se define drift como cualquier divergencia entre:

- documento declarado y documento real,
- ruta física y ruta lógica,
- estructura esperada y estructura observada,
- semántica del canon y contenido escrito,
- versión declarada y estado interno.

El drift debe ser detectado, bloqueado y corregido inmediatamente.

## 9. Operación General del Boot

Ninguna máquina del sistema puede operar si la Máquina 01 — Governance detecta inconsistencias, drift o violaciones al canon.

El Boot Agnóstico v2 opera mediante:

- control estricto de documentación,
- gobernanza estructural,
- validación permanente de consistencia,
- mantenimiento del árbol lógico,
- ejecución de máquinas bajo condiciones reguladas.

## 10. Estado de Construcción

El Boot Agnóstico v2 se encuentra en proceso de ensamblaje.\
Este documento actúa como guía principal sobre la cual se construyen el resto de los elementos canónicos.

## 11. Conclusión

Este documento establece las reglas superiores del sistema.\
Nada puede contradecirlo.\
Toda modificación requiere revisión de gobernanza y registro estructural.

