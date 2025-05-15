# CryptoKing<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Crypto King Academy - Booking & Course Info</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0; padding: 20px;
      background: #fff5f5;
      color: #660000;
    }
    .container {
      max-width: 900px;
      margin: 0 auto;
      background: white;
      padding: 30px 40px;
      border-radius: 12px;
      box-shadow: 0 4px 15px rgba(102, 0, 0, 0.2);
      border: 2px solid #cc0000;
    }
    h1, h2, h3 {
      color: #cc0000;
    }
    h1 {
      font-size: 2.4rem;
      margin-bottom: 0.4em;
    }
    h2 {
      margin-top: 1.6em;
      margin-bottom: 0.6em;
    }
    h3 {
      margin-top: 1.2em;
      margin-bottom: 0.4em;
    }
    p, li {
      line-height: 1.5;
      margin-bottom: 1em;
    }
    ul {
      padding-left: 20px;
      margin-bottom: 1.2em;
    }
    .payment-instructions {
      background: #ffe5e5;
      border-left: 5px solid #cc0000;
      padding: 15px 20px;
      margin-bottom: 30px;
      border-radius: 8px;
      white-space: pre-line;
    }
    a.button-book {
      background-color: #cc0000;
      color: white;
      padding: 15px 30px;
      border-radius: 10px;
      font-size: 1.2rem;
      font-weight: 700;
      text-decoration: none;
      display: inline-block;
      margin-bottom: 30px;
    }
    iframe {
      width: 100%;
      height: 600px;
      border: none;
      border-radius: 12px;
      box-shadow: 0 4px 20px rgba(204, 0, 0, 0.2);
    }
    form {
      margin-top: 30px;
    }
    label {
      display: block;
      margin-bottom: 6px;
      font-weight: 600;
      margin-top: 15px;
      color: #990000;
    }
    input[type="text"], input[type="email"], input[type="tel"] {
      width: 100%;
      padding: 10px;
      font-size: 1rem;
      border-radius: 6px;
      border: 1px solid #cc0000;
      box-sizing: border-box;
    }
    button[type="submit"] {
      background-color: #cc0000;
      color: white;
      border: none;
      padding: 15px 30px;
      font-size: 1.1rem;
      border-radius: 10px;
      margin-top: 20px;
      cursor: pointer;
    }
    button[type="submit"]:hover {
      background-color: #990000;
    }
    footer {
      text-align: center;
      color: #aa0000;
      margin-top: 50px;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Crypto King Academy - Booking & Course Info</h1>
    <p><strong>Hello<br>How are you dear? Hope Your doing well?</strong></p>

    <p><strong>Would you like :?</strong><br />
      Group class 15000rs<br />
      Private class 25000rs<br />
      5 Lesson (si ou bizin encor Apre 5 em lesson ou pa Bizin Re Pay Moi encor)
    </p>

    <h2>Course Outline</h2>
    <h3>What you will Learn :</h3>
    <p>
      1st Lesson Zot Pu Apprand<br />
      - Notes 20 Pages<br />
      - Zot Pour recevoir 10 File En PDF Pour Zot Apprend Kuma Trade Daily
    </p>
    <p>
      2nd Lesson Zot Pu Apprand:<br />
      - Explikation Notes From First Class<br />
      - Kuma Pour Track Ban Crypto Coin Dans Crypto Market<br />
      - Kuma Track Crypto Graphs<br />
      - Kuma Pour Hold Crypto Coin Long Term<br />
      - Crypto Transactions
    </p>
    <p>
      3rd Lesson Zot Pu Apprand:<br />
      - Technical Analysis Lor Tradingview<br />
      - Trading Patterns
    </p>
    <p>
      4th Lesson Zot Pu Apprand<br />
      - Practice Session
    </p>
    <p>
      5th Lesson Zot Pu Apprand<br />
      - Kuma Withdraw Lor Binance<br />
      - Kuma Trade Daliy Lor Binance<br />
      - Trade Ensam Avec moi Crypto King<br />
      - Using the Best Indicators/Patterns to trade
    </p>

    <h2>Payment</h2>
    <p>Select Pay by local Bank</p>

    <h2>Payment Instructions</h2>
    <div class="payment-instructions">
      Pay via <strong>Juice (MCB)</strong> app:
      <ul>
        <li><strong>Bank:</strong> SBM</li>
        <li><strong>Beneficiary Name:</strong> Computer Tech</li>
        <li><strong>Account Number:</strong> 01710100215482</li>
        <li><strong>Amount:</strong> Rs 15,000 (Group) / Rs 25,000 (Private)</li>
        <li><strong>Description:</strong> Computer Tech</li>
        <li><strong>Important:</strong> Turn ON the <em>Instant Transfer</em> option before confirming payment.</li>
      </ul>
      Send payment screenshot to WhatsApp: <a href="https://wa.me/23055112258" target="_blank">+230 5511 2258</a>
    </div>

    <h2>Book Your First Session</h2>
    <p>Choose your preferred date and time for your first class using the calendar below.</p>

    <iframe
      src="https://calendly.com/cryptoking-mauritius/first-session"
      allowtransparency="true"
    ></iframe>

    <h2>After Payment - Booking Details</h2>
    <p>Please provide your booking details below after making your payment:</p>
    <form id="bookingForm" onsubmit="return handleSubmit(event)">
      <label for="fullname">Full Name *</label>
      <input type="text" id="fullname" name="fullname" required />

      <label for="lastname">Last Name *</label>
      <input type="text" id="lastname" name="lastname" required />

      <label for="phone">Phone Number *</label>
      <input type="tel" id="phone" name="phone" required pattern="[0-9+ ]{7,15}" placeholder="+230 5511 2258" />

      <label for="email">Email *</label>
      <input type="email" id="email" name="email" required />

      <button type="submit">Submit Booking Details</button>
    </form>
  </div>

  <footer>
    &copy; 2025 Crypto King Academy. All rights reserved.
  </footer>

  <script>
    function handleSubmit(e) {
      e.preventDefault();
      const form = e.target;
      const fullname = form.fullname.value.trim();
      const lastname = form.lastname.value.trim();
      const phone = form.phone.value.trim();
      const email = form.email.value.trim();

      if (!fullname || !lastname || !phone || !email) {
        alert('Please fill in all required fields.');
        return false;
      }

      alert(`Thank you, ${fullname}! Your booking details have been received. We will contact you soon.`);

      form.reset();
      return false;
    }
  </script>
</body>
</html>
