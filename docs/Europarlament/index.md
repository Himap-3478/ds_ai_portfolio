# Analiza Danych polskich wyborów do Europarlamentu

utworzone: **27.05.2025**


Cel projektu:

Celem analizy było zbadanie ewolucji polskiej sceny politycznej w kontekście wyborów do Parlamentu Europejskiego – pod kątem:

* wyników procentowych partii politycznych,
* rozkładu mandatów w poszczególnych kadencjach,
* zmieniającego się układu sił ideologicznych (lewa–prawa strona sceny politycznej),
* wpływu systemu wyborczego na reprezentację partii.


Zakres analizy:

* Zebranie danych z lat 2004–2024 (wszystkie wybory PE po przystąpieniu Polski do UE)
* Przypisanie partii do bloków ideologicznych: prawica, centroprawica, centrum, centrolewica, lewica
* Analiza zmian w poparciu społecznym dla tych bloków
* Zestawienie liczby mandatów zdobywanych przez partie w poszczególnych kadencjach
* Ocena wpływu systemu proporcjonalnego na rozkład sił w PE


Kluczowe wnioski:

Wyniki partii politycznych:

* Najwyższe poparcie: **Prawo i Sprawiedliwość (2019)** – 45,38% głosów
* Najniższe poparcie: **Socjaldemokracja Polska (2004)** – 5,33%
* Rekord mandatów: **PiS (2019–2024)** – 27 mandatów
* Najmniej mandatów (3): m.in. PSL (2009), Wiosna (2019), Trzecia Droga i Lewica (2024)

Reprezentacja i ciągłość:

* Tylko **Platforma Obywatelska i Prawo i Sprawiedliwość** były reprezentowane we wszystkich 5 kadencjach.
* W kadencji 2014–2019 oba ugrupowania miały po równo – **19 mandatów**.

Zmienność systemu partyjnego:

* Największa różnorodność (8 partii): **kadencja 2004–2009**
* Największa koncentracja (3 partie): **kadencja 2019–2024**

Poglądy polityczne – skrajności i trendy:

| Poglądy           | Najlepszy wynik                 | Najgorszy wynik |
| ----------------- | ------------------------------- | --------------- |
| **Prawica**       | 47,47% (2014)                   | 4,63% (2019)    |
| **Centroprawica** | 49,07% (2015 – wybory krajowe?) | 24,10% (2004)   |
| **Centrum**       | 18,11% (2004)                   | 0,54% (2019)    |
| **Centrolewica**  | 38,47% (2023)                   | 0% (do 2014)    |
| **Lewica**        | 27,26% (2004)                   | 6,03% (2024)    |

**Insight:** Pomimo przewagi centroprawicy i prawicy w ostatnich latach, centrolewica zyskała istotne poparcie w 2023 r. Lewica notuje konsekwentny spadek od 2004 r.


Technologie i narzędzia:

* **Python (pandas, seaborn, matplotlib)** – analiza danych, wykresy
* **Jupyter Notebook** – interaktywna prezentacja analizy


Umiejętności zaprezentowane:

* Przetwarzanie danych politycznych i statystycznych
* Analiza trendów ideologicznych i porównawcza analiza poparcia
* Komunikacja danych za pomocą wizualizacji
* Wnioskowanie z danych społecznych i politycznych



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