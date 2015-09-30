# Cartgame21
only a test for 21-game

21
Grovt kan man säga att spelet består av en ”dealer”/PC och en spelare
Spelaren får 1 till tre kort
Varje kort adderas med det nästföljande kortet.
Följande scenarion finns för spelaren:
1)Spelaren bestämmer sig för att stanna under 22, och då stannar spelaren på denna summa och inväntar dealens spel.
2)spelaren får 22 eller över och förlorar.

Specialreglerna är:
Ett Ess kan agera 1 eller 14 beroende på om det är ”lämpligt att använda det ena eller det andra” (dvs om man förlorar med 14 använder man 1)
Dealern måste fortsätta dela ut kort till dess att men slagit spelaren (eller om denna spelat ut alla sina 3 kort)


För att få ut klasser mm så kan man säga:
- Alla spelare KAN få tre kort..
- En kortlek består AV en samling kort..
- Alla spelare tar från SAMMA kortlek.
- alla spelare har ett namn och en poäng
- spelet HAR ETT regelverk
....

Man kan säga eventuellt att:
- Kort är en superklass till kortlek
- kortleken har metoderna att ta ett kort mm

- En spelare nar metoderna "set/get" name och Points
- en spelare kan ha 0-3 kort

- kortspelet har en regelbok, det är därför inte arv utan en implimentation..
(har en är imp.. ÄR en = arv)


en spelare tilldelas ett namn och ett kort från kortleken.
får frågan om hen önskar att stoppa där eller få ett till,
om spelaren får ex en knäckt och en 2:a ger detta 11 + 2 = 14
om om spelaren får ett Ess och en kung ger detta antingen 14 + 13 eller 1 + 13..
om spelaren önskar att stanna summeras resultatet och om resultatet inte är för högt så 
måste pc:n slå detta eller måste gå upp till ett visst värde...
