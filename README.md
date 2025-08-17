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

    /* Header cu logo și nume */
    .header {
      display: flex;
      align-items: flex-start;
      gap: 15px;
      margin-bottom: 20px;
    }
    .header img {
      max-width: 120px;
    }
    .name-block {
      display: flex;
      flex-direction: column;
    }
    .name-block .name {
      font-size: 26px;
      font-weight: 400;
    }
    .name-block .surname {
      font-size: 26px;
      font-weight: 700;
    }
    .name-block .title {
      font-size: 18px;
      font-weight: 400;
      margin-top: 4px;
    }

    /* Linia mov decorativă */
    .purple-line {
      border-left: 6px solid #a57bb3;
      padding-left: 12px;
      margin-bottom: 20px;
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
      gap: 10px;
      margin-bottom: 10px;
      flex-wrap: wrap;
    }
    .contact-row span {
      flex: 1;
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
    }
    .contact-row a.button:hover {
      background: #8c629a;
    }

    /* QR code */
    .qr-code {
      margin-bottom: 30px;
    }
    .qr-code img {
      max-width: 200px;
      height: auto;
      display: block;
      margin-bottom: 8px;
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
      .header {
        flex-direction: column;
        align-items: flex-start;
      }
      .contact-row {
        flex-direction: column;
        align-items: flex-start;
      }
      .contact-row a.button {
        margin: 6px 0 0 0;
      }
      .qr-code img {
        max-width: 180px;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="header">
      <img src="logo-bca.png" alt="Logo Fortem">
      <div class="name-block">
        <div class="name">VALENTIN</div>
        <div class="surname">NEDEA</div>
        <div class="title">Manager Zonal București & Constanța</div>
      </div>
    </div>

    <div class="purple-line"></div>

    <div class="qr-code">
      <p>Scanează QR pentru vCard</p>
      <img src="qr_nedea.jpg" alt="QR code pentru vCard">
    </div>

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

    <div class="address">
      Băneasa Business & Technology Park<br>
      Șoseaua București - Ploiești 42-44<br>
      Corp A, etaj 2, București, 015011
    </div>
  </div>
</body>
</html>
