 <h1>CapSolver Extension</h1>
    <p>Este repositório contém uma extensão de navegador projetada para resolver automaticamente CAPTCHAs em páginas da web.</p>
    
  <h2>Instalação</h2>
  <h3>Clonar o Repositório</h3>
  <pre><code>git clone https://github.com/arth-inacio/capsolver_extension.git</code></pre>
  
  <h3>Carregar a Extensão no Navegador</h3>
  <h4>Google Chrome</h4>
  <ul>
      <li>Acesse <code>chrome://extensions/</code></li>
      <li>Ative o "Modo do desenvolvedor"</li>
      <li>Clique em "Carregar sem compactação" e selecione a pasta clonada</li>
  </ul>
  
  <h4>Mozilla Firefox</h4>
  <ul>
      <li>Acesse <code>about:debugging#/runtime/this-firefox</code></li>
      <li>Clique em "Carregar Temporariamente um Add-on" e selecione o arquivo <code>manifest.json</code></li>
  </ul>
  
  <h3>Configuração</h3>
  <p>Tambem é possível acessar a extensão copiando os arquivos diretamente na raiz do projeto e adicionar a extensão através do nome da pasta, sendo passada como parâmetro.</p>
  
  <h3>Configurar a Chave na Extensão</h3>
  <p>No diretório da extensão, edite o arquivo <code>assets/config.js</code>:</p>
  <pre><code>const apiKey = "SUA_CHAVE_API";</code></pre>
  
  <h2>Uso</h2>
  <p>A extensão detecta e resolve CAPTCHAs automaticamente em segundo plano.</p>
