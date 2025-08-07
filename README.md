<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>📚 Material de Estudo - Rádio & Patrulhamento</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <style>
    :root {
      --bg-color: #f4f6fc;
      --text-color: #333;
      --primary-color: #304ffe;
      --secondary-bg: #ffffff;
      --table-header: #e8eaf6;
      --hover-color: #eef1ff;
      --box-bg: #ffffff;
    }
    body.dark-mode {
      --bg-color: #121212;
      --text-color: #e0e0e0;
      --primary-color: #90caf9;
      --secondary-bg: #1e1e1e;
      --table-header: #333;
      --hover-color: #2a2a2a;
      --box-bg: #1e1e1e;
    }
    body {
      font-family: 'Poppins', sans-serif;
      background-color: var(--bg-color);
      color: var(--text-color);
      margin: 0;
      padding: 0;
      line-height: 1.6;
      transition: background 0.3s, color 0.3s;
    }
    header {
      background: var(--primary-color);
      color: white;
      text-align: center;
      padding: 20px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.2);
      position: relative;
    }
    header h1 {
      margin: 0;
      font-size: 2rem;
    }
    .toggle-mode {
      position: absolute;
      right: 20px;
      top: 20px;
      background: white;
      color: var(--primary-color);
      border: none;
      padding: 10px 15px;
      border-radius: 6px;
      font-weight: bold;
      cursor: pointer;
      transition: background 0.3s, color 0.3s;
    }
    body.dark-mode .toggle-mode {
      background: #1e1e1e;
      color: white;
      border: 1px solid #90caf9;
    }
    main {
      max-width: 1100px;
      margin: 30px auto;
      padding: 0 15px;
    }
    h2 {
      background-color: var(--primary-color);
      color: white;
      padding: 10px 15px;
      border-radius: 8px;
      margin-top: 40px;
      font-size: 1.3rem;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin: 15px 0;
      background: var(--secondary-bg);
      border-radius: 8px;
      overflow: hidden;
      box-shadow: 0 2px 8px rgba(0,0,0,0.05);
      transition: background 0.3s;
    }
    th, td {
      padding: 12px;
      text-align: left;
    }
    th {
      background: var(--table-header);
      font-weight: 600;
    }
    tr:nth-child(even) {
      background: var(--hover-color);
    }
    tr:hover {
      background: var(--table-header);
    }
    .box {
      background-color: var(--box-bg);
      padding: 15px;
      border-radius: 8px;
      margin-top: 10px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.05);
      font-size: 1rem;
      transition: background 0.3s;
    }
    .box strong {
      color: var(--primary-color);
    }
    code {
      background-color: var(--table-header);
      padding: 4px 8px;
      border-radius: 4px;
      display: inline-block;
      margin-top: 5px;
    }
    .back-top {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background: var(--primary-color);
      color: white;
      border: none;
      padding: 12px;
      border-radius: 50%;
      cursor: pointer;
      font-size: 18px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.2);
      transition: background 0.3s;
    }
    .back-top:hover {
      background: #1a34d3;
    }
  </style>
