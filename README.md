# Desafio avançado QA Instituto Atlântico

## Ecercício 1

Proposta

Praticar a adição, commit e push para o GitHub.

Passos para realização:

1. Conteúdo do projeto

-  Crie uma pasta com o nome do projeto (a sua escolha) e um arquivo chamado index.html
-  Adicione o seguinte conteúdo ao arquivo:
```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
   <title>Título da página</title>
   <meta charset="utf-8">
</head>
<body>
   <h1>Aqui vai um título</h1>
</body>
</html>
```
2. Subindo seu projeto para o GitHub

-  Crie um repositório em seu GitHubAbra o seu terminal de comando e adicione a origem remota e conecte seu projeto local com o GitHubVerifique as alterações do seu projeto e adicione ao fluxo de versionamentoFaça um commit com uma mensagem útil e na sequência, um push para o repositório remoto (GitHub)

3. Lidando com alterações

-  Abra a pasta do seu projeto, crie uma pasta chamada imagens, procure no Google por uma imagem de gato e salve dentro dessa nova pasta. Feito isso, abra seu arquivo index.html e adicione as seguintes modificações e salve o arquivo:
```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
<title>Fanpage de Gatinhos</title>
<meta charset="utf-8">
</head>
<body>
<h1>Perfil #catsoninstagram</h1>
<img src="images/nome_da_sua_imagem.jpg" />
</body>
</html
```
## Exercício 2

1. Clonando seu repositório
-   No seu perfil do GitHub na aba Repositories, crie um novo repositório clicando no botão New
-   Se desejar selecione a opção Add a README file para criar um arquivo de apresentação
-   Na página do seu repositório copie o link HTTPS ou SSH (se já houver configurado) utilizando o botão code
-   Abra o seu terminal na pasta em que deseja clonar o repositório ou utilize o comando cd no terminal pra chegar até lá
-   Utilize o comando git clone link-HTTPS/SSH

2. Criando sua nova branch & commit de mudanças
-   No terminal escreva o comando git checkout -b nome-da-sua-branch para criar a branch e mudar para ela diretamente
-   Abra o seu editor favorito e faça suas modificações, não se esqueça de salvar!
-   Voltando para o terminal e dentro da pasta do projeto, use o comando git add . para preparar todos os arquivos modificados para o commit
-   Agora use o comando git commit -m "aqui sua mensagem de commit" para fazer o commit das suas mudanças na branch
-   Para enviar seu commit para seu repositório remoto utilize o comando git push origin nome-da-sua-branch

3. Fazendo Pull Request (PR) & dando merge
-   No site do GitHub e na sua página do repositório na aba Pull requests clique no botão New pull request
-   Agora ajuste nas opções para qual branch você quer enviar as suas modificações (lado esquerdo) e a sua branch que estará enviando essas modificações (lado direito)
-   Observe se não há qualquer conflito, caso não haja confirme a PR!
-   Agora você só precisa fazer o merge, para isso na mesma aba do passo 1, clique na PR que deseja dar merge
-   Como não há nenhum conflito entre as branches (passo 3) é só clicar no botão Merge pull request
