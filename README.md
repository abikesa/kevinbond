

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        .video-container {
            display: flex;
            justify-content: space-around; /* Adjust the spacing between iframes */
            gap: 20px; /* Add a gap between iframes */
            padding: 20px; /* Add padding around the container */
        }
        .video-container iframe {
            width: 30%; /* Adjust the width of each iframe */
            height: 300px; /* Adjust the height as needed */
            border: none; /* Remove the border */
        }
        body {
            margin: 0; /* Remove margin from body */
            padding: 0; /* Remove padding from body */
            background-color: #ffffff; /* Ensure the background is white */
        }
    </style>
    <title>Embed YouTube Videos</title>
</head>
<body>
    <div class="video-container">
        <iframe src="https://www.youtube.com/embed/Vu2DVPsBzSY" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        <iframe src="https://www.kevinbond.com/bio.html" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        <iframe src="https://www.youtube.com/embed/0V8KsRtSXA4" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
</body>
</html>
