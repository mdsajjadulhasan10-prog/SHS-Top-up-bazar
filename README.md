# SHS-Top-up-bazar
Diamond top up 
<!DOCTYPE html>
<html lang="bn">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>SHS TOP-UP BAZAR</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background: #0b1020;
      color: white;
    }

    header {
      text-align: center;
      padding: 28px 15px;
      background: linear-gradient(135deg, #111827, #172554);
      border-bottom: 2px solid #2563eb;
    }

    header h1 {
      font-size: 28px;
      color: #38bdf8;
    }

    header p {
      margin-top: 8px;
      color: #cbd5e1;
    }

    .container {
      max-width: 550px;
      margin: auto;
      padding: 18px;
    }

    .box {
      background: #111827;
      border-radius: 18px;
      padding: 20px;
      margin-bottom: 20px;
      box-shadow: 0 8px 25px rgba(0,0,0,0.35);
    }

    .box h2 {
      text-align: center;
      color: #38bdf8;
      margin-bottom: 18px;
    }

    input {
      width: 100%;
      padding: 14px;
      margin-bottom: 12px;
      border: 1px solid #334155;
      border-radius: 10px;
      background: #1e293b;
      color: white;
      font-size: 16px;
      outline: none;
    }

    input::placeholder {
      color: #94a3b8;
    }

    .section-title {
      margin: 18px 0 12px;
      color: #facc15;
      font-size: 18px;
    }

    .packages {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 12px;
    }

    .package {
      background: #1e293b;
      border: 2px solid transparent;
      border-radius: 13px;
      padding: 15px 8px;
      text-align: center;
      cursor: pointer;
      transition: 0.2s;
    }

    .package:hover {
      border-color: #38bdf8;
      transform: translateY(-2px);
    }

    .package.selected {
      border-color: #22c55e;
      background: #172f27;
    }

    .diamond {
      font-size: 24px;
    }

    .package h3 {
      margin-top: 7px;
      color: #60a5fa;
      font-size: 17px;
    }

    .price {
      margin-top: 5px;
      color: #facc15;
      font-weight: bold;
    }

    button {
      width: 100%;
      padding: 15px;
      margin-top: 18px;
      border: none;
      border-radius: 11px;
      background: #22c55e;
      color: white;
      font-size: 18px;
      font-weight: bold;
      cursor: pointer;
    }

    button:hover {
      background: #16a34a;
    }

    .selected-info {
      margin-top: 15px;
      padding: 12px;
      border-radius: 10px;
      background: #1e293b;
      text-align: center;
      color: #cbd5e1;
    }

    .notice {
      margin-top: 15px;
      padding: 12px;
      background: #29210b;
      border-radius: 10px;
      color: #facc15;
      text-align: center;
      font-size: 13px;
    }

    footer {
      text-align: center;
      padding: 25px 10px;
      color: #94a3b8;
      font-size: 14px;
    }
  </style>
</head>

<body>

<header>
  <h1>💎 SHS TOP-UP BAZAR</h1>
  <p>Free Fire Diamond & Pass Top-Up</p>
</header>


<div class="container">

  <!-- PLAYER INFO -->

  <div class="box">

    <h2>🆔 Player Information</h2>

    <input
      type="text"
      id="uid"
      placeholder="Free Fire UID লিখুন"
    >

    <input
      type="text"
      id="playerName"
      placeholder="Player Name লিখুন"
    >

  </div>


  <!-- DIAMOND -->

  <div class="box">

    <h2>💎 Diamond</h2>

    <div class="packages">

      <div class="package"
           onclick="selectPackage(this, '25 Diamonds', 25)">
        <div class="diamond">💎</div>
        <h3>25 Diamonds</h3>
        <div class="price">৳25</div>
      </div>


      <div class="package"
           onclick="selectPackage(this, '50 Diamonds', 40)">
        <div class="diamond">💎</div>
        <h3>50 Diamonds</h3>
        <div class="price">৳40</div>
      </div>


      <div class="package"
           onclick="selectPackage(this, '100 Diamonds', 75)">
        <div class="diamond">💎</div>
        <h3>100 Diamonds</h3>
        <div class="price">৳75</div>
      </div>


      <div class="package"
           onclick="selectPackage(this, '240 Diamonds', 150)">
        <div class="diamond">💎</div>
        <h3>240 Diamonds</h3>
        <div class="price">৳150</div>
      </div>


      <div class="package"
           onclick="selectPackage(this, '505 Diamonds', 340)">
        <div class="diamond">💎</div>
        <h3>505 Diamonds</h3>
        <div class="price">৳340</div>
      </div>


      <div class="package"
           onclick="selectPackage(this, '1090 Diamonds', 670)">
        <div class="diamond">💎</div>
        <h3>1090 Diamonds</h3>
        <div class="price">৳670</div>
      </div>


      <div class="package"
           onclick="selectPackage(this, '2530 Diamonds', 1550)">
        <div class="diamond">💎</div>
        <h3>2530 Diamonds</h3>
        <div class="price">৳1550</div>
      </div>


      <div class="package"
           onclick="selectPackage(this, '5060 Diamonds', 3100)">
        <div class="diamond">💎</div>
        <h3>5060 Diamonds</h3>
        <div class="price">৳3100</div>
      </div>

    </div>

  </div>


  <!-- PASS -->

  <div class="box">

    <h2>🎫 Special Pass</h2>

    <div class="packages">

      <div class="package"
           onclick="selectPackage(this, 'Weekly Pass', 145)">
        <div class="diamond">🎫</div>
        <h3>Weekly Pass</h3>
        <div class="price">৳145</div>
      </div>


      <div class="package"
           onclick="selectPackage(this, 'Monthly Pass', 750)">
        <div class="diamond">🎫</div>
        <h3>Monthly Pass</h3>
        <div class="price">৳750</div>
      </div>


      <div class="package"
           onclick="selectPackage(this, 'Level Up Pass', 300)">
        <div class="diamond">🚀</div>
        <h3>Level Up Pass</h3>
        <div class="price">৳300</div>
      </div>

    </div>


    <div class="selected-info" id="selectedInfo">
      কোনো package নির্বাচন করা হয়নি
    </div>


    <button onclick="orderNow()">
      🛒 Order Now
    </button>


    <div class="notice">
      ⚠️ এটি Demo website। বর্তমানে কোনো আসল payment নেওয়া হচ্ছে না।
    </div>

  </div>

</div>


<footer>
  © 2026 SHS TOP-UP BAZAR
</footer>


<script>

  let selectedPackage = "";
  let selectedPrice = 0;


  function selectPackage(element, packageName, price) {

    document.querySelectorAll(".package").forEach(function(item) {
      item.classList.remove("selected");
    });

    element.classList.add("selected");

    selectedPackage = packageName;
    selectedPrice = price;

    document.getElementById("selectedInfo").innerHTML =
      "✅ Selected: <b>" +
      packageName +
      "</b> — ৳" +
      price;
  }


  function orderNow() {

    let uid = document.getElementById("uid").value.trim();
    let playerName = document.getElementById("playerName").value.trim();


    if (uid === "") {
      alert("দয়া করে আপনার Free Fire UID লিখুন।");
      return;
    }


    if (playerName === "") {
      alert("দয়া করে Player Name লিখুন।");
      return;
    }


    if (selectedPackage === "") {
      alert("দয়া করে একটি Package নির্বাচন করুন।");
      return;
    }


    alert(
      "🎉 Demo Order তৈরি হয়েছে!\n\n" +
      "UID: " + uid + "\n" +
      "Player: " + playerName + "\n" +
      "Package: " + selectedPackage + "\n" +
      "Price: ৳" + selectedPrice +
      "\n\nবর্তমানে এটি শুধু Demo।"
    );

  }

</script>

</body>
</html>
