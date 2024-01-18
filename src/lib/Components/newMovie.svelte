<script>
</script>

<h1>Voeg hier een nieuwe film toe</h1>
<form method="post" action="http://localhost:1337/newmovie">
    <input type="text" name="title" id="title" placeholder="TItel...." />
    <input
        type="text"
        name="director"
        id="director"
        placeholder="Regiseur..."
    />
    <input
        type="number"
        name="release_year"
        id="release_year"
        placeholder="Jaar van uitgave..."
    />
    <input type="text" name="genre" id="genre" placeholder="Genre..." />

    <button>Send</button>
</form>

<!-- Omzetten naar Fetch
    Prevent default -->

<style>
</style>
