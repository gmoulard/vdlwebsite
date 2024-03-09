
<script type="type/javascript">
$( document ).ready(function(){
    var userLang = navigator.language || navigator.userLanguage;
    if (userLang == "fr") {
        window.location.href = "/index_fr"
    }
    else {
        window.location.href = "/index_en"
    }
});
</script>