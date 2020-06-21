<style>
    h1 {
        font-weight: normal;
    }

    .emoji {
        font-size: 20px;
    }
</style>

<main>
	<h1>Hello {random}</h1>
    <p>Thanks for checking my website, but it's still under construction for now</p>
    <button on:click={setRandomEmoji}>Randomize emoji <span class="emoji">{random}</span></button>
</main>

<script>
    'use strict';
    
    const emojis = ['🗻', '🍲', '🏉', '🤼‍♂️', '👨‍💻', '⌨️', '👟', '🦠', '🎥', '🕹️', '🎲'];

    const randomEmoji = () => {
        return emojis[Math.floor(Math.random() * emojis.length)];
    }

    const setRandomEmoji = () => {
        random = randomEmoji();
    }

    let random = randomEmoji();
</script>