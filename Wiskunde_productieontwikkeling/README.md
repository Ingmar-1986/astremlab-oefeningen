# ASTREM Lab — Voorkennis integraalrekening

Statische GitHub Pages-site met twee zelftesten, zonder externe bibliotheken of backend.

## Publiceren
1. Pak de ZIP uit. Upload `index.html`, `meerkeuze.html`, `open-vragen.html`, `.nojekyll` en dit README-bestand naar de hoofdmap van een nieuwe repository (bijvoorbeeld `voorkennis-integralen`). Gebruik **Add file → Upload files** en commit naar `main`.
2. Ga naar **Settings → Pages**, kies bij Source **Deploy from a branch**, branch `main` en map `/ (root)`, en klik op **Save**.
3. Open de URL die GitHub Pages bij Settings → Pages vermeldt. Deel die URL met de student.

Bij gebruik in een bestaande site kun je de drie HTML-bestanden samen in een submap plaatsen. De links zijn relatief. Gebruik in dat geval de bestaande Pages-configuratie.

## Resultaten en privacy
- Beide testen exporteren een JSON-bestand. Stuur die bestanden naar de begeleider, niet naar de repository.
- De bestanden zijn compatibel met de afzonderlijke privé-analysetool `ASTREM_Maya_Analyse_15_open_v2.html`.
- De analysetool, verbetersleutel en ingevulde resultaten horen **niet** in de publieke repository.
- De student vult zelf haar naam in; er zijn geen vooraf ingevulde leerlinggegevens. GitHub Pages is geen afgeschermde leeromgeving. Iedereen met toegang tot de site kan de vragen zien.
- Er is geen automatische verzending, database of Cloudflare-integratie. De browser bewaart de antwoorden lokaal indien beschikbaar. Download reservekopieën.

De twee testen bevatten respectievelijk 21 meerkeuzevragen en 15 open vragen, met MathML-notatie.
