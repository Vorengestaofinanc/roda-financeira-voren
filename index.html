<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Diagnóstico Financeiro Empresarial - Voren</title>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/4.4.1/chart.umd.min.js"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@400;600;700&family=Montserrat:wght@300;400;600;700&display=swap');

        :root {
            --gold: #C9A84C;
            --gold-light: #E8C97A;
            --gold-dark: #A07830;
            --black: #0A0A0A;
            --black-mid: #141414;
            --black-card: #1A1A1A;
            --black-hover: #222222;
            --white: #F5F0E8;
            --white-dim: rgba(245,240,232,0.7);
        }

        * { margin: 0; padding: 0; box-sizing: border-box; }

        body {
            font-family: 'Montserrat', sans-serif;
            background: var(--black);
            min-height: 100vh;
            padding: 30px 20px;
            color: var(--white);
        }

        /* Gold particle background */
        body::before {
            content: '';
            position: fixed;
            inset: 0;
            background: 
                radial-gradient(ellipse at 20% 20%, rgba(201,168,76,0.06) 0%, transparent 50%),
                radial-gradient(ellipse at 80% 80%, rgba(201,168,76,0.04) 0%, transparent 50%);
            pointer-events: none;
            z-index: 0;
        }

        .container { max-width: 1400px; margin: 0 auto; position: relative; z-index: 1; }

        /* ── HEADER ── */
        .header {
            text-align: center;
            margin-bottom: 40px;
            animation: fadeDown 0.8s ease;
        }

        .logo-wrapper {
            display: inline-flex;
            flex-direction: column;
            align-items: center;
            gap: 6px;
            margin-bottom: 20px;
        }

        .logo-circle {
            width: 90px; height: 90px;
            border-radius: 50%;
            border: 2px solid var(--gold);
            background: radial-gradient(circle at center, #1a1a1a, #000);
            display: flex; align-items: center; justify-content: center;
            box-shadow: 0 0 30px rgba(201,168,76,0.3), inset 0 0 20px rgba(201,168,76,0.05);
        }

        .logo-v {
            font-family: 'Cormorant Garamond', serif;
            font-size: 2.8rem;
            font-weight: 700;
            background: linear-gradient(180deg, var(--gold-light) 0%, var(--gold) 50%, var(--gold-dark) 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            line-height: 1;
        }

        .logo-name {
            font-family: 'Cormorant Garamond', serif;
            font-size: 1.8rem;
            font-weight: 700;
            letter-spacing: 6px;
            background: linear-gradient(90deg, var(--gold-dark), var(--gold-light), var(--gold-dark));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .logo-sub {
            font-family: 'Montserrat', sans-serif;
            font-size: 0.65rem;
            letter-spacing: 4px;
            color: var(--white-dim);
            text-transform: uppercase;
        }

        .gold-divider {
            width: 200px; height: 1px;
            background: linear-gradient(90deg, transparent, var(--gold), transparent);
            margin: 12px auto;
        }

        .header h1 {
            font-family: 'Cormorant Garamond', serif;
            font-size: 2rem;
            font-weight: 600;
            color: var(--white);
            letter-spacing: 2px;
            margin-bottom: 6px;
        }

        .header p {
            font-size: 0.8rem;
            color: var(--white-dim);
            letter-spacing: 2px;
            text-transform: uppercase;
        }

        /* ── MAIN CARD ── */
        .main-card {
            background: var(--black-card);
            border: 1px solid rgba(201,168,76,0.2);
            border-radius: 16px;
            padding: 35px;
            box-shadow: 0 20px 60px rgba(0,0,0,0.6), inset 0 1px 0 rgba(201,168,76,0.1);
            animation: fadeUp 0.7s ease;
            margin-bottom: 30px;
        }

        /* ── CHART ── */
        .chart-section { text-align: center; margin-bottom: 35px; }

        .chart-wrapper {
            position: relative;
            height: 420px;
            max-width: 580px;
            margin: 0 auto;
        }


        /* ── CLIENT FORM ── */
        .client-form {
            display: grid;
            grid-template-columns: repeat(5, 1fr);
            gap: 12px;
            margin-bottom: 28px;
        }

        .client-form input {
            width: 100%;
            background: var(--black-mid);
            border: 1px solid rgba(201,168,76,0.25);
            border-radius: 10px;
            padding: 13px 14px;
            color: var(--white);
            font-family: 'Montserrat', sans-serif;
            font-size: 0.8rem;
            outline: none;
        }

        .client-form input::placeholder {
            color: rgba(245,240,232,0.45);
        }

        .client-form input:focus {
            border-color: var(--gold);
            box-shadow: 0 0 0 2px rgba(201,168,76,0.12);
        }



        .label-row {
            display: flex;
            align-items: center;
            justify-content: space-between;
            gap: 10px;
            margin-bottom: 10px;
        }

        .label-row label { margin-bottom: 0; }

        .help-wrap {
            position: relative;
            flex-shrink: 0;
            display: inline-flex;
        }

        .help-icon {
            width: 25px;
            height: 25px;
            border-radius: 50%;
            border: 2px solid var(--gold);
            color: var(--gold-light);
            background: transparent;
            display: inline-flex;
            align-items: center;
            justify-content: center;
            font-weight: 700;
            font-size: 0.85rem;
            cursor: help;
            line-height: 1;
            box-shadow: 0 0 10px rgba(201,168,76,0.18);
        }

        .help-tooltip {
            pointer-events: none;
            visibility: hidden;
            opacity: 0;
            position: absolute;
            right: -6px;
            bottom: 34px;
            width: 310px;
            background: rgba(10,10,10,0.98);
            border: 1px solid rgba(201,168,76,0.55);
            color: var(--white);
            border-radius: 10px;
            padding: 14px 16px;
            z-index: 50;
            box-shadow: 0 18px 40px rgba(0,0,0,0.6);
            transition: opacity 0.22s ease, visibility 0.22s ease;
            text-align: left;
        }

        .help-tooltip strong {
            display: block;
            color: var(--gold-light);
            font-size: 0.78rem;
            letter-spacing: 1.5px;
            text-transform: uppercase;
            margin-bottom: 8px;
        }

        .help-tooltip span {
            display: block;
            font-size: 0.78rem;
            line-height: 1.55;
            color: var(--white-dim);
            text-transform: none;
            letter-spacing: 0;
            font-weight: 400;
        }

        .help-tooltip::after {
            content: '';
            position: absolute;
            right: 12px;
            bottom: -8px;
            width: 14px;
            height: 14px;
            background: rgba(10,10,10,0.98);
            border-right: 1px solid rgba(201,168,76,0.55);
            border-bottom: 1px solid rgba(201,168,76,0.55);
            transform: rotate(45deg);
        }

        .help-wrap:hover .help-tooltip,
        .help-wrap:focus-within .help-tooltip,
        .help-wrap.open .help-tooltip {
            visibility: visible;
            opacity: 1;
        }

        /* ── CONTROLS ── */
        .section-title {
            font-family: 'Cormorant Garamond', serif;
            font-size: 1.5rem;
            color: var(--gold-light);
            text-align: center;
            letter-spacing: 2px;
            margin-bottom: 25px;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 12px;
        }

        .section-title::before,
        .section-title::after {
            content: '';
            flex: 1;
            height: 1px;
            background: linear-gradient(90deg, transparent, rgba(201,168,76,0.4));
        }
        .section-title::after { background: linear-gradient(90deg, rgba(201,168,76,0.4), transparent); }

        .controls-grid {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 14px;
        }

        .control-item {
            background: var(--black-mid);
            border: 1px solid rgba(201,168,76,0.15);
            border-radius: 10px;
            padding: 14px;
            transition: all 0.3s ease;
        }

        .control-item:hover {
            border-color: rgba(201,168,76,0.4);
            background: var(--black-hover);
            transform: translateY(-2px);
            box-shadow: 0 8px 25px rgba(201,168,76,0.1);
        }

        .control-item label {
            display: block;
            font-size: 0.75rem;
            font-weight: 600;
            color: var(--gold);
            letter-spacing: 1px;
            text-transform: uppercase;
            margin-bottom: 10px;
        }

        .slider-row {
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .slider {
            flex: 1;
            -webkit-appearance: none;
            height: 4px;
            border-radius: 4px;
            background: #333;
            outline: none;
        }

        .slider::-webkit-slider-thumb {
            -webkit-appearance: none;
            width: 16px; height: 16px;
            border-radius: 50%;
            background: linear-gradient(135deg, var(--gold-light), var(--gold));
            cursor: pointer;
            border: 2px solid var(--black);
            box-shadow: 0 0 8px rgba(201,168,76,0.5);
            transition: transform 0.2s;
        }

        .slider::-webkit-slider-thumb:hover { transform: scale(1.3); }

        .val-badge {
            background: linear-gradient(135deg, var(--gold-dark), var(--gold));
            color: var(--black);
            font-size: 0.75rem;
            font-weight: 700;
            padding: 3px 8px;
            border-radius: 12px;
            min-width: 28px;
            text-align: center;
        }

        .feedback-box {
            margin-top: 8px;
            font-size: 0.72rem;
            color: var(--white-dim);
            line-height: 1.5;
            border-left: 2px solid var(--gold);
            padding-left: 8px;
            display: none;
        }

        .feedback-box.show { display: block; animation: fadeIn 0.4s ease; }

        /* ── BUTTON ── */
        .btn-diagnose {
            display: block;
            margin: 30px auto 5px;
            padding: 16px 60px;
            background: linear-gradient(135deg, var(--gold-dark) 0%, var(--gold) 50%, var(--gold-light) 100%);
            color: var(--black);
            font-family: 'Montserrat', sans-serif;
            font-size: 0.9rem;
            font-weight: 700;
            letter-spacing: 3px;
            text-transform: uppercase;
            border: none;
            border-radius: 40px;
            cursor: pointer;
            transition: all 0.3s ease;
            box-shadow: 0 6px 25px rgba(201,168,76,0.3);
        }

        .btn-diagnose:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 35px rgba(201,168,76,0.5);
        }

        /* ── DIAGNOSIS CARD ── */
        .diag-card {
            background: var(--black-card);
            border: 1px solid rgba(201,168,76,0.2);
            border-radius: 16px;
            padding: 35px;
            box-shadow: 0 20px 60px rgba(0,0,0,0.6);
            animation: fadeUp 0.6s ease;
            display: none;
        }

        .diag-card h2 {
            font-family: 'Cormorant Garamond', serif;
            font-size: 1.8rem;
            color: var(--gold-light);
            letter-spacing: 2px;
            margin-bottom: 25px;
            text-align: center;
        }

        .diag-grid { display: grid; gap: 18px; }

        .diag-section {
            background: var(--black-mid);
            border: 1px solid rgba(201,168,76,0.1);
            border-radius: 10px;
            padding: 20px;
        }

        .diag-section h3 {
            font-size: 0.75rem;
            font-weight: 700;
            letter-spacing: 2px;
            text-transform: uppercase;
            color: var(--gold);
            margin-bottom: 15px;
        }

        .health-badge {
            display: inline-block;
            padding: 8px 20px;
            border-radius: 30px;
            font-size: 0.9rem;
            font-weight: 700;
            letter-spacing: 2px;
            margin-bottom: 15px;
            border: 1px solid currentColor;
        }

        .h-critical { color: #ff4444; background: rgba(255,68,68,0.1); }
        .h-bad      { color: #ff8800; background: rgba(255,136,0,0.1); }
        .h-regular  { color: #ffcc00; background: rgba(255,204,0,0.1); }
        .h-good     { color: #44dd88; background: rgba(68,221,136,0.1); }
        .h-excellent{ color: var(--gold-light); background: rgba(201,168,76,0.1); }

        .metric-row {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 10px 12px;
            margin: 6px 0;
            background: rgba(255,255,255,0.02);
            border-radius: 8px;
            border: 1px solid rgba(201,168,76,0.06);
            transition: all 0.2s;
        }

        .metric-row:hover {
            border-color: rgba(201,168,76,0.2);
            background: rgba(201,168,76,0.04);
        }

        .metric-name { font-size: 0.82rem; color: var(--white-dim); font-weight: 500; }

        .metric-score {
            font-size: 0.78rem;
            font-weight: 700;
            padding: 3px 10px;
            border-radius: 12px;
        }

        .rec-section {
            background: linear-gradient(135deg, rgba(201,168,76,0.08) 0%, rgba(160,120,48,0.05) 100%);
            border: 1px solid rgba(201,168,76,0.25);
            border-radius: 10px;
            padding: 20px;
        }

        .rec-section h4 {
            font-size: 0.75rem;
            letter-spacing: 2px;
            text-transform: uppercase;
            color: var(--gold);
            margin-bottom: 14px;
        }

        .rec-section ul { list-style: none; }

        .rec-section li {
            padding: 10px 12px;
            margin: 6px 0;
            background: rgba(0,0,0,0.3);
            border-left: 3px solid var(--gold);
            border-radius: 0 8px 8px 0;
            font-size: 0.82rem;
            color: var(--white-dim);
            line-height: 1.5;
            transition: all 0.2s;
        }

        .rec-section li:hover {
            background: rgba(201,168,76,0.06);
            color: var(--white);
        }

        .cta-section {
            background: linear-gradient(135deg, #0f0f0f 0%, #1a1505 100%);
            border: 1px solid rgba(201,168,76,0.3);
            border-radius: 10px;
            padding: 25px;
            text-align: center;
        }

        .cta-section h3 {
            font-family: 'Cormorant Garamond', serif;
            font-size: 1.4rem;
            color: var(--gold-light);
            letter-spacing: 2px;
            margin-bottom: 15px;
        }

        .cta-section ul {
            list-style: none;
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 8px;
            margin: 15px 0 20px;
            text-align: left;
        }

        .cta-section li {
            font-size: 0.8rem;
            color: var(--white-dim);
            padding: 8px 10px;
            background: rgba(201,168,76,0.05);
            border-radius: 6px;
        }

        .cta-section p {
            font-size: 0.82rem;
            color: var(--gold);
            font-weight: 600;
            letter-spacing: 1px;
        }

        /* ── FOOTER ── */
        .footer {
            text-align: center;
            margin-top: 20px;
            padding: 15px;
        }

        .footer-logo {
            font-family: 'Cormorant Garamond', serif;
            font-size: 1.1rem;
            letter-spacing: 4px;
            background: linear-gradient(90deg, var(--gold-dark), var(--gold-light), var(--gold-dark));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .footer-sub {
            font-size: 0.6rem;
            letter-spacing: 3px;
            color: rgba(201,168,76,0.4);
            text-transform: uppercase;
            margin-top: 4px;
        }

        /* ── ANIMATIONS ── */
        @keyframes fadeDown {
            from { opacity: 0; transform: translateY(-20px); }
            to   { opacity: 1; transform: translateY(0); }
        }
        @keyframes fadeUp {
            from { opacity: 0; transform: translateY(20px); }
            to   { opacity: 1; transform: translateY(0); }
        }
        @keyframes fadeIn {
            from { opacity: 0; } to { opacity: 1; }
        }

        /* ── RESPONSIVE ── */
        @media (max-width: 1100px) { .controls-grid { grid-template-columns: repeat(2,1fr); } .client-form { grid-template-columns: repeat(2,1fr); } }
        @media (max-width: 640px) {
            .controls-grid { grid-template-columns: 1fr; }
            .client-form { grid-template-columns: 1fr; }
            .cta-section ul { grid-template-columns: 1fr; }
            .header h1 { font-size: 1.4rem; }
            .chart-wrapper { height: 300px; }
            .help-tooltip { width: min(310px, 82vw); right: -8px; }
        }
    </style>
</head>
<body>
<div class="container">

    <!-- HEADER -->
    <div class="header">
        <div class="logo-wrapper">
            <div class="logo-circle">
                <span class="logo-v">V</span>
            </div>
            <span class="logo-name">VOREN</span>
            <span class="logo-sub">Gestão Financeira</span>
        </div>
        <div class="gold-divider"></div>
        <h1 style="display:none;">Diagnóstico Financeiro Empresarial</h1>
        <p style="font-size:1rem;color:var(--white);letter-spacing:4px;font-weight:600;">DIAGNÓSTICO FINANCEIRO EMPRESARIAL</p><p style='margin-top:8px;font-size:0.75rem;letter-spacing:2px;'>Análise realizada pela VOREN Gestão Financeira</p>
    </div>

    <!-- MAIN CARD -->
    <div class="main-card">

        <!-- CHART -->
        <div class="chart-section">
            <div class="chart-wrapper">
                <canvas id="radarChart"></canvas>
            </div>
        </div>

        <!-- CLIENT DATA -->

        <div class="section-title">Dados do Cliente</div>
        <div class="client-form">
            <input type="text" id="clienteNome" placeholder="Nome completo *" required>
            <input type="text" id="clienteEmpresa" placeholder="Empresa *" required>
            <input type="tel" id="clienteWhatsapp" placeholder="WhatsApp *" required>
            <input type="email" id="clienteEmail" placeholder="E-mail">
            <input type="text" id="clienteCnpj" placeholder="CNPJ">
        </div>

        <!-- CONTROLS -->
        <div class="section-title">Avalie Cada Pilar do Seu Negócio</div>
        <div class="controls-grid" id="controlsGrid"></div>

        <button class="btn-diagnose" onclick="generateDiagnosis()">
            Gerar Diagnóstico Completo
        </button>
    </div>

    <!-- DIAGNOSIS -->
    <div class="diag-card" id="diagCard">
        <h2>Diagnóstico Financeiro Completo</h2>
        <div class="diag-grid" id="diagContent"></div>
    </div>

    <!-- FOOTER -->
    <div class="footer">
        <div class="footer-logo">VOREN</div>
        <div class="footer-sub">Gestão Financeira • Excelência em Resultados</div>
    </div>

</div>

<script>

const pillarDefinitions = {
    receitas: 'Toda entrada de recursos financeiros através de vendas de produtos ou prestação de serviços.',
    clareza: 'Capacidade de saber exatamente de onde vem cada centavo e para onde vai, tendo ciência da saúde financeira.',
    custos: 'Custos fixos são os que não mudam conforme o volume de produção, exemplo: aluguel. Custos variáveis são os que mudam, exemplo: matéria-prima.',
    projecao: 'Estimativa do quanto a empresa vai faturar.',
    emergencia: 'Reserva que sustenta no mínimo de 3 a 6 meses sua empresa sem vender nada.',
    planejamento: 'Estratégia de ação criada para corrigir os problemas identificados e guiar o futuro.',
    oportunidades: 'Valor reservado exclusivamente para aproveitar boas chances de mercado. Compra de ativos ou estoque de mercadoria, por exemplo.',
    fluxo: 'Ferramenta que rastreia todas as entradas e saídas de recursos financeiros (dinheiro) e mostra, por um período, a capacidade de pagar contas, investir e honrar compromissos.'
};

const pillars = [
    { id:'receitas', name:'Receitas', feedbacks:{
        1:'CRÍTICO: Empresa sem receitas consistentes. Risco iminente.',
        2:'MUITO RUIM: Receitas extremamente baixas e instáveis.',
        3:'PÉSSIMO: Insuficientes para cobrir custos básicos.',
        4:'RUIM: Irregulares, comprometem o crescimento.',
        5:'REGULAR: Apenas cobrem despesas, sem margem.',
        6:'RAZOÁVEL: Estáveis mas com pouco crescimento.',
        7:'BOM: Crescentes, ainda há espaço para melhorar.',
        8:'MUITO BOM: Sólidas com tendência positiva.',
        9:'ÓTIMO: Diversificadas e crescimento consistente.',
        10:'EXCELENTE: Robustas, múltiplas fontes, alta previsibilidade.'
    }},
    { id:'clareza', name:'Clareza de Informações', feedbacks:{
        1:'CRÍTICO: Zero controle financeiro. Decisões no escuro.',
        2:'MUITO RUIM: Informações caóticas e desorganizadas.',
        3:'PÉSSIMO: Dados confusos e desatualizados.',
        4:'RUIM: Informações básicas sem análise adequada.',
        5:'REGULAR: Controles mínimos, falta visão estratégica.',
        6:'RAZOÁVEL: Relatórios básicos sem indicadores principais.',
        7:'BOM: Organizadas mas podem ser mais detalhadas.',
        8:'MUITO BOM: Relatórios claros com indicadores definidos.',
        9:'ÓTIMO: Painel completo com análises preditivas.',
        10:'EXCELENTE: Sistema integrado com visibilidade total.'
    }},
    { id:'custos', name:'Custos Fixos/Variáveis', feedbacks:{
        1:'CRÍTICO: Custos totalmente desconhecidos e fora de controle.',
        2:'MUITO RUIM: Custos elevados sem qualquer gestão.',
        3:'PÉSSIMO: Mal gerenciados, comprometem lucros.',
        4:'RUIM: Altos sem estratégia de redução.',
        5:'REGULAR: Conhecidos mas sem otimização.',
        6:'RAZOÁVEL: Algum controle, ainda há desperdícios.',
        7:'BOM: Controlados mas com oportunidades de melhoria.',
        8:'MUITO BOM: Bem gerenciados e monitorados.',
        9:'ÓTIMO: Otimizados com revisões periódicas.',
        10:'EXCELENTE: Gestão enxuta com máxima eficiência.'
    }},
    { id:'projecao', name:'Projeção de Receitas', feedbacks:{
        1:'CRÍTICO: Zero planejamento. Empresa navegando às cegas.',
        2:'MUITO RUIM: Sem qualquer projeção ou previsibilidade.',
        3:'PÉSSIMO: Projeções inexistentes ou totalmente irreais.',
        4:'RUIM: Muito básicas e imprecisas.',
        5:'REGULAR: Simples sem base histórica sólida.',
        6:'RAZOÁVEL: Básicas mas falta detalhamento.',
        7:'BOM: Estruturadas mas podem ser refinadas.',
        8:'MUITO BOM: Detalhadas com múltiplos cenários.',
        9:'ÓTIMO: Robustas com análise de sensibilidade.',
        10:'EXCELENTE: Sistema preditivo avançado e integrado.'
    }},
    { id:'emergencia', name:'Reserva de Emergência', feedbacks:{
        1:'CRÍTICO: Sem reserva. Qualquer imprevisto quebra a empresa.',
        2:'MUITO RUIM: Reserva insuficiente para 1 semana.',
        3:'PÉSSIMO: Menos de 1 mês de reserva operacional.',
        4:'RUIM: Apenas 1-2 meses de reserva.',
        5:'REGULAR: 2-3 meses, ainda arriscado.',
        6:'RAZOÁVEL: 3-4 meses, melhorando mas insuficiente.',
        7:'BOM: 4-5 meses de reserva sólida.',
        8:'MUITO BOM: 5-6 meses garantindo tranquilidade.',
        9:'ÓTIMO: 6-12 meses de segurança financeira.',
        10:'EXCELENTE: +12 meses + linha de crédito disponível.'
    }},
    { id:'planejamento', name:'Planejamento Financeiro', feedbacks:{
        1:'CRÍTICO: Sem planejamento. Modo sobrevivência puro.',
        2:'MUITO RUIM: Apenas apaga incêndios diários.',
        3:'PÉSSIMO: Planejamento caótico e reativo.',
        4:'RUIM: Foco apenas no curtíssimo prazo.',
        5:'REGULAR: Planejamento básico de curto prazo.',
        6:'RAZOÁVEL: Planos de curto e médio prazo básicos.',
        7:'BOM: Estruturado mas falta visão de longo prazo.',
        8:'MUITO BOM: Planos integrados curto/médio/longo prazo.',
        9:'ÓTIMO: Estratégico, robusto e flexível.',
        10:'EXCELENTE: Governança financeira completa com revisões.'
    }},
    { id:'oportunidades', name:'Reserva de Oportunidades', feedbacks:{
        1:'CRÍTICO: Zero capacidade de aproveitar oportunidades.',
        2:'MUITO RUIM: Perde tudo por falta de recursos.',
        3:'PÉSSIMO: Sem reserva para investimentos estratégicos.',
        4:'RUIM: Mínima, perde boas oportunidades.',
        5:'REGULAR: Alguma reserva mas insuficiente.',
        6:'RAZOÁVEL: Básica para pequenas oportunidades.',
        7:'BOM: Adequada mas pode ser ampliada.',
        8:'MUITO BOM: Boa para investimentos estratégicos.',
        9:'ÓTIMO: Robusta + acesso a capital externo.',
        10:'EXCELENTE: Caixa completo para expansão agressiva.'
    }},
    { id:'fluxo', name:'Fluxo de Caixa', feedbacks:{
        1:'CRÍTICO: Fluxo negativo constante. Risco de insolvência.',
        2:'MUITO RUIM: Caótico e completamente imprevisível.',
        3:'PÉSSIMO: Negativo frequente, sufoco constante.',
        4:'RUIM: Instável com períodos de aperto.',
        5:'REGULAR: Equilibrado mas sem folga.',
        6:'RAZOÁVEL: Positivo mas com pouca margem.',
        7:'BOM: Saudável, pode melhorar a previsibilidade.',
        8:'MUITO BOM: Consistente e bem gerenciado.',
        9:'ÓTIMO: Robusto com excelente previsibilidade.',
        10:'EXCELENTE: Otimizado com gestão de tesouraria avançada.'
    }}
];

let vals = {};
pillars.forEach(p => vals[p.id] = 5);

// BUILD CONTROLS
function buildControls() {
    const grid = document.getElementById('controlsGrid');
    pillars.forEach(p => {
        const d = document.createElement('div');
        d.className = 'control-item';
        d.innerHTML = `
            <div class="label-row">
                <label for="${p.id}">${p.name}</label>
                <span class="help-wrap" tabindex="0" onclick="this.classList.toggle('open')">
                    <span class="help-icon" onclick="toggleTooltip(event, this)" tabindex="0">?</span>
                    <span class="help-tooltip">
                        <strong>${p.name}</strong>
                        <span>${pillarDefinitions[p.id]}</span>
                    </span>
                </span>
            </div>
            <div class="slider-row">
                <input type="range" id="${p.id}" class="slider" min="1" max="10" value="5"
                    oninput="onSlide('${p.id}', this.value)">
                <span class="val-badge" id="${p.id}-val">5</span>
            </div>
            <div class="feedback-box" id="${p.id}-fb"></div>
        `;
        grid.appendChild(d);
    });
}

// CHART
const ctx = document.getElementById('radarChart').getContext('2d');
const chart = new Chart(ctx, {
    type: 'radar',
    data: {
        labels: pillars.map(p => p.name),
        datasets: [{
            data: pillars.map(() => 5),
            backgroundColor: 'rgba(201,168,76,0.15)',
            borderColor: 'rgba(201,168,76,0.9)',
            borderWidth: 2.5,
            pointBackgroundColor: '#C9A84C',
            pointBorderColor: '#0A0A0A',
            pointBorderWidth: 2,
            pointRadius: 5,
            pointHoverRadius: 7
        }]
    },
    options: {
        responsive: true,
        maintainAspectRatio: false,
        scales: {
            r: {
                min: 0, max: 10,
                ticks: { stepSize: 2, color: 'rgba(201,168,76,0.5)', backdropColor: 'transparent', font: { size: 10 } },
                grid: { color: 'rgba(201,168,76,0.12)' },
                angleLines: { color: 'rgba(201,168,76,0.1)' },
                pointLabels: { color: 'rgba(245,240,232,0.85)', font: { size: 11, family: 'Montserrat', weight: '600' } }
            }
        },
        plugins: { legend: { display: false }, tooltip: {
            backgroundColor: 'rgba(10,10,10,0.95)',
            borderColor: 'rgba(201,168,76,0.5)',
            borderWidth: 1,
            titleColor: '#C9A84C',
            bodyColor: '#F5F0E8',
            callbacks: { label: ctx => `${ctx.label}: ${ctx.parsed.r}/10` }
        }}
    }
});

function onSlide(id, v) {
    vals[id] = +v;
    document.getElementById(`${id}-val`).textContent = v;
    const pct = ((v-1)/9)*100;
    let c = v<=3 ? '#ff4444' : v<=5 ? '#ffcc00' : v<=7 ? '#44dd88' : '#C9A84C';
    document.getElementById(id).style.background =
        `linear-gradient(to right, ${c} 0%, ${c} ${pct}%, #333 ${pct}%, #333 100%)`;
    const fb = document.getElementById(`${id}-fb`);
    const pillar = pillars.find(p => p.id === id);
    fb.textContent = pillar.feedbacks[+v];
    fb.style.borderLeftColor = c;
    fb.classList.add('show');
    chart.data.datasets[0].data = pillars.map(p => vals[p.id]);
    chart.update();
}

function getScoreColor(s) {
    if (s<=3) return '#ff4444';
    if (s<=5) return '#ffcc00';
    if (s<=7) return '#44dd88';
    return '#C9A84C';
}


function toggleTooltip(event, icon) {
    event.preventDefault();
    event.stopPropagation();

    document.querySelectorAll('.help-icon.active').forEach(item => {
        if (item !== icon) item.classList.remove('active');
    });

    icon.classList.toggle('active');
}

document.addEventListener('click', function() {
    document.querySelectorAll('.help-icon.active').forEach(item => {
        item.classList.remove('active');
    });
});

function generateDiagnosis() {

    const nome = document.getElementById('clienteNome').value.trim();
    const empresa = document.getElementById('clienteEmpresa').value.trim();
    const whatsapp = document.getElementById('clienteWhatsapp').value.trim();
    const email = document.getElementById('clienteEmail').value.trim();
    const cnpj = document.getElementById('clienteCnpj').value.trim();

    if (!nome || !empresa || !whatsapp) {
        alert('Por favor, preencha Nome, Empresa e WhatsApp antes de gerar o diagnóstico.');
        return;
    }

    const scores = pillars.map(p => vals[p.id]);
    const avg = (scores.reduce((a,b)=>a+b,0)/scores.length).toFixed(1);
    let hlabel, hcls;
    if (avg<=2) { hlabel='CRÍTICA'; hcls='h-critical'; }
    else if (avg<=4) { hlabel='RUIM'; hcls='h-bad'; }
    else if (avg<=6) { hlabel='REGULAR'; hcls='h-regular'; }
    else if (avg<=8) { hlabel='BOA'; hcls='h-good'; }
    else { hlabel='EXCELENTE'; hcls='h-excellent'; }

    const sorted = [...pillars].sort((a,b) => vals[b.id]-vals[a.id]);
    const strengths = sorted.filter(p => vals[p.id] >= 7).slice(0,3);
    const weaknesses = sorted.filter(p => vals[p.id] <= 5).slice(-3).reverse();

    const recs = [];
    if (vals.receitas<=5) recs.push('Diversifique fontes de receita e implemente estratégias de crescimento imediato');
    if (vals.clareza<=5)  recs.push('Implemente painel de controle financeiro com indicadores estratégicos claros');
    if (vals.custos<=5)   recs.push('Realize auditoria completa de custos e identifique oportunidades de redução');
    if (vals.projecao<=5) recs.push('Desenvolva projeções financeiras detalhadas para os próximos 12 meses');
    if (vals.emergencia<=5) recs.push('URGENTE: Construa reserva de emergência de pelo menos 6 meses de operação');
    if (vals.planejamento<=5) recs.push('Crie planejamento estratégico financeiro de curto, médio e longo prazo');
    if (vals.oportunidades<=5) recs.push('Estabeleça reserva dedicada para aproveitar oportunidades de mercado');
    if (vals.fluxo<=5)    recs.push('Implemente controle diário de fluxo de caixa com projeções semanais');
    if (!recs.length) {
        recs.push('Continue aprimorando processos para manter a excelência');
        recs.push('Explore oportunidades de expansão e crescimento acelerado');
        recs.push('Invista em inovação e diferenciação competitiva');
    }

    document.getElementById('diagContent').innerHTML = `
        <div class="diag-section">
            <h3>Visão Geral</h3>
            <span class="health-badge ${hcls}">Saúde Financeira: ${hlabel}</span>
            <p style="font-size:.85rem;line-height:1.8;color:var(--white-dim);margin-top:12px">
                Pontuação média: <strong style="color:var(--gold-light)">${avg}/10</strong> na Roda Financeira.
                ${+avg<=5 ?
                    'É fundamental tomar ações imediatas para reverter este quadro e garantir a sustentabilidade do negócio.' :
                    +avg<=7 ?
                    'Há oportunidades significativas de melhoria que elevarão seu negócio ao próximo nível.' :
                    'Parabéns! Sua gestão financeira está no caminho da excelência. Continue aprimorando.'}
            </p>
        </div>

        <div class="diag-section">
            <h3>Análise Detalhada por Pilar</h3>
            ${pillars.map(p => {
                const s = vals[p.id], c = getScoreColor(s);
                return `<div class="metric-row">
                    <span class="metric-name">${p.name}</span>
                    <span class="metric-score" style="background:${c}20;color:${c};border:1px solid ${c}40">${s}/10</span>
                </div>`;
            }).join('')}
        </div>

        ${strengths.length ? `
        <div class="diag-section">
            <h3>Pontos Fortes</h3>
            ${strengths.map(p => `
                <div style="padding:10px 12px;margin:6px 0;background:rgba(68,221,136,0.05);border-left:3px solid #44dd88;border-radius:0 8px 8px 0;font-size:.8rem;color:var(--white-dim)">
                    <strong style="color:#44dd88">${p.name}:</strong> ${p.feedbacks[vals[p.id]]}
                </div>`).join('')}
        </div>` : ''}

        ${weaknesses.length ? `
        <div class="diag-section">
            <h3>Áreas Críticas para Melhoria</h3>
            ${weaknesses.map(p => `
                <div style="padding:10px 12px;margin:6px 0;background:rgba(255,68,68,0.05);border-left:3px solid #ff4444;border-radius:0 8px 8px 0;font-size:.8rem;color:var(--white-dim)">
                    <strong style="color:#ff4444">${p.name}:</strong> ${p.feedbacks[vals[p.id]]}
                </div>`).join('')}
        </div>` : ''}

        <div class="rec-section">
            <h4>Recomendações Prioritárias</h4>
            <ul>${recs.map(r=>`<li>${r}</li>`).join('')}</ul>
        </div>

        <div class="cta-section">
            <h3>Próximos Passos com a Voren</h3>
            <p style="font-size:.82rem;color:var(--white-dim);margin-bottom:10px">A Voren Gestão Financeira transforma o diagnóstico em resultados reais:</p>
            <ul>
                <li>Organização completa das finanças</li>
                <li>Controles e relatórios profissionais</li>
                <li>Otimização de custos e lucratividade</li>
                <li>Projeções e planejamento estratégico</li>
                <li>Reservas de emergência estruturadas</li>
                <li>Fluxo de caixa saudável e previsível</li>
            </ul>
            <p>Não adie a saúde financeira que sua empresa merece.</p>
        </div>
    `;


    fetch("https://script.google.com/macros/s/AKfycbwBrYxxwQGqYR26R_S9Xdwf8M0iZTeShEAlDpsvztCqRG4T_L69kD8lz9n1baTwud70/exec", {
        method: "POST",
        mode: "no-cors",
        body: JSON.stringify({
            nome: nome,
            empresa: empresa,
            whatsapp: whatsapp,
            email: email,
            cnpj: cnpj,
            receitas: vals.receitas,
            clareza: vals.clareza,
            custos: vals.custos,
            projecao: vals.projecao,
            emergencia: vals.emergencia,
            planejamento: vals.planejamento,
            oportunidades: vals.oportunidades,
            fluxo: vals.fluxo,
            media: avg,
            diagnostico: hlabel
        })
    }).catch(() => {
        console.log("Não foi possível registrar na planilha.");
    });

    const card = document.getElementById('diagCard');
    card.style.display = 'block';
    setTimeout(() => card.scrollIntoView({ behavior:'smooth' }), 100);
}

buildControls();
pillars.forEach(p => onSlide(p.id, 5));
</script>
</body>
</html>
