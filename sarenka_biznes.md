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
