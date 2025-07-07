# Analiza danych wyborów na prezydenta III RP 

utworzone: **02.06.2025**

W ramach własnej analizy danych prześledziłem wyniki wyborów na Prezydenta RP na przestrzeni lat, koncentrując się na trzech kluczowych aspektach:

🔹 Procent głosów oddanych na poszczególnych kandydatów w danym roku w pierwszej i drugiej turze
🔹 Wykształcenie, partia i poglądy kandydatów 

**Wnioski:**

* Kandydaci mają najczęściej wykształcecie wyższe (63)
* Najwięcej kandydatów nie należało do żadnej partii (12)
* Najwięcej kandydatów miało poglądy prawicowe
* W pierwszej turze najwięcej głosów miał A. Kwaśniewski w 2000 roku, wygrywając wybory w pierwszej turze. 
* Najwięcej głosów w II  turze otrzymał L. Wałęsa (74,2%), a najniższe poparcie w I turze miał L. Kaczyński w 2005 roku.
* We większości przypadków, w II turze wygrywało się tylko kilkoma procentami przewagi.
* Zdecydowanie najwięcej prezydentur było z Prawa i Sprawiedliwości (3)
* Najwyższe poparcie do 2012 miała centrolewica, a od 2012 centroprawica. 
* Od 2005 roku prawica zyskuje coraz więcej poparcia. 
* Największe poparcie bo aż 70% miała centroprawica w 1990 roku, aby 5 lat później mieć najmniejsze (8%). 
* Centrolewica najniższe wyniki miała w 1990 roku (18%), ale 5 lat później miała rekordowe 68%. 
* Poglądy lewicowe miały bardzo duży skok poparcia w 2005 roku (15%), a także centrum w 2020 - 16%.
* Jest duża korelacja dodatnia między zwycięstwem w I turze, a zwycięstwem w II turze, co ciekawe im mniej wykształcony kandydat tym zdobywał więcej głosów w II turze mimo, że wykształcenie nie ma wpływu na głosy oddane w I turze. 
* Poglądy nie mają większego znaczenia w wyborach, za to przynależność do partii politycznej ma ogromne.


**Umiejętności:**

* Python
* pandas 
* matplotlib
* seaborn
* numpy
* sklearn
* plotly
* EDA i ETL
* Myślenie analityczne
* Wyciąganie trafnych wniosków
* Wizualizacja



<a href="Prezydenci.ipynb" class="md-button md-button--primary">Pobierz Notebook</a>

<iframe
    id="content"
    src="Prezydenci.html"
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