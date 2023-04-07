```{warning}
De documentatie is nog volop in ontwikkeling
```
# Type licenties

## Open Source licenties

Nu we meer en meer gebruik maken van Open Source software, leek het me een goed idee om nog een keer stil te staan bij 
Open Source Software (OSS) Licenties en waar je op moet letten. Immers de ene OSS-licentie is de andere niet.


## Wat is een Open Source Licentie?

Alles wat je maakt valt standaard onder het auteursrecht (copyright) als onderdeel van het intellectueel eigendomsrecht
(IE-recht) en mag dus niet zomaar door derden, zonder jouw toestemming, worden (her)gebruikt of gedeeld. Binnen
softwareontwikkeling hebben we het dan vooral over het ontwikkelen van broncode. Door aan iemand of groepen een
gebruikerslicentie af te geven kunnen met bepaalde voorwaarden de beperkingen van het auteursrecht worden versoepelt. 
Je kan bijv. specifieke gebruikers een licentie geven de code te mogen gebruiken, te wijzigingen en/of te verspreiden.
Een open source software (OSS) licentie standaardiseert de belangrijkste aspecten die nodig zijn voor een vrije omgang
met het auteursrecht. Het gebruik van gestandaardiseerde licenties maakt het voor jezelf makkelijker om niet in juridische
valkuilen te stappen bij het opstellen van een licentie en het geeft gebruikers sneller duidelijkheid wat je precies voor
ogen hebt met je broncode. Daar bovenop worden de kernwaarden van OSS (zoals verwoord door de Open Source Initiative) naar
de buitenwereld gecommuniceerd. Het betreft dan:

- Vrij recht op verdere distributie
- Vrijheid tot aanpassingen en afleiden van werk
- Verregaande uitsluiting van verantwoordelijkheid van de auteurs op het (her)gebruik van hun werk
- Bewaking van de integriteit van de auteurs
- Bewaking van digitale rechten.

Een OSS-licentie regelt daarmee (tot zekere hoogte) verschillende aspecten rond IE-rechten en aansprakelijkheid. 
Zonder het verbinden van een OSS licentie aan broncode is er van OSS geen sprake. Broncodes kunnen nog steeds wel 
ingezien worden t.b.v. transparantie, maar niet gebruikt worden (door anderen) voor doorontwikkeling.

Het effect van OSS is dat de code van software open en vrij beschikbaar is voor iedereen, zodat iedereen voort kan 
bouwen op de software, de eventuele bugs in software kan herstellen, de software kan voorzien van nieuwe features en 
de software kan integreren in andere applicaties of delen hergebruiken in compleet andere situaties. In zijn
algemeenheid hebben OSS licenties bovenstaande elementen gemeen.

## Welke type OSS Licenties zijn er?
Vaak worden OSS licenties onderscheiden op het type wederkerigheid dat gehanteerd wordt. Dat principe wordt ook wel 
‘copyleft’ genoemd, om de tegenhang met het protectionistische auteursrecht aan te geven. We maken dit onderscheid 
omdat de mate van wederkerigheid een sterk effect heeft op de regels die moeten worden nageleefd. We onderscheiden 
dan 3 smaken:

### Permissive (toegeeflijk):
De broncode mag naar eigen inzicht worden aangepast waaarbij de aangepaste broncode niet opnieuw openbaar gemaakt 
hoeft te worden. Dit type broncode kan dus vrij gebruikt worden in gesloten software. In geval van de Apache 2.0 
licentie ben je wel verplicht kenbaar te maken welke eventuele veranderingen er hebben plaatsgevonden op de 
oorspronkelijke code. In de meeste gevallen ben je ook verplicht om een verwijzing naar de oorspronkelijk code en 
auteurs te op te nemen in het eindproduct. Waarbij de MIT-0 variant die laatste verplichting echter weer niet kent. 
Bekende voorbeelden zijn: Apache 2.0, BSD en MIT.

