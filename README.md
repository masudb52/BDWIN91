# BDWIN91 <!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>OK.Win UI Clone</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f0f0f0;
    }
    header {
      background: linear-gradient(to right, #f857a6, #ff5858);
      color: white;
      padding: 20px;
      border-bottom-left-radius: 20px;
      border-bottom-right-radius: 20px;
    }
    .user-info {
      display: flex;
      align-items: center;
      gap: 10px;
    }
    .user-info img {
      width: 60px;
      height: 60px;
      border-radius: 50%;
    }
    .balance-box {
      background: white;
      padding: 15px;
      margin: 15px;
      border-radius: 10px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      text-align: center;
    }
    .menu-grid {
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      gap: 15px;
      padding: 0 15px;
    }
    .menu-item {
      background: white;
      padding: 10px;
      border-radius: 10px;
      text-align: center;
      box-shadow: 0 1px 4px rgba(0,0,0,0.1);
    }
    footer {
      position: fixed;
      bottom: 0;
      width: 100%;
      background: white;
      display: flex;
      justify-content: space-around;
      padding: 10px 0;
      border-top: 1px solid #ddd;
    }
    footer div {
      text-align: center;
      font-size: 14px;
      color: #666;
    }
  </style>
</head>
<body>
  <header>
    <div class="user-info">
      <img src="https://via.placeholder.com/60" alt="User Profile" />
      <div>
        <h3 style="margin: 0;">MEMBERNGMROYV</h3>
        <p style="margin: 0; font-size: 14px;">UID: 12516583<br>Last login: 2025-04-15</p>
      </div>
    </div>
  </header>  <div class="balance-box">
    <h2>Total Balance: ₹0.00</h2>
  </div>  <div class="menu-grid">
    <div class="menu-item">ARWallet</div>
    <div class="menu-item">Deposit</div>
    <div class="menu-item">Withdraw</div>
    <div class="menu-item">VIP</div>
    <div class="menu-item">Game History</div>
    <div class="menu-item">Transaction</div>
    <div class="menu-item">Deposit History</div>
    <div class="menu-item">Withdraw History</div>
  </div>  <footer>
    <div>Home</div>
    <div>Activity</div>
    <div style="color: #f857a6;">Promotion</div>
    <div>Wallet</div>
    <div>Account</div>
  </footer>
</body>
</html>
