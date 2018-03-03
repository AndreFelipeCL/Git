# Git Course

Repositório criado para estudos da ferramenta de Git e GitHub.

Saiba mais meus repositóios: [André Felipe Repositórios](https://github.com/AndreFelipeCL/) 

Comandos git:

## log [--options] - mostra todo o log de commits
    [--author="<author>"]   - Filtrando commits de um determinado autor.
    [--decorate]            - Mostra mais informações de cada log.
    [--graph]               - Visualização gráfica dos commits realizados e sua estrutura.

## shortlog - Mostra um log mais resumido com o Autor e seus commits

## show <hash do commit> - Mostra de modo detalhado todas as alterações de um commit específico.

## diff [--options] - Mostra todas as modificações nos arquivos antes de um commit (arquivos modified) com o mesmo arquivo na sua versão unmodified.
    [--name-only]           - Mostra somente uma lista de arquivos modificados. 

## checkout - Descarta todas as alterações feitas no arquivo.

## reset HEAD [--options] <nome do arquivo> - Retira os arquivos em STAGED (adicionados para commit). Usar este recurso e suas opções de forma cautelosa, pois este faz alteração no histórico dos nossos commits. Obs: Evitar usar este recurso com códigos e arquivos que já ## estejam em produção ou em repositório remoto que dê acesso à outras pessoas.
    [--soft]                - Remove o último commit e mantém as alterações no arquivo. O arquivo fica STAGED.
    [--mixed]               - Remove o último commit e mantém as alterações no arquivo. O arquivo fica MODIFIED.
    [--hard]                - Ignora tudo o que fora feito em um commit e realiza um descarte agressivo, removendo tudo que foi feito, arquivos em UNMODIFIED.

## push [--options] <repositorio> <branch> - Enviar os arquivos, logs e modificações para o repositório remoto.
    [-u]                    - Realiza o mapeamento (track) do repositório remoto.