</head>
<body>

  <header>
    <h1>📚 Material de Estudo - Rádio & Patrulhamento</h1>
    <button class="toggle-mode" onclick="toggleDarkMode()">🌙 Modo Escuro</button>
  </header>

  <main>
    <section>
      <h2>📡 Códigos Q - Comunicação via Rádio</h2>
      <table>
        <tr><th>Código</th><th>Significado</th></tr>
        <tr><td>QAP</td><td>Na escuta</td></tr>
        <tr><td>QRR</td><td>Apoio terrestre </td></tr>
        <tr><td>QSL</td><td>Entendido</td></tr>
        <tr><td>QSM</td><td>Repetir mensagem</td></tr>
        <tr><td>QTO</td><td>Ir ao banheiro</td></tr>
        <tr><td>QRA</td><td>Identificação</td></tr>
        <tr><td>TKS</td><td>Obrigado</td></tr>
        <tr><td>QTX</td><td>Sair de serviço</td></tr>
        <tr><td>QRX</td><td>Silêncio</td></tr>
        <tr><td>QSJ</td><td>Dinheiro</td></tr>
        <tr><td>QTI</td><td>A caminho</td></tr>
        <tr><td>QTH</td><td>Localização</td></tr>
        <tr><td>QTA</td><td>Sair do local</td></tr>
        <tr><td>QTC</td><td>Mensagem</td></tr>
        <tr><td>QSV / VTR</td><td>Viatura</td></tr>
        <tr><td>QRV</td><td>Às ordens</td></tr>
        <tr><td>QRL</td><td>Ocupado</td></tr>
        <tr><td>QSO</td><td>Aviso de comunicação</td></tr>
      </table>
    </section>

    <section>
      <h2>🚔 Códigos de Patrulhamento</h2>
      <table>
        <tr><th>Código</th><th>Situação</th></tr>
        <tr><td>0</td><td>Iniciando patrulhamento</td></tr>
        <tr><td>1</td><td>Abordagem de rotina (baixo risco)</td></tr>
        <tr><td>2</td><td>Abordagem suspeita (risco médio)</td></tr>
        <tr><td>3</td><td>Uso de força não letal</td></tr>
        <tr><td>4</td><td>Área segura / situação sob controle</td></tr>
        <tr><td>5</td><td>Fogo liberado (risco extremo)</td></tr>
        <tr><td>6</td><td>Investigação no local</td></tr>
        <tr><td>7</td><td>QRR máximo / Apenas comandos</td></tr>
      </table>
    </section>

    <section>
      <h2>👮‍♂️ Funções dentro da Viatura</h2>
      <table>
        <tr><th>Posição</th><th>Função</th></tr>
        <tr><td>P1</td><td>É RESPONSÁVEL  PELA VIATURA,CONDUÇÃO E SUA VISÃO É FOCADA APENAS PARA FRENTE Em SITUACAO DE CODIGO 5  PROCURAR UM LUGAR SEGURO PARA O DROP</td></tr>
        <tr><td>P2</td><td>É RESPONSÁVEL PELA MODULAÇÃO COM A CENTRAL, VIA RADIO E COM UM INDIVÍDUO DURANTE AS ABORDAGENS E TAMBEM EXECUTAR ABORDAGENS</td></tr>
        <tr><td>P3</td><td>FAZER O PERIMETRO DO LOCAL DURANTE UMA ABORDAGEM</td></tr>
        <tr><td>P4</td><td>Apoio ou réu em custódia</td></tr>
      </table>
    </section>

    <section>
      <h2>📜 Lei de Miranda</h2>
      <div class="box">
        <p><strong>"Sr(a), o(a) senhor(a) está sendo preso(a) pelo Exército Brasileiro tudo que o senhor falar podera e sera usado contra vc no tribunal o senhor tem direito a uma ligacao e um adivogado e um  copo de agua vc etende seus deiretos </strong></p>
      </div>
    </section>

    <section>
      <h2>👩🏻‍🦰 Procedimento da Caixinha</h2>
      <div class="box">
        <ul>
          <li>Steves <strong>NÃO</strong> podem revistar mulheres.</li>
          <li>Se não houver Fox, solicitar 3x no rádio.</li>
          <li>Se ainda assim não vier Fox:
            <ul>
              <li>Se a cidadã aceitar o "procedimento da caixinha", Steves podem revistar.</li>
              <li>Se recusar, conduzir à DP até chegada da Fox.</li>
            </ul>
          </li>
        </ul>
      </div>
    </section>

    <section>
      <h2>🎙️ Modulações Padrão</h2>
      <div class="box">
        <p><strong>📌 modulacao 1 Exemplo :</strong><br>
          <code>QAP Central, unidade (veículo), iniciando código 0 a total <strong>QRV</strong> da rede <strong>QSL</strong></code>
        </p>
        <p><strong>📌 modulacao 2 Exemplo </strong><br>
          <code>QAP Central, solicito uma QSV no meu QTH...</code>
        </p>
      </div>
    </section>
  </main>

  <button class="back-top" onclick="window.scrollTo({top:0, behavior:'smooth'});">⬆</button>

  <script>
    function toggleDarkMode() {
      document.body.classList.toggle('dark-mode');
      const button = document.querySelector('.toggle-mode');
      if (document.body.classList.contains('dark-mode')) {
        button.textContent = '☀️ Modo Claro';
      } else {
        button.textContent = '🌙 Modo Escuro';
      }
    }
  </script>
</body>
</html>
