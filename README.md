<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="assets/css/style.css">
    <title>Formulário de Cadastro</title>
</head>
<body>
    <div class="container">
        <div class="form-img">
            <img src="assets/img/logo.jpg" alt="Imagem do Formulário.">
        </div>
        <div class="form">
            <form action="">
                <div class="form-header">
                    <div class="tittle">
                        <h1>Cadastre-se</h1>
                    </div>
                    <div class="login-button">
                        <button type="submit">Login</button>
                    </div>
                </div>
                <div class="input-group">
                    <div class="input-box">
                        <label for="firstname">Primeiro Nome</label>
                        <input id="firstname" type="text" name="firstname" placeholder="Digite seu primeiro nome">
                    </div>
                     <div class="input-box">
                        <label for="lastname">Sobrenome</label>
                        <input id="lastname" type="text" name="lastname" placeholder="Digite seu sobrenome">
                    </div>
                     <div class="input-box">
                        <label for="email">Email</label>
                        <input id="email" type="email" name="email" placeholder="Digite seu email">
                    </div>
                     <div class="input-box">
                        <label for="number">Celular</label>
                        <input id="number" type="tel" name="number" placeholder="XX XXXXX-XXXX" pattern="[0-9]{2}
                        [0-9]{5} - [0-9]{4}">
                    </div>
                     <div class="input-box">
                        <label for="password">Senha</label>
                        <input id="password" type="password" name="password" placeholder="Digite sua senha">
                    </div>
                    <div class="input-box">
                        <label for="confirmpassword">Senha</label>
                        <input id="confirmpassword" type="password" name="confirmpassword" placeholder="Confirme sua senha">
                    </div>
                </div>
                <div class="gender-inputs">
                    <div class="gender-title">
                        <h6>Gênero</h6>
                    </div>
                    <div class="gender-group">
                        <div class="gender-input">
                            <input type="radio" id="female" name="gender">
                            <label for="female">Feminino</label>
                        </div>
                         <div class="gender-input">
                            <input type="radio" id="male" name="gender">
                            <label for="male">Masculino</label>
                        </div>
                        <div class="gender-input">
                            <input type="radio" id="others" name="gender">
                            <label for="others">Outros</label>
                        </div>
                    </div>
                </div>
                <div class="register-button">
                    <button type="submit">Cadastrar</button>
                </div>
            </form>
        </div>
    </div>
</body>
</html>
















css

body{
    width: 100vw;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: white;
    font-family: 'Times New Roman', Times, serif;
}


.container{
    width: 80vw;
    height: 80vh;
    display: flex;
    box-shadow: 5px 5px 10px #dcdcdc;
}

.form-img{
    width: 50vw;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 16px;
}

.form-img img{
    width: 550px;
    height: 550px;

}

.form{
    width: 50vw;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    background-color: #ffff;
    padding: 50px;
}

.form-header{
    margin-top: 15px;
    display: flex;
    justify-content: space-between;

}

.login-button{
    display: flex;
    align-items: center;
}

.login-button button{
    border: none;
    background-color: #006400;
    font-weight: bold;
    color: #fff;
    padding: 8px 16px;
    border-radius: 5px;
    cursor: pointer;
}

.login-button button:hover{
    background-color: #087408;

}

.input-group {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    padding: 16px 0;
}

.input-box{
    display: flex;
    flex-direction: column;

}


.input-box input{
    margin: 10px 0;
    padding: 13px 19px;
    border: none;
    border-radius: 10px;
    box-shadow: 2px 2px 6px #d3d3d3;
}

.input-box input:focus-visible{
    outline: 2px solid #5b7cc2;
}

