<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Una canción por cada día</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      background: #ffe6e6 url('https://example.com/tulipanes-morados-dibujo.jpg') no-repeat center center fixed;
      background-size: cover;
      margin: 0;
      padding: 0;
      color: #333;
    }
    header {
      text-align: center;
      padding: 20px;
      background: rgba(255, 99, 99, 0.8);
      color: white;
      font-size: 2em;
    }
    .day {
      margin: 20px auto;
      padding: 15px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
      max-width: 600px;
      color: white;
      text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.5);
    }
    .day:nth-child(2) {
      background: url('https://example.com/tyler-the-creator.jpg') no-repeat center center / cover;
    }
    .day:nth-child(3) {
      background: url('https://example.com/ramma-tadu.jpg') no-repeat center center / cover;
    }
    .day:nth-child(4) {
      background: url('https://example.com/jaze-perdon.jpg') no-repeat center center / cover;
    }
    .day:nth-child(5) {
      background: url('https://example.com/jaze-lunares.jpg') no-repeat center center / cover;
    }
    .day h2 {
      color: #ffcccc;
    }
    iframe {
      width: 100%;
      height: 150px;
      border: none;
      border-radius: 5px;
    }
  </style>
</head>
<body>
  <header>
    Una canción por cada día que no hablamos
  </header>
  
  <section class="day">
    <h2>Día 1: See You Again - Tyler, the Creator</h2>
    <p>"Can I get a kiss? And can you make it last forever?"</p>
    <iframe src="https://www.youtube.com/embed/0siv2O9ijlg" allowfullscreen></iframe>
  </section>

  <section class="day">
    <h2>Día 2: Nostalgia - Ramma ft. Tadu Vázquez</h2>
    <p>"A veces pienso en lo bonito de la nostalgia, en los momentos que nunca vuelven pero siempre quedan."</p>
    <iframe src="https://www.youtube.com/embed/VusKtZHSNtU" allowfullscreen></iframe>
  </section>

  <section class="day">
    <h2>Día 3: Perdón - Jaze</h2>
    <p>"Perdón por no saber quererte bien, por no entender a tiempo lo que valías."</p>
    <iframe src="https://www.youtube.com/embed/28c_jRO69g8" allowfullscreen></iframe>
  </section>

  <section class="day">
    <h2>Día 4: Lunares - Jaze</h2>
    <p>"Los lunares en tu piel cuentan historias que quiero descubrir."</p>
    <iframe src="https://www.youtube.com/embed/vYyD1PUQYys" allowfullscreen></iframe>
  </section>
</body>
</html>
