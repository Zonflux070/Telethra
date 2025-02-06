<!--DOCTYPE html-->
<html lang="pt">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Apresentando Telethra</title>
  <style>
    /* Estilos Globais */
body {
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    background-color: #000000;
    color: #FFFFFF;
    margin: 0;
    padding: 0;
}

h1, h2 {
  font-family: 'Times New Roman', Times, serif;
}

header, main, section {
  width: 100%;
}

/* Cabeçalho */
header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #199319;
    margin: 0px;
    padding: 10px;
}

.logo {
  width: 40px;
  height: 40px;
  border: 1px solid #FFFFFFB8;
  border-radius: 30%;
}

.menu-icon {
    font-size: 30px;
    cursor: pointer;
}

/* Menu de Navegação */
.menu {
    position: fixed;
    top: 0;
    left: -60%;
    width: 60%;
    height: 100%;
    background-color: #23AF00A1;
    transition: 0.3s;
}

.menu ul {
    list-style: none;
    text-align: center;
    padding: 20px;
}

.menu ul li {
    margin: 20px 0;
}

.menu a {
  text-decoration: none;
  font-size: 18px;
  color: #FBFBFF;
}

.close-menu {
    background: none;
    border: none;
    font-size: 30px;
    text-align: right;
    cursor: pointer;
    color: white;
}

/* Seções */
.sect1 {
    background-image: url('721a8c97-be80-4991-af70-084a8ee73475.jpeg');
    background-repeat: no-repeat;
    background-size: 100% 100%;
    text-align: center;
    margin: 0px;
    padding: 20px;
}

.sect1 h1 {
  font-size: 30px;
  color: #00FF00;
}

.sect1 a {
  text-decoration: none;
  color: #FFFFFF;
  font-size: 18px;
  border: 1px solid #FFFFFF;
  padding: 1px 60px 1px 60px;
}

.sect2 {
  text-align: center;
}

.sect2 h2 {
  font-size: 15px;
}
/* secções 3, 4, 5 e 9*/
.sect3, .sect4, .sect9 {
    display: flex;
    justify-content: space-between;
}
/* secção 3*/
.poesia-texto {
  width: 48%;
  background: url('513fd248-8d5b-4f3b-961b-c849b2b10927.jpeg');
  background-repeat: no-repeat;
  background-size: 100% 100%;
}

.poesia-imagem {
  width: 48%;
  background: url('68c708e1-b972-429c-8057-27af71f10ec5.jpeg');
  background-repeat: no-repeat;
  background-size: 100% 100%;
}
/* secção 4*/
.slogan {
  width: 50%;
  font-size: 25px;
  text-align: center;
  background: url('8440efa9-7f3c-433f-b4d6-d5d8e383e941.jpeg');
  background-repeat: no-repeat;
  background-size: 100% 100%;
}
/* secção 5*/
#curioso {
  width: 200px;
  height: 400px;
  margin: 20px 1px 1px 20px;
}
/* secção 9*/
.sect9 {
  background-image: url('75f95493-157e-46cd-b986-ead2a0e8d3fd.jpeg');
  background-repeat: no-repeat;
  background-size: 100% 100%;
}
.planeta-imagem {
  width: 48%;
  background-image: url('dd0f70e4-5bb6-450e-beb6-8da5b6208765.jpeg');
  background-repeat: no-repeat;
  background-size: 100% 100%;
}
.sect9 p {
  text-align: justify;
  text-shadow: 4px 4px 2px #000000;
}
/* secção 6*/
.sect6 {
  margin: 0px;
  padding: 20px;
  text-shadow: 4px 4px 1px #000000;
  text-align: center;
  background: url('a6035d6e-b3be-46c2-b71e-7c828fdd70e2.jpeg');
  background-repeat: no-repeat;
  background-size: 100% 100%;
}

.sect6 a {
  color: #FFFFFF;
  font-size: 18px;
}
/* secção 7*/
.sect7 a {
  color: #FFFFFF;
  font-size: 18px;
}
/* secção 8*/
.sect8 {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 0px;
}

.sect8 img {
    width: 100%;
    height: 100%;
}

