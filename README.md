<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.5/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-SgOJa3DmI69IUzQ2PVdRZhwQ+dy64/BUtbMJw1MZ8t5HZApcHrRKUc4W0kG879m7" crossorigin="anonymous">
    <!-- Font Awesome CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.5/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-SgOJa3DmI69IUzQ2PVdRZhwQ+dy64/BUtbMJw1MZ8t5HZApcHrRKUc4W0kG879m7" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.5/dist/js/bootstrap.bundle.min.js" integrity="sha384-k6d4wzSIapyDyv1kpU366/PK5hCdSbCRGRCMv+eplOQJWyd1fbcAu9OCUj5zNLiq" crossorigin="anonymous"></script>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.5/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-SgOJa3DmI69IUzQ2PVdRZhwQ+dy64/BUtbMJw1MZ8t5HZApcHrRKUc4W0kG879m7" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.5/dist/js/bootstrap.bundle.min.js" integrity="sha384-k6d4wzSIapyDyv1kpU366/PK5hCdSbCRGRCMv+eplOQJWyd1fbcAu9OCUj5zNLiq" crossorigin="anonymous"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" rel="stylesheet">
    
    <style>
        .icon-box {
            display: flex;
            align-items: center;
            margin: 10px;
            padding: 15px;
            border-radius: 10px;
            background-color: #f8f9fa;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            font-family: 'Arial', sans-serif;
        }
        .icon-box i {
            font-size: 36px;
            margin-right: 15px;
            color: #007bff;
        }
        .icon-box span {
            font-size: 20px;
            font-weight: bold;
            color: #333;
        }
        .footer {
    background-color: #343A40;
    color: white;
    padding: 60px 0 40px;
    position: relative;
  }
  .footer-arc {
    position: absolute;
    top: -55px;
    left: 0;
    width: 100%;
    height: 60px;
    overflow: hidden;
  }
  .footer-arc svg {
    display: block;
    width: 100%;
    height: 100%;
  }
  .footer-content {
    padding-top: 60px; /* space below arc */
  }
  .footer-links {
    margin-bottom: 20px;
  }
  .footer-links h5 {
    font-weight: bold;
    margin-bottom: 15px;
  }
  .footer p {
    text-align: justify;
    font-size: 14px;
  }
  .footer a {
    color: #F8F9FA;
    text-decoration: none;
  }
  .footer a:hover {
    text-decoration: underline;
  }
  /* WhatsApp Icon Style */
  .whatsapp-icon {
    position: fixed;
    bottom: 20px;
    right: 20px;
    background-color: #25D366;
    color: white;
    border-radius: 50%;
    padding: 15px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
    font-size: 30px;
    z-index: 1000;
    cursor: pointer;
  }
  .whatsapp-icon:hover {
    background-color: #128C7E;
  }
  .whatsapp-icon i {
    color: white;
  }
       
.btn-light-green {
        background-color: rgb(0, 128, 0);
        color: rgb(255, 255, 255); /* Or any other text color you prefer */
        border: none; /* Remove default button border if you like */
    }

    .btn-light-green:hover {
        background-color: green;
        color: white; /* Or any other hover text color */
    }

