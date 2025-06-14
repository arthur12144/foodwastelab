<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Food Waste Lab</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Helvetica Neue', Arial, sans-serif;
            min-height: 100vh;
            background-image: url('https://images.unsplash.com/photo-1542838132-92c53300491e?ixlib=rb-4.0.3&auto=format&fit=crop&w=2000&q=80');
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 2rem;
        }
        
        .container {
            max-width: 700px;
            display: flex;
            flex-direction: column;
            gap: 2rem;
        }
        
        .content-box {
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
            padding: 2.5rem;
            border-radius: 15px;
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        
        .company-name {
            font-size: 3.5rem;
            font-weight: 300;
            color: #2c3e50;
            margin-bottom: 1rem;
        }
        
        .slogan {
            font-size: 1.6rem;
            font-weight: 300;
            color: #74b9ff;
            margin-bottom: 1.5rem;
            line-height: 1.4;
        }
        
        .description {
            font-size: 1.1rem;
            color: #7f8c8d;
            line-height: 1.6;
            font-weight: 400;
        }
        
        .bio {
            font-size: 1rem;
            color: #7f8c8d;
            line-height: 1.6;
            font-weight: 400;
        }
        
        @media (max-width: 768px) {
            body {
                padding: 1rem;
            }
            
            .content-box {
                padding: 2rem;
            }
            
            .company-name {
                font-size: 2.8rem;
            }
            
            .slogan {
                font-size: 1.3rem;
            }
            
            .description {
                font-size: 1rem;
            }
            
            .bio {
                font-size: 0.95rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="content-box">
            <h1 class="company-name">Food Waste Lab</h1>
            <p class="slogan">Dive Deeper into Data, Reduce More Shrink.</p>
            <p class="description">I help grocery retailers reduce food waste through deep inventory data analysis and supply chain optimization.</p>
        </div>
        <div class="content-box">
            <p class="bio">[My background: I have an extremely deep background in food supply chain and the use of technology and data to reduce waste. I was previously at Amazon for 7 years, most recently leading a team of technical product managers with the Amazon Grocery tech team where I was responsible for delivering and improving industry-leading grocery inventory control and health software.  I also led the team that built and scaled the Amazon Fresh perishable supply chain (including Whole Foods technical and non-technical integration), and led the Instock team for Produce, Meat, and Fish for Amazon Fresh for 2 years, which taught me very tangibly how to build optimal safety stock strategies while the business was growing 4x. These roles provided extensive experience in the physical, strategic, and technical aspects of Perishable inventory management. Prior to Amazon, I had a varied career including helping to scale two food startups, leading sustainability work for Ford and Boeing, setting up community agriculture classes in Tanzania, and various other work. I also have both an MBA and Masters in Environmental Science from the University of Michigan where I was a fellow at the Erb Institute. In addition to being an independent consultant, I am also an entrepreneur.  I live on Bainbridge Island (outside Seattle) with my wife, two kids, two dogs, and seven chickens."]</p>
        </div>
    </div>
</body>
</html>
