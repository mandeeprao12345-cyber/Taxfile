<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>EasyTax India | File Your Income Tax Return</title>

  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

  <style>

    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
    }

    body{
      font-family:'Poppins',sans-serif;
      background:#f5f9ff;
      color:#1e293b;
      line-height:1.6;
    }

    header{
      background:linear-gradient(135deg,#0052cc,#007bff);
      color:white;
      padding:20px 8%;
    }

    nav{
      display:flex;
      justify-content:space-between;
      align-items:center;
    }

    .logo{
      font-size:30px;
      font-weight:700;
    }

    .hero{
      display:flex;
      justify-content:space-between;
      align-items:center;
      padding:90px 8%;
      gap:50px;
      flex-wrap:wrap;
    }

    .hero-text{
      flex:1;
      min-width:300px;
    }

    .hero-text h1{
      font-size:55px;
      margin-bottom:20px;
      color:white;
    }

    .hero-text p{
      font-size:18px;
      margin-bottom:30px;
      color:#e2e8f0;
    }

    .hero-btn{
      display:inline-block;
      padding:15px 30px;
      background:white;
      color:#0052cc;
      text-decoration:none;
      border-radius:10px;
      font-weight:600;
      transition:0.3s;
    }

    .hero-btn:hover{
      transform:translateY(-3px);
    }

    .form-card{
      background:white;
      padding:35px;
      border-radius:20px;
      width:400px;
      box-shadow:0 10px 40px rgba(0,0,0,0.15);
    }

    .form-card h2{
      margin-bottom:25px;
      color:#0052cc;
      text-align:center;
    }

    .input-box{
      margin-bottom:20px;
    }

    .input-box label{
      display:block;
      margin-bottom:8px;
      font-weight:500;
    }

    .input-box input,
    .input-box select{
      width:100%;
      padding:14px;
      border:1px solid #cbd5e1;
      border-radius:10px;
      font-size:15px;
    }

    .submit-btn{
      width:100%;
      padding:15px;
      background:#007bff;
      color:white;
      border:none;
      border-radius:10px;
      font-size:16px;
      font-weight:600;
      cursor:pointer;
      transition:0.3s;
    }

    .submit-btn:hover{
      background:#0056d2;
    }

    section{
      padding:80px 8%;
    }

    .section-title{
      text-align:center;
      margin-bottom:50px;
    }

    .section-title h2{
      font-size:40px;
      color:#0052cc;
    }

    .features{
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
      gap:25px;
    }

    .feature-card{
      background:white;
      padding:30px;
      border-radius:18px;
      box-shadow:0 8px 25px rgba(0,0,0,0.08);
      transition:0.3s;
    }

    .feature-card:hover{
      transform:translateY(-5px);
    }

    .feature-card h3{
      color:#0052cc;
      margin-bottom:15px;
    }

    .about{
      background:#eaf3ff;
      border-radius:20px;
      padding:50px;
      text-align:center;
    }

    .about h2{
      color:#0052cc;
      margin-bottom:20px;
    }

    footer{
      background:#0052cc;
      color:white;
      text-align:center;
      padding:35px 20px;
    }

    footer p{
      margin:8px 0;
    }

    @media(max-width:900px){

      .hero{
        flex-direction:column;
      }

      .hero-text h1{
        font-size:40px;
      }

      .form-card{
        width:100%;
      }

    }

  </style>
</head>

<body>

<header>

  <nav>
    <div class="logo">EasyTax India</div>
  </nav>

  <div class="hero">

    <div class="hero-text">
      <h1>File Your Income Tax Return Easily</h1>

      <p>
        Trusted tax filing platform managed by Professional Chartered Accountants.
        Submit your details and our expert team will connect with you for smooth and accurate income tax filing.
      </p>

      <a href="#contact-form" class="hero-btn">
        Get Started
      </a>
    </div>

    <div class="form-card" id="contact-form">

      <h2>Start Your Filing</h2>

      <form>

        <div class="input-box">
          <label>Full Name</label>
          <input type="text" placeholder="Enter your name" required>
        </div>

        <div class="input-box">
          <label>Phone Number</label>
          <input type="tel" placeholder="Enter your phone number" required>
        </div>

        <div class="input-box">
          <label>Email Address</label>
          <input type="email" placeholder="Enter your email" required>
        </div>

        <div class="input-box">
          <label>Type of Filing</label>

          <select required>
            <option>Select Option</option>
            <option>Salary Income</option>
            <option>Business Income</option>
            <option>Capital Gains</option>
            <option>Crypto / Trading Income</option>
            <option>Notice Handling</option>
          </select>

        </div>

        <button class="submit-btn">
          Submit Details
        </button>

      </form>

    </div>

  </div>

</header>

<section>

  <div class="section-title">
    <h2>Why Choose EasyTax India?</h2>
  </div>

  <div class="features">

    <div class="feature-card">
      <h3>Professional CA Support</h3>
      <p>
        Your return is handled by qualified Chartered Accountants with strong taxation expertise.
      </p>
    </div>

    <div class="feature-card">
      <h3>Simple Process</h3>
      <p>
        Just submit your basic details and our team will guide you through the complete process.
      </p>
    </div>

    <div class="feature-card">
      <h3>Fast Response</h3>
      <p>
        Our team quickly connects with clients for smooth onboarding and tax filing support.
      </p>
    </div>

    <div class="feature-card">
      <h3>Secure Handling</h3>
      <p>
        Your data remains confidential and handled professionally with privacy protection.
      </p>
    </div>

  </div>

</section>

<section>

  <div class="about">

    <h2>About Us</h2>

    <p>
      EasyTax India is a modern tax filing platform built to simplify income tax return filing for individuals, professionals, salaried employees, traders, and business owners.
      The platform is operated under the guidance of professional Chartered Accountants with industry and finance expertise.
    </p>

  </div>

</section>

<footer>

  <h2>EasyTax India</h2>

  <p>Managed by Professional Chartered Accountants</p>

  <p>📍 Gurgaon, India</p>

  <p>📞 +91 7676901038</p>

  <p>✉️ mandeeprao12345@gmail.com</p>

  <p>
    © 2026 EasyTax India. All Rights Reserved.
  </p>

</footer>

</body>
</html>
