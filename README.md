# Teams-PolicyPackage
Hurtowe przypisanie Pakietów zasad dla użytkowników dla licencji nauczyciel/uczeń

W Centrum adminstracyjmym Office 365 wejdź do Użytkownicy>Aktywni użytkownicy. 
Odszukaj z menu nad listą użytków: Eksportuj użytkowników i pobierz plik do folderu. 
Zapisz go pod nazwą lista.csv
Umieść w tym samym katalogu.

W skrypcie sprawdź wartości:

$plik = "lista.csv"

$licencja_naucz_1 = "Office 365 A1 dla nauczycieli lub wykładowców"

$licencja_naucz_2 = "Microsoft Power Automate Free+Office 365 A1 dla nauczycieli lub wykładowców"

$licencja_uczen_1 = "Office 365 A1 dla uczniów lub studentów"

$licencja_uczen_2 = "Office 365 A1 dla uczniów lub studentów+Microsoft Power Automate Free"

nazwy licencji mogą się różnić np. wersja Pl En itp. Dostosój je na podstawie Twojego pliku CSV.

Uruchom skryp i poczekaj :)
