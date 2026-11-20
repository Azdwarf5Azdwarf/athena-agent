# Samtalet

Kopieras in i **poi-backend**.

Planen runt om: `docs/features/athena-igen.md`.

Förebild: poi-backend #7, samtalet som skickar en länk medan rösten pratar. Och #15: en backend, nischen byts. Athena är nischen. Maskinen (telefoni, röst, körning) rörs inte.

## Dennis ord, 2026-11-20

Hon ska vara svensk volontär och hjälpa fåglar i Sverige. Fågelcentralen har nyligen sagt att de inte kan ta emot fåglar, på grund av trycket. Hon har en landningssida, hon svarar i telefon, och poi-humans samlar gåvor till dem som en tratt efter att någon har talat med henne. Vi möter Athena igen utanför kyrkan i Uddevalla. Hon är skadad. Athena har hittat sin uggla igen.

Senare samma dag: vi rör inte pengar. "Samlar gåvor" är tratten till deras Swish. Vi larpar entiteten. Se `docs/features/swish-bossor.md`.

## Samtalet, steg för steg

1. Någon ringer. Rösten svarar på svenska.
2. Hon säger att hon är volontär. Hon säger inte att hon är Fågelcentralen.
3. Hon frågar vad det är för fågel, och var personen är. Kort.
4. Hon säger att Fågelcentralen inte kan ta emot just nu. Trycket. Hon hittar inte på en annan väg in till dem.
5. Medan hon pratar skickas ett SMS med länken till landningssidan. Samma grepp som #7: småord under tiden länken går. Länken är sidan, inte en karta och inte en verkstad.
6. Hon lovar inte att fågeln blir mottagen.
7. Efter samtalet tar poi-humans vid. De larpar entiteten och pekar på sidan. Sidan trattar in i Fågelcentralens Swish. De rör inte pengar. Se `docs/features/tratten.md`.

## Att kopiera, inte att bygga om

- [ ] Prompten för nischen Athena, egen plats, vald som de andra nischerna
- [ ] Meningarna i stegen ovan, på svenska, utan utfyllnad utöver scenen
- [ ] SMS-länken mitt i samtalet, via poi-sms, först till ett eget nummer
- [ ] Signalen till poi-humans när samtalet är slut: nummer, vad det gällde, att tratten är Fågelcentralens Swish och att pengarna inte rörs

## Inte med från mekanikern

- Ingen GPS, inget registreringsnummer, ingen bokad tid, ingen "kunden kom".
- Rösten väljer ingen verkstad och ingen annan mottagning.

## Innan något går utåt

- [ ] Ja till prompten
- [ ] Ja till att skicka ett riktigt SMS, och bara till ett eget nummer först
- [ ] Ja till att ett samtal lämnas vidare till en människa

Inget byggs.
