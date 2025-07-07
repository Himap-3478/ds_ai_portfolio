
# Analiza Danych EDA Titanica: Eksploracja Domenowa

utworzone: **28.01.2025**

Zapraszam do zapoznania się z projektem mojego autorstwa, który przenosi nas w świat analizy danych ostatniego rejsu Titanica za pomocą eksploracji domenowej (EDA). W tym projekcie znajdziesz mnóstwo trafnych wniosków i ciekawych obserwacji, które rzucają nowe światło na te najbardziej znaną tragedię morską. 


**Wnioski:**

* Najwięcej osób wyruszyło w rejs w porcie Southampton, następnie w Cherbourg, a najmniej w Queenstown. 
* Najwięcej osób było w 3 klasie, a najmniej w drugiej. 
* Więcej osób zginęło niż przeżyło. W większości były to osoby młode i mężczyżni.
* Zdecydowana większość pasażerów to osoby mlode. Większość osób na pokładzie miała mniej niż 30 lat. Były pojedyncze osoby mające ponad 66 lat
* Większość osób na pokładzie płynęła bez rodziny lub/i małżonka.
* Szalupy były nierównomiernie napełnione w niektórych było kilkanaście osób, a w innych tylko kilka osób. Co wynikało z tego że szalup ratunkowych było tylko 27, czyli o wiele za mało aby uratować chociaż połowę pasażerów.


**Umiejętności:**

* Jupyter Notebook
* SQL 
* EDA
* seaborn
* matplotlib
* Markdown
* Analiza danych
* Wizualizacja
* Analityczne i krytyczne myślenie
* Wyciąganie logicznych wniosków


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
