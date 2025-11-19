<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nithin | Creative Developer</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js"></script>
    <script src="https://unpkg.com/lucide@latest"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600&family=Italiana&family=Syncopate:wght@700&display=swap" rel="stylesheet">
    
    <style>
        :root {
            --bg-color: #080808;
            --text-main: #ffffff;
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-main);
            margin: 0;
            overflow-x: hidden;
            cursor: none;
            font-family: 'Inter', sans-serif;
        }

        body::-webkit-scrollbar { display: none; }
        html { -ms-overflow-style: none; scrollbar-width: none; }

        .serif { font-family: 'Italiana', serif; }
        .display-font { font-family: 'Syncopate', sans-serif; }

        #canvas-wrap {
            position: fixed; top: 0; left: 0; width: 100vw; height: 100vh;
            z-index: 0; pointer-events: none;
        }

        .texture-layer {
            position: fixed; top: 0; left: 0; width: 100%; height: 100%;
            pointer-events: none; z-index: 1;
            background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 200 200' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='noiseFilter'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.65' numOctaves='3' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23noiseFilter)'/%3E%3C/svg%3E");
            opacity: 0.07;
        }

        #main-content {
            position: relative; z-index: 10;
            will-change: transform;
            padding-top: 20vh;
        }

        .diff-mode { mix-blend-mode: difference; color: white; }
        
        .card {
            background: rgba(255, 255, 255, 0.02);
            backdrop-filter: blur(16px);
            -webkit-backdrop-filter: blur(16px);
            border: 1px solid rgba(255, 255, 255, 0.08);
            transition: transform 0.4s ease, border-color 0.3s;
        }
        .card:hover {
            border-color: rgba(255, 255, 255, 0.3);
            transform: scale(1.005);
        }

        #pointer {
            position: fixed; top: 0; left: 0; width: 12px; height: 12px;
            border: 1px solid white; border-radius: 50%;
            transform: translate(-50%, -50%); pointer-events: none; z-index: 9999;
            mix-blend-mode: difference;
            transition: width 0.2s, height 0.2s, background-color 0.2s;
        }
        #pointer.active { width: 64px; height: 64px; background: white; border-color: transparent; }

        .anim-up {
            transform: translateY(100%); opacity: 0;
            animation: slideUp 0.8s cubic-bezier(0.2, 1, 0.3, 1) forwards;
        }
        .d-1 { animation-delay: 0.1s; }
        .d-2 { animation-delay: 0.2s; }
        .d-3 { animation-delay: 0.3s; }

        @keyframes slideUp {
            0% { transform: translateY(40px); opacity: 0; }
            100% { transform: translateY(0); opacity: 1; }
        }

        .ticker-wrap {
            overflow: hidden; white-space: nowrap; position: relative;
        }
        .ticker {
            display: inline-block; animation: tickerScroll 25s linear infinite;
        }
        @keyframes tickerScroll { 0% { transform: translateX(0); } 100% { transform: translateX(-50%); } }
    </style>
