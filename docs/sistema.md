# Visão Geral do Sistema e Regras

## 1. Visão Geral do Sistema

A Cúpula opera em um formato de Campanha Viva focado em uma Guilda de Mercenários. O universo mistura fantasia medieval clássica com elementos de ficção científica (Sci-Fantasy).

* **Estrutura de Jogo:** A campanha é híbrida e assíncrona. Não há um grupo fixo ou horário engessado. Os jogadores interagem livremente por texto ou voz na base da guilda (fazendo Roleplay) e formam grupos rotativos sempre que uma nova missão é postada.
* **Progressão:** O avanço de nível é puramente baseado em Pontos de Experiência (XP) adquiridos ao completar contratos. O ganho de poder também está diretamente atrelado ao acúmulo de moedas e à coleta de *loot* para a melhoria de equipamentos.

## 2. Ambientação e Mundo

O mundo do jogo se passa em um vasto Arquipélago composto por ilhas de todos os tamanhos. A geografia é rica e abriga diversas cidades urbanizadas, vilarejos remotos, florestas densas, cordilheiras, lagos, rios e sistemas de cavernas profundas.

* **Mapas e Cartografia:** O universo é totalmente mapeado para facilitar a imersão. Os jogadores terão acesso a mapas gerais do arquipélago (mostrando relevo, estradas e cidades), mapas específicos de cada cidade ou vila, e mapas internos de edifícios (como castelos, tavernas e bases).
* **Grid de Batalha:** Quando a ação entra em masmorras (Dungeons) ou os jogadores entram em combates táticos declarados, o sistema utiliza o formato clássico de Grid de Batalha (mapas quadriculados, como no D&D tradicional) para definir movimentação e alcance.

## 3. Atributos de Batalha (Sistema d100) e Tiers

O sistema utiliza uma matemática clara de porcentagens (base 100), reduções fixas de dano e um sistema de **Tiers (Escalões)** que dita o poder do personagem conforme ele evolui. A liberdade de construção de personagem é total, sem amarras numéricas atreladas a classes ou raças na hora de distribuir os pontos.

* **Criação (Nível 1):** O jogador recebe 50 Pontos para distribuir livremente entre as características.
* **Evolução:** A cada novo nível alcançado, o jogador ganha +5 Pontos adicionais para distribuir onde quiser.

### O Sistema de Multiplicadores de Tier
Para garantir um crescimento balanceado do Nível 1 ao 20, o jogo é dividido em 4 Tiers. Este valor atua como um multiplicador direto para a Vida Máxima e para a quantidade de dados de dano rolados pelas habilidades e armas:
* **Tier 1** (Níveis 1 a 5): Multiplicador x1 (Média: Nível 3)
* **Tier 2** (Níveis 6 a 10): Multiplicador x2 (Média: Nível 8)
* **Tier 3** (Níveis 11 a 15): Multiplicador x3 (Média: Nível 13)
* **Tier 4** (Níveis 16 a 20): Multiplicador x4 (Média: Nível 18)

### A Economia de Pontos

* **Vida Máxima (PV):** Calculada somando a Vida Base da sua Classe com os seus pontos investidos. Fórmula: `Vida Base + (Pontos Investidos * 2 * Multiplicador de Tier)`.
* **Força:** Cada 1 ponto concede +1 de Dano Físico Fixo, somado ao dano total das habilidades corporais e armas físicas.
* **Arcana:** Cada 1 ponto concede +1 de Dano Mágico Fixo, somado ao dano total de magias e armamentos tecnológicos/arcanos.
* **Velocidade:** Define a sua Iniciativa no combate. Além disso, cada 2 pontos concedem +1 metro no deslocamento base e aumentam o alcance de habilidades de movimento.
* **Chance Crítica:** Cada 1 ponto concede +1% de chance de Acerto Crítico (um acerto crítico dobra o dano total final do ataque). **O limite máximo permitido para este atributo é 60%.**
* **Chance de Esquiva:** Cada 1 ponto concede +1% de chance de Esquiva (ignora o golpe completamente, resultando em zero dano). **O limite máximo permitido para este atributo é 60%.**
* **Armadura Física:** Cada 1 ponto investido concede -1 de Redução de Dano Fixo contra ataques físicos.
* **Armadura Mágica:** Cada 1 ponto investido concede -1 de Redução de Dano Fixo contra ataques mágicos.
* **Foco:** Cada 1 ponto concede +1% de chance de aplicar debuffs (efeitos de controle) em inimigos. 
* **Tenacidade:** Cada 1 ponto concede +1% de chance de resistir a debuffs ou controles de grupo inimigos.

