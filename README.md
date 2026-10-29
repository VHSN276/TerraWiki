# TerraWiki

Guia interativo de Terraria para acompanhar a progressão de equipamentos do início ao endgame. Reúne um roadmap por classe, árvores de criação e um catálogo de itens sem blocos, com receitas, sub-receitas e links para consultar as fontes.

O projeto é uma página estática feita em HTML, CSS e JavaScript. Não precisa de instalação de dependências nem de etapa de build: abra o arquivo no navegador ou publique o repositório em um serviço de hospedagem estática.

## Funcionalidades

### Roadmap de progressão

- Rotas para Melee, Ranged, Magic e Summoner, ou visão de todas as classes.
- Etapas da jornada organizadas da exploração inicial ao pós-Moon Lord, com objetivos gerais, equipamentos recomendados e alternativas.
- Guia “Progressão do jogo” com instruções passo a passo do início ao Moon Lord, marcos opcionais, variações entre Corruption/Crimson e a sequência dos minérios de Hardmode.
- Checklists para objetivos e materiais. Marcar um objetivo também marca os materiais associados; marcar um item pai propaga a seleção aos componentes exibidos abaixo dele.
- Receitas expansíveis com estação de criação, quantidades, ingredientes e sub-receitas quando cadastradas.
- Informações de fase, forma de obtenção, inimigo de origem e chance de drop quando aplicável. Nos drops de inimigos, abra o detalhe para ver a imagem do mob, bioma/camada, evento e horário em que aparece; itens de Treasure Bags apontam para o chefe que derruba a bolsa.
- Busca, opção para ocultar objetivos concluídos, expansão e recolhimento dos tópicos e indicadores de progresso por etapa e no total.
- Salvamento automático do progresso no armazenamento local do navegador, além de exportação e importação de backup em JSON.

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

### Personalização e uso

- Alternância entre o tema moderno e o tema Arcade, com tipografia, ícones e elementos visuais pixelados. A escolha do tema é lembrada no navegador.
- Layout responsivo para desktop e dispositivos móveis.
- Tela “Como usar” com explicações sobre filtros, progressão, receitas e leitura das informações dos itens.

## Começar

### Abrir no computador

Baixe ou clone este repositório e abra `TerraWiki.html` em um navegador. O `index.html` encaminha para essa página e é usado como entrada quando o site está hospedado na raiz do GitHub Pages.

### Publicar com GitHub Pages

No repositório, abra **Settings → Pages** e configure:

1. Em **Build and deployment**, escolha **Deploy from a branch**.
2. Selecione a branch `main` e a pasta `/(root)`.
3. Salve e aguarde a publicação.

Depois que o GitHub Pages terminar a implantação, o site ficará disponível no endereço informado na página de configuração do Pages.

## Dados, compatibilidade e privacidade

- O conteúdo do guia declara como referência Terraria Desktop/Console/Mobile versão **1.4.5.8**. Recomendações e fases são uma organização prática de progressão; algumas rotas oferecem alternativas, e a ordem do catálogo é aproximada.
- O idioma da interface é português; nomes de itens são mantidos em inglês para facilitar a busca e a conferência das receitas na wiki.
- O progresso e a preferência de tema ficam no armazenamento local do navegador. Eles não são enviados a um servidor e não sincronizam automaticamente entre dispositivos. Use a exportação JSON para transportar um backup.
- O arquivo pode ser aberto localmente, mas imagens, fontes externas, detalhes de itens e páginas da wiki precisam de conexão com a internet. Uma hospedagem HTTPS também evita restrições que alguns navegadores aplicam a arquivos locais.
- O catálogo e as receitas correspondem aos dados cadastrados no projeto; consulte os links do item para verificar detalhes ou mudanças de versão.

## Fontes e créditos

- [Official Terraria Wiki](https://terraria.wiki.gg/) — páginas de itens, receitas, fases e sprites. Os sprites da wiki são identificados no site sob a licença [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).
- [Guia oficial de Class Setups](https://terraria.wiki.gg/wiki/Class_setup) — referência para as rotas do roadmap.
- [Terraria Database](https://terraria.source.gs/) — dados e páginas de detalhes usados no catálogo.
- [Terraria Progress Tracker](https://github.com/Doeschi/Terraria-Progress-Tracker) — dados estruturados de drops, biomas, eventos e imagens dos mobs, além da organização das sprites. O recorte usado nesta versão é de 8 de outubro de 2026; os detalhes específicos de surgimento continuam vinculados à página do mob na wiki.

Confira os créditos e os links exibidos dentro do próprio site para atribuições e detalhes associados a cada conteúdo.
