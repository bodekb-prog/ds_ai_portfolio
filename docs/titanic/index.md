# Analiza Danych EDA Titanic: Eksploracja Domenowa

Zapraszam do analizy historycznego zbioru danych pasażerów Titanica, przeprowadzonej w oparciu o techniki eksploracyjnej analizy danych (EDA). Projekt koncentruje się na identyfikacji kluczowych czynników, które decydowały o szansach na przeżycie w tej katastrofie. Poprzez badanie korelacji między danymi demograficznymi a wynikami przetrwania, analiza rzuca nowe światło na społeczne i techniczne aspekty tego wydarzenia, prezentując je w formie przejrzystych wizualizacji.

<a href="titanic.ipynb" class="md-button md-button--primary">Pobierz Notebook</a>

<iframe
    id="content"
    src="titanic.html"
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