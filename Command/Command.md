## [Command Design Pattern](https://www.youtube.com/watch?v=9qA5kw8dcSU)

### Probleem

Het Command Design Pattern lost het probleem op van het koppelen van de uitvoering van een actie aan de aanroepende
code. Dit kan leiden tot problemen zoals:

- Het creëren van overmatige afhankelijkheden tussen klassen, waardoor de code moeilijker te onderhouden en te testen
  is.
- Het ontbreken van flexibiliteit bij het toevoegen van nieuwe acties of het aanpassen van bestaande acties, omdat de
  aanroepende code moet worden gewijzigd om de veranderingen te ondersteunen.
- Het gebrek aan ondersteuning voor undo-functionaliteit, wat belangrijk kan zijn in bepaalde toepassingen.

Door gebruik te maken van het Command Design Pattern, kan de uitvoering van een actie worden gescheiden van de
aanroepende code, wat leidt tot een meer flexibele, modulaire en onderhoudbare code. Bovendien maakt het Command Design
Pattern het gemakkelijker om undo-functionaliteit toe te voegen aan een toepassing, waardoor de gebruiker de
mogelijkheid heeft om onbedoelde acties ongedaan te maken.

> ChatGPT ftw

### Voorbeeld

Stel je voor dat we een afstandsbediening hebben die verschillende apparaten kan bedienen, zoals een televisie, een
dvd-speler en een versterker. Elk apparaat heeft verschillende knoppen op de afstandsbediening waarmee verschillende
acties kunnen worden uitgevoerd, zoals het in- en uitschakelen van het apparaat, het veranderen van het kanaal, het
verhogen of verlagen van het volume, het afspelen van een dvd, enzovoort.

### Oplossing

1. Definieer een Command interface
    - execute() methode -> voert de actie uit
    - undo() methode -> maakt de actie ongedaan
2. Definieer commando's voor elke receiver
    - elk commando implementeert de Command interface
    - elk commando heeft een receiver
    - elk commando heeft een execute() methode die de actie uitvoert op de receiver
    - elk commando heeft een undo() methode die de actie ongedaan maakt op de receiver

### Voorbeeld Vervolg

> stappen komen overeen met de stappen in de algemene oplossing

# [TERUG NAAR INHOUDSOPGAVE](../README.md)