</style>
</head>
<body>
    <nav class="navbar navbar-expand-lg bg-white p-3">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">Welcome</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNavDropdown">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item" style="position: relative; left: -2px;">
                        <a class="nav-link active text-black" aria-current="page" href="home.html">Home</a>
                    </li>
                    <li class="nav-item dropdown" style="position: relative; left: -2px;">
                        <a class="nav-link text-black dropdown-toggle" href="#" id="featuresDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                            Features
                        </a>
                        <ul class="dropdown-menu" aria-labelledby="featuresDropdown">
                            <li><a class="dropdown-item" href="#">WhatsApp flows</a></li>
                            <li><a class="dropdown-item" href="#">WhatsApp business API</a></li>
                            <li><a class="dropdown-item" href="#">WhatsApp chatbot</a></li>
                            <li><a class="dropdown-item" href="#">WhatsApp broadcast</a></li>
                            <li><a class="dropdown-item" href="#">WhatsApp shop</a></li>
                        </ul>
                    </li>
                    <li class="nav-item dropdown" style="position: relative; left: -2px;">
                        <a class="nav-link text-black dropdown-toggle" href="#" id="industryDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                            By Industry
                        </a>
                        <ul class="dropdown-menu" aria-labelledby="industryDropdown">
                            <li><a class="dropdown-item" href="#">E-commerce</a></li>
                            <li><a class="dropdown-item" href="#">B2B</a></li>
                            <li><a class="dropdown-item" href="#">BFSI</a></li>
                            <li><a class="dropdown-item" href="#">Education</a></li>
                            <li><a class="dropdown-item" href="#">Healthcare</a></li>
                            <li><a class="dropdown-item" href="#">Food & beverage</a></li>
                            <li><a class="dropdown-item" href="#">Advertising</a></li>
                            <li><a class="dropdown-item" href="#">Travel & Hospitality</a></li>
                        </ul>
                    </li>
                    <li class="nav-item dropdown" style="position: relative; left: -2px;">
                        <a class="nav-link text-black dropdown-toggle" href="#" id="functionsDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                            By functions
                        </a>
                        <ul class="dropdown-menu" aria-labelledby="functionsDropdown">
                            <li><a class="dropdown-item" href="#">Conversational Marketing</a></li>
                            <li><a class="dropdown-item" href="#">Conversational Commerce</a></li>
                            <li><a class="dropdown-item" href="#">Conversational Support</a></li>
                        </ul>
                    </li>
                    <li class="nav-item dropdown" style="position: relative; left: -2px;">
                        <a class="nav-link text-black dropdown-toggle" href="#" id="integrationsDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                            Integrations
                        </a>
                        <ul class="dropdown-menu" aria-labelledby="integrationsDropdown" >
                            <li><a class="dropdown-item" href="#">Zoho CRM</a></li>
                            <li><a class="dropdown-item" href="#">Shopify</a></li>
                            <li><a class="dropdown-item" href="#">WooCommerce</a></li>
                            <li><a class="dropdown-item" href="#">Zapier</a></li>
                            <li><a class="dropdown-item" href="#">HubSpot</a></li>
                            <li><a class="dropdown-item" href="#">Pabbly Connect</a></li>
                            <li><a class="dropdown-item" href="#">Make aka Integromat</a></li>
                            <li><a class="dropdown-item" href="#">WhatsApp Shop</a></li>
                            <li><a class="dropdown-item" href="#">Chat Backup</a></li>
                            <li><a class="dropdown-item" href="#">Google Sheet Sender</a></li>
                            <li><a class="dropdown-item" href="#">Klaviyo</a></li>
                            <li><a class="dropdown-item" href="#">Zoho Flow</a></li>
                        </ul>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link text-black" href="kyc.html" style="position: relative; left: -2px;">KYC for DLT</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link text-black" href="#" style="position: relative; left: -2px;">Pricing</a>
                    </li>
                    <div class="d-grid">
                        <button type="submit" id="submit" name="send" class="btn  custom-button btn-light-green">Purchase Now</button>
                    </div>
                    
                </ul>
            </div>
        </div>
    </nav>
   
   
    
 <!-- About Section -->
