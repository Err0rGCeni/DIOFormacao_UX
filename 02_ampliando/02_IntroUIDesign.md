# Introdução ao UI Design

## Wireframe

Ler títulos, subtítulos, links, iconografia, imagens e outros componentes de um wireframe. Detalhes e definições adicionais como clique, hover, estilo, shadow, etc.

## Cores

> Cor: Termo geral para descrever cada matiz, tonalidade, tom e temperatura.

- CMYK: Ciano, Magenta, Amarelo, Preto; Mistura substrativa;
- RGB: Vermelho, Verde, Azul; Mistura aditiva;
- HSB (V): Matiz, Saturação e Brilho;

Observar contrastes, escalas de cores, etc.

## Espaçamentos

- _White Space_ e _Negative Spaces_ são termos para espaço entre os elementos dentro de uma composição. Isso ajuda a organizar a interface e a balancear as informações.
- **Micro Espaços** são os espaços entre alguns elementos específicos (linhas, parágrafos, grids, imagens, links, etc.).
  - Geralmente usados pela regra de 8 (8px, 16px...);
- **Macro Espaços**  são espaços para blocos e componentes maiores.
  - Conduz o layout, dando respiro de informações diferentes e dar uma navegabilidade e experiência mais agradável;

## Mensagens e Notificações

- Notificar erros de forma simples e objetiva ao usuário;
- Dar direcionamento ao usuário (identificaçção, causa e solução);

## Design System

Um _Design System_ é uma coleção de componentes reutilizáveis, guiados por padrões claros, que podem ser montados para construir qualquer aplicação.

### Atomic Design

Metodologia criada para a criação de um design system, apresentando um paralelo entre a química e componentização de elementos de interface.

- **Átomos**: Unidades básicas (paragrafo, botão, input, etc.) e elementos mais abstratos (tokens, como paletas de cores, fontes, tamanho, espaçamento, iconografia, etc.);
- **Moléculas**: Grupos de átomos combinados entre si (por exemplo, label + input + botão);
- **Organismos**: Grupo de móléculas unidas para formar um bloco de conteúdo relativamente complexo de uma interface (por exemplo, header, footer, navegação, pesquisa, etc.);

--- Quebra da analogia química ---

- **Templates**: Grupos de organismos diagramados para formar páginas, sendo concetros e fornecendo contexto para moléculas e organismos abstratos.
- **Páginas**: Instâncias específicas dos templates, com conteúdo do espaço reservado sendo substituído pelo conteúdo real.
