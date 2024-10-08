# Git e Github

## Definições e Diferenças 
### **Git** 
É um sistema de controle de versão que permite rastrear mudanças em arquivos e coordenar o trabalho em equipe. Ele armazena o histórico de alterações de um projeto e permite criar branches e realizar merges.
### Github
É uma plataforma de hospedagem de código que utiliza o Git. Ela permite armazenar repositórios, colaborar com outros desenvolvedores, gerenciar problemas e revisar código.

## Principais Comandos Git
| Comando Git                              | Descrição                                                  |
|------------------------------------------|------------------------------------------------------------|
| `git init`                               | Inicializa um novo repositório Git.                       |
| `git clone <url>`                       | Clona um repositório remoto.                               |
| `git add <arquivo>`                     | Adiciona arquivos ao índice (staging area).               |
| `git commit -m "<mensagem>"`            | Grava as mudanças no repositório com uma mensagem.        |
| `git status`                             | Mostra o status dos arquivos no repositório.              |
| `git log`                                | Exibe o histórico de commits.                              |
| `git branch`                             | Lista as branches existentes.                               |
| `git checkout <branch>`                  | Muda para a branch especificada.                           |
| `git merge <branch>`                     | Mescla a branch especificada na branch atual.             |
| `git pull`                               | Atualiza o repositório local com as mudanças do remoto.    |
| `git push`                               | Envia as mudanças locais para o repositório remoto.       |
| `git reset <arquivo>`                    | Remove arquivos do índice (staging area).                 |
| `git remote -v`                          | Mostra os repositórios remotos associados.                 |
| `git config --global user.name "<nome>"`| Configura o nome de usuário para commits.                  |
| `git config --global user.email "<email>"`| Configura o e-mail para commits.                         |
| `git config --list`                     | Lista todas as configurações do Git.                       |
| `git config --global core.editor <editor>`| Define o editor de texto padrão para mensagens de commit.|