<section class="py-4" style="margin-top: -75px;">
    <div class="container py-md-5 py-4">
        <div class="row align-items-center">
            <!-- Left Column -->
            <div class="col-lg-6" style="margin-top: -200px;">
                <h1>Communicate Smarter Convert Better Go WhatsApp. </h1><br>
               
                <p style="text-align: justify;">Welcome to Draft4SMS, your trusted partner in WhatsApp marketing and automation – 
                    powered by Inspire Innovation Technologies. 
                    We help you stay connected with your audience through powerful tools like automated messages,
                     chatbot integrations, WhatsApp APIs, and more.
                </p><br>
                <div class="mt-3 d-flex align-items-center gap-3">
                    <button style="background-color: #228B22; color: white; border: none; padding: 10px 20px; border-radius: 5px;">
                        Get Started
                    </button>
                    <div>
                        <a href="your-video-link-here" style="text-decoration: none; color: black; font-size: 16px; display: flex; align-items: center;">
                            <i class="far fa-play-circle" style="color: green; font-size: 30px; margin-right: 10px;"></i> <!-- Icon size increased -->
                            Watch Video!
                        </a>
                    </div>
                    
                </div>
            </div>
            <!-- Right Columns -->
            <div class="col-lg-3 mt-lg-4 mt-5">
                <img src="https://shreethemes.in/leaping/layouts/images/analytics/1.png" alt="Analytics Image 1" class="img-fluid radius-image" />
                <img src="https://shreethemes.in/leaping/layouts/images/analytics/2.png" alt="Analytics Image 2" class="img-fluid radius-image" />
            </div>
            <div class="col-lg-3 mt-lg-4 mt-5">
                <img src="https://shreethemes.in/leaping/layouts/images/analytics/3.png" alt="Analytics Image 3" class="img-fluid radius-image" />
                <img src="https://shreethemes.in/leaping/layouts/images/analytics/4.png" alt="Analytics Image 4" class="img-fluid radius-image" />
            </div>
        </div>
    </div>
</section>

 <!-- Brand Icons Section -->
 <section class="py-4">
  <div class="d-flex justify-content-center flex-wrap">
      <!-- Amazon -->
      <div class="icon-box">
          <i class="fab fa-amazon"></i>
          <span>Amazon</span>
      </div>
      <!-- Google -->
      <div class="icon-box">
          <i class="fab fa-google"></i>
          <span>Google</span>
      </div>
      <!-- PayPal -->
      <div class="icon-box">
          <i class="fab fa-paypal"></i>
          <span>PayPal</span>
      </div>
      <!-- Lenovo -->
      <div class="icon-box">
          <i class="fab fa-lenovo"></i>
          <span>Lenovo</span>
      </div>
      
      <!-- Shopify -->
      <div class="icon-box">
          <i class="fab fa-shopify"></i>
          <span>Shopify</span>
      </div>
  </div>
</section>



<div class="container py-5">
    <div class="text-center mb-4">
        <h2>Our WhatsApp Services</h2>
        </div>
    <div class="row g-4">
        <!-- Row 1 -->
        <div class="col-md-4">
            <div class="feature-card bg-white text-center p-3" style="height: 100%; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1); border-radius: 10px;">
                <i class="fas fa-bullhorn" style="font-size: 50px; color: green; margin-bottom: 10px;"></i>
                <h5>WhatsApp Broadcast Campaigns</h5>
                <p class="text-muted" style="text-align: justify;">Reach thousands in seconds with personalized bulk messaging campaigns.</p>
            </div>
        </div>

        <div class="col-md-4">
            <div class="feature-card bg-white text-center p-3" style="height: 100%; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1); border-radius: 10px;">
                <i class="fas fa-comments" style="font-size: 50px; color: green; margin-bottom: 10px;"></i>
                <h5>Automated Chatbots</h5>
                <p class="text-muted" style="text-align: justify;">Build intuitive chat flows using our no-code drag-n-drop builder. Automate product inquiries, order tracking, shipping updates, and more.</p>
            </div>
        </div>
        
        <div class="col-md-4">
            <div class="feature-card bg-white text-center p-3" style="height: 100%; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1); border-radius: 10px;">
                <i class="fas fa-database" style="font-size: 50px; color: green; margin-bottom: 10px;"></i>
                <h5>Inbuilt CRM</h5>
                <p class="text-muted" style="text-align: justify;">Never miss a lead again. Notify your sales team when customers take action and schedule follow-ups effortlessly.</p>
            </div>
        </div>
        
      
       
        <!-- Row 2 -->
        <div class="col-md-4">
            <div class="feature-card bg-white text-center p-3" style="height: 100%; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1); border-radius: 10px;">
                <i class="fas fa-code" style="font-size: 50px; color: green; margin-bottom: 10px;"></i>
                <h5>WhatsApp API Integration</h5>
                <p class="text-muted" style="text-align: justify;">Send OTPs, alerts, tracking details, and notifications using our robust, secure API with rich media support.</p>
            </div>
        </div>
        <div class="col-md-4">
            <div class="feature-card bg-white text-center p-3" style="height: 100%; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1); border-radius: 10px;">
                <i class="fas fa-paint-brush" style="font-size: 50px; color: green; margin-bottom: 10px;"></i>
                <h5>Business Branding</h5>
                <p class="text-muted" style="text-align: justify;">Enhance your brand's identity with customized strategies and solutions.</p>
            </div>
        </div>
        
        <div class="col-md-4">
            <div class="feature-card bg-white text-center p-3" style="height: 100%; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1); border-radius: 10px;">
                <i class="fas fa-chart-line" style="font-size: 50px; color: green; margin-bottom: 10px;"></i>
                <h5>Data Analytics and Insights</h5>
                <p class="text-muted">Analyze customer interactions for actionable business insights.</p>
            </div>
        </div>
    </div>
