<!DOCTYPE html>
<html lang="pt-BR">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Linknabio</title>
    <style>
      * {
        margin: 0;
        padding: 0;
      }
      body {
        background-color: #f0f8ff;
        font-family: sans-serif;
        font-size: 1em;
        color: #59429d;
        margin-top: 2%;
        justify-content: center;
        display: flex;
        align-items: center;
        height: 100vh;
        margin: 0;
      }
      .conteiner {
        text-align: center;
        justify-content: center;
        box-shadow: 2px 2px 2px 2px rgba(0, 0, 0, 0.2);
        text-shadow: 1px 1px 1px 1px rgba(0, 0, 0, 0.5);
        margin: 10%;
        position: relative;
        border-radius: 10px;
        background: linear-gradient(to bottom, rgba(255,255,255,0.15) 0%, rgba(0,0,0,0.15) 100%), radial-gradient(at top center, rgba(255,255,255,0.40) 0%, rgba(0,0,0,0.40) 120%) #989898;
        background-blend-mode: multiply,multiply;
      }

      .card {
        width: 100%;
        background-color: white;
        box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
        overflow: hidden;
        border-radius: 8px;
        
      }

      .card-image {
        position: absolute;
        top: -40px;
        overflow: hidden;
      }

      .card-image img {
        transition: transform 0.4s;
        border-radius: 50%;
        overflow: hidden;
        width: 30%;
        max-width: 40%;
        max-height: 100vh;
      }

      .card-image:hover img {
        transform: scale(1.1);
      }

      .card-content {
        padding: 20px;
        margin-top: 20%;
      }

      h2 {
        margin: 0;
        font-size: 1.2rem;
        color: #333;
        font-family: helvetica, sans-serif;
      }

      p {
        margin: 10px 0;
        color: #333;
      }
      .links {
        display: flex;
        justify-content: center;
        gap: 15px;
      }
      .insta {
        width: 100px;
        max-width: 7%;
        max-height: 100px;
        margin-left: 3%;
      }
      .abilities{
        display: flex;
        flex-direction: column;
        gap: 10px;
        text-decoration: none;
        
      }
      .abilities a{
        text-decoration: none;
      }
      .logos{
        margin-bottom: 2%;
      }

      .link-acess{
        padding: 2% 5% 5% 2%;
      }
      a{
        color:white;
        text-decoration: none;
        padding: 2% 5% 5% 1%;
      }
      a:hover{
        background-color: #333;
        border-radius: 10px;
      }
    </style>
  </head>
  <body>
    <main class="conteiner">
      <div class="card-image">
        <img src="minha-imagem.jpg" alt="Imagem" />
      </div>
      <div class="card-content">
        <div class="name">
                <h2>Anderson Cassio Rodrigues</h2>
                <p>Desenvolvedor full stack / Designer / Social media</p>
            
            <div class="link-primary">
                <img src="logoinsta.png" class="insta" />
                <a href="https://www.instagram.com/anderson.rodrigues.gamer/">Pessoal</a>
                <img src="logoinsta.png" class="insta" />
                <a href="https://www.instagram.com/anderson.dev.web/">Comercial</a>
                
            </div>
        </div>

        <div class="logos"style="display: inline_block"><br>
            <img text-align="center" alt="And-Js" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg" >
            <img text-align="center" alt="And-Ts" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-plain.svg" >
            <img text-align="center" alt="And-React" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" >
            <img text-align="center" alt="And-HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg" >
            <img text-align="center" alt="And-CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg" >
            <img text-align="center" alt="And-Python" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" >
            <img text-align="center" alt="And-Csharp" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" >
        </div>


      </div>

      <div class="links">
        <div class="abilities">
          <a href="Orçamento.html" class="link-acess">Orçamentos</a>
          <a href="" class="link-acess">Meus Projetos</a>
          <a href="" class="link-acess">Website</a>
          <a href="" class="link-acess">Serviços de Mentoria</a>
        </div>

        <div class="abilities">
          <a href="https://api.whatsapp.com/send?phone=5548988563774&text=SUA_MENSAGEM"class="link-acess">Parcerias</a>
          <a href="https://github.com/AndersonRodrigues1" class="link-acess">Git hub</a>
          <a href="https://www.linkedin.com/in/anderson-rodrigues-055ba4226/" class="link-acess">Linkdin</a>
          <a href="https://www.twitch.tv/mr_brown_gameplays" class="link-acess">Streams & Videos</a>
        </div>
        
      </div>
    </main>
  </body>
</html>
