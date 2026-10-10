### 1. Metryka

- Nazwa projektu:  Zapisy na konsultacje prowadzących
- Numer zespołu i członkowie: Anna Kłos, Anastasiia Hopchuk, Łukasz Kopyrski
- Klient / organizacja / rola klienta: 
- Data i wersja: 10.10.2026 v0.1
- Status źródła informacji: symulacja na zajęciach

### 2. Problem

**Stan obecny:** Zapisy na konsultacje z wykładowcami odbywają się głównie za pośrednictwem poczty elektronicznej lub poprzez bezpośredni kontakt ze studentami. Brakuje jednolitego systemu umożliwiającego sprawdzanie dostępnych terminów oraz rezerwowanie spotkań. Studenci muszą indywidualnie kontaktować się z prowadzącymi, a wykładowcy samodzielnie zarządzają harmonogramem konsultacji.

**Negatywne skutki:** Obecny sposób organizacji konsultacji powoduje wydłużenie procesu umawiania spotkań, ryzyko nakładania się terminów oraz trudności w komunikacji między studentami a wykładowcami. Brak centralnego systemu utrudnia kontrolowanie dostępności konsultacji, prowadzi do nieporozumień i zwiększa liczbę wiadomości e-mail. Może również skutkować niewykorzystaniem dostępnych terminów oraz opóźnieniami w uzyskaniu pomocy dydaktycznej.

**Kto odczuwa problem:** Problem dotyczy przede wszystkim studentów, którzy mają trudności ze sprawnym umawianiem konsultacji, oraz wykładowców, którzy muszą ręcznie zarządzać zapisami i dostępnością terminów. Pośrednio dotyczy również administracji uczelni, odpowiedzialnej za organizację i sprawne funkcjonowanie procesu dydaktycznego.

### 3. Cel biznesowy a produkt semestru

**Pożądana zmiana u klienta:** Wdrożenie jednolitego systemu internetowego umożliwiającego studentom szybkie i wygodne zapisywanie się na konsultacje z wykładowcami. Studenci powinni mieć możliwość przeglądania dostępnych terminów, rezerwowania spotkań oraz ich odwoływania, natomiast wykładowcy – samodzielnego zarządzania harmonogramem konsultacji. System powinien usprawnić komunikację, ograniczyć konieczność wymiany wiadomości e-mail, wyeliminować konflikty terminów oraz zwiększyć dostępność i przejrzystość procesu organizacji konsultacji na uczelni.

**Co rzeczywiście oddajemy w tym semestrze:** dokumentację projektową opisującą planowany system.

### 4. Zakres

| W zakresie | Poza zakresem |
|---|---|
| Przeglądanie przez studentów dostępnych terminów konsultacji. | Rzeczywiste wdrożenie systemu na uczelni. |
| Rezerwowanie i odwoływanie konsultacji przez studentów. | Integracja z systemami USOS i innymi systemami uczelnianymi. |
| Zarządzanie harmonogramem konsultacji przez wykładowców. | Obsługa konsultacji online i wideokonferencji. |
| Ustalenie dostępności przez wykładowców. | Aplikacja mobilna |
| Przeglądanie listy zapisanych studentów przez wykładowców | |
| Zarządzanie harmonogramem konsultacji przez wykładowców. | |

### 5. Interesariusze

| ID | Grupa / rola | Potrzeba / cel | Wpływ na projekt | Co trzeba ustalić? |
|---|---|---|---|---|
| INT-01 | Studenci | Szybkie wyszukiwanie terminów i wygodne zapisywanie się na konsultacje. | Wysoki | Czy student może odwołać rezerwację i z jakim wyprzedzeniem? |
| INT-02 | Wykładowcy | Łatwe zarządzanie terminami konsultacji i listą zapisanych studentów. | Wysoki | Czy wykładowca ustala liczbę miejsc i samodzielnie zmienia harmonogram? |
| INT-03 | Administracja uczelni | Usprawnienie organizacji konsultacji i ograniczenie problemów komunikacyjnych. | Średni | Kto będzie administratorem systemu i kto będzie zarządzał kontami użytkowników? |

### 6. Założenia i pytania

| ID | Rodzaj | Treść | Kto potwierdza? | Status |
|---|---|---|---|---|
| ZA-01 | założenie | System będzie dostępny przez przeglądarkę internetową. | Klient / przedstawiciel uczelni | niepotwierdzone |
| ZA-02 | założenie | Studenci i wykładowcy będą korzystać z różnych uprawnień dostępu do systemu. | Klient / przedstawiciel uczelni | niepotwierdzone |
| ZA-03 | założenie | Jeden termin konsultacji nie będzie mógł zostać zarezerwowany przez więcej osób, niż przewiduje limit miejsc. | Wykładowcy | niepotwierdzone |
| ZA-04 | założenie | Wykładowcy będą samodzielnie ustalać i aktualizować dostępne terminy konsultacji. | Wykładowcy | niepotwierdzone |
| ZA-05 | założenie | Studenci będą mogli samodzielnie rezerwować i odwoływać terminy konsultacji. | Studenci | niepotwierdzone |
| PY-01 | pytanie | Czy logowanie do systemu będzie odbywać się za pomocą kont uczelnianych? | Administracja uczelni | otwarte |
| PY-02 | pytanie | Czy system ma automatycznie wysyłać wiadomości e-mail z potwierdzeniem rezerwacji i informacją o jej odwołaniu? | Studenci / wykładowcy | otwarte |
| PY-03 | pytanie | Czy konsultacje będą odbywać się wyłącznie stacjonarnie, czy również online? | Wykładowcy | otwarte |

