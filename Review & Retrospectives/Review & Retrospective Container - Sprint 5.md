# Review & Retrospective – Sprint 5
## 1.	Resultaat en doel

In deze vijfde sprint van het Container project zijn wij als groep bezig geweest met de hyperparameter tuning van het RL-model om de trainingstijd te verbeteren. We zijn ook aan de slag gegaan met het maken van een goede inleiding van de Research paper. Om vooraf een goede structuur aan de paper te geven, heb ik zelf per hoofdstuk aangegeven wat erin verteld moet worden. Hiermee kunnen mijn groepsleden makkelijker de stukken n.a.v. de taakverdeling uitschrijven. Dit was dan ook het doel wat centraal stond in deze sprint: “Model resultaat en trainingstijd verbeteren. Researchpaper inleiding opstellen en informatie geven per kop”. 

## 2.	Evaluatie
• **Wat ging er goed?**

Binnen deze sprint vond ik de stuursessie met de begeleidende docent omtrent het model en de research paper erg nuttig. Bepaalde termen van hyperparameters waren voor ons nieuw, waardoor we niet goed wisten wat het inhield. Daarvoor hadden we dus wat context nodig. Na het gesprek met de docent kregen wij ook het advies om meer naar de batchsize te kijken, de learning rates en dat we het model moesten trainen op de GPU-server. Dit was voor nu de prioriteit op het gebied van RL. Voor de paper kregen we ook goede feedback. We wisten meer wat er per hoofdstuk verteld moest worden en een meer logisch verband te creëren onder de hoofdstukken in de paper. Het verkrijgen van de feedback en het verwerken ervan vond ik in deze sprint dus erg handig.

•	**Wat ging er fout of kan beter?**

In deze sprint hadden we wat moeite met het optimaal krijgen van het RL-model. De voornaamste reden hiervoor was dat we het model programmeerde met behulp van tensorboard. Bij het runnen lukte het vaak niet, omdat in Jupyterhub geen tensorboard was geïnstalleerd. Hierdoor hadden we tijd nodig om goed uit te zoeken wat een andere manier is om bepaalde visualisaties te verkrijgen die de performance van het trainen konden inzien. 

•	**Hoe gaan deze verbeteringen er komen?**

Momenteel zijn we nog bezig met hoe we het bepaalde visualisaties kunnen verkrijgen over de rewardfuncties en over de lengte van een bepaald episode. Richal (mijn groepsgenoot) vond een manier om de visualisaties in te kunnen zien door het aanmaken van loggings. Deze loggings zouden dan lokaal gedownload worden en vanuit Windows administrator in tensorboard geopend worden. Momenteel zijn we daar dus nog mee bezig om te kijken of deze alternatief goed werkt. 
