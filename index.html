<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Quantum Vacuum Thruster Simulation Lab</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #0a0a2a 0%, #1a1a3a 100%);
            color: #e0e0ff;
            min-height: 100vh;
            padding: 20px;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
        }
        
        header {
            text-align: center;
            margin-bottom: 30px;
            padding: 20px;
            background: rgba(10, 15, 40, 0.7);
            border-radius: 15px;
            border: 1px solid #2a3a8a;
            box-shadow: 0 0 20px rgba(0, 100, 255, 0.2);
        }
        
        h1 {
            font-size: 2.8rem;
            margin-bottom: 10px;
            background: linear-gradient(90deg, #4facfe 0%, #00f2fe 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            text-shadow: 0 0 15px rgba(79, 172, 254, 0.5);
        }
        
        .subtitle {
            font-size: 1.2rem;
            opacity: 0.9;
            max-width: 800px;
            margin: 0 auto;
            line-height: 1.5;
        }
        
        .lab-container {
            display: flex;
            flex-wrap: wrap;
            gap: 25px;
            margin-bottom: 30px;
        }
        
        .simulation-panel {
            flex: 3;
            min-width: 300px;
            background: rgba(15, 20, 45, 0.8);
            border-radius: 15px;
            padding: 25px;
            border: 1px solid #2a3a8a;
            box-shadow: 0 0 25px rgba(0, 100, 255, 0.15);
            overflow: hidden;
        }
        
        .controls-panel {
            flex: 1;
            min-width: 250px;
            background: rgba(15, 20, 45, 0.8);
            border-radius: 15px;
            padding: 25px;
            border: 1px solid #2a3a8a;
            box-shadow: 0 0 25px rgba(0, 100, 255, 0.15);
        }
        
        .panel-title {
            font-size: 1.5rem;
            margin-bottom: 20px;
            color: #6eb6ff;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .panel-title i {
            color: #00f2fe;
        }
        
        .simulation-area {
            width: 100%;
            height: 400px;
            background: rgba(5, 10, 30, 0.9);
            border-radius: 10px;
            border: 1px solid #1a2a6a;
            position: relative;
            overflow: hidden;
            margin-bottom: 20px;
        }
        
        #simulationCanvas {
            width: 100%;
            height: 100%;
            display: block;
        }
        
        .thruster {
            position: absolute;
            bottom: 50px;
            left: 50%;
            transform: translateX(-50%);
            width: 180px;
            height: 80px;
            background: linear-gradient(90deg, #2a2a5a 0%, #3a3a7a 100%);
            border-radius: 10px 10px 0 0;
            border: 2px solid #4a6aff;
            z-index: 10;
            display: flex;
            justify-content: center;
            align-items: center;
            color: #aaccff;
            font-weight: bold;
            box-shadow: 0 0 15px rgba(74, 106, 255, 0.5);
        }
        
        .thruster::before {
            content: '';
            position: absolute;
            bottom: -25px;
            width: 120px;
            height: 25px;
            background: linear-gradient(90deg, #3a3a7a 0%, #2a2a5a 100%);
            border-radius: 0 0 5px 5px;
        }
        
        .controls {
            display: flex;
            flex-direction: column;
            gap: 20px;
        }
        
        .control-group {
            background: rgba(10, 15, 40, 0.6);
            padding: 15px;
            border-radius: 10px;
            border: 1px solid #2a3a8a;
        }
        
        .control-title {
            font-size: 1.1rem;
            margin-bottom: 12px;
            color: #8ac7ff;
        }
        
        .slider-container {
            display: flex;
            align-items: center;
            gap: 15px;
            margin-bottom: 10px;
        }
        
        .slider-value {
            min-width: 40px;
            text-align: center;
            font-weight: bold;
            color: #00f2fe;
        }
        
        input[type="range"] {
            flex: 1;
            height: 8px;
            -webkit-appearance: none;
            background: linear-gradient(90deg, #0a2a5a 0%, #2a6aff 100%);
            border-radius: 4px;
            outline: none;
        }
        
        input[type="range"]::-webkit-slider-thumb {
            -webkit-appearance: none;
            width: 22px;
            height: 22px;
            border-radius: 50%;
            background: #00f2fe;
            cursor: pointer;
            box-shadow: 0 0 10px rgba(0, 242, 254, 0.8);
        }
        
        .btn {
            background: linear-gradient(90deg, #2a6aff 0%, #00a8ff 100%);
            color: white;
            border: none;
            padding: 12px 20px;
            border-radius: 8px;
            cursor: pointer;
            font-weight: bold;
            font-size: 1rem;
            transition: all 0.3s ease;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
        }
        
        .btn:hover {
            background: linear-gradient(90deg, #3a7aff 0%, #00b8ff 100%);
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(0, 168, 255, 0.4);
        }
        
        .btn:active {
            transform: translateY(0);
        }
        
        .btn-stop {
            background: linear-gradient(90deg, #ff2a2a 0%, #ff6a6a 100%);
        }
        
        .btn-stop:hover {
            background: linear-gradient(90deg, #ff3a3a 0%, #ff7a7a 100%);
            box-shadow: 0 5px 15px rgba(255, 42, 42, 0.4);
        }
        
        .buttons {
            display: flex;
            gap: 15px;
            margin-top: 10px;
        }
        
        .readout {
            background: rgba(5, 10, 30, 0.9);
            padding: 15px;
            border-radius: 10px;
            border: 1px solid #2a3a8a;
            margin-top: 20px;
        }
        
        .readout-value {
            font-size: 1.8rem;
            font-weight: bold;
            color: #00f2fe;
            text-align: center;
            margin: 10px 0;
            text-shadow: 0 0 10px rgba(0, 242, 254, 0.7);
        }
        
        .readout-label {
            display: flex;
            justify-content: space-between;
            margin-bottom: 8px;
            font-size: 0.9rem;
            color: #aaccff;
        }
        
        .readout-bar {
            height: 10px;
            background: rgba(10, 20, 60, 0.7);
            border-radius: 5px;
            overflow: hidden;
            margin-bottom: 15px;
        }
        
        .readout-fill {
            height: 100%;
            background: linear-gradient(90deg, #00a8ff 0%, #00f2fe 100%);
            border-radius: 5px;
            width: 0%;
            transition: width 0.5s ease;
        }
        
        .theory-panel {
            background: rgba(15, 20, 45, 0.8);
            border-radius: 15px;
            padding: 25px;
            border: 1px solid #2a3a8a;
            box-shadow: 0 0 25px rgba(0, 100, 255, 0.15);
            margin-top: 20px;
        }
        
        .theory-content {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }
        
        .theory-card {
            background: rgba(10, 15, 40, 0.6);
            padding: 20px;
            border-radius: 10px;
            border-left: 4px solid #00a8ff;
        }
        
        .theory-card h3 {
            color: #6eb6ff;
            margin-bottom: 10px;
            font-size: 1.2rem;
        }
        
        .theory-card p {
            line-height: 1.6;
            opacity: 0.9;
            font-size: 0.95rem;
        }
        
        footer {
            text-align: center;
            margin-top: 30px;
            padding: 20px;
            color: #8899cc;
            font-size: 0.9rem;
            border-top: 1px solid #2a3a8a;
        }
        
        @media (max-width: 768px) {
            .lab-container {
                flex-direction: column;
            }
            
            h1 {
                font-size: 2rem;
            }
            
            .simulation-area {
                height: 300px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1><i class="fas fa-atom"></i> Quantum Vacuum Thruster Simulation Lab</h1>
            <p class="subtitle">An interactive simulation exploring the speculative principles of quantum vacuum fluctuations and their potential application in propellantless propulsion systems.</p>
        </header>
        
        <div class="lab-container">
            <div class="simulation-panel">
                <h2 class="panel-title"><i class="fas fa-vials"></i> Quantum Vacuum Simulation</h2>
                <div class="simulation-area">
                    <canvas id="simulationCanvas"></canvas>
                    <div class="thruster" id="thruster">
                        <i class="fas fa-rocket"></i> QVT-Prototype
                    </div>
                </div>
                <div class="readout">
                    <div class="readout-label">
                        <span>Virtual Particle Density</span>
                        <span id="densityValue">Medium</span>
                    </div>
                    <div class="readout-bar">
                        <div class="readout-fill" id="densityBar"></div>
                    </div>
                    
                    <div class="readout-label">
                        <span>Thrust Generated</span>
                        <span id="thrustValue">0.00 µN</span>
                    </div>
                    <div class="readout-bar">
                        <div class="readout-fill" id="thrustBar"></div>
                    </div>
                    
                    <div class="readout-label">
                        <span>Cavity Resonance</span>
                        <span id="resonanceValue">85%</span>
                    </div>
                    <div class="readout-bar">
                        <div class="readout-fill" id="resonanceBar"></div>
                    </div>
                </div>
            </div>
            
            <div class="controls-panel">
                <h2 class="panel-title"><i class="fas fa-sliders-h"></i> Control Panel</h2>
                <div class="controls">
                    <div class="control-group">
                        <div class="control-title">Virtual Particle Density</div>
                        <div class="slider-container">
                            <span class="slider-value" id="densitySliderValue">5</span>
                            <input type="range" id="densitySlider" min="1" max="10" value="5" step="1">
                        </div>
                        <div style="font-size: 0.85rem; opacity: 0.8; margin-top: 5px;">Controls the density of virtual particle-antiparticle pairs in the quantum vacuum.</div>
                    </div>
                    
                    <div class="control-group">
                        <div class="control-title">Resonance Frequency</div>
                        <div class="slider-container">
                            <span class="slider-value" id="frequencySliderValue">2.45</span>
                            <input type="range" id="frequencySlider" min="1" max="5" value="2.45" step="0.05">
                            <span>GHz</span>
                        </div>
                        <div style="font-size: 0.85rem; opacity: 0.8; margin-top: 5px;">Microwave frequency in the resonant cavity.</div>
                    </div>
                    
                    <div class="control-group">
                        <div class="control-title">Cavity Asymmetry</div>
                        <div class="slider-container">
                            <span class="slider-value" id="asymmetrySliderValue">0.7</span>
                            <input type="range" id="asymmetrySlider" min="0.1" max="1.5" value="0.7" step="0.1">
                        </div>
                        <div style="font-size: 0.85rem; opacity: 0.8; margin-top: 5px;">Shape asymmetry factor of the resonant cavity.</div>
                    </div>
                    
                    <div class="control-group">
                        <div class="control-title">Power Input</div>
                        <div class="slider-container">
                            <span class="slider-value" id="powerSliderValue">100</span>
                            <input type="range" id="powerSlider" min="10" max="500" value="100" step="10">
                            <span>W</span>
                        </div>
                        <div style="font-size: 0.85rem; opacity: 0.8; margin-top: 5px;">Electrical power supplied to the microwave generator.</div>
                    </div>
                    
                    <div class="buttons">
                        <button class="btn" id="startBtn">
                            <i class="fas fa-play"></i> Start Simulation
                        </button>
                        <button class="btn btn-stop" id="stopBtn">
                            <i class="fas fa-stop"></i> Stop
                        </button>
                    </div>
                </div>
            </div>
        </div>
        
        <div class="theory-panel">
            <h2 class="panel-title"><i class="fas fa-lightbulb"></i> Theoretical Background</h2>
            <div class="theory-content">
                <div class="theory-card">
                    <h3>Quantum Vacuum Fluctuations</h3>
                    <p>According to quantum field theory, empty space is not truly empty but filled with virtual particle-antiparticle pairs that constantly pop in and out of existence. These fleeting quantum fluctuations have measurable effects like the Casimir force.</p>
                </div>
                
                <div class="theory-card">
                    <h3>Thruster Principle</h3>
                    <p>The hypothetical quantum vacuum thruster aims to create a net thrust by interacting with these virtual particles using an asymmetric resonant cavity. Microwaves bounce within the cavity, theoretically transferring momentum to the quantum vacuum.</p>
                </div>
                
                <div class="theory-card">
                    <h3>Scientific Controversy</h3>
                    <p>This concept is highly controversial as it appears to violate conservation of momentum. Experimental results have been inconsistent, with most physicists attributing observed thrust to measurement errors or thermal effects.</p>
                </div>
            </div>
        </div>
        
        <footer>
            <p>Quantum Vacuum Thruster Simulation | This is a conceptual visualization for educational purposes only</p>
            <p>Based on theoretical physics and speculative engineering concepts | Not representative of actual proven technology</p>
        </footer>
    </div>

    <script>
        // Canvas setup
        const canvas = document.getElementById('simulationCanvas');
        const ctx = canvas.getContext('2d');
        canvas.width = canvas.offsetWidth;
        canvas.height = canvas.offsetHeight;

        // Simulation state
        let simulationRunning = false;
        let animationId = null;
        let particles = [];
        let thrust = 0;
        let resonance = 85;
        let lastTime = 0;
        
        // Thruster position
        let thrusterX = canvas.width / 2;
        let thrusterY = canvas.height - 80;
        let thrusterVelocity = 0;
        
        // DOM Elements
        const densitySlider = document.getElementById('densitySlider');
        const frequencySlider = document.getElementById('frequencySlider');
        const asymmetrySlider = document.getElementById('asymmetrySlider');
        const powerSlider = document.getElementById('powerSlider');
        const startBtn = document.getElementById('startBtn');
        const stopBtn = document.getElementById('stopBtn');
        
        const densityValue = document.getElementById('densityValue');
        const frequencyValue = document.getElementById('frequencySliderValue');
        const asymmetryValue = document.getElementById('asymmetrySliderValue');
        const powerValue = document.getElementById('powerSliderValue');
        
        const thrustValue = document.getElementById('thrustValue');
        const resonanceValue = document.getElementById('resonanceValue');
        const densityBar = document.getElementById('densityBar');
        const thrustBar = document.getElementById('thrustBar');
        const resonanceBar = document.getElementById('resonanceBar');
        
        // Particle class for virtual particle-antiparticle pairs
        class QuantumParticle {
            constructor(x, y, type) {
                this.x = x;
                this.y = y;
                this.type = type; // 'particle' or 'antiparticle'
                this.size = Math.random() * 4 + 2;
                this.speedX = (Math.random() - 0.5) * 2;
                this.speedY = (Math.random() - 0.5) * 2;
                this.life = Math.random() * 100 + 50;
                this.maxLife = this.life;
                this.color = this.type === 'particle' ? 
                    `rgba(100, 180, 255, ${0.7})` : 
                    `rgba(255, 100, 180, ${0.7})`;
            }
            
            update() {
                this.x += this.speedX;
                this.y += this.speedY;
                this.life--;
                
                // Bounce off walls
                if (this.x <= 0 || this.x >= canvas.width) this.speedX *= -1;
                if (this.y <= 0 || this.y >= canvas.height) this.speedY *= -1;
                
                // Apply some randomness
                this.speedX += (Math.random() - 0.5) * 0.1;
                this.speedY += (Math.random() - 0.5) * 0.1;
                
                // Limit speed
                const speed = Math.sqrt(this.speedX * this.speedX + this.speedY * this.speedY);
                if (speed > 3) {
                    this.speedX = (this.speedX / speed) * 3;
                    this.speedY = (this.speedY / speed) * 3;
                }
            }
            
            draw() {
                const alpha = this.life / this.maxLife;
                ctx.beginPath();
                ctx.arc(this.x, this.y, this.size, 0, Math.PI * 2);
                
                if (this.type === 'particle') {
                    ctx.fillStyle = `rgba(100, 180, 255, ${alpha * 0.7})`;
                } else {
                    ctx.fillStyle = `rgba(255, 100, 180, ${alpha * 0.7})`;
                }
                
                ctx.fill();
                
                // Draw annihilation effect when particles meet
                if (this.life < 20) {
                    ctx.beginPath();
                    ctx.arc(this.x, this.y, this.size * (1 + (1 - this.life/20) * 3), 0, Math.PI * 2);
                    ctx.strokeStyle = `rgba(255, 255, 200, ${alpha * 0.3})`;
                    ctx.lineWidth = 1;
                    ctx.stroke();
                }
            }
        }
        
        // Initialize particles
        function initParticles() {
            particles = [];
            const density = parseInt(densitySlider.value);
            const count = density * 15;
            
            for (let i = 0; i < count; i++) {
                const x = Math.random() * canvas.width;
                const y = Math.random() * canvas.height;
                const type = Math.random() > 0.5 ? 'particle' : 'antiparticle';
                particles.push(new QuantumParticle(x, y, type));
            }
        }
        
        // Update simulation
        function updateSimulation(timestamp) {
            if (!lastTime) lastTime = timestamp;
            const deltaTime = Math.min(timestamp - lastTime, 100) / 1000;
            lastTime = timestamp;
            
            // Update particles
            particles.forEach(particle => {
                particle.update();
                
                // Remove dead particles and create new ones
                if (particle.life <= 0) {
                    const index = particles.indexOf(particle);
                    particles.splice(index, 1);
                    
                    // Create new particle
                    const density = parseInt(densitySlider.value);
                    if (particles.length < density * 15) {
                        const x = Math.random() * canvas.width;
                        const y = Math.random() * canvas.height;
                        const type = Math.random() > 0.5 ? 'particle' : 'antiparticle';
                        particles.push(new QuantumParticle(x, y, type));
                    }
                }
            });
            
            // Calculate thrust based on control values
            if (simulationRunning) {
                const frequency = parseFloat(frequencySlider.value);
                const asymmetry = parseFloat(asymmetrySlider.value);
                const power = parseInt(powerSlider.value);
                const density = parseInt(densitySlider.value);
                
                // Simplified thrust calculation (purely illustrative)
                let newThrust = (power / 100) * (frequency / 2.45) * asymmetry * (density / 5);
                
                // Add some random fluctuation
                newThrust += (Math.random() - 0.5) * 0.1;
                
                // Smooth thrust change
                thrust += (newThrust - thrust) * 0.1;
                
                // Update resonance (affected by frequency tuning)
                resonance = 70 + (30 * Math.sin(timestamp / 3000)) + 
                            (10 * (frequency / 2.45 - 1)) + 
                            (Math.random() - 0.5) * 5;
                resonance = Math.max(50, Math.min(99, resonance));
                
                // Update thruster position based on thrust
                thrusterVelocity += (thrust * 0.01 - thrusterVelocity * 0.05) * deltaTime;
                thrusterX += thrusterVelocity * deltaTime * 50;
                
                // Keep thruster on screen
                thrusterX = Math.max(90, Math.min(canvas.width - 90, thrusterX));
            }
            
            // Update display values
            updateDisplay();
            
            // Draw everything
            draw();
            
            if (simulationRunning) {
                animationId = requestAnimationFrame(updateSimulation);
            }
        }
        
        // Draw simulation
        function draw() {
            // Clear canvas with a dark background
            ctx.fillStyle = 'rgba(5, 10, 30, 0.2)';
            ctx.fillRect(0, 0, canvas.width, canvas.height);
            
            // Draw quantum vacuum "background field"
            drawQuantumField();
            
            // Draw particles
            particles.forEach(particle => particle.draw());
            
            // Draw thruster exhaust effect
            if (simulationRunning && thrust > 0.1) {
                drawExhaust();
            }
            
            // Draw microwave resonance pattern
            if (simulationRunning) {
                drawResonancePattern();
            }
        }
        
        function drawQuantumField() {
            // Draw subtle grid/field lines
            ctx.strokeStyle = 'rgba(50, 100, 200, 0.05)';
            ctx.lineWidth = 1;
            
            for (let x = 0; x < canvas.width; x += 40) {
                ctx.beginPath();
                ctx.moveTo(x, 0);
                ctx.lineTo(x, canvas.height);
                ctx.stroke();
            }
            
            for (let y = 0; y < canvas.height; y += 40) {
                ctx.beginPath();
                ctx.moveTo(0, y);
                ctx.lineTo(canvas.width, y);
                ctx.stroke();
            }
            
            // Draw quantum foam effect
            for (let i = 0; i < 30; i++) {
                const x = Math.random() * canvas.width;
                const y = Math.random() * canvas.height;
                const size = Math.random() * 3 + 1;
                
                ctx.beginPath();
                ctx.arc(x, y, size, 0, Math.PI * 2);
                ctx.fillStyle = `rgba(100, 150, 255, ${Math.random() * 0.1})`;
                ctx.fill();
            }
        }
        
        function drawExhaust() {
            // Draw thruster exhaust plume
            const plumeWidth = 60 + thrust * 10;
            const plumeHeight = 80 + thrust * 20;
            
            const gradient = ctx.createLinearGradient(
                thrusterX - plumeWidth/2, thrusterY + 40,
                thrusterX + plumeWidth/2, thrusterY + plumeHeight
            );
            
            gradient.addColorStop(0, `rgba(0, 200, 255, ${0.8})`);
            gradient.addColorStop(0.5, `rgba(100, 100, 255, ${0.5})`);
            gradient.addColorStop(1, `rgba(150, 50, 255, ${0})`);
            
            ctx.fillStyle = gradient;
            ctx.beginPath();
            ctx.moveTo(thrusterX - plumeWidth/2, thrusterY + 40);
            ctx.lineTo(thrusterX + plumeWidth/2, thrusterY + 40);
            ctx.lineTo(thrusterX, thrusterY + plumeHeight);
            ctx.closePath();
            ctx.fill();
            
            // Draw particle streaks in exhaust
            for (let i = 0; i < thrust * 20; i++) {
                const x = thrusterX + (Math.random() - 0.5) * plumeWidth;
                const y = thrusterY + 40 + Math.random() * plumeHeight;
                const length = Math.random() * 20 + 10;
                
                ctx.beginPath();
                ctx.moveTo(x, y);
                ctx.lineTo(x + (Math.random() - 0.5) * 10, y + length);
                ctx.strokeStyle = `rgba(100, 200, 255, ${Math.random() * 0.7})`;
                ctx.lineWidth = Math.random() * 2 + 1;
                ctx.stroke();
            }
        }
        
        function drawResonancePattern() {
            // Draw microwave resonance pattern around thruster
            const frequency = parseFloat(frequencySlider.value);
            const asymmetry = parseFloat(asymmetrySlider.value);
            const patternRadius = 100 + (frequency - 1) * 30;
            
            ctx.strokeStyle = `rgba(0, 200, 255, ${0.3 + resonance/200})`;
            ctx.lineWidth = 2;
            ctx.setLineDash([5, 5]);
            
            // Draw asymmetric resonance cavity
            ctx.beginPath();
            ctx.ellipse(
                thrusterX, 
                thrusterY - 20, 
                patternRadius * (0.8 + asymmetry * 0.4), 
                patternRadius * (0.8 + (1 - asymmetry) * 0.4), 
                0, 0, Math.PI * 2
            );
            ctx.stroke();
            
            // Draw resonance waves
            const waveCount = Math.floor(frequency * 2);
            for (let i = 0; i < waveCount; i++) {
                const radius = patternRadius + i * 15;
                const alpha = 0.7 - i * 0.15;
                
                ctx.beginPath();
                ctx.arc(thrusterX, thrusterY - 20, radius, 0, Math.PI * 2);
                ctx.strokeStyle = `rgba(100, 150, 255, ${alpha})`;
                ctx.lineWidth = 1;
                ctx.stroke();
            }
            
            ctx.setLineDash([]);
        }
        
        function updateDisplay() {
            // Update slider value displays
            densityValue.textContent = getDensityLabel(parseInt(densitySlider.value));
            frequencyValue.textContent = frequencySlider.value;
            asymmetryValue.textContent = asymmetrySlider.value;
            powerValue.textContent = powerSlider.value;
            
            // Update bars
            densityBar.style.width = `${(parseInt(densitySlider.value) / 10) * 100}%`;
            thrustBar.style.width = `${Math.min(thrust * 10, 100)}%`;
            resonanceBar.style.width = `${resonance}%`;
            
            // Update numeric displays
            thrustValue.textContent = `${thrust.toFixed(2)} µN`;
            resonanceValue.textContent = `${Math.round(resonance)}%`;
            
            // Update thruster position
            const thrusterElement = document.getElementById('thruster');
            thrusterElement.style.left = `${(thrusterX / canvas.width) * 100}%`;
            
            // Update thruster appearance based on thrust
            const thrustColor = Math.min(255, Math.floor(thrust * 50));
            thrusterElement.style.boxShadow = `0 0 15px rgba(${thrustColor}, ${thrustColor}, 255, 0.5)`;
        }
        
        function getDensityLabel(value) {
            const labels = ['Very Low', 'Low', 'Medium-Low', 'Medium', 'Medium-High', 'High', 'Very High', 'Extreme', 'Quantum Foam', 'Planck Density'];
            return labels[value - 1] || 'Medium';
        }
        
        // Event listeners
        densitySlider.addEventListener('input', function() {
            if (simulationRunning) {
                initParticles();
            }
        });
        
        frequencySlider.addEventListener('input', function() {
            // Resonance is affected by frequency
            resonance = 70 + 20 * Math.sin(parseFloat(this.value));
        });
        
        startBtn.addEventListener('click', function() {
            if (!simulationRunning) {
                simulationRunning = true;
                lastTime = 0;
                initParticles();
                animationId = requestAnimationFrame(updateSimulation);
                startBtn.innerHTML = '<i class="fas fa-pause"></i> Pause Simulation';
                startBtn.classList.add('btn-stop');
            } else {
                simulationRunning = false;
                cancelAnimationFrame(animationId);
                startBtn.innerHTML = '<i class="fas fa-play"></i> Resume Simulation';
                startBtn.classList.remove('btn-stop');
            }
        });
        
        stopBtn.addEventListener('click', function() {
            simulationRunning = false;
            if (animationId) cancelAnimationFrame(animationId);
            
            // Reset values
            thrust = 0;
            resonance = 85;
            thrusterX = canvas.width / 2;
            thrusterVelocity = 0;
            
            startBtn.innerHTML = '<i class="fas fa-play"></i> Start Simulation';
            startBtn.classList.remove('btn-stop');
            
            updateDisplay();
        });
        
        // Handle window resize
        window.addEventListener('resize', function() {
            canvas.width = canvas.offsetWidth;
            canvas.height = canvas.offsetHeight;
            thrusterX = canvas.width / 2;
            thrusterY = canvas.height - 80;
            initParticles();
        });
        
        // Initialize
        initParticles();
        draw();
        updateDisplay();
        
        // Add some initial particles for visual effect
        for (let i = 0; i < 50; i++) {
            const x = Math.random() * canvas.width;
            const y = Math.random() * canvas.height;
            const type = Math.random() > 0.5 ? 'particle' : 'antiparticle';
            particles.push(new QuantumParticle(x, y, type));
        }
    </script>
</body>
</html>
