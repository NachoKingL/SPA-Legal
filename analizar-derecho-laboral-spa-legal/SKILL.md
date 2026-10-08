---
name: analizar-derecho-laboral-spa-legal
description: >-
  Analiza casos de derecho del trabajo chileno (individual, colectivo y procesal) con cinco manuales
  de la Academia Judicial cotejados con la ley vigente a octubre de 2026. Úsala siempre que Nacho o el
  equipo de SPA Legal pidan evaluar un despido o autodespido, nulidad del despido, indemnizaciones o
  finiquito, una relación laboral encubierta (honorarios, plataformas), subcontratación o multirut,
  tutela laboral, acoso laboral o sexual y Ley Karin, discriminación o represalias, fueros y
  desafueros, jornada (40 horas), ius variandi, sindicatos, prácticas antisindicales, negociación
  colectiva, huelga, multas de la Dirección del Trabajo, o la estrategia ante un Juzgado de Letras del
  Trabajo (plazos de caducidad, monitorio, prueba, recurso de nulidad, cobranza). Sirve si se
  representa al trabajador, al empleador o a un sindicato. No requiere contexto previo.
---

# Analizar casos de derecho del trabajo — SPA Legal

Esta skill reconstruye, en un chat nuevo y sin historial previo, el marco normativo, doctrinal y
jurisprudencial necesario para hacer una primera evaluación jurídica sólida de un caso laboral en
Chile. Se basa en la lectura íntegra de cinco materiales docentes de la **Academia Judicial de
Chile**:

- **MD81 — "Derecho laboral sustantivo. Aspectos esenciales para la labor jurisdiccional"**, Pablo
  Guidi y Gabriela Riffo (2025): principios, calificación de la relación laboral, formalización,
  subcontratación, suministro, grupo de empresas, potestades del empleador, no discriminación,
  acoso y Ley Karin, tutela, término del contrato, nulidad del despido y bases del derecho colectivo.
- **MD4 — "Tutela de derechos fundamentales en el contexto del derecho del trabajo"**, Sergio
  Gamonal y Pablo Guidi (2020): ponderación, eficacia diagonal de los derechos fundamentales,
  control tecnológico, cada derecho protegido con jurisprudencia, prueba indiciaria, remedios
  sistémicos y despido lesivo.
- **MD39 — "Acoso sexual, acoso moral y discriminación en contexto laboral"**, Walker, Sarmiento,
  García y Lagos (2022): estándares internacionales, perspectiva de género, elementos del acoso
  sexual, sexista y laboral, y su tutela. **Es anterior a la Ley Karin**: su procedimiento quedó
  reemplazado.
- **MD66 — "Derecho colectivo del trabajo"**, Condeza, Kopplin y Lanata (2023): libertad sindical,
  sindicatos, fueros, prácticas antisindicales, negociación colectiva reglada y no reglada, huelga,
  instrumentos colectivos y judicialización.
- **MD19 — "Tribunales laborales: nociones básicas de organización y funcionamiento"**, Alruiz,
  Cruces, Lorca y Villalón (2021): competencia, principios, cada procedimiento paso a paso, plazos de
  audiencias, notificaciones, recursos, cumplimiento, títulos ejecutivos y tramitación electrónica.

Todo ese contenido fue cotejado con el texto vigente y las reformas posteriores a cada manual (Ley
Karin, ley de 40 horas, ley de conciliación, reforma de pensiones, nuevas leyes de 2025-2026,
ingreso mínimo actual, competencia del Juzgado de Letras del Trabajo de Valparaíso). El resultado del
cotejo, las correcciones a los manuales y los puntos que conviene confirmar literalmente en LeyChile
están en `references/vigencia-y-reformas.md`.

## Cómo usar esta skill

1. **Lee los hechos y fija la posición del cliente.** Precisa a quién se representa (trabajador,
   empleador, sindicato, empresa principal o usuaria), si la relación está vigente o terminó, el
   tipo de contrato (indefinido, plazo fijo, obra o faena, honorarios), la remuneración, la
   antigüedad, el tamaño de la empresa y si el empleador es privado o un órgano público. Si un dato
   de ese tipo cambia la vía o el plazo y no viene en el relato, pregúntalo antes de concluir; no lo
   supongas.
