**UC-01:** Przeglądanie terminów. <br>
**Aktor główny:** Student, Wykładowca. <br>
**Warunki wstępne:** Zalogowany aktor. <br>
**Wyzwalacz:** Aktor wybiera sekcje konsultacji.

**Przebieg podstawowy:**
1. Aktor wybiera podstronę konsultacji.
2. System zwraca listę wykładowców przypisanych do studenta.
3. Student wybiera wykładowcę. 
4. System zwraca harmonogram konsultacji.
5. Aktor zapoznaje się z terminami.

**Przebieg alternatywny:**
2a - Aktorem jest wykładowca:System pomija punkt 2 i 3 przechodząc do punktu 4 przebiegu podstawowego.

**Warunek końcowy**: Aktor uzyskał dostęp do harmonogramu konsultacji na zgodnie z rolą w systemie.


**UC-02** Zapis na konsultacje. <br>
**Aktor główny:** Student. <br>
**Warunki wstępne:** Zalogowany student wybrał dostępny termin konsultacji. <br>
**Wyzwalacz:** Aktor wybiera zapisz się na konsultacje. <br>

**Przebieg podstawowy:**
1. Student wybiera opcje zapisu na konsultacje.
2. System zwraca podsumowanie wybranych konsultacji.
3. Student potwierdza wybór zapisu.
4. System weryfikuje dostępność terminu.
5. System rejestruje konsultacje.
6. System zwraca potwierdzenie zapisu.

**Przebieg alternatywny:**
-A1 - Brak dostępności wybranego terminu:System informuje studenta o niedostępności terminu.

**Warunek końcowy**: Student zostaje poprawnie zapisany na wybrane konsultacje.


**UC-03** Odwołanie obecności na konultacjach. <br>
**Aktor główny:** Student <br>
**Warunki wstępne:** Student pomyślnie zapisał się na konsultacje <br>
**Wyzwalacz:** Student wybiera funkcje odwołania obecności na konsultacjach <br>

**Przebieg podstawowy:** 
1. Student przegląda konsultacje, na które jest zapisany.
2. Student wybiera konsultacje do odwołania.
3. Student wybiera opcje odwołaj konsultację.
4. System zwraca komunikat z prośbą o potwierdzenie odwołania konsultacji.
5. Student potwierdza odwołanie.
6. System zmniejsza liczbę zapisanych studentów na konsultacje.
7. System zwraca potwierdzenie odwołania konsultacji.
**Przebieg alternatywny:**
-A1 - System nie może odwołać obecności z powodu braku potwierdzenia odwołania przez studenta

**Warunek końcowy**: Student odwołuje swoją obecność, a system zmniejsza liczbę osób zapisanych.


**UC-04** Przypomnienie o konsultacjach. <br>
**Aktor główny:** Student <br>
**Warunki wstępne:** Student pomyślnie zapisał się na konsultacje <br>
**Wyzwalacz:** Przypomnienie wysyłane 24 godziny przed terminem <br>

**Przebieg podstawowy:** 
1. System pobiera dane o konsultacjach.
2. System generuje przypomnienie z datą i godziną konsultacji.
3. System wysyła wiadomość do studenta z informacją o nadchodzącej konsultacji.
4. System potwierdza wysłanie przypomnienia
**Przebieg alternatywny:**
-A1 - System nie może wysłać przypomnienia z powodu odwołanych konsultacji przez wykładowcę
-A2 - System nie może wysłać przypomnienia z powodu odwołanej obecności przez studenta

**Warunek końcowy**: Student otrzymuje przypomnienie o nadchodzących konsultacjach.


**UC-05** Dodanie konsultacji <br>
**Aktor główny:** Wykładowca <br>
**Warunki wstępne:** Wykładowca jest zalogowany <br>
**Wyzwalacz:** Wybór funkcji dodaj konsultacje <br>

**Przebieg podstawowy:** 
1. Wykładowca wybiera funkcję dodaj konsultacje.
2. Wypełnia formularz konsultacji.
3. System waliduje formularz.
4. System potwierdza dodanie terminu konsultacji.
**Przebieg alternatywny:**
-A1 - System informuje o błednej walidacji danych 
-A2 - System nie może dodać konsultacji z powodu kolizji terminów

**Warunek końcowy**: Konsultacje zostają dodane do bazy.
