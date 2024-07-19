Olã  hoje vamos falar de truques de GIT 

Como falaei nos topicos anteriores vamos assumir que estamos usando versionamento semantico que pode ser visto em https://semver.org/lang/pt-BR/
aqui podemos ver como é descrito o versionamento semantico, recomendo òestudo para que possamos discutir como trabalhar como boas praticas de versionamento.


aqui vamos usar as recomendações do https://www.conventionalcommits.org/pt-br/v1.0.0/#especifica%c3%a7%c3%a3o
que é uma convensao utilizada para padronizar os commits


1 - git config como configura um editor para editar os comentarios.
2 - Git add junto com o commit 
3 - Criar aliazes para facilitar a vida ex. git config --global alias.ac "commit -am"
4 - commando git log mostra o log dos commits completo mas se adiconar a propriedade --one-line ele mostra somente a primeira linha dos comentarios ainda se usarmos a propriedade --graph ele mostra o grafico da linhas de branch e podemos ainda usar a propriedade --decorate para mostrar o stream de
branch ou ainda --no-decorate para remover
5 - assim como no terminal o comando cd - volta para o ultimo diretório o comando git checkout - volta para a ultima branch 
6 - Agora vamos falar de stash 
