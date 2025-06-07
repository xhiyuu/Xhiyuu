<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Her and Her</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Pacifico&family=Quicksand:wght@400;600&display=swap');

    body {
      margin: 0;
      font-family: 'Quicksand', sans-serif;
      background: radial-gradient(ellipse at top, #fdf6ff, #e0f7ff);
      overflow-x: hidden;
    }
    header {
      text-align: center;
      padding: 2rem;
      font-size: 2.5rem;
      color: #ff69b4;
      font-family: 'Pacifico', cursive;
    }
    iframe {
      display: block;
      margin: 1rem auto;
      border: none;
      border-radius: 1rem;
    }
    section {
      max-width: 800px;
      margin: 2rem auto;
      padding: 1rem;
      background: white;
      border-radius: 1rem;
      box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
    }
    h2 {
      color: #ff69b4;
      font-family: 'Pacifico', cursive;
    }
    .quote {
      font-style: italic;
      text-align: center;
      color: #555;
      padding: 1rem;
    }
    .dove {
      position: absolute;
      font-size: 2rem;
      animation: fly 10s linear infinite;
    }
    @keyframes fly {
      0% { left: -5%; top: 10%; }
      100% { left: 105%; top: 20%; }
    }
    .heart {
      position: fixed;
      bottom: 0;
      left: 50%;
      font-size: 2rem;
      animation: float 4s ease-in infinite;
      color: #ff69b4;
    }
    @keyframes float {
      0% { transform: translate(-50%, 0); opacity: 1; }
      100% { transform: translate(-50%, -100vh); opacity: 0; }
    }
    .messages {
      background: #fff0f6;
      border-radius: 1rem;
      padding: 1rem;
      margin-top: 2rem;
    }
    .messages p {
      background: #ffe4ec;
      padding: 0.75rem;
      border-radius: 1rem;
      margin-bottom: 0.5rem;
    }
    .button-container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 1rem;
      margin-top: 2rem;
    }
    .cute-button {
      background: #ffb6c1;
      border: none;
      border-radius: 1rem;
      padding: 1rem 2rem;
      font-size: 1rem;
      color: white;
      cursor: pointer;
      font-family: 'Quicksand', sans-serif;
      transition: background 0.3s ease;
    }
    .cute-button:hover {
      background: #ff69b4;
    }
    .scrapbook {
      display: flex;
      flex-direction: column;
      gap: 1rem;
      padding: 1rem;
    }
    .scrap-item {
      background: #fff0fa;
      padding: 1rem;
      border-left: 5px solid #ff69b4;
      border-radius: 1rem;
    }
  </style>
  <script>
    function showConfession() {
      alert("I think about you more than I should 💖");
    }
    function showQuiz() {
      const answer = prompt("What color reminds you of love?");
      if (answer) alert(`Aww! ${answer} is so romantic! 🌷`);
    }
    function sendLoveNote() {
      alert("💌 Sending warm hugs and sweet thoughts your way.");
    }
  </script>
