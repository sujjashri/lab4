<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Change Content Example</title>
</head>
<body>

<div id="myElement">
  <p id="myParagraph">Welcome to my website!</p>
</div>

<button onclick="changeContent()">Change Content</button>

<script>
  function changeContent() {
    document.getElementById("myParagraph").textContent = "Hello there!";
  }
</script>

</body>
</html>
