# Analiza danych wyborów do Sejmu III RP

utworzone: **19.05.2025**

Cel projektu:

Celem analizy było zbadanie, jak zmieniała się struktura polityczna Sejmu w Polsce od 1991 roku – z uwzględnieniem:

* poparcia dla partii politycznych,
* przydziału mandatów (w kontekście systemu wyborczego),
* ewolucji preferencji ideologicznych społeczeństwa.


Zakres analizy:

* Zebranie i oczyszczenie danych z wyborów parlamentarnych (10 kadencji)
* Analiza procentowego poparcia i liczby mandatów zdobytych przez partie polityczne
* Przypisanie partii do kategorii ideologicznych (prawica, centroprawica, centrum, centrolewica, lewica)
* Ocena wpływu systemu d’Hondta na rzeczywistą reprezentację ugrupowań
* Wizualizacja trendów: liczby partii w Sejmie, poparcia społecznego, siły mandatowej


Kluczowe wnioski:

Struktura Sejmu:

* **Rekord mandatów:** *Prawo i Sprawiedliwość* (2015–2023) – 235 mandatów
* **Najdłuższa obecność:** *PSL* – nieprzerwanie od 10 kadencji (w tym jako część Trzeciej Drogi)
* **Największy rozrzut partyjny:** *kadencja 1991–1993* – aż **28 partii i komitetów wyborczych**
* **Największa koncentracja:** *kadencja 2023–2027* – tylko 5 głównych bloków

Trendy polityczne:

* Od 2001 roku dominacja **PiS** i **PO/KO** – tylko te dwa ugrupowania były stale obecne.
* Największe poparcie dla partii: **PiS (2019)** – 43,59%
* Najmniejsze: **Sojusz Kobiet Przeciw Trudnościom Życia (1991)** – 0,02% (!)

Zachowania ideologiczne wyborców:

| Poglądy           | Najlepszy wynik | Najgorszy wynik |
| ----------------- | --------------- | --------------- |
| **Prawica**       | 38,28% (2005)   | 4,88% (2015)    |
| **Centroprawica** | 59,39% (2015)   | 21,66% (2001)   |
| **Centrum**       | 10,45% (1991)   | 0,19% (2011)    |
| **Centrolewica**  | 30,69% (2023)   | 0% (2011)       |
| **Lewica**        | 51,34% (2001)   | 8,72% (2023)    |

**Insight:** Polityczne centrum w Polsce niemal zniknęło po 1997 roku. Od 2005 r. scena jest spolaryzowana: dominacja centroprawicy, a **lewica notuje stały spadek** z historycznego szczytu 51% do zaledwie 8,7% w 2023.


Technologie i narzędzia:

* **Python (pandas, seaborn, matplotlib)** – analiza i wizualizacje danych
* **Excel** – obróbka danych źródłowych
* **Jupyter Notebook** – dokumentacja i narracja analizy


Umiejętności pokazane w projekcie:

* Analiza danych politycznych na przestrzeni wielu lat (longitudinal data analysis)
* Zastosowanie klasyfikacji ideologicznej do analizy społecznej
* Prezentowanie złożonych danych w czytelnej formie
* Przekształcanie danych statystycznych w konkretne wnioski polityczne
* Znajomość systemu wyborczego i jego wpływu na rozkład mandatów



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