</head>
<body>
  <header>💖 Her and Her 💖</header>

  <!-- Embedded YouTube Video -->
  <iframe width="560" height="315" src="https://www.youtube.com/embed/cqT_3c84VGI?autoplay=1&mute=0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

  <!-- Dove Emoji Animation -->
  <div class="dove">🕊️</div>
  <div class="heart">💗</div>

  <!-- Button Features -->
  <div class="button-container">
    <button class="cute-button" onclick="showConfession()">💘 Love Confession</button>
    <button class="cute-button" onclick="showQuiz()">🎀 Quick Love Quiz</button>
    <button class="cute-button" onclick="sendLoveNote()">💌 Send a Love Note</button>
  </div>

  <!-- WLW Story Time -->
  <section>
    <h2>📖 Her and Her: Short Love Stories</h2>
    <p><strong>Rain on Her Shoulder</strong><br>They sat under the same umbrella, heartbeats loud and unspoken words louder. The rain didn't stop, but neither did their smiles.</p>
    <p><strong>The Red Sweater</strong><br>She lent me her red sweater once. I never gave it back—not because I forgot, but because it smelled like her and felt like comfort.</p>
    <p><strong>Library Glance</strong><br>I caught her looking at me between pages. That one glance told me everything I needed to know—we were writing a new chapter together.</p>
  </section>

  <!-- WLW Poems -->
  <section>
    <h2>🌹 Her and Her: Soft Poems</h2>
    <p><em>When she says my name,</em><br>it sounds like soft rain on petals.<br><em>She is the poem I keep rereading.</em></p>
    <p><em>Your touch is starlight,</em><br>quiet and bold—<br><em>like a secret the universe told me.</em></p>
    <p><em>She looked at me,</em><br>and it felt like poetry.<br><em>No rhyme, no reason—just right.</em></p>
    <p><em>Her laugh is a song,</em><br>soft and fearless in the dark.<br><em>She is both spark and shelter.</em></p>
  </section>

  <!-- Love Messages Section -->
  <section class="messages">
    <h2>💌 Love Messages</h2>
    <p>"Every moment with you feels like the first spark of sunrise."</p>
    <p>"You're not just my person. You're my peace, my poem, my always."</p>
    <p>"You make the ordinary feel like magic."</p>
    <p>"Even in silence, your presence speaks love."</p>
    <p>"Your smile is the only sunshine I need."</p>
    <p>"Holding your hand feels like holding my future."</p>
  </section>

  <!-- Scrapbook Section -->
  <section>
    <h2>📸 Her and Her: Digital Scrapbook</h2>
    <div class="scrapbook">
      <div class="scrap-item">🖼️ Our first photo together at the park 🌸</div>
      <div class="scrap-item">🍦 That day we shared the biggest ice cream cone ever 🍨</div>
      <div class="scrap-item">🎶 The moment we danced in the kitchen to our favorite song</div>
      <div class="scrap-item">📝 That note you left in my book—I still keep it in my wallet</div>
      <div class="scrap-item">🌈 When we painted together and made a beautiful mess 🎨</div>
    </div>
  </section>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Her and Her</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Pacifico&family=Quicksand:wght@400;600&display=swap');

    body {
      margin: 0;
      font-family: 'Quicksand', sans-serif;
      background: radial-gradient(ellipse at top, #fdf6ff, #e0f7ff);
      overflow-x: hidden;
    }
    header {
      text-align: center;
      padding: 2rem;
      font-size: 2.5rem;
      color: #ff69b4;
      font-family: 'Pacifico', cursive;
    }
    iframe {
      display: block;
      margin: 1rem auto;
      border: none;
      border-radius: 1rem;
    }
    section {
      max-width: 800px;
      margin: 2rem auto;
      padding: 1rem;
      background: white;
      border-radius: 1rem;
      box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
    }
    h2 {
      color: #ff69b4;
      font-family: 'Pacifico', cursive;
    }
    .quote {
      font-style: italic;
      text-align: center;
      color: #555;
      padding: 1rem;
    }
    .dove {
      position: absolute;
      font-size: 2rem;
      animation: fly 10s linear infinite;
    }
    @keyframes fly {
      0% { left: -5%; top: 10%; }
      100% { left: 105%; top: 20%; }
    }
    .heart {
      position: fixed;
      bottom: 0;
      left: 50%;
      font-size: 2rem;
      animation: float 4s ease-in infinite;
      color: #ff69b4;
    }
    @keyframes float {
      0% { transform: translate(-50%, 0); opacity: 1; }
      100% { transform: translate(-50%, -100vh); opacity: 0; }
    }
    .messages {
      background: #fff0f6;
      border-radius: 1rem;
      padding: 1rem;
      margin-top: 2rem;
    }
    .messages p {
      background: #ffe4ec;
      padding: 0.75rem;
      border-radius: 1rem;
      margin-bottom: 0.5rem;
    }
    .button-container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 1rem;
      margin-top: 2rem;
    }
    .cute-button {
      background: #ffb6c1;
      border: none;
      border-radius: 1rem;
      padding: 1rem 2rem;
      font-size: 1rem;
      color: white;
      cursor: pointer;
      font-family: 'Quicksand', sans-serif;
      transition: background 0.3s ease;
    }
    .cute-button:hover {
      background: #ff69b4;
    }
    .scrapbook {
      display: flex;
      flex-direction: column;
      gap: 1rem;
      padding: 1rem;
    }
    .scrap-item {
      background: #fff0fa;
      padding: 1rem;
      border-left: 5px solid #ff69b4;
      border-radius: 1rem;
    }
  </style>
  <script>
    function showConfession() {
      alert("I think about you more than I should 💖");
    }
    function showQuiz() {
      const answer = prompt("What color reminds you of love?");
      if (answer) alert(`Aww! ${answer} is so romantic! 🌷`);
    }
    function sendLoveNote() {
      alert("💌 Sending warm hugs and sweet thoughts your way.");
    }
  </script>
