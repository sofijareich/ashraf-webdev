# HB+ Zahnärzte Nottuln — Website

Astro-Projekt (statisch, Cloudflare-Adapter), aufbauend auf dem freigegebenen
Design-Konzept (Editorial-Bold, kinetische Typografie, warme Farbwelt).

## Entwicklung

```
npm install
npm run dev       # lokaler Dev-Server
npm run build     # Produktions-Build nach dist/
npm run preview   # Build lokal ansehen
```

## Struktur

- `src/layouts/Layout.astro` — Basis-Layout, SEO-Meta, Schema.org (Dentist)
- `src/components/` — Header, Footer, Hero, TrustBar, Philosophy,
  Services, DoctorIntro, JournalPreview, ContactCta
- `src/pages/index.astro` — Startseite (Phase 2 aus dem Website-Konzept)
- `src/styles/tokens.css` — Design-Tokens (Farbe, Typografie, Reduced-Motion)

## Stand

Startseite vollständig umgesetzt (alle 9 Sektionen aus dem Konzeptdokument).
Noch offen: Leistungs-Unterseiten, Praxis/Team-Seite, Journal, Karriere,
Kontaktseite mit Online-Terminbuchung, echte Fotografie (aktuell
Platzhalter-Rahmen statt Bilder).
