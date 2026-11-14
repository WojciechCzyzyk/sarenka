# 📑 STRATEGIA OPERACYJNO-DYDAKTYCZNA: AKADEMIA APEX (Sarenka Software Kids)

## 🏢 1. Forma Prawna i Rozbieg Biznesowy (MVP)
* **Skala Startowa:** Uruchomienie od **1 do 3 grup testowych** (maksymalnie 5–15 dzieci) w celu pełnej weryfikacji procesów dydaktycznych i logistycznych bez ryzyka operacyjnego.
* **Forma Prawna (Działalność Nierejestrowana):** Start w oparciu o przepisy kwartalne.
  * **Limit Kwartalny (Stan na 2026):** Wynosi 225% minimalnego wynagrodzenia, czyli równe **10 813,50 PLN brutto / kwartał**.
  * **Zastosowanie Asymetryczne:** Nowy limit pozwala obsłużyć piki przychodowe w pierwszym miesiącu kwartału (np. opłaty wpisowe do 6500 PLN) bez konieczności natychmiastowej rejestracji firmy, o ile suma z 3 miesięcy nie przekroczy progu.
* **Plan Awaryjny (Plan B):** W przypadku szybkiego przekroczenia limitu kwartalnego, strumień przychodów zostanie podpięty pod istniejącą firmę sprzedażową Natalki poprzez dopisanie w iFirmie odpowiedniego kodu PKD:
  * **PKD 85.59.B** – *Pozostałe pozaszkolne formy edukacji, gdzie indziej niesklasyfikowane*.

## 💳 2. Architektura Płatności i Optymalizacja Kosztów
* **Brak Automatycznych Bramek Płatności:** Całkowita rezygnacja z systemów PayU/Tpay na etapie rozruchu.
  * **Zysk Finansowy:** Oszczędność 1.5% prowizji od każdej transakcji (kilkaset złotych rocznie zostaje w kieszeni).
  * **Uproszczenie Systemu:** Brak konieczności przechodzenia procedury weryfikacji konta firmowego u operatora płatności.
* **Model Przelewów Tradycyjnych (Zarządzany przez ActiveNow):**
  * W panelu wprowadzany jest bezpośredni numer konta bankowego Natalki.
  * ActiveNow automatycznie generuje i wysyła do rodziców monity (mail/SMS) ze stałą kwotą 300 PLN oraz **indywidualnym tytułem przelewu** dla każdego dziecka.
  * Księgowanie odbywa się półautomatycznie – Natalka raz w tygodniu oznacza wpłaty w systemie na podstawie wyciągu bankowego.

## ⚙️ 3. Stos Technologiczny i Rozliczenia (Data Flow)
* **Front-End & Lead Generation:** Formspree pozostaje aktywnym i darmowym sercem Landing Page `sarenka`. Zbiera zapisy do momentu fizycznego zebrania pierwszych grup.
* **System Operacyjny (ActiveNow):** Aktywacja darmowego 14-dniowego Trialu i przejście na płatny **Plan Premium 50** (125 PLN netto/mc) nastąpi dopiero w Fazie 2 (po zebraniu deklaracji od rodziców).
* **Księgowość (iFirma):** Rozliczenia pozostają w znanym środowisku iFirma.
  * *Faza MVP:* Raz w miesiącu manualny eksport pliku `.csv`/`.xls` z ActiveNow i seryjny import do iFirmy (wystawianie rachunków bez firmy lub faktur z działalności).
  * *Faza Skalowania:* Automatyzacja potoku danych za pomocą webhooków na platformie **Make.com** (*ActiveNow ➔ API iFirma ➔ Auto-wysyłka PDF*).