</head>
<body>
  <header>💖 Her and Her 💖</header>

  <!-- Embedded YouTube Video -->
  <iframe width="560" height="315" src="https://www.youtube.com/embed/cqT_3c84VGI?autoplay=1&mute=0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

  <!-- Dove Emoji Animation -->
  <div class="dove">🕊️</div>
  <div class="heart">💗</div>

  <!-- Button Features -->
  <div class="button-container">
    <button class="cute-button" onclick="showConfession()">💘 Love Confession</button>
    <button class="cute-button" onclick="showQuiz()">🎀 Quick Love Quiz</button>
    <button class="cute-button" onclick="sendLoveNote()">💌 Send a Love Note</button>
  </div>

  <!-- WLW Story Time -->
  <section>
    <h2>📖 Her and Her: Short Love Stories</h2>
    <p><strong>Rain on Her Shoulder</strong><br>They sat under the same umbrella, heartbeats loud and unspoken words louder. The rain didn't stop, but neither did their smiles.</p>
    <p><strong>The Red Sweater</strong><br>She lent me her red sweater once. I never gave it back—not because I forgot, but because it smelled like her and felt like comfort.</p>
    <p><strong>Library Glance</strong><br>I caught her looking at me between pages. That one glance told me everything I needed to know—we were writing a new chapter together.</p>
  </section>

  <!-- WLW Poems -->
  <section>
    <h2>🌹 Her and Her: Soft Poems</h2>
    <p><em>When she says my name,</em><br>it sounds like soft rain on petals.<br><em>She is the poem I keep rereading.</em></p>
    <p><em>Your touch is starlight,</em><br>quiet and bold—<br><em>like a secret the universe told me.</em></p>
    <p><em>She looked at me,</em><br>and it felt like poetry.<br><em>No rhyme, no reason—just right.</em></p>
    <p><em>Her laugh is a song,</em><br>soft and fearless in the dark.<br><em>She is both spark and shelter.</em></p>
  </section>

  <!-- Love Messages Section -->
  <section class="messages">
    <h2>💌 Love Messages</h2>
    <p>"Every moment with you feels like the first spark of sunrise."</p>
    <p>"You're not just my person. You're my peace, my poem, my always."</p>
    <p>"You make the ordinary feel like magic."</p>
    <p>"Even in silence, your presence speaks love."</p>
    <p>"Your smile is the only sunshine I need."</p>
    <p>"Holding your hand feels like holding my future."</p>
  </section>

  <!-- Scrapbook Section -->
  <section>
    <h2>📸 Her and Her: Digital Scrapbook</h2>
    <div class="scrapbook">
      <div class="scrap-item">🖼️ Our first photo together at the park 🌸</div>
      <div class="scrap-item">🍦 That day we shared the biggest ice cream cone ever 🍨</div>
      <div class="scrap-item">🎶 The moment we danced in the kitchen to our favorite song</div>
      <div class="scrap-item">📝 That note you left in my book—I still keep it in my wallet</div>
      <div class="scrap-item">🌈 When we painted together and made a beautiful mess 🎨</div>
    </div>
  </section>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Her and Her</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Pacifico&family=Quicksand&family=Playfair+Display&display=swap');

    body {
      margin: 0;
      font-family: 'Quicksand', sans-serif;
      background: radial-gradient(ellipse at top, #fff0f5, #e0f7ff);
      overflow-x: hidden;
    }

    header {
      text-align: center;
      padding: 2rem;
      font-size: 3rem;
      color: #ff69b4;
      font-family: 'Pacifico', cursive;
    }

    iframe {
      display: block;
      margin: 1rem auto;
      border: none;
      border-radius: 1rem;
    }

    section {
      max-width: 800px;
      margin: 2rem auto;
      padding: 1rem 2rem;
      background: white;
      border-radius: 1rem;
      box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
    }

    h2 {
      color: #ff69b4;
      font-family: 'Playfair Display', serif;
    }

    .quote, .poem {
      font-style: italic;
      color: #555;
      text-align: center;
      margin-bottom: 1rem;
    }

    .dove {
      position: absolute;
      font-size: 2rem;
      animation: fly 12s linear infinite;
    }

    @keyframes fly {
      0% { left: -5%; top: 10%; }
      100% { left: 105%; top: 20%; }
    }

    .heart {
      position: absolute;
      font-size: 2rem;
      animation: floatHearts 20s linear infinite;
      color: #ff5ca1;
    }

    @keyframes floatHearts {
      0% {
        transform: translateX(-100px) translateY(0);
        opacity: 1;
      }
      100% {
        transform: translateX(300px) translateY(-800px);
        opacity: 0;
      }
    }

    button {
      background-color: #ffb6c1;
      color: white;
      border: none;
      padding: 10px 20px;
      margin: 1rem 0.5rem;
      border-radius: 25px;
      cursor: pointer;
      font-family: 'Quicksand', sans-serif;
      font-weight: bold;
      transition: background 0.3s;
    }

    button:hover {
      background-color: #ff69b4;
    }

    #loveNoteDisplay, #confessionOutput, #quizResult {
      font-style: italic;
      text-align: center;
      margin-top: 1rem;
      color: #333;
    }

    .input-group {
      text-align: center;
      margin-top: 1rem;
    }

    input[type="text"] {
      padding: 10px;
      border-radius: 10px;
      border: 1px solid #ddd;
      width: 70%;
      margin-bottom: 1rem;
    }

    .scrapbook {
      display: flex;
      flex-wrap: wrap;
      gap: 1rem;
      justify-content: center;
    }

    .scrapbook div {
      background: #fff0f5;
      padding: 1rem;
      border-radius: 1rem;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
      width: 200px;
      text-align: center;
    }
  </style>
