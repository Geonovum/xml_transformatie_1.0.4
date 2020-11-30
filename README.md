# xml_transformatie_1.0.4
Deze workflow zet aangeleverde besluiten in 1.0.3 om naar 1.0.4. Dit kan door een opdracht.zip te pushen naar de repository. Daarvoor zijn twee werkwijzen:
1. De repository klonen en lokaal bestand opdracht.zip plaatsen. Na pushen start een action-script dat de transformatie uitvoert.
2. Op GitHub met 'upload file' een opdracht.zip toevoegen. Na commit start een action-script.

Het resultaat wordt op GitHub geplaatst onder de tab Actions. Hierin staat een overzicht van de uitgevoerde uploads. Selecteer de bovenste actie. Het resultaat van de actie staat bij Artifacts.