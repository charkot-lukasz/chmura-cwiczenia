
# D4. Bezpieczeństwo repozytorium
W repozytorium nie wolno przechowywać haseł ani kluczy dostępu, ponieważ osoby nieuprawnione mogłyby je wykorzystać do przejęcia kont, systemów lub danych.
Samo usunięcie pliku z hasłem nie wystarcza, ponieważ Git przechowuje historię zmian, w której nadal mogą znajdować się poufne informacje.
Osoba mająca dostęp do historii repozytorium może odzyskać usunięte hasło lub klucz.
W przypadku ujawnienia danych dostępowych należy natychmiast je unieważnić lub zmienić oraz usunąć je z historii repozytorium.
Do bezpiecznego przechowywania sekretów należy używać np. GitHub Actions Secrets lub dedykowanych menedżerów sekretów.
