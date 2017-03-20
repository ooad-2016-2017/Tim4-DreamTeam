# **DreamTeam**

### Članovi tima:

- Mersiha Ćeranić
- Maja Dugandžić
- Haris Alikadić

# **_Krim Tim 3_**

### Opis teme: 
Aplikacija je namijenjena policijskim službenicima u svrhu pretraživanja fizičkih lica sa kriminalnim dosjeima, kao i pojedinaca koji nemaju kriminalni dosije, čime imaju brz i efikasan pristup svim podacima pojedinaca u bilo kojem trenutku. Takodjer službena lica u sistem mogu unositi i nove profile tj. počinioce novih krivičnih dijela. Sistem omogućava izdavanje potvrde o nekažnjavanju u slučaju da pojedinac nema otvoren kriminalni dosije. Putem signala koji šalje elektronska narukvica, utvrđuje se lokacija osumnjičenika. Na osnovu podataka o lokaciji, policijski službenik dobija informacije da li je osumnjičeno lice prekršilo propise kojim se reguliše njegovo kretanje. Inspektor (nadležno lice) ima uvid u sve aktivnosti policijskih službenika uz pomoć ove aplikacije. Također, aplikacija omogućava brzu i efikasnu komunikaciju policijske uprave i suda, što uveliko doprinosi očuvanju sigurnosti građana.

### Funkcionalnosti:

- Obrada ličnih podataka i vođenje evidencije.
- Pregled kriminalnog dosjea svakog pojedinca, ukoliko ga ima.
- Ukoliko pojedinac nema dosjea, izdavanje potvrde o nekažnjavanju.
- Privremeno ograničavanje slobode kretanja (putem elektronske narukvice se vrši praćenje kretanja osumnjičenog).
- Obrada i ažuriranje informacija o slučaju, te prosljeđivanje podataka sudu u svrhu vođenja slučaja.

### Procesi:
- Registracija i vođenje evidencije o policijskim službenicima:  Unutar sistema policijske uprave se vrši registracija policijskih službenika. Pri registraciji se unose osnovni podaci i zadaće policijskih službenika. Pri dolasku/odlasku službenih lica na posao, službeno lice se prijavljuje/odjavljuje na sistem policijske uprave. Usljed napredovanja/nazadovanja u radu policijskih službenika, vrši se ažuriranje podataka istih. 

- Pretraživanje informacija o osumnjičeniku: Svakom policijskom službeniku je omogućen pristup bazi podataka policijske uprave. Policijski službenik ima uvid u lične podatke pojedinca (fizičkog lica). Dostupni podaci o pojedincu se koriste pri rasvjetljavanju slučaja. Pristup podacima je omogućen samo službenim licima policijske uprave.

- Otvaranje/ažuriranje kriminalnog dosjea: Ukoliko se prilikom pretraživanja baze podataka policijske uprave utvrdi da osumnjičeno lice nema prethodno otvoren kriminalni dosje, vrši se otvaranje istog. U suprotnom, ako osumnjičeno lice ima kriminalni dosje, vrši se ažuriranje prethodno unesenih podataka. 

- Izdavanje potvrde o nekažnjavanju: Fizičko lice podnosi zahtjev za izdavanje potvrde o nekažnjavanju policijskoj upravi. Policijski službenik pretražuje informacije u bazi podataka policijske uprave o pojedincu. U slučaju da fizičko lice nema otvoren kriminalni dosje, izdaje se potvrda o nekažnjavanju. 


- Postupak žalbe:  Pojedinci uneseni u bazu podataka imaju pravo javne žalbe. Osumnjičeno lice ima mogućnost da pokrene postupak žalbe koji se šalje sudu. Sud precesuira žalidbeni zahtjev. U toku procesuiranja zahtjeva, sud ustanovljava da li žalba ima osnove za uvažavanje. Ako se ustanovi da žalba ima osnove za uvažavanje, sud šalje obavijest nadležnim organima policijske uprave.

- Pravilnik o pogodnostima zatvorenika: Ukoliko je utvrđeno da zatvorenik ima uzorno ponašanje, vrši se ažuriranje kriminalnog dosjea. Na osnovu toga se omogućava smanjenje kazne ili davanje pogodnosti zatvoreniku.

### Akteri:
1. Inspektor – nadležno lice u policijskoj upravi; nadzire rad različitih tijela policijske uprave
2. Policajac – službeno lice policijske uprave;održava mir i sigurnost te provodi zakon u ime države na nekom određenom području 
3. Administrator – održava rad sistema i baze podataka u policijskoj upravi
4. Fizičko lice(osumnjičeni) – lice prema kojem je,prije pokretanja krivičnog postupka, nadležni organ poduzeo neke radnje zbog postojanja osnovane sumnje da je počinio krivično djelo
5. Sud – pravno lice koje surađuje sa policijskom upravom
