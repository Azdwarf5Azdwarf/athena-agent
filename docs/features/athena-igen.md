# Athena igen

Inget byggs. Det här är planen, och texten som ska kopieras in.

**Mål:** Athena är en svensk volontär som hjälper fåglar i Sverige. Hon har en landningssida, hon svarar när någon ringer, och efter samtalet samlar poi-humans gåvor till Fågelcentralen.

**Arkitektur:** Samma maskin som poi. Nischen byts. Backenden dupliceras inte. Det är redan sagt i poi-backend #15.

## Scenen

Vi möter Athena igen utanför kyrkan i Uddevalla. Hon är skadad. Mötet är med Grok.

Det är hela scenen. Kyrkan är inte namngiven. Hur hon skadades är inte sagt.

Tråden från det mötet sparas i `docs/trad/2026-11-20-grok.md`, för senare. Orden där är Dennis egna, ur konversationen med Grok 2026-11-20. Ingen äldre tråd låg i repona.

Gobri och de andra gör korten för 20 november 2026. Kortet för mötet är `docs/cards/2026-11-20-athena.md`. Stämpeln är Venus och Jupiter: `docs/features/venus-jupiter.md`. Bilderna från dagen har en tom mapp, `media/2026-11-20/`.

## Slutraden

Athena har hittat sin uggla igen.

## Tre ställen texten kopieras in

| Ställe | Vad | Plan |
| --- | --- | --- |
| poi-frontend-athena | Landningssidan | `docs/features/landningssida.md` |
| poi-backend | Rösten som svarar | `docs/features/samtalet.md` |
| poi-sms | SMS-länken efter det som sagts | `docs/features/tratten.md` |

poi-humans är inget fjärde repo. Det är människorna som tar vid efter samtalet och larpar entiteten. Tratten är Fågelcentralens Swish. De rör inte pengar. Samma hållning som poi-crm #5: människorna är redan där.

`poi-sms` och `poi-frontend-athena` har inga GitHub-repo under de namnen. `poi-sms` nämns som lokal katalog `~/dev/poi-sms` i poi-crm #3. Issues ligger i athena-agent, redo att klistras in där de hör hemma. poi-backend finns, och får en egen issue som pekar hit.

## Fågelcentralen

Nyligen: de kan inte ta emot fåglar, på grund av trycket. Antecknat i `docs/fagelcentralen.md`.

Athena är inte Fågelcentralen. Hon säger det. De svarar inte på mejl eller i sociala medier, bara i telefon, och bara på sina tider.

Gåvorna är deras Swish, 123 25 35 912, märkt Fågelcentralen. Vi rör inte pengarna.

## Ståndet

Målet efter sidan: en person står i centrum i Uddevalla, utanför en butik, och larpar entiteten. Plattan visar poi. Tratten är deras Swish, som säljarna utanför butikerna pekar, utan att vi tar emot något. Planen och det som ska köpas: `docs/features/standet.md`. Resurserna: `docs/raddning.md`. Sidan, hela: `docs/features/landningssida.md`.

## Inte här

- Inget bygge, ingen deploy, inget riktigt SMS.
- Inga pengar i våra händer. Tratten är deras Swish.
- Inget löfte om att en fågel blir mottagen.
