<div align="center">

<img src="banner.svg" width="100%" alt="Miguel Vivar Farfán — CEO & Tech Lead" />

<br/><br/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=22&duration=2800&pause=900&color=00D68F&center=true&vCenter=true&width=760&lines=Shipping+Odoo+18+Enterprise+en+Corporaci%C3%B3n+Inocua;Escalando+LicitaYa+tras+el+ISC+2026+Tarapoto;Arquitecturas+FullStack+%2B+Microservicios+%2B+IA;AWS+Certified+%7C+K8s+%7C+LLM+Agents+%7C+MCP" alt="Typing SVG" />
</a>

<br/><br/>

<p>
  <img src="https://img.shields.io/badge/status-shipping-00D68F?style=for-the-badge&labelColor=000000&logoColor=000000" />
  <img src="https://img.shields.io/badge/based_in-Ica,_Perú-000000?style=for-the-badge&labelColor=00D68F&logoColor=000000" />
  <img src="https://img.shields.io/badge/focus-ERP_%7C_AI_%7C_GovTech_%7C_Cloud-00D68F?style=for-the-badge&labelColor=000000" />
</p>

<p>
  <a href="https://vivar.visox.tech/" target="_blank"><img src="https://img.shields.io/badge/Portafolio-000000?style=for-the-badge&logo=vercel&logoColor=00D68F" /></a>
  <a href="https://visox.tech/" target="_blank"><img src="https://img.shields.io/badge/Visox-000000?style=for-the-badge&logo=vercel&logoColor=00D68F" /></a>
  <a href="https://linkedin.com/in/miguel-vivar-farfan" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-000000?style=for-the-badge&logo=linkedin&logoColor=00D68F" /></a>
  <a href="mailto:miguelvivarfarfan@gmail.com"><img src="https://img.shields.io/badge/Gmail-000000?style=for-the-badge&logo=gmail&logoColor=00D68F" /></a>
</p>

</div>

<br/>

## ⚡ Quick facts