## 4. A Resolução de Combate (A Regra do d100)

O combate no arquipélago foi desenhado para ser tático, mortal e ágil. Uma sequência completa de ataque é dividida em até 3 etapas rápidas, onde os dados definem tudo.

### Etapa 1: O Acerto (Esquiva vs Crítico)
Todo ataque começa com o atacante rolando um dado de cem faces (**1d100**). O resultado deste único dado cruza a Esquiva do defensor com a Chance Crítica do atacante.

1. **Erro (Esquiva):** Se o resultado for menor ou igual à Chance de Esquiva do alvo, o ataque erra completamente.
2. **Acerto Crítico:** Se o resultado for maior ou igual a **(100 - Chance Crítica do atacante + 1)**, o ataque é crítico e dobrará o dano rolado na Etapa 2.
3. **Acerto Normal:** Se o resultado cair na "zona morta" entre a Esquiva e o Crítico, o ataque acerta normalmente.

### Etapa 2: O Dano e a Mitigação
Se o ataque acertou, o atacante rola os dados referentes à arma ou habilidade utilizada e soma o seu atributo fixo. A quantidade de dados rolados é multiplicada pelo Tier atual do personagem. O alvo então subtrai a sua respectiva Armadura (Física ou Mágica) do dano bruto gerado.

### Etapa 3: Controle de Grupo e Efeitos (O Teste de Resistência)
Muitas habilidades e armas possuem efeitos secundários (como atordoar, sangrar ou enraizar) baseados em uma porcentagem de acerto. Para manter o engajamento, **quem rola o dado para definir se o efeito funcionou é sempre quem está recebendo o ataque.**

Antes de rolar o dado, o Mestre ou o Jogador calcula rapidamente a Chance Efetiva do efeito com a seguinte fórmula:
`Chance Base da Habilidade + Foco do Atacante - Tenacidade do Defensor`

O **defensor** deve rolar um dado de 100 faces (1d100). Se o resultado for **menor ou igual** à Chance Efetiva, o defensor falha em resistir e sofre o efeito. Se tirar um valor maior, ele resiste e ignora o controle de grupo.

## 5. O Turno de Combate, Ações e Equipamentos

O combate no Arquipélago é jogado em turnos sequenciais, definidos pela rolagem de Iniciativa (baseada no atributo Velocidade de cada personagem). O jogador entra na missão com um *loadout* tático de 10 habilidades fixas. Isso elimina a demora para escolher feitiços e foca a gameplay na estratégia.

Durante o seu turno, todo mercenário tem o direito de se mover pelo campo de batalha e utilizar três tipos distintos de ações, garantindo fluidez e escolhas táticas constantes.

### 5.1 A Regra de Movimentação
A capacidade de deslocamento de um personagem em combate é definida pelo seu porte biológico (Raça) somado ao seu treinamento (Atributo Velocidade). Em mapas quadriculados (Grid de Batalha), cada quadrado representa 1,5 metros.

* **Deslocamento Base por Porte:**
    * **Raças Pequenas** (Gnomos, Fadas, Greylins): 6 metros por turno (4 quadrados).
    * **Raças Médias** (Humanos, Elfos, Sintéticos): 9 metros por turno (6 quadrados).
    * **Raças Grandes** (Orcs, Draconatos, Nerunes): 12 metros por turno (8 quadrados).
* **O Modificador de Velocidade:** Cada 2 pontos investidos em Velocidade concedem +1 metro de movimentação extra ao deslocamento base.

O jogador pode quebrar a sua movimentação livremente. Por exemplo: andar 3 metros, executar uma ação, e depois andar os metros restantes do seu deslocamento.