/* Formulário */
form {
    display: flex;
    flex-direction: column;
}

.mensagem-sucesso {
  display: none;
  color: #FFFFFF;
  font-size: 25px;
  padding: 25px;
  border: 1px solid #FFFFFF;
  background-color: #54C25482;
}

.input-duplo {
    display: flex;
    justify-content: space-between;
}

input, textarea, button {
    margin: 5px 0;
    padding: 10px;
    width: 100%;
}

button {
    background-color: green;
    color: white;
    border: none;
}

/* Rodapé */
footer {
    font-size: 10px;
    font-family: monospace;
    text-align: center;
    background-color: gray;
    padding: 10px;
}

footer a {
  font-size: 10px;
  color: #FBFBFF;
}
  </style>
</head>
<body>
  <!-- Cabeçalho -->
  <header>
    <div>
      <img class="logo" src="playlistCropperBoomPlayer.jpg">
    </div>
    <div class="menu-icon" onclick="toggleMenu()">☰</div>
  </header>
  <!-- Menu de Navegação -->
  <nav id="menu" class="menu">
    <button class="close-menu" onclick="toggleMenu()">✖</button>
    <ul>
      <li><a href="#">Pág 1</a></li>
      <li><a href="#">Pág 2</a></li>
      <li><a href="#">Pág 3</a></li>
    </ul>
  </nav>
  <!-- Corpo da Página -->
  <main>
    <section class="sect1">
      <h1>Zônflux, Apresenta: Telethra</h1>
      <a href="#">Curio</a>
    </section>
    <section class="sect2">
      <h2>Sobre Telethra</h2>
      <p>Telethra, um continente de inovação deslumbrante, destaca-se por suas tecnologias incrivelmente avançadas. Ela se encontra integrada a Zenus, um fascinante planeta-ilha que orbita em harmonia dentro de um sistema solar habitado por três mundos distintos.</p>
    </section>
    <section class="sect3">
      <div class="poesia-texto">
        <p>Telethra é um continente onde as inteligências artificiais assumem o protagonismo, controlando 90% dos serviços e trabalhos. Em vez de ministérios tradicionais para monitorar água, energia ou economia, cada setor é gerido por uma IA altamente especializada. A segurança pública, englobando funções como polícia e bombeiros, é coordenada por uma única e sofisticada IA, conhecida como O Sentinela.<br /><br />Enquanto as IAs dominam os serviços que demandam lógica e precisão, como gestão, transporte e análise de dados, deixam para os humanos as profissões que envolvem criatividade, emoção e empatia, como advocacia, música e outras artes. Essa divisão harmoniosa de responsabilidades permite que as pessoas tenham mais liberdade para tomar decisões e mais tempo para aproveitar a vida com suas famílias.<br /><br />Essa dinâmica não apenas redefine o trabalho e os laços sociais, mas também molda um mundo onde humanos e máquinas coexistem em equilíbrio, cada um desempenhando papéis complementares.</p>
      </div>
      <div class="poesia-imagem"></div>
    </section>
    <section class="sect4">
      <div class="slogan"><p>"Uma terra de mistérios"</p></div>
      <div>
        <p>Telethra, como um continente futurista e avançado, possui uma estrutura organizacional semelhante à nossa, dividida em múltiplos níveis urbanos para facilitar a administração e o funcionamento social:<br /><br />Continente: A unidade maior, representando a totalidade de Telethra.<br /><br />Zonas: Equivalentes aos nossos países, cada uma com sua própria identidade cultural, econômica e tecnológica.<br /><br />Cidades: Correspondiam aos estados, funcionando como grandes centros administrativos e estratégicos dentro das Zonas.<br /><br />Municípios: Subdivisões das cidades, atuando como áreas de governança local.<br /><br />Bairros: Áreas dentro dos municípios, organizadas de forma a facilitar a vida comunitária e os serviços.<br /><br />Quarteirões: As menores unidades territoriais, representando áreas residenciais ou comerciais compactas e integradas.<br /><br />Essa hierarquia não é apenas funcional, mas também personalizada para atender às necessidades específicas de Telethra, garantindo uma administração eficiente e uma convivência harmoniosa entre humanos e inteligências artificiais.</p>
      </div>
    </section>
    <section class="sect5">
      <img id="curioso" src="ac78d3d5-7845-4707-b64a-817dceebc347.jpeg" alt="Imagem da Região">
      <p>Você sabia que a Zônflux não é apenas a base de energia em Telethra, mas também um elemento vivo que reage de forma única às emoções humanas? Alguns dizem que a Zônflux tem uma ligação direta com os segredos mais profundos do universo, podendo até mesmo revelar as origens do tempo e do espaço. Quer saber mais sobre como essa energia molda não apenas os habitantes, mas todo o equilíbrio do cosmos? Então continue conosco nesta jornada!</p>
    </section>
    <section class="sect6">
      <p>Telethra é um continente futurista de tirar o fôlego, onde o desenvolvimento tecnológico se mistura à singularidade de sua localização. Suspenso no espaço, o céu de Telethra é eternamente noturno, pontilhado por estrelas que parecem sussurrar histórias de um universo infinito.<br /><br />A inovação está presente até mesmo nos transportes: os automóveis flutuam graciosamente, dispensando rodas. As estradas, projetadas com tecnologia avançada, geram campos magnéticos que interagem com os sistemas dos veículos, criando uma mobilidade suave e silenciosa.<br /><br />Além disso, os habitantes de Telethra possuem uma conexão única com a energia chamada Zônflux. Alimentados pelo Astroflux, eles têm a habilidade de depositar Zônflux em outras pessoas, criando um elo profundo entre depositador e depositado. Esse vínculo vai além do físico, permitindo que leiam pensamentos e emoções daqueles de outras raças, embora permaneçam incapazes de acessar os segredos das mentes de seus próprios semelhantes.<br /><br />Esse equilíbrio entre tecnologia, energia e mistério faz de Telethra um lugar único, onde ciência e laços espirituais coexistem em perfeita harmonia.</p>
      <a href="#">Zenus</a>
    </section>
    <section class="sect7">
      <p>Telethra nasceu como consequência de um evento catastrófico ocorrido em Zenus, que culminou na criação de uma nova forma de Zônflux, conhecida como Astroflux. Esse acidente mudou para sempre o equilíbrio das forças no universo, dando origem a duas espécies distintas.<br /><br />A primeira delas desenvolveu habilidades extraordinárias, como superforça, velocidade impressionante, resistência sobre-humana e a capacidade de disparar raios laser pelos olhos. A segunda espécie, conhecida como os Telethrans, adquiriu a habilidade única de ler os pensamentos de outras raças, tornando-se mestres da empatia e do entendimento psíquico.<br /><br />Porém, Telethra ainda não existia como território unificado. Somente após a sangrenta Guerra dos Mundos, que marcou a luta pela sobrevivência e soberania, o continente foi estabelecido como um território independente. Desde então, Telethra passou por eras de reconstrução e inovação, evoluindo para o extraordinário mundo que conhecemos hoje, um símbolo de avanço e equilíbrio entre força, intelecto e conexão espiritual.</p>
      <a href="#">Astroflux</a>
    </section>
    <section class="sect8">
      <img src="01b44592-7292-4fe0-991a-b6df6f8dee01.jpeg" alt="Imagem 1">
      <img src="bc9f03cb-c7dd-4058-849d-4d44b0e470ec.jpeg" alt="Imagem 2">
      <img src="f6d35bc3-7523-4ef5-b770-7ac554160fd2.jpeg" alt="Imagem 3">
      <img src="5fabed52-a7e4-41eb-a9f3-79fa91ecc429.jpeg" alt="Imagem 4">
    </section>
    <section class="sect9">
      <p>Telethra, embora seja o continente mais avançado tecnologicamente do universo, enfrenta um grande desafio: a ausência de recursos naturais. No passado, seus antepassados exploraram de forma descontrolada os recursos não renováveis do território, levando ao esgotamento total. Atualmente, para sustentar sua sociedade e economia, Telethra depende da extração legal de recursos dos planetas vizinhos, com os quais mantém acordos diplomáticos e comerciais rigorosos.<br /><br />Esse histórico motivou os habitantes de Telethra a buscarem alternativas inovadoras, desenvolvendo tecnologias que priorizam a eficiência e o respeito pela natureza. Um exemplo brilhante dessa mentalidade é o WochWork (em português, "Relógio de Trabalho"), um dispositivo multifuncional que integra as funções de telemóvel, computador, TV, cartão de crédito e caderno em um único aparelho compacto e sustentável.<br /><br />Além disso, os habitantes de Telethra aboliram o uso de papel, em um esforço para proteger as árvores e preservar o equilíbrio ecológico. Essa postura reflete a filosofia do continente: aprender com os erros do passado para construir um futuro harmonioso entre tecnologia, sustentabilidade e respeito ao meio ambiente.</p>
      <div class="planeta-imagem"></div>
    </section>
    <section class="sect10">
      <h3>O que Achaste:</h3>
      <p>Cada palavra que escrevemos ganha vida através de vocês. Suas vozes, suas emoções e suas interpretações fazem desta história algo maior do que imaginamos. Queremos saber: o que essa jornada desperta em vocês? Compartilhem seus pensamentos, pois é graças a vocês que continuamos a criar.</p>
      <div id="mensagem-sucesso" class="mensagem-sucesso"></div>
      <form id="formulario">
        <input type="text" id="nome" placeholder="Nome">
        <input type="email" id="email" placeholder="E-mail">
        <div class="input-duplo">
          <input type="date" id="data">
          <input type="tel" id="contato" placeholder="Contato">
        </div>
        <textarea id="mensagem" placeholder="Comentário ou Mensagem"></textarea>
        <button type="submit">Enviar</button>
      </form>
    </section>
  </main>
  <!-- Rodapé -->
  <footer>
    <p>A você, visitante, nosso mais sincero agradecimento por embarcar nesta jornada fascinante sobre o Espectro. Sua curiosidade e dedicação nos motivam a continuar explorando os mistérios deste universo tão único. Esperamos que cada secção lida tenha despertado sua imaginação e lhe oferecido momentos de reflexão e inspiração.</p>
    <a href="#">Bóris</a>
    <p>© 2025 Universo Zônflux. Todos os direitos reservados.</p>
  </footer>
    <script>
      alert('Usa o Modo Desktop')

