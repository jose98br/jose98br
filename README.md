<!-- Cabecera animada -->
![Header](https://capsule-render.vercel.app/api?type=waving&height=230&section=header&text=Jose%20Manuel%20Benitez%20Ruiz&fontSize=44&fontColor=ffffff&fontAlignY=38&desc=Python%20Developer%20%7C%20Full%20Stack%20%7C%20Data%20Science%20y%20IA&descAlignY=58&descSize=18&color=0:0f766e,100:1f2937&animation=twinkling)

<!-- Texto que se escribe solo -->
<p align="center">
  <a href="https://jugaly.es">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=900&color=14B8A6&center=true&vCenter=true&width=620&lines=Hola!+Soy+Jose+Manuel+%F0%9F%91%8B;Software+Engineer+en+VUMI+%F0%9F%92%BC;Full+Stack+Developer+%7C+React+%2B+Node.js;Creador+de+Jugaly+%F0%9F%8E%AE+jugaly.es;Data+Science+%26+IA+con+Python+%F0%9F%A4%96;Automatizaciones+con+n8n+%E2%9A%A1" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://jugaly.es"><img src="https://img.shields.io/badge/Jugaly-Jugar_ahora-0f766e?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Jugaly"></a>
  <a href="https://jose98br.github.io/porfolio/"><img src="https://img.shields.io/badge/Portfolio-Web-1f2937?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/jose-manuel-benitez-ruiz/"><img src="https://img.shields.io/badge/LinkedIn-Perfil-0A66C2?style=for-the-badge&logo=linkedin" alt="LinkedIn"></a>
  <a href="mailto:josemanuelbenitezruiz14@gmail.com"><img src="https://img.shields.io/badge/Email-Contacto-e7a651?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

<p align="center">
  <img src="https://visitor-badge.laobi.icu/badge?page_id=jose98br.jose98br&left_text=Visitas%20al%20perfil&left_color=%231f2937&right_color=%230f766e" alt="Visitas al perfil" />
</p>

---

## 👨‍💻 Sobre mí

<img align="right" width="300" src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" alt="Coding" />

```python
class JoseManuel:
    ubicacion = "Palma del Rio, Cordoba, Spain"
    rol = "Software Engineer @ VUMI"
    estudiando = "Master en Data Science & Desarrollo de IA - Evolve Academy"
    proyecto_actual = "Jugaly -> https://jugaly.es"
    me_interesa = ["Desarrollo web/full stack", "Automatizacion", "IA aplicada"]
```

- 🌱 Desarrollador con experiencia en Python, desarrollo web y movil, automatizacion de procesos con n8n y APIs REST.
- 💼 Software Engineer en **[VUMI](https://www.vumi.io)**, software de consolidacion patrimonial para Family Offices.
- 🎮 Ahora mismo construyendo **[Jugaly](https://jugaly.es)**, mi plataforma de juegos web.
- 📫 Hablamos en [LinkedIn](https://www.linkedin.com/in/jose-manuel-benitez-ruiz/) o por [email](mailto:josemanuelbenitezruiz14@gmail.com).

<br clear="right" />

---

## 🚀 Proyectos destacados

### 🎮 Jugaly - Plataforma de juegos web

<p>
  <a href="https://jugaly.es"><img src="https://img.shields.io/badge/Demo-jugaly.es-0f766e?style=flat-square&logo=vercel&logoColor=white" alt="Demo" /></a>
  <img src="https://img.shields.io/badge/Estado-En_produccion-22c55e?style=flat-square" alt="En produccion" />
</p>

<p>
  <img src="https://skillicons.dev/icons?i=react,ts,vite,tailwind,nodejs,postgres,supabase,docker,vercel" alt="Stack de Jugaly" />
</p>

Plataforma de juegos para el navegador, sin descargas, pensada para partidas cortas desde el movil o el ordenador. Full stack: frontend en React y API REST propia con Fastify y PostgreSQL.

- ♟️ Domino, Ajedrez y Damas contra la maquina (3 niveles de dificultad), mas Solitario y Sudoku
- 🧠 Bots que se ejecutan en el navegador; el de ajedrez calcula en un Web Worker para no bloquear la interfaz
- 🔐 Registro con email o Google (JWT + OAuth) y modo invitado para jugar sin cuenta
- 🏆 Sistema de XP y niveles, historial de partidas y ranking publico por juego
- 🛡️ API REST con validacion (Zod), rate limiting y emails transaccionales (Resend)
- ☁️ Despliegue en Vercel (web y API) con Supabase como base de datos; entorno local con Docker

---

### 🏦 Banklog-IA - Diagnostico de fallos con IA (TFM)

<p>
  <img src="https://img.shields.io/badge/TFM-Master_Data_Science_y_IA-0f766e?style=flat-square" alt="TFM" />
</p>

<p>
  <img src="https://skillicons.dev/icons?i=py,fastapi,sklearn,aws,react,vite,tailwind" alt="Stack de Banklog-IA" />
  <img src="https://img.shields.io/badge/spaCy-09A3D5?style=for-the-badge&logo=spacy&logoColor=white" alt="spaCy" />
  <img src="https://img.shields.io/badge/Claude_API-D97757?style=for-the-badge&logo=anthropic&logoColor=white" alt="Claude API" />
</p>

Sistema hibrido de **ML + IA Generativa** que diagnostica automaticamente por que fallan las conexiones bancarias a partir de sus logs, para sustituir una revision manual que no escala.

- 🔎 **NER con spaCy** que extrae la informacion clave de cada log (entidad, modulo, fecha y codigo de error)
- 🌲 **Clasificador Random Forest** del tipo de fallo (login, timeout, captcha, cambio de HTML, mantenimiento...) con reentrenamiento y proteccion anti-regresion
- 📈 **Ranking de gravedad** transparente para priorizar las incidencias activas
- 🧠 **Explicacion con Claude + contexto RAG**: propone causa raiz y solucion en lenguaje natural
- 💬 **Chatbot** con tool use de la API de Anthropic para consultar el estado de las incidencias
- 🗂️ Pipeline de datos por capas (raw / processed / gold) con anonimizacion, Pandas, DuckDB y Parquet
- 🖥️ Panel web en React + Vite y API en FastAPI; IA configurable (Claude, Ollama local o stub sin coste)

---

### ⏱️ Laboro - Control de horas

<p>
  <img src="https://jose98br.github.io/porfolio/laboro-icon.svg" alt="Laboro logo" width="72" />
</p>

<p>
  <img src="https://skillicons.dev/icons?i=flutter,dart" alt="Stack de Laboro" />
</p>

**Periodo:** Ene 2026 - Feb 2026 · **Enfoque:** Offline-first, exportacion PDF y CSV

App gratuita para registrar jornadas por horas y calcular el cobro mensual. Funciona sin internet y sin cuentas.

- 💼 Hasta 3 trabajos activos
- ☕ Registro de horas con descansos no pagados
- 📅 Calendario con dias trabajados por color
- 📊 Informes por trabajo
- 📄 Exportacion rapida a PDF y CSV
- 🔒 Todo local, sin cuentas ni internet

---

### 🤖 Sports Bot - Resumen deportivo diario en Telegram

<p>
  <img src="https://skillicons.dev/icons?i=py,githubactions" alt="Stack del bot" />
  <img src="https://img.shields.io/badge/Telegram_Bot_API-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram" />
</p>

Bot que cada mañana envia a Telegram, de forma automatica, el resumen de futbol del dia y las noticias mas relevantes. Corre sin servidor: lo programa un cron de **GitHub Actions**.

- ⚽ Partidos del dia y proximas jornadas de LaLiga, Premier, Champions, Europa League, Bundesliga, Serie A y Ligue 1 (API de football-data.org)
- 🕖 Horarios convertidos a hora de España y fechas en español
- 📰 Noticias de futbol desde Google News RSS, ordenadas por prioridad (futbol español, polemica, resultados) y sin duplicados
- ⏰ Dos envios diarios automaticos (07:00 resumen y 07:05 noticias) y lanzamiento manual desde Actions
- 🔐 Tokens y claves guardados como secretos, nunca en el codigo

---

## 🛠️ Tecnologías

<table align="center">
  <tr>
    <td align="center"><b>Lenguajes</b></td>
    <td><img src="https://skillicons.dev/icons?i=py,ts,js,dart,html,css" alt="Lenguajes" /></td>
  </tr>
  <tr>
    <td align="center"><b>Frontend y movil</b></td>
    <td><img src="https://skillicons.dev/icons?i=react,vite,tailwind,flutter" alt="Frontend" /></td>
  </tr>
  <tr>
    <td align="center"><b>Backend</b></td>
    <td>
      <img src="https://skillicons.dev/icons?i=nodejs,fastapi,express,django,flask,prisma" alt="Backend" /><br />
      <img src="https://img.shields.io/badge/Fastify-000000?style=flat&logo=fastify&logoColor=white" alt="Fastify" />
    </td>
  </tr>
  <tr>
    <td align="center"><b>Bases de datos</b></td>
    <td><img src="https://skillicons.dev/icons?i=postgres,supabase,mongodb,redis" alt="Bases de datos" /></td>
  </tr>
  <tr>
    <td align="center"><b>Data Science & IA</b></td>
    <td>
      <img src="https://skillicons.dev/icons?i=sklearn" alt="scikit-learn" />
      <img src="https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white" alt="Pandas" />
      <img src="https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white" alt="NumPy" />
      <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white" alt="Jupyter" />
      <img src="https://img.shields.io/badge/spaCy-09A3D5?style=flat&logo=spacy&logoColor=white" alt="spaCy" />
      <img src="https://img.shields.io/badge/XGBoost-189FDD?style=flat" alt="XGBoost" />
      <img src="https://img.shields.io/badge/Claude_API-D97757?style=flat&logo=anthropic&logoColor=white" alt="Claude API" />
      <img src="https://img.shields.io/badge/Ollama-000000?style=flat&logo=ollama&logoColor=white" alt="Ollama" />
      <img src="https://img.shields.io/badge/DuckDB-FFF000?style=flat&logo=duckdb&logoColor=black" alt="DuckDB" />
    </td>
  </tr>
  <tr>
    <td align="center"><b>DevOps y herramientas</b></td>
    <td>
      <img src="https://skillicons.dev/icons?i=docker,aws,vercel,githubactions,git,github,postman,vscode,linux" alt="Herramientas" /><br />
      <img src="https://img.shields.io/badge/n8n-EA4B71?style=flat&logo=n8n&logoColor=white" alt="n8n" />
    </td>
  </tr>
</table>

---

## 📊 GitHub stats

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=jose98br&show_icons=true&theme=github_dark&hide_border=true&cache_seconds=86400" alt="GitHub stats" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=jose98br&layout=compact&theme=github_dark&hide_border=true&langs_count=8&cache_seconds=86400" alt="Top languages" />
</p>

<p align="center">
  <img height="170" src="https://streak-stats.demolab.com/?user=jose98br&theme=github-dark-blue&hide_border=true" alt="GitHub streak" />
</p>

<!-- Serpiente que se come tus contribuciones (la genera el workflow .github/workflows/snake.yml) -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/jose98br/jose98br/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/jose98br/jose98br/output/github-snake.svg" />
    <img alt="Serpiente de contribuciones" src="https://raw.githubusercontent.com/jose98br/jose98br/output/github-snake.svg" />
  </picture>
</p>

---

## 💼 Experiencia

<table>
  <tr>
    <td width="90" align="center"><a href="https://www.vumi.io"><img src="https://www.vumi.io/icon.png" alt="VUMI" width="64" /></a></td>
    <td>
      <b>Software Engineer</b> · <a href="https://www.vumi.io">VUMI</a><br />
      <sub>May 2026 - Actualidad</sub>
    </td>
  </tr>
  <tr>
    <td width="90" align="center">💻</td>
    <td>
      <b>Desarrollador Web y App + Automatizaciones</b> · AppyWeb<br />
      <sub>Feb 2025 - Ago 2025</sub>
    </td>
  </tr>
</table>

---

## 📫 Contacto

<p align="center">
  <a href="https://www.linkedin.com/in/jose-manuel-benitez-ruiz/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:josemanuelbenitezruiz14@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://jose98br.github.io/porfolio/"><img src="https://img.shields.io/badge/Portfolio-1f2937?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfolio" /></a>
  <a href="https://jugaly.es"><img src="https://img.shields.io/badge/Jugaly-0f766e?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Jugaly" /></a>
</p>

<!-- Pie animado -->
![Footer](https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0:0f766e,100:1f2937)