### 5.2 A Economia de Ações (Os 10 Slots)
Durante o seu turno, você pode gastar suas ações para ativar os seus Slots de Batalha. Você possui uma de cada por turno:

* **1 Ação Principal (Slots 1 a 5 - Ataque/Manobra):** É a sua ofensiva principal. Representa os ataques mágicos ou físicos desferidos, definidos pela combinação exata da sua Classe com o tipo de Arma que está empunhando no momento.
* **1 Ação Bônus / Rápida (Slots 6 a 9):** Ações rápidas que não exigem o foco total do personagem. Englobam:
    * **Slot 6 (Cura/Suporte):** Habilidade exclusiva da Sub-classe. **Regra:** Só pode ser utilizada 1 vez por batalha, a menos que a sua Classe/Sub-classe diga explicitamente o contrário.
    * **Slots 7 e 8 (Raça):** Habilidades inatas e características únicas da sua Raça.
    * **Slot 9 (Movimento):** Ação extra de deslocamento tático e reposicionamento (como *dashes* ou teletransportes).
* **1 Ação Utilitária (Slot 10):** Uma ação voltada para a logística e adaptação no combate. Com a Ação Utilitária, você pode escolher **uma** das seguintes opções por turno:
    * **Troca Rápida:** Guardar sua arma atual e sacar uma arma secundária.
    * **Inventário:** Sacar e consumir um item rápido (como beber uma Poção ou usar um artefato).
    * **Preparar Ataque de Oportunidade:** Você fica em guarda. Se um inimigo passar do seu lado ou tentar fugir da sua zona de controle fora do seu turno, você o ataca automaticamente com o seu Slot 1.
    * **Socorrista:** Tentar levantar ou estabilizar um colega que caiu a 0 Pontos de Vida. 
        * *A Regra de Queda e Finalização:* Quando um personagem chega a 0 PV, ele desmaia e cai no chão, mas ainda está vivo e pode ser socorrido. Porém, se um inimigo o **FINALIZAR** (atacando propositalmente o personagem desmaiado), o jogador fica **INCAPACITADO** de voltar à luta atual sob qualquer circunstância e perderá sua recompensa e XP da missão.

### 5.3 Equipamentos, Raridade e Status Variáveis

Os itens moldam o poder defensivo e as passivas do personagem. Qualquer peça de equipamento (Armadura, Arma, Anel ou Colar) pode conceder bônus de pontos em qualquer um dos 10 atributos principais.

A qualidade e a raridade do equipamento (Comum, Raro, Épico, etc.) ditam a quantidade total de pontos concedidos e a variância desses status. Isso significa que encontrar uma armadura que conceda bônus específicos de Vida e Esquiva pode definir a *build* do personagem.

## 6. Estrutura de Missões, Sessões e Mestres

O sistema encoraja a colaboração contínua. A Guilda é um organismo vivo mantido por todos.

### A Rotação de Mestres
Qualquer pessoa na Guilda pode atuar tanto como Mestre (Comandante/Criador de Missão) quanto como Jogador (Aventureiro), sob condições estritas:
* **Padronização:** O Mestre voluntário deve seguir religiosamente as regras do sistema para a criação da missão, formatação dos mapas e o balanceamento na criação de inimigos.
* **Imparcialidade:** Um jogador é terminantemente proibido de atuar como um aventureiro na própria missão em que está mestrando. O seu personagem pessoal deve ficar na base da Guilda durante esse período.

### O Contrato (Quadro de Missões)
Os Mestres postam contratos no Quadro de Missões contendo todas as informações prévias. O acesso e as recompensas das missões são estritamente ditados pelo **Tier**. Jogadores de um Tier não podem participar de missões destinadas a outros Tiers.

