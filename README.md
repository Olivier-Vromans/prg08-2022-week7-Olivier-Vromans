# PRG08-2022-week7
PRG08 2022 Eindopdracht deel A week 7

[screencast](https://youtu.be/YYlMBw0-6ZM)
<br>
[Protoype Website](https://olivier-vromans.github.io/prg08-2022-week7-Olivier-Vromans/)

## Stap 1 Concept

Omschrijf kort jouw concept in je inleverdocument:

- Wat is jouw TLE project, en wat is daarvoor jouw concept? Hoe draagt dit bij aan Rotterdam:Duurzame Stad?
    - Voor TLE willen wij advies geven op routes om de uitstoot van CO2 af te nemen
- Wat is de toegevoegde waarde van AI in jouw concept?
    - Voor het concept willen we de gebruiker de mogelijkheid bieden om hun eigen auto in te vullen om een nauwkeurigere resultaat terug te geven
- Welke data heb je nodig en hoe kom je daar aan?
    - uitstoot van CO2 per liter benzine/diezel. Fit kan je berekenen doormiddel van een formule.
    - uitstoot van benzine doormiddel van een dataset
    - Voor een betere accuratie maak ik gebruik van de Engine Size
    - Dit is allemaal terug te vinden in de dataset die ik van Kaggle heb gepakt en vervolgens heb aangepast.
    - Ik heb in de dataset id's toegevoegd zodat ik deze kan gebruiken om rijen met een Null waarde te verwijderen
- Welke library / algoritme denk jij dat geschikt is voor jouw concept?
    - ML5 Neural Networks, om voorspellingen te doen
    - Papa Parse, om de dataset te gebruiken
    - Scatterplot, om de data te tekenen
- Beschrijf de de uiteindelijke vorm (Website, app, installatie, etc).
    - De uitendelijke vorm is een website. hierop kunnen eindegbruikers hun eigen gegevens invullen. Hieruit komt dan de geschatte CO2 uitstoot
- Beschrijf kort de eindgebruiker en de doelgroep.
    - de eindgebruikers zijn mensen die milieu bewuster willen zijn en hiervoor kunnen zien hoeveel uitstoot ze per rit doen en daarop beslissen of ze de rit met de auto doen of met een andere vervoersmiddel

<br>
<br>
<br>

## Stap 2 Prototype

Naar aanleiding van stap 1 bouw je een werkend code prototype met behulp van de stof uit de lessen 2 t/m 7.
Het prototype gebruikt een van de algoritmes uit les 2 t/m 7. Dit mogen zijn:

- ML5 pose / hand / face model met webcam, met pre-trained model.
- ML5 Feature Extractor (dit is de image classifier met eigen images)
- KNN
- Decision Tree
- ML5 Neural Network
- Andere toepassing van een algoritme en data in overleg met docent

Je code staat in GitHub classroom. Je werkende prototype staat óók live online.
Je inleverdocument bevat een screencast van, en een link naar, je online prototype.

### Bonuspunt

Als je data van Kaggle (of andere data in een excel sheet) in je prototype gebruikt, dan heb je een scatterplot getekend om te zien welke kolommen relevant zijn.

- [Kaggle link](https://www.kaggle.com/datasets/debajyotipodder/co2-emission-by-vehicles)
- In de Scatterplot word de predication line getekend

### Bonuspunt

- Je toont de accuracy van je prototype.
    - Onder de scatterplot zijn 2 de tests die ik heb gedaan om de accuratie te testen. 
- Je hebt deze accuracy verbeterd door instellingen in het algoritme of in je data bij het trainen aan te passen. Licht toe hoe je dit gedaan hebt.
    - Ik heb gebruik gemaakt van de dataset waarin ik verschillende colomen heb toegepast om te kijken wat het beste resultaat gaf. Deze resultaten zijn ook te zien op de website.
