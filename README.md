<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>For Riddhima ❤️</title>
    <!-- Google Fonts for premium iOS look, beautiful script, and typewriter text -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@700&family=Great+Vibes&family=Playfair+Display:ital,wght@0,400..900;1,400..900&family=SF+Pro+Display:wght@300;400;600&family=Courier+Prime&display=swap" rel="stylesheet">
    
    <style>
        /* CSS Reset & Variables */
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            user-select: none;
            -webkit-user-select: none;
        }

        :root {
            --primary: #ff4d8d;
            --primary-glow: rgba(255, 77, 141, 0.5);
            --bg-gradient: linear-gradient(135deg, #12001a 0%, #290025 50%, #0c001f 100%);
            --glass-bg: rgba(255, 255, 255, 0.07);
            --glass-border: rgba(255, 255, 255, 0.12);
            --ios-shadow: 0 8px 32px 0 rgba(0, 0, 0, 0.37);
        }

        body {
            font-family: -apple-system, 'SF Pro Display', BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
            background: var(--bg-gradient);
            color: #ffffff;
            min-height: 100vh;
            overflow: hidden;
            position: relative;
            display: flex;
            justify-content: center;
            align-items: center;
            cursor: none; /* Custom premium cursor */
        }

        /* Ambient Dynamic Background & Gradients */
        .ambient-bg {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: 1;
            overflow: hidden;
            pointer-events: none;
        }

        .gradient-orb {
            position: absolute;
            border-radius: 50%;
            filter: blur(80px);
            opacity: 0.45;
            mix-blend-mode: screen;
            animation: orbFloat 15s infinite alternate ease-in-out;
        }

        .orb-1 {
            width: 350px;
            height: 350px;
            background: radial-gradient(circle, #ff007f 0%, rgba(255,0,127,0) 70%);
            top: -10%;
            left: -10%;
        }

        .orb-2 {
            width: 400px;
            height: 400px;
            background: radial-gradient(circle, #7a00ff 0%, rgba(122,0,255,0) 70%);
            bottom: -10%;
            right: -10%;
            animation-delay: -5s;
        }

        @keyframes orbFloat {
            0% { transform: translate(0, 0) scale(1); }
            100% { transform: translate(60px, 40px) scale(1.2); }
        }

        /* Canvas Overlay for Particles, Hearts, Petals, Glow */
        canvas {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: 2;
            pointer-events: none;
        }

        /* Premium Custom Cursor & Glow */
        #cursor-glow {
            position: fixed;
            width: 300px;
            height: 300px;
            border-radius: 50%;
            background: radial-gradient(circle, rgba(255, 77, 141, 0.15) 0%, rgba(255, 77, 141, 0) 70%);
            pointer-events: none;
            z-index: 9999;
            transform: translate(-50%, -50%);
            transition: width 0.3s, height 0.3s;
        }

        #cursor-heart {
            position: fixed;
            width: 16px;
            height: 16px;
            pointer-events: none;
            z-index: 10000;
            transform: translate(-50%, -50%);
            filter: drop-shadow(0 0 5px rgba(255, 77, 141, 0.8));
            transition: transform 0.05s ease-out;
        }

        /* Audio Control Button */
        .audio-control {
            position: fixed;
            top: 24px;
            right: 24px;
            width: 44px;
            height: 44px;
            border-radius: 50%;
            background: var(--glass-bg);
            border: 1px solid var(--glass-border);
            backdrop-filter: blur(12px);
            -webkit-backdrop-filter: blur(12px);
            display: flex;
            align-items: center;
            justify-content: center;
            cursor: pointer;
            z-index: 100;
            transition: all 0.3s cubic-bezier(0.25, 1, 0.5, 1);
            box-shadow: var(--ios-shadow);
        }

        .audio-control:hover {
            transform: scale(1.1);
            background: rgba(255, 255, 255, 0.15);
        }

        .audio-icon {
            color: #ffffff;
            font-size: 18px;
            animation: pulse 1.5s infinite alternate;
        }

        /* Containers & Page Transition setup */
        .app-container {
            position: relative;
            width: 90%;
            max-width: 440px;
            z-index: 10;
            perspective: 1000px;
        }

        .card {
            background: var(--glass-bg);
            border: 1px solid var(--glass-border);
            backdrop-filter: blur(20px);
            -webkit-backdrop-filter: blur(20px);
            border-radius: 30px;
            padding: 30px 24px;
            text-align: center;
            box-shadow: var(--ios-shadow);
            transition: all 0.8s cubic-bezier(0.34, 1.56, 0.64, 1);
            position: relative;
            overflow: hidden;
        }

        /* Screen Shake effect for Card */
        @keyframes shake {
            0%, 100% { transform: translateX(0); }
            10%, 30%, 50%, 70%, 90% { transform: translateX(-5px); }
            20%, 40%, 60%, 80% { transform: translateX(5px); }
        }

        .shake-active {
            animation: shake 0.4s ease-in-out;
        }

        /* Page 1 Specific Styles */
        #page-1 {
            opacity: 1;
            transform: scale(1) translateY(0);
        }

        .gif-container {
            width: 140px;
            height: 140px;
            margin: 0 auto 24px;
            border-radius: 24px;
            overflow: hidden;
            border: 2px solid rgba(255, 255, 255, 0.2);
            box-shadow: 0 8px 24px rgba(0,0,0,0.2);
            background: rgba(255, 255, 255, 0.05);
        }

        .gif-placeholder {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        .salutation {
            font-family: 'Dancing Script', cursive;
            font-size: 2.3rem;
            color: #ffb3d1;
            margin-bottom: 12px;
            text-shadow: 0 0 15px rgba(255, 77, 141, 0.3);
            letter-spacing: 0.5px;
        }

        .hook-text {
            font-size: 1rem;
            font-weight: 300;
            color: rgba(255, 255, 255, 0.85);
            margin-bottom: 28px;
            line-height: 1.5;
            letter-spacing: 0.5px;
        }

        .question-box {
            background: rgba(255, 77, 141, 0.1);
            border: 1px solid rgba(255, 77, 141, 0.25);
            border-radius: 20px;
            padding: 16px;
            margin-bottom: 25px;
            position: relative;
        }

        .question-box h2 {
            font-family: 'Playfair Display', serif;
            font-size: 1.5rem;
            font-weight: 600;
            color: #fff;
            text-shadow: 0 2px 10px rgba(0,0,0,0.3);
        }

        /* Buttons layout and interactions */
        .btn-container {
            display: flex;
            justify-content: space-around;
            align-items: center;
            min-height: 80px;
            position: relative;
            margin-top: 5px;
            margin-bottom: 25px;
        }

        .btn {
            font-family: -apple-system, 'SF Pro Display', sans-serif;
            font-weight: 600;
            border: none;
            border-radius: 50px;
            padding: 14px 28px;
            font-size: 1rem;
            cursor: pointer;
            transition: transform 0.1s ease, box-shadow 0.3s ease, background 0.3s ease;
            display: inline-flex;
            align-items: center;
            gap: 8px;
            letter-spacing: 0.5px;
            outline: none;
        }

        #btn-yes {
            background: linear-gradient(135deg, #ff4d8d 0%, #ff1a6c 100%);
            color: #fff;
            box-shadow: 0 4px 15px rgba(255, 77, 141, 0.4), inset 0 2px 4px rgba(255,255,255,0.2);
            z-index: 15;
            animation: yesPulse 2s infinite ease-in-out;
            position: relative;
        }

        #btn-yes::after {
            content: '';
            position: absolute;
            top: -4px; left: -4px; right: -4px; bottom: -4px;
            border-radius: 50px;
            border: 2px solid #ff4d8d;
            opacity: 0;
            animation: yesGlowRing 2s infinite ease-out;
        }

        @keyframes yesPulse {
            0%, 100% { transform: scale(1); box-shadow: 0 4px 15px rgba(255, 77, 141, 0.4); }
            50% { transform: scale(1.05); box-shadow: 0 6px 25px rgba(255, 77, 141, 0.6); }
        }

        @keyframes yesGlowRing {
            0% { transform: scale(1); opacity: 0.8; }
            100% { transform: scale(1.15); opacity: 0; }
        }

        #btn-no {
            background: rgba(255, 255, 255, 0.1);
            color: rgba(255, 255, 255, 0.85);
            border: 1px solid rgba(255, 255, 255, 0.2);
            backdrop-filter: blur(5px);
            -webkit-backdrop-filter: blur(5px);
            z-index: 10;
            position: relative;
            transform-origin: center;
        }

        /* Escape behavior transitions - smooth and physics-based */
        .escape-transition {
            transition: transform 0.35s cubic-bezier(0.25, 1, 0.5, 1), left 0.35s cubic-bezier(0.25, 1, 0.5, 1), top 0.35s cubic-bezier(0.25, 1, 0.5, 1) !important;
        }

        /* Glassmorphism Message Bubble Below Buttons */
        .message-bubble {
            background: rgba(255, 255, 255, 0.05);
            border: 1px solid rgba(255, 255, 255, 0.1);
            border-radius: 20px;
            padding: 16px;
            min-height: 70px;
            display: flex;
            align-items: center;
            justify-content: center;
            position: relative;
            box-shadow: inset 0 1px 1px rgba(255, 255, 255, 0.1);
            opacity: 0;
            transform: translateY(15px);
            transition: opacity 0.4s ease, transform 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
        }

        .message-bubble.visible {
            opacity: 1;
            transform: translateY(0);
        }

        .message-text {
            font-size: 0.95rem;
            color: #ffb3d1;
            font-weight: 500;
            line-height: 1.4;
            text-shadow: 0 1px 4px rgba(0,0,0,0.2);
        }

        /* Smoke effect for NO button disappearing */
        .smoke-particle {
            position: absolute;
            background: rgba(255, 255, 255, 0.6);
            border-radius: 50%;
            pointer-events: none;
            z-index: 99;
            animation: smokeExplode 0.6s ease-out forwards;
        }

        @keyframes smokeExplode {
            0% { transform: scale(1) translate(0, 0); opacity: 0.8; filter: blur(0px); }
            100% { transform: scale(3) translate(var(--dx), var(--dy)); opacity: 0; filter: blur(8px); }
        }

        /* Page 2 Styles (Hidden initially) */
        #page-2 {
            display: none;
            opacity: 0;
            transform: scale(0.9) translateY(30px);
            transition: all 1s cubic-bezier(0.34, 1.56, 0.64, 1);
        }

        .accent-heading {
            font-family: 'Great Vibes', cursive;
            font-size: 3.5rem;
            color: #ff4d8d;
            text-shadow: 0 0 20px rgba(255, 77, 141, 0.4);
            margin-bottom: 8px;
            letter-spacing: 1px;
        }

        .romantic-declaration {
            font-size: 1.05rem;
            line-height: 1.6;
            color: rgba(255, 255, 255, 0.9);
            margin: 15px auto 30px;
            font-weight: 300;
            max-width: 360px;
            font-style: italic;
        }

        /* Premium iOS Interactive Envelope */
        .envelope-wrapper {
            margin: 25px auto 20px;
            width: 100%;
            max-width: 340px;
            height: 200px;
            position: relative;
            perspective: 800px;
            cursor: pointer;
        }

        .envelope {
            position: relative;
            width: 100%;
            height: 100%;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 12px;
            border: 1px solid rgba(255, 255, 255, 0.2);
            box-shadow: 0 10px 30px rgba(0,0,0,0.3);
            transform-style: preserve-3d;
            transition: transform 0.5s ease-in-out;
        }

        /* Envelope flap */
        .envelope-flap {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 50%;
            background: rgba(255, 255, 255, 0.15);
            border-bottom: 1px solid rgba(255,255,255,0.2);
            border-radius: 12px 12px 0 0;
            clip-path: polygon(0 0, 100% 0, 50% 100%);
            transform-origin: top;
            transition: transform 0.6s cubic-bezier(0.25, 1, 0.5, 1);
            z-index: 3;
        }

        .envelope-pocket {
            position: absolute;
            bottom: 0;
            left: 0;
            width: 100%;
            height: 60%;
            background: rgba(255, 255, 255, 0.08);
            border-radius: 0 0 12px 12px;
            clip-path: polygon(0 100%, 100% 100%, 100% 0, 50% 60%, 0 0);
            border-top: 1px solid rgba(255,255,255,0.1);
            z-index: 2;
        }

        /* Interactive letter sliding up */
        .letter {
            position: absolute;
            left: 5%;
            width: 90%;
            height: 90%;
            bottom: 5%;
            background: rgba(255, 255, 255, 0.95);
            color: #2b1029;
            border-radius: 8px;
            padding: 20px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
            z-index: 1;
            transform: translateY(0);
            transition: transform 0.6s cubic-bezier(0.25, 1, 0.5, 1), z-index 0.6s;
            overflow-y: auto;
            text-align: left;
        }

        /* State: Open envelope */
        .envelope-wrapper.open .envelope-flap {
            transform: rotateX(180deg);
            z-index: 0;
        }

        .envelope-wrapper.open .letter {
            transform: translateY(-130px);
            z-index: 5;
            height: 300px; /* Expands to easily read */
            width: 100%;
            left: 0;
            box-shadow: 0 20px 40px rgba(0,0,0,0.4);
        }

        /* Typewriter styled letter styling */
        .letter-text {
            font-family: 'Courier Prime', 'SF Pro Display', monospace;
            font-size: 0.85rem;
            line-height: 1.6;
            color: #1a0822;
            white-space: pre-wrap; /* Keeps line breaks exactly as input */
            word-wrap: break-word;
            opacity: 0;
            transition: opacity 0.5s ease;
        }

        .envelope-wrapper.open .letter-text {
            opacity: 1;
        }

        .stamp-heart {
            position: absolute;
            top: 42%;
            left: 50%;
            transform: translate(-50%, -50%);
            font-size: 24px;
            z-index: 4;
            filter: drop-shadow(0 2px 5px rgba(0,0,0,0.2));
            transition: all 0.3s ease;
        }

        .envelope-wrapper.open .stamp-heart {
            opacity: 0;
            transform: translate(-50%, -50%) scale(0.5);
            pointer-events: none;
        }

        /* Signature block */
        .signature-block {
            margin-top: 40px;
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 8px;
        }

        .signature-text {
            font-family: 'Dancing Script', cursive;
            font-size: 1.6rem;
            color: #ff4d8d;
            letter-spacing: 0.5px;
        }

        .heartbeat-icon {
            font-size: 20px;
            color: #ff1a6c;
            animation: heartbeat 0.8s infinite cubic-bezier(0.215, 0.610, 0.355, 1);
            display: inline-block;
        }

        @keyframes heartbeat {
            0% { transform: scale(1); }
            14% { transform: scale(1.25); }
            28% { transform: scale(1.1); }
            42% { transform: scale(1.35); }
            70% { transform: scale(1); }
        }

        /* Media queries for smaller dynamic viewports */
        @media (max-height: 700px) {
            .card {
                padding: 20px 16px;
            }
            .gif-container {
                width: 110px;
                height: 110px;
                margin-bottom: 16px;
            }
            .salutation {
                font-size: 1.8rem;
            }
            .hook-text {
                margin-bottom: 18px;
            }
            .question-box {
                margin-bottom: 15px;
            }
            .envelope-wrapper {
                height: 140px;
            }
            .envelope-wrapper.open .letter {
                transform: translateY(-90px);
                height: 220px;
            }
        }
    </style>
