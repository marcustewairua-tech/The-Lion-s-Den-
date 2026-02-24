<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Lion's Den</title>
    <style>
        body {
            background-color: #1a1a1a;
            color: #d4af37;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            text-align: center;
            padding: 20px;
        }
        .container {
            border: 2px solid #d4af37;
            padding: 30px;
            border-radius: 15px;
            max-width: 500px;
            margin: auto;
            box-shadow: 0 0 20px rgba(212, 175, 55, 0.2);
        }
        h1 { text-transform: uppercase; letter-spacing: 3px; }
        ul { list-style-type: none; padding: 0; text-align: left; line-height: 2; }
        li { border-bottom: 1px solid #333; padding: 5px 0; }
        
        .play-btn {
            background-color: #d4af37;
            color: #1a1a1a;
            padding: 20px;
            border: none;
            font-weight: bold;
            border-radius: 50px;
            width: 100%;
            font-size: 1.3rem;
            cursor: pointer;
            margin-top: 20px;
            text-transform: uppercase;
            box-shadow: 0px 4px 15px rgba(212, 175, 55, 0.5);
        }
        .play-btn:active { transform: scale(0.98); }
    </style>
</head>
<body>

    <div class="container">
        <h1>The Lion's Den</h1>
        <p><i>Timeline Shifting: JKD Roster 2.0</i></p>
        
        <hr style="border: 0; height: 1px; background: #d4af37;">

        <ul>
            <li>🏆 Why am I financially independent?</li>
            <li>💪 Why am I in the best shape of my life?</li>
            <li>🥊 Why am I good at boxing?</li>
            <li>🏊 Why am I good at swimming?</li>
            <li>🔥 Why do I love to exercise?</li>
            <li>📈 Why am I successful at everything I do?</li>
            <li>🧘 Why am I kind, patient and calm?</li>
            <li>🕊️ Why am I slow to anger?</li>
            <li>✨ Why am I living the best version of myself?</li>
            <li>🌐 Why am I focused on my spatial awareness?</li>
        </ul>

        <audio id="askfirmationAudio">
            <source src="askfirmations101.mp3" type="audio/mpeg">
        </audio>

        <button class="play-btn" onclick="playAudio()">
            🔊 ACTIVATE ASKFIRMATIONS
        </button>
    </div>

    <script>
        function playAudio() {
            var audio = document.getElementById("askfirmationAudio");
            audio.play().catch(function(error) {
                console.log("Play failed. Check file name match.");
                alert("Check if file is named askfirmations101.mp3 exactly!");
            });
        }
    </script>

</body>
</html>
