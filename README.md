# Python-MachineLearning

### Ideą projektu jest zastosowanie perceptronu do klasyfikacji liter alfabetu oraz demonstrację wpływu uszkodzeń danych na wyniki klasyfikacji.

## Wczytanie danych z pliku
<img width="655" alt="Zrzut ekranu 2023-06-1 o 22 29 13" src="https://github.com/AnxDaczkowska51/Python-MachineLearning/assets/117481394/2f39abbd-0ddd-47d8-ae8e-0ed0d32409e1">

### Powyższy fragment kodu przedstawia wczytanie danych z pliku letters.data do zmiennej, oraz przypisanie do zbioru X pierwszych 35 wartości z 10 wybranych wierszy.


## Zawartość X:
<img width="692" alt="Zrzut ekranu 2023-06-1 o 22 38 32" src="https://github.com/AnxDaczkowska51/Python-MachineLearning/assets/117481394/73b331e9-4459-4d01-9e92-47fe22e8173e">


## Wypełnianie zbioru y:
<img width="402" alt="Zrzut ekranu 2023-06-1 o 22 41 54" src="https://github.com/AnxDaczkowska51/Python-MachineLearning/assets/117481394/30483efa-fa44-4c83-9481-30a3e4bdf35b">

### Zbiór wartości oczekiwanych o wymiarach 10x10 został wypełniony wartościami -1 wszędzie poza główną przekątną.


## Zawartość y:
<img width="346" alt="Zrzut ekranu 2023-06-1 o 22 46 32" src="https://github.com/AnxDaczkowska51/Python-MachineLearning/assets/117481394/106e469b-218b-47d6-bfb1-09699daf8dca">


## Utworzenie obiektu klasy SLP o nazwie net
<img width="483" alt="Zrzut ekranu 2023-06-1 o 22 49 16" src="https://github.com/AnxDaczkowska51/Python-MachineLearning/assets/117481394/4fcd90a2-1f8a-4c3c-9111-36b9590792a3">


## Wyświetlenie danych ze zbioru X:
<img width="721" alt="Zrzut ekranu 2023-06-1 o 22 51 22" src="https://github.com/AnxDaczkowska51/Python-MachineLearning/assets/117481394/0e693438-ed2a-43b5-8ba5-3ff5a333498d">


## Uczenie modelu za pomocą metody fit(X, y):
<img width="517" alt="Zrzut ekranu 2023-06-1 o 22 53 54" src="https://github.com/AnxDaczkowska51/Python-MachineLearning/assets/117481394/81246c46-4bd9-4dc9-b91c-cf2064e611b6">


## Wynik predict() dla zbioru uczącego X:
<img width="505" alt="Zrzut ekranu 2023-06-1 o 22 56 52" src="https://github.com/AnxDaczkowska51/Python-MachineLearning/assets/117481394/e7fddc6b-b9de-4297-a12f-a9bd31071c92">


## Wynik działania metody misclassified(X,y):
<img width="451" alt="Zrzut ekranu 2023-06-1 o 23 02 38" src="https://github.com/AnxDaczkowska51/Python-MachineLearning/assets/117481394/9a20eba6-e9c1-4973-bdc0-fdc0aa5576f0">


## Funkcja damage() uszkadzająca dany % litery ze zbioru X:
<img width="757" alt="Zrzut ekranu 2023-06-1 o 23 06 47" src="https://github.com/AnxDaczkowska51/Python-MachineLearning/assets/117481394/9adf216a-7f48-4f80-91eb-aa37c1e2c19e">


## Zawartość zbioru X po uszkodzeniu 5%:
<img width="718" alt="Zrzut ekranu 2023-06-1 o 23 11 38" src="https://github.com/AnxDaczkowska51/Python-MachineLearning/assets/117481394/b1fa7b15-065c-4fec-b9b3-161f09f451db">


## Wynik predict() i liczba błędnie sklasyfikowanych liter dla zbioru z 5% uszkodzeniem:
<img width="554" alt="Zrzut ekranu 2023-06-1 o 23 13 19" src="https://github.com/AnxDaczkowska51/Python-MachineLearning/assets/117481394/0ba048ad-d4c7-4082-9114-27e3385a44b0">


## Zawartość zbioru X po uszkodzeniu 15%:
<img width="752" alt="Zrzut ekranu 2023-06-1 o 23 17 54" src="https://github.com/AnxDaczkowska51/Python-MachineLearning/assets/117481394/531333b9-d489-4c7f-87f0-8f7802841c3b">


## Wynik predict() i liczba błędnie sklasyfikowanych liter dla zbioru z 15% uszkodzeniem:
<img width="539" alt="Zrzut ekranu 2023-06-1 o 23 19 10" src="https://github.com/AnxDaczkowska51/Python-MachineLearning/assets/117481394/def40119-75a3-4ecf-9b7c-c1e8b5e782ae">


## Zawartość zbioru X po uszkodzeniu 40%:
<img width="746" alt="Zrzut ekranu 2023-06-1 o 23 22 22" src="https://github.com/AnxDaczkowska51/Python-MachineLearning/assets/117481394/f35cc9ee-4b1f-4d22-b573-9a78bbda63b5">


## Wynik predict() i liczba błędnie sklasyfikowanych liter dla zbioru z 40% uszkodzeniem:
<img width="559" alt="Zrzut ekranu 2023-06-1 o 23 23 37" src="https://github.com/AnxDaczkowska51/Python-MachineLearning/assets/117481394/b65355e3-f790-42a3-9ce9-9bfa087f2d54">



