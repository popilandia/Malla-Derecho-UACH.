<!DOCTYPE html>
<html>
<head>
  <title>Malla Derecho</title>
  <style>
    body { font-family: sans-serif; padding: 20px; }
    h1 { text-align: center; }
    h2 { margin-top: 40px; color: #333; }
    .semestre { margin-bottom: 30px; }
    .ramo {
      border: 1px solid #ccc;
      padding: 10px;
      margin: 5px;
      display: inline-block;
      width: 250px;
      cursor: pointer;
      border-radius: 10px;
      background-color: #f9f9f9;
    }
    .ramo:hover {
      background-color: #eef;
    }
    .detalle { display: none; margin-top: 10px; font-size: 14px; }
  </style>
</head>
<body>
  <h1>Malla Interactiva - Derecho</h1>

  <!-- Aquí van los semestres -->

  <div class="semestre">
    <h2>1er Semestre</h2>
    <div class="ramo" onclick="toggle('s1r1')">
      Sistema Jurídico
      <div class="detalle" id="s1r1">🪴 Obligatorio<br>📌 Sin requisitos<br>🧪 Créditos: 7</div>
    </div>
    <div class="ramo" onclick="toggle('s1r2')">
      Historia del Derecho
      <div class="detalle" id="s1r2">🪴 Obligatorio<br>📌 Sin requisitos<br>🧪 Créditos: 5</div>
    </div>
    <div class="ramo" onclick="toggle('s1r3')">
      Teoría Constitucional
      <div class="detalle" id="s1r3">🪴 Obligatorio<br>📌 Sin requisitos<br>🧪 Créditos: 7</div>
    </div>
    <div class="ramo" onclick="toggle('s1r4')">
      Jurisdicción
      <div class="detalle" id="s1r4">🪴 Obligatorio<br>📌 Sin requisitos<br>🧪 Créditos: 5</div>
    </div>
    <div class="ramo" onclick="toggle('s1r5')">
      Comunicación Oral y Escrita
      <div class="detalle" id="s1r5">🪴 Obligatorio<br>📌 Sin requisitos<br>🧪 Créditos: 5</div>
    </div>
    <div class="ramo" onclick="toggle('s1r6')">
      Educación Física y Salud
      <div class="detalle" id="s1r6">🪴 Obligatorio<br>📌 Sin requisitos<br>🧪 Créditos: 0</div>
    </div>
  </div>

  <!-- Más semestres van aquí... -->

  <script>
    function toggle(id) {
      var x = document.getElementById(id);
      x.style.display = x.style.display === 'block' ? 'none' : 'block';
    }
  </script>
</body>
</html>
