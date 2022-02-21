<p align="center">
  <a href="#Projeto">Projeto</a> ◦ 
  <a href="#Descrição">Descrição</a> ◦ 
  <a href="#Status">Status</a> ◦ 
  <a href="#Sobre">Sobre</a> ◦ 
  <a href="#Funcionalidades">Funcionalidades</a> ◦ 
  <a href="#Tecnologias">Tecnologias</a> ◦ 
  <a href="#Link">Link</a> ◦ 
  <a href="#Autor">Autor</a>
</p>

# Projeto
Validação de cadastro

# Descrição
Formulário com cinco campos para preenchimento do usuário: Nome, Sobrenome, CPF, Usuário, Senha e Repetir Senha.
Na parte superior do formulário estão as observações de como este deve ser preenchido. Caso alguma destas exigências
não seja atendida, aparecerá uma mensagem vermelha de alerta.
<div>
  <img src="assets/img/exemplo.png" alt="Formulário.">
</div>

# Status
Finalizado

# Sobre
Aplicação da Web desenvolvida com a finalidade de aprendizagem dos conteúdos de HTML5, CSS e JavaScript. 
O HTML da página é organizado da seguinte forma:
- head:
    - adiciona o título;
    - relaciona o arquivo de css chamado "style.css", que faz as configurações dos estilos.
- body
    - uma tag h1 para título;
    - uma tag ul para listas as exigências de preenchimento;
    - uma tag form com os cinco inputs;
    - um botão para o submit;
    - ao final faz a relação com os arquivos em JavaScript chamados "validaCPF.js" e "main.js".

O documento "main.js" possui as seguintes instruções:  
    - possui apenas uma classe denominada "ValidaFormulario";  
    - o evento de clique no submit é monitorado com "addEventListener" e seu comportamento padrão é prevenido, sendo direcionado para a função "handleSubmit";  
    - o método "handleSubmit" chama dois outros métodos: "camposSaoValidos()" e "senhasSaoValidas()";  
    - a verificação do CPF possui uma regra (para saber mais clique [aqui](https://dicasdeprogramacao.com.br/algoritmo-para-validar-cpf/)), para a qual foi criada a classe "ValidaCPF.js";  
    - caso os preenchimentos de todos os campos estão corretos, é exibida uma mensagem de alerta confirmando;  
    - ao final, é instanciada a classe com new "ValidaFormulario()".

# Funcionalidades
- [x] Campos de entrada de dados de Nome, Sobrenome, CPF, Usuário, Senha e Repetir Senha
- [x] Botão de iteração com o usuário para submeter os dados 
- [x] Mensagem de erro clara e personalizada para cada campo

# Link
A hospedagem foi feita utilizando o GitHub, que oferece serviço de hospedagem de sites.
- [URL do Site](https://epfolletto.github.io/validaCadastro/)

# Tecnologias
<div>
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white">  
<img src="https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=white">
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
<img src="https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white">
<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white">
</div>

# Autor
Evandro Paulo Folletto
<div>
  <a href="https://github.com/epfolletto" target="_blank"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" target="_blank"></a>
  <a href="https://www.linkedin.com/in/evandrofolletto/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
  <a href="https://www.youtube.com/evandropaulofolletto" target="_blank"><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" target="_blank"></a>
</div>