# Find friends 

Utworzone: **18.04.2025**


### 📌 **Opis projektu:**

Stworzyłem aplikację opartą na modelu uczenia maszynowego, która analizuje odpowiedzi użytkownika z ankiety i przypisuje go do jednego z wcześniej zdefiniowanych klastrów. Każdy klaster reprezentuje **profil użytkownika o określonym zestawie umiejętności, zainteresowań i doświadczenia zawodowego**.


### ⚙️ **Funkcjonalności aplikacji:**

* **Zbieranie danych:** ankieta online z pytaniami m.in. o znajomość technologii, narzędzi analitycznych, doświadczenie zawodowe, zainteresowania AI.

* **Przetwarzanie danych:**
  * czyszczenie i walidacja danych,
  * kodowanie zmiennych kategorycznych (One-Hot / LabelEncoder),
  * standaryzacja cech (StandardScaler / MinMaxScaler).

* **Model uczenia maszynowego:**
  * klasteryzacja z wykorzystaniem algorytmu **KMeans** (lub innego, np. DBSCAN / HDBSCAN),
  * analiza silosu cech i metryki dystansu do walidacji modelu.

* **Predykcja:**
  * użytkownik otrzymuje wynik – przypisanie do klastra,
  * dodatkowo wyświetlana jest interpretacja cech klastra i jego reprezentantów.

* **Wizualizacja wyników:**
  * dashboard z opisem i cechami poszczególnych klastrów.


Zastosowane technologie:

* **Python**: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`, `streamlit`
* **Uczenie maszynowe**: klasteryzacja (`KMeans`, `silhouette_score`, `PCA`)
* **Preprocessing**: `StandardScaler`, `OneHotEncoder`
* **Aplikacja interfejsu użytkownika**: `Streamlit`


Korzyści i zastosowania:

* Pomaga zrozumieć profil użytkownika na podstawie danych wejściowych
* Może służyć jako system rekomendacji kursów, ścieżek kariery lub ról zawodowych
* Pokazuje znajomość pipeline'u ML, od zbierania danych do zastosowania modelu





<a href="https://github.com/Himap-3478/Find_friends" target="_blank" style="
  display: inline-flex;
  align-items: center;
  padding: 10px 20px;
  font-size: 16px;
  color: white;
  background-color: #24292e;
  border-radius: 5px;
  text-decoration: none;
  font-weight: bold;
">
  <svg height="20" width="20" viewBox="0 0 16 16" fill="white" style="margin-right: 8px;" xmlns="http://www.w3.org/2000/svg">
    <path d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.54 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27s1.36.09 2 .27c1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.28.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.19 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"/>
  </svg>
  Odwiedź repozytorium GitHub
</a>


Tutaj screen z projektu:

![Widok początkowy](image/Find_friends.png)