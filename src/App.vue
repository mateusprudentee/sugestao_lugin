<template>
  <div id="app">
    <div id="main-container" class="container">
      <div id="topicos-container" class="topicos-anuncios">
        <div id="topico-principal" class="ultimo-topico">
          <div id="topico-header" class="header-topico">
            <div id="author-info" class="flex" style="display: flex; gap: 15px;">
              <div id="author-avatar" class="skin-logo"></div>
              <div id="author-details" class="header-postado">
                <p>Postado por yBlokzin</p>
                <div id="post-date" class="header-data">
                  <p>01 de Jun. de 2025</p>
                </div>
              </div>
            </div>
          </div>
          <div id="topico-banner" class="header-faixa">
            <div id="banner-content" class="header-faixa-badge">
              <p style="text-transform: uppercase;">Sugestão</p>
              <div id="banner-title" class="header-faixa-title">
                <p>Partidas Platinum</p>
              </div>
            </div>
          </div>
          <div id="topico-content" class="conteudo-topico">
    
            <span id="intro-text" style="color: #2b2b2b;">No universo competitivo do Minecraft, é enfrentado diariamente desafios para manter um ambiente justo e seguro para todos. As <span style="font-weight: bold;">Partidas Platinum</span> nasceram como nossa solução que visa minimizar e deixar uma jogabilidade mais segura, justa e equilibrada contra problemas como:</span>
            
            <ul id="problem-list" style="margin-left: 20px; color: #2b2b2b;">
              <li> Contas alternativas (alts) usadas para trapacear</li>
              <li> Jogadores banidos retornando com novas contas</li>
              <li> Uso indiscriminado de hacks e vantagens ilegais</li>
              <li> Dificuldade em identificar jogadores problemáticos</li>
            </ul>
            <span id="explanation-text" style="color: #2b2b2b;">A vinculação de um número de telefone auxilia na separação de jogadores com intenção explícita de trapacear e de quem possui interesse justo na jogabilidade. Por um número de telefone ser apenas possível vincular a uma conta e <u>não ter como utilizar o mesmo número em 2 contas diferentes</u>, jogadores devem verificar tal situação antes de trapacear em partidas. </span>

            <hr id="divider1" style="border: 1px solid #f0f0f0; margin: 20px 0;">
            
            <span id="process-title" style="color: #2b2b2b;">O processo para vincular um número de celular à conta é rápido e seguro:</span>
            <ol id="process-steps" style="margin-left: 20px; color: #2b2b2b;">
              <li>Digite no chat: <code style="background: #f5f5f5; padding: 2px 5px; border-radius: 3px;">/vincular +55 65 9 9372-9345</code> (substitua pelo seu número)</li>
              <li>Você receberá um SMS com código de 6 dígitos</li>
              <li>Digite o código no jogo para confirmar</li>
            </ol>
            
            <hr id="divider2" style="border: 1px solid #f0f0f0; margin: 20px 0;">
            
            <div id="benefits-grid" style="display: grid; grid-template-columns: repeat(2, 1fr); gap: 10px;">
              <div id="benefit1" style="background: #f0f9f0; padding: 10px; border-radius: 5px;">
                <strong style="color: #00a651;">🏆 Competitividade</strong>
                <p style="margin-top: 5px; color: #2b2b2b;">Partidas apenas com jogadores verificados, reduzindo trapaças em 85%</p>
              </div>
              
              <div id="benefit2" style="background: #f0f6ff; padding: 10px; border-radius: 5px;">
                <strong style="color: #0066cc;">💎 Recompensas</strong>
                <p style="margin-top: 5px; color: #2b2b2b;">Itens exclusivos e ranking Platinum visível para todos</p>
              </div>
              
              <div id="benefit3" style="background: #fff8f0; padding: 10px; border-radius: 5px;">
                <strong style="color: #e67e00;">⚡ Prioridade</strong>
                <p style="margin-top: 5px; color: #2b2b2b;">Acesso antecipado a eventos e suporte VIP</p>
              </div>
              
              <div id="benefit4" style="background: #fff0f5; padding: 10px; border-radius: 5px;">
                <strong style="color: #cc0066;">🛡️ Proteção</strong>
                <p style="margin-top: 5px; color: #2b2b2b;">Recuperação facilitada em caso de hackeamento</p>
              </div>
            </div>
            
            <hr id="divider3" style="border: 1px solid #f0f0f0; margin: 20px 0;">
          
            <div id="feature-highlight" style="margin-top: 40px; background: rgba(0, 232, 255, 0.05); padding: 25px; border-radius: 8px; border-left: 4px solid #00e8ff; box-shadow: 0 2px 8px rgba(0,0,0,0.05);">
              <strong id="highlight-title" style="font-size: 18px; color: #00e8ff; display: block; margin-bottom: 15px;">Partidas Platinum</strong>
              
              <div id="highlight-content" style="display: flex; gap: 20px; align-items: center; margin-bottom: 20px;">
               <img id="highlight-image" src="https://i.imgur.com/de1WXQu.png" alt="Competição Justa" style="width: 100%; max-width: 300px; height: auto; border-radius: 5px; box-shadow: 0 3px 10px rgba(0,0,0,0.1);">   
                <div id="highlight-text">
                  <p style="color: #444; line-height: 1.6;">
                    <strong>O problema enfrentado pelos jogadores:</strong> Nos últimos anos, foi observado um aumento significativo em contas alternativas usadas para burlar punições e trapacear. Partidas comuns se tornaram um campo minado onde jogadores honestos sofrem com:
                  </p>
                  <ul id="problem-list2" style="color: #555; margin-left: 20px; margin-top: 10px;">
                    <li>Hackers que criam múltiplas contas após serem banidos</li>
                    <li>Timeers que usam alts para inflar estatísticas</li>
                    <li>Boicotes organizados em partidas ranqueadas</li>
                  </ul>
                </div>
              </div>

              <div id="stats-container" style="background: rgba(0, 232, 255, 0.1); padding: 15px; border-radius: 5px; margin-top: 20px; border: 1px solid rgba(0, 232, 255, 0.3);">
                <div id="stats-grid" style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 15px; text-align: center;">
                  <div id="stat1">
                    <div style="font-size: 24px; color: #00e8ff; font-weight: bold;">70%</div>
                    <div style="font-size: 14px; color: #666;">Redução de hackers</div>
                  </div>
                  <div id="stat2">
                    <div style="font-size: 24px; color: #00e8ff; font-weight: bold;">3x</div>
                    <div style="font-size: 14px; color: #666;">Mais jogos equilibrados</div>
                  </div>
                  <div id="stat3">
                    <div style="font-size: 24px; color: #00e8ff; font-weight: bold;">80%</div>
                    <div style="font-size: 14px; color: #666;">Satisfação dos jogadores</div>
                  </div>
                </div>
              </div>

              <div id="ecosystem-section" style="margin-top: 25px;">
                <p style="color: #444; line-height: 1.6;">
                  Ao exigir verificação por celular, criamos um <strong style="color: #00e8ff;">ecossistema sustentável</strong> onde:
                </p>
                <ul id="ecosystem-list" style="color: #555; margin-left: 20px; margin-top: 10px; columns: 2; column-gap: 30px;">
                  <li>Jogadores se comprometem com fair play</li>
                  <li>Estatísticas refletem habilidade real</li>
                  <li>Recompensas vão para quem merece</li>
                  <li>Campeonatos têm credibilidade</li>
                  <li>A comunidade se autorregula</li>
                  <li>Investidores patrocinam mais eventos</li>
                </ul>
              </div>
            </div>

            <span id="security-note" style="color: #2b2b2b; display: block; margin: 20px 0;">Vinculando a conta em um único número de telefone garante segurança e confiabilidade nas partidas. Em um processo simples e seguro, os jogadores podem vincular um número de telefone. Vale ressaltar que não deve ser enviado SMS ou informações além disso para o número vinculado - apenas o de confirmação de número na conta. </span>

            <span id="footer-note" style="color: #2b2b2b; display: block; margin: 20px 0;">Tópico hospedado - será descontinuado em alguns dias. <br>Sugestão para o servidor Lugin - Servidor de Minecraft</span>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
