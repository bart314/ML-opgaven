# Inleiding


Machine learning is het onderdeel van de informatica dat zich bezighoudt met het analyseren van grote hoeveelheden data en op basis daarvan structuren herkennen of voorspellingen doen. Hoewel de basis voor dit vakgebied al in de jaren zestig van de vorige eeuw is gelegd (bijvoorbeeld door het baanbrekende werk van [Frank Rosenblatt](https://en.wikipedia.org/wiki/Frank_Rosenblatt), is het pas de voorbije twee decennia echt tot grote bloei gekomen. Dit heeft vooral te maken met de enorme hoeveelheid data die heden ten dage beschikbaar wordt gesteld (een fenomeen bekend onder de term [information explosion](https://en.wikipedia.org/wiki/Information_explosion) in combinatie met de grote en goedkope computationele kracht van hedendaagse computers en data-centra.

## Opgaven

Op deze pagina's zijn de weekopgaven van dit onderdeel te vinden. Deze opgaven worden gemaakt in duo's. Tijdens het eerste practicum wordt klassikaal een begin gemaakt met de opgaven: er wordt uitgelegd hoe te werken met numpy en hoe je lineaire algebra gebruikt in het domein van ML. Ook worden hier de weekopgaven verder toegelicht.

Tijdens het tweede en derde practicum worden afspraken gemaakt met individuele duo's om het werk tot dan toe te bespreken, vragen te beantwoorden en opmerkingen te plaatsen. Tijdens deze gesprekken wordt ook het begrip van de materie getoetst.

Er zijn drie weekopgaven die uiteindelijk in de voorlaatste week van het blok moeten zijn afgerond (je bent dus vrij om één en ander te plannen, zo lang je maar aan deze eis voldoet). Eventueel reparatiewerk wordt tijdens de gesprekken besproken. Mocht dat niet voor de deadline zijn afgerond, dan is er een uitloopmogelijkheid in de laatste week van het blok; dat geldt dan wel als een herkansing: als je hiervan gebruik maakt, kun je voor dit onderdeel maximaal een 6 halen. Voor het overige zijn de cijfers ONV, 6, 8 of 10.

## Opstarten

De opgaven voor elke week gaan uit van een zipje met startcode. Het geheel gaat uit van een aantal dependencies. Deze dependencies hebben we voor het gemak in een [`requirements.txt`](files/requirements.txt) gezet. Je kunt het beste een virtuele omgeving aanmaken en hierin met pip in één keer alle dependencies installeren.:

```python
baba@aurelia ~ % virtualenv ml
created virtual environment CPython3.8.7.final.0-64 in 820ms
baba@aurelia ~ % cd ml 
baba@aurelia ml % cp ~/Downloads/requirements.txt .
baba@aurelia ml % source bin/activate
(ml) baba@aurelia ml % python -m pip install -r requirements.txt 
...
(ml) baba@aurelia ml % 
```