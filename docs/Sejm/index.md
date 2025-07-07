# Analiza danych wyborów do Sejmu III RP

utworzone: **19.05.2025**

W ramach własnej analizy danych prześledziłem wyniki polskich wyborów do Sejmu na przestrzeni lat, koncentrując się na trzech kluczowych aspektach:

🔹 Procent głosów oddanych na poszczególne partie polityczne w danym roku
🔹 Rozkład mandatów w Sejmie i jego zależność od systemu wyborczego
🔹 Poglądy polityczne partii i jak odpowiadają one preferencjom głosujących


**Wnioski:**

* Rekord posiadanych mandatów należy do Prawa i Sprawiedliwości w latach 2015-2019 oraz 2019-2023 (235 mandatów). 
* Najdłużej w Sejmie była partia: Polskie Stronnictwo Ludowe bo aż 10 kadencji (Od 2023 do 2025 skład Trzeciej Drogi), zaraz za nią jest Mniejszość Niemiecka, która była w Sejmie 9 kadencji. 
* Od 2001 roku w Sejmie obecne są dwie największe partie polityczne: Platforma (Koalicja) Obywatelska oraz Prawo i Sprawiedliwość. 
* Najwięcej partii było w Sejmie w latach 1991-1993 bo aż 28 partii i koitetów wyborczych. A najmniej w obecnej kadencji (5 partii/koalicji).
* Największe poparcie miało Prawo i Sprawiedliwość w roku 2019 (43,59%), a najmniejsze poparcie miał Sojusz Kobiet Przeciw Trudnościom Życia w 1991 roku (0,02%)
* W 2015 roku centroprawica cieszyła się najwyższym - 59% - poparciem. Najgorsze poparcie miały poglądy centrolewicowe w 2011 roku (0%). Centrum od 1997 praktycznie nie istnieje na scenie politycznej, podobnie jak centrolewica od 2005 do 2010.
* Najlepsze i najgorsze wyniki poszczególnych poglądów:
- prawica: najlepszy: rok 2005 - 38,28%; najgorszy: rok 2015 - 4,88%
- centroprawica: najlepszy: rok 2015 - 59,39%; najgorszy: rok 2001 - 21,66%
- centrum: najlepszy: rok 1991 - 10,45%; najgorszy: rok 2011 - 0,19%
- centrolewica: najlepszy: rok 2023 - 30,69%; najgorszy: rok 2011 - 0%
- lewica: najlepszy: rok 2001 - 51,34%; najgorszy: rok 2023 - 8,72%


**Umiejętności:**
* Python
* pandas
* matplotlib 
* seaborn 
* numpy
* plotly
* sklearn
* Wizualizacja
* Umiejętność wyciągania trafnych wniosków
* Analityczne i krytyczne myślenie


<a href="Sejm.ipynb" class="md-button md-button--primary">Pobierz Notebook</a>

<iframe
    id="content"
    src="Sejm.html"
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