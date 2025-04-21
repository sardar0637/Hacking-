<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Phone Hacked!</title>
  <style>
    body {
      background-color: black;
      color: red;
      font-family: 'Courier New', monospace;
      text-align: center;
      padding-top: 100px;
    }
    .warning {
      font-size: 32px;
      margin: 20px;
    }
    .sub {
      font-size: 20px;
      margin: 10px;
    }
  </style>
</head>
<body>
  <div class="warning">WARNING! Your Phone is HACKED!</div>
  <div class="sub">Accessing your contacts...</div>
  <div class="sub">Hacking WhatsApp...</div>
  <div class="sub" style="color:lime">Just kidding! You've been pranked by Mujahid Sardar!</div>  <audio autoplay>
    <source src="voice.mp3" type="audio/mpeg">
    Your browser does not support the audio element.
  </audio>  <script>
    let lines = document.querySelectorAll('.sub');
    lines.forEach((line, index) => {
      line.style.display = 'none';
      setTimeout(() => {
        line.style.display = 'block';
      }, 2000 * (index + 1));
    });
  </script></body>
</html>
