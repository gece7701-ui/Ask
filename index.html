<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Sanal VR Turlarımız ❤️</title>
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
            background-color: #0d1117;
            color: #fff;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 15px 10px;
            overflow-x: hidden;
        }

        /* GİRİŞ EKRANI */
        #login-screen {
            background: rgba(22, 27, 34, 0.95);
            border: 1px solid rgba(255, 105, 180, 0.3);
            padding: 30px 20px;
            border-radius: 20px;
            text-align: center;
            width: 100%;
            max-width: 350px;
            box-shadow: 0 0 25px rgba(255, 105, 180, 0.2);
        }

        #login-screen h2 {
            color: #ff69b4;
            margin-bottom: 15px;
            font-size: 1.5rem;
        }

        #login-screen p {
            font-size: 0.9rem;
            margin-bottom: 20px;
            color: #c9d1d9;
            line-height: 1.4;
        }

        input[type="number"] {
            width: 100%;
            padding: 14px;
            border-radius: 25px;
            border: 1px solid #ff69b4;
            background: #161b22;
            color: #fff;
            text-align: center;
            font-size: 1.4rem;
            letter-spacing: 4px;
            outline: none;
            margin-bottom: 15px;
        }

        .btn-main {
            width: 100%;
            padding: 14px;
            border-radius: 25px;
            border: none;
            background: linear-gradient(135deg, #ff416c, #ff4b2b);
            color: white;
            font-weight: bold;
            font-size: 1rem;
            cursor: pointer;
            box-shadow: 0 4px 15px rgba(255, 65, 108, 0.4);
        }

        .error-msg {
            color: #ff4d4d;
            margin-top: 15px;
            font-size: 0.85rem;
            display: none;
        }

        /* ANA İÇERİK EKRANI */
        #main-content {
            display: none;
            width: 100%;
            max-width: 600px;
        }

        header {
            text-align: center;
            margin-bottom: 20px;
        }

        header h1 {
            color: #ff69b4;
            font-size: 1.7rem;
            margin-bottom: 5px;
        }

        header p {
            color: #8b949e;
            font-size: 0.9rem;
        }

        .destinations {
            display: flex;
            flex-direction: column;
            gap: 20px;
        }

        .card {
            background: #161b22;
            border-radius: 16px;
            border: 1px solid rgba(255, 255, 255, 0.1);
            padding: 20px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.5);
        }

        .card h3 {
            color: #ff69b4;
            margin-bottom: 8px;
            font-size: 1.2rem;
        }

        .card p {
            font-size: 0.9rem;
            color: #c9d1d9;
            line-height: 1.4;
            margin-bottom: 15px;
        }

        .vr-btn {
            width: 100%;
            background: linear-gradient(135deg, #8a2be2, #4a00e0);
            color: white;
            padding: 12px;
            border-radius: 12px;
            border: none;
            font-size: 0.95rem;
            font-weight: bold;
            cursor: pointer;
            box-shadow: 0 4px 12px rgba(138, 43, 226, 0.3);
        }

        /* VR POPUP MODAL */
        #vr-modal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100vw;
            height: 100vh;
            background: #000;
            z-index: 99999;
            flex-direction: column;
        }

        #vr-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 12px 15px;
            background: #161b22;
            z-index: 10;
        }

        #vr-title {
            color: #ff69b4;
            font-size: 1rem;
            font-weight: bold;
        }

        .close-btn {
            background: #ff4d4d;
            color: white;
            border: none;
            padding: 6px 14px;
            border-radius: 8px;
            font-size: 0.85rem;
            font-weight: bold;
            cursor: pointer;
        }

        #canvas-container {
            flex: 1;
            width: 100%;
            height: 100%;
            position: relative;
            touch-action: none;
        }

        canvas {
            width: 100%;
            height: 100%;
            display: block;
        }

        .vr-hint {
            position: absolute;
            bottom: 20px;
            left: 50%;
            transform: translateX(-50%);
            background: rgba(0,0,0,0.7);
            color: #fff;
            padding: 8px 16px;
            border-radius: 20px;
            font-size: 0.8rem;
            pointer-events: none;
        }

        .heart {
            position: fixed;
            font-size: 1.5rem;
            animation: float 5s linear infinite;
            pointer-events: none;
            z-index: -1;
        }

        @keyframes float {
            0% { transform: translateY(100vh); opacity: 1; }
            100% { transform: translateY(-10vh); opacity: 0; }
        }
    </style>
