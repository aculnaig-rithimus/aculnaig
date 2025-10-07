# Mijn Portfolio - Gedichten & Fotografie

Een minimalistische portfolio website voor het delen van gedichten en fotografie.

## 📁 Project Structuur

```
mijn-portfolio/
├── index.html          # Hoofdpagina
├── css/
│   └── style.css      # Alle styling
├── js/
│   └── script.js      # Interactiviteit
├── images/
│   ├── photos/        # Jouw foto's hier plaatsen
│   └── profile.jpg    # Profielfoto (optioneel)
└── README.md          # Dit bestand
```

## 🚀 Hoe te gebruiken

### Lokaal testen
1. Open `index.html` in je browser
2. Of gebruik VS Code Live Server extensie

### Content aanpassen

#### Je naam en info wijzigen
Open `index.html` en pas aan:
- Regel 24: Je naam
- Regel 25: Je functie/titel
- Regel 120: Over mij tekst
- Regel 128-129: Contact informatie

#### Gedichten toevoegen
In `index.html`, kopieer dit blok en pas aan:
```html
<article class="poem">
    <h3>Titel van je gedicht</h3>
    <div class="poem-content">
Je gedicht hier
Regel voor regel
    </div>
    <p class="poem-date">Geschreven in 2025</p>
</article>
```

#### Foto's toevoegen
1. Plaats je foto's in de `images/photos/` map
2. Hernoem ze: `photo1.jpg`, `photo2.jpg`, etc.
3. Of pas de bestandsnamen aan in `index.html` (regel 73-96)

### Kleuren aanpassen
In `css/style.css`:
- `#2c3e50` = Donkerblauw (hoofdkleur)
- `#7f8c8d` = Grijs (accent)
- `#fafafa` = Lichtgrijs (achtergrond)
- `#ecf0f1` = Wit-grijs (borders)

## 🌐 Online zetten

### Optie 1: GitHub Pages (Gratis & Simpel)
1. Maak een GitHub repository
2. Upload je bestanden
3. Ga naar Settings → Pages
4. Selecteer `main` branch
5. Je site is live op: `username.github.io/repository-naam`

### Optie 2: Netlify (Gratis & Professioneel)
1. Ga naar netlify.com
2. Sleep je `mijn-portfolio` map naar Netlify
3. Je site is automatisch live!
4. Verbind je eigen domein (optioneel)

### Optie 3: Eigen Hosting
- Upload naar je webhost via FTP
- Plaats bestanden in `public_html` map

## 🛠️ Uitbreidingen

### Later toevoegen:
- [ ] CMS voor makkelijk beheer (Netlify CMS)
- [ ] Blog functionaliteit
- [ ] Zoekfunctie voor gedichten
- [ ] Commentaar sectie
- [ ] Dark mode toggle
- [ ] Meertalige support

## 📝 Credits

Gebouwd met:
- Pure HTML, CSS, JavaScript
- Geen frameworks of libraries nodig
- Responsive design
- Geoptimaliseerd voor performance

## 📧 Contact

Vervang met je eigen informatie

---

**Versie:** 1.0  
**Laatste update:** Januari 2025