<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Exercício 1 </title>
</head>

<body>
    <main>
        <section id="Formulario">
            <h2> Formulário </h2>
            <form action="http://10.111.211.110:8088/aula8_Exercicio.php" method="post">
                <input type="hidden" name="prontuario" value="CB3038866">


                <label for="nome_completo">Nome: </label><br>
                <input type="text" Name="nome_completo" placeholder="escreva seu nome"><br> <br>

                <label for="celular">Celular: </label> <br>
                <input type="tel" name="celular" placeholder="(13) 00000-0000"> <br> <br>

                <label for="e-mail">Email: </label> <br>
                <input type="email" name="e-mail" placeholder="seuemail@gmail.com"> <br> <br>

                <label for="idade">Idade:</label> <br>
                <input type="number" name="idade" placeholder="Escreva a sua idade" min="18" required> <br> <br>

                <label for="investimento">Investimento: </label> <br>
                <input type="range" name="investimento" placeholder="Informe o investimento" min="0" max="1000" step="10"  value="50" required> <br> <br>

                <label for="nascimento">Nascimento: </label> <br>
                <input type="date" name="nascimento" min="1925-01-01" max="2025-12-31" value="2023-06-15" required> <br> <br>

                <label for="preferencia">Agendamento:</label> <br>
                <input type="datetime-local" name="preferencia"> <br> <br>

                <label for="linkedin">Linkedin: </label> <br>
                <input type="url" name="linkedin" placeholder="https://www.exemplo.com" required> <br> <br>

                <label for="cor_preferida">Cor preferida: </label>
                <input type="color" name="cor_preferida" value="#0066cc"> <br> <br>

               <p>Informe sua formação:</p> 
                <input type="radio" id="formação" name="formacao" value="Fundamental" checked >
                <label for="Fundamental">Fundamental</label> <br>

                <input type="radio" id="formação" name="formacao" value="medio" required> 
                <label for="medio">Ensino médio</label> <br>

                <input type="radio" id="formação" name="formacao" value="superior_inco" required> 
                <label for="superior_inco">Superior incompleto</label> <br>

                <input type="radio" id="formação" name="formacao" value="superior_com" required> 
                <label for="superior_com">Superior completo</label> <br>

                <input type="radio" id="formação" name="formacao" value="pos" required> 
                <label for="pos">Pós-Graduação</label> <br>
                


                <br> <input type="submit" value="Enviar">
            </form>
        </section>
    </main>

</body>

</html>