</head>
<body>

    <!-- Ambient Floating Orbs / Lighting -->
    <div class="ambient-bg">
        <div class="gradient-orb orb-1"></div>
        <div class="gradient-orb orb-2"></div>
    </div>

    <!-- Engine Canvas: Petals, Fireflies, Heart Trails & Confetti explosions -->
    <canvas id="visualsCanvas"></canvas>

    <!-- Cursor custom assets (Glow + floating heart cursor) -->
    <div id="cursor-glow"></div>
    <svg id="cursor-heart" viewBox="0 0 32 29.6" fill="#ff4d8d">
        <path d="M23.6,0c-3.4,0-6.3,2.7-7.6,5.6C14.7,2.7,11.8,0,8.4,0C3.8,0,0,3.8,0,8.4c0,9.4,9.5,11.9,16,21.2
        c6.1-9.3,16-12.1,16-21.2C32,3.8,28.2,0,23.6,0z"/>
    </svg>

    <!-- Floating Audio Widget -->
    <div class="audio-control" onclick="togglePlayMusic()" title="Play romantic audio">
        <span class="audio-icon" id="audioBtnIcon">🎵</span>
    </div>
    <!-- Clean, empty premium audio element ready to be customized/populated by user -->
    <audio id="romanticMusic" loop>
        <source src="" type="audio/mpeg">
    </audio>

    <!-- Main Container -->
    <div class="app-container">
        
        <!-- ================= PAGE 1 ================= -->
        <div class="card" id="page-1">
            
            <div class="gif-container">
                <!-- Proposing Cute GIF - Easily customisable link -->
                <img id="page1-gif" src="https://media.tenor.com/bIfeGq7YfGoAAAAj/cute-love.gif" class="gif-placeholder" alt="Romantic GIF">
            </div>

            <h1 class="salutation">Hey Riddhima ❤️</h1>
            <p class="hook-text">I have something really important to ask you...</p>

            <div class="question-box">
                <h2>💍 Will You Be Mine Forever?</h2>
            </div>

            <div class="btn-container" id="btnContainer">
                <button class="btn" id="btn-yes" onclick="handleYesAction()">
                    ❤️ YES
                </button>
                <button class="btn" id="btn-no" onmouseenter="runAwayFromCursor()" onclick="runAwayFromCursor(true)">
                    💔 NO
                </button>
            </div>

            <!-- Beautiful Glassmorphism Message Bubble Fixed Position -->
            <div class="message-bubble" id="messageBubble">
                <span class="message-text" id="bubbleText"></span>
            </div>
        </div>

        <!-- ================= PAGE 2 ================= -->
        <div class="card" id="page-2">
            <div class="gif-container" style="width: 150px; height: 150px;">
                <!-- Confirmed / Yes GIF - Easily customisable link -->
                <img id="page2-gif" src="https://media.tenor.com/XU68Xf-W2vAAAAAj/kiss-goma.gif" class="gif-placeholder" alt="Celebrating Love GIF">
            </div>

            <h1 class="accent-heading">She Said YES ❤️</h1>
            <p class="romantic-declaration">
                "From this moment I'll stand beside you, make you laugh, support your dreams, annoy you gussa dunga for sure 101% forever, and love you with all my heart."
            </p>

            <!-- Premium Interactive Envelope -->
            <div class="envelope-wrapper" id="letterEnvelope" onclick="openAndTypeLetter()">
                <div class="envelope">
                    <div class="envelope-flap"></div>
                    <div class="stamp-heart">✉️</div>
                    <div class="letter" id="loveLetter">
                        <div class="letter-text" id="typewriterText"></div>
                    </div>
                    <div class="envelope-pocket"></div>
                </div>
            </div>

            <div class="signature-block">
                <span class="signature-text">Made with endless love by Raj</span>
                <span class="heartbeat-icon">❤️</span>
            </div>
        </div>
    </div>

    <!-- Core Interactive Engines and Canvas VFX -->
    <script>
        // Setup Canvas Config
        const canvas = document.getElementById('visualsCanvas');
        const ctx = canvas.getContext('2d');
        let particles = [];
        let systemHeight = window.innerHeight;
        let systemWidth = window.innerWidth;

        // Custom Cursor Glow Setup
        const cursorGlow = document.getElementById('cursor-glow');
        const cursorHeart = document.getElementById('cursor-heart');

        window.addEventListener('mousemove', (e) => {
            cursorGlow.style.left = e.clientX + 'px';
            cursorGlow.style.top = e.clientY + 'px';
            cursorHeart.style.left = e.clientX + 'px';
            cursorHeart.style.top = e.clientY + 'px';
            
            if(Math.random() < 0.35) {
                spawnHeartTrail(e.clientX, e.clientY);
            }
        });

        // Clean adaptive viewport resizing
        function resizeSystem() {
            systemHeight = window.innerHeight;
            systemWidth = window.innerWidth;
            canvas.width = systemWidth;
            canvas.height = systemHeight;
        }
        window.addEventListener('resize', resizeSystem);
        resizeSystem();

        // Particles setup (Fireflies, Rose Petals, Hearts)
        class Particle {
            constructor(type, x = null, y = null, isVelocityCustom = false, velX = 0, velY = 0) {
                this.type = type; // 'heart', 'petal', 'firefly', 'sparkle'
                this.x = x !== null ? x : Math.random() * systemWidth;
                this.y = y !== null ? y : (type === 'petal' || type === 'heart' ? -20 : Math.random() * systemHeight);
                this.size = Math.random() * (type === 'petal' ? 8 : 4) + 4;
                
                if (isVelocityCustom) {
                    this.vx = velX;
                    this.vy = velY;
                } else {
                    this.vx = (Math.random() - 0.5) * (type === 'firefly' ? 1.5 : 2);
                    this.vy = type === 'petal' || type === 'heart' ? Math.random() * 1.5 + 1 : (Math.random() - 0.5) * 1.5;
                }
                
                this.alpha = 1;
                this.decay = type === 'sparkle' ? 0.02 + Math.random() * 0.02 : 0;
                this.rotation = Math.random() * 360;
                this.rotSpeed = (Math.random() - 0.5) * 2;
                this.color = type === 'petal' ? '#ff85a2' : (type === 'heart' ? '#ff1a6c' : '#ffea70');
            }

            draw() {
                ctx.save();
                ctx.globalAlpha = this.alpha;
                ctx.translate(this.x, this.y);
                ctx.rotate((this.rotation * Math.PI) / 180);

                if (this.type === 'heart') {
                    ctx.fillStyle = this.color;
                    ctx.beginPath();
                    ctx.moveTo(0, -this.size / 4);
                    ctx.bezierCurveTo(this.size / 2, -this.size, this.size * 1.2, -this.size / 3, 0, this.size);
                    ctx.bezierCurveTo(-this.size * 1.2, -this.size / 3, -this.size / 2, -this.size, 0, -this.size / 4);
                    ctx.fill();
                } else if (this.type === 'petal') {
                    ctx.fillStyle = this.color;
                    ctx.beginPath();
                    ctx.ellipse(0, 0, this.size, this.size / 1.6, 0, 0, Math.PI * 2);
                    ctx.fill();
                } else if (this.type === 'firefly') {
                    ctx.shadowBlur = 10;
                    ctx.shadowColor = this.color;
                    ctx.fillStyle = this.color;
                    ctx.beginPath();
                    ctx.arc(0, 0, this.size / 2, 0, Math.PI * 2);
                    ctx.fill();
                } else if (this.type === 'sparkle') {
                    ctx.fillStyle = '#ffffff';
                    ctx.beginPath();
                    for (let i = 0; i < 4; i++) {
                        ctx.lineTo(0, -this.size);
                        ctx.lineTo(this.size / 4, -this.size / 4);
                        ctx.rotate(Math.PI / 2);
                    }
                    ctx.fill();
                }
                ctx.restore();
            }

            update() {
                this.x += this.vx;
                this.y += this.vy;
                this.rotation += this.rotSpeed;

                if (this.decay > 0) {
                    this.alpha -= this.decay;
                }

                if (this.type === 'firefly') {
                    this.vx += (Math.random() - 0.5) * 0.2;
                    this.vy += (Math.random() - 0.5) * 0.2;
                }
            }
        }

        function initParticles() {
            for (let i = 0; i < 30; i++) {
                particles.push(new Particle('firefly'));
                particles.push(new Particle('petal'));
            }
        }
        initParticles();

        function processVFXLoop() {
            ctx.clearRect(0, 0, systemWidth, systemHeight);
            
            if (particles.filter(p => p.type === 'petal').length < 25 && Math.random() < 0.05) {
                particles.push(new Particle('petal'));
            }
            if (particles.filter(p => p.type === 'firefly').length < 25 && Math.random() < 0.03) {
                particles.push(new Particle('firefly'));
            }

            for (let i = particles.length - 1; i >= 0; i--) {
                const p = particles[i];
                p.update();
                p.draw();

                if (p.alpha <= 0 || p.y > systemHeight + 20 || p.x < -20 || p.x > systemWidth + 20) {
                    particles.splice(i, 1);
                }
            }
            requestAnimationFrame(processVFXLoop);
        }
        processVFXLoop();

        function spawnHeartTrail(x, y) {
            particles.push(new Particle('heart', x, y, true, (Math.random() - 0.5) * 0.8, -Math.random() * 1.2 - 0.5));
            particles[particles.length - 1].decay = 0.03;
            particles[particles.length - 1].size = Math.random() * 5 + 3;
        }

        function createNoInteractionExplosion(x, y) {
            for (let i = 0; i < 15; i++) {
                const angle = Math.random() * Math.PI * 2;
                const speed = Math.random() * 4 + 2;
                particles.push(new Particle('heart', x, y, true, Math.cos(angle) * speed, Math.sin(angle) * speed));
                particles[particles.length - 1].decay = 0.015;
                particles.push(new Particle('sparkle', x, y, true, Math.cos(angle) * (speed * 1.2), Math.sin(angle) * (speed * 1.2)));
            }
        }

        function playGrandConfettiExplosion() {
            for (let i = 0; i < 150; i++) {
                const angle = Math.random() * Math.PI * 2;
                const speed = Math.random() * 8 + 4;
                const srcX = systemWidth / 2;
                const srcY = systemHeight / 2;
                particles.push(new Particle('heart', srcX, srcY, true, Math.cos(angle) * speed, Math.sin(angle) * speed));
                particles[particles.length - 1].decay = 0.008;
                particles.push(new Particle('sparkle', srcX, srcY, true, Math.cos(angle) * (speed * 1.3), Math.sin(angle) * (speed * 1.3)));
                particles[particles.length - 1].size *= 1.5;
            }
        }

        // ================= INTERACTION ENGINE =================

        const noMessages = [
            "Soch lo 🥺",
            "Abhi bhi time hai 😭",
            "Pakka?",
            "Ek baar aur soch lo ❤️",
            "Riddhima please 🥹",
            "Bache ka dil mat todo 💔",
            "Dil toot jayega...",
            "Itni bhi kya jaldi hai?",
            "Come on Riddhima 😔",
            "Are yaar 😭",
            "Please na ❤️",
            "Itna bhi gussa mat karo 😤",
            "We have the same mindset ❤️",
            "Meri naak tod dena, lekin YES click kar dena 😂",
            "Hadd hai, pagal! 😤❤️",
            "Just say YES... I'll teach you how to wear socks. 🧦😂",
            "Soch lo warna main sad ho jaunga 😢",
            "What will happen if you say just one YES? 😂",
            "Come on, just say YES. 😗",
            "Aren't you brave enough? 😉",
            "I know I'm annoying, but I don't care anymore. ❤️",
            "At least give me one chance, Riddhima ❤️",
            "Even this button wants you to press YES 😂",
            "How long are you going to keep running? 😅",
            "Even God is telling you to say YES 😂",
            "Destiny says YES ❤️",
            "Come on, just say YES, Riddhi ❤️",
            "Love Wins ❤️"
        ];

        let noCount = 0;
        let yesScale = 1.0;
        const btnYes = document.getElementById('btn-yes');
        const btnNo = document.getElementById('btn-no');
        const card1 = document.getElementById('page-1');
        const messageBubble = document.getElementById('messageBubble');
        const bubbleText = document.getElementById('bubbleText');

        function runAwayFromCursor(wasClicked = false) {
            noCount++;
            
            // Screen shake
            card1.classList.add('shake-active');
            setTimeout(() => card1.classList.remove('shake-active'), 400);

            // Handle the message inside the stationary bubble below buttons with smooth animation
            const currentMsgIndex = Math.min(noCount - 1, noMessages.length - 1);
            
            messageBubble.classList.remove('visible');
            setTimeout(() => {
                bubbleText.innerText = noMessages[currentMsgIndex];
                messageBubble.classList.add('visible');
            }, 150);

            // Spawn explosive visuals at NO button rect
            const rect = btnNo.getBoundingClientRect();
            createNoInteractionExplosion(rect.left + rect.width / 2, rect.top + rect.height / 2);

            // Check if final message reached
            if (noMessages[currentMsgIndex] === "Love Wins ❤️") {
                executeLoveWinsSequence();
                return;
            }

            // Yes button grows smoothly (3-5% larger)
            yesScale += 0.045;
            btnYes.style.transform = `scale(${yesScale})`;

            // Intelligent escape placement mapping
            const container = document.getElementById('btnContainer');
            const parentRect = container.getBoundingClientRect();
            
            const maxX = parentRect.width - rect.width - 20;
            const maxY = parentRect.height - rect.height - 20;

            let newX = Math.random() * maxX;
            let newY = (Math.random() - 0.5) * 80; 

            btnNo.classList.add('escape-transition');
            btnNo.style.position = 'absolute';
            btnNo.style.left = `${newX}px`;
            btnNo.style.top = `${newY}px`;
        }

        function executeLoveWinsSequence() {
            const rect = btnNo.getBoundingClientRect();
            createSmokeEffect(rect.left + rect.width/2, rect.top + rect.height/2);
            
            btnNo.style.display = 'none';

            // Yes button transitions beautifully to center stage
            btnYes.style.animation = 'none'; 
            btnYes.classList.add('escape-transition');
            btnYes.style.position = 'absolute';
            btnYes.style.left = '50%';
            btnYes.style.transform = 'translate(-50%, -10%) scale(1.4)';
            btnYes.style.boxShadow = '0 0 40px #ff4d8d';
        }

        function createSmokeEffect(x, y) {
            for (let i = 0; i < 20; i++) {
                const particle = document.createElement('div');
                particle.className = 'smoke-particle';
                const size = Math.random() * 15 + 10;
                particle.style.width = `${size}px`;
                particle.style.height = `${size}px`;
                particle.style.setProperty('--dx', `${(Math.random() - 0.5) * 80}px`);
                particle.style.setProperty('--dy', `${(Math.random() - 0.5) * 80}px`);
                particle.style.left = `${x}px`;
                particle.style.top = `${y}px`;
                document.body.appendChild(particle);
                setTimeout(() => particle.remove(), 600);
            }
        }

        // ================= YES CLICK FLOW =================

        function handleYesAction() {
            playGrandConfettiExplosion();
            
            const audio = document.getElementById('romanticMusic');
            if(audio.src) {
                audio.play().catch(e => console.log("Audio load pending source replacement."));
            }

            card1.style.opacity = '0';
            card1.style.transform = 'scale(0.8) translateY(-40px)';
            
            setTimeout(() => {
                card1.style.display = 'none';
                const card2 = document.getElementById('page-2');
                card2.style.display = 'block';
                setTimeout(() => {
                    card2.style.opacity = '1';
                    card2.style.transform = 'scale(1) translateY(0)';
                }, 100);
            }, 800);
        }

        // ================= PAGE 2 ENVELOPE TYPEWRITER =================

        let isTypingStarted = false;
        const textContent = `Just a minute, fella, right before you go out of life
All your voices said you wouldn't last a minute, bare
One more time and you'll know your life is one to share
Just a life, baby, right before we go from here
All those people said they wouldn't last a minute near
I'm with you and I could roll into another year and have to forever loulmate
Just a life fella right before you go out there next life`;

        function openAndTypeLetter() {
            const envelope = document.getElementById('letterEnvelope');
            
            if (!envelope.classList.contains('open')) {
                envelope.classList.add('open');
                
                const rainInterval = setInterval(() => {
                    if(!envelope.classList.contains('open')) {
                        clearInterval(rainInterval);
                        return;
                    }
                    particles.push(new Particle('heart', Math.random() * systemWidth, -10));
                }, 180);

                if (!isTypingStarted) {
                    isTypingStarted = true;
                    setTimeout(() => {
                        runTypewriterAnimation(document.getElementById('typewriterText'), textContent, 50);
                    }, 800); 
                }
            } else {
                envelope.classList.remove('open');
            }
        }

        function runTypewriterAnimation(element, text, delay) {
            let index = 0;
            element.innerHTML = '';
            
            function typeNext() {
                if (index < text.length) {
                    element.innerHTML += text.charAt(index);
                    index++;
                    const letterBox = document.getElementById('loveLetter');
                    letterBox.scrollTop = letterBox.scrollHeight;
                    setTimeout(typeNext, delay);
                }
            }
            typeNext();
        }

        // ================= AUDIO INTEGRATION CONTROL =================

        function togglePlayMusic() {
            const audio = document.getElementById('romanticMusic');
            const icon = document.getElementById('audioBtnIcon');
            
            if (audio.paused) {
                if(!audio.src || audio.src.endsWith('/')) {
                    alert("Click OK to activate visual music pulse! (Add your custom audio link inside index.html to play sweet music!)");
                    audio.src = "https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3"; 
                }
                audio.play()
                    .then(() => {
                        icon.innerText = "❤️";
                        icon.style.animation = 'heartbeat 0.8s infinite cubic-bezier(0.215, 0.610, 0.355, 1)';
                    })
                    .catch(err => {
                        console.log("Interactive gesture needed to trigger music engine load.");
                    });
            } else {
                audio.pause();
                icon.innerText = "🎵";
                icon.style.animation = 'pulse 1.5s infinite alternate';
            }
        }
    </script>
</body>
</html>
