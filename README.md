# Contratación por el sismo del 10 de agosto de 2026

Rastreo de la contratación pública asociada al sismo de magnitud 7,4 del **10 de agosto de
2026**, con epicentro en San José del Palmar (Chocó).

**Sitio:** https://jlzmontenegro.github.io/ContratacionSismoV2/

- **[Tablero](https://jlzmontenegro.github.io/ContratacionSismoV2/)** — 759 registros con
  filtros combinables por etapa del trámite, nivel de certeza, fuente, departamento,
  municipio, entidad, estado, fecha, valor y texto libre.
- **[Informe](https://jlzmontenegro.github.io/ContratacionSismoV2/informe.html)** — método,
  hallazgos y advertencias de lectura.

## Cifras del corte

Corte al **8 de septiembre de 2026**, con dato de SECOP actualizado al 5 de septiembre.

| Bloque | Registros | Valor (COP) |
|---|---:|---:|
| Contratos firmados | 329 | 91.874 millones |
| Procesos sin contrato registrado | 108 | 36.964 millones |
| Procesos que ya figuran como contrato — **no sumar** | 268 | 78.296 millones |
| Aportes privados de cámaras de comercio (aparte) | 54 | 4.125 millones |
| **Compromiso sin duplicar** | | **128.838 millones** |

## Fuentes

Datos abiertos de Colombia, `datos.gov.co`:

- SECOP II · Contratos Electrónicos — `jbjy-vk9h`
- SECOP II · Procesos de Contratación — `p6dx-8zbt`
- SECOP I · Procesos de Compra Pública — `f789-7hwg`

Marco normativo del perímetro: Decreto Presidencial **1261 del 19 de agosto de 2026** (estado
de emergencia económica, social y ecológica en 15 departamentos), Decreto **1.03.01-1070**
de la Gobernación del Valle del Cauca y Decretos **4112.010.20.0963** y **4112.010.20.0964**
del Distrito de Santiago de Cali, los tres del 10 de agosto de 2026.

## Cómo leer las cifras

**Contratos y procesos no se suman.** En SECOP II el proceso de contratación y el contrato que
resulta de él son dos registros del mismo trámite, unidos por `id_del_portafolio` =
`proceso_de_compra`. El 71 % de los procesos del rastreo ya figura como contrato firmado, así
que sumar ambos universos infla el resultado en unos 78.296 millones. El tablero excluye esos
registros por defecto y los marca cuando se activan.

**Los niveles de certeza importan.** *Confirmado* significa que el objeto contractual menciona
expresamente el sismo o el decreto del 10 de agosto. *Probable* es contratación por urgencia
manifiesta o calamidad pública posterior al sismo, en departamento cubierto, sin cita expresa.
*Por verificar* exige leer el expediente: a la vista del objeto, buena parte responde a otras
causas.

**Las cifras son un piso, no un techo.** La urgencia manifiesta permite contratar antes de
publicar, así que el universo crece con el tiempo.

**No incluye al FNGRD.** El Fondo Nacional de Gestión del Riesgo de Desastres ejecuta por
encargo fiduciario bajo régimen de derecho privado y casi no publica contratos en SECOP II
(14 en toda su historia frente a 1.889 procesos). Su gasto por el sismo debe pedirse a la
UNGRD o a la fiduciaria.

## Licencia y datos personales

Los datos provienen de fuentes abiertas oficiales y se reproducen con fines de control social,
conforme al artículo 74 de la Constitución Política y a la Ley 1712 de 2014 de transparencia y
acceso a la información pública. Incluyen nombres y documentos de contratistas tal como los
publica SECOP. Cualquier titular que solicite corrección o supresión de sus datos puede
abrir un *issue* en este repositorio.
