# ciufpb-livro

> Disponível diretamente em https://ciufpb-livro.pages.dev/

Este é manual dinâmico para estudantes do Centro de Informática da Universidade Federal da Paraíba (UFPB). O repositório faz parte do projeto [convergencia.xyz](https://convergencia.xyz), desenvolvido para ser uma ferramenta intuitiva e didática, facilitando o acesso a informações cruciais para a comunidade acadêmica.

## Sobre o conteúdo deste repositório

O livro é hospedado diretamente no Cloudflare Pages, oferecendo uma experiência de leitura rápida e confiável. Utilizamos o [mdBook](https://github.com/rust-lang/mdBook), uma ferramenta para criar livros online a partir de arquivos Markdown. Escolhemos o mdBook por sua simplicidade e baixa curva de aprendizado, o que facilita a colaboração no projeto.

Comparado ao antigo sistema que usava o Docusaurus, o mdBook permite que utilizemos menos tecnologias e, consequentemente, reduzimos a complexidade para novos colaboradores. Esta mudança visa tornar o projeto mais acessível e fácil de manter.

## Configuração de Deploy Automático

O deploy no Cloudflare Pages é acionado automaticamente a cada novo `push` no repositório. Esta configuração segue as práticas recomendadas de integração contínua como documentado na página do mdBook [Continuous Integration](https://rust-lang.github.io/mdBook/continuous-integration.html).

