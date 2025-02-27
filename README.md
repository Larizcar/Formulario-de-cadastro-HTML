# Formulario-de-cadastro-HTML
Formulario de cadastro somente com o HTML 
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title></title>
</head>
<body>
   <div>
     <h1>CADASTRO DE CLIENTE</h1>
     <p>Complete suas informações</p>
     <br>
   </div>
   <form>
     <fieldset>
       <legend>Informações Pessoais:</legend>
       <div>
         
         <label>Nome:</label><br>
         <input type="text" name="nome" id="nome"> 
       </div>
       <label>Sobrenome:</label> <br>
       <input type="text" name="sobrenome" id="sobrenome">
     </fieldset>
     <fieldset>
       <legend>Contato:</legend>
     
     <label> E-mail: </label> <br>
     <input type="email" nome="email" id="email">
     <div> 
     <label>Telefone:</label> <br>
     <input type="number" name="telefone" id="telefone">
     <div>
    
       <label>Rua:</label><br>
      <input type="text" name="Rua" id="Rua">
      </div>
      
      <div>
      <label>Número</label><br>
      <input type="number" name="Número" id="Número">
      </div>
      <div>
        <label>Cep:</label><br>
        <input type="number" name="Cep" id="Cep">
      </div>
      <div>
      <label>Bairro:</label> <br>
      <input type="text" name="Bairro" id="Bairro">
      </div>
      <div>
      <label>Cidade:</label><br>
      <input type="text" name="Cidade" id="Cidade">
      </div>
      <label>Estado:</label><br>
      <input type="text" name="Estado" id="Estado">
     </fieldset>
     </div>
     <div>
       <fieldset>
    <legend>Gênero:</legend>
    <input type="radio" id="masculino" name="genero" value="masculino">
    <label for="masculino">Masculino</label>
    
    <input type="radio" id="feminino" name="genero" value="feminino">
    <label for="feminino">Feminino</label>
    
    <input type="radio" id="outro" name="genero" value="outro">
    <label for="outro">Outro</label>
    
    <input type="radio" id="prefiro_nao_dizer" name="genero" value="prefiro_nao_dizer">
    <label for="prefiro_nao_dizer">Prefiro não dizer</label>
</fieldset>
<div>
  <fieldset>
   <legend>Login</legend>
       <label> Usuário: </label><br>
       <input type="text" name="usuário" id="Usuário">
       <br>
       <label>Senha:</label><br>
       <input type="text" name="Senha" id="Senha">
       </fieldset>
     </div>
     <input type="submit" value="ENVIAR">
   </form>
</body>
</html>
