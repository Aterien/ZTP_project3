Generalnie bardzo dobre rozwiązanie z drobnymi usterkami i błędami [-1.5 pkt]:

- Sugeruję unikaćp rzechowywania danych dla poszczególnych lat na osobnych zmiennych gdyż przy zmianie lat lub ich liczby trzeba zmieniać nazwy zmiennych i kod w wielu miejscach. Lepiej przechowywać je na liście lub w słowniku.

- Zamiast używania pętli w wielu przypadkach łatwiejsze i szybsze jest użycie odpowiednich metod z pandas, np. DataFrame.to_dict do tworzenia słownika, DataFrame.replace do mapowania zamiast używania pętli, itd.

- Brak 3 stacji obecnych w danych: jednej w Gdańsku i dwóch w Szczecinie (błąd przy budowie słownika do mapowania stacji)

- Błąd przy poprawianiu pomiarów dokonywanych o północy: przesunięcie ich o cały dzień powoduje zmianę kolejności pomiarów; pomiar taki będzie traktowany jako pierwszy a nie ostatni danego dnia.

- Błędy w interpretacji wykresu w zad. 2

- Brak etykiety dla osi Y w zad. 3 i zad. 4 (tu również osi X).

- W zad. 4, przekroczenie należy liczyć w stosunku do średniej dobowej a nie maksymalnej wartości, ale rozumiem, że nie było to wprost napisane w treści zadania a jedynie w odnośniku.

- Projekt wysłany po terminie!!! [-1 pkt]