### Reciprocal / weak copyleft (zwak wederkerig):
Deze licentie is iets beperkter dan de permissive licenties. Je bent namelijk verplicht om alle veranderingen aan de 
oorspronkelijke code ook weer OSS beschikbaar te maken. Dus niet alleen kenbaar maken welke verbeteringen er zijn 
gedaan, maar de letterlijk verbeterde broncode. De software waarbinnen de betreffende broncode is gebruikt hoeft niet 
OSS te zijn als geheel. Zo kunnen broncodes met deze licenties ook zonder problemen in gesloten software gebruikt 
worden. Bekende voorbeelden zijn: MPL v2.0, EUPL v1.2

### Restricted / strong copyleft (sterk wederkerig):
Deze broncode brengt bovenop de vorige licentie nog een zogenaamd 'viraal' effect mee. Dat betekent dat de 
softwareoplossing waarbinnen dit type broncode wordt gebruikt 'geïnfecteerd' raakt door deze licentie. Als je dus
GPLv3 broncode gebruikt in een groter geheel, dan moet het grotere geheel ook onder de GPLv3 licentie beschikbaar 
gesteld worden.
Vooorbeeld: Software A bestaat uit component A (MIT), B (EUPL) en C (GPLv3). Dat betekent dat software A als geheel 
onder de GPLv3 licentie valt. Component A en component B kunnen nog steeds wel onafhankelijk hergebruikt worden onder 
hun oorspronkelijke licentie. Strong copyleft licenties zijn dus niet verenigbaar met gesloten software. Het bekendste 
voorbeeld is: GPLv3.

Een variant van de GPLv3 is de LGPLv3. De LGPL vermindert het virale effect door een totale software oplossing niet 
te infecteren met de licentie van het hergebruikte component wanneer het als library (soft-linked) wordt gekoppeld.

### Noten

Een OSS licentie uit de smaak ‘Restricted / strong copyleft’ vergt meer kennis van deze betreffende OSS licentie om 
deze juist te kunnen toe te passen. Als je gebruikt maakt van OSS met een OSS licentie uit deze smaak dien je met meer 
voorwaarden rekening te houden. Wanneer je onjuist rekening houd met deze voorwaarden loop je het risico dat je 
aangesproken / aangeklaagd voor auteursrechtschending door de oorspronkelijke maker.

Met een OSS licentie geef je de controle uit handen op welke manier je broncode gebruikt gaat worden in nieuwe 
toepassingen. Je broncode kan dus gebruikt worden voor de ontwikkeling van levensreddende medicijnen, maar net zo goed 
in een kernwapen waarmee de mensheid wordt vernietigd.

Verder is het goed om te realiseren dat een OSS licentie geen openbaarheid afdwingt. Wat een OSS licentie afdwingt is 
het recht van vrije distributie. Dat recht wordt pas actief wanneer er sprake is van daadwerkelijke distrubitie oftewel 
verspreiding van de software en/of broncode. Wanneer je binnen je organisatie aan OSS software werkt die verder niet 
buiten de organisatie is gedeeld, dan is er geen sprake van verspreiding. Het recht op vrije distributie geldt dan dus 
niet. Het voordeel hiervan is dat je in organisatorisch verband (bijv. in een stichting) toch elkaar de vrijheid kan 
geven aan broncode te werken, zonder de plicht de broncode openbaar te moeten maken. Alleen, op het moment dat de 
broncode of het eindproduct wel buiten je organisatie bewust is gedeeld, dan heeft iedereen die aan de broncode heeft 
gewerkt het recht (die versie van) de broncode ook verder te verspreiden.

Andersom kan broncode ook openbaar worden gemaakt zonder OSS licentie. Daarmee blijft de broncode auteursrechtelijk
beschermd en kan het dus niet worden hergebruikt, aangepast of worden gedeeld. Openbaarmaking geeft wel inzicht in
de broncode.

## OSPO Reviewed License checklist

Om de toetsing en het gebruik van OSS licenties makkelijker te maken, kan een OSPO Reviewed License checklist helpen. 
OSPO Reviewed License checklist bevat een overzicht van veel gebruikte OSS licenties en of deze toegestaan zijn voor 
gebruik binnen je organisatie. Hiermee kun je een helder referentiekader neer te zetten voor je organisatie m.b.t. 
gebruik van OSS licenties.

Bronnen:
- https://www.gnu.org/licenses/gpl-faq.en.html#InternalDistribution
- https://www.mozilla.org/en-US/MPL/2.0/FAQ/ (Q6)


