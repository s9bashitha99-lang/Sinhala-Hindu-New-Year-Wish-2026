<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
<title>Avurudu Celebration 🇱🇰 | Sinhala & Hindu New Year</title>

<style>
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        user-select: none;
    }

    body {
        margin: 0;
        overflow: hidden;
        background: radial-gradient(circle at center, #0a0f2a 0%, #020010 100%);
        font-family: 'Segoe UI', 'Poppins', 'Noto Sans Sinhala', system-ui, -apple-system, sans-serif;
        text-align: center;
        color: white;
    }

    /* decorative traditional border effect */
    .container {
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        width: 85%;
        max-width: 800px;
        z-index: 20;
        background: rgba(0, 0, 0, 0.55);
        backdrop-filter: blur(10px);
        border-radius: 48px;
        padding: 2rem 1.5rem;
        border: 1px solid rgba(255, 215, 0, 0.4);
        box-shadow: 0 20px 40px rgba(0,0,0,0.4), 0 0 0 4px rgba(255,200,0,0.2) inset, 0 0 0 8px rgba(255,100,0,0.1) inset;
        animation: fadeSlideUp 1s ease-out;
    }

    h1 {
        font-size: clamp(28px, 7vw, 52px);
        color: #ffd966;
        margin-bottom: 0.75rem;
        letter-spacing: 2px;
        font-weight: 700;
        text-shadow: 0 0 12px #ff9900, 0 0 25px #ff5500;
        animation: gentleGlow 2.2s infinite alternate;
    }

    .subtitle {
        font-size: 1.3rem;
        font-weight: 500;
        background: linear-gradient(135deg, #FFE6B0, #FFB347);
        background-clip: text;
        -webkit-background-clip: text;
        color: transparent;
        margin-bottom: 0.9rem;
    }

    .greeting p {
        font-size: clamp(16px, 4vw, 20px);
        line-height: 1.55;
        margin: 0.8rem 0;
        font-weight: 400;
        text-shadow: 0 1px 2px black;
    }

    .wish {
        font-size: 1.2rem;
        margin-top: 1rem;
        font-style: italic;
        color: #FFE5B4;
        border-top: 1px dashed rgba(255,215,0,0.5);
        padding-top: 1rem;
        display: inline-block;
    }

    @keyframes gentleGlow {
        0% { text-shadow: 0 0 5px #ffcc33, 0 0 15px #ff8800; }
        100% { text-shadow: 0 0 20px #ffdd66, 0 0 40px #ff3300; }
    }

    @keyframes fadeSlideUp {
        0% { opacity: 0; transform: translate(-50%, 30%); }
        100% { opacity: 1; transform: translate(-50%, -50%); }
    }

    .celebration-btn {
        position: absolute;
        bottom: 10%;
        left: 50%;
        transform: translateX(-50%);
        padding: 14px 32px;
        font-size: 1.3rem;
        font-weight: bold;
        background: linear-gradient(145deg, #FFD966, #FFB347);
        border: none;
        border-radius: 60px;
        cursor: pointer;
        z-index: 30;
        color: #2c1a0a;
        box-shadow: 0 8px 20px rgba(0,0,0,0.3), 0 0 12px rgba(255,200,0,0.8);
        transition: 0.2s;
        letter-spacing: 2px;
        font-family: inherit;
        backdrop-filter: blur(4px);
    }

    .celebration-btn:hover {
        transform: translateX(-50%) scale(1.03);
        background: linear-gradient(145deg, #FFE085, #FFA559);
        box-shadow: 0 12px 28px rgba(0,0,0,0.4);
    }

    .celebration-btn:active {
        transform: translateX(-50%) scale(0.98);
    }

    /* traditional lamp decorations */
    .oil-lamp {
        position: absolute;
        bottom: 20px;
        left: 20px;
        font-size: 2rem;
        opacity: 0.7;
        z-index: 15;
        filter: drop-shadow(0 0 6px gold);
        pointer-events: none;
    }

    .oil-lamp-right {
        right: 20px;
        left: auto;
    }

    /* responsiveness */
    @media (max-width: 600px) {
        .container { padding: 1.2rem; width: 90%; }
        .celebration-btn { padding: 10px 22px; font-size: 1.1rem; bottom: 8%; }
        .greeting p { font-size: 0.9rem; }
        .wish { font-size: 0.9rem; }
    }

    canvas {
        display: block;
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        z-index: 1;
        pointer-events: none;
    }

    /* falling flower petals / traditional vibe */
    .petals-overlay {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        pointer-events: none;
        z-index: 12;
        overflow: hidden;
    }
</style>
</head>
<body>

<!-- decorative floating petals container (pure css/js visual enhancement) -->
<div class="petals-overlay" id="petalsContainer"></div>

<div class="container">
    <h1>🌾 සුභ අලුත් අවුරුද්දක් වේවා! 🌼</h1>
    <div class="subtitle">✨ Happy Sinhala & Hindu New Year ✨</div>
    <div class="greeting">
        <p>🌸 New year, new beginnings! 🌸<br>
        May you achieve all your goals and become the best version of yourself.<br>
        🎋 Prosperity, joy & togetherness fill your home 🎋</p>
        <div class="wish">🎇 ලැබුවා වූ නව වසර සුභම සුභ නව වසරන් වේවා! 🎇</div>
    </div>
</div>

<button class="celebration-btn" id="mainCelebrateBtn">🎉 Start Celebration 🎆</button>

<!-- Traditional oil lamp emojis -->
<div class="oil-lamp">🪔✨</div>
<div class="oil-lamp oil-lamp-right">✨🪔</div>

<canvas id="fireworksCanvas"></canvas>

<!-- Audio elements (will be created dynamically to avoid autoplay issues, but pre-defined with sources) -->
<audio id="rabanAudio" preload="auto" loop></audio>
<audio id="kohaAudio" preload="auto" loop></audio>
<!-- we'll generate audio dynamically but keep reference-->

<script>
    (function() {
        // ========================
        //  FIREWORKS & CELEBRATION SYSTEM
        // ========================
        const canvas = document.getElementById('fireworksCanvas');
        const ctx = canvas.getContext('2d');
        let width = window.innerWidth;
        let height = window.innerHeight;
        
        function resizeCanvas() {
            width = window.innerWidth;
            height = window.innerHeight;
            canvas.width = width;
            canvas.height = height;
        }
        window.addEventListener('resize', resizeCanvas);
        resizeCanvas();
        
        // particles store
        let particles = [];
        let rockets = [];
        
        // audio control state
        let celebrationActive = false;
        let rabanAudio = null;
        let kohaAudio = null;
        let audioStarted = false;
        
        // firecracker sound pool for multiple bursts
        let firecrackerPool = [];
        
        function initAudio() {
            // create audio elements dynamically (to ensure proper cloning and avoid autoplay restrictions)
            if (!rabanAudio) {
                rabanAudio = new Audio();
                rabanAudio.src = "https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3"; // fallback royalty-free but we provide actual local-like? but for demo it's a placeholder, yet we need functional audio? 
                // Due to external constraints, we will use a pure synthesized audio or user interaction? 
                // To ensure reliable joyful experience: we will use Web Audio API for short beeps? But that ruins tradition.
                // However better to use browser-friendly .mp3 from reliable source? I'll provide alternative: use simple oscillators? No, user expects raban & koha sounds.
                // Since we cannot host actual files, we will use embedded base64? No. But we can create fun beeps as "symbolic" plus still firecracker sound exists.
                // For better realism: I'll create short drum-like sound via Web Audio for raban, and bird whistle for koha.
                // This ensures sound works even without external files and gives cultural vibe!
                // Actually original referenced "raban.mp3" & "koha.mp3" might be missing. I'll generate synthetic but pleasant traditional-ish percussive & cuckoo-like.
                // So the celebration feels alive even without external assets.
                rabanAudio = null; // reset, we will use Web Audio synthesis.
                kohaAudio = null;
            }
        }
        
        // Create web audio context for synthesized traditional sounds (Raban drum + Koha bird)
        let audioCtx = null;
        let isAudioAllowed = false;
        
        function createRabanSound() {
            if (!audioCtx) return;
            const now = audioCtx.currentTime;
            const gainNode = audioCtx.createGain();
            gainNode.gain.setValueAtTime(0.6, now);
            gainNode.gain.exponentialRampToValueAtTime(0.0001, now + 1.2);
            gainNode.connect(audioCtx.destination);
            
            // raban drum: low frequency rhythmic thump + harmonics
            const osc = audioCtx.createOscillator();
            osc.type = 'sine';
            osc.frequency.value = 120;
            osc.connect(gainNode);
            osc.start();
            osc.stop(now + 0.35);
            
            // second layer: fast decay
            const osc2 = audioCtx.createOscillator();
            osc2.type = 'triangle';
            osc2.frequency.value = 240;
            const gain2 = audioCtx.createGain();
            gain2.gain.setValueAtTime(0.3, now);
            gain2.gain.exponentialRampToValueAtTime(0.0001, now + 0.4);
            osc2.connect(gain2);
            gain2.connect(audioCtx.destination);
            osc2.start();
            osc2.stop(now + 0.4);
            
            // short decay noise for drum skin
            const noiseNode = audioCtx.createBufferSource();
            const bufferSize = audioCtx.sampleRate * 0.2;
            const buffer = audioCtx.createBuffer(1, bufferSize, audioCtx.sampleRate);
            const data = buffer.getChannelData(0);
            for (let i = 0; i < bufferSize; i++) {
                data[i] = (Math.random() * 2 - 1) * 0.6;
            }
            noiseNode.buffer = buffer;
            const noiseGain = audioCtx.createGain();
            noiseGain.gain.setValueAtTime(0.45, now);
            noiseGain.gain.exponentialRampToValueAtTime(0.0001, now + 0.25);
            noiseNode.connect(noiseGain);
            noiseGain.connect(audioCtx.destination);
            noiseNode.start(now);
            noiseNode.stop(now + 0.25);
        }
        
        function createKohaSound() {
            if (!audioCtx) return;
            const now = audioCtx.currentTime;
            // Koel / cuckoo bird sound (two notes)
            const osc1 = audioCtx.createOscillator();
            osc1.type = 'sine';
            osc1.frequency.value = 880; // A5
            const gain1 = audioCtx.createGain();
            gain1.gain.setValueAtTime(0.25, now);
            gain1.gain.exponentialRampToValueAtTime(0.0001, now + 0.6);
            osc1.connect(gain1);
            gain1.connect(audioCtx.destination);
            osc1.start();
            osc1.stop(now + 0.45);
            
            const osc2 = audioCtx.createOscillator();
            osc2.type = 'sine';
            osc2.frequency.value = 740; // F#5
            const gain2 = audioCtx.createGain();
            gain2.gain.setValueAtTime(0.22, now + 0.3);
            gain2.gain.exponentialRampToValueAtTime(0.0001, now + 0.85);
            osc2.connect(gain2);
            gain2.connect(audioCtx.destination);
            osc2.start(now + 0.28);
            osc2.stop(now + 0.75);
            
            // slight vibrato for realism
            const lfo = audioCtx.createOscillator();
            lfo.frequency.value = 6;
            const lfoGain = audioCtx.createGain();
            lfoGain.gain.value = 12;
            lfo.connect(lfoGain);
            lfoGain.connect(osc1.frequency);
            lfo.start();
            lfo.stop(now + 0.5);
        }
        
        function playFirecrackerSound() {
            if (!audioCtx || !isAudioAllowed) return;
            const now = audioCtx.currentTime;
            const gainNode = audioCtx.createGain();
            gainNode.gain.setValueAtTime(0.35, now);
            gainNode.gain.exponentialRampToValueAtTime(0.0001, now + 0.8);
            gainNode.connect(audioCtx.destination);
            
            const noise = audioCtx.createBufferSource();
            const bufferSize = audioCtx.sampleRate * 0.35;
            const buffer = audioCtx.createBuffer(1, bufferSize, audioCtx.sampleRate);
            const data = buffer.getChannelData(0);
            for (let i = 0; i < bufferSize; i++) {
                data[i] = (Math.random() * 2 - 1) * 0.7 * (1 - i / bufferSize);
            }
            noise.buffer = buffer;
            noise.connect(gainNode);
            noise.start();
            noise.stop(now + 0.35);
            
            // additional short crackles
            for (let j = 0; j < 3; j++) {
                const crackGain = audioCtx.createGain();
                crackGain.gain.setValueAtTime(0.15, now + j*0.05);
                crackGain.gain.exponentialRampToValueAtTime(0.0001, now + j*0.05 + 0.2);
                crackGain.connect(audioCtx.destination);
                const crackNoise = audioCtx.createBufferSource();
                const crackBuf = audioCtx.createBuffer(1, audioCtx.sampleRate * 0.08, audioCtx.sampleRate);
                const crackData = crackBuf.getChannelData(0);
                for (let k = 0; k < crackBuf.length; k++) {
                    crackData[k] = (Math.random() * 2 - 1) * 0.5;
                }
                crackNoise.buffer = crackBuf;
                crackNoise.connect(crackGain);
                crackNoise.start(now + j*0.07);
                crackNoise.stop(now + j*0.07 + 0.1);
            }
        }
        
        function startContinuousMusic() {
            if (!audioCtx || !isAudioAllowed) return;
            // play rhythmic Raban loop (every 1.2 secs) and Koha call every 3 secs
            if (window.rabanInterval) clearInterval(window.rabanInterval);
            if (window.kohaInterval) clearInterval(window.kohaInterval);
            
            window.rabanInterval = setInterval(() => {
                if (celebrationActive && isAudioAllowed) {
                    createRabanSound();
                }
            }, 1100);
            
            window.kohaInterval = setInterval(() => {
                if (celebrationActive && isAudioAllowed) {
                    createKohaSound();
                }
            }, 3200);
        }
        
        function stopContinuousMusic() {
            if (window.rabanInterval) clearInterval(window.rabanInterval);
            if (window.kohaInterval) clearInterval(window.kohaInterval);
        }
        
        // Fireworks engine
        function launchRocket() {
            if (!celebrationActive) return;
            rockets.push({
                x: Math.random() * width,
                y: height,
                speed: Math.random() * 5 + 5,
                exploded: false,
                colorHue: Math.random() * 360
            });
        }
        
        function explode(x, y, hueBase) {
            if (!celebrationActive) return;
            playFirecrackerSound();
            const count = 140 + Math.floor(Math.random() * 50);
            for (let i = 0; i < count; i++) {
                const angle = Math.random() * Math.PI * 2;
                const speed = Math.random() * 6 + 1.2;
                const colorHue = (hueBase + Math.random() * 80) % 360;
                particles.push({
                    x: x,
                    y: y,
                    angle: angle,
                    speed: speed,
                    alpha: 1,
                    gravity: 0.06,
                    life: 1,
                    color: `hsl(${colorHue}, 100%, 60%)`,
                    size: Math.random() * 3 + 1.5
                });
            }
            // extra glitter
            for (let i = 0; i < 30; i++) {
                particles.push({
                    x: x,
                    y: y,
                    angle: Math.random() * Math.PI * 2,
                    speed: Math.random() * 3 + 2,
                    alpha: 0.9,
                    gravity: 0.03,
                    life: 1,
                    color: `hsl(${Math.random() * 360}, 100%, 70%)`,
                    size: Math.random() * 2 + 1
                });
            }
        }
        
        function animateFireworks() {
            if (!ctx) return;
            ctx.fillStyle = "rgba(0, 0, 0, 0.25)";
            ctx.fillRect(0, 0, width, height);
            
            // draw rockets
            for (let i = 0; i < rockets.length; i++) {
                const r = rockets[i];
                r.y -= r.speed;
                ctx.beginPath();
                ctx.arc(r.x, r.y, 4, 0, Math.PI * 2);
                ctx.fillStyle = `hsl(${r.colorHue}, 100%, 65%)`;
                ctx.fill();
                ctx.shadowBlur = 12;
                ctx.shadowColor = "orange";
                ctx.beginPath();
                ctx.arc(r.x, r.y, 2, 0, Math.PI * 2);
                ctx.fillStyle = "white";
                ctx.fill();
                ctx.shadowBlur = 0;
                
                if (r.y < height * 0.3 + Math.random() * 100 && !r.exploded) {
                    explode(r.x, r.y, r.colorHue);
                    r.exploded = true;
                }
                if (r.y < -20 || r.exploded) {
                    rockets.splice(i, 1);
                    i--;
                }
            }
            
            // update particles
            for (let i = 0; i < particles.length; i++) {
                const p = particles[i];
                p.x += Math.cos(p.angle) * p.speed;
                p.y += Math.sin(p.angle) * p.speed + p.gravity;
                p.alpha -= 0.012;
                p.life -= 0.012;
                if (p.alpha <= 0 || p.y > height + 50 || p.x < -50 || p.x > width + 50) {
                    particles.splice(i, 1);
                    i--;
                    continue;
                }
                ctx.beginPath();
                ctx.arc(p.x, p.y, p.size || 2.5, 0, Math.PI * 2);
                ctx.fillStyle = p.color || `rgba(255, 180, 40, ${p.alpha})`;
                ctx.fill();
                ctx.shadowBlur = 6;
                ctx.shadowColor = "#ffaa33";
            }
            ctx.shadowBlur = 0;
            requestAnimationFrame(animateFireworks);
        }
        
        // start periodic rocket launch
        let launchInterval = null;
        
        function startFireworks() {
            if (launchInterval) clearInterval(launchInterval);
            launchInterval = setInterval(() => {
                if (celebrationActive) {
                    launchRocket();
                    if (Math.random() < 0.4) setTimeout(() => launchRocket(), 200);
                }
            }, 750);
        }
        
        function stopFireworks() {
            if (launchInterval) {
                clearInterval(launchInterval);
                launchInterval = null;
            }
            rockets = [];
            particles = [];
        }
        
        // Falling flower petals for extra Avurudu charm
        let petals = [];
        function createPetal() {
            if (!celebrationActive) return;
            const petalTypes = ['🌸', '🌼', '🌺', '🌻', '🥥', '🍃', '✨'];
            petals.push({
                x: Math.random() * width,
                y: -20,
                size: 18 + Math.random() * 12,
                speedY: 1 + Math.random() * 2.5,
                speedX: (Math.random() - 0.5) * 0.8,
                char: petalTypes[Math.floor(Math.random() * petalTypes.length)],
                rotation: Math.random() * Math.PI * 2,
                alpha: 0.8
            });
        }
        
        function drawPetals() {
            const container = document.getElementById('petalsContainer');
            if (!container) return;
            if (!celebrationActive) {
                container.innerHTML = '';
                petals = [];
                return;
            }
            // update petals
            for (let i=0; i<petals.length; i++) {
                const p = petals[i];
                p.x += p.speedX;
                p.y += p.speedY;
                p.rotation += 0.05;
                if (p.y > height + 50 || p.x < -50 || p.x > width + 70) {
                    petals.splice(i,1);
                    i--;
                }
            }
            let html = '';
            for (let p of petals) {
                html += `<div style="position:absolute; left:${p.x}px; top:${p.y}px; font-size:${p.size}px; opacity:${p.alpha}; transform:rotate(${p.rotation}rad); transition:all 0.02s linear; pointer-events:none;">${p.char}</div>`;
            }
            container.innerHTML = html;
            requestAnimationFrame(() => drawPetals());
        }
        
        let petalInterval = null;
        function startPetals() {
            if (petalInterval) clearInterval(petalInterval);
            petalInterval = setInterval(() => {
                if (celebrationActive) {
                    for(let i=0;i<2;i++) createPetal();
                }
            }, 500);
            drawPetals();
        }
        
        function stopPetals() {
            if (petalInterval) clearInterval(petalInterval);
            document.getElementById('petalsContainer').innerHTML = '';
            petals = [];
        }
        
        // MAIN CELEBRATION TRIGGER
        window.startCelebration = function() {
            if (celebrationActive) return;
            celebrationActive = true;
            
            // Web Audio init on user gesture
            if (!audioCtx) {
                audioCtx = new (window.AudioContext || window.webkitAudioContext)();
            }
            if (audioCtx.state === 'suspended') {
                audioCtx.resume().then(() => {
                    isAudioAllowed = true;
                    startContinuousMusic();
                });
            } else {
                isAudioAllowed = true;
                startContinuousMusic();
            }
            // start all effects
            startFireworks();
            startPetals();
            
            // extra burst: multiple initial rockets
            for (let i=0;i<4;i++) {
                setTimeout(() => { if(celebrationActive) launchRocket(); }, i*180);
            }
            
            // button text change
            const btn = document.getElementById('mainCelebrateBtn');
            if (btn) btn.innerText = "🎊 Celebrating! 🎊";
            setTimeout(() => {
                if(btn && celebrationActive) btn.innerText = "✨ Avurudu Wana ✨";
            }, 1800);
        };
        
        // attach button event
        const celebrateBtn = document.getElementById('mainCelebrateBtn');
        if (celebrateBtn) {
            celebrateBtn.addEventListener('click', (e) => {
                e.preventDefault();
                if (!celebrationActive) {
                    startCelebration();
                }
            });
        }
        
        // auto-start subtle background canvas animation but not active until click, but fireworks idle
        // idle mode no rockets but background
        celebrationActive = false;
        animateFireworks();
        
        // optional - splash effect on window load
        window.addEventListener('load', () => {
            // prewarm canvas
            resizeCanvas();
            // small hint
            console.log("Avurudu ready! Click celebration button");
        });
        
        // cleanup intervals on page unload
        window.addEventListener('beforeunload', () => {
            if (window.rabanInterval) clearInterval(window.rabanInterval);
            if (window.kohaInterval) clearInterval(window.kohaInterval);
            if (launchInterval) clearInterval(launchInterval);
            if (petalInterval) clearInterval(petalInterval);
            if (audioCtx) audioCtx.close();
        });
        
        // ensure click also resumes audio if needed
        document.body.addEventListener('click', function() {
            if (audioCtx && audioCtx.state === 'suspended' && celebrationActive) {
                audioCtx.resume();
            }
        });
    })();
</script>
</body>
</html>
