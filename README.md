# Sueda — Stilberatung

Landingpage für **Sueda Stilberatung** — persönliche Modeberatung, Stilberatung & Personal Shopping im Ruhrgebiet.

🔗 **Live:** https://tobiaskammer-de.github.io/sueda-stilberatung/

## Über das Projekt

Eine einzelne, eigenständige `index.html` — kein Build-Schritt, keine Abhängigkeiten.
Umgesetzt aus einem [Claude Design](https://claude.ai/design)-Handoff: Das Design-Tool-Scaffolding
(`image-slot`, React/Babel, Tweaks-Panel) wurde entfernt und durch sauberes, produktionsfertiges
HTML/CSS/Vanilla-JS ersetzt.

- **Schriften:** Cormorant Garamond & Jost (Google Fonts)
- **Bilder:** aktuell Platzhalter von [Unsplash](https://unsplash.com) — jederzeit gegen echte Fotos austauschbar
- **Mobile-first:** Hamburger-Menü, Touch-Targets ≥ 44 px, fluide Typografie, `prefers-reduced-motion`-Support

## Anpassen

| Was | Wo |
|-----|-----|
| Akzentfarben | `:root { --rose / --mauve }` im `<style>`-Block |
| Hintergrund-Töne | `:root { --bg / --bg-2 }` |
| Bilder | `src` der `<img>`-Tags (Hero & Galerie) |
| Kontaktdaten | Abschnitt `#kontakt` (WhatsApp-, E-Mail-, Instagram-Links) |

## Noch zu ergänzen

- **Impressum & Datenschutz** — die Footer-Links sind Platzhalter (`#`) und sollten für den
  rechtskonformen Betrieb in Deutschland mit echten Inhalten gefüllt werden.
- **Kontaktformular** — sendet aktuell nichts ab (zeigt nur eine Dankesmeldung). Für echten
  Versand z. B. [Formspree](https://formspree.io) o. ä. anbinden.

## Lokal ansehen

```bash
python3 -m http.server 8000
# dann http://localhost:8000 öffnen
```

---
© 2026 Sueda Stilberatung · Ruhrgebiet
