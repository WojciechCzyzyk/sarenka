
INSTRUKCJA BOJOWA APEX: LOGISTYKA GRUPOWA (GIT & KANBAN)

Dla Instruktora (Natalki) oraz Architekta (Wojtka) – Wdrożenie Domowego Poligonu PoC

🛠️ ETAP 1: Przygotowanie Bazy przez Natalkę (Przed zajęciami)

Natalka konfiguruje na swoim koncie GitHub centralne środowisko, które będzie sercem Akademii przez cały rok.
1. Skrzynia z kodem (Repozytorium-Matka):
	• Natalka tworzy repozytorium o nazwie np. apex-starter-pack.
	• Wrzuca tam czysty szablon strony: index.html, style.css oraz odizolowane pliki-piaskownice dla dzieci (log.html, projekty.html).
2. Centrum Dowodzenia (Tablica GitHub Projects):
	• Na swoim koncie Natalka zakłada jedną, główną tablicę projektową (widok Kanban).
	• Tworzy kolumny: 📥 Inbox -> 📋 ToDo -> 🏃 In Progress -> ✅ Done.
	• Tworzy karty zadań na pierwszą lekcję (np. „Zadanie 1: Zmień kolor tła strony”). Powiela je tak, aby każde dziecko miało swoją kartę, i przypisuje je do poszczególnych profilów dzieci za pomocą funkcji Assignee (każda karta ma zdjęcie/awatar danego dziecka).
3. Pulpit Wielowidokowy (Multi-Views):
	• Na górze tablicy Natalka klika znak plusa + New view i tworzy osobne zakładki dla każdego dziecka.
	• W zakładce Kamila wpisuje w wyszukiwarkę filtr: assignee:KamilDev. W zakładce Oli: assignee:OlaCodes.
	• Wynik: Jednym kliknięciem myszki Natalka przełącza się między czystymi, odizolowanymi tablicami każdego ucznia.


ETAP 2: Onboarding Dzieci (Pierwsze 15 minut lekcji)

Prowadzimy dzieciaki za rękę przez rejestrację, używając prostego języka gier (hasła w cudzysłowach to skrót dla Natalki).
1. Zakładanie Konta Gracza: Dzieci wchodzą na github.com i przechodzą lajtową procedurę rejestracji profilu (Sign up). Wybierają czytelne, profesjonalne nicki (np. KamilDev, OlaCodes).
2. Magiczny Przycisk (Forkowanie):
	• Natalka podaje dzieciom link do swojego repozytorium apex-starter-pack.
	• Dzieci wchodzą na stronę Natalki i klikają w prawym górnym rogu ikonę 🍴 Fork.
	• GitHub pyta o nazwę: dzieci wpisują swój nick z końcówką .github.io (np. KamilDev.github.io) i klikają Create fork.
	• BUM! W tym momencie cała paczka plików startowych Natalki kopiuje się na konta dzieci, a ich własna strona www w tej samej sekundzie ożywa w internecie pod ich własnym adresem!
3. Wejście do Matrixa: Dzieci będąc w swoim nowym repozytorium wciskają na klawiaturze klawisz z kropką . (kropka). Na ich ekranach uruchamia się czarny, hakerski edytor internetowy Web VS Code (github.dev). Są gotowe do kodowania.



 ETAP 3: Praca w Pętli Czasu Rzeczywistego (Jak Natalka kontroluje sytuację?)

Dzieciaki piszą kod w swoich edytorach i przesuwają swoje karty na tablicy. Natalka siedzi wygodnie z laptopem w fotelu.
• Jak jedno dziecko nie popsuje tablicy innym?
Kiedy dzieci wchodzą na centralną tablicę Natalki, klikają przycisk filtru @me. Widzą wtedy tylko swoje zadania. Ponieważ Natalka nadała im uprawnienia wykonawców (Writers), mogą przestawiać myszką tylko swoje karty z ToDo do In Progress. GitHub zablokuje im możliwość edycji globalnego wyglądu tablicy czy przestawiania kart kolegów. Jeśli ktoś spróbuje zrobić kawał – panel boczny Activity u Natalki od razu wyświetli czerwony log z imieniem "sprawcy".
• Jak Natalka widzi zmiany w plikach bez podchodzenia do biurka?
Kiedy Kamil skończy pisać kod i kliknie w edytorze niebieski przycisk Commit & Push, pakiety lecą do chmury. Natalka na swoim laptopie:
	1. Klika w zakładkę Forks na swoim repozytorium.
	2. Widzi status Kamila: „Ahead by 1 commit”. Kliknie w jego imię.
	3. Wchodzi w historię commitów Kamila i klika w najnowszy.
	4. Magia kodu (Diff View): GitHub wyświetla Natalce czysty plik Kamila. Zmiany, które chłopak dopisał, świecą się na jaskrawy zielony kolor. Jeśli Kamil popełnił błąd, Natalka widzi to z fotela i mówi: "Kamil, w linijce 15 zapomniałeś zamknąć cudzysłowu, popraw to".
	5. Dodatkowo Natalka ma otwartą w przeglądarce kartę kamildev.github.io – po odświeżeniu widzi dokładnie ten wizualny efekt, który przed chwilą stworzyło dziecko.


