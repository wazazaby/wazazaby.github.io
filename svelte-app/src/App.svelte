<style>
    /* === MAIN === */

    #main {
        width: 60%;
        margin: 0 auto;
        padding-top: 40vh;
    }

    #main h1 {
        font-size: 50px;
        color: white;
        width: 100%;
        margin-bottom: 10px;
        text-align: center;
    }

    #main p.typed {
        font-size: 30px;
        color: white;
        font-weight: bold;
        margin-bottom: 20px;
        text-align: center;
    }

    #main .links {
        display: flex;
        justify-content: center;
    }

    #main .links .link:not(:last-child) {
        margin-right: 5em;
    }

    #main .links .link a {
        text-decoration: none;
        color: white;
        font-size: 30px;
    }

    #main .links .link a i {
        transition: all 0.2s;
    }

    /* === MAIN === */

    /* === HOVER === */

    #main .links .link a:hover .fa-github {
        color: #6e5494;
    }

    #main .links .link a:hover .fa-linkedin {
        color: #0077b5;
    }

    #main .links .link a:hover .fa-twitter {
        color: #1da1f2;
    }

    #main .links .link a:hover .fa-file-alt {
        color: #34bf49;
    }

    #main .links .link a:hover .fa-envelope {
        color: #ffd900;
    }

    #main .links .link a:hover .fa-discord {
        color: #7289da;
    }

    /* === HOVER === */


    /* === RESPONSIVE === */

    @media (max-width: 900px) {
        #main {
            width: 80%;
        }

        #main h1 {
            font-size: 45px;
        }

        #main p.typed {
            font-size: 25px;
        }

        #main .links .link:not(:last-child) {
            margin-right: 4em;
        }
    }

    @media (max-width: 600px) {
        #main {
            width: 95%;
        }

        #main h1 {
            font-size: 40px;
        }

        #main p.typed {
            font-size: 20px;
        }

        #main .links .link:not(:last-child) {
            margin-right: 2em;
        }
    }

    /* === RESPONSIVE === */
</style>

<main id="main">
	<h1>Teddy Sommavilla</h1>
    <p class="typed"></p>
    <div class="links">
        <div class="link">
            <a href="https://github.com/Wazazaby" target="_blank">
                <i class="fab fa-github"></i>
            </a>
        </div>
        <div class="link">
            <a href="https://www.linkedin.com/in/teddy-sommavilla/" target="_blank">
                <i class="fab fa-linkedin"></i>
            </a>
        </div>
        <div class="link">
            <a href="https://www.doyoubuzz.com/teddy-sommavilla" target="_blank">
                <i class="fas fa-file-alt"></i>
            </a>
        </div>
        <div class="link">
            <a href="mailto:pcteddy2017@gmail.com" target="_blank">
                <i class="fas fa-envelope"></i>
            </a>
        </div>
        <div class="link">
            <a href="https://twitter.com/Wazazaby" target="_blank">
                <i class="fab fa-twitter"></i>
            </a>
        </div>
        <div class="link">
            <a href="https://discord.gg/V2Ns3gD" target="_blank">
                <i class="fab fa-discord"></i>
            </a>
        </div>
    </div>
</main>

<script>
    'use strict';
    import Typed from 'typed.js';

    window.onload = () => {
        let typed = new Typed('.typed', {
            strings: ['Junior Web Developer'],
            typeSpeed: 60,
            showCursor: false
        });
    }
</script>