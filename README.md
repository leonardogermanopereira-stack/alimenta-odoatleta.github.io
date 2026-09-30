<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Controle de Alimentaçãodo Atleta</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
<header class="topo">
  <div class="marca">
<div class="icone-marca">🏆</div>
<div> 
  <h1>AtletaControl</h1>
  <p>Controle de alimentação e rotina esportiva</p>
 </div>
</div>
<button id="btn btn-tema">
   🌙 Tema escuro
</button>
</header>
<main class="card">
<div class="titulo">
<h2>👤 Perfil do Atleta</h2>
<p>
  informações para organizar registros.
 </p>
</div>
  <div class="grid-perfil">
  <div class="campo">
  <label>Nome</label>
  <input>
    type="text"
    id="atletaNome"
    placeholder="Nome do Atleta">
  </div>
  <div class="campo">
    <label>Modalidade</label>
    <input>
     type="text"
     placeholder="Ex: futebol">
  </div>
  <div class="campo">
    <label>Equipe / Clube</label>
  <input>
    type="text"
    id="equipe"
    placeholder="Nome da equipe">
  </div>

  </div>
  </section>
  <!--RESUMO -->
  <section class="dashboard">
  <div class="indicador">
   <span>🍽</span>
   <div>
     <small>Refeições registradas</small>
     <String id="totalRefeições=>0</strong>
    </div>
  </div>
  <div class="indicador agua">
  <span>💧</span>
  <div>
    <small>Água Registrada</small>
    <strong id="aguaTotal">0 L</strong>
  </div>
  </div>
  <div class="indicador sono">
  <span>😴</span>
  <div>
  <small>Sono</small>
  <Strong id="sonoTotal">--</Strong>
  </div>
  </div>
  <div class="indicador de energia">
  <span>⚡️</span>
  <div>
   <small>energia percebida</small>
    <strong id="energiaTotal">--</strong>strong>
    </div>
  </div>
     </section> 
  <!--REGISTRO DE REFEIÇÃO-->
  <section class="card">
   <div class="titulo">
   <h2>🍽 Registrar refeição</h2>
  </p>
   </div>
    <form id="formRefeição">
    <input type="hidden" id="refeicaold">
    <div class="form-grid">
     <div class="campo">
       <label>Tipo de Refeição *</label>
       <select id="tipoRefeicao" required>
        <option vale="">
          Selecione
        </option>
        <option>
          Café da Manhã
        </option>
        <option>
          Lanche da Manhã
        </option>
         <option>
           Almoço 
         </option>
         <option>
           Lanche da tarde
         </option>
         <option>
           Lanche da tarde
         </option>
         
     </body>
