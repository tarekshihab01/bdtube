<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>BDTube - Video Sharing Platform</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #121212;
      color: #fff;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #ff0000;
      padding: 15px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 28px;
    }
    .container {
      padding: 20px;
    }
    .video-wrapper {
      margin-bottom: 20px;
    }
    iframe {
      width: 100%;
      height: 315px;
      border: none;
    }
    .upload-section {
      margin-top: 30px;
      background: #1e1e1e;
      padding: 20px;
      border-radius: 10px;
    }
    input[type="text"] {
      width: 100%;
      padding: 10px;
      margin-bottom: 10px;
      border: none;
      border-radius: 5px;
    }
    button {
      background-color: #ff0000;
      color: white;
      border: none;
      padding: 10px 20px;
      border-radius: 5px;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <header>
    <h1>BDTube</h1>
  </header>
  <div class="container">
    <div class="video-wrapper">
      <h2>Featured Video</h2>
      <iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ" allowfullscreen></iframe>
    </div>

    <div class="upload-section">
      <h2>Submit Your Video (Demo)</h2>
      <input type="text" placeholder="Paste your YouTube Video URL here" />
      <button>Submit</button>
    </div>
  </div>
</body>
</html>
