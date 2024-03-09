

<script>
document.write(navigator.language);

if (document.write(navigator.language) == 'fr-FR')
{
    document.location.href = "/index_fr"
} else {
    document.location.href = "/index_en"
}
</script>

{% include_relative index_fr.md %}
