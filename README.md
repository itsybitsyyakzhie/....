<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Happy Birthday, Joha!</title>
  <style>
    body {
      font-family: 'Poppins', 'Arial', sans-serif;
      background-color: #d0f5ce;
      margin: 0;
      padding: 2rem;
      color: #333;
    }
    h1, h2 {
      text-align: center;
      color: #5a8f68;
    }
    .section {
      margin: 2rem auto;
      max-width: 600px;
      background-color: #fff;
      border-radius: 20px;
      padding: 1.5rem;
      box-shadow: 0 5px 15px rgba(0,0,0,0.1);
    }
    .keypad {
      display: grid;
      grid-template-columns: repeat(5, 1fr);
      gap: 10px;
      margin-top: 1rem;
    }
    .key {
      background-color: #e7fce3;
      border: 2px solid #bde5c3;
      border-radius: 10px;
      padding: 1rem;
      text-align: center;
      cursor: pointer;
      transition: transform 0.2s ease;
    }
    .key:hover {
      transform: scale(1.1);
    }
    .output {
      margin-top: 1rem;
      background: #f8fff6;
      padding: 1rem;
      border-radius: 12px;
      min-height: 50px;
    }
    .gift {
      background: url('https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExNmQ2aTN4MXRnNzZlbmtwYnQ4aHA3MjM4NTJyNDRza3d5ZGRnaHN6bSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/6g564lKXZo796/giphy.gif')
      no-repeat center/cover;
      height: 550px;
      border-radius: 10px;
      margin-bottom: 1rem;
      cursor: pointer;
    }
    .hidden {
      display: none;
    }
    .cat {
      font-size: 1.2rem;
    }
    .before-i-forget {
      background-color: #f2ffef;
      padding: 1.5rem;
      border-radius: 12px;
      text-align: center;
      font-style: italic;
    }
  </style>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
</head>
<body>
  <h1>🐾 Happy Birthday Joha 🐹🎸</h1>

  <div class="section">
    <h2>What I Like About You 💕</h2>
    <div class="keypad">
      <div class="key" onclick="showTrait(1)">1</div>
      <div class="key" onclick="showTrait(2)">2</div>
      <div class="key" onclick="showTrait(3)">3</div>
      <div class="key" onclick="showTrait(4)">4</div>
      <div class="key" onclick="showTrait(5)">5</div>
      <div class="key" onclick="showTrait(6)">6</div>
      <div class="key" onclick="showTrait(7)">7</div>
      <div class="key" onclick="showTrait(😎">8</div>
      <div class="key" onclick="showTrait(9)">9</div>
      <div class="key" onclick="showTrait(10)">10</div>
      <div class="key" onclick="showTrait(11)">11</div>
      <div class="key" onclick="showTrait(12)">12</div>
      <div class="key" onclick="showTrait(13)">13</div>
      <div class="key" onclick="showTrait(14)">14</div>
      <div class="key" onclick="showTrait(15)">15</div>
      <div class="key" onclick="showTrait(16)">16</div>
      <div class="key" onclick="showTrait(17)">17</div>
      <div class="key" onclick="showTrait(18)">18</div>
      <div class="key" onclick="showTrait(19)">19</div>
      <div class="key" onclick="showTrait(20)">20</div>
    </div>
    <div class="output" id="trait-output">Click a number to reveal something I adore about you!</div>
  </div>

  <div class="section">
    <h2>The Birthday Letter 🎁</h2>
    <div class="gift" onclick="toggleLetter()"></div>
    <div class="hidden" id="letter">
      <h2>SURPRISEEEE ฅ́˘ฅ̀ !</h2>
      <p><strong>Happy Birthday, my babyyy Johaaa!</strong></p>
      <p>It’s wild how it’s only been a week or two by the time I send this, but you’ve already become someone I think about all the time… even when I’m eating HAAJDKDJ.</p>
      <p>From our late-night convos where we end up flustered and giggling like idiots, to you jumping around like the cutest little bunny you are, to how you somehow always know when I need to eat (you got those spidey‑senses fr). Everything you do makes me feel so safe, loved, and seen.</p>
      <p>You always listen. You remember and also somehow forget?! HAHEJSHSH. You make me feel like I matter, even when I’m being chaotic and a weirdo (›´‑`‹ ).</p>
      <p>I swear, I didn’t mean to catch feelings this fast—especially with just two days of talking—but here I am writing this like the smitten little fool I’ve become. I wouldn’t have it any other way. Fook pride, I wanna write you things like this foreverrr!! (◍•ᴗ•◍)</p>
      <p><strong>BUT DO YOU REMEMBER</strong> our late‑night texts where we go full soft‑mode, being all lovey‑dovey and straight‑up flirting? I LOVE THAT.</p>
      <p>It’s my favorite part of every day. I really hope we get to have more of those moments—only this time, in person, maybe even cuddling 😏</p>
      <p>Even though we joke around a lot, I seriously admire and love you. You’re thoughtful, patient, and you make even our simplest convos feel special.</p>
      <p>You’ve carved out a space in my heart that feels like it’s always been yours. I don’t know how, but you’ve made me soft, sweet, and open—when I’m usually just sassy as heck HAHAHA. But with you? I just smile. I never get annoyed. I just… feel happy and at ease.</p>
      <p><strong>So happy birthday</strong> to the best boy I’ve ever talked to—the most handsome, sweet, and amazing one. I hope today brings you all the joy you deserve, and more.</p>
      <p>I love youuuu my hubbyyy, Johaaa. HSJAHEJR really said “here’s your dream guy” and dropped YOU into my life (╥﹏╥)</p>
      <p>Thank you for making me the happiest, softest girl alive. I can’t wait for more birthdays to come—with me by your side, ofc. 😼😼😼</p>
    </div>
  </div>

  <div class="section" id="final-message">
    <h2>Before I Forget... 🐾</h2>
    <div class="before-i-forget">
      <p>I love you so much. For everything you are. For every message, every reel, every late‑night talk, every kiss I haven’t felt yet.</p>
      <p>Thank you for making me feel the happiest I’ve ever been. Happy Birthday, Joha.</p>
      <p>P.S. I wanna marry you so bad.</p>
    </div>
    <iframe src="https://open.spotify.com/embed/track/0T3pyPYtHAsxIRymAZsTkX?utm_source=generator&theme=0" width="100%" height="352" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture"></iframe>
  </div>

  <script>
    const traits = {
      1: "Your caring personality",
      2: "How you assure me even though I don’t need it",
      3: "How you let me be my unfiltered, chaotic self and still think I’m cute",
      4: "Your charm that always brings me happiness",
      5: "How you listen to my random topics",
      6: "Your effort in updating me every day",
      7: "How you freak out over my selfies and video of me smiling",
      8: "Your (virtual) hugs and kisses",
      9: 'When you call me "love," "baby," "darling," and "wifey"',
      10: "Your bunny jumps",
      11: "When you understand me in ways people don’t",
      12: "How you genuinely care for me",
      13: "Your soothing voice",
      14: "How you respect my space but still make me feel close",
      15: "How you smother me with kisses, love, and affection",
      16: "How you always know when I'm hungry or not",
      17: "How you're not afraid of showing me your vulnerable side",
      18: "Your sense of humor",
      19: "Your handsomeness, cuteness and everything",
      20: "Everything."
    };

    function showTrait(num) {
      document.getElementById('trait-output').innerText = traits[num];
    }

    function toggleLetter() {
      const letter = document.getElementById('letter');
      letter.classList.toggle('hidden');
    }
  </script>
</body>
</html>
