# MercadoVisível

**Transforme ofertas locais em oportunidades encontradas.**

Protótipo de microaplicativo para a AppJam Expoagas 2026. O MercadoVisível ajuda pequenos e médios supermercados a transformar uma oferta genérica em conteúdo claro, estruturado e pronto para diferentes canais digitais.

> **Escopo da apresentação:** a Expoagas é o contexto de apresentação do desafio. O produto não tenta ser um aplicativo da feira; ele demonstra uma solução aplicável ao varejo supermercadista e aos seus canais digitais.

## Problema

Ofertas como “Oferta da semana: azeite com desconto” não comunicam produto, localização, preço, validade ou ação para o consumidor. Isso dificulta a compreensão do conteúdo por pessoas e buscadores e torna a publicação em vários canais inconsistente.

## MVP

O `index.html` é autocontido e funciona no GitHub Pages, sem backend, API, chave ou dependência externa. Ele oferece dois fluxos:

### Auditor de visibilidade

Cole um HTML de exemplo ou de uma página real e faça uma triagem local de:

- title e meta description;
- hierarquia de H1;
- idioma e viewport mobile;
- alt das imagens;
- textos descritivos dos links;
- HTML semântico;
- presença de JSON-LD;
- recomendações priorizadas e índice de prontidão.

### Otimizador omnichannel

- formulário guiado de oferta;
- diagnóstico antes/depois;
- índice explicável de completude (não é promessa de ranking);
- título SEO, meta description e URL amigável;
- prévias para Google, site e WhatsApp;
- exemplo de JSON-LD de Product/Offer;
- cópia dos resultados para publicação.

Os dados exibidos são de demonstração. O auditor é uma triagem local: não substitui Search Console, PageSpeed ou o teste oficial de resultados avançados. O JSON-LD é um exemplo para ser inserido na página real da oferta; gerá-lo não garante rich result ou posição no Google.

## Evolução planejada

Estas ideias fazem parte da visão do produto, mas **não são apresentadas como funcionalidades já implementadas no MVP**:

- importar uma página por URL, quando houver uma forma segura de leitura;
- validar mais tipos de dados estruturados conforme o conteúdo da página;
- gerar alt text e sugestões de links a partir do conteúdo auditado;
- exportar um pacote completo em HTML, Markdown ou JSON;
- gerar QR Code para uma oferta publicada;
- adicionar nome do fornecedor, condição comercial e localização da loja;
- registrar oportunidades e próximos passos para a equipe comercial;
- acompanhar indicadores reais após integração com Search Console, Analytics ou CMS.

Essa separação mantém a demonstração honesta: o MVP funciona sem backend e sem credenciais, enquanto a evolução mostra como a solução poderia crescer em um cenário real.

## Como testar

Abra `index.html` diretamente no navegador. Preencha os campos ou use **Usar exemplo completo** e percorra as abas do resultado.

## Publicar no GitHub Pages

1. Crie um repositório público no GitHub.
2. Envie `index.html` e este `README.md` para a branch `main`.
3. Em **Settings → Pages**, selecione a branch `main` e a pasta `/` (root).
4. Acesse o endereço informado pelo GitHub Pages.

## Relação com os critérios

- **Resolução do problema:** padroniza e melhora ofertas de pequenos supermercados.
- **Temas:** SEO local, omnichannel, automação, analytics, IA generativa (fluxo de sugestões), marketing digital, acessibilidade e varejo.
- **UX:** fluxo curto, resultado imediato, score e prévias visuais.
- **Identidade:** linguagem e interface próprias para varejo local.
- **Criatividade:** uma oferta vira ativos para vários canais e dados estruturados; a visão futura inclui QR Code e acompanhamento comercial.
- **Qualidade técnica:** HTML semântico, responsivo, acessível, offline-first e sem segredos no cliente.

## Integrantes

- Nome: ____________________  | E-mail: ____________________
- Nome: ____________________  | E-mail: ____________________
- Nome: ____________________  | E-mail: ____________________
- Nome: ____________________  | E-mail: ____________________
- Nome: ____________________  | E-mail: ____________________

## Links de entrega

- Repositório: ____________________
- Aplicação publicada: ____________________

## Licença

Protótipo acadêmico.
