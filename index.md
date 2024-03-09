

<script type="type/javascript">

document.write(navigator.language);


$( document ).ready(function(){
    var userLang = navigator.language || navigator.userLanguage;
    if (userLang == "fr") {
        window.location.href = "/index_fr"
        document.write("FR");
    }
    else {
        window.location.href = "/index_en"
        document.write("Other");
    }
});

</script>