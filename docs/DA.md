---
sort: 3
---

# Data Architectuur

## Principes

In het kader van het project OMDISK zijn de volgende dataprincipes verzameld en vastgesteld.

| Nummer | Principe |
|--------|----------|
| [GP-01](DA/GP-01.md) | Toegankelijkheid informatie |
| [GP-02](DA/GP-02.md) | Hanteren gemeenschappelijk begrippenkader |
| [GP-03](DA/GP-03.md) | Borgen gegevenskwaliteit |
| [GP-04](DA/GP-04.md) | Beleggen gegevensverantwoordelijkheid |
| [GP-05](DA/GP-05.md) | Hanteren basis- en ketenregistraties |
| [GP-06](DA/GP-06.md) | Hanteren kernregisters |
| [GP-07](DA/GP-07.md) | Terugmelden gerede twijfel juistheid |
| [GP-08](DA/GP-08.md) | Vastleggen metadata |
| [GP-09](DA/GP-09.md) | Hanteren gemeenschappelijk Aa en Maas-gegevensmodel |
| [GP-10](DA/GP-10.md) | Archiveren gegevens waar vereist |
| [GP-11](DA/GP-11.md) | Vastlegging en controle bij de bron |


De [WILMA](https://wilmaonline.nl) (waterschaps referentie architectuur) kent een beperkt aantal afgeleide principes aangaande de datalaag:

| Nummer | Afgeleid principe |
|--------|----------|
| [AP03](https://www.wilmaonline.nl/index.php/WILMA/id-6f81305c-9c48-4145-a9e1-23c8bd428eaf) | Eén authentieke bron |
| [AP04](https://www.wilmaonline.nl/index.php/WILMA/id-a60f29f9-0092-42be-a9f8-dc20515b1a59) | Doelmatige gegevensvastlegging en -verwerking |
| [AP17](https://www.wilmaonline.nl/index.php/WILMA/id-63fc8dc3-0f9d-4226-b075-28050f93e692) | De dienstverlener verschaft alleen geautoriseerde afnemers toegang tot vertrouwelijke gegevens |
| [AP18](https://www.wilmaonline.nl/index.php/WILMA/id-2842c036-aaca-48ac-9abe-78a5e63ee9d0) | De dienstverlener waarborgt de integriteit van gegevens en systeemfuncties |


De [GEMMA](https://www.gemmaonline.nl/index.php/Gemeentelijke_Model_Architectuur_(GEMMA)) (gemeentelijke referentie architectuur) noemt 3 hoofd- en 8 afgeleide principes (zie [Tactisch Gegevensmanagement](https://www.gemmaonline.nl/index.php/GMT_Principes)). Deze principes houden we in het achterhoofd: in essentie wijken ze niet af, maar geven soms net even een andere context.

| Nummer | Hoofdprincipe |
|--------|----------|
| GM-BP1 | Gegevens zijn een bedrijfsmiddel en hebben waarde |
| GM-BP2 | Gegevens worden gedeeld |
| GM-BP3 | Gegevens worden conform wet- en regelgeving verwerkt |

| Nummer | Afgeleid principe |
|--------|----------|
| GM-AP1 | We winnen gegevens eenmalig in en gebruiken ze meervoudig |
| GM-AP2 | We beheren de kwaliteit van gegevens actief |
| GM-AP3 | We borgen de beschikbaarheid, vertrouwelijkheid en integriteit van gegevens |
| GM-AP4 | We melden gerede twijfel aan de bronhouder terug|
| GM-AP5 | We verantwoorden de verwerking van persoonsgegevens |
| GM-AP6 | We hanteren uniforme definities voor gegevens |
| GM-AP7 | We borgen de duurzame toegankelijkheid van gegevens daar waar dat vereist is |
| GM-AP8 | We kennen de waarde van gegevens en de positie van deze gegevens in het informatievoorzieningsproces en dit dragen we ook uit |


# Diensten en Producten

## Woordenboek
Het woordenboek bevat de begrippen die in de organisatie gebruikt worden (thesaurus), gekoppeld aan andere begrippenlijsten (zoals die op [overheid.nl](https://www.overheid.nl/help/officiele-bekendmakingen/begrippenlijst#H)]) en andere thesaurussen (bijvoorbeeld [standaarden.overheid.nl](https://standaarden.overheid.nl/owms/terms/Thesaurus))

## CDM
Een Canonical Datamodel (CDM) beschrijft alle gebruikte (bron)data in de meest simpele vorm ter ondersteuning van gegevensuitwisseling tussen diverse systemen (ongeacht taal-, syntax en protocol verschillen).

## Kwaliteitshandboek

## AVG Verwerkingsregister
Dit register bevat alle databeschrijvingen die aan personen gerelateerd kunnen worden met de actoren die deze data gebruiken en de verwerkingsovereenkomsten die dat gebruik autoriseren.<br>
Het register wordt bijgehouden in een architectuurtool (BlueDolphin) en is als PowerBI rapport beschikbaar.

## BBN Register
Het BBN register bevat een dataclassificatie in termen van Beschikbaarheid, Integriteit en Vertrouwelijkheid.<br>
Het register wordt bijgehouden in een architectuurtool (BlueDolphin) en is als PowerBI rapport beschikbaar.

## Terugmeldvoorziening
De terugmeldvoorziening is een portaal (of emailvoorziening) waar iedereen een melding kan maken van een geconstateerde afwijking in een basis-/keten-/kernregistratie. De voorziening distribueert de melding naar de gegevensbeheerder van die registratie voor verdere afhandeling

## Autorisatiemodel
Dit zijn de standaardafspraken die gelden ten aanzien van toegang tot systemen en data.

