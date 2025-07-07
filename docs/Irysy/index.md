# Analiza Danych Irysów: Eksploracja Domenowa

Utworzone: **25.01.2025**

Zapraszam do zapoznania się z projektem mojego autorstwa, który przenosi nas w świat analizy danych irysów za pomocą eksploracji domenowej (EDA). W tym projekcie znajdziesz mnóstwo trafnych wniosków i ciekawych obserwacji, które rzucają nowe światło na te piękne kwiaty. Przygotuj się na fascynującą podróż przez dane, która z pewnością wzbogaci Twoją wiedzę i zainspiruje do dalszych badań.


**Wnioski:**

* Iris virginica: kiedy wzrasta długość płatka to wzrasta także długością kielicha. Jest to też największa odmiana Irysa
* Iris versicolor: kiedy wzrasta długość płatka, wzrasta długość kielicha i szerokość płatka. Gdy wzrasta szerokość kielicha to wzrasta szerokość płatka.
* Iris setosa: kiedy wzrasta szerokość kielicha, to wzrasta także długość kielicha. Jest to najmniejsza odmiana Irysa


**Umiejętności:**
* Jupyter Notebook
* EDA
* seaborn
* matplotlib
* Markdown
* Analiza danych
* Wizualizacja
* Analityczne i krytyczne myślenie
* Wyciąganie logicznych wniosków



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
