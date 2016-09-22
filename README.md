# KdG: Web Backend (2016-2017)

docent: Pascal Nosenzo (pascal.nosenzo@kdg.be)

ECTS: [Web back-end WP 2](https://bamaflexweb.kdg.be/BMFUIDetailxOLOD.aspx?a=56428&b=1&c=1)

## Deadlines

- Hier komen de deadlines

## Cursus

De cursus vind je terug op de [Web Backend GitHub repository](https://github.com/pascalculator/web-backend). In de [README.md](https://github.com/pascalculator/web-backend/blob/master/README.md) vind je instructies terug over hoe je deze cursus moet installeren.

### Stappenplan voor de installatie:

1. Git 

	- [Git](https://git-scm.com/downloads) installeren

		- zeker toevoegen aan de PATH variabele

	- [Github](https://github.com/) account aanmaken

2. Cursus web backend structuur

	- de volgende mappenstructuur aanmaken

		```
		web-backend
			|- cursus (NOG NIET AANMAKEN -> dit gebeurt via Git)
			|- oplossingen
		```

	- Op Github een repository "web-backend-oplossingen" aanmaken en deze linken aan je oplossingen map. Bekijk [de instructies](https://github.com/pascalculator/web-backend#je-eigen-oplossingen-uploaden-naar-je-online-repository).

	- De [cursus via Git binnenhalen](https://github.com/pascalculator/web-backend#git-gebruiken-om-cursus-te-downloaden)

		- Let op: de map "cursus" wordt automatisch aangemaakt met dit commando: ```git clone https://github.com/pascalculator/web-backend.git cursus``` (let op het laatste woordje __cursus__. Dat is de naam van de map die aangemaakt zal worden.)

3. Virtual hosts instellen

	- [Instructies](https://github.com/pascalculator/web-backend/raw/master/public/cursus/virtual-server-setup.pdf)

	- Voorbeeld van een [virtual host configuratie](https://raw.githubusercontent.com/pascalculator/web-backend/master/public/cursus/vhost-voorbeeld.txt)

		- Deze virtual host config kan je integraal overnemen (mits de nodige aanpassingen), op voorwaarde dat je de laatste nieuwe versie van XAMPP (Apache) hebt draaien

		- Mensen met Mac: lees bijgevoegde commentaar

	- Stel je virtual hosts zo in dat wanneer je naar 

		- http://web-backend.local surft de lokale map /web-backend/cursus/public wordt ingeladen

		- http://oplossingen.web-backend.local surft de lokale map /web-backend/oplossingen wordt ingeladen

4. Je naam, email en url van GitHub account toevoegen aan dit bestand

	- Edit dit bestand door op het potloodje te klikken

	- Zoek je naam en wijzig je gegevens.

	- Voer een [pull request](https://help.github.com/articles/using-pull-requests/) uit om de wijzigingen tot bij mij te krijgen
	
## Spelregels

- Deze cursus is zelfstudie: je doorloopt de slides, bekijkt de overeenstemmende voorbeelden en maakt vervolgens de opdrachten. Dat betekent niet dat je niet mag overleggen of vragen mag stellen. De docent is er om je te begeleiden en feedback te geven. Maak hier dus gebruik van!

- Je bent aanwezig tijdens de lessen zodat er persoonlijke begeleiding kan gegeven worden. Afwezigheden worden aan mij gemeld via mail én op de KdG-voorgestelde manier gemeld (via e-student services)

- Je gemaakte opdrachten komen op je publieke GitHub repository.

- Per gemaakte opdracht voer je minstens één commit uit, zodat het duidelijk is wanneer je aan welke oefening hebt gewerkt. 

- Deadlines worden gerespecteerd, zonder discussie.

- Je mag kleine dingen kopiëren of je door de voorbeeldopdrachten laten inspireren als je vast zit op voorwaarde dat je elke lijn code kan uitleggen. Integraal een oefening kopiëren en wat variabelen veranderen of commentaar bijschrijven, staat uiteraard gelijk aan plagiaat.

- Vroeger doorgaan tijdens de lessen is geen enkel probleem, mits je dit bij het begin van de les laat weten en je tijdens je aanwezigheid hebt laten zien waar je aan gewerkt hebt.

- Heb je foutjes gevonden of klopt er iets niet? Aanpassingen/verbeteringen (pull requests) aan de cursus worden beloond met minstens één extra punt op het eindtotaal én een eerbare vermelding op de [contributors](https://github.com/pascalculator/web-backend#contributors)-lijst van de cursus.

- Bij problemen (te hoge werkdruk, planning, ...) kan je mij dit in vertrouwen laten weten en dan zoeken we samen naar een oplossing. Het is belangrijk dat je dit -op voorhand- laat weten en niet bv. nadat een deadline is verstreken.

- Kom minstens om de 2 weken laten zien welke oefeningen je hebt gemaakt. Het is je eigen verantwoordelijkheid om aan te duiden of je al dan niet bent geweest (zie namenlijst onderaan in dit bestand). Wanneer je feedback hebt gehad, duid je dit aan met een 1, wanneer je niet bent geweest, duid je dit aan met een O.

## Beoordeling

- Permanente evaluatie tijdens de lessen op basis van de opdrachten en betrokkenheid
	- Laat je zien dat je jezelf kan bijsturen?
	- Ben je kritisch ten opzichte van de oplossingen?
	- Ben je periodiek met de oefeningen bezig?
	- Verricht je opzoekingswerk?
	- Stel je voldoende vragen?
	- Haal je de deadlines of communiceer je tijdig wanneer dit niet lukt?
	- Je komt minstens om de 2 weken laten zien welke oefeningen je hebt gemaakt
	- Deze evaluatie kan je ook altijd even komen raadplegen
	- 50% van het eindtotaal

- Resultaat van de tussentijdse opdrachten
	- Op het einde van elke periode volgt er een opdracht om te kijken wat je huidige kennis is. Deze wordt beoordeeld op:
		- Werkbaarheid
		- Gebruikte technieken comform met de cursus
		- Cleane code (indents, herbruikbaarheid: functies/classes, scheiding logica & html)
	- Deze opdracht moet individueel opgelost worden. Plagiaat/kopiëren wordt zwaar bestraft en krijgen een glansloze vermelding in de "Hall of shame".
	- 50% van het eindtotaal

Er wordt geen eindexamen voor Web Backend geörganiseerd.

## Feedback ivm cursus

Graag! Je mag mij altijd aanspreken tijdens de les of een mailtje sturen met eventuele verbeteringen ivm de cursus.

## Studenten

1. Aussems Alessandro
	- email: e-mailadres in de vorm van @student.kdg.be
	- GitHub: link naar de repo met je oplossingen
	- Feedback <table>
	<thead>
		<tr>
			<th>22/09</th>
			<th>06/10</th>
			<th>13/10</th>
			<th>20/10</th>
			<th>27/10</th>
			<th>24/11</th>
			<th>01/12</th>
			<th>08/12</th>
			<th>15/12</th>
			<th>22/12</th>
			<th>12/1</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
	</tbody>
</table>

2. Banasik Katriena
	- email: e-mailadres in de vorm van @student.kdg.be
	- GitHub: link naar de repo met je oplossingen
	- Feedback <table>
	<thead>
		<tr>
			<th>22/09</th>
			<th>06/10</th>
			<th>13/10</th>
			<th>20/10</th>
			<th>27/10</th>
			<th>24/11</th>
			<th>01/12</th>
			<th>08/12</th>
			<th>15/12</th>
			<th>22/12</th>
			<th>12/1</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
	</tbody>
</table>

3. Borret Sander
	- email: sander.borret@student.kdg.be
	- GitHub: https://github.com/ssssssander/web-backend-oplossingen
	- Feedback <table>
	<thead>
		<tr>
			<th>22/09</th>
			<th>06/10</th>
			<th>13/10</th>
			<th>20/10</th>
			<th>27/10</th>
			<th>24/11</th>
			<th>01/12</th>
			<th>08/12</th>
			<th>15/12</th>
			<th>22/12</th>
			<th>12/1</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
	</tbody>
</table>

4. Buys Kevin
	- email: e-mailadres in de vorm van @student.kdg.be
	- GitHub: link naar de repo met je oplossingen
	- Feedback <table>
	<thead>
		<tr>
			<th>22/09</th>
			<th>06/10</th>
			<th>13/10</th>
			<th>20/10</th>
			<th>27/10</th>
			<th>24/11</th>
			<th>01/12</th>
			<th>08/12</th>
			<th>15/12</th>
			<th>22/12</th>
			<th>12/1</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
	</tbody>
</table>

5. De Corte Jens
	- email: e-mailadres in de vorm van @student.kdg.be
	- GitHub: link naar de repo met je oplossingen
	- Feedback <table>
	<thead>
		<tr>
			<th>22/09</th>
			<th>06/10</th>
			<th>13/10</th>
			<th>20/10</th>
			<th>27/10</th>
			<th>24/11</th>
			<th>01/12</th>
			<th>08/12</th>
			<th>15/12</th>
			<th>22/12</th>
			<th>12/1</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
	</tbody>
</table>

6. de Kock Tymo
	- email: e-mailadres in de vorm van @student.kdg.be
	- GitHub: link naar de repo met je oplossingen
	- Feedback <table>
	<thead>
		<tr>
			<th>22/09</th>
			<th>06/10</th>
			<th>13/10</th>
			<th>20/10</th>
			<th>27/10</th>
			<th>24/11</th>
			<th>01/12</th>
			<th>08/12</th>
			<th>15/12</th>
			<th>22/12</th>
			<th>12/1</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
	</tbody>
</table>

7. De Ridder Stijn
	- email: stijn.deridder.1@student.kdg.be	
	- GitHub: https://github.com/DeRidderStijn/DeRidderStijnOplossingen.git
	- Feedback <table>
	<thead>
		<tr>
			<th>22/09</th>
			<th>06/10</th>
			<th>13/10</th>
			<th>20/10</th>
			<th>27/10</th>
			<th>24/11</th>
			<th>01/12</th>
			<th>08/12</th>
			<th>15/12</th>
			<th>22/12</th>
			<th>12/1</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
	</tbody>
</table>

8. Detemmerman Jordy
	- email: e-mailadres in de vorm van @student.kdg.be
	- GitHub: link naar de repo met je oplossingen
	- Feedback <table>
	<thead>
		<tr>
			<th>22/09</th>
			<th>06/10</th>
			<th>13/10</th>
			<th>20/10</th>
			<th>27/10</th>
			<th>24/11</th>
			<th>01/12</th>
			<th>08/12</th>
			<th>15/12</th>
			<th>22/12</th>
			<th>12/1</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
	</tbody>
</table>

9. Diels Lode
	- email: e-mailadres in de vorm van @student.kdg.be
	- GitHub: link naar de repo met je oplossingen
	- Feedback <table>
	<thead>
		<tr>
			<th>22/09</th>
			<th>06/10</th>
			<th>13/10</th>
			<th>20/10</th>
			<th>27/10</th>
			<th>24/11</th>
			<th>01/12</th>
			<th>08/12</th>
			<th>15/12</th>
			<th>22/12</th>
			<th>12/1</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
	</tbody>
</table>

10. Heynderickx Stijn
	- email: stijn.heynderickx @student.kdg.be
	- GitHub: https://github.com/stinooww/web-backend.git
	- Feedback <table>
	<thead>
		<tr>
			<th>22/09</th>
			<th>06/10</th>
			<th>13/10</th>
			<th>20/10</th>
			<th>27/10</th>
			<th>24/11</th>
			<th>01/12</th>
			<th>08/12</th>
			<th>15/12</th>
			<th>22/12</th>
			<th>12/1</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
	</tbody>
</table>

11. Kbyeh Manar
	- email: e-mailadres in de vorm van @student.kdg.be
	- GitHub: link naar de repo met je oplossingen
	- Feedback <table>
	<thead>
		<tr>
			<th>22/09</th>
			<th>06/10</th>
			<th>13/10</th>
			<th>20/10</th>
			<th>27/10</th>
			<th>24/11</th>
			<th>01/12</th>
			<th>08/12</th>
			<th>15/12</th>
			<th>22/12</th>
			<th>12/1</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
	</tbody>
</table>

12. Lambrechts Tyas
	- email: e-mailadres in de vorm van @student.kdg.be
	- GitHub: link naar de repo met je oplossingen
	- Feedback <table>
	<thead>
		<tr>
			<th>22/09</th>
			<th>06/10</th>
			<th>13/10</th>
			<th>20/10</th>
			<th>27/10</th>
			<th>24/11</th>
			<th>01/12</th>
			<th>08/12</th>
			<th>15/12</th>
			<th>22/12</th>
			<th>12/1</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
	</tbody>
</table>

13. Melis Pieter
	- email: e-mailadres in de vorm van @student.kdg.be
	- GitHub: link naar de repo met je oplossingen
	- Feedback <table>
	<thead>
		<tr>
			<th>22/09</th>
			<th>06/10</th>
			<th>13/10</th>
			<th>20/10</th>
			<th>27/10</th>
			<th>24/11</th>
			<th>01/12</th>
			<th>08/12</th>
			<th>15/12</th>
			<th>22/12</th>
			<th>12/1</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
	</tbody>
</table>

14. Moerloos Phedra
	- email: phedra.moerloos@student.kdg.be
	- GitHub: https://github.com/PhedraMoerloos/web-backend-oplossingen-2
	- Feedback <table>
	<thead>
		<tr>
			<th>22/09</th>
			<th>06/10</th>
			<th>13/10</th>
			<th>20/10</th>
			<th>27/10</th>
			<th>24/11</th>
			<th>01/12</th>
			<th>08/12</th>
			<th>15/12</th>
			<th>22/12</th>
			<th>12/1</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>1</td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
	</tbody>
</table>

15. Moerloos Thessa
	- email: e-mailadres in de vorm van @student.kdg.be
	- GitHub: link naar de repo met je oplossingen
	- Feedback <table>
	<thead>
		<tr>
			<th>22/09</th>
			<th>06/10</th>
			<th>13/10</th>
			<th>20/10</th>
			<th>27/10</th>
			<th>24/11</th>
			<th>01/12</th>
			<th>08/12</th>
			<th>15/12</th>
			<th>22/12</th>
			<th>12/1</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
	</tbody>
</table>

16. Monballiu Jeff
	- email: e-mailadres in de vorm van @student.kdg.be
	- GitHub: link naar de repo met je oplossingen
	- Feedback <table>
	<thead>
		<tr>
			<th>22/09</th>
			<th>06/10</th>
			<th>13/10</th>
			<th>20/10</th>
			<th>27/10</th>
			<th>24/11</th>
			<th>01/12</th>
			<th>08/12</th>
			<th>15/12</th>
			<th>22/12</th>
			<th>12/1</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
	</tbody>
</table>

17. Op de Beeck Jesse
	- jesse.opdebeeck@student.kdg.be
	- https://github.com/jessekdg/web-backend-oplossingen
	- Feedback <table>
	<thead>
		<tr>
			<th>22/09</th>
			<th>06/10</th>
			<th>13/10</th>
			<th>20/10</th>
			<th>27/10</th>
			<th>24/11</th>
			<th>01/12</th>
			<th>08/12</th>
			<th>15/12</th>
			<th>22/12</th>
			<th>12/1</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
	</tbody>
</table>

18. Peeters Lennert
	- email: e-mailadres in de vorm van @student.kdg.be
	- GitHub: link naar de repo met je oplossingen
	- Feedback <table>
	<thead>
		<tr>
			<th>22/09</th>
			<th>06/10</th>
			<th>13/10</th>
			<th>20/10</th>
			<th>27/10</th>
			<th>24/11</th>
			<th>01/12</th>
			<th>08/12</th>
			<th>15/12</th>
			<th>22/12</th>
			<th>12/1</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
	</tbody>
</table>

19. Penu Andreea
	- email: andreea.penu@student.kdg.be
	- GitHub: https://github.com/AndreeaPenu/PenuAndreeaOplossingen
	- Feedback <table>
	<thead>
		<tr>
			<th>22/09</th>
			<th>06/10</th>
			<th>13/10</th>
			<th>20/10</th>
			<th>27/10</th>
			<th>24/11</th>
			<th>01/12</th>
			<th>08/12</th>
			<th>15/12</th>
			<th>22/12</th>
			<th>12/1</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
	</tbody>
</table>

20. Pereira Jordy
	- email: jordy.pereira@student.kdg.be
	- GitHub: https://github.com/Woozsh/web-backend-oplossingen
	- Feedback <table>
	<thead>
		<tr>
			<th>22/09</th>
			<th>06/10</th>
			<th>13/10</th>
			<th>20/10</th>
			<th>27/10</th>
			<th>24/11</th>
			<th>01/12</th>
			<th>08/12</th>
			<th>15/12</th>
			<th>22/12</th>
			<th>12/1</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
	</tbody>
</table>

21. Robbe André
	- email: e-mailadres in de vorm van @student.kdg.be
	- GitHub: link naar de repo met je oplossingen
	- Feedback <table>
	<thead>
		<tr>
			<th>22/09</th>
			<th>06/10</th>
			<th>13/10</th>
			<th>20/10</th>
			<th>27/10</th>
			<th>24/11</th>
			<th>01/12</th>
			<th>08/12</th>
			<th>15/12</th>
			<th>22/12</th>
			<th>12/1</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
	</tbody>
</table>

22. Serna Delgado Yawuar
	- email: e-mailadres in de vorm van @student.kdg.be
	- GitHub: link naar de repo met je oplossingen
	- Feedback <table>
	<thead>
		<tr>
			<th>22/09</th>
			<th>06/10</th>
			<th>13/10</th>
			<th>20/10</th>
			<th>27/10</th>
			<th>24/11</th>
			<th>01/12</th>
			<th>08/12</th>
			<th>15/12</th>
			<th>22/12</th>
			<th>12/1</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
	</tbody>
</table>

23. Trompeneers Enzo
	- email: e-mailadres in de vorm van @student.kdg.be
	- GitHub: link naar de repo met je oplossingen
	- Feedback <table>
	<thead>
		<tr>
			<th>22/09</th>
			<th>06/10</th>
			<th>13/10</th>
			<th>20/10</th>
			<th>27/10</th>
			<th>24/11</th>
			<th>01/12</th>
			<th>08/12</th>
			<th>15/12</th>
			<th>22/12</th>
			<th>12/1</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
	</tbody>
</table>

24. Van Assche Jens
	- email: e-mailadres in de vorm van @student.kdg.be
	- GitHub: link naar de repo met je oplossingen
	- Feedback <table>
	<thead>
		<tr>
			<th>22/09</th>
			<th>06/10</th>
			<th>13/10</th>
			<th>20/10</th>
			<th>27/10</th>
			<th>24/11</th>
			<th>01/12</th>
			<th>08/12</th>
			<th>15/12</th>
			<th>22/12</th>
			<th>12/1</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
	</tbody>
</table>

25. Van Dijck Hendrik
	- email: e-mailadres in de vorm van @student.kdg.be
	- GitHub: link naar de repo met je oplossingen
	- Feedback <table>
	<thead>
		<tr>
			<th>22/09</th>
			<th>06/10</th>
			<th>13/10</th>
			<th>20/10</th>
			<th>27/10</th>
			<th>24/11</th>
			<th>01/12</th>
			<th>08/12</th>
			<th>15/12</th>
			<th>22/12</th>
			<th>12/1</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
	</tbody>
</table>

26. Van Loey Jonas
	- email: e-mailadres in de vorm van @student.kdg.be
	- GitHub: link naar de repo met je oplossingen
	- Feedback <table>
	<thead>
		<tr>
			<th>22/09</th>
			<th>06/10</th>
			<th>13/10</th>
			<th>20/10</th>
			<th>27/10</th>
			<th>24/11</th>
			<th>01/12</th>
			<th>08/12</th>
			<th>15/12</th>
			<th>22/12</th>
			<th>12/1</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
	</tbody>
</table>

27. Vercammen Dieter
	- email: dieter.vercammen@student.kdg.be
	- GitHub: https://github.com/DieterVercammen/Oplossingen-web-backend
	- Feedback <table>
	<thead>
		<tr>
			<th>22/09</th>
			<th>06/10</th>
			<th>13/10</th>
			<th>20/10</th>
			<th>27/10</th>
			<th>24/11</th>
			<th>01/12</th>
			<th>08/12</th>
			<th>15/12</th>
			<th>22/12</th>
			<th>12/1</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
	</tbody>
</table>

28. Verhelst Thomas
	- email: e-mailadres in de vorm van @student.kdg.be
	- GitHub: link naar de repo met je oplossingen
	- Feedback <table>
	<thead>
		<tr>
			<th>22/09</th>
			<th>06/10</th>
			<th>13/10</th>
			<th>20/10</th>
			<th>27/10</th>
			<th>24/11</th>
			<th>01/12</th>
			<th>08/12</th>
			<th>15/12</th>
			<th>22/12</th>
			<th>12/1</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
	</tbody>
</table>

29. Vermeire Adriaan
	- email: adriaan.vermeire@student.kdg.be
	- GitHub: https://github.com/adriaanvermeire/web-backend-oplossingen
	- Feedback <table>
	<thead>
		<tr>
			<th>22/09</th>
			<th>06/10</th>
			<th>13/10</th>
			<th>20/10</th>
			<th>27/10</th>
			<th>24/11</th>
			<th>01/12</th>
			<th>08/12</th>
			<th>15/12</th>
			<th>22/12</th>
			<th>12/1</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
	</tbody>
</table>

30. Verschueren Tom
	- email: e-mailadres in de vorm van @student.kdg.be
	- GitHub: link naar de repo met je oplossingen
	- Feedback <table>
	<thead>
		<tr>
			<th>22/09</th>
			<th>06/10</th>
			<th>13/10</th>
			<th>20/10</th>
			<th>27/10</th>
			<th>24/11</th>
			<th>01/12</th>
			<th>08/12</th>
			<th>15/12</th>
			<th>22/12</th>
			<th>12/1</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
	</tbody>
</table>

31. Verstocken Nick
	- email: e-mailadres in de vorm van @student.kdg.be
	- GitHub: link naar de repo met je oplossingen
	- Feedback <table>
	<thead>
		<tr>
			<th>22/09</th>
			<th>06/10</th>
			<th>13/10</th>
			<th>20/10</th>
			<th>27/10</th>
			<th>24/11</th>
			<th>01/12</th>
			<th>08/12</th>
			<th>15/12</th>
			<th>22/12</th>
			<th>12/1</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
	</tbody>
</table>

32. De Meester Arteau 
	- email: arteau.demeester@student.kdg.be
	- GitHub: https://github.com/Arteau/web-backend-oplossingen
	- Feedback <table>
	<thead>
		<tr>
			<th>22/09</th>
			<th>06/10</th>
			<th>13/10</th>
			<th>20/10</th>
			<th>27/10</th>
			<th>24/11</th>
			<th>01/12</th>
			<th>08/12</th>
			<th>15/12</th>
			<th>22/12</th>
			<th>12/1</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
	</tbody>
</table>

32. Luit Robbert 
	- email: e-mailadres in de vorm van @student.kdg.be
	- GitHub: link naar de repo met je oplossingen
	- Feedback <table>
	<thead>
		<tr>
			<th>22/09</th>
			<th>06/10</th>
			<th>13/10</th>
			<th>20/10</th>
			<th>27/10</th>
			<th>24/11</th>
			<th>01/12</th>
			<th>08/12</th>
			<th>15/12</th>
			<th>22/12</th>
			<th>12/1</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
	</tbody>
</table>

33. Matthieu Pieter 
	- email: e-mailadres in de vorm van @student.kdg.be
	- GitHub: link naar de repo met je oplossingen
	- Feedback <table>
	<thead>
		<tr>
			<th>22/09</th>
			<th>06/10</th>
			<th>13/10</th>
			<th>20/10</th>
			<th>27/10</th>
			<th>24/11</th>
			<th>01/12</th>
			<th>08/12</th>
			<th>15/12</th>
			<th>22/12</th>
			<th>12/1</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
			<td></td>
		</tr>
	</tbody>
</table>
