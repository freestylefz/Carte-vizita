<html lang="ro">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Carte-vizită Valentin Nedea</title>
  <link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Open Sans', sans-serif;
      background: #fff;
      color: #333;
      padding: 20px;
    }
    .container {
      max-width: 500px;
      margin: 0 auto;
      padding: 10px;
    }

    /* QR code sus */
    .qr-code {
      text-align: left;
      margin-bottom: 20px;
    }
    .qr-code img {
      display: block;
      max-width: 200px;
      height: auto;
      margin-bottom: 8px;
    }

    /* Logo */
    .logo {
      text-align: left;
      margin-bottom: 20px;
    }
    .logo img {
      max-width: 250px;
    }

    /* Nume, titlu */
    .purple-line {
      border-left: 6px solid #a57bb3;
      padding-left: 12px;
      margin-bottom: 15px;
    }
    .name {
      font-size: 26px;
      font-weight: 400;
      text-align: left;
    }
    .surname {
      font-size: 26px;
      font-weight: 700;
      text-align: left;
    }
    .title {
      font-size: 18px;
      font-weight: 400;
      margin-bottom: 20px;
      text-align: left;
    }

    /* Contact */
    .contact-info {
      font-size: 16px;
      color: #555;
      margin-bottom: 30px;
    }
    .contact-row {
      display: flex;
      align-items: center;
      justify-content: flex-start;
      gap: 10px; /* distanță între text și buton */
      margin-bottom: 10px;
      flex-wrap: nowrap; /* buton pe aceeași linie */
    }
    .contact-row span {
      flex: 1; /* textul ocupă cât poate */
    }
    .contact-row a.button {
      display: inline-block;
      background: #a57bb3;
      color: #fff;
      padding: 6px 12px;
      border-radius: 6px;
      text-decoration: none;
      font-size: 14px;
      transition: background 0.3s;
      white-space: nowrap; /* textul nu se rupe */
    }
    .contact-row a.button:hover {
      background: #8c629a;
    }

    /* Adresă */
    .address {
      font-size: 15px;
      color: #555;
      border-top: 3px solid #a57bb3;
      padding-top: 15px;
    }

    a {
      color: inherit;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }

    @media (max-width: 600px) {
      .contact-row {
        flex-wrap: wrap; /* pe mobil, butonul poate trece sub text */
      }
      .contact-row a.button {
        margin-left: 10px;
        margin-top: 0;
      }
      .qr-code img {
        max-width: 180px;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <!-- QR sus -->
    <div class="qr-code">
      <p>Scanează QR pentru vCard</p>
      <img src="qr_nedea.jpg" alt="QR code pentru vCard">
    </div>

    <!-- Logo -->
    <div class="logo">
      <img src="logo-bca.png" alt="Logo Fortem">
    </div>

    <!-- Nume, titlu -->
    <div class="purple-line">
      <div class="name">VALENTIN</div>
      <div class="surname">NEDEA</div>
      <div class="title">Manager Zonal București & Constanța</div>
    </div>

    <!-- Contact -->
    <div class="contact-info">
      <div class="contact-row">
        <span>📞 <a href="tel:+40742063318">+4 0742 063 318</a></span>
        <a class="button" href="tel:+40742063318">Sună</a>
      </div>
      <div class="contact-row">
        <span>✉️ <a href="mailto:valentin.nedea@fortem.ro">valentin.nedea@fortem.ro</a></span>
        <a class="button" href="mailto:valentin.nedea@fortem.ro">Email</a>
      </div>
      <div class="contact-row">
        <span>📥 <a href="valentin-nedea.vcf" download>Descarcă vCard</a></span>
        <a class="button" href="valentin-nedea.vcf" download>vCard</a>
      </div>
    </div>

    <!-- Adresă -->
    <div class="address">
      Băneasa Business & Technology Park<br>
      Șoseaua București - Ploiești 42-44<br>
      Corp A, etaj 2, București, 015011
    </div>
  </div>
</body>
</html>
