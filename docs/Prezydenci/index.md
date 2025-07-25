# Analiza danych wyborów na prezydenta III RP 

utworzone: **02.06.2025**


Cel projektu:
Celem analizy było zrozumienie zmieniających się preferencji wyborców w wyborach prezydenckich w Polsce, ze szczególnym uwzględnieniem:

* wyników procentowych kandydatów w I i II turze,
* wpływu poglądów politycznych, wykształcenia oraz przynależności partyjnej na wyniki,
* długofalowych trendów poparcia dla różnych stron sceny politycznej.


Zakres analizy:

* Porównanie wyników głosowania w I i II turze na przestrzeni 30 lat
* Analiza cech kandydatów: wykształcenie, przynależność partyjna, poglądy polityczne
* Ocena zależności między cechami kandydatów a wynikami wyborów
* Trendy poparcia dla: lewicy, centrum, prawicy, partii i bezpartyjnych


Kluczowe wnioski:

1. Wykształcenie kandydatów:

   * 63% kandydatów posiadało wyższe wykształcenie.
   * Ciekawa korelacja: im niższy poziom wykształcenia, tym **lepszy wynik w II turze**. W I turze brak zależności.

2. Przynależność partyjna:

   * Najwięcej kandydatów było niezależnych (12 osób), ale **najczęściej wygrywali kandydaci partyjni**.
   * Aż 3 prezydentury należały do kandydatów z Prawa i Sprawiedliwości.

3. Poglądy polityczne:

   * Najwięcej kandydatów miało poglądy prawicowe.
   * Największe poparcie dla:

     * Centroprawicy: 70% w 1990 roku (rekord), spadek do 8% w 1995 r.
     * Centrolewicy: 68% w 1995 r. (rekord), najniższe – 18% w 1990 r.

**Trend:** Od 2005 roku rosnące poparcie dla prawicy.

4. Wyniki wyborcze:

   * Największe zwycięstwo w I turze: **Aleksander Kwaśniewski (2000)** – wygrana bez II tury.
   * Największy wynik w II turze: **Lech Wałęsa (74,2%)
   * Zwycięstwo w I turze silnie koreluje z wygraną w II turze – **co sugeruje przewagę silnego pierwszego wrażenia kampanii**.



Technologie i narzędzia:

* **Python**: analiza danych (pandas, numpy)
* **Matplotlib i Seaborn**: wizualizacje
* **Jupyter Notebook**: prezentacja projektu


Umiejętności zaprezentowane w projekcie:

* Przetwarzanie i czyszczenie danych (data wrangling)
* Łączenie danych z różnych źródeł (kandydaci + wyniki + partie)
* Eksploracyjna analiza danych (EDA)
* Wizualizacja trendów politycznych
* Wnioskowanie i komunikacja danych w sposób przystępny




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