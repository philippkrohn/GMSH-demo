# GMSH Interne Kommunikation - Demo Website

Eine moderne, responsive Demo-Website für interne Kommunikation beim GMSH, entwickelt mit modernen Webtechnologien und Fokus auf Benutzerfreundlichkeit und Barrierefreiheit.

## 🎯 Projektübersicht

Diese Demo-Website zeigt konkrete Ansätze für moderne interne Kommunikation in öffentlichen Einrichtungen. Sie demonstriert verschiedene Kommunikationsformate und deren praktische Umsetzung.

### Zielgruppe
- Entscheider:innen in Geschäftsführung, HR und Kommunikation
- Mitarbeitende des GMSH
- Interessierte an moderner interner Kommunikation

### Designprinzipien
- **Seriosität**: Professioneller, sachlicher Ton ohne Marketing-Floskeln
- **Modernität**: Zeitgemäße UI/UX mit subtilen visuellen Effekten
- **Barrierefreiheit**: WCAG 2.1 AA konforme Umsetzung
- **Responsivität**: Mobile-First Ansatz für alle Endgeräte

## 🎨 Design & Branding

### Farbschema
- **Primär Navy**: `#003f7d` - Hauptfarbe für Überschriften und wichtige Elemente
- **Primär Azure**: `#0070b8` - Sekundärfarbe für Akzente und Icons
- **Akzent Rot**: `#c5002e` - Für Call-to-Actions und Highlights
- **Hintergründe**: `#f5f7fa` / `#f7f9fc` - Neutrale, helle Hintergründe

### Typografie
- **Schriftart**: Inter (Google Fonts)
- **Hierarchie**: Klare Größenabstufungen für optimale Lesbarkeit
- **Responsive**: Fluid Typography mit clamp() für alle Bildschirmgrößen

### Visuelle Effekte
- **Glassmorphism**: Subtile Backdrop-Filter für moderne Karteneffekte
- **Micro-Interactions**: Sanfte Hover-States und Animationen (150-250ms)
- **Schatten**: Dezente Schlagschatten für Tiefenwirkung
- **Border-Radius**: Einheitliche 12-16px Rundungen

## 📁 Projektstruktur

```
gmsh-demo/
├── index.html                 # Startseite
├── newsletter/
│   └── index.html            # Newsletter-Beispiele
├── intranet/
│   └── index.html            # Intranet-Dashboard
├── case-study/
│   └── index.html            # Fallstudie Video-Serie
├── intro/
│   └── index.html            # Intro-Video Seite
├── assets/
│   ├── css/
│   │   └── style.css         # Haupt-Stylesheet
│   ├── js/
│   │   └── app.js            # JavaScript-Funktionalität
│   └── img/                  # Bilder und Icons (SVG-Platzhalter)
├── README.md                 # Diese Dokumentation
└── test-results.md           # Testergebnisse
```

## 🚀 Features

### Navigation
- **Fixed Header**: Bleibt beim Scrollen sichtbar
- **Smooth Scrolling**: Sanfte Übergänge zwischen Sektionen
- **Active States**: Visuelle Hervorhebung der aktuellen Seite
- **Mobile Menu**: Hamburger-Menü für mobile Geräte

### Interaktivität
- **Fade-in Animationen**: Elemente erscheinen beim Scrollen
- **Hover-Effekte**: Subtile Reaktionen auf Mausinteraktion
- **Keyboard Navigation**: Vollständige Tastatursteuerung
- **Focus Management**: Sichtbare Fokus-Indikatoren

### Responsive Design
- **Mobile-First**: Optimiert für kleine Bildschirme
- **Flexible Grids**: CSS Grid und Flexbox für adaptive Layouts
- **Responsive Images**: Skalierbare Grafiken und Icons
- **Touch-Friendly**: Große Klickbereiche für Touch-Geräte

### Barrierefreiheit
- **Semantisches HTML**: Korrekte Verwendung von HTML5-Elementen
- **ARIA-Labels**: Zusätzliche Informationen für Screenreader
- **Skip Links**: Direkte Navigation zum Hauptinhalt
- **Kontrast**: WCAG AA konforme Farbkontraste
- **Reduced Motion**: Respektiert Benutzereinstellungen für Animationen

## 📄 Seitenübersicht

### 1. Startseite (`/index.html`)
- **Hero-Bereich**: Einführung in die Demo mit Fallback-Text
- **Features**: Drei Hauptkommunikationsformate
- **Prozess**: "So arbeite ich" - Analyse, Umsetzung, Messung
- **Demo-Bausteine**: Links zu allen Unterseiten
- **HR-Callout**: Spezielle Information für Entscheider

### 2. Newsletter (`/newsletter/index.html`)
- **Artikel-Übersicht**: Drei Beispiel-Newsletter
- **Kategorisierung**: Thematische Einordnung der Inhalte
- **Metadaten**: Datum und Kategorie-Tags
- **Call-to-Actions**: "Mehr erfahren" Buttons

