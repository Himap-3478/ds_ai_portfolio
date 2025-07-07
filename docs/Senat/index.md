# Analiza danych wyborów do Senatu III RP

utworzone: **22.05.2025**

W ramach własnej analizy danych prześledziłem wyniki polskich wyborów do Senatu na przestrzeni lat, koncentrując się na trzech kluczowych aspektach:

🔹 Procent głosów oddanych na poszczególne partie polityczne w danym roku
🔹 Rozkład mandatów w Sejmie i jego zależność od systemu wyborczego
🔹 Poglądy polityczne partii i jak odpowiadają one preferencjom głosujących


**Wnioski:**

* Najwięcej bo 10 razy Mniejszość Niemiecka startowała do polskiego Senatu.
* Najwięcej partii bo aż 56 miało poglądy centroprawicowe, na drugim miejscu są partie o poglądach centrum (42), podium zamykają partie o poglądach prawicowych (41).
* Rekord posiadanych mandatów należy do SLD-UP w latach 2001-2005 (75 mandatów). 
* Najdłużej w Senacie była partia: Polskie Stronnictwo Ludowe bo aż 8 kadencji. 
* Od 2001 roku w Senacie obecne są dwie największe partie polityczne: Platforma Obywatelska oraz Prawo i Sprawiedliwość. 
* Najwięcej partii było w Senacie w latach 1991-1993 bo aż 28 partii i komitetów wyborczych. A najmniej w 2007-2011 (3 partii/komitety). 
* Od 2007 do 2023 roku w Senacie rządziły praktycznie tylko dwie partie: PO oraz PIS.
* Największe poparcie miało Prawo i Sprawiedliwość w roku 2019 (44,56%), a najmniejsze miała partia Zjednoczeni w 1991 roku (0,06%).
* W 2007 roku centroprawica cieszyła się najwyższym - 81,87% - poparciem. 
* Najgorsze poparcie miały poglądy centrolewicowe w 2001 i 2007 roku (0%). 
* Prawica od 2007 do 2019 praktycznie nie istniała w polski Senacie, podobnie jak centrum od 2005 do 2007.
* Najlepsze i najgorsze wyniki poszczególnych poglądów:
- prawica: najlepszy: rok 1991 - 17,02%; najgorszy: rok 2007 - 0,93%
- centroprawica: najlepszy: rok 2007 - 81,87%; najgorszy: rok 2001 - 15,71%
- centrum: najlepszy: rok 2001 - 27,64%; najgorszy: rok 2007 - 0,33%
- centrolewica: najlepszy: rok 2019 - 39,53%; najgorszy: rok 2001 - 0%
- lewica: najlepszy: rok 2001 - 49,65%; najgorszy: rok 2019 - 2,46%


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