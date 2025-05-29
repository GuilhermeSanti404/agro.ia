# agro.ia
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Conexão Viva: Campo e Cidade Juntos</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <div class="intro">
      <h1>Conexão Viva</h1>
      <p>Festejando a conexão entre o campo e a cidade</p>
      <a href="#cidade" class="btn">Explorar a Conexão</a>
    </div>
  </header>

  <main>
    <section id="cidade" class="bloco cidade">
      <h2>Vida na Cidade</h2>
      <p>A cidade pulsa com movimento, tecnologia e serviços. Mas por trás de tudo isso, há o campo fornecendo alimentos, cultura e energia.</p>
      <ul>
        <li>Alimentos frescos das fazendas</li>
        <li>Transporte e logística rural</li>
        <li>Feiras e produtos artesanais</li>
        <section class="plataforma">
  <div class="chao"></div>
  <div class="personagem"></div>
</section>
      </ul>
    </section>

    <section class="bloco campo">
      <h2>Vida no Campo</h2>
      <p>O campo é o berço da produção, da natureza e da tranquilidade. Mas também se beneficia do conhecimento, da educação e da tecnologia urbana.</p>
      <ul>
        <li>Educação a distância</li>
        <li>Tratores inteligentes e conectividade</li>
        <li>Inovações para a agricultura</li>
      </ul>
    </section>

    <section class="bloco projetos">
      <h2>Projetos que Unem</h2>
      <div class="cards">
        <div class="card">
          <h3>Feiras Agrícolas</h3>
          <p>Eventos nas cidades com produtos locais do campo.</p>
        </div>
        <div class="card">
          <h3>Hortas Urbanas</h3>
          <p>Espaços comunitários urbanos com cultivo de alimentos.</p>
        </div>
        <div class="card">
          <h3>Conectividade Rural</h3>
          <p>Internet e tecnologia melhorando a vida no campo.</p>
        </div>
      </div>
    </section>

    <section class="bloco depoimentos">
      <h2>Depoimentos</h2>
      <blockquote>
        "Na cidade, valorizo cada alimento que vem do campo."
        <footer>— Joana, moradora urbana</footer>
      </blockquote>
      <blockquote>
        "Com internet no campo, posso estudar e vender online."
        <footer>— Lucas, jovem agricultor</footer>
      </blockquote>
    </section>
  </main>
<footer>
    <div class="creditos">
      <h3>Créditos</h3>
      <p>Desenvolvido por:</p>
      <ul> 
        <li>Guilherme Santi</li>
        <li>Luan Rafael</li>
        <li>Gustavo Miguel</li>
        <li>Nathan Haimo</li>
      </ul>
    </div>

  <footer>
    <p>Projeto desenvolvido para o Concurso Agrinho 2025</p>
    <p>&copy; 2025 - Conexão Viva</p>
  </footer>
</body>
</html>

<section class="ia">
  <h2>Converse com a IA Viva</h2>
  <p>Simule uma conversa com a IA do site. Escolha uma pergunta:</p>

  <div class="pergunta">
    <input type="radio" id="pergunta1" name="chat">
    <label for="pergunta1">O que você sabe sobre o campo?</label>
    <div class="resposta">
      <p>O campo é a base da produção de alimentos, cultura e tradições. Ele se conecta à cidade através da logística e da tecnologia.</p>
    </div>
  </div>

  <div class="pergunta">
    <input type="radio" id="pergunta2" name="chat">
    <label for="pergunta2">Como a cidade ajuda o campo?</label>
    <div class="resposta">
      <p>A cidade contribui com tecnologia, educação e acesso a mercados que valorizam os produtos do campo.</p>
    </div>
  </div>

  <div class="pergunta">
    <input type="radio" id="pergunta3" name="chat">
    <label for="pergunta3">Como posso ajudar na conexão entre campo e cidade?</label>
    <div class="resposta">
      <p>Você pode valorizar produtos locais, participar de feiras e apoiar iniciativas de educação e conectividade no meio rural.</p>
    </div>
  </div>
