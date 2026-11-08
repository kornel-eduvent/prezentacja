# Projekt: Prezentacja Eduvent dla Samorządu Miejskiego

## Cel projektu
Przygotowanie profesjonalnej prezentacji firmy Eduvent skierowanej do samorządu miejskiego (Departament Edukacji). Cel: nawiązanie współpracy. Prezentacja ma odpowiedzieć na pytania: kim jesteśmy, czym się zajmujemy, co osiągnęliśmy, i co możemy wspólnie zrobić.

## Format techniczny
- **Narzędzie:** HTML + reveal.js
- **Eksport:** Na koniec do PDF (via Playwright / decktape)
- **Assety graficzne:** `extracted_images/` — wyekstrahowane z eduvent1.pdf i eduvent2.pdf
  - `unique/` — 30 unikalnych grafik bez duplikatów
  - `eduvent1/full_page*.png` — 9 pełnych stron (4000x2250)
  - `eduvent2/full_page*.png` — 6 pełnych stron (4000x2250)

---

## O firmie Eduvent

### Czym jest Eduvent?
Pierwsza w Polsce platforma do wyszukiwania i rezerwacji wydarzeń edukacyjnych dla szkół i przedszkoli. Łączy placówki oświatowe z organizatorami warsztatów, spektakli, pokazów i zajęć edukacyjnych. Korzystanie z platformy jest **bezpłatne** dla nauczycieli i placówek.

### Strona: eduvent.pl

### Problem który rozwiązuje
1. **Rozproszenie ofert** — rynek wydarzeń edukacyjnych jest rozproszony, nauczyciele szukają po internecie, social mediach, poleceniach
2. **Weryfikacja jakości** — brak centralnego miejsca z opiniami i zweryfikowanymi organizatorami
3. **Proces rezerwacji** — czasochłonny: telefony, maile, ustalenia terminów i cen

### Jak działa (struktura rynku)
- **TERAZ:** Chaotyczna siatka połączeń nauczyciel ↔ firma (każdy z każdym)
- **Z EDUVENT:** Centralizacja — nauczyciele → Eduvent → firmy (hub pośredniczący)

### Funkcje platformy
- Wyszukiwanie i porównywanie ofert (filtry: kategoria, wiek, lokalizacja, typ placówki)
- Rezerwacja online w 5 minut (jak bilety do kina)
- System opinii i ocen (gwiazdki, filtrowanie)
- Panel zarządzania rezerwacjami (historia, statusy, szczegóły)
- Kalendarz wydarzeń
- Ulubione oferty
- Bezpośredni kontakt z organizatorami
- **Eduvent Pay** — system zbiórek (dowolny cel, e-zgody od rodziców, szybkie płatności BLIK/online, koszt przerzucony na rodzica — niewielka opłata serwisowa)
- **Eduvent Vote** — (nowa funkcjonalność, planowana do pilotażu)

### Kategorie wydarzeń
Teatr, Warsztaty, Planetarium, Animacje, Iluzjonista, Robotyka, Rośliny, Ekologia, Sport, Laboratorium, Muzyka, Profilaktyka, Zwierzęta, Kulinaria, Nowe technologie, Druk 3D, Terapia, Programowanie, Plastyka

### Poziomy edukacji
Żłobek, Przedszkole, Szkoła podstawowa, Szkoła średnia

### Typ atrakcji
W szkole, Poza szkołą

### Metody płatności
Przelewy24 (online), Przelew po wydarzeniu, Gotówka w dniu wydarzenia

---

## Model biznesowy
1. **Prowizje od rezerwacji** — od firm za każdą rezerwację
2. **Promowanie ofert** — płatne wyróżnianie ofert firm
3. **Opłata od zbiórek** (Eduvent Pay) — niewielka opłata serwisowa od rodziców

---

## Osiągnięcia (pierwszy rok działalności — rok szkolny 2025/2026)
- **80+** zarejestrowanych szkół i przedszkoli z całej Polski
- **100+** leadów (placówki zainteresowane współpracą w kolejnym roku)
- **300** aktywnych ofert wydarzeń na platformie
- **80** organizatorów wydarzeń
- **20** zrealizowanych rezerwacji
- **86 000+ zł** wartości zrealizowanych rezerwacji (GMV)
- **100%** pozytywnych opinii
- Ogólnopolski zasięg
- Działający produkt (MVP) wykorzystywany przez realnych użytkowników

