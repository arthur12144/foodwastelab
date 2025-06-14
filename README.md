<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Food Waste Lab - Data-Driven Solutions for Grocery Retail</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Helvetica Neue', Arial, sans-serif;
            line-height: 1.6;
            color: #333;
            background: #ffffff;
        }
        
        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        header {
            background: #27ae60;
            color: white;
            padding: 1.5rem 0;
            text-align: center;
        }
        
        .logo {
            font-size: 2.5rem;
            font-weight: 300;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 0.5rem;
        }
        
        .logo-icon {
            width: 50px;
            height: 50px;
            background: rgba(255, 255, 255, 0.2);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.5rem;
        }
        
        .hero {
            background: linear-gradient(135deg, #74b9ff 0%, #0984e3 100%);
            color: white;
            padding: 5rem 0;
            text-align: center;
            position: relative;
            overflow: hidden;
        }
        
        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: url('data:image/svg+xml,<svg width="60" height="60" viewBox="0 0 60 60" xmlns="http://www.w3.org/2000/svg"><g fill="none" fill-rule="evenodd"><g fill="%23fff" fill-opacity="0.1"><circle cx="30" cy="30" r="4"/></g></svg>') repeat;
        }
        
        .hero-content {
            position: relative;
            z-index: 1;
        }
        
        .tagline {
            font-size: 3rem;
            font-weight: 300;
            margin-bottom: 1.5rem;
            line-height: 1.2;
        }
        
        .hero-highlight {
            color: #ffeaa7;
            font-weight: 400;
        }
        
        .hero-description {
            font-size: 1.3rem;
            margin-bottom: 2rem;
            opacity: 0.9;
            max-width: 700px;
            margin-left: auto;
            margin-right: auto;
            line-height: 1.6;
        }
        
        .services {
            padding: 5rem 0;
            background: #f8f9fa;
        }
        
        .section-title {
            text-align: center;
            font-size: 2.5rem;
            font-weight: 300;
            color: #2c3e50;
            margin-bottom: 2rem;
        }
        
        .services-description {
            text-align: center;
            font-size: 1.1rem;
            color: #7f8c8d;
            max-width: 800px;
            margin: 0 auto;
            line-height: 1.8;
        }
        
        .bio {
            padding: 5rem 0;
            background: white;
        }
        
        .bio-content {
            display: grid;
            grid-template-columns: 200px 1fr;
            gap: 3rem;
            align-items: start;
        }
        
        .bio-photo {
            width: 200px;
            height: 200px;
            background: linear-gradient(135deg, #74b9ff, #0984e3);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 4rem;
            color: white;
            margin: 0 auto;
        }
        
        .bio-text h3 {
            font-size: 2rem;
            color: #2c3e50;
            margin-bottom: 1rem;
            font-weight: 400;
        }
        
        .bio-text p {
            color: #7f8c8d;
            line-height: 1.8;
            margin-bottom: 1.5rem;
        }
        
        .contact {
            background: #2c3e50;
            color: white;
            padding: 5rem 0;
        }
        
        .contact-form {
            max-width: 600px;
            margin: 2rem auto 0;
        }
        
        .form-group {
            margin-bottom: 1.5rem;
        }
        
        .form-group label {
            display: block;
            margin-bottom: 0.5rem;
            font-weight: 300;
        }
        
        .form-group input,
        .form-group textarea {
            width: 100%;
            padding: 1rem;
            border: none;
            border-radius: 5px;
            font-size: 1rem;
            background: rgba(255, 255, 255, 0.1);
            color: white;
            border: 2px solid transparent;
            transition: all 0.3s;
        }
        
        .form-group input::placeholder,
        .form-group textarea::placeholder {
            color: rgba(255, 255, 255, 0.6);
        }
        
        .form-group input:focus,
        .form-group textarea:focus {
            outline: none;
            border-color: #27ae60;
            background: rgba(255, 255, 255, 0.15);
        }
        
        .form-group textarea {
            height: 120px;
            resize: vertical;
        }
        
        .submit-btn {
            background: #27ae60;
            color: white;
            padding: 1rem 3rem;
            border: none;
            border-radius: 50px;
            font-size: 1.1rem;
            cursor: pointer;
            transition: all 0.3s;
            display: block;
            margin: 2rem auto 0;
        }
        
        .submit-btn:hover {
            background: #229954;
            transform: translateY(-2px);
        }
        
        @media (max-width: 768px) {
            .tagline {
                font-size: 2.2rem;
            }
            
            .hero-description {
                font-size: 1.1rem;
            }
            
            .bio-content {
                grid-template-columns: 1fr;
                text-align: center;
                gap: 2rem;
            }
            
            .bio-photo {
                width: 150px;
                height: 150px;
                font-size: 3rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div class="logo">
                <div class="logo-icon">🥬</div>
                Food Waste Lab
            </div>
        </div>
    </header>
    
    <main>
        <section class="hero">
            <div class="container">
                <div class="hero-content">
                    <h1 class="tagline">Every <span class="hero-highlight">Data Point</span> Tells a Story</h1>
                    <p class="hero-description">We decode your inventory patterns to reveal millions in hidden savings. Smart analytics for smarter grocery operations.</p>
                </div>
            </div>
        </section>
        
        <section class="services">
            <div class="container">
                <h2 class="section-title">Our Services</h2>
                <p class="services-description">
                    Food Waste Lab specializes in helping grocery retailers dramatically reduce food waste through deep inventory data analysis and supply chain optimization. We examine your sales patterns, seasonality trends, ordering cycles, and shrink data to identify specific opportunities for waste reduction and margin improvement. Our comprehensive assessments include supply chain setup reviews, demand forecasting optimization, and actionable implementation roadmaps that typically deliver 15-30% waste reduction within 90 days.
                </p>
            </div>
        </section>
        
        <section class="bio">
            <div class="container">
                <h2 class="section-title">About the Founder</h2>
                <div class="bio-content">
                    <div class="bio-photo">👤</div>
                    <div class="bio-text">
                        <h3>[Your Name]</h3>
                        <p>
                            [Add your professional background here - for example: "With over 15 years of experience in retail analytics and supply chain optimization, I've helped dozens of grocery retailers transform their operations through data-driven insights."]
                        </p>
                        <p>
                            [Add more about your expertise - for example: "My background combines deep technical expertise in data analysis with practical understanding of grocery retail operations, having worked with everything from independent stores to major regional chains."]
                        </p>
                        <p>
                            [Add your mission/approach - for example: "I believe that every piece of wasted food represents a missed opportunity - not just for profit, but for more sustainable and efficient retail operations."]
                        </p>
                    </div>
                </div>
            </div>
        </section>
        
        <section class="contact">
            <div class="container">
                <h2 class="section-title">Let's Talk About Your Data</h2>
                <p style="text-align: center; opacity: 0.9; margin-bottom: 1rem;">Ready to discover what your inventory data is really telling you?</p>
                
                <form class="contact-form">
                    <div class="form-group">
                        <label for="name">Name</label>
                        <input type="text" id="name" name="name" placeholder="Your full name" required>
                    </div>
                    
                    <div class="form-group">
                        <label for="company">Company</label>
                        <input type="text" id="company" name="company" placeholder="Company name" required>
                    </div>
                    
                    <div class="form-group">
                        <label for="email">Email</label>
                        <input type="email" id="email" name="email" placeholder="your.email@company.com" required>
                    </div>
                    
                    <div class="form-group">
                        <label for="phone">Phone</label>
                        <input type="tel" id="phone" name="phone" placeholder="(555) 123-4567">
                    </div>
                    
                    <div class="form-group">
                        <label for="message">Tell us about your current challenges</label>
                        <textarea id="message" name="message" placeholder="What specific food waste or inventory challenges are you facing? How many locations do you operate?" required></textarea>
                    </div>
                    
                    <button type="submit" class="submit-btn">Start the Conversation</button>
                </form>
            </div>
        </section>
    </main>
</body>
</html>