2. **Antes que nada, revisa los plazos.** En derecho laboral la mayoría de las acciones caduca en 60
   días hábiles, y un análisis de fondo impecable sobre una acción caducada no le sirve al cliente.
   Usa `references/plazos-montos-y-calculos.md` para identificar qué plazo corre, desde cuándo, si
   hubo reclamo ante la Inspección del Trabajo que lo suspenda y cuál es el tope absoluto. Si no hay
   fechas exactas (despido, carta, reclamo administrativo, comparendo), pídelas. Nunca asumas que los
   hechos ocurrieron "hoy".
3. **Lee siempre `references/vigencia-y-reformas.md`.** Es breve y evita aplicar reglas que los
   manuales describen pero que hoy cambiaron (por ejemplo, el procedimiento de acoso anterior a la
   Ley Karin, la jornada de 45 horas o la extensión del art. 485).
4. **Califica el conflicto y carga sólo las referencias pertinentes** según el "Mapa de
   referencias". No es necesario leer los diez archivos en cada consulta: un despido verbal con
   cotizaciones impagas exige `terminacion-del-contrato.md` y `plazos-montos-y-calculos.md`; una
   trabajadora acosada que sigue trabajando exige `discriminacion-acoso-y-ley-karin.md` y
   `tutela-de-derechos-fundamentales.md`; un "prestador a honorarios" despedido exige además
   `calificacion-y-contrato.md`.
5. **Aplica los estándares tal como están en las referencias** (indicios de subordinación, test de
   proporcionalidad, prueba indiciaria del art. 493, gravedad de las causales del art. 160, requisitos
   de la carta del art. 162). No inventes estándares ni números de rol: si necesitas jurisprudencia
   adicional o más reciente, dilo y ofrece buscarla con la skill de jurisprudencia o con vLex.
6. **Estructura la respuesta** según "Estructura de salida esperada".

## Mapa de referencias

| Tema | Archivo |
|---|---|
| Fuentes, fecha del cotejo, reformas posteriores a los manuales, correcciones, proyectos en trámite y puntos por confirmar en LeyChile | `references/vigencia-y-reformas.md` |
| Plazos de caducidad y prescripción, días hábiles, fórmulas de indemnizaciones y recargos, topes, ingreso mínimo vigente, umbral del monitorio | `references/plazos-montos-y-calculos.md` |
| Principios, existencia de relación laboral (arts. 7 y 8, indicios, honorarios, plataformas), escrituración, cláusulas tácitas, contratos a plazo y por obra | `references/calificacion-y-contrato.md` |
| Subcontratación (183-A ss.), suministro de trabajadores (183-F ss.), empleador, cambio de dueño, grupo de empresas o multirut (art. 3 y 507) | `references/subcontratacion-suministro-y-grupo-de-empresas.md` |
| Poder de dirección, ius variandi (art. 12), reglamento interno, potestad disciplinaria, control tecnológico y privacidad, deber de seguridad, jornada (40 horas), conciliación | `references/potestades-jornada-y-privacidad.md` |
| No discriminación (art. 2), igualdad salarial, acoso sexual, acoso laboral, violencia de terceros, Ley Karin (protocolo, investigación, plazos) y vías del acosado | `references/discriminacion-acoso-y-ley-karin.md` |
| Procedimiento de tutela (485-495): derechos protegidos, legitimación, ponderación, prueba indiciaria, sentencia y remedios, despido lesivo (489), indemnidad, sector público | `references/tutela-de-derechos-fundamentales.md` |
| Causales de término (159, 160, 161, 161 bis, 163 bis), carta de despido, finiquito, indemnizaciones, despido injustificado, autodespido, nulidad del despido, fueros y desafuero | `references/terminacion-del-contrato.md` |
| Libertad sindical, sindicatos, fuero sindical, prácticas antisindicales y desleales, negociación colectiva, huelga, instrumentos colectivos | `references/derecho-colectivo.md` |
| Competencia (Valparaíso/Viña del Mar), principios procesales, procedimientos (aplicación general, monitorio, tutela, reclamo de multas), audiencias, prueba, recursos, cumplimiento y títulos ejecutivos | `references/procedimiento-y-cumplimiento.md` |

## Estructura de salida esperada

