[Uploading index.html…]()
# apresentacao-gogroup<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GoGroup - Portal de Apresentações</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;600;700;800;900&display=swap" rel="stylesheet">
    <style>
        :root {
            /* Cores Exatas da Identidade GoGroup */
            --go-blue-primary: #1653A1;    
            --go-blue-dark: #0F3D78;       
            --go-orange: #FA6341;          
            --go-blue-light: #74C0E3;      
            --go-bg-light: #F4F7FA;        
            --surface-white: #FFFFFF;
            --text-dark: #1E293B;
            --text-muted: #64748B;
            --ph-bg: #EAF0F6;              
            --ph-border: #C8D9E8;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Montserrat', sans-serif;
        }

        body, html {
            width: 100vw;
            height: 100vh;
            overflow: hidden;
            background-color: var(--go-bg-light);
        }

        /* Padrão de Fundo Sutil (Dots) */
        body::before {
            content: '';
            position: fixed;
            top: 0; left: 0; width: 100vw; height: 100vh;
            background-image: radial-gradient(var(--go-blue-primary) 0.5px, transparent 0.5px);
            background-size: 24px 24px;
            opacity: 0.05;
            z-index: 0;
            pointer-events: none;
        }

        /* --- TELA INICIAL (HOME) --- */
        #home-screen {
            position: fixed;
            top: 0; left: 0;
            width: 100vw; height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            z-index: 2000;
            background: linear-gradient(135deg, var(--go-bg-light) 0%, #E2EAF1 100%);
            transition: opacity 0.6s ease, visibility 0.6s;
        }

        .home-card {
            background-color: var(--surface-white);
            padding: 60px 80px;
            border-radius: 32px;
            box-shadow: 0 20px 60px rgba(15, 61, 120, 0.08);
            text-align: center;
            max-width: 800px;
            width: 90%;
            position: relative;
            overflow: hidden;
            border-top: 6px solid var(--go-blue-primary);
        }

        .home-card::before {
            content: '';
            position: absolute;
            top: -6px; left: 0;
            width: 30%; height: 6px;
            background-color: var(--go-orange);
        }

        .home-logo {
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 16px;
            margin-bottom: 40px;
        }

        .logo-mark {
            width: 56px; height: 56px;
            background: linear-gradient(135deg, var(--go-blue-primary), var(--go-blue-light));
            border-radius: 12px;
            box-shadow: 0 8px 24px rgba(22, 83, 161, 0.3);
            position: relative;
            display: flex; justify-content: center; align-items: center;
            color: white; font-weight: 800; font-size: 24px;
        }
        
        .logo-mark::after {
            content: '';
            position: absolute; bottom: -4px; right: -4px;
            width: 16px; height: 16px; background-color: var(--go-orange);
            border-radius: 50%; border: 3px solid var(--surface-white);
        }

        .logo-text { color: var(--go-blue-primary); font-weight: 800; font-size: 28px; letter-spacing: -0.5px; }

        .home-title { font-size: 2rem; color: var(--go-blue-dark); font-weight: 800; margin-bottom: clamp(6px, 1.5vh, 12px); }
        .home-subtitle { font-size: 1.1rem; color: #64748B; margin-bottom: 48px; font-weight: 500; }

        .home-buttons {
            display: flex;
            gap: clamp(12px, 2vh, 24px);
            justify-content: center;
        }

        .btn-home {
            flex: 1;
            padding: 24px 32px;
            border-radius: 20px;
            border: none;
            cursor: pointer;
            font-size: clamp(1.2rem, 2.5vh, 1.4rem);
            font-weight: 700;
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 12px;
            transition: all 0.3s cubic-bezier(0.175, 0.885, 0.32, 1.275);
            text-decoration: none;
        }

        .btn-bc {
            background-color: var(--go-blue-primary);
            color: var(--surface-white);
            box-shadow: 0 12px 30px rgba(22, 83, 161, 0.2);
        }

        .btn-cs {
            background-color: var(--surface-white);
            color: var(--go-blue-primary);
            border: 2px solid var(--go-blue-primary);
            box-shadow: 0 12px 30px rgba(15, 61, 120, 0.05);
        }

        .btn-home:hover { transform: translateY(-8px); }
        .btn-bc:hover { background-color: var(--go-blue-dark); box-shadow: 0 16px 40px rgba(22, 83, 161, 0.3); }
        .btn-cs:hover { background-color: var(--go-bg-light); border-color: var(--go-blue-dark); color: var(--go-blue-dark); }

        /* --- AMBIENTE DE APRESENTAÇÃO --- */
        #presentation-ui {
            position: fixed;
            top: 0; left: 0;
            width: 100vw; height: 100vh;
            visibility: hidden;
            opacity: 0;
            transition: opacity 0.6s ease, visibility 0.6s;
            z-index: 1000;
        }

        .slider-track {
            width: 100vw;
            height: 100vh;
            transition: transform 0.9s cubic-bezier(0.77, 0, 0.175, 1);
            position: absolute;
            top: 0; left: 0;
            display: none; 
        }

        .slide {
            width: 100vw;
            height: 100vh;
            padding: 2vh 4vw;
            display: flex;
            flex-direction: column;
            position: relative;
        }

        /* --- ESTILOS GERAIS DA APRESENTAÇÃO --- */
        .header-brand { position: absolute; top: clamp(20px, 4vh, 40px); left: clamp(30px, 5vw, 60px); right: clamp(30px, 5vw, 60px); z-index: 10; display: flex; align-items: flex-end; gap: 8px; padding-bottom: 8px; border-bottom: 5px solid var(--go-blue-primary); }
        .header-brand .logo-mark { width: 42px; height: 42px; font-size: 20px; margin-bottom: -10px; border-radius: 12px; z-index: 2; }
        .header-brand .logo-mark::after { width: 16px; height: 16px; bottom: -4px; right: -4px; border-width: 3px; background-color: var(--go-orange); }
        .header-brand .logo-text { font-size: 26px; line-height: 1; margin-bottom: 2px; }

        .slide-content {
            flex: 1; background-color: var(--surface-white); border-radius: 24px;
            box-shadow: 0 20px 50px rgba(15, 61, 120, 0.08); padding: clamp(70px, 10vh, 90px) clamp(40px, 5vw, 60px) clamp(20px, 4vh, 40px);
            display: flex; flex-direction: column; gap: clamp(12px, 2vh, 24px); position: relative; overflow: hidden; margin-top: 0;
        }
        .slide-content::before {
            content: ''; position: absolute; top: 0; left: 0; width: 100%; height: 8px;
            display: none; /* Removido para usar a nova linha azul contínua da marca */
        }
        .decor-shape { position: absolute; bottom: -30px; right: -30px; width: 150px; height: 150px; background-color: rgba(250, 99, 65, 0.05); border-radius: 40% 60% 70% 30% / 40% 50% 60% 50%; z-index: 0; }

        
        /* Tipografia Padronizada */
        h1, h2, h3, h4, p { position: relative; z-index: 2; }
        .title-xl { font-size: clamp(3rem, 6vh, 4rem); font-weight: 900; line-height: 1.1; color: var(--surface-white); letter-spacing: -1px; }
        .title-xl span { color: var(--go-orange); }
        .title-lg { font-size: clamp(2rem, 4.5vh, 2.8rem); font-weight: 800; color: var(--go-blue-primary); letter-spacing: -0.5px; line-height: 1.2; }
        .subtitle { font-size: clamp(1.1rem, 2.5vh, 1.4rem); font-weight: 600; color: var(--text-muted); margin-top: 4px; }
        .text-body { font-size: clamp(0.95rem, 2vh, 1.15rem); line-height: 1.5; color: var(--text-dark); font-weight: 500; }
        .text-highlight { color: var(--go-blue-primary); font-weight: 700; }
        h3 { font-size: clamp(1.15rem, 2.5vh, 1.4rem); font-weight: 700; color: var(--go-blue-primary); margin-bottom: 8px; }
        h4 { font-size: clamp(1.05rem, 2.2vh, 1.25rem); font-weight: 700; color: var(--go-orange); margin-bottom: 6px; }

        /* Componentes */
        .card { 
            flex: 1; display: flex; flex-direction: column; gap: 16px; padding: clamp(12px, 2.5vh, 24px); 
            border-radius: 20px; background-color: var(--surface-white);
            border: 1px solid #E2E8F0; box-shadow: 0 8px 24px rgba(15, 61, 120, 0.04);
            border-top: 4px solid var(--go-blue-light); transition: transform 0.3s ease;
            position: relative; z-index: 2;
        }
        .card:hover { transform: translateY(-5px); box-shadow: 0 12px 32px rgba(15, 61, 120, 0.1); }
        .card:nth-child(2) { border-top-color: var(--go-orange); }
        .card:nth-child(3) { border-top-color: var(--go-blue-primary); }

        .card-icon { width: 48px; height: 48px; background-color: var(--go-bg-light); border-radius: 12px; display: flex; justify-content: center; align-items: center; color: var(--go-blue-primary); }
        .card:nth-child(2) .card-icon { color: var(--go-orange); }

        .image-box { flex: 1; width: 100%; border-radius: 20px; background-color: var(--ph-bg); border: 2px dashed var(--ph-border); display: flex; justify-content: center; align-items: center; color: var(--go-blue-light); font-weight: 600; font-size: clamp(1.2rem, 2.5vh, 1.4rem); position: relative; z-index: 2; }
        .chart-mockup { flex: 1.5; width: 100%; border-radius: 16px; background: linear-gradient(180deg, var(--surface-white) 0%, var(--go-bg-light) 100%); border: 1px dashed var(--ph-border); display: flex; flex-direction: column; justify-content: center; align-items: center; padding: 40px; position: relative; z-index: 2; color: var(--go-blue-light); font-weight: 600; }

        .author-tag { background: rgba(255,255,255,0.1); padding: 12px 24px; border-radius: 24px; color: white; font-weight: 600; border: 1px solid rgba(255,255,255,0.2); backdrop-filter: blur(10px); display: inline-flex; align-items: center; gap: 8px; }

        .layout-columns-2 { display: grid; grid-template-columns: 1fr 1fr; gap: clamp(16px, 2.5vw, 32px); flex: 1; }
        .layout-columns-3 { display: grid; grid-template-columns: repeat(3, 1fr); gap: clamp(16px, 2.5vw, 32px); flex: 1; align-items: stretch; }
        .layout-row-main { display: flex; flex-direction: column; flex: 1; gap: clamp(12px, 2vh, 24px); }

        /* Slide 01: CAPA PREMIUM */
        .slide-01 { padding: 4vh 4vw; }
        .slide-01 .slide-content { margin-top: 0; background: linear-gradient(135deg, var(--go-blue-primary) 0%, var(--go-blue-dark) 100%); border-radius: 32px; justify-content: center; align-items: flex-start; padding: clamp(40px, 8vh, 80px) clamp(40px, 8vw, 100px); }
        .slide-01 .slide-content::before { display: none; }
        .hero-shape { position: absolute; right: -10%; top: -10%; width: 60vh; height: 60vh; background-color: var(--go-orange); border-radius: 50%; opacity: 0.8; filter: blur(90px); z-index: 0; }
        .hero-shape-2 { position: absolute; left: 20%; bottom: -20%; width: 40vh; height: 40vh; background-color: var(--go-blue-light); border-radius: 50%; opacity: 0.3; filter: blur(70px); z-index: 0; }

        /* Controles de Navegação */
        .nav-controls {
            position: fixed; right: 2vw; top: 50%; transform: translateY(-50%);
            display: flex; flex-direction: column; align-items: center; gap: 16px;
            z-index: 2000; background: rgba(255,255,255,0.9); backdrop-filter: blur(12px);
            padding: 16px 8px; border-radius: 40px; box-shadow: 0 8px 32px rgba(15, 61, 120, 0.1); border: 1px solid rgba(255,255,255,0.5);
        }

        .nav-btn {
            background-color: transparent; border: none; color: var(--go-blue-primary);
            width: 44px; height: 44px; border-radius: 50%; display: flex; justify-content: center; align-items: center;
            cursor: pointer; transition: all 0.3s cubic-bezier(0.175, 0.885, 0.32, 1.275);
        }
        .nav-btn svg { width: 28px; height: 28px; transition: stroke-width 0.2s; }
        .nav-btn:hover:not(.disabled) { background-color: var(--go-orange); color: var(--surface-white); transform: scale(1.15); }
        .nav-btn.disabled { opacity: 0.2; cursor: not-allowed; color: #A0B4C8; }
        .nav-indicator { font-size: 13px; font-weight: 800; color: var(--go-blue-primary); letter-spacing: 2px; writing-mode: vertical-rl; text-orientation: mixed; transform: rotate(180deg); padding: 8px 0; }

        /* Botão de Voltar para Home */
        .btn-back-home {
            background-color: var(--go-bg-light); border: 1px solid var(--ph-border);
            color: var(--go-blue-dark); width: 44px; height: 44px; border-radius: 50%;
            display: flex; justify-content: center; align-items: center;
            cursor: pointer; transition: all 0.3s; margin-bottom: 8px;
        }
        .btn-back-home:hover { background-color: var(--go-blue-primary); color: white; transform: scale(1.1); }
        .btn-back-home svg { width: 20px; height: 20px; }

        /* Responsividade */
        @media (max-width: 1024px) {
            .slide-content { padding: 40px; }
            .layout-columns-3 { grid-template-columns: 1fr; gap: 20px; }
            .title-xl { font-size: 3rem; }
            .title-lg { font-size: 2.2rem; }
        }
        @media (max-width: 768px) {
            .home-buttons { flex-direction: column; }
            .layout-columns-2 { grid-template-columns: 1fr; }
            .slide { padding: 2vh 3vw; }
            .slide-content { padding: 30px 20px; margin-top: 60px; }
            .header-brand { top: 3vh; left: 4vw; }
            .nav-controls { top: auto; bottom: 2vh; right: 50%; transform: translateX(50%); flex-direction: row; padding: 8px 16px; border-radius: 20px; }
            .nav-indicator { writing-mode: horizontal-tb; transform: none; padding: 0 16px; }
            .slide-01 .slide-content { padding: 40px 30px; }
            .btn-back-home { margin-bottom: 0; margin-right: 8px; }
        }
    </style>
</head>
<body>

    <!-- TELA INICIAL -->
    <div id="home-screen">
        <div class="home-card">
            <div class="home-logo">
                <div class="logo-mark">go</div>
                <div class="logo-text">group</div>
            </div>
            <h1 class="home-title">Portal de Apresentações</h1>
            <p class="home-subtitle">Selecione o fluxo que deseja acessar:</p>
            
            <div class="home-buttons">
                <button class="btn-home btn-bc" onclick="startPresentation('bc')">
                    <svg width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M22 19a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h5l2 3h9a2 2 0 0 1 2 2z"/></svg>
                    Business Case
                </button>
                <button class="btn-home btn-cs" onclick="startPresentation('cs')">
                    <svg width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M17 21v-2a4 4 0 0 0-4-4H5a4 4 0 0 0-4 4v2"></path><circle cx="9" cy="7" r="4"></circle><path d="M23 21v-2a4 4 0 0 0-3-3.87"></path><path d="M16 3.13a4 4 0 0 1 0 7.75"></path></svg>
                    Case Supervisor
                </button>
            </div>
        </div>
    </div>

    <!-- AMBIENTE DA APRESENTAÇÃO -->
    <div id="presentation-ui">
        <div class="nav-controls">
            <button class="btn-back-home" onclick="goHome()" aria-label="Voltar para a Home">
                <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M3 9l9-7 9 7v11a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2z"/><polyline points="9 22 9 12 15 12 15 22"/></svg>
            </button>
            <button id="btn-up" class="nav-btn disabled" aria-label="Slide anterior">
                <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><path d="M18 15l-6-6-6 6"/></svg>
            </button>
            <div class="nav-indicator" id="indicator">01 / 07</div>
            <button id="btn-down" class="nav-btn" aria-label="Próximo slide">
                <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><path d="M6 9l6 6 6-6"/></svg>
            </button>
        </div>

        <!-- TRILHA 1: BUSINESS CASE -->
        <div id="track-bc" class="slider-track">
            <!-- Slide 01: Capa -->
            <section class="slide slide-01">
                <div class="slide-content">
                    <div class="hero-shape"></div>
                    <div class="hero-shape-2"></div>
                    
                    <div style="display: flex; align-items: center; gap: 16px; margin-bottom: 60px; z-index: 2;">
                        <div class="logo-mark" style="width: 56px; height: 56px; background: white; color: var(--go-blue-primary); font-size: 24px;">go</div>
                        <div class="logo-text" style="color: white; font-size: 24px;">group</div>
                    </div>

                    <h1 class="title-xl">Matriz de Talentos<br>Nível A<br><span>Triagem com IA</span></h1>
                    <p class="subtitle" style="color: var(--go-blue-light); margin-top: clamp(12px, 2vh, 24px); ">Estruturação de Dados para o GoGroup</p>
                    
                    <div style="margin-top: auto; z-index: 2; display: flex; gap: 16px;">
                        <div class="author-tag">
                            <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2"></path><circle cx="12" cy="7" r="4"></circle></svg>
                            Luana Lacerda
                        </div>
                    </div>
                </div>
            </section>
            
            <!-- Slide 02: Introdução -->
            <section class="slide">
                <div class="slide-content">
                    <div class="header-brand"><div class="logo-mark">go</div><div class="logo-text">group</div></div>
                    <div class="decor-shape"></div>
                    <h2 class="title-lg">A Engenharia da Triagem</h2>
                    <p class="subtitle">O fim do achismo. O início da execução.</p>
                    
                    <div class="layout-row-main" style="margin-top: clamp(12px, 2vh, 24px); width: 100%;">
                        <p class="text-body">Com esta tese sólida e hierarquizada, temos o material perfeito para programar a Inteligência Artificial. O objetivo é ler milhares de currículos e perfis, ignorando o ruído tradicional do mercado e focando no que realmente importa.</p>
                        <p class="text-body">Para estruturar o comando da IA, dividimos nossos 12 critérios em 3 níveis de ponderação: Fundamentais (Inegociáveis), Diferenciais (Desempate) e Superestimados (Vaidade).</p>
                    </div>
                </div>
            </section>
            
            <!-- Slide 03: Texto e Imagem -->
            <section class="slide">
                <div class="slide-content">
                    <div class="header-brand"><div class="logo-mark">go</div><div class="logo-text">group</div></div>
                    <div class="decor-shape"></div>
                    <h2 class="title-lg">1. Os Fundamentais (|)</h2>
                    <p class="subtitle">Peso Máximo: Os Inegociáveis</p>
                    
                    <div class="layout-columns-2" style="margin-top: clamp(12px, 2vh, 24px);">
                        <div class="layout-row-main">
                            <div style="background: var(--go-bg-light); padding: clamp(12px, 2.5vh, 24px); border-radius: 16px; border-left: 4px solid var(--go-blue-primary);">
                                <h3 class="text-highlight" style="margin-bottom: clamp(6px, 1.5vh, 12px);">Resiliência e Resultados</h3>
                                <p class="text-body"><b>Sobrevivência em ambientes de alta cobrança:</b> Prova de resiliência e adequação ao ritmo intenso. <br><br><b>Currículo orientado a resultados:</b> Foco em métricas e entregas reais, não apenas em descrição de tarefas.</p>
                            </div>
                            <div style="background: var(--go-bg-light); padding: clamp(12px, 2.5vh, 24px); border-radius: 16px; border-left: 4px solid var(--go-orange);">
                                <h3 class="text-highlight" style="margin-bottom: clamp(6px, 1.5vh, 12px); color: var(--go-orange);">Evolução e Comunicação</h3>
                                <p class="text-body"><b>Formação contínua:</b> Evidência de que o candidato não parou no tempo. <br><br><b>Comunicação clara e direta:</b> Objetividade no currículo, sem jargões desnecessários.</p>
                            </div>
                        </div>
                        <div class="image-box"><div style="width:100%; height:100%; background:url('https://images.unsplash.com/photo-1552664730-d307ca884978?q=80&w=800&auto=format&fit=crop') center/cover; border-radius: 20px;"></div></div>
                    </div>
                </div>
            </section>
            
            <!-- Slide 04: Cards -->
            <section class="slide">
                <div class="header-brand"><div class="logo-mark">go</div><div class="logo-text">group</div></div>
                <div class="slide-content" style="background-color: transparent; box-shadow: none; padding: 0;">
                    <div style="background-color: var(--surface-white); padding: 40px 60px; border-radius: 24px; box-shadow: 0 10px 30px rgba(15,61,120,0.05);">
                        <h2 class="title-lg">Hierarquia da Matriz</h2>
                        <p class="subtitle">Como a Inteligência Artificial pondera e filtra os candidatos</p>
                    </div>
                    <div class="layout-columns-3" style="margin-top: clamp(12px, 2vh, 24px);">
                        <div class="card">
                            <div class="card-icon"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M13 2L3 14h9l-1 8 10-12h-9l1-8z"/></svg></div>
                            <h3 style="color: var(--text-dark);">Fundamentais (|)</h3>
                            <p class="text-body" style="border-top: 1px solid #E2E8F0; padding-top: 12px;"><b>Os Inegociáveis (Peso Máximo).</b> Se o candidato não demonstrar esses pontos, ele é automaticamente desqualificado na triagem inicial.</p>
                        </div>
                        <div class="card">
                            <div class="card-icon"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="3" width="18" height="18" rx="2" ry="2"></rect></svg></div>
                            <h3 style="color: var(--text-dark);">Diferenciais (||)</h3>
                            <p class="text-body" style="border-top: 1px solid #E2E8F0; padding-top: 12px;"><b>Fator de Desempate (Peso Médio).</b> Indicam alto potencial e ajudam a separar os bons candidatos dos verdadeiros talentos excelentes.</p>
                        </div>
                        <div class="card">
                            <div class="card-icon"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M17 21v-2a4 4 0 0 0-4-4H5a4 4 0 0 0-4 4v2"></path><circle cx="9" cy="7" r="4"></circle></svg></div>
                            <h3 style="color: var(--text-dark);">Superestimados (///)</h3>
                            <p class="text-body" style="border-top: 1px solid #E2E8F0; padding-top: 12px;"><b>Ruído ou Vaidade (Peso Mínimo/Zero).</b> Itens que o mercado tradicional valoriza, mas que no método GoGroup não garantem entrega.</p>
                        </div>
                    </div>
                </div>
            </section>
            
            <!-- Slide 05: Gráficos/Processos -->
            <section class="slide">
                <div class="slide-content">
                    <div class="header-brand"><div class="logo-mark">go</div><div class="logo-text">group</div></div>
                    <div class="decor-shape"></div>
                    <h2 class="title-lg">2. Os Diferenciais (||)</h2>
                    
                    <div class="layout-row-main" style="margin-top: clamp(12px, 2vh, 24px); flex-direction: row; align-items: stretch;">
                        <div class="chart-mockup"><div style="text-align:left; width: 100%;">
<h3 style="color:var(--go-blue-primary); margin-bottom:16px;">O Fator de Desempate</h3>
<div style="background:var(--go-blue-primary); color:white; padding:16px 24px; border-radius:8px; margin-bottom:12px; font-weight:700;">Progressão acelerada de carreira</div>
<div style="background:var(--go-blue-light); color:white; padding:16px 24px; border-radius:8px; margin-bottom:12px; font-weight:700;">Destaques extracurriculares</div>
<div style="background:var(--go-orange); color:white; padding:16px 24px; border-radius:8px; margin-bottom:12px; font-weight:700;">Histórico de intraempreendedorismo</div>
<div style="background:var(--go-blue-dark); color:white; padding:16px 24px; border-radius:8px; font-weight:700;">Foco no usuário/cliente</div>
</div></div>
                        <div class="layout-row-main" style="flex: 1; justify-content: center;">
                            <div style="background: var(--surface-white); padding: clamp(12px, 2.5vh, 24px); border-radius: 16px; border: 1px solid #E2E8F0;">
                                <h4 style="color: var(--go-blue-primary); margin-bottom: 8px;">Velocidade & Senso de Dono</h4>
                                <p class="text-body" style="">Promoções rápidas indicam destaque e adaptação. O histórico de intraempreendedorismo prova a capacidade de criar coisas do zero.</p>
                            </div>
                            <div style="background: var(--surface-white); padding: clamp(12px, 2.5vh, 24px); border-radius: 16px; border: 1px solid #E2E8F0;">
                                <h4 style="color: var(--go-orange); margin-bottom: 8px;">Energia & Foco</h4>
                                <p class="text-body" style="">Destaques acadêmicos demonstram energia e curiosidade além do básico, e a orientação genuína para o usuário consolida o Amor pelo Cliente.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
            
            <!-- Slide 06: Imagem e Texto (Invertido) -->
            <section class="slide">
                <div class="slide-content">
                    <div class="header-brand"><div class="logo-mark">go</div><div class="logo-text">group</div></div>
                    <div class="decor-shape"></div>
                    <div class="layout-columns-2">
                        <div class="image-box"><div style="width:100%; height:100%; background:url('https://images.unsplash.com/photo-1573164713988-8665fc963095?q=80&w=800&auto=format&fit=crop') center/cover; border-radius: 20px;"></div></div>
                        <div class="layout-row-main" style="justify-content: center;">
                            <h2 class="title-lg">3. Os Superestimados (///)</h2>
                            <p class="subtitle">Ruído ou Vaidade (Peso Zero)</p>
                            <p class="text-body" style="margin-top: clamp(12px, 2vh, 24px);">A IA é instruída a desconsiderar ou dar peso mínimo para itens que o mercado valoriza, mas que não garantem execução no nosso ambiente:<br><br>• <b>Reconhecimentos:</b> Geralmente métricas de vaidade.<br>• <b>Instituições de excelência:</b> Não garantem o 'Pulo do Gato'.<br>• <b>Longevidade com propósito:</b> Tempo de casa não atesta alta performance.<br>• <b>Referências:</b> No LinkedIn, são facilmente manipuláveis.</p>
                        </div>
                    </div>
                </div>
            </section>
            
            <!-- Slide 07: Fechamento (Impacto) -->
            <section class="slide">
                <div class="slide-content" style="background: linear-gradient(135deg, var(--go-bg-light) 0%, #E2EAF1 100%); justify-content: center; align-items: center; text-align: center;">
                    <div class="logo-mark" style="width: 80px; height: 80px; font-size: 32px; margin-bottom: 24px;">go</div>
                    
                    <h2 class="title-xl" style="color: var(--go-blue-primary);">Tese Concluída.</h2>
                    <p class="subtitle" style="margin-top: 16px; ">A base perfeita para o prompt de triagem IA.</p>
                    
                    <div style="margin-top: 48px; display: flex; gap: clamp(12px, 2vh, 24px);">
                        <button style="background: var(--go-blue-primary); color: white; border: none; padding: 16px 40px; border-radius: 30px; font-size: 1.1rem; font-weight: 700; cursor: pointer; box-shadow: 0 10px 20px rgba(22, 83, 161, 0.2);">Luana Lacerda</button>
                        <button style="background: transparent; color: var(--go-blue-primary); border: 2px solid var(--go-blue-primary); padding: 16px 40px; border-radius: 30px; font-size: 1.1rem; font-weight: 700; cursor: pointer;">Executar Triagem</button>
                    </div>
                </div>
            </section>
        </div>

                <!-- TRILHA 2: CASE SUPERVISOR -->
        <div id="track-cs" class="slider-track">
            <!-- Slide 01: Capa -->
            <section class="slide slide-01">
                <div class="slide-content">
                    <div class="hero-shape"></div>
                    <div class="hero-shape-2"></div>
                    
                    <div style="display: flex; align-items: center; gap: 16px; margin-bottom: 60px; z-index: 2;">
                        <div class="logo-mark" style="width: 56px; height: 56px; background: white; color: var(--go-blue-primary); font-size: 24px;">go</div>
                        <div class="logo-text" style="color: white; font-size: 24px;">group</div>
                    </div>

                    <h1 class="title-xl">CASE – Supervisor de<br><span>Operações</span></h1>
                    <p class="subtitle" style="color: var(--go-blue-light); margin-top: clamp(12px, 2vh, 24px); ">Estruturação de Outbound</p>
                    
                    <div style="margin-top: auto; z-index: 2; display: flex; gap: 16px;">
                        <div class="author-tag">
                            <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2"></path><circle cx="12" cy="7" r="4"></circle></svg>
                            Luana Lacerda
                        </div>
                    </div>
                </div>
            </section>
            
            <!-- Slide 02: Introdução -->
            <section class="slide">
                <div class="slide-content">
                    <div class="header-brand"><div class="logo-mark">go</div><div class="logo-text">group</div></div>
                    <div class="decor-shape"></div>
                    <h2 class="title-lg">Etapa 1: Estruturação do Outbound Interno</h2>
                    <p class="subtitle">A Lógica de Service Desk</p>
                    
                    <div class="layout-columns-2" style="margin-top: clamp(12px, 2vh, 24px); width: 100%; align-items: stretch;">
                        <div style="background: var(--go-bg-light); padding: clamp(12px, 2.5vh, 24px); border-radius: 16px; border-left: 4px solid var(--go-orange);">
                            <h4 style="color: var(--go-orange); margin-bottom: 8px; ">O Diagnóstico</h4>
                            <p class="text-body" style="margin-bottom: 8px; "><b>Contexto da empresa:</b> Crescimento acelerado com a aquisição de 7 marcas de beleza em 2 anos, além da expectativa estratégica de integrar novas marcas a curto prazo.</p>
                            <p class="text-body" style="margin-bottom: 8px; "><b>A Raiz da Ineficiência:</b> A entrada constante de marcas com diferentes maturidades e volumes, sem padronização prévia, gera alta complexidade, ruídos de comunicação e perda de eficiência no operador logístico.</p>
                            <p class="text-body" style=""><b>O Gargalo Estrutural:</b> A equipe atual atua dividida por canal de venda (B2B e B2C). Isso provoca retrabalho e conflitos de priorização, impedindo a escalabilidade exigida para absorver novas aquisições sem aumento de headcount.</p>
                        </div>
                        <div style="background: var(--surface-white); padding: clamp(12px, 2.5vh, 24px); border-radius: 16px; border: 1px solid #E2E8F0;">
                            <h4 style="color: var(--go-blue-primary); margin-bottom: 8px; ">A Solução: Nível 1 & Nível 2</h4>
                            <p class="text-body" style="margin-bottom: clamp(4px, 1vh, 8px);">Quebrar a divisão por canal e reestruturar a equipe por especialidade de fluxo, sem aumentar o headcount:</p>
                            <p class="text-body"><b>Nível 1 (Front-office):</b> Uma dupla atua como o único ponto de contato para as 7 marcas. Recebem as previsões de demanda, triam as urgências e definem a priorização (a fila de chamados).</p>
                            <p class="text-body" style="margin-top: 8px;"><b>Nível 2 (Back-office):</b> A outra dupla foca 100% na operação e cobrança do operador logístico, tratando anomalias sistêmicas e destravando pedidos parados.</p>
                        </div>
                    </div>
                </div>
            </section>
            
            <!-- Slide 03: Texto e Imagem -->
            <section class="slide">
                <div class="slide-content">
                    <div class="header-brand"><div class="logo-mark">go</div><div class="logo-text">group</div></div>
                    <div class="decor-shape"></div>
                    <h2 class="title-lg">2. Operador Logístico</h2>
                    <p class="subtitle">Previsibilidade e Foco na Execução</p>
                    
                    <div class="layout-columns-2" style="margin-top: clamp(12px, 2vh, 24px);">
                        <div class="layout-row-main" style="justify-content: center;">
                            <p class="text-body" style="font-weight: 700; color: var(--go-blue-primary);">O Novo Escopo de Atuação</p>
                            <p class="text-body">O operador logístico deixa de receber demandas picadas, informais e urgentes de várias marcas diferentes. Ele passa a receber uma única fila de expedição <b>já priorizada e validada</b> pelo seu Nível 1 interno.</p>
                            
                            <p class="text-body" style="font-weight: 700; color: var(--go-blue-primary); margin-top: 16px;">SLA e Responsabilidade</p>
                            <p class="text-body">O foco do parceiro passa a ser puramente a execução. Estabeleceremos regras inegociáveis de <i>Time-to-Ship</i>. A cadência operacional deve ser padronizada: a esteira precisa rodar na mesma velocidade e regra, independentemente de qual das 7 marcas seja o pedido.</p>
                        </div>
                        <div class="image-box"><div style="width:100%; height:100%; background:url('https://images.unsplash.com/photo-1586528116311-ad8ed7c83a7f?q=80&w=800&auto=format&fit=crop') center/cover; border-radius: 20px;"></div></div>
                    </div>
                </div>
            </section>
            
            <!-- Slide 04: Cards -->
            <section class="slide">
                <div class="slide-content" style="background-color: transparent; box-shadow: none; padding: 0;">
                    <div class="header-brand"><div class="logo-mark">go</div><div class="logo-text">group</div></div>
                    <div style="background-color: var(--surface-white); padding: clamp(24px, 4vh, 50px) clamp(30px, 5vw, 60px); border-radius: 24px; box-shadow: 0 10px 30px rgba(15,61,120,0.05); margin-top: clamp(30px, 6vh, 60px);">
                        <h2 class="title-lg">3. Governança e Rituais</h2>
                        <p class="subtitle">A Matriz de Alinhamento Integrado (Torre de Controle)</p>
                    </div>
                    <div class="layout-columns-2" style="margin-top: clamp(12px, 2vh, 24px);">
                        <div class="card">
                            <div class="card-icon"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M17 21v-2a4 4 0 0 0-4-4H5a4 4 0 0 0-4 4v2"></path><circle cx="9" cy="7" r="4"></circle></svg></div>
                            <h3 style="color: var(--go-blue-primary);">Marcas (Front-office)</h3>
                            <div style="border-top: 1px solid #E2E8F0; padding-top: 12px; margin-top: 8px;">
                                <p class="text-body" style=""><b>Fórum Mensal (S&OP):</b> Reunião com líderes para mapear calendário de campanhas e prever os picos mensais.</p>
                                <p class="text-body" style="margin-top: 12px;"><b>Weekly de Alinhamento:</b> Ajustar prioridades da semana e dar transparência sobre os resultados logísticos.</p>
                            </div>
                        </div>
                        <div class="card">
                            <div class="card-icon"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="3" width="18" height="18" rx="2" ry="2"></rect></svg></div>
                            <h3 style="color: var(--go-orange);">Operador (Back-office)</h3>
                            <div style="border-top: 1px solid #E2E8F0; padding-top: 12px; margin-top: 8px;">
                                <p class="text-body" style=""><b>Daily Operacional (15 min):</b> Alinhamento tático com a liderança para metas de picking do dia e resolução sistêmica.</p>
                                <p class="text-body" style="margin-top: 12px;"><b>Weekly de SLA:</b> Fórum de auditoria para analisar quebras de prazo e cobrar planos de ação crônicos.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
            
            <!-- Slide 05: Gráficos/Processos -->
            <section class="slide">
                <div class="slide-content">
                    <div class="header-brand"><div class="logo-mark">go</div><div class="logo-text">group</div></div>
                    <div class="decor-shape"></div>
                    <h2 class="title-lg">4. Indicadores e Dados Base</h2>
                    
                    <div class="layout-row-main" style="margin-top: clamp(12px, 2vh, 24px); flex-direction: row; align-items: stretch;">
                        <div class="chart-mockup" style="padding: 24px;">
                            <h3 style="color:var(--go-blue-primary); margin-bottom:16px;">Raio-X da Base Histórica</h3>
                            <div style="display:flex; gap:16px; margin-bottom:16px; width: 100%;">
                                <div style="flex:1; background:var(--go-bg-light); border:1px solid var(--go-blue-light); border-radius:12px; padding:20px; text-align:center;">
                                    <span style="display:block; font-size:2.4rem; font-weight:800; color:var(--go-blue-dark);">1.000</span>
                                    <span style="font-size:0.9rem; color:var(--text-muted); font-weight: 700;">Pedidos/mês (Teto)</span>
                                </div>
                                <div style="flex:1; background:rgba(250, 99, 65, 0.1); border:1px solid var(--go-orange); border-radius:12px; padding:20px; text-align:center;">
                                    <span style="display:block; font-size:2.4rem; font-weight:800; color:var(--go-orange);">39%</span>
                                    <span style="font-size:0.9rem; color:var(--text-muted); font-weight: 700;">Fora do SLA</span>
                                </div>
                            </div>
                            <div style="background:var(--go-blue-primary); color:white; width: 100%; border-radius:12px; padding:20px; text-align:center;">
                                <span style="display:block; font-size:2.4rem; font-weight:800;">4.012</span>
                                <span style="font-size:1rem; opacity:0.9;">Travados em "Em Separação"</span>
                            </div>
                        </div>
                        <div class="layout-row-main" style="flex: 1; justify-content: center;">
                            <div style="background: var(--surface-white); padding: clamp(12px, 2.5vh, 24px); border-radius: 16px; border: 1px solid #E2E8F0;">
                                <h4 style="color: var(--go-orange); margin-bottom: 8px; ">A Realidade</h4>
                                <p class="text-body" style="">O teto cravado de 1.000 pedidos/mês indica que o operador não acompanha a sazonalidade. O funil trava na base, gerando alto volume de atrasos (39%).</p>
                            </div>
                            <div style="background: var(--surface-white); padding: clamp(12px, 2.5vh, 24px); border-radius: 16px; border: 1px solid #E2E8F0;">
                                <h4 style="color: var(--go-blue-primary); margin-bottom: 8px; ">A Inteligência do Painel</h4>
                                <p class="text-body" style="">O monitoramento não será passivo. O dashboard emitirá alertas visuais de <b>aging</b> para o Nível 2 atuar <i>antes</i> que o SLA estoure.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
            
            <!-- Slide 06: Imagem e Texto (Invertido) -->
            <section class="slide">
                <div class="slide-content">
                    <div class="header-brand"><div class="logo-mark">go</div><div class="logo-text">group</div></div>
                    <div class="decor-shape"></div>
                    <div class="layout-columns-2">
                        <div class="image-box"><div style="width:100%; height:100%; background:url('https://images.unsplash.com/photo-1556761175-5973dc0f32e7?q=80&w=800&auto=format&fit=crop') center/cover; border-radius: 20px;"></div></div>
                        <div class="layout-row-main" style="justify-content: center;">
                            <h2 class="title-lg">5. A Negociação</h2>
                            <p class="subtitle">Estratégia Ganha-Ganha</p>
                            <p class="text-body" style="margin-top: clamp(12px, 2vh, 24px);">Como a premissa é não aumentar custos, a negociação com o operador será pautada na troca de previsibilidade por produtividade.</p>
                            <p class="text-body" style="margin-top: 16px;"><b>O Argumento Comercial:</b> A nova estrutura blinda o operador do "caos" e da falta de padronização. Entregar uma fila centralizada reduzirá drasticamente o esforço deles.</p>
                            <p class="text-body" style="margin-top: 16px;">Esse ganho real de eficiência justifica a absorção dos volumes das <b>futuras aquisições</b> sem repasse na tabela de preços.</p>
                        </div>
                    </div>
                </div>
            </section>
            
            <!-- Slide 07: Fechamento (Impacto) -->
            <section class="slide">
                <div class="slide-content" style="background: linear-gradient(135deg, var(--go-bg-light) 0%, #E2EAF1 100%); justify-content: center; align-items: center; text-align: center; margin-top: 0; padding: clamp(40px, 8vh, 80px) clamp(40px, 8vw, 100px);">
                    <div class="logo-mark" style="width: 80px; height: 80px; font-size: 32px; margin-bottom: 24px;">go</div>
                    <h2 class="title-xl" style="color: var(--go-blue-primary);">6. Plano de 90 Dias</h2>
                    <p class="subtitle" style="margin-top: 8px; ">Roadmap de Estabilização e Escala</p>
                    
                    <div style="margin-top: 40px; display: flex; gap: clamp(12px, 2vw, 24px); text-align: left; width: 100%;">
                        <div style="flex: 1; background: var(--surface-white); padding: 24px; border-radius: 16px; border-top: 4px solid var(--go-orange); box-shadow: 0 10px 30px rgba(15, 61, 120, 0.05);">
                            <h4 style="color: var(--go-orange); margin-bottom: clamp(4px, 1vh, 8px); ">Mês 1</h4>
                            <p class="text-body" style=""><b>Arrumar a Casa:</b> Desfazer silos, implementar Níveis 1 e 2, e Kick-off nos rituais.</p>
                        </div>
                        <div style="flex: 1; background: var(--surface-white); padding: 24px; border-radius: 16px; border-top: 4px solid var(--go-blue-light); box-shadow: 0 10px 30px rgba(15, 61, 120, 0.05);">
                            <h4 style="color: var(--go-blue-light); margin-bottom: clamp(4px, 1vh, 8px); ">Mês 2</h4>
                            <p class="text-body" style=""><b>Destravar a Fila:</b> Automatizar painéis e foco tático na eliminação dos mais de 4.000 pedidos em backlog.</p>
                        </div>
                        <div style="flex: 1; background: var(--surface-white); padding: 24px; border-radius: 16px; border-top: 4px solid var(--go-blue-primary); box-shadow: 0 10px 30px rgba(15, 61, 120, 0.05);">
                            <h4 style="color: var(--go-blue-primary); margin-bottom: clamp(4px, 1vh, 8px); ">Mês 3</h4>
                            <p class="text-body" style=""><b>Escala:</b> Operação padronizada. Ambiente "Plug & Play" pronto para absorver novas marcas do grupo.</p>
                        </div>
                    </div>
                </div>
            </section>
        </div>
    </div>

    <script>
        const homeScreen = document.getElementById('home-screen');
        const presentationUI = document.getElementById('presentation-ui');
        const trackBC = document.getElementById('track-bc');
        const trackCS = document.getElementById('track-cs');
        
        const btnUp = document.getElementById('btn-up');
        const btnDown = document.getElementById('btn-down');
        const indicator = document.getElementById('indicator');
        
        let currentSlideIndex = 0;
        const totalSlides = 7;
        let isAnimating = false;
        const animationDuration = 900;
        let activeTrack = null;

        function startPresentation(type) {
            activeTrack = type === 'bc' ? trackBC : trackCS;
            currentSlideIndex = 0;

            trackBC.style.display = type === 'bc' ? 'block' : 'none';
            trackCS.style.display = type === 'cs' ? 'block' : 'none';

            activeTrack.style.transform = `translateY(0vh)`;

            homeScreen.style.opacity = '0';
            
            setTimeout(() => {
                homeScreen.style.visibility = 'hidden';
                presentationUI.style.visibility = 'visible';
                updatePresentationUI();
                
                setTimeout(() => {
                    presentationUI.style.opacity = '1';
                }, 50);
            }, 600);
        }

        function goHome() {
            presentationUI.style.opacity = '0';
            
            setTimeout(() => {
                presentationUI.style.visibility = 'hidden';
                homeScreen.style.visibility = 'visible';
                activeTrack = null;
                
                setTimeout(() => {
                    homeScreen.style.opacity = '1';
                }, 50);
            }, 600);
        }

        function updatePresentationUI() {
            if (!activeTrack) return;
            
            activeTrack.style.transform = `translateY(-${currentSlideIndex * 100}vh)`;
            indicator.textContent = `0${currentSlideIndex + 1} / 0${totalSlides}`;
            
            if (currentSlideIndex === 0) { btnUp.classList.add('disabled'); } 
            else { btnUp.classList.remove('disabled'); }

            if (currentSlideIndex === totalSlides - 1) { btnDown.classList.add('disabled'); } 
            else { btnDown.classList.remove('disabled'); }
        }

        function goToNextSlide() {
            if (!activeTrack || isAnimating) return;
            if (currentSlideIndex < totalSlides - 1) {
                currentSlideIndex++; 
                lockAnimation(); 
                updatePresentationUI();
            }
        }

        function goToPrevSlide() {
            if (!activeTrack || isAnimating) return;
            if (currentSlideIndex > 0) {
                currentSlideIndex--; 
                lockAnimation(); 
                updatePresentationUI();
            }
        }

        function lockAnimation() {
            isAnimating = true; 
            setTimeout(() => { isAnimating = false; }, animationDuration);
        }

        btnUp.addEventListener('click', goToPrevSlide);
        btnDown.addEventListener('click', goToNextSlide);

        window.addEventListener('wheel', (event) => {
            if (!activeTrack) return;
            if (Math.abs(event.deltaY) < 40) return; 
            if (event.deltaY > 0) { goToNextSlide(); } 
            else { goToPrevSlide(); }
        });

        window.addEventListener('keydown', (event) => {
            if (!activeTrack) return;
            if (event.key === 'ArrowDown' || event.key === 'PageDown') { event.preventDefault(); goToNextSlide(); } 
            else if (event.key === 'ArrowUp' || event.key === 'PageUp') { event.preventDefault(); goToPrevSlide(); }
            else if (event.key === 'Escape') { goHome(); }
        });
    </script>
</body>
</html>
