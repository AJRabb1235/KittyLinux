<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kitty Linux - Official Site</title>
    <style>
        /* 🐱 Global Reset & Theme Colors */
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #1a1921;
            /* 🐈 Cat Pattern Background */
            background-image: radial-gradient(#2c2a38 1px, transparent 1px), radial-gradient(#2c2a38 1px, #1a1921 1px);
            background-size: 40px 40px;
            background-position: 0 0, 20px 20px;
            color: #f3f3f6;
            line-height: 1.6;
            padding: 20px;
        }

        /* 📦 Main Website Container */
        .container {
            max-width: 800px;
            margin: 50px auto;
            background: rgba(34, 32, 46, 0.95);
            border: 2px solid #ff79c6;
            border-radius: 16px;
            padding: 40px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.5);
            text-align: center;
        }

        /* 🎨 Big Hero Section */
        .logo-container {
            margin-bottom: 20px;
        }

        /* Giant, bold centered logo alignment */
        .hero-logo {
            width: 180px;
            height: auto;
            display: block;
            margin: 0 auto 15px auto;
            filter: drop-shadow(0 0 10px #ff79c6);
        }

        h1 {
            color: #ff79c6;
            font-size: 3rem;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.6);
        }

        .subtitle {
            color: #8be9fd;
            font-size: 1.3rem;
            font-style: italic;
            margin-bottom: 30px;
        }

        hr {
            border: 0;
            height: 1px;
            background: linear-gradient(to right, transparent, #ff79c6, transparent);
            margin: 30px 0;
        }

        /* 🚀 Features List Section */
        .section-title {
            color: #50fa7b;
            font-size: 1.8rem;
            margin-bottom: 25px;
            text-align: left;
            border-left: 4px solid #50fa7b;
            padding-left: 10px;
        }

        ul {
            list-style: none;
            text-align: left;
            margin-bottom: 35px;
        }

        li {
            background: rgba(255, 255, 255, 0.03);
            margin-bottom: 12px;
            padding: 15px;
            border-radius: 8px;
            border-left: 4px solid #ff79c6;
            font-size: 1.1rem;
        }

        li strong {
            color: #ffb86c;
        }

        /* 📥 Download Button */
        .download-box {
            margin: 40px 0;
        }

        .btn-download {
            display: inline-block;
            background: linear-gradient(135deg, #ff79c6, #bd93f9);
            color: #1a1921;
            font-weight: bold;
            font-size: 1.3rem;
            padding: 18px 45px;
            border-radius: 50px;
            text-decoration: none;
            box-shadow: 0 5px 15px rgba(255, 121, 198, 0.4);
            transition: all 0.2s ease;
        }

        .btn-download:hover {
            transform: translateY(-3px);
            box-shadow: 0 8px 25px rgba(255, 121, 198, 0.6);
            color: #fff;
        }

        /* 📊 System Specs Grid */
        .specs-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 15px;
            margin-top: 20px;
        }

        .spec-card {
            background: #282a36;
            padding: 20px;
            border-radius: 10px;
            border: 1px solid #44475a;
        }

        .spec-title {
            color: #ffb86c;
            font-weight: bold;
            font-size: 0.9rem;
            text-transform: uppercase;
            margin-bottom: 5px;
        }

        .spec-value {
            font-size: 1.2rem;
            color: #f8f8f2;
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- 🎨 Centered Giant Logo & Headline -->
        <div class="logo-container">
            <img class="hero-logo" src="Copilot_20260720_053342.png" alt="Kitty Linux Logo">
            <h1>Kitty Linux</h1>
            <p class="subtitle">The Purr-fect Lightweight Operating System 🐾</p>
        </div>

        <hr>

        <!-- 🚀 Key Features -->
        <h2 class="section-title">Key Features</h2>
        <ul>
            <li>🐱 <strong>Ultra-Lightweight Architecture:</strong> Blazing fast performance built directly onto optimized system frames, explicitly tuned like Puppy Linux.</li>
            <li>🦊 <strong>Firefox Pre-Loaded:</strong> Bundled natively right out of the box with highly targeted security and cat-themed browser presets.</li>
            <li>💻 <strong>Total Hardware Adaptability:</strong> Boots seamlessly inside minimal resource Virtual Machines or directly on physical desktop rigs.</li>
        </ul>

        <hr>

        <!-- 📥 Dynamic Download Layer -->
        <div class="download-box">
            <a href="#" class="btn-download">📥 Download Live Image (Coming Soon)</a>
        </div>

        <hr>

        <!-- 📊 Hardware Specifications Grid Layout -->
        <h2 class="section-title">System Requirements</h2>
        <div class="specs-grid">
            <div class="spec-card">
                <div class="spec-title">Memory Allocation</div>
                <div class="spec-value">1 GB RAM Min</div>
            </div>
            <div class="spec-card">
                <div class="spec-title">Storage Footprint</div>
                <div class="spec-value">10 GB Drive Space</div>
            </div>
            <div class="spec-card">
                <div class="spec-title">Processor Model</div>
                <div class="spec-value">Intel / AMD 64-bit</div>
            </div>
        </div>
    </div>

</body>
</html>
