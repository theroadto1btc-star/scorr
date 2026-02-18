# ⚽ SCORR - Live Scores. Real Football.

**Real-time score tracking platform voor amateurvoetbal**

SCORR maakt het mogelijk om live scores bij te houden tijdens amateurwedstrijden en deze real-time te delen met ouders, supporters en de kantine.

---

## 🚀 Features

### 📱 Scheidsrechter App
- Live score bijhouden tijdens wedstrijden
- Timer die blijft lopen (ook met scherm uit)
- Doelpunten registreren met spelersnummer
- Gele en rode kaarten bijhouden
- Blessuretijd toevoegen
- PDF wedstrijdverslag genereren
- Fluitje geluid bij einde helft/wedstrijd

### 📺 Kantine Display
- Live scores van alle clubteams
- Auto-refresh elke 10 seconden
- Thuis én uitwedstrijden
- FotMob/Livescore styling
- Grote, duidelijke weergave voor op TV

### 🔐 Account Management
- **Super Admin**: SCORR platform beheer
- **Club Admin**: Per club, beheert alle teams
- **Team Manager**: Per team, registreert scores
- **Viewer**: Read-only voor displays

### 👨‍👩‍👧‍👦 Ouder Features (Toekomst)
- Unieke wedstrijd link per wedstrijd
- Seizoen link per team
- Real-time updates zonder login
- WhatsApp delen

---

## 📁 Project Structuur

```
scorr/
├── frontend/
│   ├── scheidsrechter-app/    # Live score registratie app
│   ├── kantine-display/        # TV display voor kantine
│   ├── auth/                   # Login, signup, team selectie
│   └── assets/
│       └── logos/              # Club logo's
├── docs/                       # Documentatie
├── infographics/               # Brand identity & platform overview
└── README.md
```

---

## 🎨 Brand Identity

**Kleuren:**
- **Electric Green**: `#00FF88` - Primary brand color
- **Deep Navy**: `#0A0E27` - Background
- **Hot Pink**: `#FF3D71` - Accents (goals, highlights)
- **Warning Yellow**: `#FFB800` - Yellow cards

**Typography:**
- Font: Lexend (Google Fonts)
- Logo: 900 weight, -2px letter spacing

**Tagline:** "Live Scores. Real Football."

---

## 🏁 Pilot Fase

**Huidige clubs:**
- ⚽ FC Purmerend
- ⚽ VV Monnickendam

**Seizoen:** 2025/2026

---

## 🛠️ Tech Stack

**Frontend:**
- HTML5
- CSS3 (Custom, geen frameworks)
- Vanilla JavaScript
- Web Audio API (fluitje geluiden)
- Wake Lock API (scherm aan houden)
- LocalStorage (state persistence)

**Toekomstige Backend:**
- Node.js / Python (TBD)
- PostgreSQL / MongoDB (TBD)
- REST API
- WebSockets (real-time updates)

---

## 📱 Scheidsrechter App Features

### Timer Functionaliteit
- **Background timer**: Blijft lopen met scherm uit
- **Timestamp-based**: Geen interval issues
- **Auto-save**: LocalStorage persistentie
- **Doorlopende tijd**: 2e helft start bij 45:00 (niet 0:00)

### Score Registratie
- Home/Away score tracking
- Spelersnummer selectie (1-16 grid + custom input)
- Doelpuntenmakers bijhouden
- Event timeline met timestamps

### Kaarten Systeem
- Gele kaarten (🟨)
- Rode kaarten (🟥)
- Per speler registratie

### Wedstrijd Management
- 2 helften met rust
- Blessuretijd per helft instelbaar
- Speelduur configureerbaar (standaard 45 min)
- Fluitje bij einde helft (3x kort) en wedstrijd (1x lang, 2x kort)

### PDF Export
- Professioneel wedstrijdverslag
- FC Purmerend branding
- Volledige event timeline
- Deelbaar via WhatsApp

---

## 📺 Kantine Display Features

- **Real-time updates**: Elke 10 seconden
- **Live indicator**: Groene border + pulserende badge
- **Status badges**: LIVE / Afgelopen / Straks
- **Club filtering**: Alleen eigen clubteams
- **Responsive**: Werkt op alle schermformaten
- **Clean design**: FotMob/Livescore inspired

---

## 🔐 Account Systeem

### Login Opties
1. **Email + Wachtwoord** (Admin accounts)
2. **Team Code + PIN** (Team accounts) - Aanbevolen
   - Voorbeeld: `FCP1-2526` / PIN: `1926`
3. **QR Code** (Toekomst)

### Toegangsrechten
| Rol | Toegang |
|-----|---------|
| Super Admin | Alle clubs, seizoen management, analytics |
| Club Admin | Eigen club teams, displays, statistieken |
| Team Manager | Eigen team, score registratie |
| Viewer | Read-only, kantine display |

---

## 📋 Roadmap

### ✅ Fase 1: Pilot (NU)
- [x] Scheidsrechter app met live timer
- [x] Kantine display
- [x] Login/signup flows
- [x] Team selectie
- [x] Brand identity
- [x] 2 pilot clubs

### 🚧 Fase 2: Backend & Seizoen Management
- [ ] Database setup
- [ ] REST API
- [ ] Real-time sync tussen apps
- [ ] Seizoen rollover functionaliteit
- [ ] Admin panel voor club beheer
- [ ] QR code generatie

### 🔮 Fase 3: Ouder Features
- [ ] Live wedstrijd links
- [ ] Seizoen team links
- [ ] Push notificaties
- [ ] Statistieken dashboard
- [ ] Top scorers overzicht

### 🏆 Fase 4: KNVB Integratie
- [ ] KNVB API koppeling
- [ ] Automatische team sync
- [ ] Wedstrijdschema import
- [ ] Score validatie

---

## 🤝 Contributors

- **Founder 1** - Product & Development
- **Founder 2** - Business & Partnerships
- **Claude (AI Assistant)** - Development Support

---

## 📄 Documentatie

Zie `/docs` folder voor:
- Accountbeheer strategie (Word document)
- Database schema (toekomstig)
- API documentatie (toekomstig)

Zie `/infographics` folder voor:
- Platform overview infographic
- Brand identity showcase
- Style guide

---

## 🎯 Visie

**Missie:** Van scheidsrechter naar kantine in real-time — geen bureaucratie, gewoon live scores.

**Doelgroep:**
- Amateurvoetbalclubs (4e klasse t/m hoofdklasse)
- Jeugdteams
- Scheidsrechters en coaches
- Ouders en supporters

**USP's:**
1. ⚡ **Real-time**: Geen vertraging, elke actie direct zichtbaar
2. 🎯 **Simpel**: Zo makkelijk dat elke scheidsrechter het binnen 2 minuten snapt
3. 🏆 **Professioneel**: Amateurvoetbal verdient dezelfde ervaring als Eredivisie

---

## 📞 Contact

**Website:** scorr.app (toekomstig)  
**Email:** info@scorr.app (toekomstig)  

---

## 📜 License

Copyright © 2026 SCORR. All rights reserved.

---

**🚀 SCORR - Breng amateurvoetbal naar het volgende niveau!**
