# Atelier Liniar — Asistent de planificare pentru arhitecți

Proiect pentru examenul final (Curs Vibe Coding): aplicație într-un singur fișier HTML (`index.html`) care apelează API-ul Claude.

## Cum se rulează
- Deschideți `index.html` în Chrome (dublu-click) sau prin GitHub Pages.
- **Conectează AI** (dreapta sus) → introduceți o cheie API Claude → „Testează conexiunea”. Cheia rămâne doar în browser.
- Fără cheie: **Mod demo (fără AI)** — totul funcționează local, cu excepția citirii fotografiei.
- Cod demo Atelier Signature: `LINIAR2030`.

## Flux
1. **Prezentare** — descrierea firmei și butonul „Tell us about your project”.
2. **Desen** — conturul pe grilă (doar linii orizontale/verticale), cota fiecărei laturi în metri, verificarea închiderii și aria totală. Opțional: import din fotografie.
3. **Întrebări** — camere, băi, utilizarea spațiului, stil + maximum 2 întrebări de clarificare generate de AI.
4. **Rezultat** — 3 variante de layout primite ca date structurate, validate în cod (în contur, fără suprapuneri, număr exact de camere și băi) și desenate de aplicație; PDF „Mulțumim că ați ales Atelier Liniar”.

## Extra
Ecran de bun venit cu vilă 3D (zi/noapte, sunet ambiental), română/engleză, vizualizare 3D și plimbare la persoana întâi, moodboard, buget estimativ, formular de contact, Concepte 2030, Atelier Signature, Concierge AI cu voce.
