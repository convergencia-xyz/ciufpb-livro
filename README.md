# ciufpb-livro

> Disponível diretamente em https://ciufpb-livro.pages.dev/

Este é manual dinâmico para estudantes do Centro de Informática da Universidade Federal da Paraíba (UFPB). O repositório faz parte do projeto [convergencia.xyz](https://convergencia.xyz), desenvolvido para ser uma ferramenta intuitiva e didática, facilitando o acesso a informações cruciais para a comunidade acadêmica.

- - -

## Instruções de Execução Local

Para executar o projeto localmente, é necessário que você tenha o comando `make` instalado em seu ambiente de desenvolvimento. As instruções abaixo detalham como manipular o projeto utilizando o `make`.

### Comandos Disponíveis:

- **Executar o Projeto:** Para rodar o livro localmente e visualizar as alterações em tempo real, utilize o comando:
  ```bash
  make run
  ```
  Este comando compila os arquivos e serve o livro em um servidor local, permitindo que você visualize as modificações instantaneamente.

- **Gerar Arquivos Estáticos:** Caso queira gerar uma versão estática do livro para distribuição ou testes offline, execute:
  ```bash
  make
  ```
  Esse comando compila todos os arquivos Markdown em formatos web estáticos que podem ser facilmente distribuídos ou visualizados sem necessidade de um servidor.

- **Limpar Arquivos Gerados:** Após os testes ou a compilação, para remover todos os arquivos estáticos gerados e manter o diretório de trabalho limpo, use:
  ```bash
  make clean
  ```
  Isso assegura que todos os arquivos temporários ou de compilação sejam apagados, mantendo o ambiente organizado.


## Informações técnicas repositório

O livro é hospedado diretamente no Cloudflare Pages, oferecendo uma experiência de leitura rápida e confiável. Utilizamos o [mdBook](https://github.com/rust-lang/mdBook), uma ferramenta para criar livros online a partir de arquivos Markdown. Escolhemos o mdBook por sua simplicidade e baixa curva de aprendizado, o que facilita a colaboração no projeto.

Comparado ao antigo sistema que usava o Docusaurus, o mdBook permite que utilizemos menos tecnologias e, consequentemente, reduzimos a complexidade para novos colaboradores. Esta mudança visa tornar o projeto mais acessível e fácil de manter.

### Configuração de Deploy Automático

O deploy no Cloudflare Pages é acionado automaticamente a cada novo `push` no repositório. Esta configuração segue as práticas recomendadas de integração contínua como documentado na página do mdBook [Continuous Integration](https://rust-lang.github.io/mdBook/continuous-integration.html).

