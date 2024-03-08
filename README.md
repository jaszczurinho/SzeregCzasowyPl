# Analiza zobowiązań kredytowych gospodarstw domowych w Kanadzie

To repozytorium zawiera kod Pythona do analizy zobowiązań kredytowych gospodarstw domowych w Kanadzie przy użyciu technik analizy szeregów czasowych. Kod pobiera i przetwarza dane z pliku CSV o nazwie `kanada.csv`, a następnie wykonuje różne analizy i wizualizacje.

## Przegląd kodu

Skrypt Python wykonuje następujące zadania:

1. Odczytanie danych z pliku CSV `kanada.csv` i wstępne ich przetworzenie.
2. Generowanie wizualizacji w celu analizy trendów i wzorców kredytów niehipotecznych:
 - Średni rozkład zaciągniętych kredytów niehipotecznych.
 - Box plot przedstawiający rozkład kredytów niehipotecznych w poszczególnych latach.
 - Box plot przedstawiający całkowitą kwotę kredytu niehipotecznego miesięcznie.
 - Wykres liniowy przedstawiający trend kredytów niehipotecznych w poszczególnych latach.
 - Wykres każdej składowej szeregu czasowego
3. Obliczenie i wyświetlenie danych statystycznych:
 - Wartość średnia i odchylenie standardowe kredytów niehipotecznych w ciągu roku.
4. Stosuje modele prognozowania szeregów czasowych:
 - Model Holta Wintersa do estymacji trendu.
 - Model SARIMA do prognozowania.

## Biblioteki
- pandas
- matplotlib
- seaborn
- statsmodels
- pmdarima
