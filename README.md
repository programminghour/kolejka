# kolejka
do poprawy

AL_01_02 - KOLEJKA

W spokojnym na ogół Lesie Przedziałowym wybuchło ostatnio zamieszanie. Było ono spowodowane promocją na bilety do ZOO. 
Każde zwierzę chciało jak najszybciej kupić bilet, jako że zostało ich już niewiele. Jak wiadomo, w lesie panuje prawo dżungli - 
wygrywa silniejszy. Kolejka do kasy z biletami nie działa więc na zasadzie FIFO (First In First Out). 
Jej działanie wyjaśnimy na przykładzie.

Do pustej kolejki wchodzi sobie zając. Lis okazał się być wolniejszy i doszedł trochę później. 
Ale czemu miałby stanać za zającem, skoro może go wyrzucić z kolejki i zająć jego miejsce? Pierwsze miejsce zajmuje zatem lis. 
Następnie dochodzi inny zając i widząc potężnego lisa musi stanąć za nim. Nagle z krzaków wyłania się kolejny zając. 
Widząc swojego pobratymca zastanawia się czy dałby radę wygonić go z kolejki, 
ale postanawia nie ryzykować przegranej i staje za nim. W końcu doczłapał się i niedźwiedź. Zające same uciekły z kolejki, 
a jednym ruchem łapy niedźwiedź wyeliminował i lisa, zajmując pierwsze miejsce. 
Do kasy dochodziły nowe i nowe zwierzęta zajmując odpowiednie miejsce pozbywając się słabszej konkurencji.

Twoim zadaniem jest wyświetlenie ostatecznej kolejki do kasy z biletami.

Uwaga: Kasa zostaje otwarta dopiero po utworzeniu ostatecznej kolejki, 
więc żadne zwierzę nie odchodzi od kasy w trakcie formowania się kolejki.

WEJŚCIE

W pierwszej linii znajduje się liczba testów t (t<106). Każda z następnych t linii zawiera ciąg znaków (a..z, A..Z) 
oznaczających siłę kolejnych zwierząt ustawiających się w kolejce ('a'<'z', 'a'>'A', początek kolejki jest po lewej stronie). 
Długość ciągu n nie przekracza 106 oraz t*n<107.

WYJŚCIE

Dla każdego testu jedna linia opisująca ostateczną kolejność zwierząt.
Przykład

WEJŚCIE:
2
klkkn
klKKnNLlNL

WYJŚCIE:
n
nlNL