## 📜 4. Zabezpieczenie Kontraktowe (Szablon Umowy)
* **Struktura Umowy (§ 1 - § 7):** Przygotowano nowoczesny, partnerski kontrakt gotowy do wdrożenia do modułu zgód w ActiveNow (rodzic akceptuje "ptaszkiem" przy rejestracji).
* **Kluczowe Paragrafy:**
  * **§ 2 (Limity):** Sztywny, elitarny limit maksymalnie 5 osób w grupie.
  * **§ 3 (Finanse):** Stały abonament 300 PLN/mc, płatny do 5. dnia miesiąca z góry, niezależny od dni roboczych.
  * **§ 4 (Nieobecności):** Brak zwrotów za opuszczone zajęcia (rezerwacja miejsca); możliwość odrobienia w innej grupie w miarę dostępności slotów.
  * **§ 5 (Wypowiedzenie):** Okres próbny 14 dni, po nim elastyczny 1-miesięczny okres wypowiedzenia ze skutkiem na koniec miasta.
  * **§ 6 (Sprzęt & Narzędzia):** Wymóg własnego laptopa; zgoda na założenie konta GitHub (portfolio ucznia); wyłączenie odpowiedzialności Akademii za sprzęt.
  * **§ 7 (RODO & Wizerunek):** Zgoda na nieodpłatne publikowanie wizerunku i projektów uczniów w celach marketingowych (Showcase) z prawem do jej odwołania.

---

## 🎯 UNIKALNA WARTOŚĆ RYNKOWA (Manifest USP)
Akademia APEX trwale ńczy zaawansowane myślenie projektowe (Agile, DevOps, Git) z realną pomocą w naukach ścisłych. Zamiast rynkowych kursów-świetlic, w których dzieci bezrefleksyjnie klikają gotowe bloczki, u nas od pierwszych zajęć wchodzą w rolę deweloperów. Strona internetowa, którą dziecko samodzielnie publikuje pod własnym adresem URL, rośnie razem z nim, stanowiąc żywy dowód kompetencji (Showcase) dla rodziców i rówieśników.

---

## 📅 SYLLABUS: I KWARTAŁ (Sprint Wdrożeniowy: Fundamenty Web & Agile)
*Założenie dydaktyczne: Budujemy jeden, żywy system (Monolit), który rozwijamy przez powolne dodawanie kolejnych funkcjonalności (features). Dzieci oswajają się ze stałym środowiskiem pracy.*

### 🌐 LEKCJA 1: Moja Pierwsza Strona w Globalnej Sieci!
* **Cel:** Efekt WOW i przełamanie barier.
* **Przebieg:** Rejestracja konta GitHub, współpraca z AI przy generowaniu podstawowej struktury HTML wizytówki, wstrzyknięcie linku do awatara i premiera strony pod publicznym adresem URL.

### 📋 LEKCJA 2: Szkolne Obowiązki jako Logiczny ToDo
* **Cel:** Mapowanie realnych problemów na logikę programistyczną.
* **Przebieg:** Zrozumienie stanów zadania (Todo -> In Progress -> Done). Przeniesienie planu lekcji i zadań domowych do nowo utworzonej, dedykowanej sekcji w kodzie HTML. Manualna symulacja bazy danych przez fizyczne przenoszenie fragmentów tekstu w kodzie.

### ✍️ LEKCJA 3: Mój Cyfrowy Log Dewelopera
* **Cel:** Nauka systematyczności, pracy na gałęziach i formatowania tekstu.
* **Przebieg:** Utworzenie izolowanej gałęzi `odprawa-1`. Dodanie na dole strony dedykowanej sekcji logu (czego się nauczyłem / co zrobiłem) z wykorzystaniem znaczników listy (`<ul>`, `<li>`). Wdrożenie unikalnego obrazka-trofeum z danej lekcji i procedura Pull Request.

### 🎬 LEKCJA 4: Multimedialny Wtrysk (Efekt Kina)
* **Cel:** Bezpieczne osadzanie zasobów zewnętrznych i kontrola layoutu.
* **Przebieg:** Nauka mechanizmu `Share -> Embed` w serwisie YouTube. Wstrzyknięcie znacznika `<iframe>` do kodu strony. Analiza parametrów rozmiaru (`width`, `height`) oraz źródła (`src`). Dopasowanie kontenera z pomocą AI, aby odtwarzacz nie rozbijał widoku mobilnego.