---

## Rynek edukacyjny w Polsce
- **6,5 mln** uczniów
- **500 tys.** nauczycieli
- **48 tys.** placówek
- **72%** dzieci uczestniczy w zajęciach dodatkowych (tendencja wzrostowa od 2013, źródło: CBOS)
- Średnia wydatków rodziców na dodatkowe zajęcia: **629 zł/miesiąc**
- Szacowany udział edukacji nieformalnej (warsztaty, wydarzenia): **~32 zł/miesiąc** (~5%)
- **Wartość rynku: 1 350 000 000 zł rocznie** (32 zł × 9 msc × 6,5 mln × 72%)

### Koszyk zakupowy (wydatki na wydarzenia edukacyjne wg miast)
- Szczecin: 2 696 zł | Gdańsk: 2 657 zł | Ełk: 2 675 zł
- Poznań: 1 972 zł | Warszawa: 2 306 zł | Zielona Góra: 2 409 zł
- **Wrocław: 2 261 zł** | Katowice: 2 040 zł | Rzeszów: 2 454 zł
- **Średnia dla Polski: 2 400 zł**

### Dolny Śląsk
- **460 000 uczniów** na Dolnym Śląsku

---

## Konkurencja
| Firma | Klient docelowy | Główna funkcja |
|-------|----------------|----------------|
| LiveKid, Librus | Nauczyciele | Zarządzanie placówką |
| **Eduvent** | **Nauczyciele** | **Rezerwacja wydarzeń** |
| Kidos, Fajny Czas | Rodzice | Rezerwacja wydarzeń |

Eduvent jest **jedyną platformą** skierowaną do nauczycieli, specjalizującą się w rezerwacji wydarzeń.

---

## Finanse (prognozy)
- **CAC:** 106 zł (koszt pozyskania klienta)
- **ARPU:** 900 zł (średni przychód z aktywnego użytkownika/rok)
- **LTV:** 2 700 zł (wartość klienta na 3 lata)
- **Szacowany współczynnik aktywnych użytkowników:** 25%

| Metryka | Czerwiec 2026 | Czerwiec 2027 | Czerwiec 2028 |
|---------|--------------|--------------|--------------|
| Użytkownicy | 3 300 | 6 600 | 10 000 |
| Aktywni użytkownicy | 825 | 1 650 | 2 500 |
| Rezerwacje/miesiąc | 200 | 400 | 600 |
| Przychód/miesiąc | 60 000 zł | 120 000 zł | 180 000 zł |

---

## Zespół
- **Piotr Ramotowski** — Biznes. 10 lat w branży edukacyjnej, sprzedaż 1,2 mln zł/rok. Odpowiada za kampanie Meta ADS, koordynację, rozwój platformy, obsługę klienta.
- **Kornel Mrozek** — Technologia. 10 lat jako programista, Scala developer, Kubernetes/Kafka/Cassandra. Odpowiada za rozwój platformy, wdrażanie funkcjonalności, skalowalność.
- **Marcin Porzuczek** — Biznes. Przedsiębiorca od 2016, ponad rok w branży edukacyjnej. Odpowiada za pozyskiwanie firm i poszukiwanie finansowania.
- **Karol Węgrzyniak** — Marketing. Założyciel Data-Driven Expert — konsultingu specjalizującego się w PPC, analityce i automatyzacji AI. Odpowiada za marketing i strategię digitalową opartą na danych. (bio: datadrivenexpert.com/team/karol-wegrzyniak/)

---

## Propozycje współpracy z samorządem (z pomysły.txt)

### 3 główne propozycje:

**1. Cykl warsztatów profilaktycznych pod patronatem Departamentu Edukacji**
- Bezpłatne warsztaty dla uczniów/nauczycieli/dyrektorów
- Tematy dla Przedszkoli+SP: Hejt w internecie, Ograniczone zaufanie do obcych, Ekologia, Tolerancja, Cyberbezpieczeństwo
- Tematy dla Ponadpodstawowych: Hejt w internecie, Wpływ narkotyków i alkoholu, AI jako zagrożenie i szansa, Zdrowie psychiczne, Ścieżki rozwoju zawodowego w świecie AI
- **W zamian:** współpraca przy pozyskiwaniu grantów/funduszy unijnych i krajowych

