# digital-card-for-Aarti

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="styles.css">
  <title>Your Digital Gift</title>
</head>
<body>

  <div class="card">
    <h1>Hey Aarti,</h1>
    <p>Just wanted to let you know...</p>
    <p>You mean a lot to me!</p>
    <p>Hope this brightens your day!</p>
    <p>From, Gursirjan</p>
  </div>

  <script src="script.js"></script>
</body>
</html>

body {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100vh;
  margin: 0;
  background-color: #f5f5f5;
}

.card {
  background-color: #fff;
  border-radius: 8px;
  padding: 20px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  text-align: center;
}

h1 {
  color: #e44d26;
}

p {
  margin: 10px 0;
}

// Optional: You can add interactivity or animations using JavaScript.
// For a simple card, it might not be necessary.

// Example: Add a hover effect to the card
const card = document.querySelector('.card');

card.addEventListener('mouseover', function () {
  card.style.transform = 'scale(1.1)';
});

card.addEventListener('mouseout', function () {
  card.style.transform = 'scale(1)';
});
