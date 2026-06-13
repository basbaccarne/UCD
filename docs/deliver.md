# Deliver

### Feedback
Alvorens definitief in te dienen werd een moment ingelast om met studenten burgerlijk ingenieur de projecten te bespreken en feedback te ontvangen. Uit deze feedback kwamen een paar zeer interessante uitgangspunten waarvoor het op dit moment in het proces te laat is om deze te testen of aan te passen. Deze visies zijn vooral gericht op toekomstige massaproductie. Daarom is het interessant om dit mee te nemen in het proces als verdere mogelijkheden.
* **End of life**: kiezen voor recycleerbare onderdelen.
Dit is vooral van toepassing voor de projector. Deze bestaat namelijk uit elektronica met een kunststof behuizing waardoor het moeilijk te recycleren is omdat deze componenten van elkaar gescheiden moeten worden. De eigen toegevoegde steun bestaat momenteel uit PLA. In de context van massaproductie is dit niet het bestpassend uiteindelijke materiaal. Hiervoor zou hoogstwaarschijnlijk voor ABS gekozen worden. 
 
 * **Stroomvoorziening**: Nu worden de Raspberry Pi en de projector afzonderlijk gevoed. In principe is het relatief eenvoudig om met een transformator het ingangssignaal naar de projector af te tappen naar een voeding die geschikt is voor de Raspberry Pi. Zo zou één kabel allebei de onderdelen van stroom voorzien. 

 * **Projector vervangen**: Om snel een proof of concept te kunnen doen werd besloten om een draagbare projector te gebruiken. Nu de proof of concept gebeurd is kan de projector eventueel vervangen worden door een LED display. Dit zou de kost enorm verlagen en het systeem vereenvoudigen. 

* **Algoritme**: Als laatste punt van feedback werd er gesproken over een algoritme dat geluiden van kinderen en volwassenen onderscheidt. Dit zou als extra voorwaarde dienen vooraleer de projector aangaat. De microfoon laat een signaal door de treshold, waarna het algoritme nagaat als het signaal nuttig (van een kind) is. 