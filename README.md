<!DOCTYPE html>
<html>
<head>
  <title>YouTube Video Downloader</title>
  <style>
    .container {
      text-align: center;
      margin-top: 100px;
    }

    h1 {
      font-family: Arial, sans-serif;
    }

    input {
      padding: 10px;
      width: 300px;
      margin-bottom: 10px;
    }

    button {
      padding: 10px 20px;
      background-color: #4CAF50;
      color: white;
      border: none;
      cursor: pointer;
      font-size: 16px;
    }

    button:hover {
      background-color: #45a049;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>YouTube Video Downloader</h1>
    <input type="text" id="urlInput" placeholder="Enter YouTube URL">
    <button id="downloadButton">Download</button>
  </div>

  <script>
    function downloadVideo() {
      var urlInput = document.getElementById('urlInput');
      var videoUrl = urlInput.value;

      // Perform the necessary operations here
      // such as making requests to a backend server
      // to handle the video downloading process

      console.log('Downloading video:', videoUrl);
    }

    document.getElementById('downloadButton').addEventListener('click', downloadVideo);
  </script>
</body>
</html>
