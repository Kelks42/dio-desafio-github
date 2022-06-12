#  <span style="color:Violet">Repositório do Desafio de Projeto sobre Git/GitHub da Dio</span> :call_me_hand:





## Anotações do conteúdo da aula de Git/GitHub :writing_hand:

- Bloob - hash encripta no git e contém meta dados;

- Tree - as tree armazenam bloobs ou seja é uma crescente. O bloco sendo básico básico de composição, a Tree armazenando e apontados para tipos de blocos diferentes e os commits;

- O bloob é um que encapsula esse sistema de diretórios e ele é usado para apontar diretórios que contém arquivos também;

- O Commit é o objeto mais importante pois ele é o que vai juntar tudo, vai dar sentido a alteração que vc está fazendo. Então o commit aponta para uma árvore, aponta para um parente, ou seja, aponta para um commit realizado antes dele, o commit aponta para um autor e aponta para uma mensagem tb;

- Os commits tb possuem um shaun que é a geração desse rech identificador desses metadados (incriptação) desses arquivos;

- Comanndos para criar chavves no gir bach:  ssh-keygen -t ed25519 -c "usuário@gmail.com";

- git config --global user.email "email@usuário.com" - vincula um e-mail ao git (de preferência o mesmo do github);

- git config --global user.name "Nome Usuário" - vincula um usuário ao git (de preferência o mesmo do github);

- git config --list - mostra a lista de configurações do git, como usuário e email;

- git clone "link do repositório no github" - "clona" o repositório remoto do github para sua máquina;

- git init - criar repositório;

- git status - verificar estado dos arquivos (mostra quando é pra fazer commit, quando tá pronto pra enviar pro github, etc.);

- git add . (ou *) - muda o arquivo untracked e modified para a staged (área);

- git add "nome do arquivo" - adicionamos um arquivo no diretório;

- git commit -m "mensagem" - "commitamos" os arquivos da staged area e adicionamos uma mensagem que dará significância a eles;

- git push origin master (ou main) - empurra os arquivos para o github;

- git pull origin master (ou main) - traz os arquivos do github para nossa máquina;

- git remote -v - aponta o link do diretório remoto;

- ctrl + l - limpar a tela;

  

  #### Imagens:

  ![](C:\Users\profk\Downloads\Perkles.png)

  

  #### ![](C:\Users\profk\Downloads\Venilton.png)

  

  #### <span style="color:green">Links Úteis:</span>

  [Síntaxe Básica Markdown](https://www.markdownguide.org/basic-syntax/)

  

  

  

  

  

  

  

  :ok_hand::facepunch:







