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
| PY-01 | pytanie | Czy logowanie do systemu będzie odbywać się za pomocą kont uczelnianych? | Administracja uczelni | otwarte |
| PY-01 | pytanie | Czy system ma automatycznie wysyłać wiadomości e-mail z potwierdzeniem rezerwacji i informacją o jej odwołaniu? | Studenci / wykładowcy | otwarte |
| PY-01 | pytanie | Czy konsultacje będą odbywać się wyłącznie stacjonarnie, czy również online? | Wykładowcy | otwarte |

### 7. Wymagania funcjonalne (WF)

| ID | Treść | Priorytet | Źródło | Kryterium akceptacji / uwagi |
|---|---|---|---|---|
| WF-1 | System pozwala studentom na zapoznanie się z dostępnymi terminami konsutacji |Wysoki|||  
| WF-2 | Student może zapisać się na konsultacje z zajęć na które jest zapisany | Wysoki ||
| WF-3 | Student może odwołać swoją obecność na konsultacjach | Wysoki ||
| WF-4 | Student otrzymuje przypomnienie o nadchodzących konultacjach drogą mailową | Średni | Analiza wymagań ||
| WF-5 | Wykładowca może przeglądać harmonogram konsultacji|Wysoki|Wymagania klienta||
| WF-5 | Wykładowca dodaje terminy konsultacji | Wysoki ||
| WF-6 | Wykładowca ma możliwość edycji terminów swoich spotkań | Wysoki ||
| WF-7 | Wykładowca może odwołać zaplanowane konsultacje | Wysoki ||





