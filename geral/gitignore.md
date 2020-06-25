# .GITIGNORE

![](./../imagens/git/logo.png)

## Afinal, o que é esse tal ".gitignore"?

Então, é extremamente simples o propósito do `.gitignore`, ele possibilita com que ao dar um `push` para o repositório, alguns arquivos e/ou diretórios sejam ignorados. Ou seja, pelo próprio nome já da para entender `git ignore`, ou seja, coisas a serem ignoradas pelo Git.

## Entendi, mas e como é que eu faço para usar?

É fácil, vamos lá!
- Primeiramente você deve saber qual arquivo ou diretório do seu projeto você não quer que seja adicionado quando executar o comando `git push`.
- Ok, agora que você já sabe, vamos criar esse arquivo dentro do seu projeto, então o nome do arquivo tem que ser `.gitignore` (Sim, tem esse ponto no início do nome mesmo).
- Abra o arquivo `.gitignore` e dentro dele coloque o nome do arquivo/diretório que deseja que o Git ignore.
- Você pode também dizer para o `.gitignore` ignorar a si mesmo, é só colocar o nome `.gitignore` dentro do arquivo.

## Ok, e como faço para saber se ta funcionando?

Bem simples, se você digitar o comando `git status`, você verá que mesmo que exista esse arquivo/diretório dentro do projeto, o Git vai ignorar ele, se realmente isso acontecer é porque está funcionando.

Para entender mais sobre o `.gitignore`, [clique aqui](https://womakerscode.gitbook.io/desvendando-git-e-github/ciclo-de-vida-basico/o-que-e-o-.gitignore).


Achou algo faltando aqui? Abre um PR e ajude a manter essa documentação viva :)