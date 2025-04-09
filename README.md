<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Just a Notepad</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="toolbar">
    <input type="color" id="colorPicker" value="#000000">
    <input type="range" id="penSize" min="1" max="10" value="2">
    <button id="clearCanvas">Clear</button>
    <button id="saveCanvas">Save</button>
  </div>
  <canvas id="drawingCanvas"></canvas>
  <script src="script.js"></script>
</body>
</html>
