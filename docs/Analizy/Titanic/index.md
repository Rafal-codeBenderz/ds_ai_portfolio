
# Analiza Danych – Titanic (EDA)

W ramach eksploracyjnej analizy danych pasażerów Titanica, dążyłem do zidentyfikowania czynników, które miały wpływ na przeżycie podczas tragedii. Zestaw danych obejmuje informacje takie jak płeć, wiek, klasa podróży, powiązania rodzinne na pokładzie oraz miejsce zaokrętowania. Analiza obejmowała wstępne czyszczenie danych, tworzenie wizualizacji oraz porównania między różnymi grupami pasażerów. Projekt ten pokazuje, jak dane historyczne mogą zostać wykorzystane do formułowania praktycznych wniosków i rozwijania analitycznej intuicji.

<a href="titanic_analiza.ipynb" class="md-button md-button--primary">Pobierz Notebook z analizą Tytanica</a>

<iframe
    id="content"
    src="titanic_analiza.html"
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