</head>
<body>

    <!-- GİRİŞ EKRANI -->
    <div id="login-screen">
        <h2>❤️ Özel VR Girişi ❤️</h2>
        <p>Aşkım, seninle çıkacağımız sanal tura hoş geldin! Şifreyi gir ve 360° dünyamıza adım at.</p>
        <input type="number" id="password-input" placeholder="2808" pattern="[0-9]*" inputmode="numeric">
        <button class="btn-main" onclick="checkPassword()">VR Turunu Başlat 🥽</button>
        <div id="error-message" class="error-msg">Hatalı şifre Birtanem! ❤️</div>
    </div>

    <!-- ANA İÇERİK EKRANI -->
    <div id="main-content">
        <header>
            <h1>Hayallerimizdeki Rota ✈️</h1>
            <p>360° Sanal Gerçeklik Simülasyonu (v2.0)</p>
        </header>

        <div class="destinations">
            <div class="card">
                <h3>İsviçre - Alp Dağları 🏔️</h3>
                <p>Ahşap dağ evinde, karlarla kaplı zirvelere karşı sıcak çikolatamızı yudumlayacağımız o büyülü atmosfer...</p>
                <button class="vr-btn" onclick="openVR('İsviçre Alpleri', 'alps')">🥽 360° VR Simülasyonuna Gir</button>
            </div>

            <div class="card">
                <h3>Maldivler - Sahil 🏖️</h3>
                <p>Turkuaz deniz, palmiyeler ve sahil boyunca el ele yürüyeceğimiz huzur dolu sahil simülasyonu...</p>
                <button class="vr-btn" onclick="openVR('Maldivler Sahili', 'beach')">🥽 360° VR Simülasyonuna Gir</button>
            </div>

            <div class="card">
                <h3>Romanya - Tarihi Şato 🏰</h3>
                <p>Masalsı kuleler ve gizemli dağ manzaraları eşliğinde tarihi bir gezi...</p>
                <button class="vr-btn" onclick="openVR('Romanya Şatosu', 'castle')">🥽 360° VR Simülasyonuna Gir</button>
            </div>

            <div class="card">
                <h3>Avustralya - Sidney 𝓚</h3>
                <p>Okyanus esintisi ve gün batımının kızıllığı eşliğinde harika bir akşam simülasyonu...</p>
                <button class="vr-btn" onclick="openVR('Sidney Manzarası', 'sydney')">🥽 360° VR Simülasyonuna Gir</button>
            </div>
        </div>
    </div>

    <!-- VR POPUP MODAL -->
    <div id="vr-modal">
        <div id="vr-header">
            <span id="vr-title">360° VR Görünümü</span>
            <button class="close-btn" onclick="closeVR()">Çıkış ✖</button>
        </div>
        <div id="canvas-container">
            <canvas id="vrCanvas"></canvas>
            <div class="vr-hint">👆 Parmağınla 360° Etrafta Gezin</div>
        </div>
    </div>

    <script>
        function checkPassword() {
            const input = document.getElementById('password-input').value;
            if (input === '2808') {
                document.getElementById('login-screen').style.display = 'none';
                document.getElementById('main-content').style.display = 'block';
                
                setInterval(() => {
                    const heart = document.createElement('div');
                    heart.classList.add('heart');
                    heart.innerHTML = '❤️';
                    heart.style.left = Math.random() * 100 + 'vw';
                    document.body.appendChild(heart);
                    setTimeout(() => heart.remove(), 5000);
                }, 300);
            } else {
                document.getElementById('error-message').style.display = 'block';
            }
        }

        // CANVAS 360 ENGINE
        const canvas = document.getElementById('vrCanvas');
        const ctx = canvas.getContext('2d');
        let isDragging = false;
        let startX = 0, startY = 0;
        let rotationX = 0, rotationY = 0;
        let currentTheme = 'alps';
        let animId = null;

        function resizeCanvas() {
            canvas.width = window.innerWidth;
            canvas.height = window.innerHeight - 50;
        }

        window.addEventListener('resize', resizeCanvas);

        function drawScene() {
            ctx.clearRect(0, 0, canvas.width, canvas.height);
            const w = canvas.width;
            const h = canvas.height;

            let grad = ctx.createLinearGradient(0, 0, 0, h);
            if (currentTheme === 'alps') {
                grad.addColorStop(0, '#1a365d');
                grad.addColorStop(0.5, '#63b3ed');
                grad.addColorStop(1, '#ebf8ff');
            } else if (currentTheme === 'beach') {
                grad.addColorStop(0, '#0284c7');
                grad.addColorStop(0.6, '#38bdf8');
                grad.addColorStop(1, '#bae6fd');
            } else if (currentTheme === 'castle') {
                grad.addColorStop(0, '#2e1065');
                grad.addColorStop(0.6, '#7c3aed');
                grad.addColorStop(1, '#ddd6fe');
            } else {
                grad.addColorStop(0, '#831843');
                grad.addColorStop(0.6, '#f43f5e');
                grad.addColorStop(1, '#fde047');
            }
            ctx.fillStyle = grad;
            ctx.fillRect(0, 0, w, h);

            const offsetX = (rotationX % w + w) % w;
            const offsetY = Math.max(-100, Math.min(100, rotationY));

            ctx.save();
            ctx.translate(-offsetX, offsetY);

            for (let i = -1; i <= 2; i++) {
                const shift = i * w;

                if (currentTheme === 'alps') {
                    ctx.fillStyle = '#2d3748';
                    ctx.beginPath();
                    ctx.moveTo(shift + 0, h - 100);
                    ctx.lineTo(shift + w * 0.3, h - 350);
                    ctx.lineTo(shift + w * 0.6, h - 100);
                    ctx.fill();

                    ctx.fillStyle = '#fff';
                    ctx.beginPath();
                    ctx.moveTo(shift + w * 0.25, h - 280);
                    ctx.lineTo(shift + w * 0.3, h - 350);
                    ctx.lineTo(shift + w * 0.35, h - 280);
                    ctx.fill();

                    ctx.fillStyle = '#744210';
                    ctx.fillRect(shift + w * 0.4, h - 180, 120, 80);
                    ctx.fillStyle = '#9b2c2c';
                    ctx.beginPath();
                    ctx.moveTo(shift + w * 0.4 - 10, h - 180);
                    ctx.lineTo(shift + w * 0.4 + 60, h - 230);
                    ctx.lineTo(shift + w * 0.4 + 130, h - 180);
                    ctx.fill();
                } else if (currentTheme === 'beach') {
                    ctx.fillStyle = '#fef08a';
                    ctx.fillRect(shift + 0, h - 150, w, 150);
                    ctx.fillStyle = '#0284c7';
                    ctx.fillRect(shift + 0, h - 220, w, 70);
                } else if (currentTheme === 'castle') {
                    ctx.fillStyle = '#475569';
                    ctx.fillRect(shift + w * 0.3, h - 300, 80, 200);
                    ctx.fillRect(shift + w * 0.5, h - 380, 100, 280);
                } else {
                    ctx.fillStyle = '#1e293b';
                    ctx.fillRect(shift + w * 0.2, h - 250, 90, 150);
                    ctx.fillRect(shift + w * 0.4, h - 320, 110, 220);
                }
            }

            ctx.restore();

            if (!isDragging) {
                rotationX += 0.5;
            }

            animId = requestAnimationFrame(drawScene);
        }

        const container = document.getElementById('canvas-container');

        container.addEventListener('mousedown', (e) => {
            isDragging = true;
            startX = e.clientX;
            startY = e.clientY;
        });

        window.addEventListener('mousemove', (e) => {
            if (!isDragging) return;
            const dx = e.clientX - startX;
            const dy = e.clientY - startY;
            rotationX -= dx * 0.8;
            rotationY += dy * 0.5;
            startX = e.clientX;
            startY = e.clientY;
        });

        window.addEventListener('mouseup', () => isDragging = false);

        container.addEventListener('touchstart', (e) => {
            isDragging = true;
            startX = e.touches[0].clientX;
            startY = e.touches[0].clientY;
        });

        container.addEventListener('touchmove', (e) => {
            if (!isDragging) return;
            const dx = e.touches[0].clientX - startX;
            const dy = e.touches[0].clientY - startY;
            rotationX -= dx * 0.8;
            rotationY += dy * 0.5;
            startX = e.touches[0].clientX;
            startY = e.touches[0].clientY;
        });

        container.addEventListener('touchend', () => isDragging = false);

        function openVR(title, theme) {
            document.getElementById('vr-title').innerText = title;
            document.getElementById('vr-modal').style.display = 'flex';
            currentTheme = theme;
            resizeCanvas();
            if (animId) cancelAnimationFrame(animId);
            drawScene();
        }

        function closeVR() {
            document.getElementById('vr-modal').style.display = 'none';
            if (animId) cancelAnimationFrame(animId);
        }
    </script>
</body>
</html>
