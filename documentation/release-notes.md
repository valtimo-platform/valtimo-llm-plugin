# Release notes

Overzicht van wijzigingen per versie van de Valtimo LLM-plugin.

## 6.1.0

Met het nieuwe veld **Model** in de pluginconfiguratie kies je welk taalmodel de acties **Give summary**, **Chat** en *
*AI chat with Memory** gebruiken. De plugin werkt daarmee met elke OpenAI-compatibele chat-API, zoals een lokale Ollama.
Blijft het veld leeg, dan gebruikt de plugin zoals voorheen `open-mistral-nemo-2407`; bestaande configuraties werken dus
ongewijzigd.

De acties van verschillende pluginconfiguraties die tegelijk draaien, gebruiken nu altijd de URL, het token en het model
van hun eigen configuratie; voorheen konden ze die van elkaar overnemen. Een API-URL met een pad maar zonder slash aan
het eind wordt nu onder dat pad aangeroepen.

## 6.0.3

Ondersteuning voor Valtimo 13.48.0.

## 6.0.2

Valtimo bijgewerkt naar versie 13.41.0.

## 6.0.1

Versienummer gelijkgetrokken met de al gepubliceerde 6.0.0. Deze release bevat geen functionele wijzigingen.

## 6.0.0

Uitgebracht vanuit de monorepo; deze release stond niet in de release notes van deze repository.

## 5.4.4

Ondergebracht in een eigen repository met voorbeeldapplicatie, aparte documentatie en een PR-checks workflow. Broncode
gesynchroniseerd met de monorepo en ktlint-issues opgelost.

## 5.4.3

Versie-ophoging van Valtimo LLM.

## 5.4.2

Verbeteringen en opschoning: NotifyNL-tekst verwijderd uit plugin-acties, logica verplaatst van client- naar
domeinpakket, tokenauthenticatie opnieuw geïmplementeerd, vertalingen en camelCase-consistentie verbeterd, ongebruikte
afhankelijkheden en configuratievariabelen opgeruimd.

## 5.4.1

Tussentijdse versie-ophoging.

## 5.4.0

Eerste release onder de naam Valtimo LLM (voorheen Mistral): tekst samenvatten en chatten via Mistral.
