#Programmastic-four

1. Nejra Bahti�
2. Amina Alji�evi�
3. Selma Ahmetovi�
4. Hanad Bajramba�i�

#Opis sistema

**Kino e-Cinema Star** je osnovano 2016. godine i kao takvo je najsavremenije kino u Sarajevo i u cijeloj Bosni i Hercegovini. Dr�i korak sa novim tehnologijama u svijetu filma, pristupa korisnicima, projekcije filma i nabavljanja filmova. Tako�er, fokusira se i na afirmisanju doma�ih filmova i doma�ih glumaca.

Vlasnik kina �eli da modernizuje i olak�a kupovinu karata, kao i cjelokupan do�ivljaj kina korisnicima. Vlasnik kina - klijent �eli da korisnici kina imaju 24/7 pristup preko interneta.
Nudi mnoge usluge, kao �to su projekcije filmova, online kupovina karata, online rezervacija karata, pregled filmova koje je korisnik pogledao, predlaganje gledanja filmova istog ili sli�nog �anra onim filmovima koje korisnik ina�e gleda. On �eli interfejs pomo�u kojeg bi klijentima bila omogu�ena kupovina karata ili naru�ivanje istih.

#Procesi

Prilikom kupovine karata u kinu, korisnik se obra�a uposleniku kina. Da bi registracija kupovina karata i�la aplikacija, uposlenik se loguje na stranicu kina kao admin. U admin panelu se nalazi sve �to uposleniku treba, odabir filmova, vrijeme projekcija, cijene karata, mogu�nost popusta. Najprije se gleda da li je korisnik uplatio preko aplikacije. Ukoliko jeste ide samo izdavanje karte. Ukoliko nije bilo pla�anja preko aplikacije, ide izbor filma, kao i popust. Popusti su u slu�aju studenata kao korisnika, korisnika koji je logovan na kino aplikaciju. Prvo se gleda izbor mjesta, tj. dostupnost kupovine karte ili ne. Ukoliko ima dovoljno mjesta, gleda se da li postoji neki popust. Nakon toga cijena se obra�unava i izdaje karta. 

Prilikom kupovine karata putem aplikacije, korisnik se registruje na aplikaciju kina (ukoliko to nije prethodno uradio). U svom profilu ima mogu�nost vidjeti koji su filmovi trenutno aktuelni, kao i vrijeme projekcija, cijenu karata, mogu�nost popusta i mogu�nost online kupovine. Online kupovina ide preko maestro ili master card kartice. Korisniku se mo�e ponuditi i odvojena lista filmova koje mo�da �eli da gleda, ukoliko je prethodno bio registrovan. Lista se kreira na osnovu fimova koje je korisnik prethodno gledao. 

###Klijent

Klijent je vlasnik kina. On ima poseban admin account na aplikaciji i pristupa svim izmjenama aplikacije. Klijentu su dostupni svi podaci o aplikaciji i na�inu kupovine.


###Uposlenik

Uposlenik kina nalazi se na �alteru. Ima uposlenik account na aplikaciji. Mo�e vr�iti izmjene u aplikaciji kao �to su a�uriranje filmova, vo�enje evidencija o rezervaciji, prodanim kartama, zauzetim mjestima itd. Na �alteru ukoliko korisnik ima neki popust, uposlenik ga obra�unava. Tako�er, vodi ra�una i o tome da li je hrana naru�ena ili ne.


###Pla�anje
 
Pla�anje se vr�i na �alteru kina ili online, tj. preko aplikacije. Rezervacije se mogu vr�iti u aplikaciji i ukoliko je izv�ena rezervacija, dobije se popust preko aplikacije i pla�a online. Ukoliko nije do�lo do online transakcije, karta se kupuje na �alteru, gdje uposlenik obra�unava cijenu i izdaje kartu. U slu�aju kupovine karte direktno na �alteru, popust je samo ukoliko je osoba student.


###Realizacija kupovine

U slu�aju da je korisnik vi�e od pola godine aktivan u aplikaciji kina, tj. da vi�e od pola godine redovno ide u kino, mo�e postati �lan kluba �Ljubitelji filma� i time ostvaruje popust od 5% pri svakoj kupovini karte. Ovaj popust se dodaje na popust ukoliko je u pitanju student ili ukoliko je osoba korisnik aplikacije.
Online kupovina, koju �emo kasnije specificirati.


###Realizacija ostalih usluga

Rezervacija 3D nao�ala ukoliko je u pitanju 3D film, kao i poru�ivanje hrane, koja �e �ekati servirana na mjestu koje je korisnik platio.
Skeniranje QR koda. Nakon skeniranja, aplikacija izbaci sve informacije o filmu, kao �to su trailer, glumci i sli�no.


#Funkcionalnosti

* Registracija novih korisnika aplikacije preko forme
* Pregled postoje�ih korisnika preko liste
* Forma za pregled svih filmova koji su u ponudi 
* Forma za a�uriranje ponude (promjena cijena, a�uriranje liste filmova..)
* Odvojena forma za korisnika i za uposlenika (admina)
* Forma za prikaz statistike o pregledanim filmovima nakon �to zavr�e projekcije tog filma
* Rezervacija karata (online ili preko telefona)
* Popusti za odre�ene skupine (studenti, Ljubitelji filma, korisnici aplikacije)
* Mogu�nost laganog pristupa svim korisnicima informacijama o kinu, radu, kontakt kao i FAQ o kinu
* Registracija korisnika u klub Ljubitelji filma i time omogu�avanje popusta
* Promocija doma�ih filmova, neke promo cijene 
* Kori�tenje mastercard simplify za online transakcije (eksterni servis)
* RFID reader za poni�tavanje karata (eksterni ure�aj)
* Skeniranje QR koda

#Akteri

* Klijent (vlasnik kina)
* Korisnici 
* Uposlenik


