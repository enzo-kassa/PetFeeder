# PetFeeder
Um alimentador para pets com conexão via Google FireBase com acesso remoto e configuração de horários 
Nesse documento, irei passar etapa por etapa de como criar a FireBase, linkar a firebase ao APP e montar o Esp32 para receber 


Etapa 1 - Criar um projeto na FireBase:
  1.1 Acesse o site https://firebase.google.com e clique no botão Go To Console
  1.2 Crie um projeto
      1.2.1 Nomeie o projeto
      1.2.2 Ative a função ‘Google analytics for this project’
      1.2.3 Insira a sua região
      1.2.4 Clique em "Criar Projeto"
Etapa 2 - Criando a RealTime DataBase
  2.1 Dentro do projeto criado na etapa 1, acesse a categoria "Criação" na barra lateral esquerda
  2.2 Clique em RealTime DataBase
  2.3 Clique em criar Database 
  2.4 Na aba dados da RealTime DataBase, obtenha a URL
Etapa 3 - FireBase Keys
Para os componentes do projeto interegirem com o banco de dados, é necessario uma URL e um código Secret
  3.1 Acesse as configurações do projeto criado na etapa 1
  3.2 Acesse a aba "Contas de Serviço"
  3.3 Acesse "Secrets do DataBase"
  3.4 Copie o código "secrets"
Etapa 4 - Criando cópia do APP inventor e Cadastrando a FireBase
  4.1 Acesse https://ai2.appinventor.mit.edu/#5977753403850752
  4.2 Crie uma cópia do Projeto
  4.3 Dentro do Projeto, procure pelo elemento FirebaseDB1
  4.4 No elemento, preencha o campo "FireBase Url" com Url da etapa 3.
  4.5 Ainda no elemento, preencha o campo "Firebase TOKEN" com o "secrets" da etapa 2.4
  4.6 Na aba superior do APP Inventor, clique em Build e selecione a opção "Android APP(.apk)
Etapa 5 - Instalando o aplicativo
  5.1 Passe o arquivo do seu computador para seu celular
  5.2 Procure o arquivo no seu dispositivo móvel e instale
  5.3 O app exclusivo da sua FireBase já está pronto para uso
