<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>My Cat Baton</title>
  <style>
    body {
      font-family: 'Comic Sans MS', cursive, sans-serif;
      line-height: 1.6;
      background-color: #fff8f0;
      color: #333;
      margin: 0;
      padding: 0;
    }

    .container {
      max-width: 900px;
      margin: auto;
      padding: 20px;
      text-align: center;
    }

    h1 {
      color: #4a4a4a;
      font-size: 2rem;
      margin-bottom: 10px;
    }

    h2 {
      color: #fdd835;
      margin-top: 40px;
    }

    img {
      max-width: 100%;
      border-radius: 10px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    }

    p {
      font-size: 1.2rem;
      margin-bottom: 20px;
    }

    .info {
      background: #e1bee7;
      padding: 10px 20px;
      border-radius: 5px;
      color: #333;
      margin-top: 20px;
      display: inline-block;
    }

    .schedule {
      background: #c8e6c9;
      padding: 15px;
      border-radius: 10px;
      margin-top: 20px;
      text-align: left;
      display: inline-block;
      width: 100%;
    }

    .schedule ul {
      list-style: none;
      padding-left: 0;
    }

    .schedule li {
      padding: 5px 10px;
      margin: 5px 0;
      background: #a5d6a7;
      border-radius: 5px;
      color: #333;
    }

    button {
      background-color: #fbc02d;
      border: none;
      padding: 10px 20px;
      font-size: 1rem;
      color: white;
      border-radius: 5px;
      cursor: pointer;
      transition: 0.3s ease;
    }

    button:hover {
      background-color: #fdd835;
    }

    footer {
      text-align: center;
      padding: 20px;
      font-size: 0.9rem;
      color: #aaa;
    }
  </style>
</head>
<body>

<div class="container">

  <h1>🐾 Hello! Meet Baton — the genius of mischief 🌟</h1>

  <!-- ВАШЕ ФОТО -->
  <img src="https://iili.io/FVvGnyB.jpg " alt="Baton the Cat">

  <p>He's not just a cat… He’s a mastermind in fur disguise. Baton is known across the house for his brilliant escape plans, sneaky hideouts, and dramatic food demands.</p>

  <div class="info">
    <strong>Favorite food:</strong> Fish 🐟 (preferably fishy enough to make him purr with approval)
  </div>

  <button onclick="feedBaton()">Feed Baton</button>
  <p id="feeding-message"></p>

  <h2>🧬 About Baton</h2>
  <p><strong>Baton is a street-smart, non-pedigree legend.</strong> Some say he was born with a PhD in “How to Annoy Humans Without Getting Caught.” He’s clever, sneaky, and sometimes throws tantrums just to remind you who’s really in charge.</p>

  <h2>🕒 Baton's Daily Routine</h2>
  <div class="schedule">
    <ul>
      <li>🌅 Morning? Nope. 😴 Waking up around noon</li>
      <li>🍽️ 12:15 PM — Breakfast time (with dramatic meows if it's late)</li>
      <li>🚪 12:20 PM — Demands to open the door, then stares at freedom like it betrayed him</li>
      <li>🛋️ 1:00 PM — Hiding under the couch like he's planning a heist</li>
      <li>🌙 2:00 AM — Time to run across furniture like a ninja on caffeine</li>
      <li>🧸 2:30 AM — Sudden urge to play with toys (or destroy them)</li>
      <li>💤 5:00 AM — Finally decides to nap (right on your face)</li>
    </ul>
  </div>

</div>

<footer>
  &copy; 2025 All rights reserved.
</footer>

<script>
  function feedBaton() {
    const messages = [
      "Baton gives you one proud stare. You passed the test.",
      "Fish accepted. No thanks given. Such is life.",
      "He ate everything except the packaging. Impressive.",
      "You hear a suspiciously satisfied meow from under the bed.",
      "Baton approved... for now."
    ];
    const randomIndex = Math.floor(Math.random() * messages.length);
    document.getElementById("feeding-message").textContent = messages[randomIndex];
  }
</script>

</body>
</html>