### 🤝 LEKCJA 5: Zmiana Punktu Widzenia (Symulacja Code Review)
* **Cel:** Nauka pracy w zespole, testowania oraz konstruktywnej krytyki kodu.
* **Przebieg:** Praca w parach – zamiana ról. Uczeń A wchodzi w kod źródłowy Ucznia B, lokalizuje usterki (literówki, niedomknięte tagi) i zgłasza je jako oficjalne `Issue` w repozytorium kolegi. Uczeń B naprawia błąd w swoim kodzie i zamyka zgłoszenie merytorycznym komentarzem.

### 👑 LEKCJA 6: Przejęcie Kontroli (Najlepszy Uczeń jako Tech Lead)
* **Cel:** Zrozumienie hierarchii w zespole programistycznym i odpowiedzialności za produkcję.
* **Przebieg:** Najbardziej efektywny deweloper z poprzedniej lekcji zostaje mianowany "Tech Leadem". Otrzymuje uprawnienia administratorskie do tablicy GitHub Projects całej grupy. Klasa ma za zadanie dodać wspólny element (np. stopkę autorską). Dzieci pracują na gałęziach, ale decyzję o kliknięciu `Merge Pull Request` i wpuszczeniu zmian na żywą produkcję podejmuje wyłącznie Tech Lead po weryfikacji czystości kodu.

### 🚀 LEKCJA 7: Wielka Rewizja i Zamrożenie Kodu (Demo Day)
* **Cel:** Prezentacja wyników, konsolidacja wiedzy i publiczne zamrożenie kamienia milowego.
* **Przebieg:** Sanacja kodu (usuwanie nadmiarowych spacji, czyszczenie linków). Każdy uczeń przeprowadza 2-minutowe Demo dla grupy i rodziców – prezentuje działającą stronę, tablicę zadań, log oraz osadzony film. Oficjalne zatwierdzenie kwartału przez Mentora, zamrożenie wersji kodu i dystrybucja adresu URL w świat.


## 📅 SYLLABUS: II KWARTAŁ (Sprint Multimedialny: Cyfrowe Wideo & Integracja Systemowa)
*Założenie dydaktyczne: Utrwalamy nawyki z I kwartału (Scrum, Kanban, Git, Logi). Do stosu technologicznego wprowadzamy CapCut, dawkując funkcje po męsku — po 1-2 na lekcję. Każdy projekt przechodzi pełną ścieżkę od karty Todo do publikacji linku deweloperskiego na stronie.*

### 🎬 LEKCJA 8: Pierwsze Cięcie i Import Surowca
* **Funkcja CapCut:** Import materiałów, nawigacja po osi czasu (Timeline) i surowe cięcie (Split) materiału wideo.
* **Proces Scrum & Web:** Tworzenie karty zadania w Kanbanie. Po zmontowaniu krótkiego, 15-sekundowego klipu (np. intro), eksportujemy go i wrzucamy na chmurę (np. YouTube/Drive). Na stronie WWW powstaje nowa sekcja: `Kwartał II - Kino`. Dodajemy pierwszy link i obowiązkowy wpis do Logu Dewelopera.

### 🎨 LEKCJA 9: Dynamika i Emocje (Filtry & Przejścia)
* **Funkcja CapCut:** Nakładanie przejść (Transitions) między ujęciami oraz podstawowa korekcja klimatu za pomocą filtrów kolorystycznych.
* **Proces Scrum & Web:** Praca z checklistą w zadaniu. Dzieci uczą się, że przejścia muszą mieć sens logiczny, a nie być losowym chaosem. Aktualizacja kodu HTML o nowy, ulepszony materiał. Logowanie postępów na gałęzi testowej.

### 🔊 LEKCJA 10: Architektura Dźwięku (Audio & Podkłady)
* **Funkcja CapCut:** Wycinanie oryginalnego audio z wideo, dodawanie ścieżki muzycznej w tle oraz kontrola głośności (Volume/Fade).
* **Proces Scrum & Web:** Zrozumienie pojęcia "praw autorskich" i bezpiecznych bibliotek audio. Uczniowie szukają darmowej muzyki. Wdrożenie zaktualizowanego filmu z dźwiękiem do portfolio. Tech Lead grupy sprawdza, czy nikt nie przekroczył dopuszczalnej głośności (Peer Review).

