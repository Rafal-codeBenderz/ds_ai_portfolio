
# Analiza Danych – Irysy (EDA)

Przeprowadziłem analizę eksploracyjną danych (EDA) dotyczącą irysów, koncentrując się na zrozumieniu relacji między różnymi cechami tych roślin. Projekt zawiera wizualizacje, wnioski i obserwacje, które ujawniają, jak bogate informacje można wydobyć z tego klasycznego zestawu danych.



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