* **Tier da Missão:** Define qual escalão de jogadores pode aceitar o contrato (Ex: Missão Tier 1 aceita apenas jogadores do Nível 1 ao 5).
* **Vantagem, Desvantagem e Multiplicadores de XP:** Cada Tier possui um Nível Médio (Tier 1 = Nv. 3; Tier 2 = Nv. 8; Tier 3 = Nv. 13; Tier 4 = Nv. 18). A quantidade de Pontos de Experiência recebida por cada jogador é baseada na sua distância em relação ao Nível Médio daquele Tier:
    * **2 Níveis de Desvantagem** (Ex: Nível 1 no Tier 1): Recebe **+200% de Exp** (missão extremamente letal).
    * **1 Nível de Desvantagem** (Ex: Nível 2 no Tier 1): Recebe **+150% de Exp** (missão muito perigosa).
    * **Sem Desvantagem** (Ex: Nível 3 no Tier 1): Recebe **100% da Exp** (missão balanceada).
    * **1 Nível de Vantagem** (Ex: Nível 4 no Tier 1): Recebe apenas **50% da Exp** (missão de baixo risco).
    * **2 Níveis de Vantagem** (Ex: Nível 5 no Tier 1): **Não ganha Exp**, apenas o valor da recompensa em dinheiro (missão trivial).
* **Quantidade Recomendada:** Número ideal de mercenários para o serviço.
* **Objetivo Principal.**
* **Objetivos Secundários:** Interesses adicionais que rendem bônus.
* **Local(is) de Atuação.**
* **Recompensa Base:** Valor em dinheiro pago por mercenário que concluir o trabalho (o nível do jogador não afeta o ganho financeiro, apenas o XP).
* **Descrição:** Breve descrição dos objetivos do trabalho.

## 7. A Sede da Guilda e Economia

A Guilda é o lar dos aventureiros, operando como um refúgio seguro e persistente.

* **Aposentos e Convívio:** Os personagens possuem espaços detalhados para interagir entre si livremente (um *RP infinito* via chat ou voz). É o local para desenvolver laços, rivalidades e táticas.
* **O Mercado da Guilda:** Jogadores podem negociar armas, artefatos e materiais livremente entre si. A Guilda possui uma Loja oficial administrada por NPCs, que recebe remessas periódicas de itens novos para aquisição.
* **Sistema de Moedas:** A economia gira em torno de metais.
    * 1 Moeda de Prata (PP) = 100 Moedas de Bronze (PB)
    * 1 Moeda de Ouro (PO) = 100 Moedas de Prata (PP)

## 8. Morte, Derrota e Desfiliação

A Guilda não financia o fracasso, mas o sistema poupa o jogador de perder o personagem definitivamente por causa de rolagens ruins de dados.

* **A Regra de Honra (Cair em Batalha):** Se um personagem chegar a 0 Pontos de Vida durante um combate, ele cai inconsciente e incapacitado pelo resto da luta. É uma regra estrita da Guilda que apenas quem termina o serviço de pé recebe o pagamento. O personagem caído **perde 100% da sua parcela da recompensa financeira e de loot da missão**, e **todo o XP ganho na sessão é irremediavelmente perdido**.
* **Doações e Camaradas:** A guilda não paga quem cai, mas os jogadores sobreviventes recebem os pagamentos deles normalmente. Se os aventureiros que ficaram de pé ficarem com pena e quiserem doar parte de seus próprios ganhos (moedas de ouro ou itens) para o companheiro caído, isso é totalmente permitido, mas deve ser feito puramente através do *roleplay* e da boa vontade, gerando dívidas de vida e dinâmicas sociais riquíssimas. Apenas o dinheiro pode ser doado; o XP é pessoal e intransferível.
* **Desfiliação (Troca de Personagem):** Personagens não morrem fisicamente no calor da batalha. A única forma de um personagem deixar de existir no mundo do jogo é se o próprio criador decidir aposentá-lo (seja por cansaço da classe ou encerramento de arco narrativo). Ele desafilia o personagem da Guilda e cria um mercenário inteiramente novo, começando obrigatoriamente do Nível 1.

## 9. Identidade e Roleplay (Perícias)

O "Mercenário" (seus atributos de combate) e a "Pessoa" (sua vivência e personalidade) são entidades distintas no sistema. Enquanto o combate utiliza a precisão matemática do d100, as interações narrativas, a exploração e a sua história de vida são representadas pelas **Perícias** e resolvidas através do clássico dado de vinte faces (**1d20**).

As perícias não evoluem automaticamente com os seus níveis de combate. Elas representam os seus talentos naturais e aquilo que você aprendeu antes ou fora das batalhas.

