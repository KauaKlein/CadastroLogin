// efetuar-login
//Metodo para logar em sites

JS

<meta charset="UTF-8">
<script>

    var loginCadastrado = "felipe";
    var senhaCadastrada = "github2021";

    var loginInformado = prompt("Informe seu login");
    var senhaInformada = prompt("Informe sua senha");

    if( loginCadastrado == loginInformado && senhaCadastrada == senhaInformada ) {

        alert("Bem-vindo ao sistema " + loginInformado);
    } else {

        alert("Login inválido. Tente novamente");
    }
</script>
