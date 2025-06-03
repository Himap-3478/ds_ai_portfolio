# Analiza danych wyborów na prezydenta III RP 

utworzone: **02.06.2025**

W ramach własnej analizy danych prześledziłem wyniki wyborów na Prezydenta RP na przestrzeni lat, koncentrując się na trzech kluczowych aspektach:

🔹 Procent głosów oddanych na poszczególnych kandydatów w danym roku w pierwszej i drugiej turze
🔹 Wykształcenie i poglądy kandydatów 


📁 Analiza wykonana z użyciem: Python, pandas, matplotlib, seaborn, numpy, plotly, sklearn.

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