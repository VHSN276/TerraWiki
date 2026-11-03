# TerraWiki

Guia interativo de Terraria para acompanhar a progressão de equipamentos do início ao endgame. Reúne um roadmap por classe, progressão do jogo, eventos, árvores de criação, um catálogo completo de mobs e um catálogo de itens sem blocos, com receitas, sub-receitas e links para consultar as fontes.

O projeto é uma página estática feita em HTML, CSS e JavaScript. Não precisa de instalação de dependências nem de etapa de build: abra o arquivo no navegador ou publique o repositório em um serviço de hospedagem estática.

## Funcionalidades

### Roadmap de progressão

- Rotas para Melee, Ranged, Magic e Summoner, ou visão de todas as classes.
- Etapas da jornada organizadas da exploração inicial ao pós-Moon Lord, com objetivos gerais, equipamentos recomendados e alternativas. As recomendações por classe seguem o guia oficial Class Setups e são agrupadas em um tópico expansível por classe, com divisões para armas, armaduras, acessórios, lacaios, poções e demais funções.
- Destaques visuais mostram as prioridades do guia por etapa: melhores armas, armaduras defensivas, gerais ou ofensivas, acessórios, buffs/poções e montarias. Prioridades combinadas, como General/Offensive, aparecem juntas; itens sem prioridade específica continuam como alternativas normais.
- Guia “Progressão do jogo” com instruções passo a passo do início ao Moon Lord, marcos opcionais, variações entre Corruption/Crimson e a sequência dos minérios de Hardmode.
- Checklists para objetivos e materiais. Marcar um objetivo também marca os materiais associados; marcar um item pai propaga a seleção aos componentes exibidos abaixo dele.
- Receitas expansíveis com estação de criação, quantidades, ingredientes e sub-receitas quando cadastradas.
- Informações de fase, forma de obtenção, inimigo de origem e chance de drop quando aplicável. Nos drops de inimigos, abra o detalhe para ver a imagem do mob, bioma/camada, evento e horário em que aparece; itens de Treasure Bags apontam para o chefe que derruba a bolsa.
- Busca, opção para ocultar objetivos concluídos, expansão e recolhimento dos tópicos, indicadores de progresso por etapa e avisos configuráveis para etapas e tópicos iniciados, mas incompletos.
- Salvamento automático do progresso no armazenamento local do navegador, além de exportação e importação de backup em JSON.

### Eventos

- Página dedicada aos 19 eventos principais de Terraria, com Halloween e Natal em uma seção sazonal.
- Para cada evento: fase da progressão, critérios naturais, como iniciar ou invocar, inimigos, recompensas exclusivas, melhores destaques e NPCs envolvidos.
- Busca por evento, inimigo, item ou NPC e filtros combináveis por tipo e fase.
- Links diretos para as páginas oficiais com as tabelas completas e as taxas detalhadas; as taxas podem variar por modo, inimigo e onda.

### Árvores de criação

- Receitas e cadeias de componentes para itens importantes da progressão.
- Filtros combináveis por categoria, classe e fase do jogo, além de busca por nome.
- Ingredientes, quantidades, estações e sub-receitas em níveis expansíveis.
- Conjuntos de armadura apresentados em conjunto com as peças correspondentes quando aplicável.

### Todos os itens

- Catálogo de itens do jogo, sem blocos, com cartões, imagens, categoria e indicação de fase.
- Categorias e subcategorias, como classe de arma, tipo de ferramenta, peça de armadura, função de acessório e tipo de munição.
- Filtros de progressão — Pré-Hardmode, Hardmode e Endgame — nas categorias em que essa divisão é útil; filtros podem ser combinados com categoria e subcategoria.
- Busca, navegação paginada e ordenação aproximada pela progressão, considerando marcos de obtenção, fontes e dependências de receitas. Itens de fase variável são identificados separadamente.
- Receitas e sub-receitas expansíveis para os itens fabricáveis com receita cadastrada, com marcação de materiais.
- Quando o item ou um material da receita vem de um inimigo, detalhe expansível com imagem do mob e contexto de surgimento. Drops de Treasure Bags também mostram o chefe de origem e identificam quando o item é obtido ao abrir a bolsa.
- Prévia ampliada da imagem e links para detalhes e para a página correspondente na wiki.
- Favoritos com estrela: os itens favoritos sobem para o início da lista e podem ser consultados pelo filtro “Favoritos”.

### Todos os mobs

