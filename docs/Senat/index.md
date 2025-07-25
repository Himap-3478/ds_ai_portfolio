# Analiza danych wyborów do Senatu III RP

utworzone: **22.05.2025**


Cel projektu:

Projekt miał na celu analizę danych z wyborów do Senatu RP z ostatnich 30 lat, by zrozumieć:

* jak zmieniało się poparcie społeczne dla partii politycznych,
* jak system większościowy wpływał na rozkład mandatów,
* jak odpowiadały wyniki wyborów preferencjom ideologicznym Polaków.


Zakres analizy:

* Zebranie i standaryzacja danych z wyborów do Senatu z lat 1991–2023
* Przypisanie partii do kategorii ideologicznych (prawica, centroprawica, centrum, centrolewica, lewica)
* Porównanie udziału głosów i mandatów partii w każdej kadencji
* Analiza wpływu systemu wyborczego (większościowego) na reprezentację mniejszych ugrupowań
* Wyodrębnienie trendów dotyczących dominacji politycznej i polaryzacji sceny senackiej


Wnioski

Struktura i udział partii:

* **Rekordzistą startów do Senatu** jest *Mniejszość Niemiecka* – 10 razy.
* Najwięcej partii o poglądach:

  * **Centroprawicowych** – 56 ugrupowań
  * **Centrowych** – 42
  * **Prawicowych** – 41

Mandaty i dominacja polityczna:

* **Rekord mandatów**: *SLD-UP (2001–2005)* – 75 mandatów.
* Najdłuższa obecność: *Polskie Stronnictwo Ludowe* – 8 kadencji.
* Od 2001 roku: **PO i PiS nieprzerwanie obecne w Senacie.**

Zmienność polityczna:

* **Najwięcej partii w Senacie**: kadencja 1991–1993 (28 partii/komitetów)
* **Najmniej**: kadencja 2007–2011 (tylko 3 ugrupowania)
* Od 2007 do 2023 scena senacka **zdominowana przez PO i PiS**

Preferencje ideologiczne społeczeństwa:

| Poglądy           | Najlepszy wynik | Najgorszy wynik |
| ----------------- | --------------- | --------------- |
| **Prawica**       | 17,02% (1991)   | 0,93% (2007)    |
| **Centroprawica** | 81,87% (2007)   | 15,71% (2001)   |
| **Centrum**       | 27,64% (2001)   | 0,33% (2007)    |
| **Centrolewica**  | 39,53% (2019)   | 0% (2001, 2007) |
| **Lewica**        | 49,65% (2001)   | 2,46% (2019)    |

**Insight:** System większościowy faworyzuje silne bloki partyjne – od 2007 roku mniejsze partie niemal całkowicie zniknęły z Senatu. Lewica, mimo historycznie wysokich wyników (2001), **zanikła po 2011 roku**. Centroprawica miała rekordowe poparcie (81%) w 2007 r., ale jej siła w Senacie ulega fluktuacji.


Technologie i narzędzia:

* **Python (pandas, matplotlib, seaborn)** – analiza danych, wykresy
* **Jupyter Notebook** – narracja i prezentacja analizy
* **Excel** – standaryzacja danych wejściowych


Umiejętności zaprezentowane:

* Praca z danymi historycznymi i klasyfikacją ideologiczną
* Identyfikacja trendów w systemie większościowym (vs proporcjonalnym)
* Tworzenie syntetycznych wizualizacji wyników politycznych
* Porównawcza analiza wyborcza z elementami socjologicznymi i politologicznymi



<a href="Senat.ipynb" class="md-button md-button--primary">Pobierz Notebook</a>

<iframe
    id="content"
    src="Senat.html"
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