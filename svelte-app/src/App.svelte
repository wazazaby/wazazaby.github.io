<style>

</style>

<main>
	<h1>Hello World!</h1>
    <h2>{random}</h2>
    <button on:click={setRandomEmoji}>Get new emoji</button>
    <p>
    Lorem ipsum dolor sit amet consectetur, adipisicing elit. Doloribus eum facilis minima quidem sit officiis consequatur, ipsam laudantium, quas ut nemo veritatis quae! Sunt aliquam soluta, sint vero illo deleniti? => ===
    </p>
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