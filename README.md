# Introdução ao GitHub e Git

Este repositório foi criado para auxiliar no aprendizado sobre como utilizar o Git e o GitHub para gerenciar projetos de software.

## O que você aprenderá

Nesta aula, você será capaz de:

- Criar sua conta no GitHub para compartilhar seus projetos e colaborar com outros;
- Baixar e instalar o Git em seu computador;
- Configurar suas informações de usuário localmente no Git;
- Criar um repositório remoto no GitHub;
- Conectar seu repositório local ao repositório remoto usando comandos como `git init`, `git add`, `git commit`, `git remote add`, e `git push`.
- - Baixar uma cópia de um repositório hospedado no GitHub para seu computador utilizando o comando `git clone`;
- Realizar alterações no código de um projeto e registrá-las com commits, utilizando os comandos `git add` e `git commit`;
- Visualizar quais arquivos foram modificados no repositório local, utilizando o comando `git status`;
- Listar os commits realizados no repositório, com dados do autor, data e mensagem de cada commit, utilizando o comando `git log`;
- Visualizar os repositórios remotos linkados com o repositório local, utilizando o comando `git remote`;
- Enviar commits feitos no repositório local para o repositório remoto, utilizando o comando `git push`;
- Baixar commits do repositório remoto para o repositório local, utilizando o comando `git pull`;
- Adicionar uma pessoa como colaboradora em um repositório no GitHub, e também aceitar um convite de colaboração recebido.
- Utilizar o Git pela integração do VSCode, ao invés de utilizar pelo terminal;
- Entender como acontecem conflitos de códigos em commits que modificam um mesmo arquivo, feitos por pessoas distintas;
- Identificar e resolver conflitos de maneira manual, editando os arquivos afetados e realizando commits para marcar o conflito como resolvido.
- Reverter mudanças de um commit de maneira automática, utilizando o comando git revert;
Apagar um determinado commit do histórico, desfazendo automaticamente suas mudanças no código, utilizando o comando git reset;
Modificar o último commit efetuado, alterando sua mensagem ou modificações no código, utilizando o comando git commit com o parâmetro --amend.

## Pré-requisitos

Antes de começar, é recomendado possuir um conhecimento básico de linha de comando e acesso à internet para configurar sua conta no GitHub.

## Como Utilizar este Repositório

1. **Criar uma Conta no GitHub**: Acesse [GitHub](https://github.com) e siga as instruções para criar uma conta, caso ainda não tenha uma.

2. **Instalar o Git**: Baixe e instale o Git em seu computador. Você pode encontrar o instalador em [Git](https://git-scm.com/).

3. **Configurar o Git**: Após instalar o Git, configure suas informações de usuário localmente utilizando os comandos:
    ```bash
    git config --global user.name "Seu Nome"
    git config --global user.email "seuemail@example.com"
    ```

4. **Criar um Repositório Remoto no GitHub**: No GitHub, crie um novo repositório. Siga as instruções na interface do GitHub para criá-lo.

5. **Clonar o Repositório Localmente**: Clone o repositório para seu computador utilizando o comando:
    ```bash
    git clone URL_DO_REPOSITORIO
    ```
    Substitua `URL_DO_REPOSITORIO` pela URL do repositório que você criou no GitHub.

6. **Conectar o Repositório Local ao Repositório Remoto**: Utilize os comandos `git add`, `git commit`, `git remote add origin`, e `git push` para conectar seu repositório local ao remoto.

7. **Realizar Alterações e Commits**: Faça alterações no código do projeto, adicione os arquivos modificados com `git add` e registre suas alterações com `git commit`.

8. **Verificar o Status e Visualizar Commits**: Use `git status` para ver os arquivos modificados e `git log` para listar os commits realizados.

9. **Trabalhar com Repositórios Remotos**: Utilize `git remote` para visualizar repositórios remotos, `git push` para enviar commits locais para o repositório remoto e `git pull` para baixar commits do repositório remoto para o local.

10. **Adicionar Colaboradores no GitHub**: Acesse as configurações do seu repositório no GitHub para adicionar colaboradores ou aceitar convites de colaboração.

11. **Integração do Git com VSCode**: Aprenda a utilizar o Git através da integração com o VSCode, explorando as funcionalidades oferecidas pela interface gráfica.

12. **Conflitos de Código**: Entenda como ocorrem conflitos de código quando alterações são feitas por diferentes colaboradores no mesmo arquivo.

13. **Resolução de Conflitos**: Saiba como o Git sinaliza conflitos e aprenda a resolvê-los manualmente, editando os arquivos afetados e realizando commits para marcar o conflito como resolvido.
14. Reverter Mudanças de um Commit: Aprenda a reverter mudanças de um commit de maneira automática utilizando o comando git revert.

15. Apagar um Commit do Histórico: Saiba como apagar um commit específico do histórico, desfazendo suas mudanças automaticamente no código, com o comando git reset.

16. Modificar o Último Commit Efetuado: Entenda como modificar o último commit efetuado, alterando sua mensagem ou modificações no código, utilizando o comando git commit com o parâmetro --amend.


## Contribuição

Este repositório foi criado com o propósito de aprendizado, no entanto, sinta-se à vontade para contribuir com correções, melhorias ou adição de informações relevantes.

Para contribuir:

1. Faça um fork deste repositório.
2. Crie uma branch para sua contribuição: `git checkout -b sua-feature`.
3. Faça as alterações desejadas.
4. Faça o commit das alterações: `git commit -m 'Adicionando funcionalidade X'`.
5. Faça o push para a branch: `git push origin sua-feature`.
6. Abra um pull request explicando suas alterações.