### 💬 LEKCJA 11: Masowa Animacja Tekstu (Dynamiczne Napisy)
* **Funkcja CapCut:** Automatyczne generowanie napisów (Auto Captions), zmiana fontów, kolorów oraz masowe animowanie tekstu (Text Effects/Animations).
* **Proces Scrum & Web:** Symulacja realnego zlecenia od klienta – film musi być czytelny bez dźwięku na telefonie. Dzieciaki projektują napisy pod okiem Natalki. Wrzucenie osadzonego wideo na stronę, aktualizacja tabeli Todo do statusu Done.

### ⏳ LEKCJA 12: Kontrola Czasu i Przestrzeni (Speed & Zoom)
* **Funkcja CapCut:** Manipulacja prędkością wideo (Speed Control / Slomo / Timelapse) oraz kluczowanie przybliżeń (Keyframe Zoom).
* **Proces Scrum & Web:** Nauka planowania dynamicznych ujęć. Zgłoszenie technicznego `Issue` u kolegi, jeśli napisy z poprzedniej lekcji rozjeżdżają się z przyspieszonym wideo. Naprawa błędu regresji na produkcji.

### 👑 LEKCJA 13: Wielka Produkcja (Tech Lead jako Reżyser Montażu)
* **Funkcja CapCut:** Łączenie wszystkich poznanych technik w jeden, 60-sekundowy autorski format reklamowy lub deweloperski.
* **Proces Scrum & Web:** Pełna symulacja studia produkcyjnego. Tech Lead lekcji zarządza priorytetami w GitHub Projects. Sprawdza, czy formaty wyjściowe wideo zgadzają się ze specyfikacją techniczną, zanim pozwoli na finalne scalenie Pull Requesta z głównym kodem strony WWW.

### 🚀 LEKCJA 14: Cyfrowy Festiwal Filmowy (Demo Day II)
* **Funkcja CapCut:** Ostateczny render i optymalizacja wagi pliku do publikacji sieciowej.
* **Proces Scrum & Web:** Wielkie sprzątanie repozytorium (usuwanie starych wersji roboczych filmów z assetów, zostawiamy tylko finalne linki). Każde dziecko prezentuje swoją rozwiniętą o sekcję wideo stronę WWW przed rodzicami. Zamrożenie kodu II kwartału. Sukces rynkowy i dydaktyczny potwierdzony logami.

* ## 📅 SYLLABUS: III KWARTAŁ (Sprint Algorytmiczny: Wprowadzenie do Scratcha & Logiki)
*Założenie dydaktyczne: Trzymamy żelazną dyscyplinę organizacyjną (Kanban, Git, Log, osadzanie projektów na stronie WWW za pomocą tagu iframe). Wprowadzamy Scratcha. Pierwsze 3 lekcje to szybkie, jednolekcyjne projekty (zrozumienie pętli i zdarzeń), a lekcje 4-7 to ambitniejsze, dwulekcyjne wyzwanie.*

### 🎮 LEKCJA 15: Cyfrowy Start i Karuzela Zdarzeń (Projekt: Klikacz)
* **Algorytm Scratch:** Zdarzenie uruchomieniowe (`Kiedy kliknięto zieloną flagę`), zmiana kostiumu duszka oraz detekcja kliknięcia myszką.
* **Proces & Web:** Praca z Kanbanem. Po zakodowaniu prostej minigry w klikanie duszka, dzieci publikują ją na platformie MIT Scratch. Kopiują link i osadzają go na swojej stronie WWW jako `iframe`. Wpis do logu na chmurze Git.

