# LaboReeks Git
## **Labo 2**

In ons tweede labo gaan we opnieuw aan de slag met een **remote repository**.
Deze keer kiezen we echter voor de *easy way* om onze remote repo te gaan clonen, i.p.v. zelf de remote te linken aan een lokaal zelf aangemaakte repo.

Na de clone dien je alles wat gevraagd wordt opnieuw lokaal toe te voegen en vervolgens via de nodige commando's ook in de online repository te brengen. 

#### **Aanvullende toets op Leho**
Na het afwerken van dit labo heb je op Leho een aanvullende toets met betrekking tot het labo en de leerstof gekoppeld aan het labo.
Je kan/mag de aanvullende toets steeds afleggen gebruik makend van alle bronnen (cursusmateriaal, labo, online bronnen, ...).
**Maak zeker de toets, deze wordt finaal gequoteerd.**

### **Deel 1: Clonen van de remote repo**

- [ ] Open de Git Bash Console op de locatie waar je dit labo wil gaan clonen. Dit kan via een rechtermuisklik op de locatie in kwestie en vervolgens de keuze **Git Bash Here** te selecteren.
>**Tip!** Indien deze optie niet beschikbaar is dan heb je een stap in de aanbevolen installatie van git overgeslaan.

- [ ] Gebruik het gepaste git commando om een lokale kopie te verkrijgen op je pc van deze remote repo voor labo 2.

>**Opgelet!** In tegenstelling tot in labo 1, maak je deze keer dus **niet zelf** eerst een lege lokale repo aan, maar gebruik je een git commando dat
meteen voor jou een lokale kopie van de remote maakt, inclusief alle inhoud en commit-geschiedenis.

- [ ]  Ga **na het clonen** via de console naar de gecloonde repository. Dit kan/mag je uiteraard ook doen door de nieuwe aangemaakt folder aan te klikken en hier opnieuw een Git Bash console te openen via de **Git Bash Here** optie.
>**Tip!** Controleer voor je verder werkt of je al dan niet in de juiste git repository zit! Je kan dit snel visueel vaststellen in je console.

- [ ] Voer even een extra controle uit om na te gaan welke remote repositories gekoppeld zijn na het clonen. Maak hiervoor gebruik van het passende git commando.
- [ ] Voer een git commando uit om te controleren dat je lokaal ook dezelfde commit(s) in de geschiedenis terugvindt als deze op je remote repo.
- [ ] Neem een screenshot van de commando's die je in de vorige stappen gebruikte (en hun output).
      Deze screenshot plaats je in de **lokale** Screenshot folder van labo2. *(Op jouw PC/laptop dus!)* Geef deze screenshot de naam **deel1** (met extensie naar keuze).

- [ ] Gebruik de/het gepaste git commando('s) om deze screenshot toe te voegen aan je lokale versiebeheer.
>**Tip!** Denk aan de conventies rondom naamgeving van de commit messages!

- [ ] Zorg er finaal voor dat de toegevoegde screenshot ook naar de remote doorgestuurd wordt, opnieuw met een git commando.

### **Deel 2: Gitignore**

- [ ] Maak een .gitignore bestand aan in de root van dit labo.

- [ ] Zorg ervoor dat overheen de volledige git repository alle bestanden met extensie **tmp** niet opgenomen worden in git. Plaats de zin **temporary files are excluded** net boven de regel die je hiervoor gemaakt hebt, deze regel wordt als commentaar aanzien.

- [ ] Maak gebruik van passende git commando's om het .gitignore bestand te commiten naar je lokale repo.
>**Tip!** Denk aan de conventies rondom naamgeving van de commit messages!

- [ ] Voeg een regel toe aan de .gitignore die de folder **temp** zal gaan negeren. Plaats de zin **temporary folder is excluded** net boven de regel die je hiervoor gemaakt hebt, deze regel wordt als commentaar aanzien.
>**Tip!** Vergeet de wijzigingen niet op te slaan na je aanpassingen!

- [ ] Maak gebruik van passende git commando's om het .gitignore bestand te commiten naar git.
>**Tip!** Denk aan de conventies rondom naamgeving van de commit messages!

- [ ] Bekijk even de structuur van de reeds aanwezige **docs** folder.
Je zal zien dat deze o.a. drie subfolders bevat, elk verwijzend naar een fase (phase1, phase2 & phase3). 
Voeg eerst en vooral volgende regel commentaar toe in je .gitignore: **All phases except phase1 are ignored**.
Vervolgens voorzie je de nodige regels waardoor je alle bestanden in de map phase2 en phase3 zal negeren, maar deze in de map phase1 niet!
Tracht dit te bekomen door efficient gebruik te maken van de .gitignore functionaliteit en niet door elke genegeerde phase folder op een afzonderlijke regel toe te voegen.
>**Tip!** Je zal hiervoor hoogstwaarschijnlijk 2 regels nodig hebben. Vergeet de wijzigingen niet op te slaan na je aanpassingen!

- [ ] Maak gebruik van passende git commando's om het .gitignore bestand te commiten naar git.
>**Tip!** Denk aan de conventies rondom naamgeving van de commit messages!

- [ ] Kopieer onderstaande lijst van commando's *(in 1 keer)*. Plak deze vervolgens in je console. Na uitvoeren zal deze blijven staan op de **git status** regel. Voer deze uit en neem een screenshot van het resultaat. Deze screenshot plaats je in de **lokale** Screenshot folder van labo2. *(Op jouw PC/laptop dus!)* Geef deze screenshot de naam **deel2** (met extensie naar keuze).


```
clear
touch file01.tmp
touch file02.temp
touch docs/temp/garbage.txt
touch docs/temp/tmp.txt
touch docs/file01.tmp
touch docs/file01.temp
touch docs/phase1/file01.md
touch docs/phase1/phase1.md
touch docs/phase1/phase2.md
touch docs/phase1/phase3.md
touch docs/phase2/file01.md
touch docs/phase2/phase1.md
touch docs/phase2/phase2.md
touch docs/phase2/phase3.md
touch docs/phase3/file01.md
touch docs/phase3/phase1.md
touch docs/phase3/phase2.md
touch docs/phase3/phase3.md
touch docs/phase1.md
touch docs/phase2.md
touch docs/phase3.md
clear
git status
```

- [ ] Maak gebruik van passende git commando's om alle lokale bestanden te commiten naar git.
      **Synchroniseer** vervolgens je lokale repository nogmaals met de online repository op GitHub.
>**Tip!** Denk aan de conventies rondom naamgeving van de commit messages!

#### **Afwerken van het labo**
- [ ] Na het voltooien van alle taken editeer je deze **README.md** file (lokaal, in een editor naar keuze)
  en plaats je alle taken op voltooid door de markup te wijzigen van [ ] naar [x]. 
- [ ] Commit deze wijziging in je lokale repo.
- [ ] Synchroniseer een laatste keer de lokale geschiedenis naar de remote repo op GitHub.

>**Tip!** Je kan hier gerust VS Code gaan gebruiken. Deze heeft ook een preview mode om met markdown aan de slag te gaan.

>**Tip!** Controleer **op GitHub** nog even of je aangepaste opmaak ook wel degelijk goed verwerkt werd!
          Het vinkje wordt pas zichtbaar als er geen spaties rondom staan!
          Indien het niet gelukt is, kan je het bestand **README.md** nogmaals aanpassen en de wijzigingen nogmaals naar de remote sturen.