### 3. Intranet (`/intranet/index.html`)
- **Dashboard-Layout**: Zentrale Übersicht aller Services
- **Sidebar-Navigation**: Strukturierte Menüführung
- **Quick-Access Cards**: Schnellzugriff auf wichtige Bereiche
- **Service-Grid**: Übersicht aller verfügbaren Services
- **Mobile-Optimierung**: Off-Canvas Sidebar für mobile Geräte

### 4. Fallstudie (`/case-study/index.html`)
- **Timeline-Design**: Chronologische Projektdarstellung
- **Prozess-Schritte**: Ausgangslage → Ziele → Konzept → Umsetzung → Lessons Learned → Mehrwert
- **Metriken**: Konkrete Erfolgszahlen und KPIs
- **Mockup-Galerie**: Platzhalter für Projektvisualisierungen

### 5. Intro-Video (`/intro/index.html`)
- **Video-Embed**: YouTube-Integration (Privacy-Enhanced)
- **Responsive Player**: 16:9 Aspect Ratio für alle Geräte
- **Begleitinhalte**: Zusätzliche Informationen zum Video
- **Kontakt-Sektion**: Call-to-Action für weitere Gespräche

## 🛠 Technische Implementierung

### HTML5
- **Semantische Struktur**: Korrekte Verwendung von `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`
- **Accessibility**: ARIA-Rollen und -Eigenschaften
- **SEO-Optimierung**: Meta-Tags und strukturierte Daten (erweiterbar)

### CSS3
- **Custom Properties**: CSS-Variablen für konsistente Werte
- **Modern Layout**: CSS Grid und Flexbox
- **Responsive Design**: Media Queries und fluid Typography
- **Performance**: Optimierte Selektoren und minimale Redundanz

### JavaScript (ES6+)
- **Module Pattern**: Strukturierte Code-Organisation
- **Event Delegation**: Effiziente Event-Behandlung
- **Intersection Observer**: Performance-optimierte Scroll-Animationen
- **Accessibility**: Keyboard-Navigation und Focus-Management

### Performance
- **Lazy Loading**: Vorbereitet für Bilder und Medien
- **Debouncing**: Optimierte Scroll-Handler
- **Minimal Dependencies**: Keine externen JavaScript-Bibliotheken
- **Optimized Assets**: Komprimierte und optimierte Ressourcen

## 🔧 Installation & Verwendung

### Lokale Entwicklung
```bash
# Repository klonen oder Dateien herunterladen
cd gmsh-demo

# Lokalen Server starten (Python 3)
python3 -m http.server 8000

# Oder mit Node.js
npx http-server -p 8000

# Website öffnen
open http://localhost:8000
```

### Deployment
Die Website ist vollständig statisch und kann auf jedem Webserver gehostet werden:
- GitHub Pages
- Netlify
- Vercel
- Apache/Nginx
- CDN-Services

### Anpassungen
1. **Inhalte**: Texte in den HTML-Dateien anpassen
2. **Styling**: CSS-Variablen in `style.css` modifizieren
3. **Bilder**: SVG-Platzhalter durch echte Bilder ersetzen
4. **Funktionalität**: JavaScript in `app.js` erweitern

## 🎯 Zukünftige Erweiterungen

### Kurzfristig
- [ ] Echte Bilder und Medien hinzufügen
- [ ] Mobile Sidebar-Funktionalität testen
- [ ] Kontaktformular mit Validierung
- [ ] SEO-Optimierung (Meta-Tags, Schema.org)

### Mittelfristig
- [ ] Content Management System Integration
- [ ] Analytics und Tracking
- [ ] A/B Testing für verschiedene Inhalte
- [ ] Newsletter-Anmeldung

### Langfristig
- [ ] Mehrsprachigkeit (DE/EN)
- [ ] Erweiterte Barrierefreiheit
- [ ] Progressive Web App Features
- [ ] Backend-Integration für dynamische Inhalte

## 📊 Browser-Unterstützung

### Vollständig unterstützt
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

### Eingeschränkt unterstützt
- Internet Explorer 11 (Fallback ohne moderne Features)
- Ältere Mobile Browser (Basis-Funktionalität)

## 🤝 Beitragen

### Code-Standards
- **HTML**: Semantisch korrekt, validiert
- **CSS**: BEM-ähnliche Namenskonvention
- **JavaScript**: ES6+ Features, dokumentiert
- **Accessibility**: WCAG 2.1 AA konform

### Testing
- **Cross-Browser**: Testen in allen unterstützten Browsern
- **Responsive**: Testen auf verschiedenen Bildschirmgrößen
- **Accessibility**: Screenreader und Keyboard-Navigation
- **Performance**: Lighthouse-Scores überwachen

## 📞 Kontakt & Support

Für Fragen zur Implementierung oder Anpassungen:
- **Technische Fragen**: Siehe Code-Kommentare und Dokumentation
- **Design-Fragen**: Referenz zu den Design-Prinzipien in diesem README
- **Inhaltliche Fragen**: Siehe ursprüngliche Anforderungen

---

**Entwickelt mit ❤️ für moderne interne Kommunikation**

