# Tratten

Kopieras in i **poi-sms**, och är arbetet för **poi-humans**.

Planen runt om: `docs/features/athena-igen.md`. Landningssidan: `docs/features/landningssida.md`. Samtalet: `docs/features/samtalet.md`.

Förebild: poi-crm #3, telefon in och SMS som bär beskedet. Och poi-crm #5, människorna är redan där när samtalet är slut.

## Ordningen

1. Någon har talat med Athena.
2. SMS:et har gått, eller går i slutet av samtalet, med länken till sidan.
3. poi-humans tar vid. De larpar entiteten. De pekar på Fågelcentralens Swish. De rör inte pengarna.

Tratten börjar efter det sagda. Före samtalet visas ingen Swish. Swishnumret står på sidan, inte i SMS:et.

## SMS-texten, att klistra in

Avsändaren är fortfarande `poi-[placeholder]`, som i poi-crm #3. Platshållaren för den här nischen är Athena, inte ett bolag.

> Athena. Fågelcentralen tar inte emot fåglar just nu, trycket är för högt. Sidan: {länk}

Inget swishnummer i texten. Inget "ge nu".

## poi-humans

Människorna är entiteten efter samtalet. Sidan och SMS:et pekar. Sidan öppnar Fågelcentralens Swish. De rör inte pengar.

Öppet, och det avgörs inte här:

- [x] Hur en gåva når Fågelcentralen: deras Swish 123 25 35 912. Vi rör den inte (2026-11-20, senare). Se `docs/features/swish-bossor.md`.
- [ ] Vem av poi-humans som ringer tillbaka när fågeln fortfarande behöver någon
- [ ] Första SMS:et bara till ett eget nummer

## Inte här

Mejl. Betalning i rösten. Ett löfte om plats på Fågelcentralen.

Inget byggs.
