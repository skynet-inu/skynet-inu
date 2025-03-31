<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Skynet Inu - Memecoin AI Masa Depan</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Orbitron&display=swap');
        body {
            font-family: 'Orbitron', sans-serif;
            text-align: center;
            background-color: #000016;
            background-image: url('https://www.solarsystemscope.com/textures/download/2k_stars.jpg');
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
            color: white;
            margin: 0;
            padding: 0;
            overflow-x: hidden;
        }
        .container {
            position: relative;
            z-index: 1;
            padding: 50px;
        }
        .logo {
            max-width: 150px;
            animation: float 3s ease-in-out infinite, glow 2s alternate infinite;
            background: transparent;
        }
        @keyframes float {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-10px); }
            100% { transform: translateY(0px); }
        }
        @keyframes glow {
            from { filter: drop-shadow(0 0 5px #00aaff); }
            to { filter: drop-shadow(0 0 20px #0044ff); }
        }
        .btn {
            background: linear-gradient(90deg, #00aaff, #0044ff);
            color: white;
            padding: 15px 30px;
            text-decoration: none;
            border-radius: 5px;
            display: inline-block;
            margin-top: 20px;
            transition: transform 0.3s, box-shadow 0.3s;
        }
        .btn:hover {
            transform: scale(1.1);
            box-shadow: 0 0 15px rgba(0, 170, 255, 0.8);
        }
        h1, h2, p, a {
            animation: slideUp 1.5s ease-in-out;
            text-decoration: none;
        }
        .neon-text {
            color: #00aaff;
            text-shadow: 0 0 5px #00aaff, 0 0 10px #0088ff, 0 0 15px #0044ff;
        }
        .section {
            padding: 60px 20px;
            border-bottom: 1px solid rgba(255, 255, 255, 0.2);
            opacity: 0;
            transform: translateY(30px);
            transition: opacity 1s ease-out, transform 1s ease-out;
        }
        .section.visible {
            opacity: 1;
            transform: translateY(0);
        }
    </style>
</head>
<body>
    <div class="container">
        <img src="skynet_inu_logo.png" alt="Skynet Inu Logo" class="logo">
        <h1 class="neon-text">Selamat Datang di Skynet Inu</h1>
        <p>Memecoin berbasis AI yang akan menguasai blockchain!</p>
        <a href="#buy" class="btn">Beli $SKYINU</a>
    </div>
    
    <div class="section" id="tokenomics">
        <h2 class="neon-text">Tokenomics</h2>
        <p>Total Supply: 1,000,000,000 $SKYINU</p>
    </div>
    
    <div class="section" id="roadmap">
        <h2 class="neon-text">Roadmap</h2>
        <p>Peluncuran, komunitas, listing DEX, ekspansi global.</p>
    </div>
    
    <div class="section" id="how-to-buy">
        <h2 class="neon-text">Cara Membeli</h2>
        <p>1. Buat dompet Solana seperti Phantom atau Solflare.</p>
        <p>2. Beli SOL di bursa kripto.</p>
        <p>3. Hubungkan dompet ke DEX seperti Raydium.</p>
        <p>4. Tukarkan SOL dengan $SKYINU.</p>
    </div>
    
    <div class="section" id="community">
        <h2 class="neon-text">Gabung Komunitas</h2>
        <a href="https://twitter.com" target="_blank">Twitter</a> | 
        <a href="https://t.me" target="_blank">Telegram</a> | 
        <a href="https://discord.com" target="_blank">Discord</a>
    </div>
    
    <script>
        function revealSections() {
            let sections = document.querySelectorAll('.section');
            sections.forEach(section => {
                let position = section.getBoundingClientRect().top;
                let screenPosition = window.innerHeight / 1.3;
                if (position < screenPosition) {
                    section.classList.add('visible');
                }
            });
        }
        window.addEventListener('scroll', revealSections);
        revealSections();
    </script>
</body>
</html>
