<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Business Name - Home</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
            line-height: 1.6;
            color: #333;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
        }

        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 2rem;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
        }

        .main-card {
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
            border-radius: 20px;
            padding: 3rem;
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.1);
            text-align: center;
            width: 100%;
            border: 1px solid rgba(255, 255, 255, 0.2);
        }

        .logo {
            width: 100px;
            height: 100px;
            background: linear-gradient(45deg, #667eea, #764ba2);
            border-radius: 50%;
            margin: 0 auto 2rem;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 2.5rem;
            font-weight: bold;
            color: white;
        }

        h1 {
            font-size: 3rem;
            margin-bottom: 1rem;
            background: linear-gradient(45deg, #667eea, #764ba2);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }

        .tagline {
            font-size: 1.3rem;
            color: #666;
            margin-bottom: 3rem;
            font-weight: 300;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
        }

        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            margin: 3rem 0;
        }

        .service-card {
            background: rgba(255, 255, 255, 0.8);
            padding: 2rem;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
            transition: all 0.3s ease;
            border: 1px solid rgba(255, 255, 255, 0.3);
        }

        .service-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.15);
        }

        .service-icon {
            width: 60px;
            height: 60px;
            background: linear-gradient(45deg, #667eea, #764ba2);
            border-radius: 50%;
            margin: 0 auto 1rem;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.5rem;
            color: white;
        }

        .service-title {
            font-size: 1.3rem;
            font-weight: 600;
            margin-bottom: 1rem;
            color: #333;
        }

        .service-description {
            color: #666;
            margin-bottom: 1.5rem;
        }

        .action-button {
            display: inline-block;
            background: linear-gradient(45deg, #667eea, #764ba2);
            color: white;
            padding: 0.8rem 1.5rem;
            border: none;
            border-radius: 25px;
            font-size: 1rem;
            font-weight: 600;
            text-decoration: none;
            cursor: pointer;
            transition: all 0.3s ease;
            box-shadow: 0 4px 15px rgba(103, 126, 234, 0.3);
        }

        .action-button:hover {
            transform: translateY(-2px);
            box-shadow: 0 8px 25px rgba(103, 126, 234, 0.4);
        }

        .action-button.secondary {
            background: transparent;
            color: #667eea;
            border: 2px solid #667eea;
            box-shadow: none;
        }

        .action-button.secondary:hover {
            background: #667eea;
            color: white;
        }

        .contact-section {
            margin-top: 3rem;
            padding-top: 2rem;
            border-top: 1px solid rgba(0, 0, 0, 0.1);
        }

        .contact-info {
            display: flex;
            justify-content: center;
            gap: 2rem;
            flex-wrap: wrap;
            margin-bottom: 2rem;
        }

        .contact-item {
            color: #555;
            font-size: 1rem;
        }

        .footer {
            margin-top: 2rem;
            color: rgba(255, 255, 255, 0.8);
            font-size: 0.9rem;
        }

        @media (max-width: 768px) {
            .container {
                padding: 1rem;
            }
            
            .main-card {
                padding: 2rem;
            }
            
            h1 {
                font-size: 2.5rem;
            }
            
            .tagline {
                font-size: 1.1rem;
            }

            .services-grid {
                grid-template-columns: 1fr;
            }

            .contact-info {
                flex-direction: column;
                gap: 1rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="main-card">
            <!-- Replace with your logo or company initial -->
            <div class="logo">YB</div>
            
            <h1>Your Business Name</h1>
            <p class="tagline">Welcome to our professional services. We're here to help you succeed with quality solutions and exceptional service.</p>
            
            <div class="services-grid">
                <div class="service-card">
                    <div class="service-icon">📋</div>
                    <h3 class="service-title">Services</h3>
                    <p class="service-description">Learn about our comprehensive range of professional services designed to meet your needs.</p>
                    <a href="#" class="action-button secondary">Learn More</a>
                </div>
                
                <div class="service-card">
                    <div class="service-icon">💳</div>
                    <h3 class="service-title">Make Payment</h3>
                    <p class="service-description">Secure and convenient payment processing. Pay invoices or make purchases safely online.</p>
                    <a href="#" class="action-button">Pay Now</a>
                </div>
                
                <div class="service-card">
                    <div class="service-icon">📞</div>
                    <h3 class="service-title">Contact Us</h3>
                    <p class="service-description">Get in touch with our team for inquiries, support, or to discuss your specific requirements.</p>
                    <a href="#" class="action-button secondary">Contact</a>
                </div>
            </div>
            
            <div class="contact-section">
                <div class="contact-info">
                    <div class="contact-item">📧 contact@yourbusiness.com</div>
                    <div class="contact-item">📱 (555) 123-4567</div>
                    <div class="contact-item">📍 Your City, State</div>
                </div>
                
                <p style="color: #666; font-size: 0.95rem;">
                    Professional, reliable, and secure. Your satisfaction is our priority.
                </p>
            </div>
        </div>
        
        <div class="footer">
            <p>&copy; 2025 Your Business Name. All rights reserved.</p>
        </div>
    </div>
</body>
</html>
