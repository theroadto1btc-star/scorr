# 🤝 Contributing to SCORR

Bedankt voor je interesse in SCORR! Dit document beschrijft hoe je kunt bijdragen aan het project.

---

## 📋 Code of Conduct

- Wees respectvol naar andere contributors
- Constructieve feedback geven
- Focus op wat het beste is voor het project
- Professionaliteit behouden

---

## 🚀 Development Setup

### Vereisten
- Git
- Een moderne browser (Chrome, Firefox, Safari, Edge)
- Code editor (VS Code aanbevolen)
- (Toekomst) Node.js 18+ voor backend

### Repository Clonen
```bash
git clone https://github.com/theroadto1btc-star/scorr.git
cd scorr
```

### Lokaal Draaien
Open gewoon de HTML bestanden in je browser:
```bash
# Scheidsrechter app
open frontend/scheidsrechter-app/index.html

# Kantine display
open frontend/kantine-display/index.html

# Login flow
open frontend/auth/login.html
```

---

## 🌿 Branch Strategy

### Main Branches
- `main` - Productie-ready code (protected)
- `develop` - Development branch voor nieuwe features

### Feature Branches
Maak een nieuwe branch voor elke feature:
```bash
git checkout -b feature/naam-van-feature
```

Voorbeelden:
- `feature/add-notifications`
- `feature/improve-timer`
- `fix/logo-display-issue`
- `docs/update-readme`

---

## 💻 Coding Standards

### HTML
- Gebruik semantische HTML5 tags
- Altijd `alt` attributen op images
- Proper indentation (2 spaces)

### CSS
- BEM naming convention waar mogelijk
- CSS variabelen gebruiken voor kleuren
- Mobile-first responsive design

### JavaScript
- ES6+ syntax
- `const` en `let`, geen `var`
- Duidelijke functie namen
- Comments voor complexe logica

### Brand Consistency
**Gebruik altijd SCORR brand kleuren:**
```css
--scorr-electric: #00FF88
--scorr-deep: #0A0E27
--scorr-slate: #1E2749
--scorr-accent: #FF3D71
--scorr-cloud: #F5F7FA
--scorr-warning: #FFB800
```

**Font:** Lexend (Google Fonts)

---

## 📝 Commit Messages

Gebruik duidelijke commit messages:

### Format
```
type(scope): subject

body (optioneel)
```

### Types
- `feat`: Nieuwe feature
- `fix`: Bug fix
- `docs`: Documentatie
- `style`: Code formatting (geen functionaliteit)
- `refactor`: Code refactoring
- `test`: Tests toevoegen
- `chore`: Build process, dependencies

### Voorbeelden
```bash
git commit -m "feat(timer): add background timer with wake lock"
git commit -m "fix(login): resolve logo display issue"
git commit -m "docs(readme): update installation instructions"
git commit -m "style(display): improve responsive design"
```

---

## 🔄 Pull Request Process

### 1. Fork & Clone
```bash
git clone https://github.com/YOUR-USERNAME/scorr.git
```

### 2. Create Feature Branch
```bash
git checkout -b feature/your-feature
```

### 3. Make Changes
- Write code
- Test thoroughly
- Follow coding standards

### 4. Commit & Push
```bash
git add .
git commit -m "feat: your feature description"
git push origin feature/your-feature
```

### 5. Create Pull Request
- Go to GitHub
- Click "New Pull Request"
- Fill in description:
  - What does this PR do?
  - Why is this needed?
  - Any breaking changes?
  - Screenshots (if UI change)

### 6. Review Process
- Wait for review from maintainers
- Address feedback if requested
- Once approved, will be merged

---

## 🧪 Testing

### Manual Testing Checklist
- [ ] Test op Chrome
- [ ] Test op Safari (iOS)
- [ ] Test op Firefox
- [ ] Test responsive design (mobile/tablet/desktop)
- [ ] Check console for errors
- [ ] Test with screen off (timer apps)
- [ ] Verify logo's laden correct

### Feature Specific
**Scheidsrechter App:**
- [ ] Timer blijft lopen met scherm uit
- [ ] Scores worden correct opgeslagen
- [ ] PDF download werkt
- [ ] Fluitje speelt bij einde helft

**Kantine Display:**
- [ ] Auto-refresh werkt
- [ ] Live indicator update
- [ ] Logo's laden correct

---

## 📚 Documentation

Update documentatie als je:
- Een nieuwe feature toevoegt
- API verandert
- Configuration options toevoegt
- Breaking changes maakt

---

## 🐛 Bug Reports

### Template
```markdown
**Beschrijving**
Korte beschrijving van de bug

**Stappen om te reproduceren**
1. Ga naar '...'
2. Klik op '...'
3. Zie error

**Verwacht gedrag**
Wat had er moeten gebeuren

**Screenshots**
(Als relevant)

**Device info:**
- OS: [bijv. iOS 17]
- Browser: [bijv. Safari]
- Versie: [bijv. 1.0]
```

---

## 💡 Feature Requests

### Template
```markdown
**Probleem**
Beschrijf het probleem dat deze feature oplost

**Oplossing**
Beschrijf de gewenste feature

**Alternatieven**
Andere oplossingen die je hebt overwogen

**Extra context**
Screenshots, mockups, etc.
```

---

## 🎨 Design Guidelines

### Brand Consistency
- Gebruik altijd SCORR kleuren
- Lexend font voor alle tekst
- Logo: altijd gradient of wit/zwart variant
- Icons: emoji's waar mogelijk (universeel)

### UI/UX Principles
- **Mobile-first**: Begin met mobile design
- **Touch-friendly**: Min 44x44px touch targets
- **Clear hierarchy**: Belangrijke acties prominent
- **Fast feedback**: Immediate visual feedback op acties
- **Error prevention**: Confirm destructive actions

---

## 📞 Contact

Vragen? Neem contact op via:
- GitHub Issues
- (Email - nog toe te voegen)

---

**Bedankt voor je bijdrage aan SCORR! ⚽💚**
