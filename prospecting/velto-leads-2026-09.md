# Velto WebDesign — lokalne landing page per placówka. Wersja 3: PO WERYFIKACJI

**Data: 21.09.2026.** Wersja 3 zastępuje ranking z wersji 1–2. Każda pozycja TOP przeszła realną weryfikację w internecie, a nie ocenę „na oko". Efekt jest taki: **weryfikacja wywaliła większość pierwszego TOP-u** — duże, dojrzałe sieci franczyzowe prawie zawsze mają już strony per lokalizacja (podstrony, subdomeny albo własne domeny franczyzobiorców). To najważniejszy wniosek tego dokumentu.

Pełny log dowodów: `prospecting/weryfikacja-2026-09.md`.

---

## 0. Filtr i metoda (po korektach)

**Bramka A — lokalna intencja zakupowa.** Czy klient końcowy wpisuje „usługa + miasto/dzielnica" i kupuje w konkretnym punkcie? Masaż, depilacja, beauty, fryzjer/barber, EMS, dentysta, fizjoterapia, weterynarz, szkoły dla dzieci, warsztat, biuro nieruchomości → TAK. Restauracja w galerii handlowej, zarządca wspólnot, deweloper, dealer, agencja → NIE / słabo.

**Bramka B — luka lokalna (rozstrzygająca).** Sprawdzam, czy lokalizacje mają własne, indeksowalne strony. Jeśli tak → **ODRZUCONE (zasada −5)**, zgodnie z Twoją korektą o Da Grasso.

### Test „3 lokalizacji" — jak sprawdzam każdą sieć (10 minut)
1. Szukam w strukturze strony: `/oddzial/`, `/salony/`, `/gabinety/`, `/szkola/`, `/studia/`, `/baseny/`.
2. Sprawdzam, czy istnieją subdomeny per lokalizacja (np. `rzeszow-instytut.yasumi.pl`, `amakidslodz.pl`).
3. Sprawdzam, czy lista lokalizacji to tylko osadzona mapa (Google My Maps) albo wpisy w Booksy/Fresha/belliata.
4. Wpisuję w Google „marka + miasto" i patrzę, czy pojawia się strona salonu, czy wyłącznie katalogi zewnętrzne.

### Progi
A+ = 10+, A = 7–9, B = 4–6. **Zasada ostrożności przyjęta po weryfikacji:** A+ dostają wyłącznie firmy z **potwierdzoną** luką lokalną; przy niepełnej weryfikacji maksimum to A. Brak danych = „brak danych", zero zgadywanych e-maili.

---

## 1. Wynik weryfikacji — co się stało z poprzednim TOP 20

