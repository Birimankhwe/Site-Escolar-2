<!DOCTYPE html>
<html lang="pt-br">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>O Pequeno Mercado PM</title>
  <link rel="stylesheet" href="site.escolar.css">
</head>

<body>
  <header>
    <h1>Escola XYZ</h1>
    <nav>
      <ul>
        <li><a href="#sobre">Sobre</a></li>
        <li><a href="#cursos">Cursos</a></li>
        <li><a href="#contato">Contato</a></li>
      </ul>
    </nav>
  </header>

  <section id="sobre">
    <h2>Sobre Nós</h2>
    <p>Breve descrição sobre a Escola XYZ...</p>
  </section>

  <section id="cursos">
    <h2>Nossos Cursos</h2>
    <ul>
      <li>Curso 1</li>
      <li>Curso 2</li>
      <li>Curso 3</li>
    </ul>
  </section>

  <section id="contato">
    <h2>Entre em Contato</h2>
    <form action="enviar_email.php" method="post">
      <label for="nome">Nome:</label>
      <input type="text" id="nome" name="nome" required>
      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required>
      <label for="mensagem">Mensagem:</label>
      <textarea id="mensagem" name="mensagem" required></textarea>
      <button type="submit">Enviar</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2024 Escola XYZ. Todos os direitos reservados.</p>
  </footer>
</body>

</html>
