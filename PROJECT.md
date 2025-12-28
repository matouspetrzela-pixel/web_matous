# Matouš Petržela - Osobní Web

**Typ:** Single-page osobní prezentace
**Technologie:** Čistý HTML + CSS (vanilla, bez frameworků)
**Účel:** Osobní web AI nadšence, vibecoding ambasadora

## 🎯 Klíčové Prvky

### Hero Sekce
- **Jméno:** Top 32%, font-size 10.1rem, bold 900
- **Tři věty (vlevo dole):**
  - Radek 1: "Učím se s AI nahlas." (bold 700)
  - Radek 2: "Stavím systémy, ne hype." (normal 400)
  - Radek 3: "Beru ostatní s sebou." (normal 400)
  - Jednotný styl: 1.8rem, spacing 0.6rem, color #4a5568

### Animovaná Rotace (uprostřed dole)
- **Slova:** "stavím" → "učím se" → "ladím" → "zkouším"
- **Timing:** Každé slovo 6 sekund
- **Animace:** Fade in/out, infinite loop
- **Pozice:** Bottom 17% (desktop), 14% (mobile)
- **Font:** 1.155rem (desktop), 0.945rem (mobile)

### Design System
```css
--white: #ffffff
--black: #0f0f0f
--grey: #6b7280
--orange: #ff8a00
```

### Header
- Oranžový pás: 22px výška

### Navigace
- O mně | Projekty | Vibecoding | Kontakt | [in] (LinkedIn)

### Typografie (Sjednocená)
- **Body text všech sekcí:** 1.1rem, color: #0f0f0f, line-height: 1.8
- **Nadpisy sekcí:** 2.5rem, bold 700

## 📄 Sekce

### Vibecoding
- Začít dřív, než mám jasno
- Myslet nahlas s AI
- Učit se stavěním

### Projekty
1. **Knowledge Base pro Vibe Coding**
   - 31 souborů, 272 KB dokumentace
2. **AI Asistent pro Analýzu Pojistek**
   - M365 Copilot specialista

### O mně
- "Učím se nahlas."
- "Sdílím proces, ne hotové věci. Baví mě cesta, ne póza. A lidi, kteří staví podobným způsobem."
- "V práci působím jako AI ambasador. Mimo ni si zkouším, co všechno jde postavit pomocí vibe codingu."

### Kontakt
- Email: matous&#46;petrzela&#64;gmail&#46;cz (entity encoding pro bot protection)
- LinkedIn: https://www.linkedin.com/in/matou%C5%A1-petr%C5%BEela
  - Security: rel="noopener noreferrer nofollow external"

## 🔒 Security
- CSP headers
- X-Frame-Options: DENY
- X-Content-Type-Options: nosniff
- Email: žádný mailto:, entity encoding
- External links: plné security atributy

## 📱 Responsive
- Desktop: Vertikální split layout
- Mobile (@media max-width: 768px): Horizontální stack
- Font scaling pro všechny velikosti

## 🎨 Animace
```css
@keyframes fadeInOut {
    0% { opacity: 0; }
    4% { opacity: 1; }
    21% { opacity: 1; }
    25% { opacity: 0; }
    100% { opacity: 0; }
}
```

## 📂 Struktura
```
C:\web_matous\
├── index.html (hlavní soubor)
├── test.html
└── PROJECT.md (tento soubor)
```

## 🚀 Deployment Ready
- Statický web, hostitelný kdekoliv (GitHub Pages, Netlify, Vercel)
- Žádné závislosti
- Optimalizovaný, minimalistický

---
**Poslední update:** 2025-12-28
**Git commit:** Inicializováno s kompletním webem
