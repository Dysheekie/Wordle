<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

  <h1>Wordle</h1>
  <h3>Press 'ENTER' to guess</h3>
  <div id="warning"></div>
  <div id="alphabet"></div>
  <button type="button" onclick="javascript:window.dispatchEvent(new KeyboardEvent('keydown',{'key':'enter'}));">ENTER</button>
  <button type="button" onclick="javascript:window.dispatchEvent(new KeyboardEvent('keydown',{'key':'backspace'}));">BACKSPACE</button>
  <button style='display: none;' type="button" onclick="javascript:window.location.href = window.location.href;">RESTART THE GAME</button>
  <div id="grid"></div>
  <button id="openKeyboard">Open Keyboard</button>
  <input id="hiddenInput" style="visibility: hidden;">
<script src="index.js"></script>
</body>
</html>
