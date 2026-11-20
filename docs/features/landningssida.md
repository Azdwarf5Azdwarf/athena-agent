# Landningssidan

Kopieras in i **poi-frontend-athena**.

**Ansvarig: Athena** (beslut 2026-11-20). Hon äger sidan: texten, numret och Swish-bössorna.

Planen runt om: `docs/features/athena-igen.md`. Bössorna: `docs/features/swish-bossor.md`. Resurserna: `docs/raddning.md`. Ståndet som visar sidan: `docs/features/standet.md`.

Förebild: poi-admin #6, en första sida och inget annat. Här är sidan inte en inloggning. Den är scenen, telefonen, entiteten och tratten. Vi rör inte pengar.

Sidan är en kolumn i telefonen, från SMS:et. På plattan i ståndet är mitten fortfarande mitten: poi i glasets mitt, frågan vid sidan, som säljaren står vid sidan av dörren.

Inget byggs.

## Texten, att klistra in

> Vi möter henne igen utanför kyrkan i Uddevalla. Hon är skadad.
>
> Athena är en svensk volontär. Hon hjälper fåglar i Sverige.
>
> Fågelcentralen kan inte ta emot fåglar just nu. Trycket är för högt. De är inte den här sidan. De svarar i telefon, på sina tider.
>
> Ring. Athena svarar.
>
> Efter samtalet tar entiteten vid. Tratten är Fågelcentralens Swish.
>
> Athena har hittat sin uggla igen.

Frågan, bredvid mitten på plattan och under läget i telefonen:

> Swish går till Fågelcentralen.
>
> Vi rör den inte.

## Sidan, uppifrån

### 1. Mitten, poi

Bara scenen.

> Vi möter henne igen utanför kyrkan i Uddevalla. Hon är skadad.

Under den, namnet:

> Athena är en svensk volontär. Hon hjälper fåglar i Sverige.

Ett märke, ingen karta: `Här.` På ståndet är ordet platsen man står på. I telefonen efter SMS:et är det samma plats. Inga koordinater, inga andra punkter i mitten. Länken är sidan, inte en karta. Kyrkan förblir "kyrkan i Uddevalla".

### 2. Ringen

> Ring. Athena svarar.

Numret, när det finns, står här. Tills dess har raden inga siffror. Fågelcentralens akuttelefon står inte här, så ingen ringer dit och tror att det är hon.

### 3. Läget

> Fågelcentralen kan inte ta emot fåglar just nu. Trycket är för högt. De är inte den här sidan. De svarar i telefon, på sina tider.

### 4. Frågan

En mening, sedan deras QR. Inga belopp. Inget "ge nu". Ingen räknare. Vi har ingen summa.

> Swish går till Fågelcentralen.

QR för 123 25 35 912, märkning `Fågelcentralen`. Numret under koden. Bankgiro 740-8198 i mindre stil. Källa: deras egen sida, läst 20 november 2026, [fagelcentralen.se/stod-oss](https://fagelcentralen.se/stod-oss/).

> Vi rör den inte.

Ingen bössa i handen, och ingen bössa på marken. Numret på glaset är deras, redan publicerat. Personen är entiteten. Se `docs/features/swish-bossor.md`.

### 5. Efter samtalet

> Efter samtalet tar entiteten vid. Tratten är Fågelcentralens Swish.

### 6. Hittat en fågel

Tre rader, sedan stopp. Hela listan är `docs/raddning.md`. Sidan trycker inte privata rehabiliterares mobilnummer.

- Fågelcentralen, 0733-105773, varje dag 10–12 och 13–16. De tar inte emot en fågel just nu. Det här är deras telefon, inte Athenas.
- Svenska Djurambulansen, 0771-999 112. Transport i Västra Götaland, med Kungsbacka, och i Stockholms län. Inte en rehabilitering.
- Annat län: [kfv-riks.se/Kontakt](https://kfv-riks.se/Kontakt).
- Död örn, falk, glada, kärrhök, fiskgjuse eller någon av de stora ugglorna som är statens vilt: polisen 114 14. Inte ståndet.

### 7. Slutraden

> Athena har hittat sin uggla igen.

## På glaset

Plattan låses till sidan. Ljusstyrkan uppe. En laminerad A4 med samma QR när solen tar skärmen. A4:an säger samma mening och samma nummer. Den lägger inte till en berättelse.

## Vad sidan är

- En sida. Scenen i mitten, vem hon är, läget hos Fågelcentralen, att man ringer, deras Swish vid sidan, tre rader om hitta en fågel, slutraden.
- Numret i ringen är hennes nummer, när det finns.
- En tratt till Fågelcentralens Swish. Vi rör inte pengarna.

## Vad sidan inte är

- Inte en inloggning, inte flera formulär.
- Inte en karta, inte en verkstad, inte en butik.
- Inte Fågelcentralens webbplats, och inte skriven som om vi vore de.
- Inte en berättelse utöver scenen.
- Inte ett löfte om att en fågel blir mottagen.
- Inte kalender, holk eller Sponsorhuset. Det säljer de själva.

## Öppet

- [ ] Vilket nummer som står i ringen
- [x] Om gåvan pekar på Fågelcentralens egna sätt att ta emot: ja, tratten är deras Swish (2026-11-20)
- [x] Fågelcentralens Swish-nummer verifierat mot fagelcentralen.se/stod-oss, 20 november 2026: 123 25 35 912, märk `Fågelcentralen`. Bankgiro 740-8198
- [x] Vi ställer inte ut en bössa och vi rör inte pengar. Entiteten larpas. Tratten är deras nummer (2026-11-20, senare)
- [ ] Repo `poi-frontend-athena` finns inte på GitHub än. Texten väntar här

Inget byggs.
