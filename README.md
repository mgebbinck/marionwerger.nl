# marionwerger.nl

Statische website van **Marion Werger Coaching & Yoga**, klaar om te hosten op GitHub Pages.

## Inhoud

| Bestand | Pagina |
|---|---|
| `index.html` | Home |
| `wat-is-ademwerk.html` | Ademwerk – Wat is ademwerk? |
| `ademcoaching.html` | Ademwerk – Ademcoaching, individuele sessie |
| `ademcirkels.html` | Ademwerk – Ademcirkels |
| `yogastijlen.html` | Yoga – Wat is Yoga / Yogastijlen |
| `individuele-yoga.html` | Yoga – Individuele Yoga |
| `groepslessen.html` | Yoga – Groepslessen |
| `bedrijfsyoga.html` | Yoga – Bedrijfsyoga |
| `coaching.html` | Coaching – Coaching Stressreductie |
| `herstel-bij-burn-out.html` | Coaching – Herstel bij Burn-out |
| `yogareis-nepal.html` | Reizen – Yogareis Nepal |
| `retreats.html` | Reizen – Weekend & One Day Retreats |
| `mountainbikereis-nepal.html` | Reizen – Mountainbikereis Nepal |
| `voor-werkgevers.html` | Voor werkgevers |
| `team.html` | Over ons – Team |
| `marion.html` | Over ons – Marion |
| `contact.html` | Contact |
| `algemene-voorwaarden.html` | Algemene voorwaarden |
| `privacyverklaring.html` | Privacyverklaring |

Opmaak staat in `assets/css/style.css`, alle foto's in `assets/img/`.
De site is statisch: geen build-stap, geen framework, geen database.

## Publiceren op GitHub Pages

1. Maak een nieuwe (lege) repository aan op GitHub, bijvoorbeeld `marionwerger-nl`.
2. Zet de inhoud van deze map in de repository:

   ```bash
   git init
   git add .
   git commit -m "Eerste versie website marionwerger.nl"
   git branch -M main
   git remote add origin https://github.com/<gebruikersnaam>/marionwerger-nl.git
   git push -u origin main
   ```

3. Ga in de repository naar **Settings → Pages** en kies bij *Source*:
   `Deploy from a branch` → branch `main`, map `/ (root)`.
4. Eigen domein: het bestand `CNAME` bevat al `www.marionwerger.nl`.
   Zet bij je domeinprovider een CNAME-record voor `www` naar
   `<gebruikersnaam>.github.io`. Vink daarna in GitHub Pages *Enforce HTTPS* aan.

Het bestand `.nojekyll` zorgt dat GitHub de bestanden ongewijzigd publiceert.

## Nog aan te vullen

- `privacyverklaring.html` — de originele tekst kon niet worden opgehaald en moet nog
  worden ingevuld.
- Het contactformulier opent het e-mailprogramma van de bezoeker. Wil je een echt
  verzendend formulier, koppel dan een dienst als Formspree of Netlify Forms
  (GitHub Pages kan zelf geen formulieren verwerken).
- Actuele lesroosters, data en prijzen: controleer voor livegang of alles nog klopt.

© Marion Werger Coaching & Yoga | Fotografie: o.a. Lizet Beek
