# Projeto X

Este projeto faz XYZ.  
Feito para a atividade do professor.

## Como usar
- Abra o arquivo index.html no navegador.
- Faça os testes.
# atividade-html-aria

# Projeto de Acessibilidade e Semântica HTML

Este exercício teve como objetivo transformar um código HTML não semântico em uma estrutura organizada, acessível e compreensível para usuários e leitores de tela. O código final utiliza tags semânticas, WAI-ARIA e boas práticas de acessibilidade.

## Como o WAI-ARIA ajudou no resultado
O uso de atributos WAI-ARIA permitiu rotular corretamente elementos sem texto visível, ajudando leitores de tela a identificar suas funções. A aplicação de `aria-label` e `aria-labelledby` tornou o conteúdo mais claro para navegação assistiva. Além disso, o uso de `role` só foi aplicado quando o HTML não tinha semântica nativa, garantindo acessibilidade sem exageros.

## Justificativa das escolhas de tags semânticas
As tags `<header>`, `<nav>`, `<main>`, `<section>` e `<article>` foram usadas para organizar a página em blocos lógicos. Isso melhora a navegação, a leitura do código e o entendimento por tecnologias assistivas. Também ajustei os títulos para seguir a hierarquia correta (`h1` → `h2` → `h3`), garantindo estrutura clara e coerente. O uso de tags semânticas substituiu `divs` sem função, deixando tudo mais acessível.

## Material versionado
- `index.html` com código final organizado
- `README.md` explicando o processo
