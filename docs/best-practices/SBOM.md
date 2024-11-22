# Software Bill of Materials (SBOM) | Wat, waarom en hoe?

De moderne digitale wereld kan niet zonder (open source) software. Veel van de software die we dagelijks gebruiken, bestaat uit complexe componenten die door verschillende ontwikkelaars en leveranciers zijn gecreëerd. Maar hoe weet je precies welke componenten er in een stuk software zitten? Het antwoord ligt in een Software Bill of Materials (SBOM). Zowel van uit Open Source Foundations als Cyber Security Centres is veel aandacht voor SBOM. Zo heeft Open Source Security Foundation een [‘SBOM Everywhere’](https://openssf.org/blog/2023/06/30/sbom-everywhere-and-the-security-tooling-working-group-providing-the-best-security-tools-for-open-source-developers/)  initiatief gestart en heeft het Nationaal Cyber Security Centrum (NCSC) heeft een paar maanden terug een nieuwe gids uitgebracht: [de SBOM Startersgids](https://www.ncsc.nl/documenten/publicaties/2023/juli/5/sbom-startersgids) . Deze gids is ontworpen om organisaties te helpen SBOM’s beter te begrijpen en hoe ze SBOM’s kunnen integreren in hun softwareontwikkelingsprocessen. Deze best pratcice geeft inzicht in wat SBOM’s inhouden en waarom ze van belang zijn.

## 1. Wat is een SBOM?
Een SBOM is een gedetailleerde lijst softwarecomponenten die in een stuk software zijn opgenomen. Het biedt een volledige weergave van alle softwarecomponenten, inclusief open-source libaries, commerciële componenten, en zelfgeschreven code die deel uitmaakt van het softwareproduct. In essentie is een SBOM de ingrediëntenlijst van een softwareproduct.

## 2. Waarom is een SBOM belangrijk?
Een SBOM is een belangrijke tool om inzicht te krijgen in potentiële technische kwetsbaarheden die verbonden zijn aan hun software. Het helpt organisaties te begrijpen van welke softwarecomponenten ze afhankelijk zijn, waar deze softwarecomponenten worden gebruikt, en hoe dit hen kan blootstellen aan potentiële security risico's. Een SBOM is tevens van cruciaal belang om adequaat te kunnen reageren op nieuwe technische kwetsbaarheden in softwarecomponenten omdat snel de impact bepaald kan worden.

## 3. Wat staat er in een SBOM?
Hoewel er momenteel geen uniforme beschrijving is van hoe een SBOM er precies uit moet zien of welke elementen het moet bevatten, stelt de in ontwikkeling zijnde update van ISO/IEC 27036-3 een set van essentiële elementen voor die een SBOM moet bevatten. Dit omvat informatie zoals de auteur van de SBOM, een tijdstempel, informatie over de levenscyclus, leveranciersnaam, componentnaam, versie, een unieke identifier en andere relevante details.

## 4. SBOM-Standaarden
Er bestaan momenteel twee populaire SBOM-standaarden: de Software Package Data Exchange (SPDX) en CycloneDX. Beide zijn open-source standaarden, waarbij de eerste een ISO-gecertificeerde standaard is. Het wordt aangeraden om zowel SPDX als CycloneDX te ondersteunen, omdat er voldoende overlap is tussen de verschillende velden en de essentiële elementen kunnen worden beschreven in alle standaarden. Bovendien krijg je als organisatie al snel met beide varianten te maken door de verscheidenheid aan tools en partijen.

## 5. Implementatie van SBOM in een organisatie
De implementatie van SBOM in een organisatie vereist enkele overwegingen. Organisaties moeten processen vaststellen voor het genereren, beheren en delen van SBOMs. Dit omvat het maken van afspraken met softwareleveranciers over het leveren van SBOMs, het genereren van SBOMs voor zelfontwikkelde software of software waar geen SBOM voor beschikbaar is, en het organiseren van processen voor het up-to-date houden en delen van SBOMs.

## 6. SBOM en Vulnerability Management
Een SBOM kan zeer nuttig zijn voor het beheer van technische kwetsbaarheden. Door inzicht te krijgen in de softwarecomponenten die deel uitmaken van een softwareproduct, kunnen teams sneller en efficiënter kwetsbaarheden identificeren en mitigeren. 

## 7. Slotgedachte
Een SBOM is een cruciaal hulpmiddel om de transparantie te verhogen en de beveiliging in de software supply chain te versterken. Hoewel er momenteel nog discussies gaande zijn over de exacte vorm en inhoud van SBOMs, kun je wel al beginnen met het toepassen ervan. 
