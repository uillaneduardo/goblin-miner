# Princípios de escopo e interação

## Objetivo

Definir como novas características, sistemas e informações devem ser avaliados antes de entrarem no jogo.

**Goblin Miner** deve buscar profundidade por meio da interação entre poucos sistemas claros, evitando acumular atributos, barras, exceções e comportamentos que aumentem o custo de implementação sem criar decisões relevantes.

## Regra principal

> Nenhuma característica deve existir como mecânica apenas para enriquecer a lore. Toda característica mecânica deve criar uma decisão, consequência ou possibilidade perceptível para o jogador.

Uma informação pode continuar existindo no universo, na aparência, nos diálogos ou nos eventos sem precisar fazer parte dos cálculos centrais do jogo.

## Processo de avaliação

Antes de transformar uma ideia em sistema, responder:

1. Com qual parte do jogo o jogador interage por meio dessa característica?
2. Qual decisão nova ela cria?
3. Como o jogador percebe seu efeito?
4. Ela altera preparação, execução ou consequência de uma atividade?
5. Pode ser representada por um sistema já existente?
6. O mesmo resultado pode ser alcançado com menos regras?
7. Ela é necessária para o primeiro protótipo?

Se essas respostas não forem claras, a ideia deve permanecer como elemento de mundo ou ser adiada.

## Profundidade emergente acima de complexidade sistêmica

O projeto deve preferir poucos sistemas capazes de se combinar de formas diferentes.

Exemplo desejado:

- uma aptidão influencia o desempenho básico;
- uma obsessão influencia motivação e atenção;
- experiência melhora atividades praticadas;
- equipamento define ferramentas e capacidades disponíveis;
- estado atual modifica temporariamente o desempenho.

Esses elementos podem produzir diferentes composições de equipe sem exigir dezenas de atributos independentes.

## Separação entre mundo e mecânica

Características culturais e biológicas não precisam gerar modificadores numéricos.

Podem existir apenas como:

- aparência;
- origem narrativa;
- falas e vocabulário;
- eventos;
- relações entre personagens;
- rituais;
- preferências visuais;
- contexto para escolhas.

Exemplos:

- ancestralidade pode influenciar aparência, reconhecimento e eventos sem alterar atributos;
- rituais podem aparecer em eventos e celebrações sem formar um sistema permanente;
- títulos podem registrar feitos sem conceder bônus automaticamente;
- manias podem aparecer em animações e falas sem exigir inteligência artificial específica.

## Design orientado à interação

Características de personagens devem ser definidas a partir das ações disponíveis no jogo.

O processo recomendado é:

1. definir as atividades que existem;
2. definir as decisões que o jogador toma ao atribuir personagens;
3. identificar quais diferenças entre goblins tornam essas decisões interessantes;
4. criar apenas as propriedades necessárias para representar essas diferenças.

Não se deve criar uma lista extensa de atributos primeiro e procurar usos para eles depois.

## Modelo mínimo provisório de personagem

Para orientar as próximas discussões, um goblin pode ser representado inicialmente por:

- identificação: nome, apelido, título e tribo;
- função atual no posto;
- uma aptidão principal;
- uma obsessão;
- experiência em atividades praticadas;
- equipamento;
- estado físico ou operacional atual.

Este modelo não é definitivo. Cada campo deverá ser validado contra atividades reais do protótipo.

## Critério para o primeiro protótipo

Uma característica só deve entrar no primeiro protótipo quando for necessária para validar pelo menos uma destas perguntas:

- vale a pena escolher goblins diferentes para uma tarefa?
- a preparação de uma equipe muda o resultado da expedição?
- a obsessão altera uma escolha ou comportamento observável?
- a experiência adquirida muda futuras possibilidades?
- equipamento e estado criam decisões de risco e oportunidade?

## Antiobjetivos

Evitar:

- atributos sem uso frequente e compreensível;
- bônus pequenos difíceis de perceber;
- necessidades que apenas criam cliques repetitivos;
- traços que exigem árvores complexas de comportamento;
- sistemas completos para elementos que funcionariam melhor como eventos;
- simulação detalhada sem impacto no core loop;
- personagens definidos por uma ficha maior do que a quantidade de decisões que oferecem.

## Direção

> Primeiro definimos o que o jogador faz. Depois definimos quais diferenças entre os goblins tornam essas ações interessantes.
