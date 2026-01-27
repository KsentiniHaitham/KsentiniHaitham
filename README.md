<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio Développeur</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { 
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif; 
            background: #0a0a0a; color: #fff; padding: 40px; line-height: 1.6;
        }
        .container { max-width: 800px; margin: 0 auto; }
        .header { 
            display: flex; align-items: center; gap: 20px; margin-bottom: 40px; 
        }
        .avatar { width: 80px; height: 80px; border-radius: 50%; background: #333; }
        h1 { font-size: 2.5em; font-weight: 700; }
        .tag { background: #1a1a1a; padding: 8px 16px; border-radius: 20px; font-size: 0.9em; }
        .section { margin-bottom: 60px; }
        .section h2 { 
            font-size: 1.8em; margin-bottom: 20px; color: #fff; 
            border-left: 4px solid #007acc; padding-left: 20px;
        }
        .tech-stack { display: grid; grid-template-columns: repeat(auto-fit, minmax(100px, 1fr)); gap: 20px; }
        .tech-item { 
            text-align: center; padding: 20px; background: rgba(255,255,255,0.05); 
            border-radius: 12px; transition: transform 0.3s;
        }
        .tech-item:hover { transform: translateY(-5px); }
        .tech-logo { width: 60px; height: 60px; margin: 0 auto 10px; background: #444; border-radius: 12px; }
        .tech-name { font-size: 0.9em; font-weight: 500; }
        @media (max-width: 768px) { body { padding: 20px; } }
    </style>
</head>
<body>
    <div class="container">
        <!-- Header -->
        <div class="header">
            <div class="avatar"></div>
            <div>
                <h1>Florent Béra</h1>
                <span class="tag">Développeur Full Stack</span>
            </div>
        </div>

        <!-- About -->
        <div class="section">
            <h2>About</h2>
            <p>Build backend systems and SaaS platforms with Laravel, Livewire, and ship modern frontends with Next.js/React.</p>
            <ul style="margin-top: 20px; padding-left: 20px;">
                <li>Build UI, tools & workflows (PHP, SQL, multi-tenant).</li>
                <li>Interested in clean architecture, performance & DX.</li>
            </ul>
        </div>

        <!-- Tech Stack -->
        <div class="section">
            <h2>Tech Stack (👨‍💻)</h2>
            <div class="tech-stack">
                <div class="tech-item">
                    <div class="tech-logo"></div>
                    <span class="tech-name">Backend</span>
                </div>
                <div class="tech-item">
                    <div class="tech-logo"></div>
                    <span class="tech-name">Python</span>
                </div>
                <div class="tech-item">
                    <div class="tech-logo"></div>
                    <span class="tech-name">Laravel</span>
                </div>
                <div class="tech-item">
                    <div class="tech-logo"></div>
                    <span class="tech-name">Frontend</span>
                </div>
                <div class="tech-item">
                    <div class="tech-logo"></div>
                    <span class="tech-name">Next.js</span>
                </div>
                <div class="tech-item">
                    <div class="tech-logo"></div>
                    <span class="tech-name">React</span>
                </div>
                <div class="tech-item">
                    <div class="tech-logo"></div>
                    <span class="tech-name">Data & Infra</span>
                </div>
                <div class="tech-item">
                    <div class="tech-logo"></div>
                    <span class="tech-name">Docker</span>
                </div>
                <div class="tech-item">
                    <div class="tech-logo"></div>
                    <span class="tech-name">Kubernetes</span>
                </div>
            </div>
        </div>

        <!-- Automation & AI -->
        <div class="section">
            <h2>Automation & AI</h2>
            <div class="tech-stack">
                <div class="tech-item"><div class="tech-logo"></div><span>Automatisation</span></div>
                <div class="tech-item"><div class="tech-logo"></div><span>IA</span></div>
            </div>
        </div>
    </div>
</body>
</html>
