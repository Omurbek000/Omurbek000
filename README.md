<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:050505,45:16112b,75:302b63,100:050505&height=230&section=header&text=AZIAT%20OMURBEK&fontSize=56&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=BACKEND%20%E2%80%A2%20AI%20ENGINEER&descAlignY=60&descSize=20" width="100%"/>

<br>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=21&duration=2200&pause=700&color=A78BFA&center=true&vCenter=true&width=750&lines=%3E+initializing+backend+system...;%3E+loading+AI+pipeline...;%3E+connecting+PostgreSQL...;%3E+starting+Celery+workers...;%3E+SYSTEM+ONLINE+%E2%9C%93" />

<br><br>

<img src="https://img.shields.io/badge/BACKEND-ONLINE-7C3AED?style=for-the-badge&labelColor=080808"/>
<img src="https://img.shields.io/badge/AI-ONLINE-7C3AED?style=for-the-badge&labelColor=080808"/>
<img src="https://img.shields.io/badge/DATABASE-ONLINE-7C3AED?style=for-the-badge&labelColor=080808"/>
<img src="https://img.shields.io/badge/CELERY-ONLINE-7C3AED?style=for-the-badge&labelColor=080808"/>

</div>

---

<div align="center">

```text
╔══════════════════════════════════════════════════════════════╗
║                    AZIAT OMURBEK // DEV                     ║
╠══════════════════════════════════════════════════════════════╣
║                                                              ║
║   ROLE        Backend / AI Engineer                          ║
║   PRIMARY     Python / Django / DRF                          ║
║   DATABASE    PostgreSQL / Redis                              ║
║   ASYNC       Celery                                         ║
║   AI          Whisper / NLLB / TTS                           ║
║   INFRA       Docker / Linux                                 ║
║                                                              ║
║   STATUS      ● BUILDING  •  47 repos  •  Bishkek 🇰🇬          ║
║                                                              ║
╚══════════════════════════════════════════════════════════════╝
```

</div>

# `> whoami`

I'm a **Backend / AI Engineer** building real-world systems — from `delivery` and `car rental` marketplaces to **AI dubbing**.

```text
        BACKEND
           │
           ▼
       ┌───────┐
       │  API  │
       └───┬───┘
           │
     ┌─────┴─────┐
     ▼           ▼
 DATABASE       QUEUE
     │           │
     │           ▼
     │         WORKER
     │           │
     └─────┬─────┘
           ▼
        AI / ML
```

**Focus:** `Django 5.2` • `DRF + JWT` • `PostgreSQL + Redis + Celery` • `Whisper / NLLB / TTS` • `Docker` — **26-37 tests • production ready**