function toggleMenu() {
    const menu = document.getElementById('menu');
    if (menu.style.left === "0px") {
        menu.style.left = "-60%";
        document.removeEventListener("click", closeMenuOnClickOutside);
    } else {
        menu.style.left = "0px";
        setTimeout(() => {
            document.addEventListener("click", closeMenuOnClickOutside);
        }, 100);
    }
}

function closeMenuOnClickOutside(event) {
    const menu = document.getElementById('menu');
    const menuIcon = document.querySelector(".menu-icon");

    if (!menu.contains(event.target) && !menuIcon.contains(event.target)) {
        menu.style.left = "-60%";
        document.removeEventListener("click", closeMenuOnClickOutside);
    }
}

document.getElementById("formulario").addEventListener("submit", function(event) {
    event.preventDefault();

    let nome = document.getElementById("nome").value;
    let email = document.getElementById("email").value;
    let data = document.getElementById("data").value;
    let contato = document.getElementById("contato").value;
    let mensagem = document.getElementById("mensagem").value;

    if (nome && email && data && contato && mensagem) {
        let dados = {
            nome,
            email,
            data,
            contato,
            mensagem
        };

        // Armazena os dados no LocalStorage
        localStorage.setItem("formularioTelethra", JSON.stringify(dados));

        document.getElementById("mensagem-sucesso").innerText = "Agradecemos pelo seu feedback";
        document.getElementById("mensagem-sucesso").style.display = "block";

        setTimeout(() => {
            document.getElementById("mensagem-sucesso").style.display = "none";
        }, 3000);

        document.getElementById("formulario").reset();
    } else {
        alert("Preencha todos os campos!");
    }
});
    </script>
</body>
</html>
