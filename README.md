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
  </div>
  </body>
