# Analiza Danych polskich wyborów do Europarlamentu

utworzone: **27.05.2025**

W ramach własnej analizy danych prześledziłem wyniki polskich wyborów do Europarlamentu na przestrzeni lat, koncentrując się na trzech kluczowych aspektach:

🔹 Procent głosów oddanych na poszczególne partie polityczne w danym roku
🔹 Rozkład mandatów w Parlaemncie Europejskim i jego zależność od systemu wyborczego
🔹 Poglądy polityczne partii i jak odpowiadają one preferencjom głosujących


**Wnioski:**

*Najlepsze i najgorzesz wyniki danych poglądów:
- prawica: najlepszy: rok 2014 - 47,47%; najgorszy: rok 2019 - 4,63%
- centroprawica: najlepszy: rok 2015 - 49,07%; najgorszy: rok 2004 - 24,10%
- centrum: najlepszy: rok 2004 - 18,11%; najgorszy: rok 2019 - 0,54%
- centrolewica: najlepszy: rok 2023 - 38,47%; najgorszy: do roku 2014 - 0%
- lewica: najlepszy: rok 2004 - 27,26%; najgorszy: rok 2024 - 6,03%
* Jeżeli chodzi o najlepsze wyniki partii politycznych to największe poparcie miało Prawo i Sprawiedliwość w roku 2019 (45,38%), a najmniejszym poparciem cieszyła się Socjaldemokracja Polska w 2004 roku (5,33%).
* Rekord posiadanych mandatów należy do Prawa i Sprawiedliwości w latach 2019-2024 (27 mandatów).
* Najmniej mandatów (3) miały: Socjaldemokracja Polska (2004), Polskie Stronnictwo Ludowe (2009), Wiosna (2019), Trzecia Droga i Lewica (2024).
* Najdłużej w Europarlamencie była partia: Platforma Obywatelska oraz Prawo i Sprawiedliwość bo aż 5 kadencji. 
* W latach 2014-2019 liczba mandatów PO i PIS była równa i wynosiła po 19 mandatów. 
* Najwięcej polskich partii w Europarlamencie było w latach 2004-2009 bo, aż 8. Za to najmniej w latach 2019-2024 bo tylko 3 partie.


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


<a href="Europarlament_pl.ipynb" class="md-button md-button--primary">Pobierz Notebook</a>

<iframe
    id="content"
    src="Europarlament.html"
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