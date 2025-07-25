# Analiza Danych Irysów: Eksploracja Domenowa

Utworzone: **25.01.2025**


### 🎯 **Cel projektu:**

Celem projektu była eksploracja klasycznego zbioru danych **Iris**, obejmującego trzy gatunki kwiatów: *Setosa*, *Versicolor* i *Virginica*. Analiza miała na celu odkrycie zależności między zmiennymi (cechami fizycznymi) kwiatów oraz zrozumienie różnic pomiędzy gatunkami.


Zakres analizy:

* Wczytanie i wstępne oczyszczenie danych
* Analiza rozkładów zmiennych: długości i szerokości kielicha oraz płatka
* Obliczenie korelacji między cechami
* Wizualizacja danych za pomocą parplotów, heatmap i wykresów pudełkowych
* Wyciągnięcie obserwacji biologiczno-statystycznych dla każdego z gatunków


Najciekawsze wnioski:

**Iris Virginica** *(największy z kwiatów)*:

* Im dłuższy płatek, tym dłuższy kielich → **silna dodatnia korelacja**
* Największe średnie wartości długości i szerokości wśród wszystkich gatunków

**Iris Versicolor**:

* Wraz z długością płatka rosną zarówno długość kielicha, jak i szerokość płatka
* **Szerokość kielicha wpływa na szerokość płatka** – interesująca korelacja między "obwodami"

**Iris Setosa** *(najmniejszy gatunek)*:

* Wzrost szerokości kielicha wiąże się z większą długością kielicha
* Najniższe wartości cech fizycznych – dobrze odseparowane od pozostałych gatunków (widoczne na wykresach klastra)

**Insight**: Różnice między gatunkami są na tyle wyraźne, że można je rozpoznać nawet na podstawie prostych wykresów 2D. To tłumaczy, dlaczego ten zbiór jest tak często wykorzystywany do uczenia modeli klasyfikacyjnych.


Technologie i narzędzia:

* **Python** – eksploracja i analiza danych
* **Pandas, NumPy** – manipulacja danymi
* **Seaborn, Matplotlib** – wizualizacje
* **Jupyter Notebook** – dokumentacja i narracja analizy


Umiejętności zaprezentowane:

* Eksploracyjna analiza danych (EDA)
* Analiza korelacji między zmiennymi
* Tworzenie estetycznych i informatywnych wizualizacji
* Formułowanie precyzyjnych wniosków na podstawie danych liczbowych



<a href="irysy.ipynb" download class="md-button md-button--primary">Pobierz Notebook</a>

<iframe
    id="content"
    src="irysy.html"
    width="100%"
    style="border:1px solid black;overflow:hidden;"
></iframe>

<script>
function resizeIframeToFitContent(iframe) {
    iframe.onload = function() {
        iframe.style.height = (iframe.contentWindow.document.documentElement.scrollHeight + 50) + "px";
        iframe.contentDocument.body.style["overflow"] = 'hidden';
    };
}
window.addEventListener('load', function() {
    var iframe = document.getElementById('content');
    resizeIframeToFitContent(iframe);
});
window.addEventListener('resize', function() {
    var iframe = document.getElementById('content');
    resizeIframeToFitContent(iframe);
});
</script>