</head>
<body>

    <div id="pointer"></div>

    <div class="texture-layer"></div>

    <div id="canvas-wrap"></div>

    <main id="main-content" class="w-full min-h-screen px-6 md:px-16 pb-24">
        
        <nav class="fixed top-0 left-0 w-full p-8 flex justify-between items-center z-50 diff-mode pointer-events-none">
            <div class="display-font font-bold text-lg tracking-widest pointer-events-auto cursor-pointer hover:opacity-60 transition-opacity">
                NITHIN
            </div>
            <div class="hidden md:flex gap-10 text-xs uppercase tracking-[0.2em] font-bold pointer-events-auto">
                <a href="#projects" class="hover:underline">Projects</a>
                <a href="#about" class="hover:underline">About</a>
                <a href="mailto:contact@nithinspacetime.com" class="hover:underline">Connect</a>
            </div>
        </nav>

        <section class="min-h-[75vh] flex flex-col justify-center relative mb-24">
            <div class="diff-mode">
                <p class="text-xs md:text-sm uppercase tracking-[0.4em] mb-4 anim-up">Full Stack Developer</p>
                <h1 class="serif text-[14vw] leading-[0.85] anim-up d-1">
                    Creative
                </h1>
                <div class="flex items-center gap-6 md:gap-10 anim-up d-2">
                    <div class="h-[1px] w-16 md:w-32 bg-white"></div>
                    <h1 class="serif text-[14vw] leading-[0.85] italic">
                        Technologist
                    </h1>
                </div>
            </div>
            
            <div class="absolute bottom-0 right-0 max-w-md text-right diff-mode anim-up d-3">
                <p class="text-sm md:text-base font-light leading-relaxed opacity-90">
                    Specializing in high-performance web applications, interactive 3D experiences, and scalable frontend architecture.
                </p>
                <div class="mt-6 flex justify-end gap-6 text-xs font-mono uppercase opacity-70">
                    <span>React</span>
                    <span>WebGL</span>
                    <span>Node.js</span>
                </div>
            </div>
        </section>

        <section id="projects" class="w-full max-w-[1600px] mx-auto mb-32">
            <div class="flex items-baseline justify-between mb-10 diff-mode border-b border-white/10 pb-4">
                <h2 class="text-3xl md:text-5xl serif">Selected Works</h2>
                <span class="font-mono text-xs opacity-60">01 / 04</span>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-5 h-auto md:h-[750px]">
                
                <a href="https://github.com/NITHINSPACETIME" target="_blank" class="card col-span-1 md:col-span-1 md:row-span-2 p-8 flex flex-col justify-between group relative overflow-hidden">
                    <div class="absolute inset-0 bg-gradient-to-b from-transparent to-purple-900/10 opacity-0 group-hover:opacity-100 transition-opacity duration-500"></div>
                    
                    <div class="relative z-10 flex justify-between items-start">
                        <span class="font-mono text-[10px] border border-white/10 px-2 py-1 rounded-full uppercase tracking-wider">Repositories</span>
                        <i data-lucide="arrow-up-right" class="w-5 h-5 opacity-60"></i>
                    </div>
                    
                    <div class="relative z-10 mt-8">
                        <i data-lucide="github" class="w-12 h-12 mb-5 opacity-90 group-hover:scale-105 transition-transform duration-300"></i>
                        <h3 class="text-3xl serif mb-2">GitHub</h3>
                        <p class="text-xs text-gray-400 font-light leading-relaxed">
                            Open source contributions, experimental libraries, and production-ready codebases.
                        </p>
                        <div class="mt-6 font-mono text-[10px] text-white/50 group-hover:text-white transition-colors">
                            VIEW PROFILE
                        </div>
                    </div>
                </a>

                <a href="https://myanimelist.net/profile/NITHINSPACETIME" target="_blank" class="card col-span-1 md:col-span-2 p-8 flex flex-col md:flex-row items-end md:items-center justify-between group relative overflow-hidden">
                    <div class="absolute inset-0 bg-[url('https://images.unsplash.com/photo-1626544827763-d516dce335ca?q=80&w=2000&auto=format&fit=crop')] bg-cover bg-center opacity-0 group-hover:opacity-20 transition-opacity duration-700 grayscale"></div>
                    
                    <div class="relative z-10">
                        <span class="font-mono text-[10px] border border-white/10 px-2 py-1 rounded-full uppercase tracking-wider">Database</span>
                        <h3 class="text-5xl md:text-6xl serif mt-4 group-hover:italic transition-all">MAL</h3>
                    </div>
                    <div class="relative z-10 text-right mt-6 md:mt-0">
                        <div class="text-lg font-light">MyAnimeList</div>
                        <div class="text-xs text-gray-400 mt-1">Personal collection & ratings</div>
                    </div>
                </a>

                <a href="https://anilist.co/user/NITHINSPACETIME/" target="_blank" class="card col-span-1 p-8 flex flex-col justify-center group relative">
                    <div class="absolute inset-0 bg-blue-900/5 opacity-0 group-hover:opacity-100 transition-opacity"></div>
                    <div class="relative z-10 text-center">
                        <h3 class="text-2xl font-bold tracking-tight mb-2">AniList</h3>
                        <div class="w-6 h-[2px] bg-blue-400 mx-auto opacity-70"></div>
                        <p class="mt-4 text-[10px] font-mono text-blue-200/80 uppercase tracking-widest">Sync Active</p>
                    </div>
                </a>

                <div class="card col-span-1 p-8 flex flex-col justify-between relative group">
                    <div class="absolute top-6 right-6">
                         <span class="font-mono text-[10px] border border-white/10 px-2 py-1 rounded-full uppercase tracking-wider">Stack</span>
                    </div>
                    <div class="mt-auto">
                        <div class="flex flex-wrap gap-x-3 gap-y-1">
                            <span class="text-xl md:text-2xl serif text-white/90">React</span>
                            <span class="text-xl md:text-2xl serif text-white/50">Three.js</span>
                            <span class="text-xl md:text-2xl serif text-white/90">TypeScript</span>
                            <span class="text-xl md:text-2xl serif text-white/50">Node</span>
                            <span class="text-xl md:text-2xl serif text-white/90">Next.js</span>
                            <span class="text-xl md:text-2xl serif text-white/50">PostgreSQL</span>
                        </div>
                    </div>
                </div>

            </div>
        </section>

        <div class="py-20 diff-mode opacity-40">
            <div class="ticker-wrap">
                <div class="ticker">
                    <span class="text-7xl display-font font-bold mx-6">DESIGN & DEVELOPMENT</span>
                    <span class="text-7xl display-font font-bold mx-6 text-transparent stroke-white" style="-webkit-text-stroke: 1px white;">INTERACTIVE EXPERIENCES</span>
                    <span class="text-7xl display-font font-bold mx-6">FULL STACK ENGINEERING</span>
                    <span class="text-7xl display-font font-bold mx-6 text-transparent stroke-white" style="-webkit-text-stroke: 1px white;">WEBGL EXPERIMENTS</span>
                </div>
            </div>
        </div>

        <footer class="flex flex-col items-center justify-center py-32 diff-mode relative">
            <p class="text-[10px] uppercase tracking-widest mb-8 opacity-60">Have a project in mind?</p>
            <a href="mailto:contact@nithinspacetime.com" class="text-4xl md:text-8xl serif hover:italic transition-all duration-300 cursor-none">
                Get in touch.
            </a>
            
            <div class="absolute bottom-0 w-full flex justify-between px-8 pb-8 text-[10px] font-mono uppercase text-white/40">
                <span>&copy; 2025 Nithin</span>
                <span id="clock">00:00:00</span>
            </div>
        </footer>

    </main>

    <script id="v-shader" type="x-shader/x-vertex">
        varying vec2 vUv;
        void main() {
            vUv = uv;
            gl_Position = projectionMatrix * modelViewMatrix * vec4(position, 1.0);
        }
    </script>

    <script id="f-shader" type="x-shader/x-fragment">
        uniform float time;
        uniform vec2 resolution;
        uniform vec2 pointer;

        varying vec2 vUv;

        vec3 mod289(vec3 x) { return x - floor(x * (1.0 / 289.0)) * 289.0; }
        vec2 mod289(vec2 x) { return x - floor(x * (1.0 / 289.0)) * 289.0; }
        vec3 permute(vec3 x) { return mod289(((x*34.0)+1.0)*x); }
        float noise(vec2 v) {
            const vec4 C = vec4(0.211324865405187, 0.366025403784439, -0.577350269189626, 0.024390243902439);
            vec2 i  = floor(v + dot(v, C.yy) );
            vec2 x0 = v - i + dot(i, C.xx);
            vec2 i1;
            i1 = (x0.x > x0.y) ? vec2(1.0, 0.0) : vec2(0.0, 1.0);
            vec4 x12 = x0.xyxy + C.xxzz;
            x12.xy -= i1;
            i = mod289(i);
            vec3 p = permute( permute( i.y + vec3(0.0, i1.y, 1.0 )) + i.x + vec3(0.0, i1.x, 1.0 ));
            vec3 m = max(0.5 - vec3(dot(x0,x0), dot(x12.xy,x12.xy), dot(x12.zw,x12.zw)), 0.0);
            m = m*m ;
            m = m*m ;
            vec3 x = 2.0 * fract(p * C.www) - 1.0;
            vec3 h = abs(x) - 0.5;
            vec3 ox = floor(x + 0.5);
            vec3 a0 = x - ox;
            m *= 1.79284291400159 - 0.85373472095314 * ( a0*a0 + h*h );
            vec3 g;
            g.x  = a0.x  * x0.x  + h.x  * x0.y;
            g.yz = a0.yz * x12.xz + h.yz * x12.yw;
            return 130.0 * dot(m, g);
        }

        void main() {
            vec2 st = gl_FragCoord.xy / resolution.xy;
            st.x *= resolution.x / resolution.y;

            float t = time * 0.15;
            
            float dist = distance(st, pointer);
            float influence = smoothstep(0.5, 0.0, dist) * 0.4;

            vec2 q = vec2(0.);
            q.x = noise(st + vec2(0.0, t));
            q.y = noise(st + vec2(1.0, t));

            vec2 r = vec2(0.);
            r.x = noise(st + 1.0 * q + vec2(1.7, 9.2) + 0.15 * t + influence);
            r.y = noise(st + 1.0 * q + vec2(8.3, 2.8) + 0.126 * t);

            float f = noise(st + r);

            vec3 color = mix(vec3(0.08, 0.08, 0.08), vec3(0.02, 0.02, 0.05), clamp((f*f)*4.0,0.0,1.0));
            color = mix(color, vec3(0.0, 0.8, 0.9), clamp(length(q), 0.0, 1.0) * 0.15);
            color = mix(color, vec3(0.9, 0.0, 0.4), clamp(length(r.x), 0.0, 1.0) * 0.2);

            color = pow(color, vec3(1.1));

            gl_FragColor = vec4(color, 1.0);
        }
    </script>

    <script>
        // Wrap script in an IIFE to avoid global scope pollution
        (function() {
            lucide.createIcons();

            setInterval(() => {
                const n = new Date();
                document.getElementById('clock').innerText = n.toLocaleTimeString([], {hour: '2-digit', minute:'2-digit', second:'2-digit'});
            }, 1000);

            const pointer = document.getElementById('pointer');
            let mX = 0, mY = 0;
            let cX = 0, cY = 0;

            window.addEventListener('mousemove', (e) => {
                mX = e.clientX;
                mY = e.clientY;
            });

            function loop() {
                cX += (mX - cX) * 0.12;
                cY += (mY - cY) * 0.12;
                pointer.style.left = `${cX}px`;
                pointer.style.top = `${cY}px`;
                requestAnimationFrame(loop);
            }
            loop();

            const interactables = document.querySelectorAll('a, .card, .pointer-events-auto');
            interactables.forEach(el => {
                el.addEventListener('mouseenter', () => pointer.classList.add('active'));
                el.addEventListener('mouseleave', () => pointer.classList.remove('active'));
            });

            const canvasDiv = document.getElementById('canvas-wrap');
            const scene = new THREE.Scene();
            const cam = new THREE.OrthographicCamera(-1, 1, 1, -1, 0, 1);
            const rend = new THREE.WebGLRenderer({ alpha: true });
            
            rend.setSize(window.innerWidth, window.innerHeight);
            rend.setPixelRatio(Math.min(window.devicePixelRatio, 2));
            canvasDiv.appendChild(rend.domElement);

            const geo = new THREE.PlaneGeometry(2, 2);
            
            // Renamed 'u' to 'uniforms' to avoid identifier conflicts
            const uniforms = {
                time: { value: 0 },
                resolution: { value: new THREE.Vector2(window.innerWidth, window.innerHeight) },
                pointer: { value: new THREE.Vector2(0.5, 0.5) }
            };

            const mat = new THREE.ShaderMaterial({
                uniforms: uniforms,
                vertexShader: document.getElementById('v-shader').textContent,
                fragmentShader: document.getElementById('f-shader').textContent,
            });

            const mesh = new THREE.Mesh(geo, mat);
            scene.add(mesh);

            window.addEventListener('resize', () => {
                rend.setSize(window.innerWidth, window.innerHeight);
                uniforms.resolution.value.set(window.innerWidth, window.innerHeight);
            });

            window.addEventListener('mousemove', (e) => {
                uniforms.pointer.value.x = e.clientX / window.innerWidth;
                uniforms.pointer.value.y = 1.0 - (e.clientY / window.innerHeight);
            });

            const clock = new THREE.Clock();
            function render() {
                requestAnimationFrame(render);
                uniforms.time.value = clock.getElapsedTime();
                rend.render(scene, cam);
            }
            render();
        })();
    </script>
</body>
</html>
