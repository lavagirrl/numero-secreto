# Introdução ao GitHub e Git

Este repositório foi criado para auxiliar no aprendizado sobre como utilizar o Git e o GitHub para gerenciar projetos de software.

## O que você aprenderá

Nesta aula, você será capaz de:

- Criar sua conta no GitHub para compartilhar seus projetos e colaborar com outros;
- Baixar e instalar o Git em seu computador;
- Configurar suas informações de usuário localmente no Git;
- Criar um repositório remoto no GitHub;
- Conectar seu repositório local ao repositório remoto usando comandos como `git init`, `git add`, `git commit`, `git remote add`, e `git push`.

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

## Contribuição

Este repositório foi criado com o propósito de aprendizado, no entanto, sinta-se à vontade para contribuir com correções, melhorias ou adição de informações relevantes.

Para contribuir:

1. Faça um fork deste repositório.
2. Crie uma branch para sua contribuição: `git checkout -b sua-feature`.
3. Faça as alterações desejadas.
4. Faça o commit das alterações: `git commit -m 'Adicionando funcionalidade X'`.
5. Faça o push para a branch: `git push origin sua-feature`.
6. Abra um pull request explicando suas alterações.

