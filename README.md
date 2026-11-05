# Mõttesäde – programmeerimisprojekti plaan

**Projekti seis:** kavandamisel. Tegemist on koolitöö raames koostatava projektiplaaniga; veebilehte ei ole veel valmis programmeeritud.

## 1. Projekti nimi

**Mõttesäde**

Projekti võimalik veebiaadress on **mottesade.ee** (domeeninime kasutatavus tuleb enne registreerimist üle kontrollida).

Projekti juhtmõte on **„Mõtle ise. Avasta rohkem.”**

## 2. Eesmärk

Mõttesäde on kavandatav õppeveebileht, mis aitab lastel ja noortel arendada iseseisvat mõtlemist, loogikat, probleemilahendusoskust ja tehisintellekti (AI) alaseid teadmisi.

Tehisintellekti kasutatakse üha rohkem õppimisel ja igapäevaelus, kuid selle vastused ei pruugi alati õiged olla. Seetõttu on oluline õpetada noori ise mõtlema, küsimusi esitama, vastuseid kontrollima ja infot kriitiliselt hindama. Veebilehe eesmärk ei ole panna lapsi iga ülesande puhul AI-d kasutama, vaid näidata, kuidas tehnoloogia saab inimest toetada ilma iseseisvat mõtlemist asendamata.

Õppimine peab olema lihtsasti kättesaadav: põhiharjutuste tegemiseks ei ole vaja kontot luua ega sisse logida.

## 3. Sihtgrupp

Mõttesäde on mõeldud eelkõige:

- **1.–4. klassi õpilastele**, kellele luuakse esimeses versioonis lihtsad ja mängulised harjutused;
- **lapsevanematele**, kes soovivad koos lapsega arendada mõtlemisoskust ja selgitada AI võimalusi ning piiranguid;
- **õpetajatele**, kes saavad harjutusi tunnis kasutada.

Tulevikus võiks õppekeskkonda laiendada **5.–9. klassile, gümnaasiumiõpilastele, kutseõppuritele ja IT-huvilistele**, pakkudes igale vanuserühmale sobiva raskusastmega ülesandeid.

## 4. Funktsionaalsus

Esimesse versiooni kavatsen teha järgmised funktsioonid:

1. **Õppimine ilma kontota.** Kasutaja saab kohe ülesandeid lahendama hakata, ilma et peaks registreeruma.
2. **Õppeteemade ja raskusastme valimine.** Kasutaja saab valida näiteks loogikaülesandeid, kriitilise mõtlemise harjutusi või tehisintellekti tundmaõppimist.
3. **Interaktiivsed ülesanded.** Kasutaja saab lahendada küsimusi, mõistatusi ja olukorraülesandeid ning valida või sisestada vastuseid.
4. **Piltidega ülesanded.** Kasutaja saab lahendada ka piltide põhjal tehtud harjutusi, näiteks leida pildilt vigu, jätkata mustrit, võrrelda pilte või valida pildi järgi õige vastuse. See aitab arendada tähelepanu, loogikat ja iseseisvat mõtlemist.
5. **AI vastuste kontrollimise harjutused.** Kasutajale näidatakse eelnevalt koostatud näidisvastuseid, milles võib olla vigu. Ta peab ise mõtlema ja otsustama, kas vastus on õige ning kuidas seda kontrollida.
6. **Tagasiside ja selgitused.** Pärast vastamist saab kasutaja teada, kas vastus oli õige, ning näeb lihtsat ja eakohast selgitust. Oluline on mõista lahenduskäiku, mitte ainult punkte koguda.
7. **Eestikeelne õppekeskkond.** Veebilehe tekstid, juhised ja ülesanded on esialgu eesti keeles.
8. **Õppimise edenemise salvestamine samas brauseris.** Lahendatud ülesanded ja lihtne punktiseis salvestatakse võimaluse korral brauseri kohalikku salvestusruumi. Brauseri andmete kustutamisel võib külalise edenemine kaduda.
9. **Telefoni-, tahvli- ja arvutisõbralik kujundus.** Veebileht peab olema kasutatav eri ekraanisuurustel.

### Edasised võimalused