- Catálogo dos 506 inimigos, chefes e criaturas do bestiário; NPCs moradores ficam fora desta lista.
- Cada ficha traz sprite, número no bestiário, bioma/camada, evento e horário de aparição quando aplicáveis, além de link para a Wiki oficial.
- Drops expansíveis com imagem e nome do item, quantidade e taxa/chance por modo. Itens obtidos ao abrir uma Bolsa do Tesouro são identificados separadamente, e condições, variantes e grupos de drops são indicados quando cadastrados.
- Filtros combináveis por tipo e habitat, busca por mob, bioma, evento ou item dropado, e navegação paginada. As tabelas são carregadas ao abrir cada ficha para manter a consulta leve.
- Os dados de bestiário e drops acompanham a build 1.4.5.8 e são incorporados ao HTML, então a tela funciona com `file://`; as imagens e links ainda precisam de conexão com a internet.

### Sala de troféus de chefes

- O arquivo independente [`Boss_Room_Guide.html`](Boss_Room_Guide.html) ajuda a planejar uma sala decorativa com uma combinação de bloco e parede de fundo para cada um dos 28 chefes e encontros listados.
- Cada ficha informa a fase do jogo, se o encontro pertence a um evento, onde obter os materiais, qual ferramenta usar, a receita, as quantidades e a estação de criação.
- Busca por chefe, bloco, parede ou estação e filtros por fase e tipo de encontro. As sugestões consideram um mundo Corruption e apontam alternativas quando o material depende de um mundo Crimson.
- Abra o arquivo separadamente; este guia ainda não é uma tela da navegação principal do TerraWiki.

### Personalização e uso

- Alternância entre o tema moderno e o tema Arcade, com tipografia, ícones e elementos visuais pixelados. A escolha do tema é lembrada no navegador.
- Seletor entre português do Brasil e inglês para nomes de itens, materiais, inimigos, biomas e eventos; a preferência de idioma também fica salva neste navegador.
- Layout responsivo para desktop e dispositivos móveis.
- Tela “Como usar” com explicações sobre filtros, progressão, receitas e leitura das informações dos itens.

## Começar

### Acessar pela web

Abra o [TerraWiki no GitHub Pages](https://vhsn276.github.io/TerraWiki/). O site é publicado a partir da branch `main`; commits enviados para ela atualizam a versão web automaticamente.

### Abrir no computador

Baixe ou clone este repositório e abra `TerraWiki.html` em um navegador. O `index.html` encaminha para essa página. O guia da sala de troféus pode ser aberto pelo link acima ou diretamente em `Boss_Room_Guide.html`.

## Dados, compatibilidade e privacidade

- O conteúdo do guia declara como referência Terraria Desktop/Console/Mobile versão **1.4.5.8**. Recomendações e fases são uma organização prática de progressão; algumas rotas oferecem alternativas, e a ordem do catálogo é aproximada.
- A interface geral permanece em português. O seletor do cabeçalho alterna entre português do Brasil e inglês os nomes do jogo e os filtros dos catálogos, incluindo itens, materiais, inimigos, biomas e eventos; a busca aceita nomes localizados e originais.
- O progresso e as preferências de tema e idioma ficam no armazenamento local do navegador. Eles não são enviados a um servidor e não sincronizam automaticamente entre dispositivos. Use a exportação JSON para transportar um backup.
- O arquivo pode ser aberto localmente, mas imagens, fontes externas, detalhes de itens e páginas da wiki precisam de conexão com a internet. Uma hospedagem HTTPS também evita restrições que alguns navegadores aplicam a arquivos locais.
- O catálogo e as receitas correspondem aos dados cadastrados no projeto; consulte os links do item para verificar detalhes ou mudanças de versão.

## Fontes e créditos

- [Official Terraria Wiki](https://terraria.wiki.gg/) — páginas de itens, receitas, fases e sprites, além do [banco oficial de textos pt-BR do jogo](https://terraria.wiki.gg/pt/wiki/M%C3%B3dulo:GameText/db-pt.json), usado como referência para nomes localizados. Os sprites da wiki são identificados no site sob a licença [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).
- [Guia oficial de Class Setups](https://terraria.wiki.gg/wiki/Class_setup) — referência para as rotas do roadmap.
- [Terraria Database](https://terraria.source.gs/) — dados e páginas de detalhes usados no catálogo.
- [Terraria Progress Tracker](https://github.com/Doeschi/Terraria-Progress-Tracker) — dados estruturados do bestiário, habitats, eventos, taxas e quantidades dos drops, e referências das imagens de mobs e itens. O recorte usado nesta versão é de 8 de outubro de 2026; confira as páginas oficiais para condições e atualizações posteriores.

Confira os créditos e os links exibidos dentro do próprio site para atribuições e detalhes associados a cada conteúdo.