### A Regra de Distribuição de Pontos
Durante a criação do personagem, você deve distribuir um total exato de **15 pontos** entre as 18 perícias disponíveis. Para montar um personagem realista (com qualidades e defeitos), você deve seguir três regras matemáticas obrigatórias:

1. **A Soma Total:** A soma de todas as suas perícias (contando os números positivos e subtraindo os negativos) deve resultar em exatamente 15.
2. **O Limite Máximo (Especialista):** O valor máximo permitido em uma única perícia é **+6**.
3. **O Limite Mínimo (Falha de Personagem):** O valor mínimo obrigatório para uma perícia é **-4**. Pontuar negativo em uma perícia é uma excelente forma de ganhar pontos extras para gastar em outras áreas, além de render momentos de *roleplay* (interpretação) muito divertidos para o grupo, mostrando que o seu personagem é terrível em alguma coisa.

### Como Funcionam os Testes de Roleplay (A Regra do d20)
Fora de combate, sempre que o seu personagem tentar fazer algo que tenha chance de falha (como pular um abismo, mentir para um guarda ou hackear um terminal de Éter), o Mestre pedirá um "Teste de Perícia". 

A resolução é simples: role **1d20 e some (ou subtraia) o valor da sua perícia**. 
> **Exemplo Prático:** Você tenta intimidar um mercador corrupto. Sua perícia de Intimidação é +4. Você rola o 1d20 e tira 12. O seu resultado final é **16**. O Mestre compara esse 16 com a "Classe de Dificuldade" (CD) invisível que ele definiu para o mercador. Se a CD era 15, você conseguiu assustá-lo!

### Lista Oficial de Perícias

Abaixo estão as 18 perícias oficiais do sistema e o que elas cobrem dentro do mundo do Arquipélago:

| Perícia | Descrição e Exemplos de Uso no Mundo |
| :--- | :--- |
| **Acrobacia** | Equilíbrio e agilidade corporal. Usado para andar em parapeitos estreitos, amortecer quedas, escapar de amarras ou realizar manobras evasivas no cenário. |
| **Arcanismo** | Conhecimento sobre magia e Tecnologia de Éter. Usado para identificar feitiços, decifrar runas antigas ou entender o funcionamento de reatores alienígenas e cristais de plasma. |
| **Atletismo** | Força bruta e resistência física. Usado para escalar paredes íngremes de castelos, nadar contra correntezas, pular grandes distâncias ou empurrar objetos pesados. |
| **Atuação** | A arte do entretenimento e do disfarce. Usado para dançar, tocar instrumentos, atuar em uma peça ou fingir ser outra pessoa usando a linguagem corporal adequada. |
| **Enganação** | A arte de mentir e ocultar as próprias intenções. Usado para passar informações falsas a guardas da Cúpula, blefar em um jogo de cartas ou se fingir de morto. |
| **Furtividade** | Movimentação silenciosa e capacidade de se esconder. Usado para passar despercebido por patrulhas, esgueirar-se nas sombras ou seguir alguém sem ser notado. |
| **História** | Conhecimento sobre o passado do Arquipélago. Usado para lembrar de eventos de antes do Cataclismo, reconhecer a linhagem de reis antigos ou os tratados da Cúpula. |
| **Intimidação** | Impor medo e forçar a obediência. Usado para ameaçar capangas em uma taverna, arrancar informações à força ou fazer um inimigo recuar usando apenas a sua postura. |
| **Intuição** | Empatia e leitura de pessoas. Usado para perceber se alguém está mentindo para você, ler a linguagem corporal de um NPC ou prever as verdadeiras intenções de um aliado. |
| **Investigação** | Busca ativa e dedução lógica. Usado para procurar pistas em uma cena de crime, encontrar gavetas com fundo falso, ler contratos procurando entrelinhas e achar itens ocultos. |
| **Lidar com Animais** | Conexão com a fauna natural ou sintética. Usado para acalmar bestas nativas, domar montarias ou entender o comportamento de criaturas selvagens do mundo. |
| **Medicina** | Conhecimentos práticos de primeiros socorros e anatomia. Usado para estabilizar aliados sangrando fora de combate, diagnosticar doenças ou identificar causas de morte. |
| **Natureza** | Conhecimento sobre o meio ambiente, clima e sobrevivência. Usado para identificar plantas venenosas, prever tempestades ou entender a flora adaptada por tecnologia alienígena. |
| **Percepção** | Os seus cinco sentidos (visão, audição, faro, etc). É a perícia mais usada do jogo. Serve para ouvir passos distantes, notar inimigos escondidos ou farejar gás vazando. |
| **Persuasão** | Convencer pessoas de forma pacífica, diplomática ou sedutora. Usado para negociar recompensas melhores, fazer amizades ou convencer NPCs a ajudarem a guilda. |
| **Prestidigitação** | Agilidade manual e truques de mãos. Usado para bater carteiras no Eixo Mercantil, plantar evidências falsas, roubar chaves de guardas ou fazer truques de mágica. |
| **Religião** | Conhecimento sobre divindades, cultos e misticismo alienígena. Usado para reconhecer rituais sectários, os deuses antigos ou a filosofia cósmica e a cultura das naves Nerunes. |
| **Sobrevivência** | Capacidade de resistir na selva. Usado para rastrear pegadas na lama, acender fogueiras, encontrar água potável, caçar para comer ou se guiar pelas constelações caóticas. |

