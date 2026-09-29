# AtividadePraticaONG-DonTECH

Projetar e desenvolver um conjunto de páginas web utilizando o padrão HTML5 semântico, garantindo uma arquitetura de informação consistente e organizada em diretórios estruturados para a **ONG DonTECH**. O ecossistema é composto por uma página inicial (`index.html`) apresentando a instituição e sua assistência técnica solidária, uma página focada nas iniciativas da comunidade (`projetos.html` - detalhando o projeto *Circuito Solidário: Renovando Eletrodomésticos, Melhorando Vidas*) e uma página de engajamento social (`cadastro.html`).

O grande destaque do desafio foi implementar, nesta última, um formulário interativo completo contendo validações nativas e máscaras de entrada rigorosas (CPF, Telefone, CEP) para garantir o registro íntegro e seguro de futuros beneficiários e colaboradores que buscam manutenção gratuita de seus eletroeletrônicos.

Atividade de conteúdo prático de aula da matéria de Desenvolvimento Front-End Para Web. 2º Semestre do curso de Análise e Desenvolvimento de Sistemas (ADS).

---

## 🌐 Observação de Arquitetura: Estratégia de Roteamento (Hash Routing)

Em ambientes de produção estáticos (como o GitHub Pages), rotas internas diretas de um ecossistema SPA podem gerar o erro 404 ao atualizar uma página (Refresh). Para garantir a persistência de rotas e a resiliência da aplicação sem depender de um servidor Back-end configurado para redirecionamento, a estratégia ideal a ser aplicada em próximas iterações deste projeto é o **Hash Routing** (utilizando o padrão `/#/cadastro`).

Dessa forma, o navegador intercepta a hashtag localmente, permitindo que o motor do JavaScript resolva o roteamento dinâmico e o usuário atualize a página sem quebrar o fluxo de navegação do site da ONG.
