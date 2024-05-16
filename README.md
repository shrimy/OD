# Problem najkrótszych dróg w kontekście sieci komputerowych

## Opis
Ten program został napisany w języku Python i implementuje algorytmy do wyznaczania najkrótszych ścieżek w grafach skierowanych z wagami na krawędziach. Wykorzystuje bibliotekę NetworkX do generowania grafów oraz algorytmy Dijkstry, Forda-Bellmana-Moora i Floyda-Warshalla.

## Funkcje programu

1. **Generowanie grafu:** Program umożliwia generowanie losowych grafów skierowanych z wagami na krawędziach na podstawie podanej liczby wierzchołków i krawędzi.

2. **Macierz wag:** Generuje i wyświetla macierz wag dla wygenerowanego grafu.

3. **Rysowanie grafu:** Rysuje wygenerowany graf wraz z krawędziami i wagami.

4. **Algorytmy najkrótszych ścieżek:**
    - **Algorytm Dijkstry:** Wyznacza najkrótsze ścieżki z danego wierzchołka startowego do pozostałych wierzchołków.
    - **Algorytm Forda-Bellmana-Moora:** Wyznacza najkrótsze ścieżki z danego wierzchołka startowego do pozostałych wierzchołków.
    - **Algorytm Floyda-Warshalla:** Wyznacza najkrótsze ścieżki między wszystkimi parami wierzchołków.

## Instrukcja użycia

1. Uruchom program za pomocą interpretera języka Python.
2. Podaj liczbę wierzchołków oraz liczbę krawędzi grafu.
3. Wyświetlona zostanie macierz incydencji oraz graf wraz z krawędziami i wagami.
4. Program przeprowadzi pomiary czasu wykonania dla każdego z algorytmów i wyświetli wyniki.

## Wymagane biblioteki

- `networkx`
- `matplotlib`
- `numpy`

## Autor

- Autorzy: Patryk Ryba, Mateusz Rzeźnikiewicz
