# Azure resources
De naam van een Azure-VM kan bijvoorbeeld zijn: “vm-shiny-datalab-westeu-p001”.<br>
De onderliggende naamconventie is in dit geval:<br>
`<resourcetype>-<application/workload>-<subscription>-<region>-<dtap><instancenummer>`

## Snake_cased
Naamonderdelen bevatten alleen deze characters:<br>`a..z,0..9,_`

## Tags
ToDo

## Application/workload
* shiny
* etl
* sql
* ..

# Subscription
De naam van de resource-set waartoe dit onderdeel behoort. Ook wel abbonnement genoemd.
* datalab
* ..

# Region
Standaard waarde (gezien opslag van data buiten EU niet toegestaan is):
* westeu

# Dtap
De dtap is een letteraanduiding die aangeeft wat voor omgeving het betreft.

| Aanduiding | omgeving |
|------------|----------|
| d | development |
| t | test |
| a | acceptatie |
| p | productie |

# Instancenummer
Dit is wat een resourceaanduiding uniek maakt. De toekenning van dit nummer is de verantwoordelijkheid van een persoon of een script.
Het eerstvolgende (vrije) nummer is niet automatisch opvraagbaar.

