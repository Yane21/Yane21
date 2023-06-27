<!DOCTYPE html>
<html>
<head>
  <title>Página de Pagamento</title>
  <style>
    /* Estilos CSS para a página de pagamento */
    /* ... adicione seus estilos personalizados aqui ... */
  </style>
</head>
<body>
  <h1>Página de Pagamento</h1>

  <form action="/processar-pagamento" method="post">
    <div>
      <label for="nome-cartao">Nome no Cartão:</label>
      <input type="text" id="nome-cartao" name="nome-cartao" required>
    </div>
    <div>
      <label for="numero-cartao">Número do Cartão:</label>
      <input type="text" id="numero-cartao" name="numero-cartao" required>
    </div>
    <div>
      <label for="validade-cartao">Validade:</label>
      <input type="text" id="validade-cartao" name="validade-cartao" required>
    </div>
    <div>
      <label for="cvv-cartao">CVV:</label>
      <input type="text" id="cvv-cartao" name="cvv-cartao" required>
    </div>
    <div>
      <label for="valor">Valor a Pagar:</label>
      <input type="text" id="valor" name="valor" required>
    </div>
    <div>
      <label for="email">E-mail:</label>
      <input type="email" id="email" name="email" required>
    </div>
    <div>
      <input type="submit" value="Pagar">
    </div>
  </form>

</body>
</html>