| Poprzednia pozycja | Firma | Wynik weryfikacji | Dowód |
|---|---|---|---|
| 1 | DepilConcept (122 salony) | ❌ **ODRZUCONY** | każdy salon ma podstronę z lokalnym SEO: `depilconcept.pl/oddzial/depilconcept-gdynia/` („depilacja w Gdyni", adres, telefon salonu, formularz) |
| 5 | Yasumi (148) | ❌ **ODRZUCONY** | subdomeny per salon: `rzeszow-instytut.yasumi.pl` (kontakt, o nas, rezerwacja, zespół) |
| 4 | Depilacja.pl (62) | ❌ **ODRZUCONY** | struktura `depilacja.pl/salony/<usługa>/<miasto>/`, np. „Endermologia Kraków Centrum" |
| 10 | Moose (107) | ❌ **ODRZUCONY** | podstrony per oddział: `moose.pl/oddzial/oddzial-w-katowicach/` |
| 7 | Early Stage (850) | ❌ **ODRZUCONY** | podstrony per szkoła: `earlystage.pl/szkola/bialoleka-1`, subdomeny (`universe.earlystage.pl`) |
| 8 | Helen Doron (220) | ❌ **ODRZUCONY** | podstrony per miasto/oddział: `helendoron.pl/nauka-angielskiego-krakow/` |
| 9 | AMAKids (387/225) | ⚠️ **B** | część oddziałów ma własne domeny (`amakidslodz.pl`, `amakidskatowice.pl`); liczby niespójne (387 vs 225) |
| 2 | Orient Massage (32) | ⚠️ **B** | Szczecin ma własną domenę (`orientmassage-szczecin.pl`), Kielce tylko Booksy |
| 3 | mobileEnglish (75) | ⚠️ **dane nieaktualne** | `mobileenglish.pl` to dziś blog językowy, nie strona sieci szkół |
| 11 | Trendy Hair (~70) | ✅ **LUKA POTWIERDZONA** | lista salonów to wyłącznie osadzona Google My Maps; dla Poznania/Lublina w Google tylko katalogi zewnętrzne |
| 6 | Dentity (122 gab.) | ✅ **luka zawężona** | marki regionalne mają strony; bez podstron per miasto jest ~6 marek / ~12 centrów (Dentica, Estetique, Dental Medicenter, Uśmiechnij Mi Się, Dentiti) |
| 12 | Tax Care (~380 biur) | 🔶 dane z 2019 (6 własnych + 30 fran. + 350 partnerskich) | brak potwierdzenia stron per biuro |
| 13 | Freedom (100+ oddz.) | 🔶 skala potwierdzona (100–120 oddziałów, 600 agentów) | brak potwierdzenia stron per oddział |
| 14 | LuxVet (8 → cel 150–200) | 🔶 przejmowane lecznice zachowują własne marki i strony; grupa daje wsparcie marketingu | `vetkompleksowo.pl` 09.2023 |
| 16 | Edina Vetcare (→200) | 🔶 jak LuxVet; każda lecznica ma własną domenę (np. `lecznica-brynow.pl`) | newseria, lecznica-brynow.pl |
| 17 | In.Time (17 studiów) | ✅ **luka częściowa** | są strony per miasto (`intime.pl/trening-ems-wroclaw/`), brak per studio/dzielnica (Wrocław ma 4 studia na jednej stronie) |
| 18 | Haircut Express | ✅ **dane skorygowane** | w PL tylko 20–25 salonów (nie 30+); właścicielka Iryna Pohodina; strony per salon niepotwierdzone |
| 19 | Hasten (14 lokalizacji) | ❌ **ODRZUCONY** | podstrony per basen: `hasten.pl/baseny/...-legionowo-piaskowa/` |
| 20 | Gentlemen Barber (19) | ✅ **LUKA POTWIERDZONA** | są tylko strony per województwo (`/nasze-salony/slaskie/`), a katalog franczyzy pokazuje 40+ lokalizacji |
| — | Perfect Look (86) | ❌ **ODRZUCONY** | podstrony per salon: `perfectlook.clinic/gabinety/plc-wielun/` |
| — | British School (27–40) | ❌ **ODRZUCONY** | podstrony per oddział: `britishschool.pl/warszawa-targowice/...` |
| — | KIDS&Co (35) | ❌ **ODRZUCONY** | podstrony per placówka: `kids-co.pl/kindergarten/wroclaw/nokia/` |
| — | Galeria Uśmiechu / Uśmiechnij Mi Się | ❌ **ODRZUCONY** | podstrony per miasto: `/gliwice/`, `/nowy-sacz/` |

**Bilans:** 11 firm wypadło całkowicie, 3 mocno straciły na ocenie, a ocalało 4 z potwierdzoną luką i 12 wymagających jeszcze dokończenia weryfikacji.

---

## 2. TOP 20 po weryfikacji

Kolumna „Status" ma teraz kluczowe znaczenie: **✅ luka potwierdzona** (można dzwonić), **🔶 do dokończenia** (jedna rzecz do sprawdzenia — opisana w kolumnie „Co jeszcze sprawdzić").