</div>

     <!-- Footer -->
<footer class="footer text-center">
    <!-- Top Arc Curve -->
    <div class="footer-arc">
      <svg viewBox="0 0 1440 100" preserveAspectRatio="none">
        <path d="M0,0 C480,100 960,100 1440,0 L1440,100 L0,100 Z" fill="#343A40"></path>
      </svg>
    </div>
    <!-- Footer Content -->
    <div class="footer-content container">
      <div class="row">
        <!-- About -->
        <div class="col-sm-6 col-md-4 text-start">
          <img src="https://img.icons8.com/fluency/48/sms.png" alt="Modern SMS Icon" class="mb-3" style="width:40px; height:auto;">
          <p>India’s leading Omni-Channel Communication Platform, helping businesses connect, engage, and grow through powerful WhatsApp and SMS solutions.</p>
          <a href="#" class="btn btn-sm btn-success mt-2">Get in touch</a>
        </div>
        <!-- Features -->
        <div class="col-sm-6 col-md-2 text-start">
          <h5>Features</h5>
          <ul class="list-unstyled">
            <li><a href="#">WhatsApp Flows</a></li>
            <li><a href="#">WhatsApp Business API</a></li>
            <li><a href="#">WhatsApp Chatbot</a></li>
            <li><a href="#">WhatsApp Broadcast</a></li>
            <li><a href="#">WhatsApp Shop</a></li>
          </ul>
        </div>
        <!-- Resources -->
        <div class="col-sm-6 col-md-2 text-start">
          <h5>Resources</h5>
          <ul class="list-unstyled">
            <li><a href="#">Contact us</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Affiliate/Partner</a></li>
            <li><a href="#">Become an Affiliate</a></li>
            <li><a href="#">Become a Partner</a></li>
          </ul>
        </div>
        <!-- Social Media -->
        <div class="col-sm-6 col-md-2 text-start">
          <h5>Follow Us</h5>
          <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
          <a href="#" class="text-light fs-4">
            <i class="fab fa-linkedin"></i>
          </a>
          <a href="#" class="text-light fs-4">
            <i class="fab fa-facebook"></i>
          </a>
          <a href="#" class="text-light fs-4">
            <i class="fab fa-instagram"></i>
          </a>
        </div>
      </div>
    </div>
    <!-- WhatsApp Floating Icon -->
    <div class="whatsapp-icon">
      <a href="https://wa.me/your-phone-number" target="_blank">
        <i class="fab fa-whatsapp"></i>
      </a>
    </div>
  </footer>
  
    
  
     <!-- Bootstrap JS and Popper.js -->
     <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.6/dist/umd/popper.min.js"></script>
     <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.min.js"></script>    
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.5/dist/js/bootstrap.bundle.min.js" integrity="sha384-k6d4wzSIapyDyv1kpU366/PK5hCdSbCRGRCMv+eplOQJWyd1fbcAu9OCUj5zNLiq" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
