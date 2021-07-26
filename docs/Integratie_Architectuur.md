---
sort: 4
---

# Integratie Architectuur
Bij <b>systeemintegratie</b> worden verschillende systemen samengevoegd, om daarna als één (nieuw) systeem te opereren.
Deze integraties worden vaak projectmatig (éénmalig) uitgevoerd. De data uit de oorspronkelijke systemen wordt daarbij gemigreerd (verplaatst).

Bij <b>systeemkoppelingen</b> is er sprake van afstemming tussen verschillende systemen (vanwege overlappende functionaliteit of datamodel). Het maken van een systeemkoppeling gebeurt via een change request (éénmalig verzoek) en kan leiden tot systeemaanpassingen. Data in deze systemen wordt over de koppeling heen en weer gesynchroniseerd.

Bij <b>data integratie</b> is er geen sprake van systeemaanpassingen. De data wordt in dit geval uit de systemen opgehaald en bij elkaar gebracht. De data is daarbij goed en eenduidig beschreven zodat deze buiten de oorspronkelijke systemen verder kan worden bewerkt.

Bij data integratie gaat het om de volgende vraagstelling:
* Wat is het doel en welke data moet daarvoor geïntegreerd worden
* Vanuit welke systemen moet de data worden geïntegreerd
* Is alle data wel aanwezig en wat is de kwaliteit daarvan
* Om welke volumes het gaat
* Wie de eigenaar is van de data
* Is er al een best-practice voor deze integratie

## Verplichte Standaarden

Bij Integratie Architectuur betreft het data die buiten de context van systemen is geplaatst. Des te belangrijker is het om afspraken te maken over meta-data, uitwisselformaten en -protocollen.

| Standaard | Typering |
|-----------|----------|
| NEN-ISO/IEC 27001 | Managementsysteem voor informatiebeveiliging |
| NEN-ISO/IEC 27002 | Richtlijnen en principes voor informatiebeveiliging |
| HTTPS en HSTS | Beveiligde websiteverbinding |
| SAML | Authenticatie en autorisatie |
| PDF (NEN-ISO) | Formaat documentpublicatie |
| OpenAPI Specification | Beschrijven van REST APIs |
| REST-API Design Rules	| Verzameling regels voor het structureren en documenteren van REST API’s |
| OWMS | Metadata overheidsinformatie |
| SKOS | Linked data en begrippenlijsten |
| Aquo-standaard (IMWA) | Watermanagement informatie |
| StUF | Uitwisseling administratieve overheidsgegevens |
| COINS | BIM uitwisselingsstandaard |
| Digikoppeling | Veilige berichtenuitwisseling |
| Digitoegankelijk (EN 301 549 met WCAG 2.1) | Toegankelijkheid websites, webapplicaties en documenten |
| Geo-Standaarden (koppelvlakken) | Geografische informatie |
| NL GOV Assurance profile for OAuth 2.0 | Beveiligingstandaard voor het autoriseren van toegang tot REST API’s |

Zie [Forum standaardisatie](https://www.forumstandaardisatie.nl/open-standaarden/verplicht

## Aanbevolen Standaarden

# Strategie
