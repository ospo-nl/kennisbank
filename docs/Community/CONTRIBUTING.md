# Contributing Guide

> _Voor het maken van een eigen CONTRIBUTING kijk onderaan bij [Attribution](#attribution)_

Om te beginnen, hartelijk dank voor je interesse om bij te dragen aan dit OSPO-NL initiatief! Door te delen in kennis en
ervaring en samen te werken komen we tot 'best practices' en hulp om Open Source projecten in Nederland goed te
organiseren.

> **For non-Dutch native readers**: First off, thank you for your interest to contribute to this OSPO-NL initiative! By
> sharing knowledge and experiences and collaborate we'll be able to produce Best Practices and help to set up Open
> Source projects in The Netherlands. Because the gap between needs and knowledge in The Netherlands the content of this
> initiative will be mainly in Dutch.
>
> We are very sorry if this creates a feeling of not being inclusive ... which is of course against our [Code of
> Conduct](CODE_OF_CONDUCT.md); We would like to be as inclusive as possible!
>
> BUT to choose to write mainly in Dutch we will be more inclusive to the less equiped and Dutch native readers of our
> content and those are the primary focus of these practices. Nonetheless, much content is probably not managed here or
> produced inside these repositories but will be linked to or just translated summaries of content elsewhere.

Door deze richtlijnen te volgen, communiceer je dat je de tijd respecteert van de ontwikkelaars die dit open
source-project beheren en ontwikkelen. In ruil daarvoor moeten ze dat respect beantwoorden bij het aanpakken van uw
melding, het beoordelen van wijzigingen en het helpen afronden van uw pull requests.

Houd een open geest! Het verbeteren van documentatie, melden van fouten, of bijdragen aandragen zijn voorbeelden van
nuttige bijdragen. Veel informatie is mogelijk al ergens beschikbaar, waarschijnlijk in het Engels, en het verwijzen
naar andere documentatie helpt ons allemaal. Helemaal als daar samenvattingen (of volledige) vertalingen van in het
Nederlands toegevoegd worden (daar of in dit project)!

Mochten bijdragen niet voldoen aan deze richtlijnen dan houden wij ons de vrijheid om commentaren te negeren en
bijdragen te sluiten. Daarbij zullen wij verwijzen naar deze richtlijnen / Contributing Guide.

> En als je het project leuk vindt, maar gewoon geen tijd hebt om bij te dragen, is dat prima. Er zijn andere eenvoudige
> manieren om het project te steunen en je waardering te tonen, waar we ook erg blij mee zijn:
>
> - Geef het project een ster
> - Tweet erover
> - Verwijs naar dit project in de readme van uw project
> - Noem het project op lokale meetups en vertel het aan je vrienden/collega's

# Basis regels

## Gedragscode

Dit project en iedereen die eraan deelneemt, wordt bestuurd door de [OSPO-NL Gedragscode](CODE_OF_CONDUCT.md). Door deel
te nemen, wordt van u verwacht dat u zich aan deze code houdt. Gelieve onaanvaardbaar gedrag te melden volgens de
[Gedragscode#Handhaving](CODE_OF_CONDUCT.md#handhaving).

## Verwachtingen

Vrijwel alle content is beschreven in Markdown. Daarbij maken wij gebruik van MkDocs Material om alle documentatie te
publiceren. Bij gebruik van plaatjes is het fijn als de bron daarvan ook onderdeel is van dit project ... en bij
voorkeur in een open formaat. Dat betekent dat deze aangepast en bijgewerkt kunnen worden zonder kosten te maken voor
tools. Nogmaals: bij voorkeur.

- Zorg dat bijdragen cross-platform uitwisselbaar zijn: Windows, Mac, Linux.
- Zorg dat code en documentatie compleet is en voldoet aan de [styleguides](#styleguides).
- Maak issues aan voor elke grote wijziging en verbetering die je graag wilt maken. Bespreek de dingen transparant en
  vraag community feedback.
- Probeer bijdragen compact en klein te houden; dat draagt bij aan het behoud van overzicht en wijzigingen.
- Wees open naar nieuwe mensen en moedig nieuwe bijdragen aan van alle achtergronden.
- Issues behoren van een passend label te zijn voorzien:
  - `Bug` betekent een urgent probleem in de community of in de documentatie
  - `Enhancement` betekent een bijdrage voor uitbreiding
  - `Question` betekent een vraag

# Ik heb een vraag

> Als je een vraag wilt stellen, gaan we ervan uit dat je de beschikbare
> [documentatie](https://ospo-nl.github.io/kennisbank/) hebt gelezen.

Voordat je een vraag stelt, kun je het beste zoeken naar bestaande
[issues](https://github.com/ospo-nl/kennisbank/issues) die je kunnen helpen. Als u een geschikt probleem hebt gevonden
en nog steeds verduidelijking nodig heeft, kunt u uw vraag in dit nummer schrijven. Het is ook raadzaam om eerst op
internet naar antwoorden te zoeken.

Als je dan toch de behoefte voelt om een vraag te stellen en verduidelijking nodig hebt, raden we het volgende aan:

- Open een [issue](https://github.com/ospo-nl/kennisbank/issues/new).
- Geef het issue een passend label (zie [verwachtingen](#verwachtingen]).
- Geef zoveel mogelijk context over waar je tegenaan loopt.
- Indien van toepassing: Lever technische afhankelijkheden die relevant lijken.

We zullen het probleem dan zo snel mogelijk in behandeling nemen.

# Ik wil bijdragen

> **Juridische mededeling**
>
> Wanneer u bijdraagt aan dit project, moet u ermee instemmen dat u 100% van de inhoud hebt geschreven, dat u over de
> benodigde rechten op de inhoud beschikt en dat de inhoud die u bijdraagt onder de projectlicentie mag worden geleverd.

## Issues melden

### Voordat u een issue indient

Een goed issue zou er niet voor moeten zorgen dat anderen u moeten achtervolgen voor meer informatie. Daarom vragen we u
om dit zorgvuldig te onderzoeken, informatie te verzamelen en het probleem in detail te beschrijven in uw melding.

- Zorg ervoor dat u de nieuwste versie gebruikt.
- Lees de [documentatie](https://ospo-nl.github.io/kennisbank/) aandachtig door en ontdek of de functionaliteit al wordt
  gedekt, misschien door een individuele configuratie.
- Voer een [zoekopdracht](https://github.com/ospo-nl/kennisbank/issues) uit om te zien of de verbetering al is
  voorgesteld. Als dit het geval is, voeg dan een opmerking toe aan de bestaande uitgave in plaats van een nieuwe te
  openen.

Voor dit moment is er alleen documentatie en zijn verdere voorbereidingen niet nodig. Mocht er ooit tools en software
componenten opgeleverd worden, dan is het van belang om de details daarvan ook duidelijk te melden en te onderzoeken of
het daadwerkelijk een probleem met die software is of dat het wellicht toch een fout in uw omgeving is.

### Hoe dien ik een goed issue in?

> U mag beveiligingsgerelateerde problemen, kwetsbaarheden of issues, inclusief gevoelige informatie, nooit melden aan
> de issue tracker of elders in het openbaar. In plaats daarvan moeten gevoelige bugs per e-mail naar <TODO> worden
> gestuurd.

We gebruiken GitHub-problemen om issue en fouten op te sporen. Als u een probleem met het project tegenkomt:

- Open een [issue](https://github.com/ospo-nl/kennisbank/issues/new). (Omdat we op dit moment niet zeker weten of het
  een fout is of niet, vragen we je om nog niet over een fout te praten en het probleem niet te labelen.)
- Leg zo duidelijk mogelijk uit wat u verwacht of wens en geef suggesties voor invulling daarvan.
- Geef de informatie op die u in het vorige gedeelte hebt verzameld.

Zodra het is ingediend:

- Het projectteam zal het probleem dienovereenkomstig labelen.
- Een teamlid zal proberen het issue te begrijpen en op te volgen.

### Meer hulp

Hier zijn een paar vriendelijke (maar Engelse) handleidingen voor meer hulp en achtergronden: [First Timers
Only](http://www.firsttimersonly.com/) en [Make A Pull Request](http://makeapullrequest.com/)

## Verbeteringen voorstellen

Deze sectie begeleidt u bij het indienen van een verbeteringssuggestie voor OSPO-NL, **inclusief volledig nieuwe
functies en kleine verbeteringen aan bestaande functionaliteit**. Door deze richtlijnen te volgen, kunnen beheerders en
de community uw suggestie begrijpen en gerelateerde suggesties vinden.

### Voordat u een verbetering indient

- Zorg ervoor dat u de nieuwste versie gebruikt.
- Lees de [documentatie](https://ospo-nl.github.io/kennisbank/) aandachtig door en ontdek of de functionaliteit al wordt
  gedekt, misschien door een individuele configuratie.
- Voer een [zoekopdracht](https://github.com/ospo-nl/kennisbank/issues) uit om te zien of de verbetering al is
  voorgesteld. Als dit het geval is, voeg dan een opmerking toe aan de bestaande uitgave in plaats van een nieuwe te
  openen.
- Ga na of uw idee past binnen de reikwijdte en doelstellingen van het project. Het is aan u om een sterk pleidooi te
  houden om de ontwikkelaars van het project te overtuigen van de voordelen van deze functie. Houd er rekening mee dat
  we functies willen die nuttig zijn voor de meerderheid van onze gebruikers en niet slechts voor een kleine subgroep.
  Als u zich slechts op een minderheid van gebruikers richt, overweeg dan om een bibliotheek met add-ons/plug-ins te
  schrijven.

### Hoe dien ik een goede verbeteringssuggestie in?

Suggesties voor verbeteringen worden bijgehouden als [GitHub issues](https://github.com/ospo-nl/kennisbank/issues).

- Gebruik een **duidelijke en beschrijvende titel** voor het probleem om de suggestie te identificeren.
- Geef een stapsgewijze beschrijving van de voorgestelde verbetering met zoveel mogelijk details.
- Beschrijf het huidige gedrag en leg uit welk gedrag je in plaats daarvan verwachtte te zien en waarom. Op dit punt
  kunt u ook zien welke alternatieven niet voor u werken.
- Misschien wilt u schermafbeeldingen en geanimeerde GIF's toevoegen die u helpen de stappen te demonstreren of aan te
  geven op welk onderdeel de suggestie betrekking heeft. U kunt deze tool gebruiken om GIF's op macOS en Windows op te
  nemen, en deze tool of deze tool op Linux.
- Leg uit waarom deze verbetering nuttig zou zijn voor de meeste gebruikers van OSPO-NL. Misschien wil je ook wijzen op
  de andere projecten die het beter hebben opgelost en die als inspiratie kunnen dienen.

# Review proces

Om wijzigingen goed te kunnen beheren, volgen en uit te leggen, volgen we een eenvoudig proces van review en Pull
Requests (PRs).

- Wijzigingen wordt nooit direct op de `main` branch gedaan, maar altijd in een 'feature' branch.
- Maak een Pull Request aan zodra je klaar bent. Of maak gelijk een Draft Pull Request aan nadat u uw feature branch
  hebt aangemaakt. Zodra uw wijzigingen klaar zijn voor review, wijzigt u uw Draft PR naar 'Ready for Review'.
- Een teamlid reviewt de wijzigingen in het Pull Request en geeft commentaar en/of goedkeuring (Approve).
- Na goedkeuring kan het Pull Request gemerged worden. Hiervoor wordt standaard 'Squash & Merge' gebruikt. In geval dat
  de PR door een teamlid is ingediend, reviewt een ander teamlid de PR maar wordt de merge overgelaten aan de auteur van
  de PR.
- Na de merge dienen bijbehorende issues bijgewerkt te worden zodat deze niet onnodig open blijven staan ofwel
  beantwoord worden.

# Styleguides

## Markdown

Alle documentatie moet 'machine-readable' zijn en tegelijk ook makkelijk leesbaar en onderhoudbaar voor mensen. Daarom
maken we gebruik van **Markdown**. Zie ook [GitHub
Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
en de algemene [Markdown handleiding](https://www.markdownguide.org/basic-syntax/) (EN) (of zelfs de originele
[documentatie](https://daringfireball.net/projects/markdown/syntax)).

Alinea's worden op of binnen **120 karakters** afgekapt om versiebeheer per regel beheersbaar te maken. Dit kan
automatisch worden afgedwongen in tooling, bijv. [Rewrap in VSCode](https://stkb.github.io/Rewrap/) (keyboard shortcut:
`alt+Q`).

# Community

De OSPO-NL Community is nog in oprichting. Voor dit moment zijn er nog geen officiële kanalen en samenwerkingsverbanden
anders dan actief betrokken personen. Zie ook meer in de [over ons](https://ospo-nl.github.io/kennisbank/Over_ons).

# Attribution

Een eigen CONTRIBUTING maken is niet echt moeilijk ... en toch ook weer wel. Inspiratie voor deze variant komt van een
[template](https://github.com/nayafia/contributing-template/blob/HEAD/CONTRIBUTING-template.md) en **contributing-gen**.
[Genereer zelf](https://github.com/bttger/contributing-gen) (incl. CODE OF CONDUCT) !
