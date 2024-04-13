# HTML Semântico

O HTML Semântico é uma abordagem na escrita de código HTML que enfatiza o significado dos elementos em vez de apenas sua apresentação visual. Em outras palavras, ele usa tags que descrevem o conteúdo e a estrutura do documento de forma mais clara e compreensível para humanos e máquinas.

## Vantagens do HTML Semântico

- **Melhor Acessibilidade**: Ao usar tags semânticas como `<header>`, `<nav>`, `<main>`, `<footer>`, entre outras, tornamos o conteúdo mais acessível para usuários com necessidades especiais e para mecanismos de busca.

- **Facilidade de Manutenção**: O código HTML se torna mais organizado e fácil de entender, facilitando a manutenção e a colaboração entre desenvolvedores.

- **SEO Aprimorado**: Os motores de busca valorizam o conteúdo semântico, o que pode melhorar a classificação nos resultados de pesquisa.

## Usabilidade do HTML Semântico

O HTML Semântico é amplamente utilizado em projetos web modernos, incluindo sites, aplicativos web e páginas de destino. Ele é essencial para garantir uma experiência de usuário consistente e acessível em diferentes dispositivos e plataformas.

## Principais Benefícios do HTML Semântico

1. **Clareza e Legibilidade**: O código HTML se torna mais legível e fácil de entender, facilitando o trabalho em equipe e a manutenção do projeto.

2. **Melhor Acessibilidade**: Tags semânticas fornecem uma estrutura clara e significativa para o conteúdo, melhorando a acessibilidade para usuários com deficiências visuais ou cognitivas.

3. **SEO Aprimorado**: O conteúdo semântico é mais compreensível para os motores de busca, o que pode resultar em uma melhor classificação nos resultados de pesquisa.

---

# Diferenças entre "class", "id" e "tags" no contexto do CSS

No CSS, "class", "id" e "tags" são seletores que são usados para aplicar estilos a elementos HTML. Aqui está uma breve explicação das diferenças entre eles:

- **Tags**: São os próprios elementos HTML, como `<div>`, `<p>`, `<h1>`, etc. Selecionar uma tag aplica estilos a todos os elementos com essa tag no documento.

- **Class**: É um atributo HTML que pode ser aplicado a um ou mais elementos para identificá-los. Classes são selecionadas no CSS precedidas por um ponto (`.`). Uma classe pode ser reutilizada em vários elementos.

- **ID**: É um atributo HTML exclusivo que identifica um elemento específico. IDs são selecionados no CSS precedidos por um hashtag (`#`). Cada ID deve ser exclusivo dentro de um documento HTML.

Exemplo de uso no CSS:

```css
/* Seleciona todas as tags <p> */
p {
    /* Estilos para todos os parágrafos */
}

/* Seleciona elementos com a classe "destaque" */
.destaque {
    /* Estilos para elementos com a classe "destaque" */
}

/* Seleciona o elemento com o ID "cabecalho" */
#cabecalho {
    /* Estilos para o elemento com o ID "cabecalho" */
}