### 10. Raças (Estética e Slots 7 e 8)

No mundo de A Cúpula, a escolha da sua raça vai muito além do seu pano de fundo narrativo. Ela influencia diretamente quatro pilares vitais do seu personagem: o seu **tamanho** (porte físico), a sua **estética** principal, a sua **origem** cultural dentro do Arquipélago e, no momento do combate, as suas **Habilidades Inatas**.

A biologia e a herança histórica da sua espécie fornecem talentos únicos que outras raças não conseguem replicar. Durante a preparação para a batalha, os poderes da sua raça preenchem obrigatoriamente os **Slots 7 e 8** do seu *loadout* tático. Essas habilidades inatas podem ser características passivas contínuas (como visão no escuro aprimorada ou respiração subaquática) ou ações ativas poderosas (como um sopro elemental, um pulso telepático ou um teletransporte curto).

O Arquipélago abriga nove espécies principais unidas sob a Cúpula, categorizadas pelo seu porte físico:

* **Raças Grandes:** Orcs (nativos vulcânicos e guerreiros rústicos), Draconatos (herdeiros orgulhosos dos antigos dragões), Nerunes (alienígenas Arcturianos altos, esguios e de vasto intelecto cósmico).
* **Raças Médias:** Humanos (populosos, ambiciosos e dominantes do comércio), Elfos (longevos e sintonizados com as linhas de magia natural), Sintéticos (inteligências artificiais mágicas abrigadas em corpos robóticos alienígenas).
* **Raças Pequenas:** Gnomos (inventores supremos que misturam magia e metal), Fadas (seres feéricos erráticos e de ilusão impecável), Greylins (alienígenas clássicos do tipo "Grey", diminutos, furtivos e donos de fortes poderes mentais).

## 11. Classes e Sub-classes (Ditam Slots 1 a 6)

* **Guerreiro:** Samurai, Arqueiro de Guerra, Duelista, Inquisidor, Cavaleiro.
* **Bárbaro:** Berserker, Colosso, Fanático, Boxeador, Arauto.
* **Paladino:** Bastião, Carrasco, Algoz, Guardião, Renegado.
* **Ladino:** Ladrão, Assassino, Sombra, Acrobata, Atirador de Elite.
* **Patrulheiro:** Dançarino dos Ventos, Ninja, Alquimista, Curandeiro, Domador de Feras.
* **Mago:** Cronomancer, Necromancer, Ilusionista, Evocador, Lâmina Arcana.
* **Elementarista:** Piromante, Criomante, Litomante, Aeromante, Monge Astral.
* **Bruxo:** Simbionte Infernal, Espectro do Crepúsculo, Médium do Vazio, Parasita Sagrado, Bastião de Ossos.
* **Clérigo:** Bispo, Padre/Madre, Juiz, Sentinela, Profeta.
* **Engenheiro:** Artilheiro, Mecha, Médico de Combate, Demolidor, Tecnomante.