# **Analiza Danych EDA Irysów: Eksploracja Domenowa**

Prezentowana analiza to kompleksowe podejście do badania zbioru irysów przy użyciu metod eksploracji danych (EDA). Celem projektu jest identyfikacja wzorców oraz korelacji występujących w pomiarach botanicznych, co pozwala na precyzyjne odróżnienie poszczególnych gatunków. Zapraszamy do wnikliwej lektury wyników, które stanowią rzetelne źródło wiedzy o strukturze badanych danych.

<a href="iris.ipynb" class="md-button md-button--primary">Pobierz Notebook</a>

<iframe
    id="content"
    src="iris.html"
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