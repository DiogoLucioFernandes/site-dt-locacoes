# Site DT Locações

Site da minha empresa de locação de mesas e cadeiras para eventos em Goiânia. É a versão simples, em produção, que recebe o tráfego de anúncios e leva o cliente direto para o WhatsApp.

Site no ar: https://dtlocacoes.com.br

## O que ele faz

- Página única com destaque, catálogo de produtos, contato, mapa e avaliação no Google.
- Catálogo montado por JavaScript a partir de uma lista de produtos, cada um com botão de WhatsApp e mensagem pronta com o nome do item.
- **Mensagem personalizada por origem do tráfego:** lê o parâmetro `utm_source` da URL e muda a mensagem inicial do WhatsApp conforme o cliente veio do Google ou do Instagram/Facebook, para saber de onde cada contato chegou.
- Animações ao rolar a página e efeito de parallax na imagem principal.
- Layout responsivo, pensado para celular.

## Tecnologias

HTML, CSS e JavaScript · Google Tag Manager (o ID real foi trocado por `GTM-XXXXXXX` neste repositório) · AOS (animações) · Font Awesome

## Como foi feito

Desenvolvi com apoio de IA e adaptei às necessidades do negócio. Estou estudando o código para evoluí-lo por conta própria.

## Contexto

Este site é a versão que ficou no ar depois de eu testar uma versão com orçamento online completo (veja o projeto *Orçamento Online DT Locações*). A versão simples gerou mais contatos no WhatsApp.

## Próximos passos

- [ ] Separar CSS e JavaScript em arquivos próprios.
- [ ] Guardar a lista de produtos em um arquivo de dados.
- [ ] Revisar acessibilidade (textos alternativos e contraste).

## O que já aprendi estudando este projeto

- [ ] Como o `renderProducts` cria os cartões a partir de uma lista
- [ ] Como ler parâmetros da URL com `URLSearchParams`
- [ ] Como o evento de rolagem controla o efeito de parallax
