# 20hadits
Memuat 20 hadits dari hadits-hadits arba'in an-Nawawy yang harus dipelajari dan diamalkan.
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pemutar Audio Google Drive</title>
    <style>
        body { text-align: center; font-family: Arial, sans-serif; }
        button { margin: 10px; padding: 10px; font-size: 16px; }
    </style>
</head>
<body>
    <h2>Pemutar Audio dari Google Drive</h2>
    <audio id="audio" controls>
        <source id="audioSource" src="https://docs.google.com/uc?export=download&id=1-J4Gkf_h6bqF1gMe5WkjPk5JTzozImx6" type="audio/mp3">
        Browser Anda tidak mendukung pemutar audio.
    </audio>
    <br>
    <button onclick="playAudio()">Play</button>
    <button onclick="pauseAudio()">Pause</button>
    <button onclick="reverseAudio()">Reverse (Ulang)</button>
    <a id="downloadLink" href="https://docs.google.com/uc?export=download&id=1-J4Gkf_h6bqF1gMe5WkjPk5JTzozImx6" download>
        <button>Download</button>
    </a>
    
    <script>
        let audio = document.getElementById("audio");
        function playAudio() { audio.play(); }
        function pauseAudio() { audio.pause(); }
        function reverseAudio() { audio.currentTime = 0; }
    </script>
</body>
</html>
