# Analiza Danych polskich wyborów do Europarlamentu

utworzone: **27.05.2025**

W ramach własnej analizy danych prześledziłem wyniki polskich wyborów do Europarlamentu na przestrzeni lat, koncentrując się na trzech kluczowych aspektach:

🔹 Procent głosów oddanych na poszczególne partie polityczne w danym roku
🔹 Rozkład mandatów w Sejmie i jego zależność od systemu wyborczego
🔹 Poglądy polityczne partii i jak odpowiadają one preferencjom głosujących


📁 Analiza wykonana z użyciem: Python, pandas, matplotlib, seaborn, numpy, plotly, sklearn.

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