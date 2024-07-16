# codigo-formulario

<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulário de Feedback de Evento</title>
    
</head>
<body>
    <div class="container">
        <table border="1">
            <tr>
                <th><h1>Cadastro de Livros</h1></tr>
            </tr>
            <td>

                
            </td>


        </table>
        <h1>Feedback de Evento</h1>
        <form action="#" method="post">
            <br>
            
            <label for="evento">Qual evento você participou?</label>
            <br>
            <select id="evento" name="evento">
                <option value="conferencia">Conferência</option>
                <option value="workshop">Workshop</option>
                <option value="seminario">Seminário</option>
                <option value="palestra">Palestra</option>
                <option value="feira">Feira</option>
            </select>
            <br>
            <br>
            <label>O que você achou do evento?</label>
            <div class="checkbox-group">
                <label><input type="checkbox" name="feedback" value="ótimo"> Bom</label>
                <label><input type="checkbox" name="feedback" value="ruim"> Ruim</label>
                <label><input type="checkbox" name="feedback" value="regular"> Regular</label>
            </div>
            <br>
            <label for="comentarios">Comentários Adicionais:</label>
            <br>
            <textarea id="comentarios" name="comentarios" rows="4" placeholder="Compartilhe suas opiniões e sugestões"></textarea>
            <br>
            <label for="nome">Seu Nome:</label>
            <br>
            <input type="text" id="nome" name="nome" placeholder="Digite seu nome" required>
            <br>
            <label for="senha">Sua Senha:</label>
            <br>
            <input type="password" id="senha" name="senha" placeholder="Digite sua senha" required>
            <br>
            <br>
            <input type="submit" value="Enviar Feedback">
            <br>
            <br>
            <input type="reset" value="Limpar Formulário">
            <br>
            <br>
        </form>
    </div>
</body>
</html>
