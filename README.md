# HTML-Day-8
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Multimedia Webpage</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
        }

        .container {
            width: 80%;
            margin: auto;
            background: white;
            padding: 20px;
        }

        img {
            border-radius: 10px;
            margin: 10px;
        }
    </style>
</head>

<body>
    <div class="container">
        <h1>My Multimedia Webpage</h1>

        <!-- First Video -->
        <h2>Nature Video</h2>
        <video controls width="400">
            <source src="nature-video.mp4" type="video/mp4">
        </video>
        <p>A relaxing nature video.</p>

        <!-- Second Video -->
        <h2>Travel Video</h2>
        <video controls width="400">
            <source src="travel-video.mp4" type="video/mp4">
        </video>
        <p>An exciting travel experience.</p>

        <!-- Audio Section -->
        <h2>Audio Section</h2>
        <audio controls>
            <source src="music.mp3" type="audio/mpeg">
        </audio>
        <p>A calming background music track.</p>

        <!-- Image Gallery -->
        <h2>Image Gallery</h2>
        <img src="pic1.jpg" width="200">
        <p>Beautiful scenery image.</p>

        <img src="pic2.jpg" width="200">
        <p>Peaceful nature view.</p>

        <img src="pic3.jpg" width="200">
        <p>Stunning landscape.</p>

        <!-- YouTube Video -->
        <h2>YouTube Video</h2>
        <iframe 
            width="420" 
            height="250" 
            src="https://www.youtube.com/embed/VIDEO_ID" 
            allowfullscreen>
        </iframe>
        <p>An interesting YouTube video.</p>

    </div>
</body>
</html>