### 🏃 LEKCJA 16: Pętle Nieskończone i Układ Współrzędnych (Projekt: Strażnik Graniczny)
* **Algorytm Scratch:** Ruch duszka, sterowanie strzałkami (klawiatura), pętla `Zawsze` oraz instrukcja warunkowa `Jeżeli na brzegu, odbij się`. Zrozumienie osi X i Y.
* **Proces & Web:** Tworzenie checklisty zadań. Wdrożenie zaktualizowanej wersji gry (sterowanej z klawiatury) na żywą produkcję. Logowanie postępów przez Pull Request.

### 🛡️ LEKCJA 17: Detekcja Kolizji i Zmienna Wyniku (Projekt: Zbieracz Gwiazd)
* **Algorytm Scratch:** Tworzenie zmiennej (`Wynik`), losowanie pozycji obiektów na ekranie oraz czujnik dotyku (`Dotyka duszka X`).
* **Proces & Web:** Zrozumienie pojęcia "zmiennej" jako komórki w pamięci RAM. Aktualizacja strony www. Testowanie gry kolegi (Code Review) i zgłaszanie uwag w GitHub Issues, jeśli punkty naliczają się błędnie.

### 🌓 LEKCJA 18 & 19: Algorytm Sztucznej Inteligencji w pętli (Projekt: Klasyczny Pong — Wyzwanie 2-lekcyjne)
* **Lekcja 18 (Sprint 1):** Architektura fizyki odbicia. Duszek-paletka sterowany myszą + piłka poruszająca się i odbijająca od ścian i paletki.
* **Lekcja 19 (Sprint 2):** Logika przegranej (strefa czerwona na dole restartuje wynik) + wdrożenie drugiego duszka sterowanego prostym algorytmem śledzenia piłki (Bot jako przeciwnik).
* **Proces & Web:** Duża aktualizacja sekcji gry na stronie. Tech Lead weryfikuje poprawność działania fizyki piłki przed dopuszczeniem kodu PR do gałęzi głównej.

### 🤖 LEKCJA 20 & 21: Komunikacja międzyprocesowa (Projekt: Interaktywny Komiks / Dialog — Wyzwanie 2-lekcyjne)
* **Lekcja 20 (Sprint 1):** Nadawanie komunikatów radiowych (`Nadaj komunikat X i czekaj`). Koordynacja czasowa – kiedy Duszek A kończy mówić, Duszek B zaczyna reagować.
* **Lekcja 21 (Sprint 2):** Dynamiczna zmiana tła (scenografii) oraz wstrzyknięcie efektów dźwiękowych wywoływanych odebranym komunikatem.
* **Proces & Web:** Zrozumienie mechanizmu asynchronicznego przesyłania wiadomości (Broadcast). Wdrożenie interaktywnej animacji na stronę WWW. Zamrożenie kodu III kwartału.

---

## 📅 SYLLABUS: IV KWARTAŁ (Sprint Inżynierski: Projekt Monolit & Wielki Finał)
*Założenie dydaktyczne: Przez cały kwartał dzieci budują jeden, potężny, wielowątkowy projekt (Monolit). Uczą się pisać czysty, modułowy kod blokowy, optymalizować algorytmy oraz zarządzać wielotygodniowym projektem deweloperskim w Scrumie.*

### 🚀 LEKCJE 22–27: Projekt Monolit: Cyfrowy Asystent Dzielenia Pisemnego (lub własna strategiczna gra RPG)
* **Ramy Projektowe:** Cały kwartał to jeden, żywy system podzielony na mniejsze kamienie milowe.
* **Kamień Milowy 1 (Lekcje 22-23):** Silnik matematyczny i parsowanie danych. Duszek pyta użytkownika o dwie liczby, sprawdza warunki logiczne i rozbija tekst liczby na pojedyncze cyfry (tablice/listy).
* **Kamień Milowy 2 (Lekcje 24-25):** Matryca wizualna. Wykorzystanie mechanizmu klonowania kratek (Clone Engine) do dynamicznego rysowania na ekranie matematycznej siatki dzielenia krok po kroku.
* **Kamień Milowy 3 (Lekcje 26-27):** Warstwa UX/UI i audio. Dodawanie komunikatów głosowych błędu i sukcesu, animacje kursorów pomocniczych, ostateczne polerowanie kodu blokowego i optymalizacja pętli.
* **Proces Scrum & Web:** Praca na zaawansowanej tablicy Kanban (Sub-issues, priorytety kart). Co tydzień na stronie WWW ląduje nowa, zaktualizowana wersja systemu (Wersje Alfa, Beta, Release Candidate).

