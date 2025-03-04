<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lucas Diniz - Profile</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #0d1117;
            color: #c9d1d9;
            margin: 0;
            padding: 20px;
        }
        .container {
            max-width: 800px;
            margin: auto;
            background: #161b22;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(255, 255, 255, 0.1);
        }
        h1, h2 {
            color: #58a6ff;
        }
        .name {
            color: #ff7b72;
        }
        .recent-tracks ul {
            list-style: none;
            padding: 0;
        }
        .recent-tracks li {
            background: #21262d;
            margin: 5px 0;
            padding: 10px;
            border-radius: 5px;
        }
        .waifus {
            text-align: center;
        }
        .waifu-list img {
            width: 80px;
            height: 80px;
            border-radius: 10px;
            margin: 5px;
        }
        .anime-favorites .anime {
            display: flex;
            align-items: center;
            margin-bottom: 10px;
            background: #21262d;
            padding: 10px;
            border-radius: 5px;
        }
        .anime img {
            width: 80px;
            height: 120px;
            border-radius: 5px;
            margin-right: 10px;
        }
        .coding-stats .languages p {
            background: #21262d;
            padding: 5px;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Hi there, I'm <span class="name">Lucas Diniz</span> 🔥</h1>
        </header>
        
        <section class="recent-tracks">
            <h2>🎵 Recent Tracks</h2>
            <ul>
                <li>🎶 Tennessee Whiskey - Chris Stapleton</li>
                <li>🎶 Nobody Else - Bridges To Nowhere</li>
                <li>🎶 Babymetal - Headbanggeeeerrr!!!!!</li>
                <li>🎶 How Much I Love You, Baby - 03</li>
            </ul>
        </section>

        <section class="waifus">
            <h2>❤️ Waifus</h2>
            <div class="waifu-list">
                <img src="senjougahara.jpg" alt="Senjougahara">
                <img src="nao_tomori.jpg" alt="Nao Tomori">
                <img src="taiga.jpg" alt="Taiga">
                <img src="saotome.jpg" alt="Saotome">
                <img src="kuroki.jpg" alt="Kuroki">
            </div>
        </section>

        <section class="anime-favorites">
            <h2>📺 Anime Favorites</h2>
            <div class="anime">
                <img src="bakemonogatari.jpg" alt="Bakemonogatari">
                <div>
                    <h3>Bakemonogatari</h3>
                    <p>⭐ 8.32 | #94 | ❤️ 15 | 📅 2009</p>
                    <p>🕵 Mystery | ❤️ Romance | 🔮 Supernatural | 🧛‍♂ Vampire</p>
                </div>
            </div>

            <div class="anime">
                <img src="nodame.jpg" alt="Nodame Cantabile">
                <div>
                    <h3>Nodame Cantabile</h3>
                    <p>⭐ 8.25 | #794 | ❤️ 23 | 📅 2007</p>
                    <p>😂 Comedy | ❤️ Romance | 🎵 Music | 🔞 Adult Cast</p>
                </div>
            </div>

            <div class="anime">
                <img src="toradora.jpg" alt="Toradora">
                <div>
                    <h3>Toradora!</h3>
                    <p>⭐ 8.05 | #25 | ❤️ 25 | 📅 2008</p>
                    <p>❤️ Romance | 🎭 Drama | 🎒 School | 🔀 Love Polygon</p>
                </div>
            </div>
        </section>

        <section class="coding-stats">
            <h2>💻 Coding Stats</h2>
            <div class="languages">
                <p>📜 TypeScript: <span>67.25%</span></p>
                <p>📜 JavaScript: <span>17.60%</span></p>
                <p>📜 Python: <span>8.44%</span></p>
                <p>📜 CSS: <span>4.51%</span></p>
            </div>
        </section>
    </div>

    <script>
        document.addEventListener("DOMContentLoaded", function () {
            console.log("Profile Loaded! 🎉");
        });
    </script>
</body>
</html>
