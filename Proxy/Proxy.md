## [Proxy Design Pattern]()

- Virtuele proxy:
  - Een virtuele proxy wordt gebruikt om de kosten van het maken van een object uit te stellen totdat het daadwerkelijk
    nodig is. Dit kan handig zijn bij het werken met objecten die veel systeembronnen vereisen of waarvan de constructie
    tijdrovend is. In plaats van het echte object direct te maken, maakt de virtuele proxy een placeholder-object dat
    als surrogaat fungeert. Het werkelijke object wordt pas gemaakt wanneer een client erom vraagt. Dit patroon kan ook
    worden gebruikt om extra functionaliteit toe te voegen aan het echte object, zoals lazy loading van gegevens.

- Beschermende proxy:
  - Een beschermende proxy wordt gebruikt om de toegang tot een object te controleren. Het controleert of de client
    geautoriseerd is om bepaalde operaties op het object uit te voeren voordat het de operatie doorstuurt naar het echte
    object. Dit patroon wordt vaak gebruikt in situaties waarin toegangscontrole en beveiliging een rol spelen, zoals
    het beperken van toegang tot bepaalde gevoelige gegevens of het afdwingen van machtigingen.

- Remote proxy:
  - Een remote proxy wordt gebruikt om de communicatie tussen een client en een object dat zich op een andere locatie
    bevindt te beheren. Het fungeert als een lokaal surrogaat voor het externe object en handelt de netwerkcommunicatie
    af, bijvoorbeeld door verzoeken door te sturen via het netwerk en de ontvangen resultaten terug te sturen naar de
    client. Dit patroon is vooral handig bij het werken met gedistribueerde systemen of bij het gebruik van services via
    een netwerk.

### Probleem

Deze proxy-patronen bieden een manier om de interactie tussen clients en objecten te beheren en extra functionaliteit
toe te voegen, zoals vertraging bij het maken van objecten, toegangscontrole of netwerkcommunicatie.

### Voorbeeld

### Oplossing

### Voorbeeld Vervolg

> stappen komen overeen met de stappen in de algemene oplossing

# [TERUG NAAR INHOUDSOPGAVE](../README.md)
