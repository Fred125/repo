# Azure resources
De naamconventie voor Azure resources is:<br>`<resourcetype>-<application/workload>-<subscription>-<region>-<dtap><instancenummer>`

Voorbeeld van een Azure-VM instantie:<br>`vm-shiny-datalab-westeu-p001`

Meer informatie:
* [Microsoft Azure naming conventions](https://azurelessons.com/microsoft-azure-naming-conventions/#:~:text=Below%20are%20some%20Naming%20rules%20and%20restrictions%20as,to%2050%20characters.%20It%20should%20contain%20alphanumeric%20characters.)
* [Microsoft Azure naming conventions (Lessons)](https://azurelessons.com/microsoft-azure-naming-conventions/#:~:text=Below%20are%20some%20Naming%20rules%20and%20restrictions%20as,to%2050%20characters.%20It%20should%20contain%20alphanumeric%20characters.)
* [Develop your naming and tagging strategy for Azure resources](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-best-practices/naming-and-tagging)

## Lettertype
* Alle onderdelen van een resourcenaam bevatten deze characters:<br>`snake_case: a..z,0..9,_` 
* Alle onderdelen van een resourcenaam worden met elkaar verbonden met dit koppelteken:<br>`-`

## Gebruik van tags
ToDo

## Resource type

|     Typeaanduiding       | Omschrijving |
|------------|----------|
| adf | Azure Data Factory |
| dbs | Databricks Service|
| kv | Key Vault |
| log | Log Analytics |
| pip | Public IP |
| st | Storage Account |
| vm | Virtual Machine |
| .. | .. |

Meer typeaanduidingen: [Recommended abbreviations for Azure resource types](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-best-practices/resource-abbreviations)

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
De dtap is een aanduiding die aangeeft wat voor omgeving het betreft.

| Type omgeving | Omschrijving |
|------------|----------|
| d | development |
| t | test |
| a | acceptatie |
| p | productie |

# Instancenummer
Dit is wat een resourcenaam uniek maakt. De toekenning van dit nummer is de verantwoordelijkheid van een persoon of een script.
Het eerstvolgende (vrije) nummer is niet automatisch opvraagbaar.