**2. Pilotaż innowacyjnych rozwiązań w placówkach Wrocławia**
- Testowanie Eduvent Pay i Eduvent Vote w wybranych szkołach/przedszkolach
- Raporty i analizy wpływu na organizację pracy, oszczędność czasu

**3. Współpraca doradcza**
- Przedstawiciel Departamentu jako doradca przy projektowaniu nowych funkcjonalności
- Wspólne tworzenie rozwiązań dopasowanych do potrzeb wrocławskich placówek

### Program partnerski (cashback)
- Placówki mogą otrzymać cashback na koniec roku na dowolny cel statutowy (remont sali, wsparcie uczniów, festyn, inne)
- Przy 460 000 uczniów na Dolnym Śląsku — potencjał jest znaczący

### Dane dla miasta
- Raporty trendów: z czego korzysta edukacja w regionie (najpopularniejsze kategorie)
- Dane których urząd nie posiada — wartościowe dla planowania polityki edukacyjnej

### Kalendarz wydarzeń miejskich
- Eduvent jako dodatkowy kanał komunikacji miejskich wydarzeń (konkursy, granty, akcje ekologiczne, projekty sportowe/zdrowotne)
- Osobny dział na stronie lub integracja z newsletterem

### 3 konkretne pomysły na projekty edukacyjne:

**"AI Detektywi" — gra miejska / escape room**
- Uczniowie rozwiązują sprawę cyfrowego zagrożenia (deepfake, phishing, manipulacja)
- Uczy: krytycznego myślenia, cyberbezpieczeństwa, ochrony danych
- Medialny format: finał, dyplomy, ranking szkół, patronat prezydenta
- Wpisuje się w program "Cyfrowy Uczeń" 2025-2029

**"Młodzi przedsiębiorcy"**
- Uczniowie tworzą mini-projekty dla lokalnej społeczności
- Uczy: przedsiębiorczości, budżetowania, prezentacji, współpracy
- Finał w urzędzie/centrum kultury — efekt wizerunkowy

**Konkurs "AI dla mojego miasta"**
- Uczniowie projektują wykorzystanie AI dla problemów miasta
- Uczy: kreatywności, odpowiedzialnego projektowania technologii
- Miasto pokazuje się jako nowoczesne i odpowiedzialne

---

## Identyfikacja wizualna (branding)

### Kolory
- **Primary:** Cyjan/turkus (~#22B8CE / #00B4D8) — logo, nagłówki, akcenty, przyciski
- **Secondary:** Żółty/złoty — używany w "PAY" w logo Eduvent Pay
- **Tekst:** Czarny/ciemny szary — nagłówki bold
- **Tło:** Białe z delikatnymi szarymi elementami dekoracyjnymi (okręgi, łuki)

### Styl
- Czysty, nowoczesny, minimalistyczny
- Neumorfizm (miękkie cienie, zaokrąglone karty)
- Duże dekoracyjne okręgi/łuki w tle (element rozpoznawalny)
- Zaokrąglone przyciski i karty z subtelnymi cieniami
- Numeracja slajdów w turkusowym prostokącie (prawy dolny róg)
- Logo "eduvent" w boldzie, bezszeryfowe, małe litery

### Font
- Bold sans-serif (prawdopodobnie niestandardowy/custom)
- Nagłówki: bardzo grube, czarne
- Podtytuły/opisy: normalna waga, ciemny szary
- Akcenty (nazwy w turkusie): bold

### Elementy graficzne w assetach
- Screenshoty platformy (wersja desktop i mobile)
- Mapa Polski z kosztami zakupowymi wg miast
- Diagramy struktury rynku (teraz vs przyszłość)
- Ikony: globus, weryfikacja, ludzie (w kółkach z cieniami)
- Zdjęcia zespołu (okrągłe ramki)
- Logo Eduvent Pay (turkusowy zaokrąglony prostokąt)