</section>


/* style.css */

:root {
  --cor-campo: #8BC34A;
  --cor-cidade: #607D8B;
  --cor-texto: #333;
  --cor-fundo: #f4f4f4;
  --fonte: 'Segoe UI', sans-serif;
}

body {
  margin: 0;
  font-family: var(--fonte);
  background-color: var(--cor-fundo);
  color: var(--cor-texto);
  scroll-behavior: smooth;
}

header {
  height: 100vh;
  background: linear-gradient(to right, var(--cor-cidade) 50%, var(--cor-campo) 50%);
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  color: white;
}

.intro h1 {
  font-size: 3rem;
  margin-bottom: 0.5rem;
}

.intro p {
  font-size: 1.2rem;
}

.btn {
  margin-top: 1rem;
  padding: 0.8rem 1.5rem;
  background-color: white;
  color: var(--cor-cidade);
  text-decoration: none;
  font-weight: bold;
  border-radius: 8px;
  transition: 0.3s;
}

.btn:hover {
  background-color: var(--cor-campo);
  color: white;
}

main {
  padding: 2rem;
}

.bloco {
  margin: 2rem 0;
  padding: 2rem;
  border-radius: 12px;
  background-color: white;
  box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

.cidade {
  border-left: 10px solid var(--cor-cidade);
}

.campo {
  border-left: 10px solid var(--cor-campo);
}

.cards {
  display: flex;
  flex-wrap: wrap;
  gap: 1rem;
  justify-content: center;
}

.card {
  flex: 1 1 250px;
  padding: 1rem;
  border-radius: 10px;
  background-color: #e8f5e9;
  box-shadow: 0 0 5px rgba(0,0,0,0.1);
  transition: transform 0.3s ease;
}

.card:hover {
  transform: scale(1.05);
}

.depoimentos blockquote {
  font-style: italic;
  margin: 1rem 0;
  padding-left: 1rem;
  border-left: 5px solid var(--cor-campo);
}

footer {
  text-align: center;
  background-color: var(--cor-cidade);
  color: white;
  padding: 1rem;
}

@media (max-width: 768px) {
  header {
    flex-direction: column;
    text-align: center;
    background: var(--cor-campo);
  }

  .cards {
    flex-direction: column;
  }

  .btn {
    width: 80%;
  }
}

/* style.css */

:root {
  --cor-campo: #8BC34A;
  --cor-cidade: #607D8B;
  --cor-texto: #333;
  --cor-fundo: #f4f4f4;
  --fonte: 'Segoe UI', sans-serif;
}

body {
  margin: 0;
  font-family: var(--fonte);
  background-color: var(--cor-fundo);
  color: var(--cor-texto);
  scroll-behavior: smooth;
}

header {
  height: 100vh;
  background: linear-gradient(to right, var(--cor-cidade) 50%, var(--cor-campo) 50%);
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  color: white;
}

.intro h1 {
  font-size: 3rem;
  margin-bottom: 0.5rem;
}

.intro p {
  font-size: 1.2rem;
}

.btn {
  margin-top: 1rem;
  padding: 0.8rem 1.5rem;
  background-color: white;
  color: var(--cor-cidade);
  text-decoration: none;
  font-weight: bold;
  border-radius: 8px;
  transition: 0.3s;
}

.btn:hover {
  background-color: var(--cor-campo);
  color: white;
}

main {
  padding: 2rem;
}

.bloco {
  margin: 2rem 0;
  padding: 2rem;
  border-radius: 12px;
  background-color: white;
  box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

.cidade {
  border-left: 10px solid var(--cor-cidade);
}

.campo {
  border-left: 10px solid var(--cor-campo);
}

.cards {
  display: flex;
  flex-wrap: wrap;
  gap: 1rem;
  justify-content: center;
}

.card {
  flex: 1 1 250px;
  padding: 1rem;
  border-radius: 10px;
  background-color: #e8f5e9;
  box-shadow: 0 0 5px rgba(0,0,0,0.1);
  transition: transform 0.3s ease;
}

.card:hover {
  transform: scale(1.05);
}

.depoimentos blockquote {
  font-style: italic;
  margin: 1rem 0;
  padding-left: 1rem;
  border-left: 5px solid var(--cor-campo);
}

footer {
  text-align: center;
  background-color: var(--cor-cidade);
  color: white;
  padding: 1rem;
}

/* Animação estilo jogo de plataforma */

.plataforma {
  position: relative;
  overflow: hidden;
  background: linear-gradient(#87ceeb, #fff);
  height: 200px;
  margin-top: 3rem;
  border-radius: 12px;
  box-shadow: 0 0 10px rgba(0,0,0,0.2);
}

.chao {
  position: absolute;
  bottom: 0;
  height: 50px;
  width: 100%;
  background-color: #4CAF50;
}

.personagem {
  position: absolute;
  bottom: 50px;
  left: 0;
  width: 50px;
  height: 50px;
  background-color: orange;
  border-radius: 50%;
  animation: andar 5s linear infinite, pular 1s ease-in-out infinite;
}

@keyframes andar {
  0% { left: -50px; }
  100% { left: 100%; }
}

@keyframes pular {
  0%, 100% { transform: translateY(0); }
  50% { transform: translateY(-30px); }
}

@media (max-width: 768px) {
  header {
    flex-direction: column;
    text-align: center;
    background: var(--cor-campo);
  }

  .cards {
    flex-direction: column;
  }

  .btn {
    width: 80%;
  }
}

.ia {
  margin: 2rem 0;
  padding: 2rem;
  background-color: white;
  border-left: 10px solid var(--cor-campo);
  border-radius: 12px;
  box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

.ia h2 {
  margin-bottom: 1rem;
  font-size: 1.8rem;
  color: var(--cor-campo);
}

.ia p {
  font-size: 1rem;
  margin-bottom: 1rem;
}

.pergunta {
  margin-bottom: 1rem;
}

.pergunta input[type="radio"] {
  display: none;
}

.pergunta label {
  display: block;
  background-color: #e8f5e9;
  padding: 1rem;
  border-radius: 8px;
  cursor: pointer;
  transition: background-color 0.3s ease;
  font-weight: bold;
  border: 2px solid var(--cor-campo);
}

.pergunta label:hover {
  background-color: #dcedc8;
}

.resposta {
  max-height: 0;
  overflow: hidden;
  opacity: 0;
  transform: scaleY(0.95);
  transition: all 0.4s ease;
  padding-left: 1rem;
  margin-top: 0.5rem;
  border-left: 4px solid var(--cor-cidade);
}

.pergunta input:checked + label + .resposta {
  max-height: 500px;
  opacity: 1;
  transform: scaleY(1);
}

.ia {
  margin: 2rem 0;
  padding: 2rem;
  background-color: white;
  border-left: 10px solid var(--cor-campo);
  border-radius: 12px;
  box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

.ia h2 {
  margin-bottom: 1rem;
  font-size: 1.8rem;
  color: var(--cor-campo);
}

.ia p {
  font-size: 1rem;
  margin-bottom: 1rem;
}

.pergunta {
  margin-bottom: 1rem;
}

.pergunta input[type="radio"] {
  display: none;
}

.pergunta label {
  display: block;
  background-color: #e8f5e9;
  padding: 1rem;
  border-radius: 8px;
  cursor: pointer;
  transition: background-color 0.3s ease;
  font-weight: bold;
  border: 2px solid var(--cor-campo);
  color: var(--cor-texto);
}

.pergunta label:hover {
  background-color: #dcedc8;
}

.resposta {
  max-height: 0;
  overflow: hidden;
  opacity: 0;
  transform: scaleY(0.95);
  transition: all 0.4s ease;
  padding-left: 1rem;
  margin-top: 0.5rem;
  border-left: 4px solid var(--cor-cidade);
  color: var(--cor-texto); /* agora o texto aparece corretamente */
}
