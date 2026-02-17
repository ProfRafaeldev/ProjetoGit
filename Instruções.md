#1. Prmeiro passo
Verificar se o git está instalado com o comando no cmd `git --version` em seguida abrir a pasta do projeto usando o Git Bash (é encontrado clicando com o botão direito na pasta)

---
#2. Segundo passo
Com a pasta aberta no Git Bash, usar o comando `git init` para introduzir a pasta do projeto no git e agora só resta logar seu perfil no git usando os seguintes comando>>>
```
git config --global user.email "seuemail@exemplo.com"
git config --global user.name "Seu Nome"
```
---
#3. Terceiro passo
Agora logado, vamos encaminhar os arquivos da pasta do projeto para o Github, usando os seguintes comando nessa ordem>>>
```
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/SeuNome/NomedoProjeto.git
git push -u origin main
```
---
#4. Quarto passo
Para encaminhar novos arquivos no projeto é necessário somente os seguintes comandos>>>
```git add .
git commit -m "second commit"
git push -u origin main
```
---
#5. Quinto passo
É possível fazer o push das suas alterações direto pelo VsCode, seguindo as seguintes instruções:\\
1.No VsCode acessar no canto esquerdo do programa, o icone *Controle do Código-Fonte*, toda vez que tiver uma alteração a ser aplicada aparecerá um número nesse icone.\\
2.Em seguida, com o mouse em cima do tópico com o nome *Alterações*, clique no icone `+` para aplicar todas as alterações no projeto.\\
3.Por fim, na caixa de texto acima do tópico *Alterações* escreva uma mensagem para nomear as alterações que serão aplicadas e confirme no botão logo abaixo, e depois sincronize as alterações no seu Github, que aparecerá no mesmo lugar que o botão de Confirmar.