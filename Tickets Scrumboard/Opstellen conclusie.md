# Opstellen Conclusie + future work

Binnen deze Scrum ticket heb ik het hoofdstuk 'Conclusie' in het research paper opgesteld. Dat hoofdstuk heb ik kunnen opstellen door alle hoofdstukken in de paper samen te vatten en er een passende eindconclusie aan te koppelen. Het opstellen van de conclusie hoofdstuk ging niet in één keer. Ik heb namelijk feedback opgevraagd bij de begeleidende docent om (voor zover dat kan) de conclusie hoofdstuk in de paper te verbeteren. Na de feedback te hebben ontvangen ben ik deze meteen gaan verwerken in de paper om een definitieve versie neer te zetten. Zie [hier de Scrum ticket](https://github.com/akram090/Portfolio-Applied-Data-Science/blob/main/Tickets%20Scrumboard/Ticket%20opstellen%20conclusie%20paper.png) uit het scrumboard voor het opstellen van de conclusie.
 
Naast het opstellen van de eindconlusie, heb ik ook een aanbeveling gedaan voor vervolgonderzoek. Hierin gaf ik een drietal punten mee die voor in een vervolgonderzoek verder onderzocht moeten worden:

1. Uitbreiding van de gesimuleerde container environment in de hoogte (3x3x1 naar 3x3x3 bijv.)
2. Uitbreiden van de rewardfunctie naar het kunnen identificeren van gelijksoortige containerbestemmingen die op of onder elkaar zitten.
3. Rekening houden met toegankelijkheid van een reachstacker voor het plaatsen van een container (bepaalde containers kunnen ervoor zorgen dat beschikbare locaties worden afgesloten)


Zie hieronder het hoofdstuk 'Conclusie' wat in onze paper is geschreven:

De hoofdvraag dat in dit project centraal stond, luidt als volgt “Hoe kan ervoor gezorgd worden dat containers op de kade op een efficiënte manier opgestapeld kunnen worden, zodat de afnemer van de containers hier makkelijk bij kan”. Voor het beantwoorden van deze hoofdvraag, is het probleemdomein van tevoren in kaart gebracht. Hieruit is gebleken dat de containerplaatsing op een kade momenteel handmatig verloopt, wat tijd en geld kost. 

Om dit optimaliseringsprobleem op te lossen, is er gebruik gemaakt van RL. De toepassing van RL ging gepaard met twee verschillende agents, PPO en A2C, die interacties voerden met een environment. Naar aanleiding van evaluaties op de performance van de RL-agents, kwam PPO het best naar voren op basis van de episodelengte en de resultaten. 

De optimale PPO-agent heeft er uiteindelijk voor gezorgd dat de containers op een efficiënte wijze worden geplaatst. Dit is bewerkstelligd door een container nauwkeurig te plaatsen aan de hand van de bestemming van een naastgelegen container. Het plaatsen van een container naast een ander container met een identieke bestemming, is afgeleid uit de ingerichte rewards en penalties in het environment.

Door gebruik te maken van de kracht en leervermogen van de PPO-agent, zorgt het voor besparen van tijd en geld. Het efficiënt plaatsen van containers in dit onderzoek, is in ieder geval een basis voor vervolgonderzoek voor in de scheepvaartindustrie. 

Voor vervolgonderzoek zal de focus moeten liggen in de uitbreiding van de environment en de rewardfunctie. Een manier voor de uitbreiding van de environment is om een afmeting van 3x3x3 aan te houden, in plaats van 3x3x1. Voor de rewardfunctie is het van belang dat deze ook uitgebreid wordt naar het identificeren van gelijksoortige containerbestemmingen die op of onder elkaar zitten. Hierbij zal dan ook rekening gehouden moeten worden met de locaties die toegankelijk zijn voor een reachstacker. Bepaalde geplaatste containers kunnen er namelijk voor zorgen dat beschikbare locaties worden afgesloten. De uitbreiding van de environment naar de hoogte, het uitbreiden van de rewardfuncties en het bevorderen van de toegankelijkheid zal voor een meer praktische simulatie en weergave van de werkelijkheid zorgen.

