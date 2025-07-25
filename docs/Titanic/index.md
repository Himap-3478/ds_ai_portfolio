
# Analiza Danych EDA Titanica: Eksploracja Domenowa

utworzone: **28.01.2025**


### 🎯 **Cel projektu:**

Celem analizy było zrozumienie, jakie czynniki mogły mieć wpływ na przeżycie pasażerów słynnego rejsu RMS Titanic. Skoncentrowałem się na eksploracji danych demograficznych, klasowych i logistycznych w celu wyciągnięcia wartościowych wniosków oraz wizualizacji statystycznych zależności.


Zakres analizy:

* Czyszczenie i analiza jakości danych
* Eksploracja zmiennych: wiek, płeć, klasa, port zaokrętowania, liczba członków rodziny
* Wykresy: heatmapy, histogramy, wykresy słupkowe, rozkłady przeżywalności
* Weryfikacja hipotez nt. czynników wpływających na przeżycie


Najciekawsze wnioski:

* **Port zaokrętowania**: Najwięcej pasażerów wsiadło w Southampton, najmniej w Queenstown.
* **Klasa podróży**: Dominowała 3. klasa, co koreluje z niższym wskaźnikiem przeżycia.
* **Śmiertelność**: Więcej pasażerów zginęło niż przeżyło – najczęściej byli to **młodzi mężczyźni z niższych klas**.
* **Wiek**: Większość pasażerów miała mniej niż 30 lat; osoby starsze stanowiły mniejszość.
* **Rodzina na pokładzie**: Zdecydowana większość pasażerów podróżowała samotnie lub bez członków rodziny.
* **Szalupy ratunkowe**: Tylko 27 szalup – zbyt mało, by uratować wszystkich. Szalupy były **nierównomiernie napełnione** – niektóre zawierały zaledwie kilka osób, co mogło wynikać z paniki i braku przeszkolenia załogi.

**Insight**: Pasażerowie płci żeńskiej i dzieci z wyższych klas mieli wyraźnie większe szanse przeżycia. To potwierdza zasadę "kobiety i dzieci pierwsi", choć nie została ona egzekwowana jednolicie.


Technologie i narzędzia:

* **Python** – eksploracja danych
* **Pandas, NumPy** – przygotowanie i manipulacja danymi
* **Seaborn, Matplotlib** – wykresy i heatmapy
* **Jupyter Notebook** – prezentacja analizy i wniosków


Umiejętności zaprezentowane:

* Czyszczenie i eksploracja danych (EDA)
* Wizualizacja danych i rozkładów
* Analiza zależności między zmiennymi (np. klasa a przeżycie)
* Wnioskowanie na podstawie danych historycznych



<a href="Titanic.ipynb" class="md-button md-button--primary">Pobierz Notebook</a>

<iframe
    id="content"
    src="Titanic.html"
    width="100%"
    style="border:1px solid black;overflow:hidden;"
></iframe>
<script>
function resizeIframeToFitContent(iframe) {
    iframe.style.height = (iframe.contentWindow.document.documentElement.scrollHeight + 50) + "px";
    iframe.contentDocument.body.style["overflow"] = 'hidden';
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