### 🏆 LEKCJA 28: Wielki Finał i Audyt Certyfikacyjny (Showcase)
* **Przebieg:** Ostateczne czyszczenie kodu i optymalizacja pamięci. Każdy młody inżynier przygotowuje uroczystą prezentację swojego rocznego dorobku.
* **Efekt końcowy:** Rodzice otrzymują link do kompletnego, rocznego portfolio ucznia. Na jednej stronie WWW znajduje się cała historia jego nauki, logi z 28 lekcji, zmontowane produkcje wideo oraz osadzone, w pełni grywalne i zaawansowane aplikacje ze Scratcha. Natalka (Mentor) wręcza oficjalne inżynierskie certyfikaty ukończenia rocznej Akademii APEX. Kod zostaje trwale zamrożony w chmurze GitHub.

* ## 💰 PLAN FINANSOWANIA ZEWNĘTRZNEGO I DOTACJI: AKADEMIA APEX (2026)

### 🧭 Architektura Decyzyjna: Firma na Wojtka vs Firma na Natalkę
* **Wariant A — Start i dotacja na Wojtka (Rekomendowany):** Pozwala na uzyskanie bezzwrotnych środków na start (55 000 – 150 000 zł). Prowadzenie własnej JDG **nie blokuje** późniejszego powrotu na etat w korporacji/software house'ie Embedded, a po okresie trwałości dotacji (12 lub 24 m-ce) umożliwia płynne przejście na kontrakt B2B IT. Natalka może być zatrudniona w firmie jako główny instruktor.
* **Wariant B — Rozwój na istniejącej firmie Natalki:** Brak dostępu do dotacji na otwarcie działalności (ze względu na aktywne CEIDG). Możliwe wyłącznie mniejsze dofinansowania na szkolenia (BUR) lub nisko oprocentowane pożyczki rozwojowe.

---

### 📊 Porównanie Dwóch Głównych Ścieżek Dotacyjnych (2026)

| Parametr | Ścieżka 1: Dotacja PFRON (przez PUP) | Ścieżka 2: Premia unijna LGD (Jeżów Sudecki) |
| :--- | :--- | :--- |
| **Kwota wsparcia** | Do **55 400 zł** (12 m-cy) lub do **138 500 zł** (24 m-ce) | Zwykle **100 000 – 150 000 zł** (zależnie od naboru) |
| **Wkład własny** | **0 zł** (100% finansowania z dotacji) | Wymagany (zwykle ok. **35%** wartości projektu) |
| **Główny warunek** | Orzeczenie o niepełnosprawności + status bezrobotnego lub poszukującego pracy | Zamieszkanie na obszarze wiejskim (Jeżów Sudecki spełnia warunek) |
| **Zakup samochodu** | Możliwy przy mocnym uzasadnieniu (przewóz sprzętu + ograniczenia kręgosłupa) | Standardowo akceptowany jako środek trwały firmy |
| **Czas realizacji** | Szybki (nabory w PUP ruszają zwykle na początku roku) | Dłuższy (zależny od harmonogramu konkursów LGD) |

---

### 🚀 Mapa Drogowa w Sprintach (Krok po Kroku)

#### Sprint 0: Zabezpieczenie Dokumentacji Szpitalnej (Dzień wypisu z Wałbrzycha)
* **Cel:** Wyjście ze szpitala z kompletem papierów medycznych.
* **Zadania:**
  1. Pobranie wszystkich kart informacyjnych z leczenia (hematologia + obie operacje neurochirurgiczne Th6-Th8).
  2. Poproszenie lekarza prowadzącego o wypełnienie **zaświadczenia lekarskiego o stanie zdrowia na druku PZON** (uwaga: druk jest ważny tylko **30 dni** od daty wystawienia).
  3. Dopilnowanie adnotacji lekarza o **braku możliwości osobistego stawiennictwa na komisji** (gwarantuje tryb zaoczny bez dojazdu).

