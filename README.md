<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:2C5364&height=180&section=header&text=Villa%20Valenza&fontSize=40&fontColor=ffffff&fontAlignY=36&desc=Website%20%26amp%3B%20booking%20platform%20for%20a%20holiday%20villa&descSize=18&descAlignY=58" alt="Villa Valenza" width="100%" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/source-private-555555?style=for-the-badge&logo=github" alt="Source private" />
  <img src="https://img.shields.io/badge/project-showcase-36BCF7?style=for-the-badge" alt="Project showcase" />
</p>

> [!NOTE]
> This repository is a **project showcase**: the source code is private. A demo is available on request.

## 🧭 Overview

Full website for **Villa Valenza**, a holiday villa in Favara (Agrigento, Sicily), with a **multi-type booking system**, photo gallery, reviews and an admin panel to manage everything.

*Client project.*

## ✨ Key features

- 🏡 **Public site**: gallery, apartments, reviews, services, FAQ and contacts
- 📅 **Multi-type bookings**: single apartments, the whole villa, private pool, garden events
- 🧩 **Availability rules**: each booking type automatically blocks the ones it conflicts with on the same dates, while apartments stay independent from each other
- 🧾 **PDF generation** of booking summaries
- 🔐 **Admin panel** to manage bookings and availability
- 🚀 **Deployed on Vercel**

## 🏗️ Booking logic

```mermaid
flowchart LR
    V[Whole villa] -->|blocks| ALL[Everything]
    E[Garden event] -->|blocks| ALL
    B[Room / apartment] -->|blocks| P[Private pool]
    B -->|blocks| E2[Garden event]
    P -->|blocks| B2[Rooms]
```

## 🧰 Tech stack

![Next.js](https://img.shields.io/badge/Next.js_14-000000?style=flat&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white)

## 📬 Contact

Built by **Salvatore Cutaia**, Computer Engineer specialized in AI agents & automations.

[![GitHub](https://img.shields.io/badge/GitHub-Salvo1583-181717?style=flat&logo=github)](https://github.com/Salvo1583)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Salvatore_Cutaia-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/salvatore-cutaia-6047b0155/)
