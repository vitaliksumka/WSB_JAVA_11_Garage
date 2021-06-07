## Task 11

1. Usuń pole Car car z Human i na jego miejsce wstaw tablicę samochodów o nazwie garage.

2. Popraw konstruktor w Human tak, aby nowo utworzony człowiek posiadał garaż z domyślną liczą pojazdów.

3. Dodaj nowy konstruktor w którym rozmiar garażu będzie (kolejnym?) parametrem.

4. Popraw metody getCar i setCar, żeby przyjmowały jako parametr numer miejsca parkingowego w garażu z którego ma być pobrany samochód lub na które ma być wstawiony samochód.

5. Utwórz metodę, która zwraca sumę wartości pojazdów w garażu. Pole Double value powinno znajdować się w klasie Device.

6. Utwórz metodę sortującą samochody w garażu po roku produkcji od najstarszych do najmłodszych. 

7. Zmień metodę Car.sell(Human seller, Human buyer, Double price) tak, aby zawierała:

- sprawdzenie, czy sprzedawca posiada samochód w garażu (jeżeli nie, metoda powinna rzucić wyjątek)
- sprawdzenie, czy kupujący posiada wolne miejsce w garażu (jeżeli nie, metoda powinna rzucić wyjątek)
- sprawdzenie, czy kupujący posiada wystarczającą ilość gotówki (jeżeli nie, metoda powinna rzucić wyjątek)
- usunięcie pojazdu z garażu sprzedawcy
- dodanie pojazdu w pierwsze wolne miejsce w garażu kupującego
- wymianę gotówki
- wypisanie informacji jeżeli transakcja zakończyła się sukcesem

8. Sprawdzenie w main wszystkich utworzonych metod, commit, push, link do github.
