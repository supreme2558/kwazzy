<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Legend of Kwazzy</title>
    <style>
        body {
            background-color: #000;
            color: #fff;
            font-family: 'Courier New', Courier, monospace;
            margin: 0;
            padding: 0;
            overflow-x: hidden;
        }
        header {
            text-align: center;
            padding: 50px 20px;
            background: url('https://files.catbox.moe/8ywlwh.jpg') no-repeat center center/cover;
            position: relative;
        }
        header::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.7);
        }
        header h1 {
            font-size: 4rem;
            text-transform: uppercase;
            letter-spacing: 4px;
            position: relative;
            z-index: 1;
        }
        .content {
            padding: 20px;
            line-height: 1.6;
        }
        .content p {
            font-size: 1.2rem;
            margin-bottom: 20px;
        }
        .image-container img {
            display: block;
            margin: 0 auto;
            max-width: 100%;
            height: auto;
            border: 5px solid #fff;
        }
        .transparent-image-container {
            text-align: center;
            margin-top: 50px;
        }
        .transparent-image {
            max-width: 300px;
            width: 100%;
            height: auto;
        }
        .reaction-button {
            display: block;
            width: 200px;
            margin: 20px auto;
            padding: 15px;
            font-size: 1.2rem;
            text-align: center;
            background-color: #ff4500;
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        .reaction-button:hover {
            background-color: #e63900;
        }
        .hidden-info {
            display: none;
            text-align: center;
            font-size: 1.3rem;
            margin-top: 30px;
        }
        .hidden-info p {
            margin: 10px 0;
        }
        footer {
            text-align: center;
            padding: 20px;
            background: #111;
            color: #aaa;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        a {
            color: #ff4500;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1>The Legend of Kwazzy</h1>
    </header>
    <div class="content">
        <p>In the dark corners of the internet, there exists a tale so chilling, so bizarre, that it has become the stuff of legend. The story of <strong>Kwazzy</strong>, also known as <strong>KwazzyGaming</strong> on Twitch, will haunt your dreams—and maybe even your social media apps.</p>

        <div class="image-container">
            <img src="https://files.catbox.moe/uhyo72.png" alt="Kwazzy's Profile Picture">
        </div>

        <p><strong>Kwazzy</strong> was once just an ordinary gamer trying to make his mark in the world of online streaming. But something sinister lurked beneath the surface. Known as the "<em>Chopped Guy</em>," Kwazzy became infamous for his unsettling presence and relentless pursuit of attention.</p>

        <p>Rumors spread like wildfire when whispers began about Kwazzy's obsession with the dating app <em>Monkey</em>. Women would log in, only to find themselves face-to-face with Kwazzy’s pixelated avatar. His attempts at charm were met with swift rejection—he got skipped more times than anyone thought possible. It was said that his profile picture alone could send shivers down your spine.</p>

        <p>But here’s where the story takes a darker turn. Rejected and humiliated, Kwazzy didn’t retreat into obscurity. Instead, he embraced the shadows. Tales emerged of him lurking in chat rooms, stalking women across platforms, and leaving cryptic messages like:</p>

        <blockquote style="text-align: center; font-size: 1.3rem;">
            “You can skip me, but you can’t escape me.”
        </blockquote>

        <p>Some claim they’ve seen him in their followers list late at night. Others swear they’ve heard his voice whispering through their headphones during livestreams. Is Kwazzy real? Or is he just a figment of our collective imagination—a cautionary tale born from the chaos of modern technology?</p>

        <p>One thing is certain: if you ever encounter someone named Kwazzy online, think twice before engaging. You might become part of the legend yourself...</p>

        <p>For more spooky stories and updates on this project, visit <a href="#" target="_blank">our main page</a>.</p>

        <button class="reaction-button" onclick="revealInfo()">Reveal Secrets</button>

        <div class="hidden-info" id="hiddenInfo">
            <p><strong>Who is Kwazzy?</strong> A mysterious figure who stalks fine shyts on Monkey.</p>
            <p><strong>Gender:</strong> Bisexual</p>
            <p><strong>Height:</strong> 5'6"</p>
            <p><strong>Gooning Count (Past 6 Months):</strong> Over 700</p>
        </div>

        <!-- Transparent Image Section -->
        <div class="transparent-image-container">
            <img src="https://files.catbox.moe/8ft8xs.png" alt="Transparent Image" class="transparent-image">
        </div>
    </div>
    <footer>
        &copy; 2023 The Legend of Kwazzy | Created for Educational Purposes
    </footer>

    <script>
        function revealInfo() {
            const hiddenInfo = document.getElementById('hiddenInfo');
            if (hiddenInfo.style.display === 'none' || hiddenInfo.style.display === '') {
                hiddenInfo.style.display = 'block';
            } else {
                hiddenInfo.style.display = 'none';
            }
        }
    </script>
</body>
</html>