</head>
<body>

  <header>💖 Her and Her 💖</header>

  <!-- YouTube Music -->
  <iframe width="560" height="315" src="https://www.youtube.com/embed/cqT_3c84VGI?autoplay=1&mute=0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

  <!-- Dove Emoji -->
  <div class="dove">🕊️</div>

  <!-- Flying Hearts (JavaScript adds them) -->
  <script>
    for (let i = 0; i < 20; i++) {
      let heart = document.createElement('div');
      heart.className = 'heart';
      heart.innerText = '💗';
      heart.style.left = Math.random() * window.innerWidth + 'px';
      heart.style.top = Math.random() * window.innerHeight + 'px';
      heart.style.animationDuration = 10 + Math.random() * 10 + 's';
      heart.style.fontSize = 1 + Math.random() * 2 + 'rem';
      document.body.appendChild(heart);
    }
  </script>

  <!-- Stories -->
  <section>
    <h2>📖 Love Stories</h2>
    <p><strong>Red Sweater:</strong> She lent me her red sweater. I never gave it back—because it felt like home.</p>
    <p><strong>Quiet Glance:</strong> One glance from her in the library wrote a thousand unsaid poems in my heart.</p>
  </section>

  <!-- Poems -->
  <section>
    <h2>🌸 Soft Poems</h2>
    <p class="poem">She is not the sun,<br>but the morning after rain—<br>warm and quiet.</p>
    <p class="poem">Our fingers brushed,<br>and the world paused—<br>for just a moment.</p>
  </section>

  <!-- Love Note Generator -->
  <section>
    <h2>💌 Love Note Generator</h2>
    <button onclick="generateLoveNote()">Drop a Love Note</button>
    <p id="loveNoteDisplay"></p>
  </section>

  <script>
    const loveNotes = [
      "You're the calm to my chaos.",
      "You laugh, and I fall all over again.",
      "You are poetry in motion.",
      "I didn’t know softness until I met you.",
      "Every time you say my name, it feels like magic."
    ];
    function generateLoveNote() {
      const note = loveNotes[Math.floor(Math.random() * loveNotes.length)];
      document.getElementById('loveNoteDisplay').innerText = note;
    }
  </script>

  <!-- Confession Box -->
  <section>
    <h2>💬 Confession Box</h2>
    <div class="input-group">
      <input type="text" id="confessionInput" placeholder="Write your soft confession here...">
      <button onclick="submitConfession()">Send</button>
      <p id="confessionOutput"></p>
    </div>
  </section>

  <script>
    function submitConfession() {
      const value = document.getElementById('confessionInput').value;
      document.getElementById('confessionOutput').innerText = `"${value}" has been sent with love 💌`;
    }
  </script>

  <!-- Quiz -->
  <section>
    <h2>🎀 Soft Love Quiz</h2>
    <p>What's her favorite place to be?</p>
    <button onclick="showQuizResult('Anywhere with me')">Anywhere with me</button>
    <button onclick="showQuizResult('Curled up in bed with tea')">Curled up in bed with tea</button>
    <button onclick="showQuizResult('By the ocean at dusk')">By the ocean at dusk</button>
    <p id="quizResult"></p>
  </section>

  <script>
    function showQuizResult(answer) {
      document.getElementById('quizResult').innerText = `Aww! She loves being ${answer.toLowerCase()} 💖`;
    }
  </script>

  <!-- Love Messages -->
  <section>
    <h2>💖 Love Messages</h2>
    <p class="quote">"She didn't need to say 'I love you' — her eyes did it for her."</p>
    <p class="quote">"We don't just finish each other's sentences — we rewrite them together."</p>
    <p class="quote">"Home isn't a place, it's her."</p>
  </section>

  <!-- Scrapbook Section -->
  <section>
    <h2>📔 Scrapbook Memories</h2>
    <div class="scrapbook">
      <div>🌊 Beach Day</div>
      <div>☕ Rainy Café</div>
      <div>🌸 First Blossoms</div>
      <div>🎶 Our Song</div>
    </div>
  </section>

</body>
</html>
