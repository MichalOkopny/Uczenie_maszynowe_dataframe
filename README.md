
# Analiza Regresji Liniowej w Pythonie

### Opis projektu

W ramach tego projektu przeprowadzana jest analiza regresji liniowej dla czterech par zmiennych \\( (x_i, y_i) \\). 
Celem jest zrozumienie zależności między zmiennymi oraz wizualizacja wyników na wykresach rozrzutu z linią regresji.

### Funkcjonalności

1. **Podstawowe statystyki**:
   - Średnie wartości \\(x\\) i \\(y\\),
   - Wariancje \\(x\\) i \\(y\\),
   - Współczynniki korelacji.

2. **Analiza regresji liniowej**:
   - Obliczenie równania regresji \\(y = ax + b\\),
   - Wyznaczenie współczynnika determinacji \\(R^2\\).

3. **Wizualizacja wyników**:
   - Wykresy rozrzutu z nałożoną linią regresji dla każdej pary zmiennych.

4. **Interaktywność**:
   - Wykresy wyświetlane są pojedynczo, aby umożliwić użytkownikowi opisanie każdego z nich przed przejściem do następnego.

---

### Struktura danych

Plik wejściowy powinien być w formacie CSV i zawierać następujące kolumny:
- `x1`, `y1`, `x2`, `y2`, `x3`, `y3`, `x4`, `y4`.

Przykładowe dane:
| x1   | y1   | x2   | y2   | x3   | y3    | x4   | y4   |
|------|------|------|------|------|-------|------|------|
| 10.0 | 8.04 | 10.0 | 9.14 | 10.0 | 7.46  | 8.0  | 6.58 |
| 8.0  | 6.95 | 8.0  | 8.14 | 8.0  | 6.77  | 8.0  | 5.76 |

---

### Wymagania

- Python 3.8+
- Zainstalowane biblioteki:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `statsmodels`

Aby zainstalować wymagane biblioteki, użyj polecenia:

```bash
pip install -r requirements.txt
