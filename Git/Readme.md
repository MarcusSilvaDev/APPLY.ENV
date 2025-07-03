# Instalação
 - Baixar [.gitconfig](https://github.com/Lowpoc/APPLY.ENV/blob/master/Git/.gitconfig).
 - Adicionar a nova configuração  utilizando commando ``git config --global -e``
 - Alterar o campo Email e User do .config costumizado
 - Fechar e Abrir terminall
 
Agora você terás estes alias disponiveis lá:
   ```bash
commit-style = "!f() { git commit -m \"🎨 ${1}\"; }; f"                 #🎨 melhorar a estrutura/formato do código;
commit-feature = "!f() { git commit -m \"🆕 ${1}\"; }; f"               #🆕 incluir nova funcionalidade/código;
commit-perf = "!f() { git commit -m \"🐎 ${1}\"; }; f"                  #🐎 melhorar a performance;
commit-leak = "!f() { git commit -m \"🚰 ${1}\"; }; f"                  #🚰 memory leaks;
commit-doc = "!f() { git commit -m \"📝 ${1}\"; }; f"                   #📝 escrever alguma documentação;
commit-log = "!f() { git commit -m \"✏️ ${1}\"; }; f"                   #✏️ adicionar log na aplicação;
commit-fix = "!f() { git commit -m \"🐞 ${1}\"; }; f"                   #🐞 corrigir um bug;
commit-fix-ci = "!f() { git commit -m \"💚 ${1}\"; }; f"                #💚 corrigir uma build no CI;
commit-tests = "!f() { git commit -m \"✅ ${1}\"; }; f"                 #✅ adicionar testes;
commit-deps-up = "!f() { git commit -m \"⬆️ ${1}\"; }; f"               #⬆️ upgrade em dependências;
commit-deps-down = "!f() { git commit -m \"⬇️ ${1}\"; }; f"             #⬇️ downgrade em dependências;
commit-fix-lint = "!f() { git commit -m \"👕 ${1}\"; }; f"              #👕 remover problemas com linter;
commit-fix-typo = "!f() { git commit -m \"🐽 ${1}\"; }; f"              #🐽 corrigir algo simples (ex. typo, nome de variável...);
commit-omg = "!f() { git commit -m \"💩 ${1}\"; }; f"                   #💩 m***a forte!
commit-security = "!f() { git commit -m \"🔒 ${1}\"; }; f"               #🔒 melhorar a segurança;
commit-die = "!f() { git commit -m \"🔥 ${1}\"; }; f"                    #🔥 remover códigos ou arquivos;
commit-help = "!f() { echo '🎨 commit-style => melhorar a estrutura/formato do código'; echo '🆕 commit-feature => incluir nova funcionalidade/código'; echo '🐎 commit-perf => melhorar a performance'; echo '🚰 commit-leak => memory leaks'; echo '📝 commit-doc => escrever alguma documentação'; echo '✏️ commit-log => adicionar log na aplicação'; echo '🐞 commit-fix => corrigir um bug'; echo '🔥 commit-die => remover códigos ou arquivos'; echo '💚 commit-fix-ci => corrigir uma build no CI'; echo '✅ commit-tests => adicionar testes';  echo '🔒 commit-security => melhorar a segurança';  echo '⬆️ commit-deps-up => upgrade em dependências';  echo '⬇️ commit-deps-down => downgrade em dependências';  echo '👕 commit-fix-lint => remover problemas com linter';  echo '🐽 commit-fix-typo => corrigir algo simples (ex. typo, nome de variável...)'; echo '💩 commit-omg => m***a forte'; }; f"
```

Feito por **Marcus Vinicius(Lowpoc/olasoumarcus)**!