Kui esimene versioon hästi töötab, saab veebilehte edasi arendada. Näiteks võiks kasutaja soovi korral konto luua, et oma tulemusi erinevates seadmetes näha. Lapsevanem võiks aidata lapse õppimist jälgida ja õpetaja saaks valida klassile sobivaid ülesandeid. Tulevikus võiks lisada keerulisemaid harjutusi 5.–12. klassi õpilastele ning kutse- ja IT-õppuritele.

## 5. Tehnoloogiad

Esimese versiooni arendamiseks kavatsen kasutada järgmisi tehnoloogiaid ja tööriistu:

- **HTML** – veebilehe struktuuri loomiseks;
- **CSS** – kujunduse ning eri ekraanisuurustele sobiva paigutuse tegemiseks;
- **JavaScript** – interaktiivsete ülesannete, piltidega harjutuste ja vastuste kontrollimise programmeerimiseks;
- **JSON** – küsimuste, vastuste ja selgituste korrastatud hoidmiseks;
- **localStorage** – lihtsa õppimisprogressi salvestamiseks kasutaja brauseris;
- **Visual Studio Code** – koodi kirjutamiseks;
- **Git ja GitHub** – muudatuste jälgimiseks ja projekti hoidmiseks.

Kui projekt kasvab ja lisanduvad kasutajakontod, võib hiljem kasutada **Node.js-i**, **Expressi** ja näiteks **SQLite'i või PostgreSQL-i** andmebaasi. Neid ei ole esimeseks töötavaks versiooniks tingimata vaja.

## 6. Teostusplaan

1. **Planeerimine.** Täpsustan sihtgrupi, valin esimesed õppeteemad ja kirjeldan, kuidas ülesanded töötavad.
2. **Kujundamine.** Koostan lihtsa, sõbraliku ja arusaadava veebilehe kavandi, mida on mugav kasutada ka telefonis ja tahvelarvutis.
3. **Veebilehe põhja loomine.** Programmeerin avalehe, teemade valiku ja eestikeelse kasutajaliidese.
4. **Harjutuste programmeerimine.** Loon esimesed loogikaülesanded, piltidega harjutused ning AI näidisvastuste kontrollimise ülesanded koos selgitustega.
5. **Edenemise salvestamine.** Lisan lahendatud ülesannete ja punktide salvestamise brauserisse ilma kasutajakontota.
6. **Testimine ja parandamine.** Kontrollin veebilehte arvutis ja mobiilseadmes, proovin eri vastuseid ning küsin võimaluse korral õpetajatelt või lapsevanematelt tagasisidet.
7. **Esimese versiooni viimistlemine.** Parandan leitud vead, kontrollin õppematerjalide arusaadavust ja kirjeldan projekti kasutamist GitHubis.

Pärast esimese versiooni valmimist saan otsustada, millised lisafunktsioonid on kasutajatele päriselt vajalikud.

## 7. Valmisoleku kriteeriumid

Loen **projekti esimese versiooni** valminuks, kui:

- veebileht avaneb ja seda saab kasutada nii arvutis kui ka telefonis;
- kasutaja saab alustada õppimist **ilma registreerumise ja sisselogimiseta**;
- olemas on vähemalt **kolm õppeteemat**: loogika, kriitiline mõtlemine ja AI tundmaõppimine;
- õppeteemades on töötavad tekstipõhised ja piltidega ülesanded;
- ülesannetele vastates kuvatakse asjakohane tagasiside ja selgitus;
- veebilehe juhised, küsimused ja selgitused on **eesti keeles**;
- kasutaja põhiline õppimisprogress salvestub samas brauseris ja on lehe uuesti avamisel nähtav, kui brauseri andmeid pole kustutatud;
- põhilised funktsioonid on testitud ning teadaolevad kasutamist takistavad vead on parandatud.

Esialgu saab õppida ilma kasutajakontota. Kõigepealt keskendun sellele, et ülesanded oleksid huvitavad, arusaadavad ja korralikult töötavad.

---

**Projekti põhimõte:** laps proovib kõigepealt ise mõelda ja lahendust leida. Tehisintellekti kohta õpitakse seda, kuidas selle võimalusi mõista, selle vastuseid kontrollida ning seda vastutustundlikult kasutada.

**Taustamaterjal:** [OECD ja Euroopa Komisjoni 2026. aasta tehisintellekti kirjaoskuse raamistik üldharidusele](https://www.oecd.org/en/publications/empowering-learners-for-the-age-of-ai_65cd27d4-en.html).