#### Sprint 1: Orzeczenie o Niepełnosprawności (Tydzień 1–2 po powrocie do domu)
* **Cel:** Uzyskanie formalnego orzeczenia (otwiera drogę do PFRON, ulg podatkowych i świadczeń).
* **Dokumenty do złożenia w PZON Jelenia Góra:**
  1. Wypełniony wniosek o wydanie orzeczenia o stopniu niepełnosprawności.
  2. Oryginał zaświadczenia lekarskiego ze szpitala (z ważną datą do 30 dni).
  3. Kserokopie kart informacyjnych ze szpitala (oryginały do wglądu przy składaniu).
* **Czas oczekiwania:** Ok. 1–2 miesiące na wydanie decyzji.

#### Sprint 2: Rejestracja i Status w Urzędzie Pracy (Po otrzymaniu orzeczenia)
* **Cel:** Uzyskanie statusu uprawniającego do złożenia wniosku o dotację.
* **Żelazna zasada:** Zakaz rejestracji nowej firmy w CEIDG przed podpisaniem umowy o dotację.
* **Dokumenty w PUP Jelenia Góra:**
  1. Dowód osobisty oraz orzeczenie o stopniu niepełnosprawności.
  2. Dyplomy ukończenia studiów (Politechnika Wrocławska) oraz dokumenty potwierdzające brak zatrudnienia.
  3. Rejestracja jako osoba bezrobotna lub **poszukująca pracy niepozostająca w zatrudnieniu** (w przypadku pobierania renty z ZUS).

#### Sprint 3: Wniosek o Dotację i Kosztorys APEX (Start: ok. 2–3 miesiące od dziś)
* **Cel:** Złożenie kompletnego wniosku o dotację PFRON (lub w naborze LGD Partnerstwo Ducha Gór).
* **Dokumenty do przygotowania:**
  1. Wniosek o przyznanie środków na podjęcie działalności gospodarczej (formularz z PUP/PFRON).
  2. **Biznesplan Akademii APEX** (opis programu 31 lekcji, grup docelowych w szkołach podstawowych, kalkulacja przychodów i kosztów).
  3. **Szczegółowy kosztorys zakupów:** np. 8 laptopów dla uczniów, laptop instruktora, rzutnik/ekran, router mobilny 5G, oprogramowanie/licencje, strona/marketing oraz środek transportu (samochód do przewozu mobilnej pracowni między szkołami).
  4. **Zabezpieczenie zwrotu dotacji:** Poręczenie osób trzecich (np. rodzina) lub blokada środków na rachunku bankowym.

#### Sprint 4: Podpisanie Umowy, Rejestracja CEIDG i Zakupy
* **Cel:** Fizyczne uruchomienie firmy ze środków dotacyjnych.
* **Kolejność działań:**
  1. Podpisanie umowy o dotację z urzędem i wpływ środków na konto bankowe.
  2. Rejestracja jednoosobowej działalności gospodarczej w CEIDG (kod PKD edukacyjny: **85.59.B**).
  3. Zakup sprzętu i pojazdu zgodnie z kosztorysem oraz rozliczenie faktur w urzędzie (zwykle w ciągu 30–60 dni od otrzymania środków).
 
* ## 🧲 Faza 2 Marketingu: Interaktywny Lead Magnet („Wędka Quizowa APEX”)

### 1. Decyzja Strategiczna (Lead Magnet zamiast osobnego SaaS)
* **Analiza rynku:** Istniejące narzędzia AI generujące quizy ze zdjęć (np. Studera.ai, Tapnote, Quizgecko) operują w wysoce konkurencyjnym modelu B2C z hojnymi darmowymi planami. Budowa osobnego startupu SaaS wiązałaby się z wysokimi kosztami utrzymania i marketingu.
* **Przewaga Akademii APEX:** Konkurencja sprzedaje gotową „rybkę” (zamkniętą aplikację), podczas gdy APEX sprzedaje „wędkę” i status twórcy – dzieci same piszą i wdrażają własny kod. Generator ze zdjęcia zostaje wykorzystany jako niskokosztowy, wysokokonwertujący **Lead Magnet** na stronie `sarenka`, budujący bazę mailową rodziców uczniów klas 3–8 z regionu.

