# Performance Audit 

Doe een Performance audit op een bestaande website uit je eigen omgeving en rapporteer daarover.

De instructies van deze opdracht staan in [INSTRUCTIONS](https://github.com/fdnd-task/performance-audit/blob/main/docs/INSTRUCTIONS.md).


## Lumion

![image](https://github.com/user-attachments/assets/097a2a63-39a1-4ac3-8f0d-a120df7300ce)

Voor deze audit heb ik de website [lumion](https://lumion.amsterdam/) getest op Performance. Uit de analyses met Lighthouse en PageSpeed Insights blijkt dat de desktopversie uitstekend presteert (96/100), maar de mobiele versie verbeterpunten nodig heeft (67-71/100).

## Lighthouse
**Mobile**
**Resultaat**

![image](https://github.com/user-attachments/assets/48e99bab-0889-4dee-af84-5191d3c21cdc)

**Desktop**
**Resultaat**

![image](https://github.com/user-attachments/assets/920d6745-eb21-4621-aa86-1c8f42ec1c9d)

**Verschillen tussen Lighthous en PageSpeed Insights**

Uit de tests blijkt dat de website op smartphones veel trager laadt dan op computers.

Dit komt door:
* Langzame LCP: Het belangrijkste element (zoals een grote afbeelding of koptekst) verschijnt op mobiel veel langzamer terwijl dit op desktop snel zichtbaar word.
* Render-blokkades: CSS- en JavaScript-bestanden houden de pagina tegen bij het opbouwen.
* Externe vertragers: Google Fonts en Analytics zorgen voor extra wachttijd.

## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).
