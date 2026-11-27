---
title: "Politica de confidențialitate"
permalink: /privacy/ro/
lang: ro
alt: /privacy/
altLabel: Русский
---
# Politica de confidențialitate

**Aplicația:** AI Storyteller: Fairy Gardens  
**Operatorul datelor:** Turlaeva Elena Vladimirovna, Republica Moldova  
**Contact pentru date:** aistoryteller.team@gmail.com  
**Data intrării în vigoare:** 26.11.2026

## 1. Cine și de ce
Contul este creat de un **adult** (părinte/reprezentant legal). Prelucrăm minimul de
date necesar pentru funcționarea Aplicației: crearea poveștilor, păstrarea
bibliotecii familiei și funcționarea abonamentului.

## 2. Ce date colectăm
- **Contul adultului:** autentificarea se face prin Google — primim adresa de e-mail
  și identificatorul contului Google. Aplicația nu are o parolă separată, iar parola
  de Google nu o vedem.
- **Datele de autentificare:** token-uri de sesiune, ca să nu vă cerem autentificarea
  la fiecare pornire. Se păstrează în spațiul securizat al dispozitivului (Android
  Keystore / iOS Keychain) și nu se transmit terților.
- **Codul PIN al secțiunii pentru părinți:** se păstrează pe dispozitiv **sub formă
  de hash cu „sare”**; nu cunoaștem codul și nu îl putem recupera.
- **Biometria (opțional):** amprenta sau fața este verificată de **sistemul de
  operare însuși**. Aplicația primește doar răspunsul „confirmat / neconfirmat”;
  datele biometrice nu părăsesc dispozitivul și nu ne sunt transmise.
- **Numele adultului — opțional.** Câmpul poate fi lăsat gol sau șters mai târziu.
  Atunci aplicația afișează în locul numelui rolul ales („Mama”, „Tata” sau propria
  formulare). Rolul este necesar: intră în poveste, iar rudele se recunosc după el.
- **Profilul copilului (introdus de adult):** numele, genul, avatarul ales,
  deprinderile bifate. Numele este necesar pentru ca povestea să fie despre un
  anumit copil — acesta este rostul aplicației. **Nu introduceți date personale
  inutile despre copii: numele de familie, adresa, școala sau grădinița.**

  Data nașterii și vârsta copilului **nu le cerem și nu le păstrăm**. Un prenume
  fără nume de familie aproape că nu identifică pe nimeni, dar combinația „prenume +
  data exactă a nașterii” deja da, iar pentru o aplicație pentru copii acesta este un
  risc inutil. Nivelul limbajului se stabilește altfel: implicit textul folosește
  cele mai simple cuvinte, iar dacă e nevoie de o poveste pentru un copil mai mare,
  adultul scrie acest lucru în câmpul de dorințe speciale.

  Nici nume al familiei nu avem: oamenii scriau acolo numele de familie, iar
  aplicației nu îi trebuia deloc.
- **Conținutul creat:** textele poveștilor, ilustrațiile, narațiunile audio — se
  păstrează ca să vă puteți întoarce la ele.
- **Date tehnice:** jurnalele de generare (ora, abonamentul, statutul
  reușită/eroare, ce serviciu a lucrat) — pentru limite, protecția împotriva
  abuzurilor și statistici agregate.
- **Hash-ul identificatorului dispozitivului — doar pentru protecția poveștilor
  gratuite.** Pe Android aplicația ia identificatorul pe care sistemul îl atribuie
  anume aplicației noastre (ANDROID_ID) și **trimite nu identificatorul, ci un hash
  ireversibil al lui** (SHA-256); pe server este „hash-uit” încă o dată. Scopul este
  unul: setul de povești gratuite se acordă o singură dată pe telefon, nu fiecărui
  cont nou creat pe el. Hash-ul se păstrează separat de cont, de familie și de e-mail;
  lângă el se află doar numărul de povești gratuite deja folosite, așa că
  înregistrarea nu poate fi legată de o persoană. Din același motiv se păstrează și
  un **hash al adresei de e-mail** (SHA-256, fără adresa însăși) cu același contor:
  altfel setul ar putea fi obținut din nou ștergând contul și înregistrându-vă cu
  același e-mail. ANDROID_ID însuși nu părăsește dispozitivul, iar alte aplicații nu
  ne pot asocia după el: fiecare aplicație îl are pe al său. Identificatorul de
  publicitate (AAID), IMEI, numerele de serie, adresa MAC și alți identificatori
  hardware **nu îi colectăm**.
