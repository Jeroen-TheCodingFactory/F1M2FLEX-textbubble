# Textbubble (Flat / 2D)
[![Het gerealiseerde eindproduct op desktop](https://textbubble.css-art.nl/img/textbubble.png)](https://textbubble.css-art.nl/video/promo.mp4) 
<i>Klik op de video hierboven voor een demo!</i>

Een Textbubble nagemaakt in HTML en CSS, geheel in "Flat" / 2D-design. Wanneer je klikt op de Textbubble speelt er een animatie af! 

## Intro
Bij het vak "Flex CSS-Art" leren studenten van de opleiding Software Developer op het Mediacollege (Ma) kleine kunstwerkjes maken met HTML en CSS. In week 4 (4e les) leren studenten deze Textbubble maken, in eerste instantie met een animatie die afspeelt wanneer je over de Textbubble "hovered". Voor die studenten die wat extra willen is er een animatie gerealiseerd die aan- en uitgezet kan worden door op het figure te klikken. Dit allemaal in HTML en CSS, geen JavaScript!

## Dingen die ik heb geleerd
1. Hoe een pastel achtige kleur een "mooi" effect geeft op een 2D / Flat textbubble.
2. Dat je een <code> border </code> en <code> clip-path </code> niet kan combineren aangezien de border ook weggesneden wordt. 
3. Dat je 2. kan oplossen door een element onder het andere element te plaatsen. Als je dit onderste element iets groter maakt (of het element erboven iets kleiner) en de kleur van de border (in dit geval zwart) geeft je alsnog een border kan faken. 
4. Hoe <code> appearance:none; </code> werkt.
5. Hoe je met een een <code> input </code> en <code> label </code> bepaalde styling kan toepassen / aanzetten en kan verwijderen / uitzetten.
6. Dat het <code> label </code> element geen <code> figure </code> als child mag hebben, dit geeft een fout in de W3C-validator. Hiervoor moet dus een andere oplossing (zoals <code> position: absolute; </code> van het label) geïmplementeerd worden. 
7. Dat je naast appearance ook de <code> outline </code> weg moet halen om de checkbox écht te laten verdwijnen. Dit maakt het geheel allen niet accessible (toegangkelijk). Verder onderzoek moet uitblijken hoe dit accessible gemaakt dient te worden. 
8. Samenvattend heb ik dus geleerd hoe je "click-events" kan toepassen in alleen HTML en CSS, zonder JavaScript. 


## Screenshots
Verschillende screenshots van de Textbubble op desktop. Op mobiel is alles nagenoeg gelijk. Voor de leuk wat extra screenshots gemaakt met andere achtergrondkleuren. 

### Desktop Screenshot
![Het gerealiseerde eindproduct op desktop: Textbubble met animatie, gerealiseerd in HTML en CSS](https://textbubble.css-art.nl/img/textbubble.png "Textbubble")

![Het gerealiseerde eindproduct op desktop: Textbubble met animatie, met een groen-blauwe achtergrond, gerealiseerd in HTML en CSS](https://textbubble.css-art.nl/img/textbubble--green-blue.png "Textbubble")

![Het gerealiseerde eindproduct op desktop: Textbubble met animatie, met een roze achtergrond, gerealiseerd in HTML en CSS](https://textbubble.css-art.nl/img/textbubble--pink.png "Textbubble")

![Het gerealiseerde eindproduct op desktop: Textbubble met animatie, met een rode achtergrond, gerealiseerd in HTML en CSS](https://textbubble.css-art.nl/img/textbubble--red.png "Textbubble")

## Live demo
https://textbubble.css-art.nl

## Resources
1. W3C-validator, voor het checken van mijn code => https://validator.w3.org/
2. Colorhunt, voor het kiezen van kleuren voor de achtergrond => https://colorhunt.co/
3. OpenGraph, een site voor het makkelijk genereren van Open Graph Protocol (OGP) meta-tags => https://opengraph.xyz