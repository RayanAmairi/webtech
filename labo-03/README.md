# Labo 3 - reflecties

Naam: Rayan Amairi

## 1. Kleurenstalen

- Welke twee waarden uit de user agent stylesheet moest je op de lijst wegwerken, en waar las je ze af?
  De padding-left en de list-style. Ik las ze af in het boxmodel-diagram.
- Wat verandert er aan de banden als je het venster hoger maakt, en wat verandert er niet?
  De banden worden hoger want ze zijn 50vh. De breedte en de kleuren blijven hetzelfde.

## 2. Slogan

- Welke property centreerde de tekst, en welke de kolom?
  text-align center voor de tekst en margin 0 auto voor de kolom.
- Waarom werkte de padding op de knop pas na `display: inline-block`?
  Een link is inline en daar telt padding boven en onder niet mee. Met inline-block is het een echte box.

## 3. Tabblad

- Wat is de visuele breedte van het tabblad, en waarom is dat exact 15rem en geen 15rem plus padding plus border?
  15rem. De reset zet box-sizing op border-box dus padding en border zitten al in de width.

## 4. Donut

- Waarom werkt `height: 70%` op de cirkel, terwijl F3.2 zegt dat een procentuele hoogte meestal niets doet?
  Omdat de ouder een vaste hoogte heeft in vh. Dan kan de browser het percentage uitrekenen.
- Tegen welke maat van de ouder rekende de browser `margin: 15%`: de breedte of de hoogte?
  De breedte. Ook voor boven en onder.

## 5. Landingspagina

- Gaf je `main` een `height` of een `min-height`, en waarom?
  min-height want de hero moet minstens 80vh zijn maar mag groeien als er meer inhoud komt.
- Wat gebeurt er met de twee helften als je een regeleinde zet tussen `</article>` en `<div class="afbeelding">`?
  Er komt een spatie tussen de twee inline-block boxen. Samen zijn ze dan breder dan 100% dus de afbeelding valt onder de tekst.

## Thuis: B3.1 (met AI of zonder AI)

Nog te doen.