/* Estilos base (mantidos da estrutura original) */
.ultimas-novidades-list {
  padding: 1.5em;
  margin-top: -40px;
  line-height: 20.5px;
  color: white;
  font-size: 16px;
}
#highlight-image {
  width: 200px;
  max-width: 300px;
  height: auto;
  display: block;
  margin: 0 auto;
}

@media (min-width: 600px) {
  #highlight-image {
    max-width: 100%;
    width: auto;
    max-height: 300px;
  }
}
.ultimas-novidades-title {
  font-size: 22px;
  padding: 1em;
  font-weight: 500;
  color: white;
}
.continuar-lendo {
  margin-top: 30px;
  text-align: center;
}
.btn {
    padding: 15px;
    font-size: 16px;
    border-radius: 5px;
    line-height: 16px;
    background-color: #0095fd;
    margin-bottom: 12px;
}
.btn-primary {
    color: #fff;
    background-color: #0095fd;
}
.btn {
    border-radius: 5px;
    border: 0;
    text-decoration: none !important;
    font-weight: 300;
}
.conteudo-topico {
    font-size: 17px;
    line-height: 1.6;
    color: rgb(74, 74, 74);
    padding: 25px;
}
.header-faixa-title {
  font-size: 26px;
    font-weight: bold;
    color: #fff;
    margin-top: -20px;
}
.header-faixa-badge {
    font-size: 18px;
    font-weight: 300;
    color: white;
    padding: 0.1em 1em;
}
.header-faixa {
  margin-top: 10px;
  width: 100%;
  height: 100px;
  background-color: #2b2b2b;
}
.header-data {
  color: gray;
  margin-top: -10px;
}
.header-postado {
    font-size: 16px;
    margin-top: 10px;
    color: #2b2b2b;
    margin-top: -0px;
    font-weight: normal;
}
.header-topico {
  padding: 15px;
}
.skin-logo {
    border-radius: 5px;
    width: 70px;
    background-image: url('https://cravatar.eu/helmavatar/yBlokzin/190.png');
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
    height: 70px;
}
.topicos-anuncios {
  max-width: 815px;
}
.ultimo-topico {
  box-shadow: 0px 3px 12px -3px rgba(0, 0, 0, 0.5);
  background: #fff;
    border-radius: 5px;
    width: 100%;
    margin-bottom: 30px;
    margin-top: 20px;
    height: 100%;
}
.promocao::before {
  background-image: url("https://i.imgur.com/vet5hUo.png");
}
.promocao {
   width: 815px;
   margin-top: 10px;
  height: 160px;
  position: relative;
  border-radius: 5px;
  overflow: hidden;
  background-color: #000;
  box-shadow: rgba(0, 0, 0, 0.5) 0px 3px 12px -3px;
  display: flex;
  align-items: flex-end;
  color: white;
  cursor: pointer;
}
.cards {
  display: flex;
  gap: 10px;
  margin-top: 20px;
}
.ultimas-novidades {
  position: relative;
  border-radius: 5px;
  box-shadow: 0px 3px 12px -3px rgba(0, 0, 0, 0.5);
  background: #fff;
    border-radius: 5px;
    width: 100%;
    background: #0095FD;
    height: 100%;
  width: 385px;
  height: 460px;
}
.noticia-grande,
.noticia-menor {
  position: relative;
  border-radius: 5px;
  overflow: hidden;
  background-color: #000;
  box-shadow: rgba(0, 0, 0, 0.5) 0px 3px 12px -3px;
  display: flex;
  align-items: flex-end;
  color: white;
  cursor: pointer;
}
.noticia-grande::before,
.noticia-menor::before,
.promocao::before {
  content: "";
  position: absolute;
  inset: 0;
  background-size: cover;
  background-position: center;
  transition: transform 0.4s ease;
  z-index: 0;
}
.noticia-grande::before {
  background-image: linear-gradient(rgba(0, 0, 0, 0) 0%, rgba(0, 0, 0, 0.65) 89%, rgba(0, 0, 0, 0.75) 100%),
    url("https://i.imgur.com/FdU5YNG.jpg");
}
.bedwars::before {
  background-image: linear-gradient(rgba(0, 0, 0, 0) 40%, rgba(0, 0, 0, 0.75) 100%),
    url("https://i.imgur.com/idG7Gr7.jpg");
}
.discord::before {
  background-image: linear-gradient(rgba(0, 0, 0, 0) 40%, rgba(0, 0, 0, 0.75) 100%),
    url("https://i.imgur.com/3G0EbXZ.jpg");
}
.noticia-grande:hover::before,
.noticia-menor:hover::before,
.promocao:hover::before {
  transform: scale(1.05);
}
.noticia-conteudo {
  position: relative;
  z-index: 1;
  padding: 1em;
  width: 100%;
}
.nosso-ip-subtitle-recomendacao {
  font-size: 16px;
  margin-top: 20px;
    display: block;
    color: rgb(75, 75, 75);
    font-weight: 300;
}
.nosso-ip-subtitle {
  font-size: 16px;
    display: block;
    color: gray;
    font-weight: 300;
}
.nosso-ip-title {
  font-size: 22px;
  font-weight: bold;
  margin-top: -10px;
  margin-bottom: 15px;
}
.nosso-ip-container {
  margin: 0 auto;
  padding: 50px;
  text-align: center;
}
.nosso-ip {
  width: 385px;
    height: 300px;
    background: white;
    border-radius: 3px;
    margin-top: 20px;
    box-shadow: 0px 3px 12px -3px rgba(0, 0, 0, 0.5);
}
.noticia-grande {
  width: 402px;
  height: 460px;
}
.noticia-menor {
  width: 400px;
  height: 225px;
}
.coluna-menores {
  display: flex;
  flex-direction: column;
  gap: 10px;
}
.categoria {
  font-size: 22px;
  font-weight: 300;
}
.titulo {
  text-transform: uppercase;
  font-size: 26px;
  font-weight: bold;
  margin-top: -20px;
}
.topicos-recentes {
    padding: 20px;
    margin-bottom: -30px;
    padding-bottom: 5px;
    background: #fff;
    color: #2b2b2b;
    border: none;
    font-size: 22px;
    font-weight: 100;
}
.container {
  max-width: 1015px;
  margin: 0 auto;
  justify-content: center;
  align-items: center;
  display: flex;
  flex-direction: column;
}
html, body {
  font-family: 'Ubuntu', sans-serif;
  font-weight: 400;
  height: 100%;
  margin: 0;
  padding: 0;
  background-color: #ECECEC;
  box-sizing: border-box;
}
#app, .app-container {
  min-height: 100vh;
  background-color: #ECECEC;
  margin: 0;
  font-family: 'Ubuntu', sans-serif;
  padding: 0;
}

