<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-oscuro.svg">
  <img alt="José María Loyola — implemento IA dentro del negocio y la mido antes de decir que funciona" src="assets/banner-claro.svg" width="100%">
</picture>

**Líder de implementación de IA · Forward Deployed Engineer** en Innovattia / Ordenaris / Orquestia, Ciudad de México.

Me siento con el área o con el cliente, entiendo el proceso real y entrego algo que funciona con sus datos sucios y sus casos borde. No diapositivas: sistemas en producción, con la medición que dice si sirvieron.

Estudiante de Actuaría en el ITAM. Trabajo con clientes de telecomunicaciones, retail y banca en México.

---

### En qué trabajo

| | Qué | Cómo se sabe que sirve |
|---|---|---|
| **Agentes de IA en campo** | Bot de voz para portabilidad telefónica (LiveKit) que atendió llamadas reales en un centro de contacto | Conversión medida en campo |
| | Campañas conversacionales sobre RCS con IA para **Bait** y los **Charros de Jalisco**; captura por QR con envío RCS automático, montada en vivo en un evento | Tasa de lectura y de respuesta reales, no la promesa del proveedor |
| **Analítica que decide** | Rentabilidad por sucursal de la red de tiendas **Bait (Walmart)**: break-even, modelos estocásticos y criterio de cierres | Para decisiones de dirección |
| | Casos de negocio de MVNO para **Tiendas Neto** y **Farmacias Similares**; máquina de adquisición para una tarjeta de crédito de **BBVA** | Auditados hasta el flujo después de impuestos, no el de la lámina |
| **Herramientas que la gente usa** | Homologador de catálogos de obra contra el tabulador oficial de la **CDMX** | En producción |
| | Dashboards ejecutivos de mensajería A2P (SMS/RCS) para revisión con cliente y pipelines de datos sobre el punto de venta | Revisados con el cliente |
| **El entorno de trabajo con IA** | [Kit Chema](https://github.com/chemaw8/claude-kit-chema), mi propio harness de agentes y mi sistema operativo, [chemarchy](https://github.com/chemaw8/chemarchy-repo) | Ver abajo |

---

### Kit Chema: estándar de calidad para Claude Code, medido

[![Kit Chema](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fraw.githubusercontent.com%2Fchemaw8%2Fclaude-kit-chema%2Fmain%2F.claude-plugin%2Fplugin.json&query=%24.version&label=kit-chema&prefix=v&color=2b7a4b)](https://github.com/chemaw8/claude-kit-chema)
[![Licencia MIT](https://img.shields.io/badge/licencia-MIT-5d6873)](https://github.com/chemaw8/claude-kit-chema/blob/main/LICENSE)
[![En español](https://img.shields.io/badge/idioma-espa%C3%B1ol-5d6873)](https://github.com/chemaw8/claude-kit-chema)

La mayoría de los "kits" para agentes son prosa bien redactada que nadie verificó. **Éste está medido, y las mediciones se vuelven a correr cuando algo cambia:**

| Qué | Medición |
|---|---|
| Las skills se disparan cuando deben | **27/27**, incluidas 7 fronteras entre dominios vecinos, y con las **70 skills** que compiten de verdad, no en laboratorio |
| El que verifica el trabajo, verificado | **28/28, cero falsos positivos**, incluidas 12 trampas escritas por agentes adversarios |
| El council muerde, no decora | Rechazó por unanimidad **una skill que yo mismo propuse** |
| Las reglas también se retiran | La v1.34 **quitó una regla del núcleo** con el criterio de retiro con que había entrado: a los 25 días no movió el patrón que debía corregir |
| Nada sube sin revisión | Gate de push: pruebas en un worktree aislado y un revisor de **otro modelo** antes de cada `git push` |
| Sabe cuándo **no** hacer algo | Cinco propuestas de mejora medidas y **descartadas** en vez de acumuladas |

→ **[github.com/chemaw8/claude-kit-chema](https://github.com/chemaw8/claude-kit-chema)** · núcleo de reglas + 9 skills de dominio + 4 subagentes + 5 hooks + council · en español

---

### Proyectos públicos

| Repo | Qué es |
|---|---|
| [**claude-kit-chema**](https://github.com/chemaw8/claude-kit-chema) | El estándar de arriba: reglas, skills, subagentes, hooks y su banco de mediciones |
| [**chemarchy-repo**](https://github.com/chemaw8/chemarchy-repo) | Repositorio pacman firmado de chemarchy, mi sistema operativo personal sobre Arch Linux |
| [**aureus-quant-engine**](https://github.com/chemaw8/aureus-quant-engine) | Motor de backtesting y paper trading cuantitativo, tipado y probado: ensamble bayesiano de señales y detección de régimen con HMM |

---

### Cómo trabajo

- **Medir antes que opinar.** Si una afirmación mueve una decisión, va con su número y su fuente. "Se siente más rápido" no es un dato.
- **Terminado significa verificado.** Código ejecutado, cifras recalculadas, fuentes abiertas. Un "listo" falso cuesta más que un "me faltó esto".
- **Evaluación crítica antes que complacencia.** Detectar un error en la propuesta de quien me pide algo y callarlo es el peor fallo posible.
- **Esfuerzo proporcional al riesgo.** No todo merece un panel de revisión; lo que va a dirección o mueve dinero, sí.

---

### Herramientas

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-Postgres%20%C2%B7%20MySQL-336791?logo=postgresql&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude%20Code%20%C2%B7%20Agent%20SDK-D97757?logo=anthropic&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-5d6873)
![RAG local](https://img.shields.io/badge/RAG%20local-embeddings%20%2B%20reranker-2b7a4b)
![LiveKit](https://img.shields.io/badge/LiveKit-1f2933)
![Rust](https://img.shields.io/badge/Rust-000000?logo=rust&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Arch Linux](https://img.shields.io/badge/Arch%20Linux-1793D1?logo=archlinux&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?logo=vercel&logoColor=white)

---

<sub>Actuaría @ ITAM · Ciudad de México · <a href="https://github.com/chemaw8/claude-kit-chema">Kit Chema</a></sub>
