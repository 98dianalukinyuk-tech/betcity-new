# QA-rapport — BetCity Pokerroomgids Nederland

- HTML-pagina’s: **17**
- Taal/lokale instelling: **nl-NL**
- Lokale WebP-bestanden: **52**
- Unieke afbeeldingshashes: **52**
- Ontbrekende lokale links/bestanden: **0**
- Unieke titles en descriptions: **OK**
- Exacte beeldduplicaten: **0**
- Zichtbare Qbet-verwijzingen: **0**

## Positionering

- De site is zichtbaar aangeduid als onafhankelijke bezoekersgids.
- De site gebruikt een origineel gidslogo en niet het officiële BetCity-logo.
- Poker, toernooien en uitzendingen worden uitsluitend als fysieke activiteiten beschreven.
- Via de site kan niet worden gespeeld, gestort of aan een uitzending worden deelgenomen.
- Niet-bevestigde locatie-, contact- en evenementgegevens blijven verborgen.
- `noindex,nofollow` en `Disallow: /` blijven actief vóór publicatie.

## Techniek

- Cookiekeuze gebruikt een projectspecifieke opslagkey.
- Accept en Reject verbergen de banner vóór opslag wordt geprobeerd.
- Mobiele navigatie, FAQ, gallery-modal, filters en formulieren zijn in `script.js` geïmplementeerd.
- Alle WebP-bestanden zijn met Pillow gedecodeerd.

## Automatische controles

```json
{
  "errors": [],
  "duplicate_image_files": {},
  "html_pages": 17,
  "webp_files": 52
}
```

## Chromium-interactietest

De hoofdpagina is in headless Chromium gerenderd met lokaal ingesloten CSS, JavaScript, SVG en WebP-assets op de volgende breedtes:

- 1440 px
- 1024 px
- 768 px
- 430 px
- 390 px
- 360 px

Resultaten:

- horizontale overflow: **niet aangetroffen**;
- cookiebanner bij eerste weergave: **zichtbaar**;
- `Alles accepteren`: **banner gesloten**;
- `Alles weigeren`: **banner gesloten**;
- mobiel menu opent en sluit: **OK**;
- sluiten met `Escape`: **OK**;
- JavaScript page errors: **0**.

De test gebruikte `page.set_content` met lokaal ingesloten assets. Een laatste controle op de uiteindelijke productiehosting blijft vereist.