Responde siempre en prosa, en un texto conversacional dirigido a un abogado; no generes un
documento ni uses las skills de .docx para esto, la salida es la respuesta misma. Usa listas sólo
cuando ayuden a separar alternativas o partidas de dinero. La respuesta debe cubrir estos cinco
puntos, en este orden:

1. **Calificación del caso y pretensiones.** Qué conflicto es (despido injustificado, despido
   indirecto, tutela con relación vigente o con ocasión del despido, nulidad del despido,
   declaración de relación laboral, práctica antisindical, reclamo de multa, etc.), qué acciones
   caben, cuáles deben acumularse y cuál va en subsidio, y en qué procedimiento se tramitan.
2. **Normativa y criterios aplicables.** Artículos del Código del Trabajo y leyes especiales que
   rigen (con su texto vigente), el estándar que aplicarán los tribunales y los criterios
   jurisprudenciales o administrativos relevantes citados en las referencias.
3. **Análisis del caso.** Aplicación a los hechos: si la causal invocada se sostiene, qué indicios
   existen, quién prueba qué, qué partidas proceden y una estimación de montos cuando haya datos
   suficientes (señalando la base de cálculo y los topes usados).
4. **Riesgos y observaciones prácticas.** Plazos que corren y su fecha límite estimada, debilidades
   de la posición del cliente, prueba que hay que asegurar ya (carta de despido, liquidaciones,
   certificados de cotizaciones, correos, WhatsApp, testigos, informe de fiscalización), gestiones
   previas convenientes (reclamo ante la Inspección del Trabajo, medida prejudicial, reserva de
   derechos en el finiquito) y riesgos de costas o de reconvención.
5. **Antecedentes faltantes.** Qué información fáctica no fue entregada y cambiaría el análisis
   (fechas exactas, contenido literal de la carta, estado de cotizaciones, número de trabajadores,
   existencia de reglamento interno o protocolo Ley Karin, afiliación sindical, fuero), en vez de
   asumirla.

## Notas de tono y alcance

SPA Legal es un estudio jurídico de Viña del Mar. Los casos de Viña del Mar, Valparaíso, Concón y
Juan Fernández son de competencia del **Juzgado de Letras del Trabajo de Valparaíso** (y la
cobranza, del Juzgado de Cobranza Laboral y Previsional de Valparaíso); los recursos van a la
**Corte de Apelaciones de Valparaíso**. Ante falta de criterio uniforme, prefiere los fallos más
recientes de la Corte Suprema (en especial los de unificación de jurisprudencia) y, si existen, los
de la Corte de Apelaciones de Valparaíso. Los manuales citan varios fallos del JLT y de la Corte de
Valparaíso; están identificados en las referencias.

Los manuales tienen fechas distintas (2020 a 2025) y la legislación laboral cambió mucho desde
entonces. Cuando una regla provenga de un manual anterior a una reforma, dilo y aplica el texto
vigente. Si el usuario necesita citar literalmente un artículo en un escrito, recomiéndale verificar
la redacción exacta en LeyChile: el cotejo se hizo con fuentes secundarias confiables porque el
acceso directo a LeyChile no estuvo disponible, y algunos puntos quedaron marcados como "por
confirmar".

No confundas la caducidad con la prescripción: los 60 días hábiles del art. 168 (y de los arts.
171, 486 y 489) son de caducidad y el tribunal debe declararlos de oficio; los plazos del art. 510
son de prescripción y sólo operan si se alegan. Tampoco confundas el despido injustificado con el
despido lesivo: todo despido lesivo es injustificado, pero no al revés, y la acción de tutela con
ocasión del despido obliga a acumular las demás acciones en la misma demanda, con la de despido
injustificado en subsidio, bajo sanción de entenderlas renunciadas.

Para redactar la demanda, contestación, reclamo, recurso o carta, deriva a la skill
`escritos-judiciales-spa-legal`. Para cotizar honorarios, a `propuestas-honorarios-spa-legal`. Si el
empleador está en liquidación concursal, complementa con `analizar-liquidacion-concursal-spa-legal`
(verificación de créditos laborales, art. 163 bis). Si el caso involucra retención de pensión de
alimentos por el empleador, con `analizar-pension-alimentos-spa-legal`. Para jurisprudencia
adicional, ofrece usar `revisar-jurisprudencia-spa-legal` o `busqueda-vlex-spa-legal`.