/* Estilos responsivos por ID */
#app {
  width: 100%;
  overflow-x: hidden;
}

#main-container {
  width: 100%;
  padding: 0 15px;
  box-sizing: border-box;
}

#topicos-container {
  width: 100%;
  max-width: 815px;
}

#topico-principal {
  width: 100%;
  box-sizing: border-box;
}

#topico-header {
  padding: 15px;
}

#author-info {
  flex-direction: column;
  align-items: flex-start;
  gap: 10px !important;
}

#author-avatar {
  width: 50px;
  height: 50px;
}

#topico-banner {
  height: auto;
  padding: 15px 0;
}

#banner-title p {
  font-size: 22px;
  margin-top: 5px;
}

#topico-content {
  padding: 15px;
  font-size: 16px;
}

#benefits-grid {
  grid-template-columns: 1fr !important;
}

#highlight-content {
  flex-direction: column;
}

#highlight-image {
  max-width: 100% !important;
  margin-bottom: 15px;
}

#stats-grid {
  grid-template-columns: 1fr !important;
}

#ecosystem-list {
  columns: 1 !important;
}

/* Media Queries para ajustes específicos */
@media (min-width: 480px) {
  #author-info {
    flex-direction: row;
    align-items: center;
  }
  
  #banner-title p {
    font-size: 24px;
  }
  
  #stats-grid {
    grid-template-columns: repeat(3, 1fr) !important;
  }
}

@media (min-width: 600px) {
  #benefits-grid {
    grid-template-columns: repeat(2, 1fr) !important;
  }
  
  #highlight-content {
    flex-direction: row;
  }
  
  #ecosystem-list {
    columns: 2 !important;
  }
}

@media (min-width: 768px) {
  #author-avatar {
    width: 70px;
    height: 70px;
  }
  
  #banner-title p {
    font-size: 26px;
  }
  
  #topico-content {
    font-size: 17px;
    padding: 25px;
  }
}

@media (min-width: 992px) {
  #main-container {
    padding: 0;
  }
}
</style>

<script>
export default {
  data() {
    return {
    };
  },
  mounted() {  },
  methods: {

  },
  beforeUnmount() {
  },
};
</script>