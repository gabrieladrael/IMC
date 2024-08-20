<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="assets/css/style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" integrity="sha512-DTOQO9RWCH3ppGqcWaEA1BIZOC6xxalwEsw9c2QQeAIftl+Vegovlnee1c9QX4TctnWMn13TZye+giMm8e2LwA==" crossorigin="anonymous" referrerpolicy="no-referrer" />

    <title>Calculadora de IMC</title>
</head>
<body>
    <main id="container">
        <section id="img">
            <img src="assets/css/js/images/ilustretion.svg" alt="">
        </section>

        <section id="calculator">
            <form id="form">
                <h1 id="title">
                    Calculadora - IMC
                </h1>

                <div class="input-box">
                    <label for="weight">
                        Peso em Kg
                    </label>
                    <div class="input-field">
                        <i class="fa-solid fa-weight-hanging"></i>
                        <input type="number" id="weight" required>
                        <span>
                            Kg
                        </span>
                    </div>
                </div>

                <div class="input-box">
                    <label for="height">
                        Altura em metros
                    </label>
                    <div class="input-field">
                        <i class="fa-solid fa-ruler"></i>
                        <input type="number" id="height" required>
                        <span>
                            M
                        </span>
                    </div>
                </div>

                <button id="calculate">
                    Calcular
                </button>
            </form>

            <div id="infos" class="hidden">
                <div id="result">
                    <div id="bmi">
                        <span id="value"></span>
                        <span>Seu IMC</span>
                    </div>
                    <div id="description">
                        <span></span>
                    </div>
                </div>

                <div id="more_info">
                    <a href="https://mundoeducacao.uol.com.br/saude-bem-estar">
                        Mais informações sobre o IMC
                        <i class="fa-solid fa-arrow-up-right-from-square"></i>
                    </a>
                </div>
            </div>
        </section>
    </main>
    <script src="assets/css/js/script.js"></script>
</body>
</html>
