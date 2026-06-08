1.	Jāizveido attēls ar vismaz 4 ģeometrisko datu slāņi ar ģeometriskajiem un atributīvajiem datiem.
Katru slāni veido pamat-tabula ar ģeometriskiem datiem (vismaz 4 objekti katrā slānī) un papildus tabulas ar atributīviem datiem.
2.	Pirms datu ievades jānorāda ģeometriju meta-dati – koordināšu minimālās un maksimālās vērtības, kā arī precizitāte.
3.	Gan atributīvo, gan ģeometrisko datu ielāde jāveic izmantojot SQL komandu INSERT; 
4.	Gan atributīvo, gan ģeometrisko datu ielāde jāveic izmantojot specializētu datu ievades programmu (Oracle DB gadījumā ar SQL*Loader);
5.	Jāpielieto parastie, hibrīda un R-koku indeksi. Jāveic indeksu ātrdarbības salīdzinājums;
6.	Ģeometriju datu bāzes pārbaudei jādefinē un jārealizē dažādas sarežģītības pakāpes datu izgūšanas vaicājumi:
a.	primārā filtra vaicājumi (2);
b.	topoloģiju analīzes vaicājumi (4);
c.	ģeometriju skaitlisko raksturojumu iegūšanas vaicājumi (4);
d.	atributīvo datu izgūšanas vaicājumi (3);
e.	ģeometriju ģeometrisko datu iegūšanas vaicājumi (4)).
7.	Jāveic ģeometriskās datu bāzes ģeometriju vizualizēšana izmantojot kādu no grafisko datu vizualizācijas paketēm (Oracle Map Viewer);
8.	Jāveic ģeometriskās datu bāzes izgūšanas vaicājumu rezultātu vizualizēšana;