### 2. Potrójny Filtr Ochronny (Ochrona przed kanibalizacją kursu)
Aby darmowy generator budował apetyt, ale nie zastępował udziału w warsztatach, wprowadzono trzy twarde ograniczenia:
1. **Limit objętości (10 pytań):** Generator tworzy próbkę składającą się maksymalnie z 10 pytań z jednego zdjęcia – wystarczającą na efekt „WOW”, ale za małą na cały dział przed sprawdzianem.
2. **Limit użycia (1 przejście / Demo Single-Pass):** Wygenerowany quiz działa w trybie jednorazowego przejścia (blokada ponownego uruchomienia po zakończeniu gry za pomocą `localStorage` w przeglądarce). Uniemożliwia to traktowanie linku jako darmowej „ściągi do wielokrotnego wkuwania”.
3. **Wezwanie do działania (CTA na ekranie blokady):** Po ukończeniu demo rodzic i dziecko widzą komunikat: *„Świetny wynik! To była wersja demonstracyjna (1 przejście). Chcesz zapisać ten quiz na stałe, grać bez limitu przed każdym sprawdzianem, rozbudować go do 100 pytań i opublikować na własnej stronie w internecie? Dołącz do Akademii APEX – pokażemy Ci, jak samodzielnie stworzyć i utrzymać własny system nauki!”*.

### 3. Lekki Stos Technologiczny Wdrożenia (Zero kosztów stałych)
* Formularz wgrania zdjęcia + adres e-mail rodzica ➔ Webhook **Make.com** ➔ Tanie API modelu wizyjnego (ekstrakcja 10 pytań do szablonu HTML/JS z blokadą `localStorage`) ➔ Automatyczna wysyłka linku/pliku na e-mail rodzica.


### 🤖 Autorski System „APEX AI Code Mentor” (Automatyczne Code Review & Grywalizacja)
* **Koncepcja systemu:** Własny silnik dydaktyczny oparty na automatyzacji **GitHub Actions** oraz modelach językowych (LLM), który analizuje rzeczywisty kod pisany przez ucznia po każdym zatwierdzeniu zmian (`Commit / Push`) i prowadzi jego indywidualną historię rozwoju.
* **Pamięć i profilowanie postępów (`mentor_log`):** System przechowuje historię wcześniejszych wpisów i postępów konkretnego dziecka. Dzięki temu AI nie generuje powtarzalnych szablonów, lecz odnosi się do realnej ścieżki ucznia (np. docenia wyeliminowanie błędów z poprzednich zajęć i proponuje kolejne wyzwanie dopasowane do jego tempa).
* **Okienko postępu na żywo na stronie ucznia (Grywalizacja):** Na osobistej witrynie każdego dziecka (`nick.github.io`) znajduje się dedykowany widget **„Status od AI Mentora”**, który kilkanaście sekund po zapisaniu kodu wyświetla spersonalizowaną pochwałę oraz kolejną wskazówkę techniczną. Wyzwala to zdrową rywalizację, dumę z własnych rozwiązań i natychmiastową informację zwrotną na sali.
* **Podwójny strumień wyjściowy (Uczeń + Rodzic):** Z jednej analizy kodu (`git diff` + historia logów) system generuje dwa osobne komunikaty:
  1. **Dla ucznia (na stronę WWW):** Krótki, motywujący feedback techniczny w stylu partnerskiego mentora.
  2. **Dla rodzica (raport po zajęciach):** Zrozumiałe podsumowanie oparte na wzorcu *Feedback Sandwich* (konkretna pochwała za efekt + życzliwa wskazówka rozwojowa + bezpośredni link do działającego projektu).