| # | Firma | Model | Skala | Strony lokalne — co ustaliłem | Kontakt / decydent | Score | Co jeszcze sprawdzić |
|---|---|---|---|---|---|---|---|
| 1 | **Trendy Hair Fashion** | franczyza — fryzjerstwo | ~70 salonów (60+ franczyzowych), PL + CZ + SK | ✅ **LUKA POTWIERDZONA**: katalog salonów = wyłącznie mapa Google My Maps; brak stron salonów w Google (tylko katalogi zewnętrzne) | trendyhair@trendyhair.pl, tel. (33) 816 42 22; decydent: brak danych | **11 → A+** | czy istnieją subdomeny per salon (sprawdzić 3 salony); czy część salonów nie działa niezależnie pod szyldem (np. Lublin = PRYMAT S.C.) |
| 2 | **Gentlemen Barber Shop** | franczyza — barber | 40+ lokalizacji wg katalogu franczyzy (8 własnych + 20 franczyzowych w 2023, wciąż otwierają) | ✅ **LUKA POTWIERDZONA**: istnieją tylko zbiorcze strony per województwo, brak stron per salon | franczyza@gentlemenbarber.pl, tel. 790 371 100; decydent: brak danych | **11 → A+** | czy salony mają wizytówki/Booksy (tak = luka tylko w „landing + rezerwacja") |
| 3 | **Dentity** | konsolidacja sieci regionalnych stomatologii | 25 centrów / 122 gabinety, 19 miast | ✅ **LUKA ZAWĘŻONA, POTWIERDZONA**: ~6 marek bez podstron per miasto (Dentica 3 miasta, Estetique 3, Dental Medicenter 2, Uśmiechnij Mi Się 2, Dentiti) | **Grzegorz Struzik — CEO**; formularz na dentity.pl | **11 → A+** | które dokładnie marki nie mają podstron (przejść 25 centrów — lista gotowa w logu) |
| 4 | **Studio Synergy** | franczyza — studia EMS | 12–14 studiów (4 własne w Krakowie), miasta 20–200 tys. | ✅ **LUKA PRAWDOPODOBNA, POTWIERDZONA CZĘŚCIOWO**: „Nasze studia" = lista z kontaktami; strony per miasto istnieją tylko dla kandydatów franczyzowych | franczyza@studiosynergy.pl, tel. 514 514 179; **Bartłomiej Stanek** (cytat, 06.2026) | **10 → A+** | czy studia mają osobne strony dla klientów (sprawdzić Kraków Centrum i Płock) |
| 5 | **Samui Spa** | franczyza — masaż balijski/tajski | 12 lokalizacji (10 własnych + 2 franczyzowe), własna szkoła masażu | ✅ **luka prawdopodobna**: `samui-spa.pl/salony/` = lista adresowa, brak śladu stron per salon; w serwisach zewnętrznych tylko wizytówki Fresha | formularz franczyzowy; decydent: brak danych | **9 → A** | czy salony mają osobne strony/Booksy (3 salony) |
| 6 | **In.Time EMS Studios** | franczyza — studia EMS | 17 studiów (7 własnych + 10 franczyzowych) | ✅ **luka częściowa potwierdzona**: strony per miasto istnieją, ale brak stron per studio — Wrocław ma 4 studia opisane na jednej stronie, Warszawa 2 | **franczyza@intime.pl, 780 560 537; Kacper Orłowski** | **9 → A** | czy właściciele studiów mają własne strony (3 studia) |
| 7 | **Freedom Nieruchomości** | franczyza — biura nieruchomości | 100–120 oddziałów, 600 agentów, 5000 transakcji rocznie | 🔶 skala potwierdzona, **stron oddziałów nie potwierdzono** — w nieruchomościach franczyzobiorcy często mają własne strony | franczyza.freedom.pl (formularz); **Agnieszka Dąbrowska** (dane 2018, potwierdzić) | **9 → A** | czy oddziały mają własne strony (3 oddziały) i jak wygląda „biuro nieruchomości + miasto" w Google |
| 8 | **Haircut Express** | franczyza — fryzjerstwo | **20–25 salonów w PL** (nie 30+), 150 w 5 krajach, 120 franczyzowych | 🔶 brak potwierdzenia stron per salon; sieć ma własne oprogramowanie i aplikację mobilną | franczyza@haircutexpress.pl, tel. 886 388 206; **Iryna Pohodina — właścicielka** | **9 → A** | czy salony w PL mają strony (salony są głównie własne → decyzja centralna) |
| 9 | **SPW Szkoła Pamięci** | franczyza — kursy dla dzieci | ~100 oddziałów | 🔶 oddziały mają **własne, tanie strony** (np. `szkola-pamieci-spw.localo.site`) — luka jakościowa, nie brak obecności | **praca@spw.pl, 731 059 182; Ewa Mak — menedżer sieci SPW**; współwłaściciel Tomasz Wachowiak | **9 → A** | ile oddziałów ma własne strony i czy centrala chce je ustandaryzować |
| 10 | **Tax Care** | franczyza + partnerstwo — biura rachunkowe | dane 2019: 6 własnych + 30 franczyzowych + **350 partnerskich** (dane 2016 mówiły o 53 własnych + 270 partnerskich) | 🔶 brak potwierdzenia stron per biuro (biura to niezależne podmioty w programie partnerskim) | formularz; **Adam Głos — prezes** (dane 2016, potwierdzić) | **9 → A** | aktualna liczba biur (2026) i czy partnerskie mają własne strony |
| 11 | **Football Academy** | franczyza — szkółki piłkarskie | 150+ szkółek (2019), dziś ponad 100 w nawigacji strony | 🔶 centralna lista miast; **nie potwierdzono stron per szkółka** | **Krzysztof Łoś — dyrektor ds. rozwoju sieci** (dane 2019) | **9 → A** | czy miasta w nawigacji to linki do stron szkółek (jeśli tak → odrzucić) |
| 12 | **LuxVet** | konsolidacja — weterynaria | 8 przychodni (2023) → cel 150–200, budżet 100–150 mln € | 🔶 przejmowane lecznice zachowują marki i strony; grupa daje administrację, księgowość i marketing, ale nie ma jednolitego standardu stron | brak publicznego e-maila; prezes cytowany w prasie (**Marcin Halicki** — potwierdzić) | **9 → A** | czy lecznice mają własne strony (sprawdzić 5 z listy grupy) |
| 13 | **ProfiAuto Serwis** | kanał — sieć warsztatów | 3500 warsztatów (+16% r/r) | 🔶 warsztaty to niezależne firmy — sieć nie prowadzi za nich stron; sprzedaż szyta pod model kanałowy („strony dla członków sieci") | brak publicznego e-maila; decydent: brak danych | **9 → A** | czy centrale sieci warsztatów mają program marketingu dla członków |
| 14 | **Q Service / Compet / S-Plus** | kanał — sieci warsztatów | ~600 / 518 / 700+ warsztatów | 🔶 jak ProfiAuto | brak danych | **8 → A** | jak wyżej |
| 15 | **Mała Lingua** | franczyza — szkoły językowe | 40+ partnerów w ~152–200 punktach | 🔶 punkty często działają w przedszkolach/szkołach — sprawdzić, które mają publiczne adresy i strony | brak danych | **8 → A** | czy partnerzy mają własne strony (3 punkty) |
| 16 | **Edina Vetcare Group** | konsolidacja — weterynaria | kilkanaście lecznic → cel 200+ (TDJ Equity) | 🔶 każda lecznica ma własną domenę (np. `lecznica-brynow.pl`), brak jednolitych stron lokalnych | **Aleksandra Gutkowska — prezes/pomysłodawczyni** | **8 → A** | czy nowe lecznice wchodzą bez stron (to byłby wolumen) |
| 17 | **SOCATOTS Polska** | franczyza — zajęcia sportowe dla dzieci | ~70 oddziałów (wcześniejsze dane) | 🔶 struktura do sprawdzenia; na stronie głównie lista miast dostępnych pod franczyzę | PLCFDS Polska (Socatots Polska) sp., Szczecin, tel. 91 350 9566, franczyza@brazylijskieszkolki.pl | **7 → A** | czy oddziały mają własne strony (3 oddziały) |
| 18 | **Fizjoacademy** | franczyza/mentoring — fizjoterapia | 4 gabinety własne (Ruda Śląska, Katowice ×3) + 1 franczyza (Pruszków, od 03.2026) + 100+ placówek w programie mentoringowym | 🔶 franczyzobiorcy prowadzą gabinety **pod własnymi markami** → brak jednolitego systemu stron | biuro@fizjoacademy.pl, tel. 536 071 754 | **7 → A** | czy gabinety w programie Masterwey mają własne strony (sprawdzić 3) |
| 19 | **Orient Massage + Thai Organic** | franczyza — masaż (dwie marki) | 32 salony (18 + 12 + po 2 własne), cel 50–60 | ⚠️ część salonów ma własne domeny (Szczecin), część tylko Booksy → **potrzeba niepewna** | **Martyna Buchalska — właścicielka/rozwój sieci** | **6 → B** | policzyć, ile z 32 salonów ma własną stronę (jeśli mniejszość → wróci wyżej) |
| 20 | **AMAKids** | franczyza — edukacja dzieci | 387 oddziałów (dane własne) vs 225 lokalizacji (dane oddziału Łódź) | ⚠️ część oddziałów ma własne domeny (`amakidslodz.pl`, `amakidskatowice.pl`) | brak danych | **6 → B** | ustalić realną liczbę i udział oddziałów z własnymi stronami |

---

## 3. TOP 4 — kto realnie zasługuje na telefon dzisiaj

1. **Trendy Hair Fashion** — jedyna duża sieć fryzjerska, gdzie przez stronę centralną widać wyłącznie mapę Google My Maps, a w wyszukiwarce dla konkretnych miast pojawiają się tylko katalogi zewnętrzne. 70 salonów × fraza „fryzjer + miasto/dzielnica" to gotowy wolumen, a marka działa od 1988 roku i prowadzi akademię — czyli ma marketing, ale nie ma stron lokalnych. Kąt: landing per salon z cennikiem i rezerwacją, wdrożenie paczkami po 10.
2. **Gentlemen Barber Shop** — sieć z 40+ lokalizacjami, która rozwiązanie „po taniości" zrobiła tylko połowicznie: ma zbiorcze strony wojewódzkie, ale nie ma stron salonów. To najlepszy typ klienta, bo problem jest już przez niego nazwany („strony per region"), tylko niedokończony. Kąt: strona salonu + rezerwacja + mapowanie usług barber (broda, strzyżenie, combo).
3. **Dentity** — 25 centrów stomatologicznych, z których ~6 marek (ok. 12 centrów) nie ma podstron per miasto, a grupa świadomie odrzuca centralizację, więc każda marka robi to po swojemu. Nie sprzedajemy „stron", a „standard widoczności lokalnej w 19 miastach". Decydent jest znany z nazwiska (CEO Grzegorz Struzik). Kąt: szablon landingów per centrum + spójny LocalBusiness, wdrożenie etapami.
4. **Studio Synergy** — 12–14 studiów EMS w 12 miastach, w tym w mniejszych miejscowościach, gdzie konkurencja w Google jest słaba. Strony per miasto już mają, ale służą rekrutacji franczyzobiorców, nie klientom — a to zupełnie inna intencja i inna treść. Kąt: przestawienie tych stron na klienta + osobne landingi dla studiów (Kraków Centrum, Płock, Poznań).

**Uwaga uczciwościowa:** w poprzednich wersjach na szczycie były DepilConcept, Yasumi, Depilacja.pl i Moose — po weryfikacji **wszystkie cztery odpadły**, bo mają podstrony/subdomeny per lokalizacja z lokalnym SEO. Nie wpisuję ich z powrotem.

---

## 4. Backup — 30 leadów (tu zmiana struktury po weryfikacji)

Po weryfikacji nie ma 30 kolejnych sieci usługowych z **potwierdzoną** luką — dlatego miejsca 21–50 zajmują firmy z innych modeli (B2B i kanał partnerski), które zostawiam świadomie, ale **nie mieszam ich z TOP**. Każda ma w pliku CSV znacznik `POZA PROFILEM LOKALNYCH USLUG`.

| # | Firma / grupa | Typ | Skala | Dlaczego nie w TOP | Co z tym zrobić |
|---|---|---|---|---|---|
| 21–31 | Novisa, Trust Investment, EKOPARK, Home Invest, BUD-RIM, JDM, Invest Komfort, Victoria Dom, Tree Development, Grupa Moderator, Budlex | poza profilem — deweloperzy | 7–36 inwestycji każdy | brak lokalnej intencji „usługa + miasto" | osobny produkt: landing per inwestycja |
| 32–42 | Grupa Biurowiec (4473 nieruchomości), Status (500+ wspólnot), Nawigator (250), Avente (140), Ga-Mi II (160+), ZNDOM (140+), Sekro (#1 rankingu), nKrak (top 3), JMK (top 5), Parvis/Egendom, ADMIN | poza profilem — zarządcy | 140–4473 obiektów | klient nie szuka zarządcy lokalnie — wygrywa przetarg | wrócić, jeśli Velto wejdzie w strony per osiedle/wspólnota (B2B) |
| 43–46 | Grupa Cichy-Zasada, Grupa Plichta, Grupa Bemo, Grupa PTH / Auto Spektrum / Lellek | poza profilem — dealerzy | 14–32 salony, 7–11 marek | szablony OEM + wewnętrzny marketing | ewentualnie kanał: landingi per salon usługowy („serwis + miasto") |
| 47–50 | PROFIT system, ARSS, Semgence (white-label SEO), SEOGods / Sunrise System / Funkymedia / iCEA | kanał partnerski | 20+ agencji partnerskich (Semgence), 200–300+ konceptów (ARSS/PROFIT) | to nie sieci lokalizacji, a dostawcy/wykonawcy marketingu | rozmowa o podwykonawstwie: Velto jako zaplecze webdev pod ich klientów lokalnych |

---

## 5. ODRZUCONE — z dowodem (19)

| Firma | Powód odrzucenia (dowód) |
|---|---|
| **DepilConcept** (122 salony) | ❌ każdy salon ma podstronę z lokalnym SEO na domenie sieci (`/oddzial/depilconcept-gdynia/`) — centrala już realizuje to, co sprzedaje Velto |
| **Yasumi** (148) | ❌ subdomeny per salon z pełną stroną (`rzeszow-instytut.yasumi.pl`) |
| **Depilacja.pl** (~62) | ❌ podstrony per salon i usługa (`/salony/endermologia/krakow-srodmiescie/`) |
| **Moose** (~107) | ❌ podstrony per oddział z treścią lokalną (`/oddzial/oddzial-w-katowicach/`) |
| **Early Stage** (850+) | ❌ podstrony per szkoła (`/szkola/bialoleka-1`) + subdomeny |
| **Helen Doron** (220+) | ❌ podstrony per miasto i oddział (`/nauka-angielskiego-krakow/`) |
| **British School** (27–40) | ❌ podstrony per oddział (`/warszawa-targowice/...`) |
| **Perfect Look Clinic** (~70–86) | ❌ podstrony per salon (`/gabinety/plc-wielun/`) |
| **Hasten** (14 lokalizacji) | ❌ podstrony per basen (`/baseny/...-legionowo-piaskowa/`) |
| **KIDS&Co** (35) | ❌ podstrony per placówka (`/kindergarten/wroclaw/nokia/`) |
| **Galeria Uśmiechu / Uśmiechnij Mi Się** | ❌ podstrony per miasto (`/gliwice/`, `/nowy-sacz/`) |
| **Kodano Optyk** (130+) | ❌ centralne strony per salon + własny e-commerce i dział IT |
| **Da Grasso** (~190) | ❌ centralny kanał transakcji — jedna strona obsługuje wszystkie lokalizacje i zamówienia |
| **Biesiadowo** (119) | ❌ franczyzobiorca dostaje integrację z aplikacją zamówień (biesiadowo.pl, zjemy.co), a restauracje mają centralne podstrony per lokal |
| **Studio Figura** (420 gabinetów) | ❌ istnieją subdomeny per gabinet (`zielonagora.studio-figura.pl`) |
| **GO4Robot** | ❌ centralne podstrony miast + panel rodzica |
| **Olimp** (~90, dane 2020) | ❌ lokalizacje wyłącznie w galeriach handlowych — ruch z galerii, brak lokalnej intencji wyszukiwania (Bramka A) |
| **Delante** | konkurent — sam sprzedaje „separate pages for each location" |
| **mobileEnglish** | ⚠️ dane nieaktualne: domena `mobileenglish.pl` to dziś blog językowy, sieć szkół niepotwierdzona — wrócić wyłącznie po potwierdzeniu, że sieć istnieje |

---

## 6. TRZY SEGMENTY — przepisane po weryfikacji

Wniosek z weryfikacji: **dojrzałe sieci (100+ lokalizacji, franczyza od 10+ lat) prawie zawsze mają już strony lokalne.** Realne luki są tam, gdzie sieć jest **młoda (5–15 lat franczyzy), ma 10–70 punktów i franczyzobiorców-właścicieli**, a centrala nie wdrożyła systemu stron.

### SEGMENT 1 — Sieci usług osobistych z centralą „bez stron" (fryzjer, barber, masaż, beauty)
**Dowody z tej weryfikacji:** Trendy Hair (~70 salonów, tylko mapa), Gentlemen Barber (tylko strony wojewódzkie), Samui Spa (lista adresowa), Studio Synergy (strony miast robione pod franczyzobiorców).
**Problem klienta:** marka ogólnopolska, ale w wynikach lokalnych pusto — klient z „fryzjer Pszczyna" nie widzi salonu, a rezerwacje przejmuje Booksy i pojedyncze salony.
**Co sprzedajemy:** jeden szablon → N landingów (miasto w URL/H1, adres, cennik, zespół, rezerwacja), domena lub subdomena, wdrożenia paczkami po 10, 199–299 zł/mies. opieki, opcja white-label dla franczyzodawcy.
**Decydent:** właściciel/franczyzodawca, dyrektor ds. rozwoju sieci, franczyza@… (kontakt imienny najlepiej z LinkedIn).
**Zapytania Google (przykłady):** „fryzjer Pszczyna", „barber Rzeszów centrum", „masaż tajski Wrocław Krzyki", „depilacja laserowa Ełk".
**Zapytania LinkedIn:** `"dyrektor ds. rozwoju sieci" fryzjer OR barber`, `"franchise manager" beauty Poland`, `"właściciel" sieć salonów masażu`.

**Cold e-mail (wzór pod Trendy Hair):**
> Temat: 70 salonów Trendy Hair — w Google widać tylko mapę
> Dzień dobry,
> sprawdziłem, jak wygląda „fryzjer Poznań" i „fryzjer Kielce" — nie ma tam salonu Trendy Hair, są tylko katalogi typu targeo i oferteo. Państwa lista salonów na stronie to osadzona mapa, której Google nie traktuje jak stron lokalnych.
> Robię dokładnie to, czego tu brakuje: jeden szablon → osobna strona każdego salonu (miasto w adresie i tytule, cennik, zespół, rezerwacja), gotowa do wdrożenia paczkami po 10 salonów. 999–2000 zł za lokalizację, 199–299 zł/mies. za hosting i aktualizacje.
> Czy mogę pokazać wersję demo dla dwóch salonów — np. Bielska-Białej i Poznania?
> [podpis]

### SEGMENT 2 — Konsolidatorzy usług medycznych i weterynaryjnych (Dentity, LuxVet, Edina, Fizjoacademy)
**Dowody:** Dentity — ~6 marek bez podstron per miasto; LuxVet i Edina — każda przejęta lecznica zachowuje własną markę i stronę, brak wspólnego standardu.
**Problem klienta:** grupa rośnie przez akwizycje, więc „dziedziczy" kilkadziesiąt stron o różnej jakości, a nowe placówki startują bez stron lokalnych. Pacjent szuka „dentysta Jaworzno" i trafia do konkurencji.
**Co sprzedajemy:** standaryzacja (szablon + LocalBusiness + mapowanie usług), migracja starych stron, wdrożenia dla nowych placówek w modelu „cena za lokalizację w ramach umowy ramowej".
**Decydent:** CEO/COO grupy, dyrektor operacyjny, dział marketingu centrali; przy markach regionalnych — właściciel centrum.
**Zapytania Google:** „dentysta Jaworzno", „implanty Nowy Sącz", „weterynarz Czechowice-Dziedzice", „fizjoterapeuta Pruszków".
**Zapytania LinkedIn:** `"CEO" grupa stomatologiczna`, `"dyrektor operacyjny" klinika weterynaryjna`, `"head of marketing" veterinary group`.

**Cold e-mail (wzór pod Dentity):**
> Temat: 12 centrów Dentity bez stron pod „dentysta + miasto"
> Dzień dobry,
> przy 25 centrach część marek — Dentica, Estetique, Dental Medicenter, Uśmiechnij Mi Się — nie ma osobnych stron dla swoich miast. Pacjent z Jaworzna czy Polanicy nie ma szans trafić na te centra w Google, mimo że centra działają od lat.
> Proponuję szablon landingów per centrum z panelem dla placówki i spójnym LocalBusiness, wdrożony etapami (najpierw jedna marka, potem reszta). 999–2000 zł za stronę, 199–299 zł/mies. utrzymania.
> Z kim najlepiej o tym porozmawiać — Pan Grzegorz Struzik czy osoba z marketingu grupy?
> [podpis]

### SEGMENT 3 — Sieci z franczyzobiorcami bez wsparcia marketingowego (edukacja, kursy, warsztaty, biura)
**Dowody:** SPW (~100 oddziałów, franczyzobiorcy robią sobie strony na darmowych kreatorach typu `localo.site`), Tax Care (~380 biur partnerskich, niezależne podmioty), Mała Lingua (~152–200 punktów), Football Academy (150+ szkółek), sieci warsztatów (3500 + 600 + 700).
**Problem klienta:** centrale nie mają produktu „strona lokalna", więc każdy partner kombinuje sam — albo nie ma nic. Efekt: niejednolita jakość, brak standardu, marka traci lokalnie na rzecz lokalnych konkurentów.
**Co sprzedajemy:** pakiet dla sieci — szablon + szkolenie partnera + wdrożenia w modelu abonamentowym; dla sieci warsztatów: „strony dla członków sieci" jako benefit członkowski.
**Decydent:** menedżer sieci (SPW: Ewa Mak), dział rozwoju (Football Academy: Krzysztof Łoś), marketing centrali.
**Zapytania Google:** „kurs szybkiego czytania Lublin", „biuro rachunkowe Radom", „angielski dla dzieci Legionowo", „wymiana oleju Płock".
**Zapytania LinkedIn:** `"menedżer sieci" edukacja`, `"dyrektor rozwoju" partnerzy`, `"network manager" warsztaty`.

**Cold e-mail (wzór pod SPW):**
> Temat: 100 oddziałów SPW — każdy robi stronę na własną rękę
> Dzień dobry,
> część oddziałów SPW ma strony na darmowych kreatorach (np. Lublin/Świdnik na localo.site), część nie ma żadnej. To odwraca uwagę franczyzobiorców od sprzedaży kursów i rozjeżdża markę w Google.
> Mogę dostarczyć sieci prosty standard: jeden szablon → strona każdego oddziału z zapisami, plus panel, w którym partner sam zmienia dane i terminy. 999–2000 zł za oddział, 199–299 zł/mies. utrzymania, wdrożenie w paczkach.
> Czy rozmowa o tym powinna iść przez Panią (menedżer sieci) czy przez centralę w Bydgoszczy?
> [podpis]

---

## 7. Czego jeszcze nie wiem (dokończenie weryfikacji)

| Priorytet | Do sprawdzenia | Jak |
|---|---|---|
| 🔴 krytyczne dla TOP | Trendy Hair: subdomeny per salon (3 salony) i czy części salonów nie prowadzą inne podmioty | Google „trendyhair" + miasto, wizytówki, księgi wieczyste nie — wystarczy strona i LinkedIn salonu |
| 🔴 | Gentlemen Barber: czy salony mają już strony/Booksy (3 salony) | Google „barber + miasto", Booksy |
| 🔴 | Dentity: które z 25 centrów nie mają podstron per miasto (lista marek w logu — do przejścia) | dentity.pl/nasze-centra + wejścia na marki |
| 🟠 | Studio Synergy, Samui Spa, In.Time, SOCATOTS, Mała Lingua, Fizjoacademy, Orient Massage, AMAKids: obecność stron per lokalizacja (3 lokalizacje na firmę) | wg Testu „3 lokalizacji" (rozdz. 0) |
| 🟠 | Football Academy: czy miasta w nawigacji to osobne strony szkółek | kliknąć 3 miasta |
| 🟡 | Dane: Tax Care (ostatnie znane 2019), SPW (2016 → potwierdzić 2026), Freedom (potwierdzone 100+ oddziałów 2025/26), Haircut Express (20–25 w PL), Football Academy (150+) | prasa branżowa, LinkedIn, strony firm |
| 🟡 | Decydenci: Trendy Hair, Gentlemen Barber, Samui Spa, Mała Lingua, SOCATOTS, Fizjoacademy, AMAKids, Tax Care (aktualność Adama Głosa), Freedom (aktualność Agnieszki Dąbrowskiej), LuxVet (stanowisko Marcina Halickiego) | LinkedIn + KRS + franczyza@ — bez zgadywania |

**Metoda dla Ciebie, gdy chcesz sprawdzić leada w 5 minut:** wpisz w Google `site:domena.pl oddzial` / `salony` / `gabinety` / `szkola` i zobacz, czy w wynikach są podstrony z nazwami miast; następnie wyszukaj „marka + miasto" i sprawdź, czy wynikiem jest strona marki, czy katalog zewnętrzny (targeo, belliata, oferteo, Booksy). Jeśli wynikiem jest strona marki → **lead do kosza**.

---

## 8. Rekomendacja: następna fala prospectingu (gdzie szukać)

Po weryfikacji widzę jasny wzorzec — kolejną falę warto zrobić **w sieciach młodszych i mniejszych**, bo tam luka najczęściej jeszcze istnieje:
1. **Franczyzy beauty/barber/masaż z 10–70 punktami, franczyza uruchomiona po 2015 r.** (młode sieci nie mają jeszcze systemu stron).
2. **Konsolidatorzy medyczni w trakcie akwizycji** (stomatologia, weterynaria, fizjoterapia, optyka) — każdy nowy przejęty podmiot = brak spójnej strony lokalnej.
3. **Sieci edukacyjne dla dzieci drugiego szeregu** (tańsze franczyzy, 20–100 punktów) — pierwsza liga ma już podstrony (Early Stage, Helen Doron, Moose).
4. **Sieci warsztatowe i usługowe kanałowe** (ProfiAuto, Q Service, Compet, S-Plus, a także sieci serwisów AGD/IT) — sprzedaż przez centralę, wdrożenia dla członków.
**Czego unikać w kolejnej fali:** sieci z franczyzą dłuższą niż ~12 lat i 100+ punktami (prawie zawsze mają już rozwiązanie), gastronomia z centralnym zamówieniem, deweloperzy i zarządcy wspólnot.

---

## 9. Podsumowanie liczbowe i źródła

| Pozycja | Liczba |
|---|---|
| Leadów w CSV (TOP 20 + backup 30) | **50** |
| Odrzuconych z dowodem | **19** |
| Leadów z potwierdzoną luką (✅) | **4** (Trendy Hair, Gentlemen Barber, Dentity, Studio Synergy) |
| Leadów wymagających dokończenia weryfikacji (🔶) | **14** |
| Firm ocenionych łącznie (w tym odrzucone po weryfikacji) | **~90** |
| Firm, którym weryfikacja obniżyła ocenę lub odebrała miejsce w TOP | **14** |
| Decydenci znani z nazwiska | **8** (Struzik, Stanek, Orłowski, Pohodina, Mak, Gutkowska, Buchalska, + Wachowiak; 3 dane wymagają odświeżenia) |

**Najważniejsze wnioski:**
1. Weryfikacja jest ważniejsza niż scoring: cztery firmy z czołówki (DepilConcept, Yasumi, Depilacja.pl, Moose) miały podstrony/subdomeny per lokalizacja — bez sprawdzenia sprzedałoby się im coś, co już mają.
2. Najczęstszy wzorzec „mają" to podstrony na domenie sieci (`/oddzial/`, `/salony/`, `/szkola/`, `/gabinety/`, `/baseny/`) oraz subdomeny per salon.
3. Realne luki są w sieciach, które zatrzymały się na poziomie **mapy albo strony zbiorczej** (Trendy Hair — mapa; Gentlemen Barber — województwa; Studio Synergy — strony dla franczyzobiorców).
4. Zapytania lokalne warto odróżnić od „franczyzowych": strona `twoja-franczyza-ems-opole` nie sprzedaje masażu klientowi — i to jest właśnie miejsce na Velto.

**Źródła kluczowe (weryfikacja):** depilconcept.pl/oddzial/depilconcept-gdynia/ · rzeszow-instytut.yasumi.pl · depilacja.pl/salony/endermologia/krakow-srodmiescie/ · moose.pl/oddzial/oddzial-w-katowicach/ · earlystage.pl/szkola/bialoleka-1 · helendoron.pl/nauka-angielskiego-krakow/ · britishschool.pl/warszawa-wola-centrum · perfectlook.clinic/gabinety/plc-wielun/ · hasten.pl/baseny/... · kids-co.pl/kindergarten/wroclaw/nokia/ · dentity.pl/nasze-centra/ · trendyhair.pl/salony/ · gentlemenbarber.pl/nasze-salony/slaskie/ · samui-spa.pl/salony/ · studiosynergy.pl/franczyza/ · intime.pl/trening-ems-wroclaw/ · franczyza.freedom.pl · franchising.pl (Haircut Express, błędne liczby PL) · sprawdzonybiznes.pl (SPW: Ewa Mak) · pb.pl (Tax Care 2019) · footballacademy.pl · fleet.com.pl (sieci warsztatów) · samui-spa.pl/franczyza/ · vetkompleksowo.pl (LuxVet) · newseria.pl (Edina).

*Wszystkie ustalenia i linki per firma: `prospecting/weryfikacja-2026-09.md`.*
