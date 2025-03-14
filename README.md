#### Kurs "Grafiska verktyg för gränssnittsdesign"

### Uppgift 1: Generera en AI-bild

- Lägg in din AI-genererade bild i README:n på repot, och förklara dess tanke/användningsområde kortfattat.

### Uppgift 2: SVG-animation

- Texten **"Flummox!"** är outline:ad i Figma för att konvertera varje enskilt tecken till vektorgrafik och sedan exporterad i SVG-format, så att textens utseende bevaras även om typsnittet saknas hos en användares dator.

- **SVG används för att skapa en textbaserad grafik**, där varje bokstav representeras av en `<path>`.
- Den här uppgiften använder **GSAP (GreenSock Animation Platform)** för att animera SVG-element, inklusive:
  - **Rotation och färgändring** av en bokstav.
  - **Upp-och-ner-hoppande rörelse** med en studseffekt.
  - **Elastisk färgskiftning** av en annan bokstav.
  - **Skalning och förflyttning** av utropstecknet.
- **Animeringarna upprepas oändligt** (`repeat: -1`) och använder `yoyo: true` för att växla mellan start- och slutläge.
- **SVG-filen är inställd med `viewBox` och `preserveAspectRatio`**, vilket gör den skalbar och responsiv.

## Live Demo

Lägg till en länk till din live-demo här:
https://medieinstitutet.github.io/fed24d-grafiska-verktyg-individuell-fridanordenlow