[📍 Bishkek](https://github.com/Omurbek000) • [📧 dseba436@gmail.com](mailto:dseba436@gmail.com) • [🚀 Service](https://github.com/Omurbek000/Service) • [🚗 AVTO Demo](https://omurbek000.github.io/auto_project/presentation_menu.html)

---

# `> core_stack`

<div align="center">

<img src="https://skillicons.dev/icons?i=python,django,fastapi,postgres,redis,docker,linux,git,github" />

<br><br>

<img src="https://skillicons.dev/icons?i=react,typescript,vite" />

</div>

<br>

```text
BACKEND       ████████████████████  Python / Django / DRF + JWT
DATABASE      ██████████████████░░  PostgreSQL / Redis
ASYNC         █████████████████░░░  Celery
AI            ████████████████░░░░  Whisper / NLLB / TTS / FFmpeg
INFRA         ███████████████░░░░░  Docker / Linux
FRONTEND      ████████████░░░░░░░░  React 18 / TypeScript / Vite
TESTING       █████████████░░░░░░░  Pytest / Django Tests  26-37
```

---

# `> featured_projects`

## `01 // AutoDub — AI VIDEO DUBBING`

<div align="center">

### 🤖 Service — флагман

`WHISPER` `NLLB` `TTS` `CELERY` `REDIS` `FFMPEG` `37 Tests`

> Загружаешь видео → `en` → выбираешь `ru` → забираешь `.srt` + `dubbed.mp4` — `Whisper → pyannote → NLLB → edge-tts/CosyVoice → atempo → mux`

</div>

```text
┌─────────┐
│  VIDEO  │
└────┬────┘
     ▼
┌──────────────┐
│   WHISPER    │  Speech→Text  (faster-whisper base)
└──────┬───────┘
       ▼
┌──────────────┐
│     NLLB     │  Translation  (nllb-200)
└──────┬───────┘
       ▼
┌──────────────┐
│     TTS      │  edge-tts / CosyVoice3
└──────┬───────┘
       ▼
┌──────────────┐
│    FFMPEG    │  atempo + mux
└──────┬───────┘
       ▼
┌──────────────┐
│ DUBBED VIDEO │
└──────────────┘
```

<div align="center">

[![Service](https://img.shields.io/badge/Service-AutoDub_AI-7C3AED?style=for-the-badge&logo=python&logoColor=white)](https://github.com/Omurbek000/Service) [![Tests](https://img.shields.io/badge/tests-37%2F37-10B981?style=flat-square)](https://github.com/Omurbek000/Service)

[🎬 Presentation](https://github.com/Omurbek000/Service/blob/main/presentation.html) • [📋 PLAN](https://github.com/Omurbek000/Service/blob/main/PLAN.md) • [GitHub](https://github.com/Omurbek000/Service) • `GET /health/`

</div>

---

## `02 // AVTO — CAR RENTAL MARKETPLACE`

<div align="center">

### 🚗 60+ endpoints • каталог → бронь → чат → KPI

`DJANGO` `DRF` `POSTGRESQL` `REACT` `TYPESCRIPT` `VITE`

</div>

```text
              CLIENT (React 18 / TS / Vite)
                       │
                       ▼
                    REST API (DRF + JWT)
                       │
           ┌───────────┴───────────┐
           ▼                       ▼
      BOOKING (защита              CHAT
      от гонки)               по аренде
           │
           ▼
      PostgreSQL + KPI Dashboard
```

`🚘 Cars` · `🔎 Search + Filters` · `📅 Booking + Calendar` · `🛡️ Availability` · `💬 Chat` · `⭐ Reviews` · `📊 KPI`

<div align="center">

[🎬 Demo](https://omurbek000.github.io/auto_project/presentation_menu.html) • [GitHub](https://github.com/Omurbek000/auto_project)

</div>

---

## `03 // Onigiri — FOOD DELIVERY API`

<div align="center">

### 🍣 22 endpoints • 26 tests • один ресторан, 3 клика до заказа

`PYTHON` `DJANGO` `DRF` `JWT` `POSTGRESQL`

</div>

```text
USER → AUTH (JWT) → MENU (Category→Dish) → CART → ORDER (Promo → OrderItem) → DELIVERY (created→delivered)
```

> `Category → Dish → Favorite → Promo → Order → OrderItem` — `django-filter` + `PageNumberPagination 10` + `IsOwnerOrAdmin`

<div align="center">

[🎨 UI mockup](https://github.com/Omurbek000/delivery/blob/main/ui-mockup-main.html) • [GitHub](https://github.com/Omurbek000/delivery) • [Swagger](https://github.com/Omurbek000/delivery#api--22-эндпоинта)

</div>

---

> Ещё 3 TOP в пине: [`IT-online`](https://github.com/Omurbek000/IT-online) • [`freelancehub-api`](https://github.com/Omurbek000/freelancehub-api) • [`Etno_Practic`](https://github.com/Omurbek000/Etno_Practic) — все `MIT` + `topics` (как у топов 2026)

---

# `> ai_lab`

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:090909,100:24124d&height=90&text=AI%20MODEL%20%E2%86%92%20WORKER%20%E2%86%92%20API&fontSize=25&fontColor=ffffff" width="90%"/>

</div>

I turn AI models into **usable backend services**:

```text
  AI MODEL → WORKER (Celery) → REDIS QUEUE → DJANGO API → CLIENT
  Whisper → NLLB → TTS → FFmpeg → Service API
```

`Whisper → NLLB → TTS → PyTorch → FFmpeg → Celery → Redis`

---

# `> engineering_principles`

```text
┌─────────────────────────────────────────────┐
│  01  CLEAN ARCHITECTURE                     │
│  02  ASYNC PROCESSING  (Celery + Redis)     │
│  03  DATABASE FIRST    (Postgres + FK)      │
│  04  API DESIGN        (DRF + JWT)          │
│  05  TESTING           (26-37 tests)        │
│  06  PRODUCTION MINDSET (Docker + health)   │
└─────────────────────────────────────────────┘
```

---

# `> system_status`

<div align="center">

| SYSTEM          |  STATUS  |
| :-------------- | :------: |
| 🐍 Python       | `ONLINE` |
| 🌐 Django / DRF | `ONLINE` |
| 🗄️ PostgreSQL  | `ONLINE` |
| ⚡ Redis         | `ONLINE` |
| 🔄 Celery       | `ONLINE` |
| 🐳 Docker       | `ONLINE` |
| 🤖 AI Pipeline  | `ONLINE` |
| 🎥 FFmpeg       | `ONLINE` |

</div>

---

# `> github_stats`

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=Omurbek000&show_icons=true&hide_border=true&theme=tokyonight&bg_color=050505&title_color=A78BFA&icon_color=A78BFA&text_color=E5E7EB"/>

<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Omurbek000&layout=compact&hide_border=true&theme=tokyonight&bg_color=050505&title_color=A78BFA&text_color=E5E7EB"/>

</div>

<br>

<div align="center">

![Snake animation](https://raw.githubusercontent.com/Omurbek000/Omurbek000/output/github-contribution-grid-snake.svg)

</div>

---

# `> connect`

<div align="center">

<a href="mailto:dseba436@gmail.com">
<img src="https://img.shields.io/badge/EMAIL-7C3AED?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

<a href="https://github.com/Omurbek000">
<img src="https://img.shields.io/badge/GITHUB-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<br><br>

```text
> keep_building()
```

<br>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:050505,45:16112b,75:302b63,100:050505&height=130&section=footer" width="100%"/>

</div>
