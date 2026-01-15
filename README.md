<div align="center">

<img src="https://github.com/NexGen-Interactive/nxgn-ui/blob/main/icons/NXGN.png?raw=true" alt="NXGN Banner" width="1100" />

# NexGen Interactive

<b>Wir bauen eine RP-Plattform, nicht nur Content.</b><br/>
NXGN ist ein System-Stack: <b>Creator-first</b>, <b>modular</b>, <b>auditierbar</b> – damit neue Ideen in Minuten live gehen, nicht in Wochen.

<br/>

<img alt="Status" src="https://img.shields.io/badge/Status-Early%20Build-0A0A0A?style=for-the-badge" />
<img alt="Stack" src="https://img.shields.io/badge/Stack-FiveM-0A0A0A?style=for-the-badge" />
<img alt="Principle" src="https://img.shields.io/badge/Principle-System%20%3E%20Skripte-0A0A0A?style=for-the-badge" />
<img alt="Workflow" src="https://img.shields.io/badge/Workflow-PR%20Only-0A0A0A?style=for-the-badge" />

<br/><br/>

<a href="#was-ist-nxgn">Was ist NXGN?</a> •
<a href="#plattform-dna">Plattform-DNA</a> •
<a href="#repos">Repos</a> •
<a href="#dev-start">Start für Devs</a> •
<a href="#architektur">Architektur</a> •
<a href="#contributing">Contributing</a>

</div>

---

<a id="was-ist-nxgn"></a>
## 🧬 Was ist NXGN?
NXGN ist eine **Creator-Driven Roleplay-Plattform** auf FiveM-Basis:  
Wir entwickeln ein **System**, das Fraktionen, Rollen und Features **konfigurierbar** macht – ohne Hardcode pro “Job”.

---

<a id="plattform-dna"></a>
## 🧩 Plattform-DNA
**Design-Prinzipien, die in jedem Repo gelten:**
- **Server entscheidet, UI zeigt an**
- **Permissions first** (Rollen/Rechte sind Keys, nicht Sonderlogik)
- **Module-Driven** (enabledModules + permissions)
- **Audit-First** bei Creator/Staff/Security-Aktionen

---

<a id="repos"></a>
## 🗺️ Repo-Landkarte
> Schnellüberblick: Wo liegt was?

| Repo | Rolle | Kurzbeschreibung |
|---|---|---|
| **babylonfx** | 🧠 Core Engine | Fraktionen, Permissions, Templates, Storage, Exports (Single Source of Truth) |
| **nxgn-admin** | 🛠 Creator/Staff Backend | Serverseitige Actions + Validierung + Audit |
| **nxgn-ui** | 🎨 Zentrale NUI | Design System + Views (Creator/Manager/…); keine Business-Logik |
| **nxgn-jobs** | 🧩 Modules | Feature-Module (Garage/Armory/MDT/…); keine Job-Hardcodes |
| **nxgn-security** | 🔒 Guard Layer | Validation, Rate-Limits, Flags, Exploit Protection |
| **nxgn-bot** | 🤖 Automation (später) | Ops/Alerts/Workflow-Shortcuts |

---

<a id="dev-start"></a>
## 🚀 Start für Devs
1) Repo clonen → `develop` auschecken  
2) Lokale Config setzen (niemals Secrets committen)  
3) Feature-Branch von `develop`: `feature/<name>`  
4) PR nach `develop` → mindestens 1 Review  
5) Integration/Tests laufen über Testserver (`develop`)

---

<a id="architektur"></a>
## 📦 Architektur in einem Satz
**BabylonFX** liefert Systeme & Wahrheit → **Admin** orchestriert & audit-logged → **UI** visualisiert → **Modules** liefern Features → **Security** schützt den gesamten Flow.

---

<a id="contributing"></a>
## 🤝 Contributing (Team)
- Kleine PRs > große PRs
- Definition of Done: validation, permissions, audit, config-first
- Reviews sind kein “Nice-to-have”, sondern Teil des Systems

<div align="center">

<b>NXGN ist das Gegenteil von Chaos.</b><br/>
Systeme. Struktur. Skalierung.

</div>
