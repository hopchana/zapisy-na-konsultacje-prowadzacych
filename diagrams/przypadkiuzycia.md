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
-A1 - Aktorem jest wykładowca:System pomija punkt 2 i 3 przechodząc do punktu 4 przebiegu podstawowego.

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



**UC-03** Przypomnienie o konsultacjach. <br>
**Aktor główny:** Student <br>
**Warunki wstępne:** Student pomyślnie zapisał się na konsultacje <br>
**Wyzwalacz:** Przypomnienie wysyłane 24 godziny przed terminem <br>

**Przebieg podstawowy:** 
1. System pobiera dane o konsultacjach.
2. System generuje przypomnienie z datą i godziną konsultacji.
3. System wysyła wiadomość do studenta z informacją o nadchodzącej konsultacji.
4. System potwierdza wysłanie przypomnienia
**Przebieg alternatywny:**
-A1 - 

**Warunek końcowy**: Student otrzymuje przypomnienie o nadchodzących konsultacjach.