| | |
|---|---|
| 🎓 **Educación** | Ingeniería de Sistemas — UNICA (Ica, Perú) · Tercio Superior |
| 🏛️ **CEO & Tech Lead** | [LicitaYa](https://vivar.visox.tech/) — SaaS B2B de automatización para SEACE |
| ⚙️ **Co-Founder & Tech Lead** | Visox — consultoría de software e ingeniería de sistemas |
| 🧩 **Consultor ERP** | Corporación Inocua — Odoo 18 Enterprise (CRM, Ventas, Compras) |
| 🤖 **Software Developer** | ASU Digital S.A.C. — pipelines de IA Generativa / MinIO / K8s |
| 🌐 **Organizer** | GDG Ica — Google Developer Groups |
| 📜 **Certificaciones** | AWS Certified · DeepTech Bootcamp (individual, top score) |

<br/>

<div align="center">

<img src="https://img.shields.io/badge/10%2B-Proyectos_entregados-000000?style=for-the-badge&labelColor=00D68F&logoColor=000000" />
<img src="https://img.shields.io/badge/99.9%25-Uptime_promedio-000000?style=for-the-badge&labelColor=00D68F&logoColor=000000" />
<img src="https://img.shields.io/badge/50%25%2B-Ahorro_operativo_cliente-000000?style=for-the-badge&labelColor=00D68F&logoColor=000000" />
<img src="https://img.shields.io/badge/250k%2B-Líneas_de_código-000000?style=for-the-badge&labelColor=00D68F&logoColor=000000" />

<sub>Métricas agregadas de los proyectos entregados vía Visox</sub>

</div>

<br/>

```typescript
interface TechLeader {
  readonly name: string;
  location: string;
  education: string;
  roles: Role[];
  currentSprint: string[];
  stack: TechStack;
}

interface Role {
  title: string;
  org: string;
  since: `${number}-${number}`;
}

type TechStack = Record<
  "languages" | "frontend" | "backend" | "data" | "cloud" | "ai",
  string[]
>;

const miguel: TechLeader = {
  name: "Miguel Alonso Vivar Farfán",
  location: "Ica, Perú 🇵🇪",
  education: "Ingeniería de Sistemas — UNICA",
  roles: [
    { title: "CEO & Tech Lead", org: "LicitaYa",           since: "2025-12" },
    { title: "ERP Consultant",  org: "Corporación Inocua", since: "2026-05" },
    { title: "Software Dev",    org: "ASU Digital S.A.C.", since: "2025-08" },
    { title: "Organizer",       org: "GDG Ica",            since: "2025-05" },
  ],
  currentSprint: [
    "🚀 Escalando LicitaYa post-ISC 2026 Tarapoto",
    "🧩 Cerrando Go-Live de Odoo 18 Enterprise (Corporación Inocua)",
    "🤖 Optimizando pipelines de IA generativa (DeepSeek + Whisper) en ASU Digital",
  ],
  stack: {
    languages: ["TypeScript", "JavaScript", "Python", "Java", "SQL"],
    frontend:  ["Next.js", "React", "Astro", "TailwindCSS"],
    backend:   ["Node.js", "Express", "Spring Boot", "FastAPI"],
    data:      ["PostgreSQL", "MongoDB", "MySQL", "Redis"],
    cloud:     ["AWS", "Docker", "Kubernetes", "Azure", "Railway"],
    ai:        ["LLM Agents", "DeepSeek", "Whisper", "n8n", "MCP"],
  },
};

export default miguel; // siempre shippeando
```

<br/>

## 🕒 Línea de tiempo

```
2025 ─┬─ May   GDG Ica (Organizer) · InnovaTech Ica (Lead Front-End)
      ├─ Jun   Sistema de Gestión Académica — Tech Lead (7 devs, Scrum)
      ├─ Ago   ASU Digital S.A.C. (Software Dev) · DeployGuru (FullStack Node.js)
      ├─ Dic   LicitaYa — fundación como CEO & Tech Lead
2026 ─┼─ May   Corporación Inocua — Consultor ERP (Odoo 18 Enterprise)
      └─ Jul   LicitaYa finalista ISC 2026 (Tarapoto) · Go-Live Odoo en curso
```

<br/>

## 🧭 Ejecutando en producción

<table>
<tr>
<td width="50%" valign="top">

### 🏛️ LicitaYa — CEO & Tech Lead
`Dic 2025 — Actualidad`
Plataforma SaaS B2B que automatiza la generación de anexos legales para compras públicas (**SEACE**), reduciendo el riesgo de descalificación para MYPES. Arquitectura FullStack con **Next.js + TypeScript** en frontend y **Node.js/Express + Prisma ORM** en backend, orquestada en **Docker** y **Kubernetes (k3s)**. Fase Beta con **15 empresas** activas en la región y **finalista en el ISC 2026 (Tarapoto)**.

### 🧩 Corporación Inocua — Consultor ERP
`May 2026 — Actualidad`
Auditoría técnica y reingeniería del módulo **CRM en Odoo 18 Enterprise** bajo **Gap Analysis** y **BPM** (flujos AS-IS/TO-BE), eliminando cotizaciones huérfanas y garantizando trazabilidad del pipeline de ventas. Activación de **AI Lead Scoring**, integración multicanal (WhatsApp Corporativo) y dashboards de KPIs (Win Rate, Forecasting) sobre un roadmap ágil de 4 semanas.

</td>
<td width="50%" valign="top">

### ⚡ ASU Digital S.A.C. — Desarrollador de Software
`Ago 2025 — Actualidad`
Microservicios con **FastAPI (Python)** desplegados en **Docker/Kubernetes** sobre servidor GPU dedicado (CUDA 12.4 + cuDNN 9). Pipelines de **IA Generativa** (DeepSeek + Whisper/Faster-Whisper) para análisis y transcripción automatizada, almacenamiento en **MinIO**, control de acceso vía **Redis**, y automatización end-to-end con **n8n** + bots de Discord.

### 🌐 GDG Ica — Organizer & Community Ops
`May 2025 — Actualidad`
Desarrollo de la web oficial con **Astro + TailwindCSS + TypeScript** bajo prácticas **Scrum**, documentación técnica y arquitectura modular orientada a mantenibilidad a largo plazo.

</td>
</tr>
</table>

<br/>

## 🚀 Proyecto insignia

<table>
<tr>
<td width="100%">

### 🎓 Sistema de Gestión Académica por Microservicios — Tech Lead & FullStack Architect
`Jun 2025 — Actualidad`

Arquitectura desacoplada de Intranet y Matrícula: **Next.js** en frontend, ecosistema de microservicios con **Spring Boot 3.5 + PostgreSQL** en backend, seguridad con **JWT + RBAC**, y CI/CD sobre **Railway** con despliegues continuos sin downtime. Lideré un escuadrón ágil de **7 desarrolladores** bajo Scrum, definiendo estándares de code review y arquitectura de soluciones.

</td>
</tr>
</table>

<br/>

## 📜 Trayectoria

<table>
<tr><td width="70%"><b>DeployGuru</b> — FullStack Node.js</td><td width="30%"><code>Ago 2025 – Oct 2025</code></td></tr>
<tr><td colspan="2">Integración IMAP para ingestión de correos del sector asegurador, clasificación automática de eventos críticos y scraping resiliente con <b>Puppeteer</b> para enriquecimiento de expedientes (data enrichment).</td></tr>
<tr><td width="70%"><b>InnovaTech Ica</b> — Lead Front-End Engineer</td><td width="30%"><code>May 2025 – Actualidad</code></td></tr>
<tr><td colspan="2">Landing page del evento con <b>Astro + TailwindCSS</b>, despliegue continuo en GitHub Pages y estrategia visual responsiva coordinada con marketing.</td></tr>
</table>

<br/>

## 📌 Repositorios destacados

<div align="center">
  <a href="https://github.com/MiguelVivar/EscuelaPosgradoUNICA">
    <img src="https://github-stats-extended.vercel.app/api/pin/?username=MiguelVivar&repo=EscuelaPosgradoUNICA&theme=dark&hide_border=true&bg_color=0A0A0A&title_color=00D68F&text_color=DFF7EE&icon_color=00D68F" />
  </a>
  <a href="https://github.com/MiguelVivar/GeneradorExamenesPython">
    <img src="https://github-stats-extended.vercel.app/api/pin/?username=MiguelVivar&repo=GeneradorExamenesPython&theme=dark&hide_border=true&bg_color=0A0A0A&title_color=00D68F&text_color=DFF7EE&icon_color=00D68F" />
  </a>
</div>

<br/>

## 🛠️ Stack completo

<div align="center">

**Lenguajes**
<br/>
<img src="https://skillicons.dev/icons?i=ts,js,python,java&theme=dark&perline=4" />

**Frontend**
<br/>
<img src="https://skillicons.dev/icons?i=nextjs,react,astro,tailwind,html,css&theme=dark&perline=6" />

**Backend**
<br/>
<img src="https://skillicons.dev/icons?i=nodejs,express,spring,fastapi,php&theme=dark&perline=5" />

**Bases de Datos**
<br/>
<img src="https://skillicons.dev/icons?i=postgres,mongodb,mysql,redis&theme=dark&perline=4" />
<img src="https://img.shields.io/badge/SQL_Server-000000?style=flat-square&logo=microsoftsqlserver&logoColor=00D68F" />

**Cloud & DevOps**
<br/>
<img src="https://skillicons.dev/icons?i=docker,kubernetes,aws,azure,nginx,git&theme=dark&perline=6" />
<img src="https://img.shields.io/badge/CI%2FCD-000000?style=flat-square&logo=githubactions&logoColor=00D68F" />
<img src="https://img.shields.io/badge/Railway-000000?style=flat-square&logo=railway&logoColor=00D68F" />

**IA, Automatización & Herramientas**
<br/>
<img src="https://img.shields.io/badge/LLM_%2F_IA_Generativa-000000?style=flat-square&color=00D68F" />
<img src="https://img.shields.io/badge/DeepSeek-000000?style=flat-square&logoColor=00D68F" />
<img src="https://img.shields.io/badge/Whisper_%2F_Faster--Whisper-000000?style=flat-square&logoColor=00D68F" />
<img src="https://img.shields.io/badge/n8n-000000?style=flat-square&logo=n8n&logoColor=00D68F" />
<img src="https://img.shields.io/badge/Puppeteer-000000?style=flat-square&logo=puppeteer&logoColor=00D68F" />
<img src="https://img.shields.io/badge/MinIO-000000?style=flat-square&logo=minio&logoColor=00D68F" />
<img src="https://img.shields.io/badge/Prisma_ORM-000000?style=flat-square&logo=prisma&logoColor=00D68F" />
<img src="https://img.shields.io/badge/JWT_%2F_RBAC-000000?style=flat-square&logo=jsonwebtokens&logoColor=00D68F" />
<img src="https://img.shields.io/badge/Odoo_18_Enterprise-000000?style=flat-square&logo=odoo&logoColor=00D68F" />
<img src="https://img.shields.io/badge/Figma-000000?style=flat-square&logo=figma&logoColor=00D68F" />
<img src="https://img.shields.io/badge/AWS_Certified-000000?style=flat-square&logo=amazonaws&logoColor=00D68F" />

</div>

<br/>

## 📊 Métricas

<div align="center">
  <img src="https://github-stats-extended.vercel.app/api?username=MiguelVivar&show_icons=true&theme=dark&hide_border=true&bg_color=0A0A0A&title_color=00D68F&icon_color=00D68F&text_color=DFF7EE&count_private=true" height="165" alt="stats graph" />
  <img src="https://github-stats-extended.vercel.app/api/top-langs/?username=MiguelVivar&layout=compact&theme=dark&hide_border=true&bg_color=0A0A0A&title_color=00D68F&text_color=DFF7EE&langs_count=8" height="165" alt="languages graph" />
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com/?user=MiguelVivar&theme=dark&hide_border=true&background=0A0A0A&ring=00D68F&fire=00D68F&currStreakLabel=00D68F&sideNums=DFF7EE&sideLabels=7C8985&dates=5A6A64" alt="streak stats"/>
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=MiguelVivar&theme=react-dark&bg_color=0A0A0A&color=00D68F&line=00D68F&point=ffffff&hide_border=true" width="100%" alt="activity graph" />
</div>

<div align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=MiguelVivar&theme=github_dark" height="150" alt="repos por lenguaje" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=MiguelVivar&theme=github_dark" height="150" alt="lenguaje con más commits" />
</div>

<div align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=MiguelVivar&theme=github_dark&utcOffset=-5" height="150" alt="horario más productivo (UTC-5, Perú)" />
</div>

<div align="center">
  <img src="https://github-trophies.vercel.app/?username=MiguelVivar&theme=matrix&no-frame=true&no-bg=true&margin-w=4&row=1&column=7" alt="trophies" />
</div>

<br/>

> *"Si no puedo mostrarlo en el standup de mañana, no lo estoy construyendo bien."*
> **— M. Vivar**

<div align="center">

### 📫 ¿Construyendo algo en ERP, GovTech o IA? Hablemos.

<a href="https://linkedin.com/in/miguel-vivar-farfan" target="_blank"><img src="https://img.shields.io/badge/Conectemos_en_LinkedIn-000000?style=for-the-badge&logo=linkedin&logoColor=00D68F" /></a>
<a href="mailto:miguelvivarfarfan@gmail.com"><img src="https://img.shields.io/badge/Escríbeme-000000?style=for-the-badge&logo=gmail&logoColor=00D68F" /></a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=miguelvivar&label=Vistas+del+Perfil&color=00D68F&style=for-the-badge&labelColor=000000" alt="views" />

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B0F0D,100:00D68F&height=100&section=footer" width="100%"/>
