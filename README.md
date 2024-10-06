 
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Video Presentation</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f4f4f4;
        }
        video {
            max-width: 100%;
            height: auto;
        }
    </style>
</head>
<body>
    <video id="presentationVideo" controls autoplay>
        <source src="videoplayback.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>

    <script>
        const video = document.getElementById('presentationVideo');
        
        video.onended = function() {
            window.location.href = "https://linktr.ee/ANT_SILIANA";  // Redirect to the desired page
        };
    </script>
</body>
</html>
