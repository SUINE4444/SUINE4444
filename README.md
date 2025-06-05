 <!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Judi Online Terpercaya</title>
<style>
  body {
    margin: 0; 
    font-family: Arial, sans-serif; 
    background-color: #121212;
    color: #fff;
  }
  header {
    background: linear-gradient(90deg, #8b0000, #ff0000);
    padding: 20px;
    text-align: center;
    font-size: 2rem;
    font-weight: bold;
    letter-spacing: 2px;
  }
  nav {
    background-color: #1f1f1f;
    display: flex;
    justify-content: center;
    gap: 30px;
    padding: 15px 0;
  }
  nav a {
    color: #ff4444;
    text-decoration: none;
    font-weight: bold;
    font-size: 1.1rem;
    transition: color 0.3s;
  }
  nav a:hover {
    color: #ff0000;
  }
  main {
    max-width: 900px;
    margin: 30px auto;
    padding: 0 15px;
  }
  .promo {
    background: #330000;
    border-radius: 10px;
    padding: 20px;
    margin-bottom: 30px;
    text-align: center;
    font-size: 1.3rem;
    font-weight: bold;
    color: #ff6666;
  }
  .games {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
    gap: 20px;
  }
  .game-card {
    background-color: #1b1b1b;
    border: 1px solid #ff0000;
    border-radius: 8px;
    padding: 15px;
    cursor: pointer;
    transition: background-color 0.3s;
  }
  .game-card:hover {
    background-color: #330000;
  }
  .game-title {
    font-size: 1.2rem;
    margin-bottom: 10px;
  }
  .bet-section {
    margin-top: 20px;
  }
  label, input, button {
    display: block;
    margin: 8px 0;
  }
  input[type="number"] {
    width: 100%;
    padding: 8px;
    border: none;
    border-radius: 5px;
  }
  button {
    background-color: #ff0000;
    border: none;
    padding: 10px;
    color: white;
    font-weight: bold;
    border-radius: 5px;
    cursor: pointer;
    width: 100%;
  }
  button:hover {
    background-color: #cc0000;
  }
  .history {
    margin-top: 30px;
    background-color: #220000;
    border-radius: 8px;
    padding: 15px;
    max-height: 150px;
    overflow-y: auto;
  }
  .history h3 {
    margin-top: 0;
    color: #ff6666;
  }
  .login-register {
    max-width: 350px;
    margin: 30px auto;
    background-color: #1f1f1f;
    border: 1px solid #ff0000;
    padding: 20px;
    border-radius: 8px;
  }
  .login-register h2 {
    margin-top: 0;
    color: #ff4444;
    text-align: center;
  }
  .login-register input {
    width: 100%;
    padding: 8px;
    margin: 8px 0;
    border: none;
    border-radius: 5px;
  }
  .chat-box {
    position: fixed;
    bottom: 20px;
    right: 20px;
    width: 300px;
    max-height: 400px;
    background-color: #1b1b1b;
    border: 1px solid #ff0000;
    border-radius: 8px;
    display: flex;
    flex-direction: column;
  }
  .chat-header {
    background: #330000;
    padding: 10px;
    color: #ff6666;
    font-weight: bold;
    text-align: center;
  }
  .chat-messages {
    flex-grow: 1;
    padding: 10px;
    overflow-y: auto;
    color: #fff;
  }
  .chat-input {
    display: flex;
    border-top: 1px solid #ff0000;
  }
  .chat-input input {
    flex-grow: 1;
    padding: 10px;
    border: none;
    border-radius: 0 0 0 8px;
    background-color: #121212;
    color: white;
  }
  .chat-input button {
    background-color: #ff0000;
    border: none;
    padding: 10px 15px;
    cursor: pointer;
    color: white;
    border-radius: 0 0 8px 0;
  }
</style>
</head>
<body>

<header>JUDI ONLINE TERPERCAYA</header>
<nav>
  <a href="#promo">Promo</a>
  <a href="#games">Game</a>
  <a href="#history">Riwayat</a>
  <a href="#login">Login/Register</a>
</nav>

<main>
  <section id="promo" class="promo">
    🎉 Bonus Deposit 100% untuk Member Baru! 🎉
  </section>

  <section id="games" class="games">
    <div class="game-card" data-game="Slot">
      <div class="game-title">Slot Online</div>
      <div>Taruhan mulai dari Rp 10.000</div>
      <div class="bet-section">
        <label>Jumlah Taruhan (Rp):</label>
        <input type="number" min="10000" step="10000" value="10000" />
        <button onclick="placeBet(this)">Pasang Taruhan</button>
      </div>
    </div>
    <div class="game-card" data-game="Poker">
      <div class="game-title">Poker</div>
      <div>Taruhan mulai dari Rp 50.000</div>
      <div class="bet-section">
        <label>Jumlah Taruhan (Rp):</label>
        <input type="number" min="50000" step="50000" value="50000" />
        <button onclick="placeBet(this)">Pasang Taruhan</button>
      </div>
    </div>
    <div class="game-card" data-game="Togel">
      <div class="game-title">Togel</div>
      <div>Taruhan mulai dari Rp 5.000</div>
      <div class="bet-section">
        <label>Jumlah Taruhan (Rp):</label>
        <input type="number" min="5000" step="5000" value="5000" />
        <button onclick="placeBet(this)">Pasang Taruhan</button>
      </div>
    </div>
  </section>

  <section id="history" class="history">
    <h3>Riwayat Taruhan</h3>
    <ul id="betHistory"></ul>
  </section>

  <section id="login" class="login-register">
    <h2>Login / Register</h2>
    <input type="text" id="username" placeholder="Username" />
    <input type="password" id="password" placeholder="Password" />
    <button onclick="login()">Login</button>
    <button onclick="register()">Register</button>
    <p id="loginMsg" style="color: #ff6666;"></p>
  </section>
</main>

<div class="chat-box" id="chatBox">
  <div class="chat-header">Live Chat Support</div>
  <div class="chat-messages" id="chatMessages"></div>
  <div class="chat-input">
    <input type="text" id="chatInput" placeholder="Tulis pesan..." />
    <button onclick="sendMessage()">Kirim</button>
  </div>
</div>

<script>
  let loggedInUser = null;
  let betHistory = [];

  function placeBet(button) {
    if (!loggedInUser) {
      alert("Silakan login dulu untuk memasang taruhan.");
      return;
    }
    const card = button.closest('.game-card');
    const gameName = card.dataset.game;
    const input = card.querySelector('input[type="number"]');
    const betAmount = parseInt(input.value);
    if (isNaN(betAmount) || betAmount <= 0) {
      alert("Masukkan jumlah taruhan yang valid.");
      return;
    }
    // Simulasi hasil taruhan (menang/kalah random)
    const win = Math.random() < 0.5;
    const resultText = win ? "MENANG" : "KALAH";
    const resultColor = win ? "green" : "red";

    const historyEntry = {
      user: loggedInUser,
      game: gameName,
      amount: betAmount,
      result: resultText,
      time: new Date().toLocaleString()
    };
    betHistory.push(historyEntry);
    updateHistory();

    alert(`Taruhan ${gameName} sebesar Rp ${betAmount} kamu ${resultText}!`);
  }

  function updateHistory() {
    const historyList = document.getElementById('betHistory');
    historyList.innerHTML = '';
    betHistory.slice(-10).reverse().forEach(entry => {
      const li = document.createElement('li');
      li.textContent = `${entry.time} - ${entry.user} - ${entry.game} - Rp ${entry.amount} - ${entry.result}`;
      li.style.color = entry.result === "MENANG" ? "lightgreen" : "salmon";
      historyList.appendChild(li);
    });
  }

  function login() {
    const username = document.getElementById('username').value.trim();
    const password = document.getElementById('password').value.trim();
    const msg = document.getElementById('loginMsg');

    if (!username || !password) {
      msg.textContent = "Isi username dan password.";
      return;
    }
    // Simulasi login sederhana (tidak aman)
    if (localStorage.getItem(`user_${username}`) === password) {
      loggedInUser = username;
      msg.style.color = 'lightgreen';
      msg.textContent = `Selamat datang, ${username}!`;
    } else {
      msg.style.color = 'salmon';
      msg.textContent = "Username atau password salah.";
    }
  }

  function register() {
    const username = document.getElementById('username').value.trim();
    const password = document.getElementById('password').value.trim();
    const msg = document.getElementById('loginMsg');

    if (!username || !password) {
      msg.textContent = "Isi username dan password.";
      return;
    }
    if (localStorage.getItem(`user_${username}`)) {
      msg.style.color = 'salmon';
      msg.textContent = "Username sudah digunakan.";
      return;
    }
    // Simpan user ke localStorage (hanya simulasi)
    localStorage.setItem(`user_${username}`, password);
    loggedInUser = username;
    msg.style.color = 'lightgreen';
    msg.textContent = `Registrasi berhasil. Selamat datang, ${username}!`;
  }

  // Chat sederhana (hanya simpan di client)
  const chatMessages = document.getElementById('chatMessages');
  const chatInput = document.getElementById('chatInput');

  function sendMessage() {
    const msg = chatInput.value.trim();
    if (!msg) return;

    const user = loggedInUser || "Tamu";
    const messageElement = document.createElement('div');
    messageElement.textContent = `${user}: ${msg}`;
    chatMessages.appendChild(messageElement);
    chatMessages.scrollTop = chatMessages.scrollHeight;
    chatInput.value = '';

    // Simulasi balasan otomatis
    setTimeout(() => {
      const botMsg = document.createElement('div');
      botMsg.textContent = "Support: Terima kasih atas pesan Anda. Kami akan segera merespons.";
      botMsg.style.color = '#ff4444';
      chatMessages.appendChild(botMsg);
      chatMessages.scrollTop = chatMessages.scrollHeight;
    }, 1500);
  }
</script>

</body>
</html>