### 8. Wymagania niefunkcjonalne (WNF)

| ID | Obszar | Wymaganie | Miernik / sposób przyszłej weryfikacji | Źródło |
|---|---|---|---|---|
| WNF-01 | bezpieczeństwo | System musi umożliwiać dostęp do funkcji zgodnie z rolą użytkownika. Student może zarządzać własnymi rezerwacjami, a wykładowca swoim harmonogramem konsultacji. | Testy uprawnień dla kont studenta i wykładowcy, w tym próby dostępu do funkcji niedostępnych dla danej roli. | Założenie projektowe |
| WNF-02 | dostępność | System powinien być dostępny przez przeglądarkę internetową i umożliwiać korzystanie z podstawowych funkcji bez konieczności instalowania dodatkowego oprogramowania. | Test uruchomienia systemu i wykonania rezerwacji w uzgodnionych przeglądarkach internetowych. Lista przeglądarek: do uzgodnienia. | Cel biznesowy projektu |
| WNF-03 | audyt | System powinien rejestrować istotne operacje związane z rezerwacjami, w szczególności ich utworzenie, zmianę i odwołanie, wraz z datą i godziną wykonania operacji. | Test wykonania każdej z wymienionych operacji i sprawdzenie, czy zapis zawiera wymagane informacje. Okres przechowywania zapisów: do uzgodnienia. | Założenie projektowe |
| WNF-04 | wydajność | System powinien wyświetlać listę dostępnych terminów konsultacji w czasie umożliwiającym sprawne korzystanie z aplikacji. | Pomiar czasu wyświetlenia listy terminów w ustalonych warunkach. Maksymalny czas odpowiedzi: do uzgodnienia. | Cel biznesowy projektu |
| WNF-05 | integralność danych | System nie może dopuścić do zarezerwowania tego samego miejsca na konsultację przez więcej niż jednego studenta. | Test równoczesnych prób rezerwacji tego samego miejsca; poprawny wynik to maksymalnie jedna skuteczna rezerwacja. | Założenie projektowe |
| WNF-05 | użyteczność | Interfejs systemu powinien umożliwiać studentowi odnalezienie dostępnego terminu i dokonanie rezerwacji bez konieczności kontaktowania się z wykładowcą poza systemem. | Test użyteczności polegający na wykonaniu rezerwacji przez reprezentatywnych użytkowników. Kryterium zaliczenia i liczba uczestników: do uzgodnienia. | Cel biznesowy projektu |

### 9. Dwa kryteria akceptacji w formacie Dane/Gdy/Wtedy

**KA-01 - Rezerwacja terminu konsultacji**
**Dane:** Student jest zalogowany do systemu i wybrał wykładowcę, który posiada dostępne terminy konsultacji.
**Gdy:** Student wybierze wolny termin konsultacji i zatwierdzi rezerwację.
**Wtedy:** System zapisze rezerwację, wyświetli komunikat potwierdzający oraz zaktualizuje liczbę dostępnych miejsc na wybrany termin.

**KA-02 – Odwołanie rezerwacji konsultacji**
**Dane:** Student jest zalogowany do systemu i posiada aktywną rezerwację na przyszły termin konsultacji.
**Gdy:** Student wybierze swoją rezerwację i potwierdzi jej odwołanie.
**Wtedy:** System anuluje rezerwację, wyświetli komunikat potwierdzający oraz ponownie udostępni zwolnione miejsce innym studentom.

### 11. Rejestr ryzyk

| ID | Ryzyko | Prawdopodobieństwo (N/Ś/W) | Wpływ (N/Ś/W) | Reakcja |
|---|---|---|---|---|
| R-01 | Konflikty rezerwacji wynikające z jednoczesnego wyboru tego samego terminu przez kilku studentów. | Ś | W | Wdrożenie mechanizmu kontroli dostępności i blokowania miejsc podczas zapisywania rezerwacji. |
| R-02 | Niska akceptacja systemu przez studentów i wykładowców. | Ś | W | Zapewnienie intuicyjnego interfejsu, przeprowadzenie testów z użytkownikami oraz przygotowanie instrukcji obsługi. |
| R-03 | Nieautoryzowany dostęp do danych użytkowników i informacji o rezerwacjach. | Ś | W | Zastosowanie uwierzytelniania, kontroli uprawnień oraz odpowiednich mechanizmów ochrony danych. |
| R-04 | Awaria systemu uniemożliwiająca rezerwowanie i odwoływanie konsultacji. | Ś | W | Wdrożenie systemu monitorowania, regularnych kopii zapasowych oraz procedur przywracania działania systemu. |
| R-05 | Zmiany wymagań funkcjonalnych w trakcie realizacji projektu powodujące opóźnienia. | Ś | Ś | Wczesne uzgodnienie wymagań z interesariuszami, określenie priorytetów i kontrolowanie wprowadzanych zmian. |
| PY-04 | pytanie | Czy konsultacje będą miały charakter indywidualny, czy również grupowy? | Wykładowcy | otwarte |
| PY-05 | pytanie | Czy rezerwacje mają być zatwierdzane automatycznie, czy wymagać akceptacji wykładowcy? | Wykładowcy | otwarte |
