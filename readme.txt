PUBLIQUE!

Fácil inserção de freesite - mantenha a sua!

Criar um site gratuito é muito fácil, você não precisa ser um programador para escrever ou publicar 
("inserir") seu site gratuito. Publicar um ou mais sites gratuitos também pode ser divertido, obter feedback, 
ver seu conteúdo sendo vinculado e publicado em índices ...

O conteúdo: freenet ainda precisa de mais conteúdo, se você ainda não tem um tópico para o seu freesite, escreva 
algo sobre o último programa de TV que você assistiu, seu vizinho, seu trabalho, um hobby, ... ele receberá leia e 
provavelmente melhore a qualidade geral do conteúdo.    

Simplicidade em mente

Não se preocupe com o design no momento, sites gratuitos interessantes não são necessariamente os mais bonitos.
A publicação do seu freesite consistirá em 3 etapas fáceis:
• criando uma imagem pequena
• escrevendo uma página html simples
• inserindo-o na freenet.

---------------------------------------------------------------------------------------------------------------------

1º Crie seu próprio "link de ativação"

Um "link de ativação" é uma pequena imagem associada ao seu site. Distinguindo e identificando seu freesite, 
esta pequena imagem também ajuda outros usuários da freenet a carregar seu freesite.

Especificações: para garantir que o link ativo seja exibido corretamente para outros usuários, existem algumas 
regras em relação ao formato e às dimensões do arquivo que você deve seguir; eles são descritos abaixo.

Especificações do "link de ativação"

Antes de continuar lendo, crie um diretório no seu computador para armazenar seus arquivos de freesite.

Sua imagem do "link de ativação" deve:
• ser nomeado activelink.png (deve ser salvo como um arquivo png)
• reside na sua pasta raiz do freesite
• mede 108x36 pixels

----------------------------------------------------------------------------------------------------------------------

2º Escreva sua primeira página

Escrever uma página para o freenet não é diferente de escrever uma página para a web comum. Esta página mostrará a base, 
mantendo o mais simples possível.

Requisitos: você só precisa de um editor de texto; se estiver executando o Microsoft Windows, poderá usar o Bloco de Notas. 
Use seu editor de texto favorito se você executar outra plataforma.

Página simples

Aqui está o texto mínimo que você deve escrever em qualquer página que pretende publicar:

<html xmlns="http://www.w3.org/1999/xhtml">
 <head>
  <title>My page  title</title>
  <meta name="description" content="page summary"/>
 </head>
 <body>
  <p>Hi world!</p>
 </body>
</html>

Copie e cole o texto exato no seu editor de texto e salve o arquivo como index.html no diretório do seu site gratuito. 
(ao lado de activelink.png)

Esta página é bastante simples, pois exibirá apenas “Olá, mundo!”, Mas é suficiente para mostrar todo o processo.
Os blocos "<p> </p>" são parágrafos, você pode adicionar quantos deles quiser / precisar.
Você pode visualizar sua página a qualquer momento: clique duas vezes no arquivo "index.html" e ele aparecerá no seu navegador.

-------------------------------------------------------------------------------------------------------------------------------

3º Publique seu site gratuito

Então, agora que você tem uma página nova e brilhante, é hora de inseri-la na freenet. A inserção de um freesite é feita usando 
software de terceiros incluído na instalação do freenet: “jSite”.

O jSite é um ótimo software java escrito por “Bombe”. Ele irá lidar com todas as tarefas complicadas para você, colocando sua 
publicação em site gratuito a poucos cliques de distância.

Você pode baixá-lo anonimamente no site oficial de jSite

Inicie o jSite

No windows, clique duas vezes no arquivo jSite.jar localizado em um diretório jSite no diretório de instalação do freenet.
Em outras plataformas, use "java -jar jSite.jar"

A janela principal do programa deve aparecer (clique para ampliar):

Crie um novo projeto

Como o jSite permite que você mantenha mais de um site gratuito por vez, você precisará criar um novo projeto: clique no 
botão "Adicionar projeto".

Agora, você deve preencher algumas informações do projeto:
• Nome: insira um nome para o projeto. por exemplo: HelloWorld
• Descrição: uma descrição pequena, para sua própria conveniência. por exemplo: minha primeira página
• Caminho local: esse é o diretório em que seus arquivos residem (clique no botão Procurar e aponte para diretório mantendo 
        os arquivos index.hmtl & activelink.png)
• Caminho: insira uma única palavra sem espaços aqui, isso aparecerá no seu URL do site gratuito.

Quando tudo estiver preenchido corretamente, pressione Avançar.

Insira seu freesite

A seguinte caixa de diálogo deve aparecer agora (clique para ampliar):

• Escolha “index.html” e marque “Arquivo padrão”
• Clique no botão "Inserir agora"

Após alguns minutos, uma mensagem será exibida, informando que o seu freesite foi inserido.

Clique no botão "Copiar URI para a área de transferência" e cole-o na barra de endereços do navegador, depois de 
"http://127.0.0.1:8888/", para que se pareça com: http://127.0.0.1:8888/USK@[..ashion,AQACAAE/word/1/

Você pode marcar este URL como favorito (de preferência usando os favoritos do Fproxy), pois é o seu URL de freesite. 
Outras publicações deste projeto jSite aumentarão o último número no URI (aka Edition)

------------------------------------------------------------------------------------------------------------------------------

4º Qual é o próximo?

Agora seu site gratuito está inserido, é hora de torná-lo conhecido, anunciando-o em diferentes lugares.

Existem várias maneiras de tornar seu site gratuito conhecido pela comunidade freenet, algumas delas são:
• publicar sua chave (todo o "USK @ [...] / word / 1 /") nas placas de "sites" da Frost ou FMS.
• publicá-lo em um índice na freenet (um site gratuito listando outros sites, alguns deles podem residir na sua página do Fproxy)
• adicionando seu link a um índice público
• ...

Mais detalhes sobre freesites e freenet

O site do FIP fornece informações detalhadas sobre freenet, aplicativos de terceiros, freesites ...