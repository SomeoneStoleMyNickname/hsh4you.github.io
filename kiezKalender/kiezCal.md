Umsetzung durch den <a class="external_link" href="https://kiezkalender-lichtenberg.de/" target="blank">Kiezkalender Lichtenberg</a>
<div id="kiezkalender"></div>
<script src="https://kiezkalender-lichtenberg.de/lib/1.0.0/kiezkalender.min.js"></script>
<script type="text/javascript">
    var t = new Date();

    // Kategorien 600 Alt-Hohenschönhausen 624 Hohenschönhausen

    var options = {
        start_date: `${t.getFullYear()}-${String(t.getMonth()+1).padStart(2,"0")}-${String(t.getDate()).padStart(2,"0")}`,
        categories: '600, 624'
    };
    var kiezkalender = new Kiezkalender("#kiezkalender", options);
</script>