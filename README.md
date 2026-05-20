# Verblijfskosten en nachttoeslag calculator

Een enkelvoudig HTML-hulpmiddel voor salarisadministratie. Laad een MendriX TMS salarisrapport (`.xlsx`) in en zie direct per medewerker de opgebouwde verblijfskosten en nachttoeslag-uren over de geselecteerde periode.

## Wat doet het?

- Leest een MendriX exportbestand in — rechtstreeks in de browser, er worden geen gegevens verstuurd
- Berekent per medewerker:
  - **Verblijfskosten** (in euro's)
  - **Nachttoeslag uren** (19%-toeslag, weergegeven in uren)
- Toont een overzichtstabel met sortering op naam, code, verblijf of nachttoeslag
- Zoekfunctie op naam of medewerkerscode
- Samenvattende totalen bovenaan (medewerkers, totaal verblijfskosten, totaal nachttoeslag uren)

## Gebruik

1. Download `verblijf_nacht_calculator.html`
2. Open het bestand in een moderne browser (Chrome, Edge, Firefox)
3. Sleep een MendriX TMS exportbestand (`.xlsx`) op het uploadgebied, of klik om een bestand te kiezen
4. De resultaten verschijnen direct in de tabel

> Geen installatie, geen server, geen internet vereist. Alle berekeningen vinden lokaal in de browser plaats.

## Bestandsformaat

Het hulpmiddel verwacht een MendriX TMS exportbestand in het formaat **Samenvatting voor salarisadministratie**. Klik op de knop **ℹ Hoe kom ik aan het rapport bestand?** in de applicatie voor instructies.

## Technisch

- Puur HTML + JavaScript, geen externe afhankelijkheden behalve [SheetJS (xlsx)](https://sheetjs.com/) voor het lezen van `.xlsx`-bestanden
- Werkt volledig offline
- Ondersteunt licht- en donkermodus

## Auteur

Gemaakt door **Jeroen Krajenbrink** — 2026  
[github.com/jeroenk22](https://github.com/jeroenk22)
