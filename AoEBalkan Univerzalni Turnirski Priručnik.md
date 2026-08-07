# AoEBalkan Univerzalni Turnirski Priručnik

**Verzija 1.0 — August 2026**

> Ovo je živi dokument za AoEBalkan zajednicu. Organizatori turnira trebaju koristiti ovaj priručnik kao osnovu i navesti bilo kakve izmjene specifične za njihov turnir u najavi.

---

## Sadržaj

1. [Uvod](#1-uvod)
2. [Kontrolna Lista za Organizatore](#2-kontrolna-lista-za-organizatore)
3. [Registracija i Seeding](#3-registracija-i-seeding)
4. [Zakazivanje i Točnost](#4-zakazivanje-i-točnost)
5. [Zahtjevi za Map Pool](#5-zahtjevi-za-map-pool)
6. [Pravila za Map Draft](#6-pravila-za-map-draft)
7. [Pravila za Civ Draft](#7-pravila-za-civ-draft)
8. [Lobby Postavke](#8-lobby-postavke)
9. [Pravila u Igri](#9-pravila-u-igri)
10. [Pravila za Laming](#10-pravila-za-laming)
11. [Pravila za Nomad Mape](#11-pravila-za-nomad-mape)
12. [Restart Pravila](#12-restart-pravila)
13. [Pauziranje i Disconnectovi](#13-pauziranje-i-disconnectovi)
14. [Pravila za Team Game](#14-pravila-za-team-game)
15. [Fair Play i Ponašanje](#15-fair-play-i-ponašanje)
16. [Streaming i Emitiranje](#16-streaming-i-emitiranje)
17. [Prijava Rezultata](#17-prijava-rezultata)
18. [Prize Pool](#18-prize-pool)
19. [Kazne i Provođenje](#19-kazne-i-provođenje)
20. [Prava i Odgovornosti Admina](#20-prava-i-odgovornosti-admina)
21. [Korisni Linkovi i Alati](#21-korisni-linkovi-i-alati)
22. [Changelog](#22-changelog)

---

## 1. Uvod

### O AoEBalkan Zajednici

AoEBalkan je zajednica igrača Age of Empires 2: Definitive Edition iz balkanskog regiona (zemlje bivše Jugoslavije) i prijatelja. Naš Discord server ima ~700 članova sa 50-100 aktivnih igrača i jezgrom od ~30 ljudi koji igraju zajedno već više od 5 godina. Organiziramo vlastite turnire, igramo lobby igre svaku večer, a čak smo organizirali i IRL LAN okupljanja.

### Svrha Ovog Priručnika

Ovaj priručnik postoji da:

- **Spriječi organizacijske greške** koje su se dešavale na prošlim eventima
- **Pruži univerzalnu osnovu** koju bilo koji član zajednice može koristiti pri organiziranju turnira
- **Osigura fer, uravnoteženo i ugodno takmičenje** za sve nivoe vještine
- **Uštedi vrijeme** — organizatori ne moraju pisati pravila od nule

Ovaj dokument je inspiriran [Službenim AoE2 Tournament Priručnikom](https://www.ageofempires.com/news/tournament_handbook_ageiide/) i prilagođen potrebama naše zajednice.

### Kako Koristiti Ovaj Priručnik

Kada organizirate turnir, započnite najavu sa:

> *"Ovaj turnir prati AoEBalkan Univerzalni Turnirski Priručnik sa sljedećim izmjenama/dodacima: [navedite specifične modifikacije]"*

---

## 2. Kontrolna Lista za Organizatore

Prije najave turnira, provjerite da ste riješili:

### Prije Najave (najmanje 1-2 sedmice prije prijava)

- [ ] **Format definiran**: 1v1, 2v2, 3v3, 4v4? Single elimination, double elimination, round robin, Swiss?
- [ ] **Dužine serija definirane**: BO1, BO3, BO5, BO7 za svaku fazu
- [ ] **Map pool finaliziran**: Sve mape testirane i funkcionalne
- [ ] **Map draft preset kreiran**: Koristeći [aoe2cm.net](https://aoe2cm.net)
- [ ] **Civ draft preset kreiran**: Sa odgovarajućim banovima/snipeovima
- [ ] **Vremenski okvir utvrđen**: Period registracije, datumi grupne faze, playoff datumi, finale
- [ ] **Prize pool (ako postoji)**: Iznos, postoci distribucije i način plaćanja najavljeni unaprijed
- [ ] **Admin tim**: Najmanje 1-2 osobe dostupne za pomoć tokom turnira

### Prije Početka Turnira

- [ ] **Seeding završen**: Korištenjem konzistentne, transparentne metodologije
- [ ] **Bracketovi/grupe objavljeni**: Na Challonge, start.gg, ili Toornament
- [ ] **Map pack objavljen**: U AoE2 mod centru (ako se koriste custom mape)
- [ ] **Komunikacijski kanali spremni**: Discord kanali za zakazivanje, rezultate, itd.
- [ ] **Dokument s pravilima finaliziran**: Sve modifikacije specifične za turnir dokumentirane

### Zahtjevi za Custom Mape

**Custom mape MORAJU biti testirane prije uključivanja.** Minimalno:

- [ ] Odigrajte najmanje 2-3 test igre na svakoj custom mapi
- [ ] Provjerite da se svi početni resursi pravilno generiraju
- [ ] Provjerite da resursi nisu zarobljeni ili nedostupni
- [ ] Provjerite balans mape (oba spawna trebaju biti otprilike jednaka)
- [ ] Dokumentirajte sve specijalne mehanike ili postavke
- [ ] Ako mapa ima problema, popravite je ili je uklonite iz poola

> ⚠️ **Nikada ne uključujte netestirane custom mape u turnir.** Ovo je uzrokovalo probleme u prošlosti.

---

## 3. Registracija i Seeding

### Zahtjevi za Registraciju

- Igrači se moraju registrirati sa svojim **primarnim accountom** (najviše rangiran, najaktivniji, najpoznatiji)
- Igrači bi trebali imati najmanje **20 odigranih ranked 1v1 igara** za pomoć pri točnom seedingu
- Smurf accounti neće biti prihvaćeni
- Igrači ne bi trebali mijenjati svoje ime u igri tokom turnira

### Metode Seedinga

Odaberite jednu metodu i primjenjujte je konzistentno:

#### Za 1v1 Turnire

**Preporučeno**: Zbir (trenutnog 1v1 Elo) + (peak 1v1 Elo) sa [aoe2insights.com](https://aoe2insights.com)

- Account bi trebao imati razuman broj igara za točan rating



#### Za Team Game Turnire

**Preporučeno**: Zbir (trenutnog 1v1 Elo + peak 1v1 Elo + trenutnog TG Elo + peak TG Elo) po igraču.

- Koristite 4 najviše rangirana igrača za seeding tima (čak i ako je roster veći)
- Ručna prilagođavanja dozvoljena ako Elo jasno ne odražava vještinu

### Transparentnost Seedinga

- Objavite metodologiju seedinga prije početka turnira
- Dozvolite igračima da ospore očite greške prije izvlačenja grupa
- Ako niže seediran igrač pobijedi više seediranog igrača, nasljeđuje taj seed za naredne runde

### Poznati Igrači Bez Nedavne Ranked Aktivnosti

Za igrače s poznatim imenima u AoEBalkan zajednici koji su igrali na nekoliko prethodnih turnira ili su dugo aktivni u zajednici, organizatori mogu koristiti alternativne kriterije osim samo Elo-a. Ovo je posebno relevantno za:

- Igrače koji ne igraju ranked igre redovno
- TG-only igrače koji sudjeluju na team game turnirima
- Igrače čiji trenutni Elo ne odražava njihov stvarni nivo vještine

U takvim slučajevima, admini mogu koristiti poznavanje zajednice, prošle turnirske rezultate, ili procjenu kolega za prilagodbu seedinga.

---

## 4. Zakazivanje i Točnost

### Komunikacija

- Sva službena turnirska komunikacija mora biti na **engleskom**
- Igrači koji ne mogu komunicirati na engleskom mogu odrediti predstavnika
- Igrači moraju odgovoriti na poruke o zakazivanju unutar **24 sata**
- Sva vremena mečeva i draftovi moraju biti objavljeni u određenom Discord kanalu

### Tournament Player Voice Kanali

- Igrači registrirani za AoEBalkan turnire dobit će **Tournament Player** ulogu
- Ova uloga daje pristup posebnim voice kanalima namijenjenim za turnirske mečeve
- **Igrači moraju biti prisutni u tim voice kanalima kada igraju svoje turnirske mečeve**
- Ovo omogućava adminima da brzo pristupe i komuniciraju ako nastanu problemi
- Brže rješavanje problema i jasnija komunikacija koristi svima

### Discord Uloge za Organizaciju Turnira

| Uloga | Opis |
|-------|------|
| **Event Organiser** | Članovi aktivno uključeni u organizaciju turnira |
| **Cavalier** | Moderatori servera — mogu pomoći s turnirskim pitanjima |
| **Paladin** | Admini servera — najviša uloga ispod osnivača servera |

Ako vam treba pomoć tokom turnira, kontaktirajte bilo koga s ovim ulogama.

### Zakazivanje Mečeva

- Igrači bi trebali kontaktirati protivnike što je prije moguće
- Ponudite više dostupnih termina, ne samo jedan
- Mečevi bi trebali biti zakazani s najmanje **24 sata unaprijed**
- Koristite [Crab Fit](https://crab.fit/) za pronalazak zajedničke dostupnosti
- Koristite [Discord Timestamps](https://r.3v.fi/discord-timestamps/) za vremena koja se prikazuju u lokalnoj vremenskoj zoni
- **Nakon zakazivanja, obavijestite admina** da kreira Seshbot event za vrijeme meča — ovo vrijedi za sve mečeve, bez obzira hoće li biti castani ili ne

### Točnost

- Igrači moraju biti spremni za početak u zakazano vrijeme
- **20+ minuta kašnjenja bez obavijesti**: Protivnik osvaja set, osim ako ne pristane na preraspodjelu termina
- Ako oba igrača kasne, riješite to među sobom ili kontaktirajte admina

### Setovi Moraju Biti Odigrani U Potpunosti

Kada set počne, **sve igre moraju biti odigrane u jednoj sesiji** (isti dan, uzastopno). Ne počinjite BO5 ako nemate vremena završiti ga.

### Rokovi

- Timovi/igrači koji zaostanu **2+ sedmice iza rasporeda** bit će diskvalificirani
- Ako igrač ne može igrati do roka, odmah kontaktirajte admine za moguće produženje

---

## 5. Zahtjevi za Map Pool

### Opći Zahtjevi

- Map poolovi bi trebali sadržavati **7-11 mapa** za tipične turnire
- Mape bi trebale nuditi **raznolikost** u stilu igre (open, closed, hybrid, water)
- Sve mape moraju biti testirane i potvrđeno funkcionalne na trenutnom patchu

### Standardne (Službene) Mape

Preferirajte službene mape ili poznate community mape (npr. KotD Arabia verzije). One su već balansirane i testirane.

### Custom Mape

Ako koristite custom mape:

1. **Testiranje je obavezno** — minimum 2-3 igre po mapi prije turnira
2. **Dokumentirajte specijalne postavke** (npr. "igra se na Explored", "Regicide mode")
3. **Objavite map pack** u AoE2 mod centru najmanje **1 sedmicu prije** početka turnira
4. **Pružite screenshotove** ili opise namjeravanog generiranja mape
5. **Imajte rezervni plan** — ako custom mapa ima problema usred turnira, što onda?

### Što Provjeriti Pri Testiranju Mapa

- Početni resursi se pravilno generiraju za oba igrača
- Resursi nisu zarobljeni ili nedostupni
- Relikvije se generiraju u ispravnoj količini
- Villageri ili jedinice nisu zarobljeni
- Šume, zlato, kamen, bobice su dostupni za sakupljanje
- Generiranje mape je otprilike balansirano između spawnova

---

## 6. Pravila za Map Draft

### Ključni Zahtjev

> **Svaki map draft MORA uključivati barem jedan oblik uskraćivanja protivniku (ban).**

Ovo osigurava da igrači ne mogu biti prisiljeni na mape koje hard-counteraju njihov stil igre.

### Alat za Draft

Koristite [aoe2cm.net](https://aoe2cm.net) za sve draftove. Kreirajte preset i podijelite link u pravilima turnira.

### Tko Hostira Draft

- **Više seediran igrač hostira oba drafta** (map draft prvi, zatim civ draft)
- U playoffu: igrač/tim s boljim plasmanom na turniru hostira
- Ako je jednako, originalni seed određuje hosta

### Preporučeni Draft Formati

#### BO3 Map Draft (9 mapa u poolu)
```
Host banuje 2 → Guest banuje 2 → Host pickuje 1 → Guest pickuje 1 → Random od preostalih = neutralna mapa
```

#### BO5 Map Draft (9 mapa u poolu)
```
Host banuje 1 → Guest banuje 1 → Host pickuje 2 → Guest pickuje 2 → Random od preostalih = neutralna mapa
```

#### BO7 Map Draft (11 mapa u poolu)
```
Host banuje 1 → Guest banuje 1 → Host pickuje 3 → Guest pickuje 3 → Random od preostalih = neutralna mapa
```

### Redoslijed Mapa Tokom Seta

**Opcija A (Preporučeno za BO3 grupe)**: Odigrajte sve mape redom (neutralna → pick nižeg seeda → pick višeg seeda)

**Opcija B (Preporučeno za playoff)**: Neutralna mapa prva, zatim **gubitnik prethodne igre bira sljedeću mapu** iz svojih draftanih mapa.

### Home Mape vs. Neutralne Mape

- **Home mapa**: Mapa koju je igrač pickao za sebe
- **Neutralna mapa**: Random ili slijepo pickana, nijedan igrač je nije izabrao
- Razmislite o davanju blage prednosti u serveru igraču na home mapi ako su pingovi nejednaki

---

## 7. Pravila za Civ Draft

### Ključni Zahtjev

> **Svaki civ draft MORA uključivati uskraćivanje protivniku — minimalno 2 globalna bana po igraču.**

S obzirom na trenutno stanje balansa u AoE2, civ banovi su esencijalni za fer natjecanje.

### Zašto Su Banovi Obavezni

- Neke civilizacije su značajno prejake na određenim mapama
- Bez banova, draftovi postaju "pickaj OP civ" vježbe
- Banovi dodaju stratešku dubinu i nagrađuju pripremu

### Alat za Draft

Koristite [aoe2cm.net](https://aoe2cm.net). Kreirajte presete koji odgovaraju dužini vaše serije.

### Objašnjenje Draft Akcija

| Akcija | Značenje |
|--------|----------|
| **Ban** | Nijedan igrač ne može pickati ovaj civ za bilo koju igru |
| **Pick** | Ovaj civ ide u vaš pool; možete izabrati da ga igrate u jednoj igri |
| **Snipe** | Uklanjate civ koji je protivnik već pickao (gubi ga iz svog poola) |
| **Steal** | Uzimate civ koji je protivnik pickao i dodajete ga u svoj pool |

### Preporučeni Draft Formati

#### BO3 Civ Draft
```
Globalni banovi: Host banuje 2 → Guest banuje 2
Pickovi: Naizmjenični pickovi dok svaki igrač nema 3 civa
```

#### BO5 Civ Draft
```
Globalni banovi: Host banuje 3 → Guest banuje 3
Pickovi: Naizmjenični pickovi dok svaki igrač nema 5 civova
Opcionalno: Uključite 1 snipe po igraču
```

#### BO7 Civ Draft
```
Globalni banovi: Host banuje 3 → Guest banuje 3
Pickovi: Naizmjenični pickovi dok svaki igrač nema 7 civova
Opcionalno: Uključite 1-2 snipea po igraču
```

### Pravila Civ Drafta

- **Bez ponavljanja civa**: Igrač ne može igrati istu civilizaciju dvaput u setu
- Igrači mogu pickati samo civove koje posjeduju (imaju DLC)
- Ako igrač picka civ kojeg ne može igrati (banan, već korišten, ili ne posjeduje), protivnik bira koji dostupni civ mora igrati umjesto toga

### DLC Civilizacije

- Svi trenutno objavljeni DLC civovi su dozvoljeni osim ako nije drugačije specificirano
- Ako novi DLC izađe tokom turnira, admini će najaviti je li dozvoljen
- Igrači bi trebali draftati samo civove koje osobno posjeduju

---

## 8. Lobby Postavke

### Standardne 1v1 Postavke

| Postavka | Vrijednost |
|----------|------------|
| Game Mode | Random Map (ili kako mapa specificira) |
| Location | [Mapa iz drafta] |
| Map Size | Tiny (2 player) |
| Difficulty | Hard |
| Resources | Standard |
| Population | 200 |
| Game Speed | Normal |
| Reveal Map | Normal (osim ako mapa zahtijeva drugačije) |
| Starting Age | Standard (Dark Age) |
| Ending Age | Standard |
| Treaty Length | None |
| Victory | Conquest |
| Team Together | Yes |
| All Techs | No |
| Lock Teams | Yes |
| Lock Speed | Yes |
| Record Game | Yes |

### Lobby Postavke

| Postavka | Vrijednost |
|----------|------------|
| Visibility | Public |
| Allow Spectators | Yes |
| Hide Civilizations | Yes |
| Spectator Delay | 2 minute |

### Odabir Servera

- Oba igrača trebaju podijeliti screenshotove pingova na različite servere
- Odaberite server koji minimizira ukupni ping i izjednačava razliku u pingu
- Ako se ne može postići dogovor, kontaktirajte admina
- Za home mape, blaga prednost može biti dana home igraču ako pingovi dozvoljavaju

### Oba Igrača Su Odgovorna

**Oba igrača moraju provjeriti postavke prije pokretanja.** Netočne postavke mogu rezultirati restartom.

---

## 9. Pravila u Igri

### Dozvoljene Akcije

Igrači mogu raditi sve što igra dozvoljava, uključujući:

- Walanje resursa, relikvija ili neutralnih objekata
- Ubijanje neprijateljskih villagera, herdable životinja ili divljih životinja
- Tower rush, castle drop, ili bilo koju agresivnu strategiju
- Bilo koju kreativnu ili nekonvencionalnu strategiju

### Zabranjene Akcije

- **Cheatovi ili hackovi** bilo koje vrste — instant diskvalifikacija
- **Macros** (eksterni softver koji emulira višestruke pritiske tipki) — instant diskvalifikacija
- **Stream sniping** — gledanje protivnikovog streama tokom igre
- **Vanjska pomoć** — primanje pomoći od spectatora, stream chata, ili voice chata s ne-saigračima
- **Namjerni bugovi/exploiti** — korištenje poznatih game-breaking exploita

### Grafički Modovi

- Grafički modovi iz službenog mod centra su dozvoljeni
- Small trees, grid terrain, i slični vizualni pomagači su dozvoljeni
- Modovi koji daju gameplay prednost nisu dozvoljeni (npr. otkrivanje skrivenih informacija)

---

## 10. Pravila za Laming

### Definicija

"Laming" se odnosi na early-game taktike uznemiravanja koje ometaju protivnikovu ekonomiju bez direktnog vojnog angažmana, kao što su:

- Krađa ili ubijanje neprijateljskih ovaca/vepra
- Walanje neprijateljskih resursa
- Ubijanje neprijateljskih jelena ili druge divljači
- Scout harassment

### Defaultno Pravilo: Laming Dozvoljen

**Po defaultu, laming je dozvoljen** na standardnim mapama. Ovo uključuje:

- Krađa neprijateljskih herdable životinja (ovce, vepra, jelena)
- Ubijanje neprijateljskih herdable životinja
- Walanje neprijateljskih resursa
- Bilo kakva rana agresija

### Opcionalno: No-Laming Pravilo

Organizatori mogu izabrati implementaciju **no-laming pravila** za specifične turnire. Ako da, jasno definirajte:

1. Koje akcije su zabranjene
2. Vremenski okvir (npr. "prvih 5 minuta" ili "do Feudal Age")
3. Kaznu za prekršaj (obično gubitak igre)

Primjer no-laming pravila:
> *"Laming je zabranjen u Dark Age. Igrači ne smiju krasti, ubijati, ili walati protivnikove početne resurse (ovce, veprove, bobice, jelene) dok barem jedan igrač ne dosegne Feudal Age. Prekršaj rezultira gubitkom igre."*

### Pravila za Laming Specifična za Turnir Moraju Biti Jasna

Ako vaš turnir modificira laming pravila, navedite to eksplicitno. Ne ostavljajte dvosmisleno.

---

## 11. Pravila za Nomad Mape

> **Napomena**: Ova pravila se primjenjuju samo na **custom nomad mape koje onemogućuju ugrađeni Nomad Treaty**. Defaultne nomad mape u igri (kao Nomad, Land Nomad, itd.) imaju ugrađeni Treaty koji automatski upravlja ovim restrikcijama — ova ručna pravila nisu potrebna za te mape.

Na custom nomad mapama bez ugrađenog Treaty-ja, sljedeća pravila vrijede tokom **prve 3 minute** in-game vremena:

### Zabranjene Akcije (Prve 3 Minute)

- ❌ Napadanje neprijateljskih jedinica, zgrada ili herdable životinja
- ❌ Walanje neprijateljskih jedinica, zgrada ili resursa
- ❌ Walanje relikvija
- ❌ Gradnja vašeg prvog TC-a u dometu paljbe neprijateljskog TC-a
- ❌ Ubijanje divljih životinja bez sakupljanja najmanje 35 hrane s lešine

### Dozvoljene Akcije (Prve 3 Minute)

- ✅ Krađa neprijateljskih herdable životinja (preuzimanje kontrole bez ubijanja)
- ✅ Scouting neprijateljskih pozicija
- ✅ Normalne ekonomske aktivnosti

### Postavljanje TC-a

Ako dva igrača slučajno izgrade svoje TC-ove u dometu jedan drugog, igra mora biti **odmah restartana**.

### Nakon 3 Minute

Nakon 3 minute, sva normalna pravila vrijede. Laming, napadanje i agresivna igra su u potpunosti dozvoljeni.

---

## 12. Restart Pravila

### Restart od Strane Igrača

- Svaki igrač dobija **1 besplatni restart** po setu (BO3, BO5, itd.)
- Besplatni restart može biti pozvan samo u **prvih 5 minuta** in-game vremena
- Razlog ne mora biti naveden za besplatni restart
- Nakon korištenja besplatnog restarta, dodatni restarti zahtijevaju odobrenje admina

### Admin Restarti (Bugovane Mape)

Admin restarti se ne računaju protiv igračevog besplatnog restarta. Odobravaju se kada:

- Više od 25% resursa (zlato, kamen, bobice) je nedostupno
- Početni resursi se nisu pravilno generirali
- Villageri ili jedinice su spawn zarobljeni
- Relikvije se nisu generirale u ispravnoj količini
- Herdable ili divlje životinje su zarobljene ili nedostupne
- Bilo koji veći propust u generiranju mape koji utječe na fer igru

### Kako Zatražiti Restart

1. **Pauzirajte igru odmah**
2. **Kontaktirajte admina** ako je dostupan; inače, razgovarajte s protivnikom
3. **Dokumentirajte problem** (screenshot ako je moguće)
4. Ako admin nije dostupan i igrači se ne slažu, igra se nastavlja i admin pregledava replay

### Nakon Restarta

- **Ista mapa** se mora igrati
- **Iste civilizacije** se moraju koristiti
- Igrači ne smiju otkriti mapu ili gledati replay prije rehosta

---

## 13. Pauziranje i Disconnectovi

### Pravila Pauziranja

- Pauzirajte samo za **tehničke probleme** (lag, problemi s konekcijom, problemi s hardverom)
- Ne pauzirajte iz strateških razloga (provjera tech treea, razmišljanje o odlukama)
- Obavijestite protivnika odmah kada pauzirate
- Igrač koji je pauzirao mora unpausirati
- Potvrdite da je protivnik spreman prije unpausiranja

### Prekomjerno Pauziranje

Ponavljano pauziranje bez validnog razloga rezultirat će upozorenjima i potencijalnim kaznama.

### Disconnectovi i Crashevi

1. Ako igra crashuje ili desynca, **izađite bez otkrivanja mape**
2. Pokušajte **restorati igru** koristeći restore funkciju
3. Ako restore ne uspije:
   - **Jasna prednost**: Admin može dodijeliti igru igraču koji vodi
   - **Bez jasne prednosti**: Ponovno odigrajte cijelu igru s istim civovima i mapom
4. Ne gledajte replay prije rehosta

### Igrač Ne Može Nastaviti

Ako igrač ima tehničke probleme koji ga sprječavaju da nastavi:

- Odmah kontaktirajte admina
- Admin će odrediti je li moguće prerasporediti termin
- Ponavljani tehnički problemi mogu rezultirati forfeitom

---

## 14. Pravila za Team Game

### Sastav Tima

- Rosteri timova trebaju biti deklarirani prije početka turnira
- Promjene rostera nakon prijave zahtijevaju odobrenje admina
- Zamjenski igrači moraju imati jednak ili niži Elo od igrača kojeg zamjenjuju

### Zahtjevi za Igrače

- Svi igrači na rosteru trebaju sudjelovati u najmanje 1 igri tokom grupne faze
- Timovi se potiču da imaju 5+ igrača radi fleksibilnosti u zakazivanju

### Boje Timova

Koristite standardne dodjele boja timovima:

- **Tim 1**: Blue (1), Green (3), Teal (5), Gray (7) — flankovi su 1 i 7
- **Tim 2**: Red (2), Yellow (4), Purple (6), Orange (8) — flankovi su 2 i 8

Omogućite "Team Positions" u lobby-ju za kontrolu spawn pozicija.

### Pravila za Slinging

**Defaultno pravilo**: Slinging (slanje resursa saigračima) je dozvoljen samo kada:

- **Igrač koji šalje** je u višem Age-u od igrača koji prima, ILI
- I pošiljalac i primalac su u **Imperial Age**

Organizatori turnira mogu modificirati ovo pravilo, ali moraju to jasno navesti.

### Komunikacija Tima

- Timovi mogu koristiti voice chat (Discord, itd.) tokom igara
- Komunikacija s bilo kim izvan tima tokom igara nije dozvoljena

---

## 15. Fair Play i Ponašanje

### Očekivano Ponašanje

Svi sudionici moraju:

- Pokazivati dobar sportski duh u svakom trenutku
- Tretirati protivnike, admine i castere s poštovanjem
- Surađivati s adminima na rješavanju sporova
- Uvijek igrati za pobjedu (bez namjernog gubljenja)

### Zabranjeno Ponašanje

- **Uvrede, uznemiravanje ili toksično ponašanje** — u igri, na Discordu, ili drugdje
- **Rasizam, seksizam ili diskriminacija** bilo koje vrste
- **Namještanje mečeva ili klađenje** na igre u kojima sudjelujete
- **Manipulacija seedinga** — namjerno gubljenje za lakši bracket
- **Lažno predstavljanje** — igranje pod tuđim accountom

### Komunikacija Tokom Igara

- Komunikacija s bilo kim osim saigračima i adminima je **zabranjena** tokom igara
- Ovo uključuje stream chat, spectatore, i voice chat s ne-saigračima
- Prekršaj se smatra varanjem

### Sporovi

- Ako vjerujete da je protivnik prekršio pravila, **pauzirajte i kontaktirajte admina**
- Ne raspravljajte u igri; pustite admine da rješavaju sporove
- Odluke admina su konačne

---

## 16. Streaming i Emitiranje

### Igrački Streaming (POV)

- Igrači mogu streamati svoj POV **na vlastiti rizik**
- Stream delay nije potreban, ali igrači prihvaćaju rizik da protivnici potencijalno gledaju
- Stream chat i donacije ne bi trebali biti vidljivi/čujni igraču tokom igara

### Casting

- Sve turnirske igre mogu biti castane od bilo koga
- Casteri trebaju navesti turnir i organizatore
- Live castovi moraju poštovati spectator delay
- Za castove snimljenih igara, rezultati ne smiju biti otkriveni prije emitiranja
- **Ako casteri žele streamati igru uživo**, igrači moraju surađivati i pružiti game/lobby ID ako casteri imaju problema sa spectateanjem

### Stream Sniping

- Gledanje protivnikovog streama tokom igre je **strogo zabranjeno**
- Ovo se smatra varanjem i rezultira trenutnom diskvalifikacijom

### Privatni Mečevi

- Neki mečevi se mogu igrati privatno za kasnije emitiranje
- Igrači ne smiju otkrivati rezultate prije emitiranja
- Snimljene igre moraju biti poslane odmah nakon seta

---

## 17. Prijava Rezultata

### Kako Prijaviti

1. Završite sve igre u setu
2. **Preimenujte vaše snimljene igre** u format: `IgračA vs IgračB g1.aoe2record`, `IgračA vs IgračB g2.aoe2record`, itd.
3. **Spakirajte sve snimljene igre u .zip datoteku** (npr. `IgračA_vs_IgračB.zip`)
4. Objavite u **#recorded-games** kanalu na AoEBalkan Discordu
5. Uključite sljedeće informacije:
   - Imena igrača
   - Map draft link (sa aoe2cm.net)
   - Civ draft link (sa aoe2cm.net)
   - **Rezultat u spoiler tagovima** (koristite `||2-1||` format na Discordu)
6. Priložite .zip datoteku

### Primjer Formata

```
IgračA vs IgračB
Maps: https://aoe2cm.net/draft/yMFrx
Civs: https://aoe2cm.net/draft/LWfKR
Result: ||2-1||
[IgračA_vs_IgračB.zip priložen]
```

### Kako Dodati Spoiler Tagove na Discordu

**Metoda 1 (tipkanje)**: Omotajte tekst u dvostruke pipe znakove: `||2-1||` → prikazuje se kao ||2-1||

**Metoda 2 (selekcija)**: 
1. Upišite vašu poruku s rezultatom
2. Selektirajte/označite tekst rezultata
3. Kliknite na **ikonu oka** (👁) u traci za formatiranje koja se pojavi
4. Selektirani tekst postaje spoileriran

### Snimljene Igre

- Sve snimljene igre moraju biti sačuvane i poslane
- **Anti-spoiler pravilo**: Ako je set završio prije maksimalnog broja igara (npr. 2-0 u BO3), uključite dummy datoteku za neodigrane igre — samo kopirajte i preimenujte drugi replay. Ovo sprječava castere da saznaju rezultat na temelju broja datoteka.
- Snimke mogu biti zatražene od admina u bilo kojem trenutku
- Sumnjive igre će biti pregledane

---

## 18. Prize Pool

### Zahtjev za Transparentnost

Ako turnir ima prize pool, organizator **mora najaviti sljedeće prije zatvaranja prijava**:

1. **Početni iznos prize poola** (čak i ako se očekuje da će rasti)
2. **Postoci distribucije** za svako mjesto (1., 2., 3., itd.) — ovi ostaju fiksni bez obzira na konačni iznos
3. **Način plaćanja** (PayPal, bankovna transakcija, itd.)
4. **Očekivani rok isplate** (npr. "unutar 2 sedmice od kraja turnira")

Ako se prihvaćaju donacije:
- Podijelite link za donacije (npr. PayPal pool)
- Držite zajednicu informiranom o trenutnom ukupnom iznosu kako raste
- Konačni prize pool je koliki god iznos bude kad turnir završi

### Preporučeni Primjeri Distribucije

#### 1v1 Turnir (Top 4 plaćeni)
| Mjesto | Postotak |
|--------|----------|
| 1. | 50% |
| 2. | 25% |
| 3. | 15% |
| 4. | 10% |

#### 1v1 Turnir (Top 8 plaćeni)
| Mjesto | Postotak |
|--------|----------|
| 1. | 40% |
| 2. | 20% |
| 3.-4. | 12% svaki |
| 5.-8. | 4% svaki |

#### Team Turnir (Top 4 plaćeni)
| Mjesto | Postotak |
|--------|----------|
| 1. | 50% |
| 2. | 30% |
| 3. | 20% |

### Principi Fer Distribucije

- Distribucija treba biti najavljena **prije** početka turnira, ne poslije
- Ne mijenjajte distribuciju usred turnira osim ako se svi pogođeni igrači ne slože
- Prize pool od kotizacija treba u cijelosti ići igračima (minus jasno navedeni troškovi)
- Ako koristite donacije, budite transparentni o trenutnom ukupnom iznosu

### Isplata

- Organizatori trebaju isplatiti nagrade **unutar 30 dana** od završetka turnira
- Komunicirajte s pobjednicima o preferencijama načina plaćanja
- Vodite evidenciju izvršenih plaćanja

---

## 19. Kazne i Provođenje

### Uobičajeni Prekršaji i Kazne

| Prekršaj | Kazna |
|----------|-------|
| Kašnjenje na meč (20+ min) | Protivnik osvaja set (osim ako se dogovori preraspodjela) |
| Nepojavljivanje bez obavijesti | Protivnik osvaja set + potencijalna diskvalifikacija |
| Stream sniping | Diskvalifikacija |
| Pogrešan civ pickan | Restart, protivnik bira vaš civ |
| Pogrešne lobby postavke | Restart (bez kazne ako se uhvati rano) |
| Prekršaj laming pravila (ako vrijede) | Gubitak igre |
| Prekršaj Nomad pravila | Gubitak igre |
| Korištenje macrosa/cheatova | Diskvalifikacija + potencijalni ban |
| Toksično ponašanje | Upozorenje → privremeni ban → trajni ban |
| Namještanje mečeva | Diskvalifikacija + trajni ban |

### Eskalacija

1. **Prvi prekršaj (manji)**: Upozorenje
2. **Drugi prekršaj ili veći prekršaj**: Gubitak igre/seta
3. **Ponovljeni prekršaji ili ozbiljno nedolično ponašanje**: Diskvalifikacija
4. **Varanje ili namještanje mečeva**: Trajni ban sa community turnira

### Diskrecija Admina

Admini mogu primijeniti bilo koju kaznu koju smatraju prikladnom. Ovo uključuje situacije koje nisu eksplicitno pokrivene pravilima.

---

## 20. Prava i Odgovornosti Admina

### Prava Admina

- Izmijeniti, ukloniti ili promijeniti pravila po potrebi
- Donositi prosudbe o situacijama koje nisu pokrivene pravilima
- Primjenjivati kazne kako je prikladno
- Restartati ili dodijeliti igre na temelju dokaza

### Odgovornosti Admina

- Biti dostupan tokom zakazanih vremena mečeva
- Odgovarati na upite igrača pravovremeno
- Primjenjivati pravila konzistentno i fer
- Dokumentirati sve presude i kazne
- Ostati nepristran

### Sukob Interesa

- Ako je organizator ili admin također igrač, moraju se **izuzeti** iz bilo kakvih odluka koje uključuju njihove vlastite mečeve
- Drugi admin mora rješavati sporove koji uključuju admin-igrače

### Žalbe

- Igrači mogu uložiti žalbu na odluke admina glavnom organizatoru
- Držite žalbe razumnima — mi smo zajednica, ne sud
- Konačne odluke donosi organizator turnira

---

## 21. Korisni Linkovi i Alati

### Draftanje

- **Captains Mode**: [aoe2cm.net](https://aoe2cm.net) — za map i civ draftove

### Bracketovi i Zakazivanje

- **Challonge**: [challonge.com](https://challonge.com)
- **Start.gg**: [start.gg](https://start.gg)
- **Toornament**: [toornament.com](https://toornament.com)
- **Crab Fit**: [crab.fit](https://crab.fit) — dostupnost za zakazivanje
- **Discord Timestamps**: [r.3v.fi/discord-timestamps](https://r.3v.fi/discord-timestamps/)

### Statistike Igrača i Seeding

- **AoE2 Insights**: [aoe2insights.com](https://aoe2insights.com) — profili igrača i detaljne statistike
- **AoE2.gg**: [aoe2.gg](https://aoe2.gg/) — alternativa ako aoe2insights ne radi

### Resursi za Igru

- **AoE2 Tech Tree**: [aoe2techtree.net](https://aoe2techtree.net) — online tech treeovi za sve civilizacije

### Upravljanje Replayevima

- **Replay Packer**: [replaypacker.zeta-two.com](https://replaypacker.zeta-two.com/)

### Službeni Resursi

- **Službeni AoE2 Tournament Priručnik**: [ageofempires.com/news/tournament_handbook_ageiide](https://www.ageofempires.com/news/tournament_handbook_ageiide/)
- **AoE2 Code of Conduct**: [ageofempires.com/code-of-conduct](https://www.ageofempires.com/code-of-conduct/)

### AoEBalkan Zajednica

- **Web stranica**: [aoebalkan.com](https://aoebalkan.com/) — informacije o našim eventima
- **Discord**: [discord.com/invite/dfZWAFR](https://discord.com/invite/dfZWAFR)
- **Twitch**: [twitch.tv/aoebalkan](https://twitch.tv/aoebalkan)
- **YouTube**: [youtube.com/@AoEBalkan](https://www.youtube.com/@AoEBalkan)

---

## 22. Changelog

| Verzija | Datum | Izmjene |
|---------|-------|---------|
| 1.0 | August 2026 | Inicijalna verzija bazirana na Akkal's 4v4 League, Službenom MS Priručniku i iskustvu zajednice |

---

## Dodatak A: Brza Referentna Kartica

### Određivanje Hosta Drafta
- Viši seed = Host za oba drafta
- U playoffu, bolji plasman = Host

### Točnost
- 20 min kašnjenja = protivnik osvaja set (osim ako pristanu na preraspodjelu)

### Restarti
- 1 besplatni restart po setu (prvih 5 minuta)
- Admin restarti za bugovane mape (ne broje se protiv vas)

### Nomad Pravila (Custom mape bez ugrađenog Treaty-ja, prve 3 min)
- Bez napadanja
- Bez walanja neprijateljskih resursa
- Krađa herdable životinja OK
- TC u dometu neprijateljskog TC-a = trenutni restart

### Slinging (Team Games)
- OK ako je pošiljalac u višem Age-u, ILI oboje u Imperial Age

---

## Dodatak B: Predložak za Najavu Turnira

```
📢 [IME TURNIRA]

Format: [1v1 / 2v2 / itd.] [Single Elim / Double Elim / Round Robin]
Prize Pool: [Iznos ili "Za slavu"]
Datumi: [Registracija] → [Grupna Faza] → [Playoff] → [Finale]

Ovaj turnir prati AoEBalkan Univerzalni Turnirski Priručnik sa ovim modifikacijama:
- [Navedite izmjene]

Map Pool: [Navedite mape ili link na map pack]
Draft Linkovi:
- Map Draft: [aoe2cm.net link]
- Civ Draft: [aoe2cm.net link]

Prijava: [Google Form / Discord komanda / itd.]
Pitanja: Kontaktirajte [Imena admina]
```

---

*Ovaj priručnik održava AoEBalkan zajednica. Prijedlozi za poboljšanja su dobrodošli.*
