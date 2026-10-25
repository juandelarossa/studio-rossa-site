# studio-rossa-site

Website van Studio Rossa, live op https://studiorossa.nl via GitHub Pages (tak `main`, domein in `CNAME`).

## Bestanden

| Bestand | Inhoud |
|---|---|
| `index.html` | Startpagina: Domtoren, uitvoeringen, maten en kleuren op verzoek, bedrijvensectie, de maker, contact en uitleg Studio Rossa MCP. |
| `privacy.html` | Privacyverklaring, inclusief het onderdeel Studio Rossa MCP. |
| `style.css` | Alle opmaak. Kleuren staan bovenaan als variabelen. |
| `assets/` | Logo, merkteken, favicons en deelafbeelding, gemaakt uit de artwork in Drive (Marketing/Artwork), plus de productfoto `premium-domtoren.jpg` (zonder EXIF/locatie). |

## Regels

- Geen externe fonts, scripts of trackers. De site laadt alleen eigen bestanden, zodat de privacyverklaring klopt.
- De uitleg over Studio Rossa MCP op de startpagina en in de privacyverklaring blijft staan. De Google-verificatie van de app verwijst ernaar.
- De bedrijvensectie gebruikt een `mailto:`-link met een ingevulde vragenlijst. Er is geen formulier of server, dus er worden geen gegevens op de site verzameld.
- Etsy-link: zodra de shop open is, zoek je op `ETSY-LINK` in `index.html`. Er zijn twee plekken (bovenaan bij de knoppen en onder de uitvoeringen). Vervang daar het element `<span class="btn soon">` door `<a class="btn" href="URL-VAN-DE-SHOP">Naar de Etsy-shop</a>` en pas ook de regel "Binnenkort via Etsy" bovenaan aan.
- Bedrijfsaanvraag: een `mailto:`-link kan geen bijlage meesturen. De tekst vraagt daarom om het logo als bijlage bij de mail. Een echte uploadknop vraagt een extern formulier en een aanpassing van de privacyverklaring.
- Geen prijzen, levertijden of kwaliteitsclaims op de site voordat die zijn vastgesteld.
- `main` is live. Wijzigingen gaan eerst via een branch en worden pas samengevoegd na akkoord van Johan.

Aansturing en beleid staan in de repository `studio-rossa` (zie het onderdeel Website in `CLAUDE.md`).
