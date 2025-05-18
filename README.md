# A65 Digitale Speisekarte

Eine responsive, digitale Speisekarte für das A65, umgesetzt als statische HTML/CSS-Website. Das Design orientiert sich an der originalen Speisekarte und wurde für optimale Lesbarkeit auf allen Geräten optimiert.

## Features

- Responsives Design für alle Bildschirmgrößen
- Moderne, übersichtliche Typografie
- Optimierte Darstellung von Preisen und Mengenangaben
- Elegante Animationen und Übergänge
- Spezielle Gestaltung für die Shisha-Tabak-Sektion
- Dekorative Elemente wie die rote Ziersäule

## Technische Details

### Verwendete Technologien
- HTML5
- CSS3
- Google Fonts (Roboto, Dancing Script)

### Struktur

```
.
├── index.html          # Hauptdatei mit der Menüstruktur
├── styles.css          # Alle Styles und responsive Anpassungen
└── README.md          # Projektdokumentation
```

### Fonts
- **Hauptschrift**: Roboto (400, 700)
- **Dekorative Schrift**: Dancing Script (600)
- **Logo**: Arial Black

### Farbschema
- Hintergrund: `#18191b`
- Akzentfarbe (Rot): `#e63a2e`
- Text: `#fff`
- Dezente Texte: `rgba(255, 255, 255, 0.5)`

## Responsive Breakpoints

- Desktop: > 430px
- Tablet: ≤ 430px
- Mobile: ≤ 360px

## Menü-Kategorien

1. Weine
2. Biere
3. Alkoholfreie Getränke
4. Spirituosen
5. Snacks
6. Shisha

## Anpassungen & Wartung

### Neue Getränke hinzufügen

```html
<tr>
    <td>Getränkename</td>
    <td>Menge</td>
    <td>0,00&nbsp;€</td>
</tr>
```

### Neue Kategorie hinzufügen

```html
<div class="menu-section">
    <div class="section-title">Kategoriename</div>
    <table class="menu-table">
        <!-- Getränke hier einfügen -->
    </table>
</div>
```

### Preise aktualisieren
Preise können direkt im HTML-Code in der entsprechenden Tabellenzelle angepasst werden:
```html
<td>0,00&nbsp;€</td>
```

## Mobile Optimierung

Die Speisekarte wurde speziell für mobile Geräte optimiert:
- Angepasste Schriftgrößen
- Optimierte Spaltenbreiten
- Verbesserte Touch-Targets
- Reduzierte Abstände

## Wartung und Updates

1. Änderungen am Design in `styles.css` vornehmen
2. Neue Einträge in `index.html` hinzufügen
3. Responsive Breakpoints bei Bedarf in den Media Queries anpassen

## Lizenz

Alle Rechte vorbehalten. Diese Speisekarte wurde speziell für das A65 entwickelt. 