# Camardine Lokobe Tours — Website

Een statische marketingwebsite voor Camardine, een lokale tourgids op Nosy Be, Madagascar.

## Wat dit project is

Single-page website (één `index.html`) voor **Camardine Lokobe Tours** — gidstours door het Lokobe Nationaal Park op Nosy Be. De site richt zich op toeristen die willen boeken via WhatsApp of e-mail.

## Structuur

```
index.html          — de volledige website (HTML + inline CSS + inline JS)
*.JPG / *.jpeg      — foto's van dieren en landschappen
logo.jpeg           — logo van de gids
island-video.mp4.MOV — achtergrondvideo
favicon*.png / .ico — favicons voor alle platformen
apple-touch-icon.png
_redirects          — Netlify redirect-regels
```

## Deployment

De site wordt gehost op **Netlify** via `camardinelokobetours.com`. Het `_redirects` bestand is voor Netlify-routing.

## Contactgegevens (in de site)

- Telefoon / WhatsApp: +261 32 995 3831
- E-mail: saidcamardine197@gmail.com
- Locatie: Ambatozavary, Nosy Be, Madagascar

## Technische keuzes

- Geen build-stap, geen frameworks — puur HTML/CSS/JS
- Alle stijlen zijn inline in `index.html`
- SEO-metadata, Open Graph en structured data (JSON-LD) zijn aanwezig
