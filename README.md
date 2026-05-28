# Hi, I'm Abran Paul 👋

**Full Stack Java Developer** · React Native · Spring Boot · Berlin, Germany

3.5+ years building enterprise Java applications and full-stack products.
Currently **open to Java backend, full stack, or mobile developer roles in Berlin** (or remote across Europe).

> Comfortable working in English-speaking international teams · German: B1

---

## 🚀 What I'm Building

### [Timeliner](https://github.com/Abran7411/timeliner) &nbsp;·&nbsp; *In active development — Play Store & App Store launch coming soon*

**Your whole trip. One timeline. Works offline.**

Every traveler knows the problem: photos in Google Photos, expenses in Splitwise, tickets buried in email, notes scattered everywhere. Timeliner brings everything into a single offline-first timeline designed for use **during** the trip — not just before or after it.

| Feature | What it does |
|---|---|
| 📸 Trip timeline | Moments with photos, GPS location, notes + timestamps in one scroll |
| 💸 Expense splitting | Shared costs with debt simplification — minimises transactions to settle |
| 📄 Travel documents | Flights, hotels, tickets stored and accessible in airplane mode |
| 👥 Multi-user trips | Friend groups sharing one trip with role-based data access |
| 📡 Offline-first | Auto-downloads documents in background — always available at the gate |

**Technical highlights worth knowing:**
- **Captive portal detection** — dual `isConnected` + `isInternetReachable` checks catch hotel/airport WiFi that shows connected but has no real internet
- **Background document caching** — files silently download on fetch and persist locally via `expo-file-system`; confirmed available via `FileSystem.getInfoAsync` before display (no false positives)
- **Debt simplification algorithm** — calculates the minimum number of transactions to settle a group trip
- **Supabase RPC + PostgreSQL functions** — multi-user trip access model without exposing raw table queries
- **Offline write blocking** — intentional V1 decision to prevent silent data loss on poor connections

**Stack:** React Native (Expo SDK 55) · Supabase (PostgreSQL, Auth, Storage) · React Navigation · Context API (OfflineContext, AuthContext) · EAS Build · Android Studio

**Status:** Android tested on physical device + emulator · iOS supported via Expo Go · Play Store + App Store release in progress

---

### [Ezhilagam](https://github.com/Abran7411/ezhilagam) &nbsp;·&nbsp; *Tamil literature learning app*

Bringing classical Tamil works — Thirukkural, Kamba Ramayanam, Bharathiyar — into a clean modern mobile experience.

**Stack:** React Native · Supabase · Expo Auth · Purple + Gold cultural UI theme

*Coming soon: audio playback, bookmarks, reading progress tracking*

---

## 🛠️ Tech Stack

**Languages**
`Java` `JavaScript` `TypeScript` `Kotlin` *(learning)*

**Backend**
`Spring Boot` `REST APIs` `Microservices` `PostgreSQL` `Supabase` `Node.js`

**Mobile**
`React Native` `Expo SDK 55` `EAS Build` `Android Studio`

**Frontend**
`React` `HTML` `CSS`

**DevOps & Tools**
`Docker` `Git` `Agile` `Scrum`

---

## 💼 Professional Background

**Software Engineer — Timelapse Informatics** *(3.5 years · Chennai, India)*

Built and maintained Java-based enterprise applications for ERP and logistics systems.
- Spring Boot microservices with RESTful APIs across logistics and finance domains
- Full-stack features integrating Java backends with React frontends
- Docker containerisation for environment consistency
- Agile/Scrum delivery across cross-functional teams

---

## 📫 Let's connect

I'm actively looking for my next role in Berlin.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-abran--paul-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/abran-paul)
[![Email](https://img.shields.io/badge/Email-contact@abran.work-EA4335?style=flat&logo=gmail)](mailto:contact@abran.work)
[![Phone](https://img.shields.io/badge/Berlin-+49%2017632181579-34A853?style=flat)](tel:+4917632181579)

---

*I enjoy building apps that combine culture + technology — bringing Tamil literature into modern mobile experiences is one of the more unique things I've shipped.*