- **Datele despre cumpărături:** identificatorul produsului și token-ul de cumpărare
  Google Play, statutul și termenul abonamentului. Token-ul se leagă de familia
  dumneavoastră, ca un singur bon plătit să nu poată fi folosit în mai multe conturi.
  Numărul cardului și alte date de plată **nu le primim și nu le păstrăm**: plata
  este procesată integral de Google Play.
- **Reclama — doar în abonamentul gratuit și doar la alegerea adultului.** Când
  adultul creează o poveste în secțiunea pentru părinți (protejată cu un cod PIN),
  Aplicația propune vizionarea unui clip scurt cât se scrie povestea. Clipul pornește
  doar dacă adultul apasă singur „Vizionează”. În secțiunea copilului nu există
  reclame. Clipurile sunt afișate de rețeaua publicitară **Google AdMob** (Google LLC,
  vezi secțiunea 5).

  Al doilea caz este narațiunea propriei povești cu vocea Studio în schimbul unui
  clip (cel mult două pe zi). Vocea se alege în setările de lectură, dar propunerea
  de a viziona clipul apare doar după verificarea că este un adult: introducerea
  codului PIN al părintelui sau, dacă PIN-ul nu este setat, tastarea unui număr
  scris în cuvinte. Copilul nu poate porni singur clipul.

  Fiecare cerere de reclamă este marcată ca fiind destinată copiilor și ca venind de
  la un utilizator sub vârsta consimțământului. De aceea reclama este
  **nepersonalizată**: Google nu o alege după istoricul acțiunilor și nu construiește
  un profil publicitar, iar conținutul este limitat la categoria „pentru toate
  vârstele” (G). Aplicația nu cere identificatorul de publicitate (AAID): această
  permisiune este blocată în ea.

  Pentru a afișa clipul, Google primește date tehnice: adresa IP, modelul
  dispozitivului și versiunea sistemului, limba, informații despre Aplicație,
  identificatorul setului de aplicații (App Set ID), informații despre afișarea
  clipului și atingeri. Google le folosește pentru livrarea reclamei, numărarea
  afișărilor și protecția împotriva fraudei, conform
  [politicii](https://policies.google.com/technologies/ads) sale. Date despre cont,
  e-mail, numele copiilor și textele poveștilor rețeaua publicitară **nu primește**
  de la noi.

  Temeiul juridic este interesul nostru legitim: reclama plătește poveștile gratuite
  (art. 6 alin. (1) lit. (f) GDPR). Puteți oricând să nu vizionați clipul: apăsați
  „Anulează” (atunci povestea gratuită nu se creează) sau treceți la un abonament
  plătit, unde nu există reclame.

**Nu** colectăm locația sau contactele, nu afișăm reclame personalizate și nu vindem
date.

## 2.1. Protecția împotriva abuzurilor
Pentru ca limitele gratuite să nu poată fi ocolite, iar serviciul să rămână
disponibil tuturor, aplicăm:
- limitarea frecvenței cererilor (câte generări pe minut sunt permise de pe un cont)
  — pentru aceasta se păstrează pentru scurt timp momentele cererilor;
- numărarea poveștilor, ilustrațiilor și narațiunilor create pe zi — pentru
  respectarea limitei abonamentului;
- legarea bonului de plată de familie, ca o cumpărătură să nu poată fi folosită în
  mai multe conturi;
- oprirea automată a generării după erori tehnice repetate — ca să nu se consume
  degeaba nici limitele dumneavoastră, nici resursele noastre.

Temeiul juridic este interesul nostru legitim de a proteja serviciul de abuzuri
(art. 6 alin. (1) lit. (f) GDPR pentru utilizatorii din UE).

## 2.2. Verificarea conținutului cererilor
Aplicația este pentru copii, de aceea textul pe care adultul îl scrie în câmpul de
dorințe speciale se păstrează în jurnal **90 de zile** și se verifică automat pentru
teme interzise (violență, conținut sexual, droguri, autovătămare, arme, ură,
cruzime). Dacă o astfel de temă este depistată, cererea ajunge într-o notificare
către administrator.

Ce înseamnă aceasta în practică:
- povestea însăși rămâne potrivită pentru copii indiferent de cerere — de asta
  răspund instrucțiunile date serviciului AI, nu această verificare;
- pentru un cerc restrâns de teme care nu pot fi interpretate nevinovat (de exemplu,
  consumul de substanțe sau acțiuni periculoase de imitat), povestea **nu se creează
  automat** pentru o astfel de cerere: Aplicația spune imediat ce nu este în regulă,
  iar limita nu se consumă;
- **blocarea automată a contului nu are loc**: decizia de a restricționa accesul o ia
  un om, și doar în caz de încălcări sistematice (vezi Termenii de utilizare despre
  încetarea accesului);
- după 90 de zile înregistrarea se șterge automat.

Temeiul juridic este interesul nostru legitim pentru siguranța publicului format din
copii și respectarea cerințelor magazinelor de aplicații privind conținutul pentru
copii (art. 6 alin. (1) lit. (f) GDPR).

## 3. Datele copiilor
3.1. Aplicația este folosită în numele copilului de un adult; datele copilului sunt
introduse de adult, care le poate modifica sau șterge. Aplicația este destinată
copiilor sub 14 ani, de aceea consimțământul pentru prelucrarea datelor lor îl dă
părintele sau alt reprezentant legal — adultul care creează profilul copilului
(art. 8 din Legea Republicii Moldova nr. 195/2024). Consimțământul poate fi retras
oricând, ștergând profilul copilului.
3.2. Nu le cerem copiilor să furnizeze singuri date personale. Reclama este afișată
doar adultului (în secțiunea pentru părinți sau după codul PIN / o verificare pentru
adulți) și doar la alegerea lui (vezi secțiunea 2); secțiunea copilului nu conține reclame.
3.3. Introduceți despre copil doar ce este necesar — prenumele este suficient pentru
povești. Vârsta și data nașterii nu le cerem deloc (vezi secțiunea 2).
3.4. În secțiunea copilului nu există reclame, chat-uri încorporate, comentarii și nicio
altă posibilitate pentru copil de a lua legătura cu străini.

## 4. Unde și cum se păstrează datele
4.1. Datele se păstrează în infrastructura cloud a furnizorului nostru de găzduire (o
bază de date administrată și un spațiu de stocare a fișierelor). Accesul este limitat
prin reguli de securitate la nivel de rând: o familie își vede doar propriile date.
4.2. Ilustrațiile și narațiunile se află într-un spațiu de stocare **închis**.
Aplicația ajunge la ele prin linkuri semnate temporare, valabile un timp limitat;
fișierele nu au adrese publice permanente.
4.3. Cheile secrete ale serviciilor terților se păstrează pe server și nu se transmit
niciodată în aplicație.
4.4. **Pe dispozitivul dumneavoastră** aplicația păstrează: datele de autentificare
(în spațiul securizat al sistemului), hash-ul codului PIN, setările, memoria cache a
ilustrațiilor deja afișate și **o copie a datelor familiei pentru lucru fără
internet** — profilurile copiilor, poveștile, bifele deprinderilor și premiile.
Memoria cache a ilustrațiilor are un volum limitat și se curăță automat pe măsură ce
se umple. Copia datelor se șterge la deconectarea din cont. Toate acestea se șterg
complet la dezinstalarea aplicației sau la resetarea datelor din setări.

## 4.1. Transferul datelor în afara Republicii Moldova
Aplicația funcționează pe infrastructura cloud și pe serviciile AI ale unor terți.
Serverele lor se află în **Uniunea Europeană, Statele Unite și alte țări** — ceea ce
înseamnă un **transfer transfrontalier de date**.

Nu numim furnizorii individuali în acest document. Componența serviciilor se schimbă
mai des decât apare o versiune nouă a Aplicației: modelele evoluează, la fel și
condițiile de prelucrare ale furnizorilor, iar o listă scrisă în politică s-ar
învechi mai repede decât am reuși s-o actualizăm — și o listă învechită este mai rea
decât niște categorii descrise cinstit. De aceea dezvăluim **categoriile de
destinatari, datele pe care le primește fiecare și țările în care se află serverele**,
așa cum permite art. 13 alin. (1) lit. (e) GDPR, iar **lista completă și actuală a
furnizorilor, cu linkuri la politicile lor, o oferim la cerere** la
aistoryteller.team@gmail.com — gratuit, în cel mult 30 de zile.

Un avertisment separat despre narațiune: sintezei vocale din cloud îi ajunge
**textul complet al poveștii** — care poate conține numele copilului, dacă povestea
este despre el. Este cel mai mare transfer pe care îl facem, de aceea are loc **doar
la cererea dumneavoastră**: fără apăsarea butonului nimic nu se trimite, iar povestea
poate fi citită sau ascultată cu vocea dispozitivului fără acest transfer.

Ne străduim să reducem la minimum ce se transmite și spunem direct ce pleacă:
**numele copilului este transmis serviciului AI care scrie povestea** — altfel eroul
nu ar putea purta acest nume, iar acesta este rostul aplicației. Împreună cu numele
pleacă textul dorințelor adultului, genul ales și denumirile deprinderilor bifate.

Ce **nu** se transmite serviciilor AI: adresa de e-mail, datele contului, orice
identificator al dispozitivului (hash-ul din secțiunea 2 rămâne la noi și nu este
transmis serviciilor AI), informațiile despre cumpărături. Numele copilului se
transmite fără nume de familie, fără data nașterii și fără date de contact — pe
ultimele două nici nu le avem. Doar după textul cererii nu se poate stabili despre ce
persoană concretă este vorba.

Dacă nu doriți ca numele copilului să părăsească dispozitivul, dezactivați „povestea
personală” la creare: atunci eroul va primi un nume inventat, iar noi nu vom trimite
nimic ce s-ar referi personal la copil.

Transferul se face în baza contractelor cu furnizorii, care includ clauzele
contractuale standard (SCC) sau garanții de protecție echivalente, conform
capitolului V din GDPR și Legii Republicii Moldova nr. 195/2024 „Privind protecția
datelor cu caracter personal”.

## 5. Categoriile de destinatari ai datelor (persoane împuternicite)
Mai jos sunt toate categoriile de persoane împuternicite terțe și ce primește fiecare.
Denumirile concrete ale furnizorilor se oferă la cerere — vezi secțiunea 4.1.

- **Serviciul AI de generare a textului** — textul cererii: dorințele adultului,
  genul ales, denumirile deprinderilor bifate și numele eroului (acesta poate fi
  numele copilului, vezi 4.1). Dacă continuați o poveste — și un rezumat scurt al
  celei anterioare; dacă apăsați „Tradu” — textul complet al poveștii.
- **Serviciul AI de generare a ilustrațiilor** — o descriere textuală a scenei și a
  înfățișării personajelor, compusă de modelul de text. Numele eroului **poate**
  ajunge în această descriere: o scrie modelul, nu noi, și nu putem garanta contrariul.
- **Serviciul de sinteză vocală din cloud** (doar la cererea dumneavoastră) — textul
  complet al poveștii, inclusiv numele eroului. Vezi secțiunea 4.1.
- **Serviciul de sinteză cu vocea părintelui** (doar la cererea dumneavoastră și doar
  dacă funcția este activată) — o mostră a vocii adultului și textul poveștii.
- **Infrastructura cloud: baza de date, autentificarea, stocarea fișierelor** — toate
  datele contului și conținutul creat, așa cum este descris în secțiunea 4.
- **Serviciul de colectare a informațiilor despre erori** — informații tehnice despre
  eroare.
- **Serviciul de livrare a e-mailurilor** — conținutul mesajului și adresa de pe care
  ați scris, când trimiteți o plângere sau o scrisoare către asistență.
- **Serviciul de mesagerie instantanee pentru notificarea administratorului** — o
  notificare internă despre o eroare tehnică sau o plângere. În ea poate ajunge
  **adresa de e-mail a contului dumneavoastră**, identificatorul familiei, denumirea
  abonamentului și identificatorul poveștii: fără ele nu putem înțelege la cine
  anume s-a stricat ceva și nu vă putem acorda povești în compensație.
- **Magazinul de aplicații Google Play (Google LLC)** — primirea plăților și
  distribuirea Aplicației; [politica](https://policies.google.com/privacy). Pe acest
  furnizor îl numim direct: de el depinde însăși posibilitatea de a instala
  Aplicația, nu poate fi înlocuit, iar la cumpărare încheiați oricum un contract cu
  el. Datele de plată Google le primește direct de la dumneavoastră — noi nu le vedem.
- **Rețeaua publicitară Google AdMob (Google LLC)** — doar în abonamentul gratuit și
  doar când adultul a acceptat să vizioneze un clip: datele tehnice ale dispozitivului
  și informațiile despre afișare enumerate în secțiunea 2. Reclama este
  nepersonalizată, iar cererile sunt marcate ca fiind destinate copiilor;
  [cum folosește Google aceste date](https://policies.google.com/technologies/partner-sites).
  Și pe acest furnizor îl numim direct: el primește datele direct de pe dispozitiv,
  nu de la serverul nostru.

**Serviciilor AI** (primele patru categorii) nu le transmitem identificatori direcți
ai persoanei: nici adresa de e-mail, nici datele contului, nici vreun identificator
al dispozitivului nu le primesc de la noi — doar textul cererii. Singura excepție
sunt notificările către administrator, numite direct mai sus: acolo poate ajunge
e-mailul.

Cu fiecare persoană împuternicită este încheiat un contract care include clauzele
contractuale standard (SCC) sau garanții de protecție echivalente, iar fiecare
acționează și conform propriei politici de confidențialitate. Dacă schimbăm un
furnizor în cadrul unei categorii, conținutul acestei secțiuni nu se schimbă; dacă
apare o categorie nouă de destinatari, completăm secțiunea și actualizăm data
intrării în vigoare din partea de sus a documentului.

## 6. Temeiurile juridice
Operatorul se află în Republica Moldova, iar prelucrarea se face în conformitate cu
Legea Republicii Moldova nr. 195/2024 „Privind protecția datelor cu caracter
personal” (în vigoare din 23.08.2026). Pentru utilizatorii din Uniunea Europeană ne
bazăm și pe GDPR.
Temeiurile prelucrării: executarea contractului (oferirea funcțiilor Aplicației),
consimțământul (acolo unde se aplică) și interesele noastre legitime (securitatea,
prevenirea abuzurilor).

## 7. Termenele de păstrare și ștergerea
7.1. Păstrăm datele cât timp există contul dumneavoastră. Puteți șterge profilurile
copiilor, povești individuale și întregul cont din setările Aplicației.
7.2. **Ce se întâmplă la ștergerea contului.** Ștergerea o porniți din setări și se
execută imediat, fără perioadă de așteptare. Se șterg:
- toate înregistrările din baza de date — familia, profilurile copiilor, poveștile,
  deprinderile, realizările;
- toate fișierele din spațiul de stocare — ilustrațiile și narațiunile;
- contul însuși, împreună cu adresa de e-mail.

După aceasta datele nu mai pot fi recuperate prin Aplicație — nici de
dumneavoastră, nici de noi. Copiile de rezervă ale infrastructurii se suprascriu după
ciclul furnizorului (până la 7 zile), după care nu mai rămân nici în ele.

**Ce rămâne după ștergere.** Hash-ul adresei de e-mail și hash-ul identificatorului
dispozitivului, cu contorul poveștilor gratuite folosite (secțiunea 2), nu se șterg:
altfel ștergerea contului ar deveni o cale de a obține din nou setul gratuit. Din
aceste înregistrări nu pot fi recuperate nici e-mailul, nici identificatorul și nu
conțin nici nume, nici povești, nici date despre copii.

7.3. Termenele concrete pentru celelalte date:
- jurnalele antiflood (momentele cererilor) — până la 24 de ore; contorul
  redesenărilor imaginilor familiei — până la 30 de zile;
- textul dorințelor speciale pentru poveste — 90 de zile (vezi secțiunea 2.2), apoi
  se șterge automat;
- jurnalele de generare (ora, abonamentul, reușită/eroare) — până la 12 luni, după
  care sunt anonimizate și rămân doar ca statistică generală;
- hash-urile e-mailului și ale identificatorului dispozitivului cu contorul
  poveștilor gratuite — pe termen nelimitat (vezi 7.2);
- datele despre cumpărături — cât este activ abonamentul și apoi pe durata prevăzută
  de regulile Google Play și de legislația fiscală;
- datele primite de rețeaua publicitară Google AdMob — termenele le stabilește
  Google conform politicii sale; la noi aceste date nu se păstrează.

7.4. Dacă pur și simplu ați încetat să folosiți Aplicația și nu v-ați autentificat
mai mult de 24 de luni, putem șterge contul și datele, după ce vă avertizăm printr-un
e-mail la adresa indicată.

## 8. Drepturile dumneavoastră
8.1. Aveți dreptul: să accesați datele și să obțineți o copie a lor, să corectați
datele inexacte, să le ștergeți, să restricționați prelucrarea sau să vă opuneți ei,
să primiți datele într-un format lizibil de calculator (portabilitate) și să retrageți
consimțământul dat anterior. Retragerea consimțământului nu afectează legalitatea
prelucrării de până la retragere.
8.2. **O copie a datelor o puteți obține direct în aplicație, fără să ne scrieți:**
„Pentru părinți → Setări → Datele mele”. Exportul se creează pe dispozitiv în două
formate — PDF, pentru citit, și JSON, lizibil de calculator, pe care îl puteți
transfera la alt serviciu. Conține profilurile copiilor, toate poveștile cu textele
lor, deprinderile bifate, bifele de îndeplinire, premiile, componența familiei și
datele despre abonament.

Excluse intenționat: hash-ul codului PIN, token-urile de autentificare și cele de
cumpărare — acestea sunt chei de acces, nu informații despre dumneavoastră, iar
transmiterea lor nu este sigură. Fișierele ilustrațiilor și narațiunilor nu se
includ din cauza dimensiunii — ele rămân disponibile în aplicație.

8.3. Pentru celelalte drepturi scrieți la **aistoryteller.team@gmail.com**. Răspundem
în cel mult **30 de zile**. Nu se percepe nicio plată.
8.4. Dacă considerați că v-au fost încălcate drepturile, puteți depune o plângere la
o autoritate de supraveghere:
- în Republica Moldova — Centrul Național pentru Protecția Datelor cu Caracter
  Personal, [datepersonale.md](https://datepersonale.md);
- în România — Autoritatea Națională de Supraveghere a Prelucrării Datelor cu
  Caracter Personal (ANSPDCP), [dataprotection.ro](https://www.dataprotection.ro);
- în alte țări ale Uniunii Europene — autoritatea pentru protecția datelor din țara
  dumneavoastră de reședință.

8.5. **Nu luăm decizii automatizate** care să aibă pentru dumneavoastră efecte
juridice sau alte efecte semnificative și nu facem profilare. Automatizarea din
Aplicație se ocupă doar de compunerea poveștilor și de numărarea limitelor
abonamentului.

## 9. Securitatea
9.1. Aplicăm măsuri rezonabile: criptarea canalului (HTTPS), delimitarea accesului
prin regulile bazei de date, spații închise de stocare a fișierelor cu linkuri
temporare, păstrarea secretelor doar pe server, limitarea frecvenței cererilor.
Securitate absolută nu există, dar ne străduim să reducem riscurile la minimum.
9.2. **Încălcarea securității datelor.** Dacă are loc o încălcare a securității care
poate crea un risc pentru drepturile dumneavoastră, vom notifica autoritatea de
supraveghere în cel mult 72 de ore de când am aflat de ea, iar în cazul unui risc
ridicat vă vom informa și direct, descriind ce s-a întâmplat și ce trebuie făcut.

## 10. Modificarea politicii
Despre modificări vă anunțăm în Aplicație și actualizăm data intrării în vigoare.

## 11. Contacte
Întrebări despre confidențialitate: aistoryteller.team@gmail.com.
