<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>MOBE LOBBY</title>
  <link rel="icon" href="https://assets.onecompiler.app/42swzbgaa/433g7msea/1000049145.png" type="image/png">
  
  <!-- Font Awesome -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  
  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&display=swap" rel="stylesheet">
  
  <style>
    :root {
      --primary: #00FFCD;
      --secondary: #0099FF;
      --accent: #FF00AA;
      --dark: #0A0A2A;
      --light: #E0F8FF;
      --glow: 0 0 15px currentColor;
    }
    
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    
    body {
      font-family: 'Orbitron', sans-serif;
      background: linear-gradient(135deg, #0f0c29, #302b63, #24243e);
      color: var(--light);
      min-height: 100vh;
      overflow-x: hidden;
    }
    
    /* Ping Display */
    .ping-container {
      position: fixed;
      top: 10px;
      right: 10px;
      display: flex;
      align-items: center;
      background-color: rgba(10, 10, 42, 0.8);
      padding: 6px 12px;
      border-radius: 20px;
      border: 1px solid var(--primary);
      box-shadow: 0 0 10px rgba(0, 255, 205, 0.3);
      z-index: 100;
      backdrop-filter: blur(5px);
    }
    
    .ping-icon {
      width: 16px;
      height: 16px;
      margin-right: 8px;
      color: var(--primary);
    }
    
    .ping-value {
      font-size: 12px;
      font-weight: bold;
      margin-left: 4px;
    }
    
    .ping-value.excellent {
      color: lime;
    }
    
    .ping-value.good {
      color: #00FFCD;
    }
    
    .ping-value.fair {
      color: yellow;
    }
    
    .ping-value.poor {
      color: orange;
    }
    
    .ping-value.bad {
      color: red;
    }
    
    .no-connection {
      color: red;
    }
    
    /* Main Container */
    .lobby-container {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      padding: 20px;
      position: relative;
    }
    
    /* Header */
    .lobby-header {
      text-align: center;
      margin-bottom: 20px;
    }
    
    .lobby-title {
      font-size: 2rem;
      color: var(--primary);
      text-shadow: 0 0 10px var(--primary);
      margin-bottom: 5px;
      letter-spacing: 2px;
    }
    
    .lobby-subtitle {
      font-size: 1rem;
      color: var(--secondary);
      letter-spacing: 1px;
    }
    
    /* Leaderboard */
    .leaderboard {
      background-color: rgba(10, 10, 42, 0.8);
      padding: 15px;
      border-radius: 10px;
      width: 100%;
      max-width: 400px;
      border: 1px solid var(--secondary);
      box-shadow: 0 0 15px rgba(0, 153, 255, 0.3);
      backdrop-filter: blur(5px);
      margin-bottom: 20px;
    }
    
    .leaderboard-title {
      font-size: 1.2rem;
      color: var(--primary);
      text-align: center;
      margin-bottom: 15px;
      letter-spacing: 1px;
    }
    
    .player-list {
      list-style: none;
    }
    
    .player-item {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 10px;
      margin: 5px 0;
      background-color: rgba(0, 0, 0, 0.3);
      border-radius: 5px;
      border-left: 2px solid var(--primary);
    }
    
    .player-name {
      font-size: 0.9rem;
      font-weight: bold;
    }
    
    .player-score {
      color: var(--primary);
      font-weight: bold;
      font-size: 0.9rem;
    }
    
    .player-badge {
      margin-left: 5px;
      font-size: 0.8rem;
    }
    
    /* Buttons */
    .action-buttons {
      display: flex;
      flex-direction: column;
      gap: 15px;
      width: 100%;
      max-width: 400px;
    }
    
    .btn {
      padding: 12px 20px;
      border: none;
      border-radius: 5px;
      font-family: 'Orbitron', sans-serif;
      font-size: 1rem;
      font-weight: bold;
      cursor: pointer;
      transition: all 0.2s ease;
    }
    
    .btn-primary {
      background: linear-gradient(45deg, var(--primary), var(--secondary));
      color: var(--dark);
    }
    
    .btn-secondary {
      background: linear-gradient(45deg, var(--secondary), var(--accent));
      color: white;
    }
    
    .btn:hover {
      transform: translateY(-2px);
      box-shadow: 0 5px 10px rgba(0, 0, 0, 0.3);
    }
    
    .btn:active {
      transform: translateY(0);
    }
    
    /* Social Icons */
    .social-container {
      display: flex;
      justify-content: center;
      gap: 20px;
      margin-top: 30px;
    }
    
    .social-icon {
      color: var(--light);
      font-size: 1.5rem;
      transition: all 0.2s ease;
    }
    
    .social-icon:hover {
      color: var(--primary);
      transform: translateY(-3px);
    }
    
    /* Loading State */
    .loading-message {
      text-align: center;
      padding: 20px;
      color: var(--secondary);
    }
    
    /* Responsive */
    @media (min-width: 768px) {
      .lobby-title {
        font-size: 2.5rem;
      }
      
      .action-buttons {
        flex-direction: row;
        justify-content: center;
      }
      
      .btn {
        padding: 12px 25px;
      }
    }
  </style>
</head>
<body>
  <!-- Ping Display -->
  <div class="ping-container">
    <i class="fas fa-wifi ping-icon"></i>
    <span id="pingStatus" class="no-connection">Checking...</span>
    <span id="pingValue" class="ping-value"></span>
  </div>
  
  <!-- Main Content -->
  <div class="lobby-container">
    <div class="lobby-header">
      <h1 class="lobby-title">MOBE</h1>
      <p class="lobby-subtitle">BATTLE ARENA</p>
    </div>
    
    <div class="leaderboard">
      <h2 class="leaderboard-title" id="leaderboardTitle">LOADING PLAYERS...</h2>
      <ul class="player-list" id="playerList">
        <li class="loading-message">Connecting to database...</li>
      </ul>
    </div>
    
    <div class="action-buttons">
      <button class="btn btn-primary" id="playMultiplayerBtn">
        <i class="fas fa-users"></i> MOBE & MOBE
      </button>
      <button class="btn btn-secondary" id="trainingBtn">
        <i class="fas fa-dumbbell"></i> CREATE SKILL
      </button>
    </div>
    
    <div class="social-container">
      <a href="https://roy9957.github.io/MOBE-SPACE-JOURNEY/" target="_blank" class="social-icon">
        <i class="fas fa-globe"></i>
      </a>
      <a href="https://discord.gg/cGh65u7FN3" target="_blank" class="social-icon">
        <i class="fab fa-discord"></i>
      </a>
      <a href="share.html" class="social-icon">
        <i class="fas fa-share-alt"></i>
      </a>
    </div>
  </div>
  
  <!-- Firebase & Game SDK -->
  <script src="https://www.gstatic.com/firebasejs/8.10.0/firebase-app.js"></script>
  <script src="https://www.gstatic.com/firebasejs/8.10.0/firebase-database.js"></script>
  
  <script>
    // Firebase Configuration
    const firebaseConfig = {
      apiKey: "AIzaSyCrQJRwfTV8a1BIwMQexWxsHi2OKyTj8hg",
      authDomain: "artificial-intelligence-55880.firebaseapp.com",
      databaseURL: "https://artificial-intelligence-55880-default-rtdb.asia-southeast1.firebasedatabase.app",
      projectId: "artificial-intelligence-55880",
      storageBucket: "artificial-intelligence-55880.appspot.com",
      messagingSenderId: "985195404301",
      appId: "1:985195404301:web:12aea7b9c4719b6bdb0944"
    };
    
    // Initialize Firebase
    firebase.initializeApp(firebaseConfig);
    const database = firebase.database();
    
    // Server Configuration
    const SERVER_URL = "https://game-server-five.vercel.app";
    const PING_INTERVAL = 5000; // 5 seconds
    
    // DOM Elements
    const pingStatusEl = document.getElementById('pingStatus');
    const pingValueEl = document.getElementById('pingValue');
    const leaderboardTitleEl = document.getElementById('leaderboardTitle');
    const playerListEl = document.getElementById('playerList');
    const playMultiplayerBtn = document.getElementById('playMultiplayerBtn');
    const trainingBtn = document.getElementById('trainingBtn');
    
    // Initialize
    document.addEventListener('DOMContentLoaded', () => {
      // Start checking server connection
      checkServerConnection();
      setInterval(checkServerConnection, PING_INTERVAL);
      
      // Load players from Firebase
      loadPlayers();
      
      // Button event listeners
      playMultiplayerBtn.addEventListener('click', () => {
        alert("GAME TIPS:\n\n• Check your internet connection\n• Monitor your ping for best performance\n• Touch to move\n• Tap to fire\n• Always watch your health\n• Destroy all enemies!");
        setTimeout(() => {
          window.location.href = "game.html";
        }, 500);
      });
      
      trainingBtn.addEventListener('click', () => {
        window.location.href = "train.html";
      });
    });
    
    // Check server connection and measure ping
    async function checkServerConnection() {
      const startTime = Date.now();
      
      try {
        const response = await fetch(`${SERVER_URL}/api/health`, {
          method: 'GET',
          cache: 'no-store'
        });
        
        if (response.ok) {
          const ping = Date.now() - startTime;
          updatePingDisplay(ping);
          return true;
        } else {
          throw new Error('Server error');
        }
      } catch (error) {
        console.error("Connection error:", error);
        pingStatusEl.textContent = "OFFLINE";
        pingStatusEl.className = "no-connection";
        pingValueEl.textContent = "";
        return false;
      }
    }
    
    // Update ping display with appropriate styling
    function updatePingDisplay(ping) {
      pingStatusEl.textContent = "ONLINE";
      pingValueEl.textContent = `${ping}ms`;
      
      // Remove all classes
      pingStatusEl.className = "";
      pingValueEl.className = "ping-value";
      
      // Add appropriate class based on ping
      if (ping <= 100) {
        pingValueEl.classList.add('excellent');
      } else if (ping <= 200) {
        pingValueEl.classList.add('good');
      } else if (ping <= 350) {
        pingValueEl.classList.add('fair');
      } else if (ping <= 500) {
        pingValueEl.classList.add('poor');
      } else {
        pingValueEl.classList.add('bad');
      }
    }
    
    // Load players from Firebase
    function loadPlayers() {
      const playersRef = database.ref('players');
      
      playersRef.on('value', (snapshot) => {
        const playersData = snapshot.val();
        updateLeaderboard(playersData);
      }, (error) => {
        console.error("Firebase error:", error);
        playerListEl.innerHTML = '<li class="loading-message">Error loading players</li>';
      });
    }
    
    // Update leaderboard with real players
    function updateLeaderboard(playersData) {
      if (!playersData) {
        leaderboardTitleEl.textContent = "NO PLAYERS ONLINE";
        playerListEl.innerHTML = '<li class="loading-message">Waiting for players to join...</li>';
        return;
      }
      
      // Convert players object to array and sort by score
      const playersArray = Object.values(playersData);
      playersArray.sort((a, b) => b.score - a.score);
      
      leaderboardTitleEl.textContent = "ONLINE PLAYERS";
      playerListEl.innerHTML = "";
      
      if (playersArray.length === 0) {
        playerListEl.innerHTML = '<li class="loading-message">No active players</li>';
        return;
      }
      
      playersArray.forEach((player, index) => {
        const playerEl = document.createElement('li');
        playerEl.className = 'player-item';
        
        // Determine badge based on score
        let badge = '';
        if (player.score >= 500) {
          badge = '<span class="player-badge" style="color: #FFD700;">👑</span>';
        } else if (player.score >= 300) {
          badge = '<span class="player-badge" style="color: #C0C0C0;">🥈</span>';
        } else if (player.score >= 100) {
          badge = '<span class="player-badge" style="color: #CD7F32;">🥉</span>';
        }
        
        playerEl.innerHTML = `
          <span class="player-name">${player.id || 'Anonymous'}</span>
          <div>
            <span class="player-score">${player.score || 0}</span>
            ${badge}
          </div>
        `;
        
        playerListEl.appendChild(playerEl);
      });
    }
    
    // Share function
    function sharePage() {
      if (navigator.share) {
        navigator.share({
          title: 'MOBE WINTERLAND',
          text: 'Join me in MOBE WINTERLAND - the ultimate battle arena!',
          url: window.location.href
        }).catch(err => {
          console.log('Error sharing:', err);
          fallbackShare();
        });
      } else {
        fallbackShare();
      }
    }
    
    function fallbackShare() {
      const shareUrl = window.location.href;
      prompt("Copy this link to share:", shareUrl);
    }
  </script>
</body>
</html>
