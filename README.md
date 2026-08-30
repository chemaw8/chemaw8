# José María Loyola

**Forward Deployed Engineer** · Innovattia / Ordenaris / Orquestia — Ciudad de México

Construyo y despliego sistemas de IA dentro del negocio: me siento con el área o
con el cliente, entiendo el proceso real, y entrego algo que funciona con sus datos
sucios y sus casos borde. No diapositivas — sistemas en producción.

Estudiante de Actuaría en el ITAM. Trabajo con clientes de telecomunicaciones,
retail y banca en México.

---

### En qué trabajo

**Agentes de IA en producción.** Un bot de voz para portabilidad telefónica
(LiveKit + VICIdial) atendiendo llamadas reales en un centro de contacto, con
medición de conversión en campo. Campañas conversacionales sobre RCS con IA para
**Bait** y para los **Charros de Jalisco**, medidas contra tasa de lectura y de
respuesta reales — no contra la promesa del proveedor.

**Analítica que decide.** Rentabilidad por sucursal para la red de tiendas
**Bait (Walmart)**: break-even, modelos estocásticos y el criterio de cierres.
Casos de negocio de MVNO para **Tiendas Neto** y **Farmacias Similares**,
auditados hasta el flujo después de impuestos, no el de la lámina. Máquina de
adquisición para una tarjeta de crédito de **BBVA**.

**Herramientas internas que la gente usa.** Homologador de catálogos de obra
contra el tabulador oficial de la **CDMX**, en producción. Dashboards ejecutivos
de mensajería A2P (SMS/RCS) para revisión con cliente. Pipelines de datos sobre
el punto de venta.

**Ingeniería del entorno de trabajo con IA.** Lo de abajo.

---

### Kit Chema — estándar de calidad para Claude Code, medido

[![Kit Chema](https://img.shields.io/badge/kit--chema-v1.15-1f6e8c)](https://github.com/chemaw8/claude-kit-chema)
[![Licencia MIT](https://img.shields.io/badge/licencia-MIT-3a7a51)](https://github.com/chemaw8/claude-kit-chema/blob/main/LICENSE)
[![En español](https://img.shields.io/badge/idioma-espa%C3%B1ol-a9631f)](https://github.com/chemaw8/claude-kit-chema)

La mayoría de los "kits" para agentes son prosa bien redactada que nadie verificó.
**Éste está medido, y las mediciones se vuelven a correr cuando algo cambia:**

| Qué | Medición |
|---|---|
| Las skills se disparan cuando deben | **27/27**, incluidas 7 fronteras entre dominios vecinos — y con las **70 skills** que compiten de verdad, no en laboratorio |
| El que verifica el trabajo, verificado | **28/28, cero falsos positivos** — incluidas 12 trampas escritas por agentes adversarios |
| El council muerde, no decora | Rechazó por unanimidad **una skill que yo mismo propuse** |
| El estado sobrevive entre sesiones | Contrato de reanudación con ancla de git; la rotación verifica **línea por línea** que nada se pierde |
| Sabe cuándo **no** hacer algo | Cinco propuestas de mejora medidas y **descartadas** en vez de acumuladas |

→ **[github.com/chemaw8/claude-kit-chema](https://github.com/chemaw8/claude-kit-chema)** · núcleo de reglas + 9 skills de dominio + 3 subagentes + council · en español

---

### Cómo trabajo

- **Medir antes que opinar.** Si una afirmación mueve una decisión, va con su número
  y su fuente. "Se siente más rápido" no es un dato.
- **Terminado significa verificado.** Código ejecutado, cifras recalculadas, fuentes
  abiertas. Un "listo" falso cuesta más que un "me faltó esto".
- **Evaluación crítica antes que complacencia.** Detectar un error en la propuesta de
  quien me pide algo y callarlo es el peor fallo posible.
- **Esfuerzo proporcional al riesgo.** No todo merece un panel de revisión; lo que va
  a dirección o mueve dinero, sí.

---

### Herramientas

`Python` · `SQL` · `TypeScript / Next.js` · `Claude Code & Agent SDK` · `MCP`
`RAG local (embeddings + reranker)` · `LiveKit` · `Docker` · `Postgres / MySQL` · `Vercel`

---

<sub>Actuaría @ ITAM · Ciudad de México · <a href="https://github.com/chemaw8/claude-kit-chema">Kit Chema</a></sub>
