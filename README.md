<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ahhhmmmmm Hellooo</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Noto+Serif+JP:wght@300;400&display=swap');

  * { margin: 0; padding: 0; box-sizing: border-box; }

  body {
    background: #0f0812;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    min-height: 100vh;
    font-family: 'Noto Serif JP', serif;
    overflow: hidden;
  }

  .scene {
    position: relative;
    width: 280px;
    height: 260px;
  }

  /* ── your original pixel-art animation ── */
  .pixelart-to-css {
    position: absolute;
    animation: x 1s infinite;
    -webkit-animation: x 1s infinite;
    -moz-animation: x 1s infinite;
    -o-animation: x 1s infinite;
  }

  @keyframes x {
    0%, 33.3% {
      box-shadow:
        40px 30px 0 0 rgba(255,205,210,1), 140px 30px 0 0 rgba(255,205,210,1),
        30px 40px 0 0 rgba(255,205,210,1), 40px 40px 0 0 rgba(255,205,210,1),
        50px 40px 0 0 rgba(255,205,210,1), 130px 40px 0 0 rgba(255,205,210,1),
        140px 40px 0 0 rgba(255,205,210,1), 150px 40px 0 0 rgba(255,205,210,1),
        40px 50px 0 0 rgba(255,205,210,1), 140px 50px 0 0 rgba(255,205,210,1),
        90px 60px 0 0 rgba(255,205,210,1), 80px 70px 0 0 rgba(255,205,210,1),
        90px 70px 0 0 rgba(255,205,210,1), 100px 70px 0 0 rgba(255,205,210,1),
        90px 80px 0 0 rgba(255,205,210,1), 160px 90px 0 0 rgba(255,205,210,1),
        150px 100px 0 0 rgba(255,205,210,1), 160px 100px 0 0 rgba(255,205,210,1),
        170px 100px 0 0 rgba(255,205,210,1), 160px 110px 0 0 rgba(255,205,210,1),
        70px 120px 0 0 rgba(255,205,210,1), 200px 120px 0 0 rgba(255,205,210,1),
        60px 130px 0 0 rgba(255,205,210,1), 70px 130px 0 0 rgba(255,205,210,1),
        80px 130px 0 0 rgba(255,205,210,1), 190px 130px 0 0 rgba(255,205,210,1),
        200px 130px 0 0 rgba(255,205,210,1), 210px 130px 0 0 rgba(255,205,210,1),
        70px 140px 0 0 rgba(255,205,210,1), 200px 140px 0 0 rgba(255,205,210,1),
        140px 150px 0 0 rgba(255,205,210,1), 130px 160px 0 0 rgba(255,205,210,1),
        140px 160px 0 0 rgba(255,205,210,1), 150px 160px 0 0 rgba(255,205,210,1),
        140px 170px 0 0 rgba(255,205,210,1);
      height: 10px; width: 10px;
    }
    33.31%, 66.7% {
      box-shadow:
        70px 50px 0 0 rgba(255,205,210,1), 170px 50px 0 0 rgba(255,205,210,1),
        60px 60px 0 0 rgba(255,205,210,1), 70px 60px 0 0 rgba(255,205,210,1),
        80px 60px 0 0 rgba(255,205,210,1), 160px 60px 0 0 rgba(255,205,210,1),
        170px 60px 0 0 rgba(255,205,210,1), 180px 60px 0 0 rgba(255,205,210,1),
        70px 70px 0 0 rgba(255,205,210,1), 170px 70px 0 0 rgba(255,205,210,1),
        110px 90px 0 0 rgba(255,205,210,1), 210px 90px 0 0 rgba(255,205,210,1),
        100px 100px 0 0 rgba(255,205,210,1), 110px 100px 0 0 rgba(255,205,210,1),
        120px 100px 0 0 rgba(255,205,210,1), 200px 100px 0 0 rgba(255,205,210,1),
        210px 100px 0 0 rgba(255,205,210,1), 220px 100px 0 0 rgba(255,205,210,1),
        110px 110px 0 0 rgba(255,205,210,1), 210px 110px 0 0 rgba(255,205,210,1),
        60px 130px 0 0 rgba(255,205,210,1), 50px 140px 0 0 rgba(255,205,210,1),
        60px 140px 0 0 rgba(255,205,210,1), 70px 140px 0 0 rgba(255,205,210,1),
        60px 150px 0 0 rgba(255,205,210,1), 120px 150px 0 0 rgba(255,205,210,1),
        180px 150px 0 0 rgba(255,205,210,1), 110px 160px 0 0 rgba(255,205,210,1),
        120px 160px 0 0 rgba(255,205,210,1), 130px 160px 0 0 rgba(255,205,210,1),
        170px 160px 0 0 rgba(255,205,210,1), 180px 160px 0 0 rgba(255,205,210,1),
        190px 160px 0 0 rgba(255,205,210,1), 120px 170px 0 0 rgba(255,205,210,1),
        180px 170px 0 0 rgba(255,205,210,1);
      height: 10px; width: 10px;
    }
    66.71%, 100% {
      box-shadow:
        180px 20px 0 0 rgba(255,205,210,1), 170px 30px 0 0 rgba(255,205,210,1),
        180px 30px 0 0 rgba(255,205,210,1), 190px 30px 0 0 rgba(255,205,210,1),
        180px 40px 0 0 rgba(255,205,210,1), 40px 50px 0 0 rgba(255,205,210,1),
        30px 60px 0 0 rgba(255,205,210,1), 40px 60px 0 0 rgba(255,205,210,1),
        50px 60px 0 0 rgba(255,205,210,1), 210px 60px 0 0 rgba(255,205,210,1),
        40px 70px 0 0 rgba(255,205,210,1), 200px 70px 0 0 rgba(255,205,210,1),
        210px 70px 0 0 rgba(255,205,210,1), 220px 70px 0 0 rgba(255,205,210,1),
        210px 80px 0 0 rgba(255,205,210,1), 130px 110px 0 0 rgba(255,205,210,1),
        20px 120px 0 0 rgba(255,205,210,1), 120px 120px 0 0 rgba(255,205,210,1),
        130px 120px 0 0 rgba(255,205,210,1), 140px 120px 0 0 rgba(255,205,210,1),
        10px 130px 0 0 rgba(255,205,210,1), 20px 130px 0 0 rgba(255,205,210,1),
        30px 130px 0 0 rgba(255,205,210,1), 130px 130px 0 0 rgba(255,205,210,1),
        20px 140px 0 0 rgba(255,205,210,1), 200px 170px 0 0 rgba(255,205,210,1),
        190px 180px 0 0 rgba(255,205,210,1), 200px 180px 0 0 rgba(255,205,210,1),
        210px 180px 0 0 rgba(255,205,210,1), 70px 190px 0 0 rgba(255,205,210,1),
        200px 190px 0 0 rgba(255,205,210,1), 60px 200px 0 0 rgba(255,205,210,1),
        70px 200px 0 0 rgba(255,205,210,1), 80px 200px 0 0 rgba(255,205,210,1),
        70px 210px 0 0 rgba(255,205,210,1);
      height: 10px; width: 10px;
    }
  }

  /* ── decorative label ── */
  .label {
    margin-top: 2rem;
    color: rgba(255, 205, 210, 0.55);
    font-size: 0.7rem;
    letter-spacing: 0.45em;
    text-transform: uppercase;
  }
</style>
</head>
<body>
  <div class="scene">
    <div class="pixelart-to-css"></div>
  </div>
  <p class="label">sakura · 桜</p>
</body>
</html>
