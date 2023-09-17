# Detekcija anomalija na maloj maturi pomoću ML metoda

Projekat na kursu [Mašinsko učenje](https://ml.matf.bg.ac.rs/) @ [MATF](https://www.matf.bg.ac.rs).

Cilj ovog projekta je ispitivanje više metoda mašinskog učenja kako bi se pronašle anomalije u rezultatima male mature. Ove anomalije mogu biti raznorodne: recimo, nejednaki kriterijumi za neke ili za sve predmete u nekim školama, ili rasprostranjene neregularnosti na završnom ispitu. Klasične statističke metode nam mogu pomoći u otkrivanju nekih očiglednijih anomalija koje možemo formulisati u dovoljno preciznim terminima, ali postavlja se pitanje da li postoji neki opštiji, nenadgledani metod, koji bi nam olakšao pronalaženje sumnjivih instanci u ovom skupu podataka. Za potrebe projekta se koriste [podaci](https://github.com/luka-j/UpisDbMigrator/releases/tag/20.0) dobijeni [scrape-ovanjem portala](https://github.com/luka-j/UpisScraper/) za upis u srednje škole u periodu 2015-2020.

Istraživali smo dva moguća pristupa. Prvi je primena jednoklasnog SVM-a koji bi izdvojio neki procenat podataka kao anomalije i on je dostupan u fajlu 01-oneClassSVM.ipynb. Drugi je primena autoenkodira i proglašavanje onih instanci na kojima on najviše greši za anomalije, dostupan u fajlu 02-autoencoder.ipynb. Detaljniji opis postupaka i samih podataka je dat kao deo notebook-ova.

## Članovi tima
- Jelena Keljać 1081/2022
- Luka Jovičić 1067/2022
