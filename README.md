# projekt-analiza-i-wizualizacja-danych

Informacje o zbiorze danych na których dokonałem analizy i wizualizacji:
Dane pozyskałem ze strony dane.gov.pl. Obejumują one informację o zarejestrowanych pożarach lasów od 2018 do 2022 roku.
Linki do baz danych:
    https://dane.gov.pl/pl/dataset/2634/resource/36240/table?page=1&per_page=20&q=&sort=
    https://dane.gov.pl/pl/dataset/2990/resource/44796,291-rodzaj-pozarow-lasow-w-rozbiciu-na-wojewodztwo-powiat/table?page=1&per_page=20&q=&sort=
    https://dane.gov.pl/pl/dataset/1783/resource/21603,29_1_rodzaj-pozarow-lasow-w-rozbiciu-na-wojewodztwo-powiat/table
    https://dane.gov.pl/pl/dataset/1422/resource/15225,29_1-rodzaj-pozarow-lasow-w-rozbiciu-na-wojewodztwo-powiat/table
    https://dane.gov.pl/pl/dataset/1783/resource/21603,29_1_rodzaj-pozarow-lasow-w-rozbiciu-na-wojewodztwo-powiat/table

Podstawowe inforamcje: W Polsce na przełomie lat 2018-2022 wybuchło ponad 35 000 pożarów leśnych, większość z nich bo, aż około 90% były to pożary pokrywy gleby, resztę pożarów zaliczamy do kategorii ‘podpowierzchniowych’, ‘całkowity drzew’ i ‘pojedyńcze drzewo’.
Definicje pożarów:
- Podpowierzchniowy: Pożar rozwijający się pod ziemią, palący korzenie i materię organiczną pod powierzchnią gleby.
- Pokrywy gleby: Pożar, który obejmuje roślinność na powierzchni ziemi, taką jak suche liście, trawa i niższe gałęzie.
- Całkowity drzew: Intensywny pożar, który sięga koron drzew, paląc gałęzie i liście w koronie.
- Pojedyncze drzewo: Pożar ograniczony do jednego drzewa lub niewielkiej grupy drzew.

O zbiorze danych:
Na zbiór składa się pięć plików CSV, w każdym z nich znajdziemy informację o łącznej liczbie pożarach w Polsce, w danym województwie jak i powiecie w danym roku. Znajdziemy również informacje o tym ile wybuchło pożarów danego rodzaju.
    Nagłówki kolumn to odpowiednio:
    - LP. - numer indeksu liczony od 1,
    - OGÓŁEM - suma wszyskich rodzajów pożaru lasu dla danego miejsca,
    - Podpowierzchniowy - ilość pożarów o tym rodzaju,
    - Pokrywy gleby - ilość pożarów o tym rodzaju,
    - Całkowity drzew - ilość pożarów o tym rodzaju,
    - Pojedyncze drzewo - ilość pożarów o tym rodzaju