<style>

</style>

<main>
	<h1>Hello World!</h1>
    <h2>{random}</h2>
    <button on:click={setRandomEmoji}>Get new emoji</button>
</main>

<script>
    const emojis = ['😀', '😁', '😂', '🤣', '😃', '😄', '😅', '😆', '😉', '😊', '😋', '😎', '😍', '😘', '😗', '😙', '😚'];

    const randomEmoji = () => {
        return emojis[Math.floor(Math.random() * emojis.length)];
    }

    const setRandomEmoji = () => {
        random = randomEmoji();
    }
    
    let random = randomEmoji();
</script>