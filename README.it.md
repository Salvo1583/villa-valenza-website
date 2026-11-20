<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:2C5364&height=180&section=header&text=Villa%20Valenza&fontSize=40&fontColor=ffffff&fontAlignY=36&desc=Sito%20web%20e%20prenotazioni%20per%20una%20villa%20vacanze&descSize=18&descAlignY=58" alt="Villa Valenza" width="100%" />
</p>

<p align="center"><a href="README.md">🇬🇧 English</a> · <b>🇮🇹 Italiano</b></p>

<p align="center">
  <img src="https://img.shields.io/badge/codice-privato-555555?style=for-the-badge&logo=github" alt="Codice privato" />
  <img src="https://img.shields.io/badge/vetrina-progetto-36BCF7?style=for-the-badge" alt="Vetrina del progetto" />
</p>

> [!NOTE]
> Questo repository è una **vetrina del progetto**: il codice sorgente è privato. Una demo è disponibile su richiesta.

## 🧭 Panoramica

Sito completo per **Villa Valenza**, villa per le vacanze a Favara (Agrigento), con un **sistema di prenotazione multi-tipo**, galleria fotografica, recensioni e un pannello di amministrazione per gestire tutto.

*Progetto per un cliente.*

## ✨ Funzionalità principali

- 🏡 **Sito pubblico**: galleria, appartamenti, recensioni, servizi, FAQ e contatti
- 📅 **Prenotazioni di più tipi**: singoli appartamenti, villa in esclusiva, piscina privata, eventi in giardino
- 🧩 **Regole di disponibilità**: ogni tipo di prenotazione blocca automaticamente quelli in conflitto nelle stesse date, mentre gli appartamenti restano indipendenti tra loro
- 🧾 **Generazione PDF** dei riepiloghi di prenotazione
- 🔐 **Pannello admin** per gestire prenotazioni e disponibilità
- 🚀 **Pubblicato su Vercel**

## 🏗️ Logica delle prenotazioni

```mermaid
flowchart LR
    V[Villa in esclusiva] -->|blocca| ALL[Tutto]
    E[Evento in giardino] -->|blocca| ALL
    B[Camera / appartamento] -->|blocca| P[Piscina privata]
    B -->|blocca| E2[Evento in giardino]
    P -->|blocca| B2[Camere]
```

## 🧰 Tecnologie

![Next.js](https://img.shields.io/badge/Next.js_14-000000?style=flat&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white)

## 📬 Contatti

Realizzato da **Salvatore Cutaia**, ingegnere informatico specializzato in agenti AI e automazioni.

[![GitHub](https://img.shields.io/badge/GitHub-Salvo1583-181717?style=flat&logo=github)](https://github.com/Salvo1583)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Salvatore_Cutaia-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/salvatore-cutaia-6047b0155/)
[![Website](https://img.shields.io/badge/Website-neuralform.it-111111?style=flat&logo=googlechrome&logoColor=white)](https://neuralform.it/)
