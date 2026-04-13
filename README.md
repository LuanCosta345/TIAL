# Divulgação Cultural Independente

## 1. Introdução

### Informações básicas do projeto

- **Projeto:** Divulgação Cultural Independente
- **Repositório GitHub:** [https://github.com/LuanCosta345/TIAL](https://github.com/LuanCosta345/TIAL)
- **Membros da equipe (Grupo 6):**
  - Gabriela Pinheiro Pierazolli
  - Luan de Assis Fonseca Moraes Costa
  - Luiza Morais Braga
  - Maria Fernanda Melo e Reis
  - Maria Luiza Aparecida Trindade de Meneses
  - Nubia Torres de Oliveira
  - Yuri Campos Silva

O projeto é uma plataforma na web que ajuda artistas independentes a ganharem visibilidade e facilita para bares e espaços de evento encontrarem e contratarem atrações com mais organização.

**Outros links úteis**

- Protótipo no Figma (TI — Projeto de Interfaces): [abrir no Figma](https://www.figma.com/design/LkoTl3oKDp301oRZIQ7S81/TI-Projeto-de-Interfaces?node-id=0-1&t=A83yy0KHKhqGcryK-1)
- Quadro Kanban (Trello): *(inserir link público do quadro quando o grupo tiver)*

A documentação do projeto é estruturada da seguinte forma:

1. Introdução
2. Contexto
3. Product Discovery
4. Product Design
5. Metodologia
6. Solução
7. Referências Bibliográficas

---

## 2. Contexto

### Problema

Na prática, muitos artistas independentes sofrem para conseguir espaço em palcos e para serem vistos além do círculo de amigos e do algoritmo das redes. Do outro lado, quem tem bar ou organiza evento pequeno também não tem um lugar simples para achar artista com estilo certo, ver material de apresentação e fechar um combinado sem depender de várias conversas soltas no WhatsApp ou no direct. O resultado é pouca divulgação para eventos menores, contratação desorganizada e comunicação que muitas vezes falha no meio do caminho.

### Um pouco de pesquisa (por que faz sentido falar disso)

Antes de fechar o tema, lemos notícias e relatórios sobre o mercado da música no Brasil e sobre como as pessoas usam internet e redes sociais. O que mais chamou atenção foi que o setor da música até cresce em faturamento em alguns recortes, mas isso não significa que todo mundo aparece: tem muita gente postando conteúdo e pouco “espaço” para quem está começando ou trabalha fora das grandes gravadoras. Quase todo mundo ouve música por streaming, e artistas costumam divulgar muito no Instagram e em apps parecidos — o que ajuda, mas nem sempre vira show pago ou agenda fechada. Também existem debates públicos sobre a vida de quem trabalha com arte (pressão, censura, insegurança), o que reforça que ter processos mais claros na contratação pode ajudar no dia a dia.

Não fizemos um estudo estatístico profundo; usamos isso mais para mostrar que o tema não é “inventado” e aparece na discussão sobre cultura e trabalho. Como referência de pesquisa documental, o grupo leu  relatórios do setor e textos sobre hábitos de consumo de música e uso de redes.

### Objetivo do Projeto

**Objetivo geral:** diminuir um pouco essa bagunça na informação entre quem faz show e quem precisa de atração, juntando perfil, busca e propostas num fluxo mais claro.

**Objetivos específicos**

- Dar para o artista montar um perfil com informações, vídeos e estilo, divulgar onde vai tocar e ver oportunidades com mais estrutura.
- Dar para o estabelecimento buscar artista (por exemplo por gênero), ver perfil com vídeo e mandar proposta pelo próprio sistema, sem uma interface cheia de passos desnecessários.

### Justificativa

A gente acha que vale a pena porque o problema aparece no dia a dia de quem vive de show e de quem programa evento, e dá para encarar no trabalho da disciplina: pensar em usuário, desenhar telas e depois implementar em web. O projeto junta necessidade real com o que a matéria pede (descoberta, design e desenvolvimento).

### Público-alvo

**Artistas independentes:** quem faz apresentação e hoje depende muito de rede social para se mostrar, mas sente falta de oportunidade organizada e de um lugar onde contratante ache fácil.

**Donos de bar e quem organiza evento:** quem escolhe atração e precisa decidir rápido, com informação no mesmo lugar (estilo, vídeo, contato pela plataforma).

**Sobre tecnologia:** a ideia é que quem use saiba o básico de celular e navegador, como já usa no dia a dia. Nada de fluxo complicado demais.

---

## 3. Product Discovery

O grupo seguiu uma linha próxima do **Design Thinking**: primeiro tentamos **entender** o problema (leituras e entrevistas em formato roteirizado), depois **organizamos** o que descobrimos (matriz CSD, stakeholders, persona), e por fim **sintetizamos** em insights para orientar o design da solução. Abaixo estão os principais artefatos.

### Matriz CSD

**Certezas**

- Artista independente costuma ter menos visibilidade que grandes nomes.
- Bar e espaço de evento precisam de atração para movimentar o lugar.
- A conversa entre artista e contratante muitas vezes é por mensagem solta, sem padrão.
- Evento pequeno sofre para divulgar.

**Suposições**

- Perfil com vídeo e estilo definido ajuda na hora de confiar no artista.
- Busca por gênero e proposta dentro do app podem acelerar o “sim” ou o “não”.
- Artistas preferem receber proposta num lugar só do que só no direct misturado com outras coisas.

**Dúvidas**

- Quais filtros o estabelecimento mais usa na prática.
- Como não deixar a tela pesada se o perfil tiver muita informação.
- O que mais atrapalha as pessoas a se cadastrarem ou voltarem a usar.

### Mapa de Stakeholders

**Quem é central:** artistas e estabelecimentos (são quem usam o sistema de verdade).

**Quem é importante:** o grupo que desenvolve e o professor da disciplina (entrega e avaliação).

**Quem influencia:** público que vai aos shows (sofre o efeito da programação) e movimentos culturais da cidade (podem divulgar ou criticar a ideia).

### Pesquisa e Entendimento

Combinamos leitura de materiais na internet com entrevistas **montadas pelo grupo** (não são entrevistas reais gravadas, mas seguem um roteiro e ajudam a explicar o problema como a gente enxerga). Falamos com dois tipos de artista e dois tipos de dono de estabelecimento, no papel, para tirar ideias de dor e de necessidade.

**Roteiro em linhas gerais:** por que faz show, onde divulga, onde trava na hora de fechar data, como escolhe atração, o que costuma dar errado na conversa (valor, horário, estilo), o que esperaria de um app assim.

**Artista A — cantora, 29 anos**

“Eu posto vídeo direto, mas o convite bom costuma vir quando alguém me indica. No direct fica misturado pedido de orçamento com coisa que nem é trabalho.”

**Artista B — instrumentista, 41 anos**

“Já perdi data porque a conversa ficou no grupo do Zap e ninguém fechou valor direito.”

**Estabelecimento A — dono de bar, 47 anos**

“Eu quero MPB que não seja ensurdecedor. Fico caçando hashtag no Insta, é meio sorte.”

**Estabelecimento B — organiza evento em espaço multiuso, 34 anos**

“Preciso de várias atrações no mês e não dá para negociar em três redes diferentes.”

**O que deu para tirar disso**

- Tanto artista quanto bar sentem falta de um jeito mais direto de se achar.
- Mensagem informal vira confusão e coisa que se perde.
- Vídeo e estilo claros ajudam na decisão.
- Faz sentido ter perfil, busca e proposta no mesmo lugar, sem tentar substituir 100% as redes, mas ordenando melhor o contato.

### Personas

**Jorge — artista**

Cantor, 35 anos. Usa rede social para mostrar trabalho e buscar espaço. Quer ser levado a sério e ter mais chances de show, mas sente que oportunidade boa aparece pouco e de forma desorganizada. Quer juntar repertório, estilo e vídeo num perfil só, ser achado por quem procura atração parecida e receber proposta num canal que não se perca.

---

## 4. Product Design

### Histórias de Usuário

**Artista (Jorge)**

1. Como artista, quero criar um perfil com informações, vídeos e estilo musical para que contratantes entendam meu trabalho.
2. Como artista, quero divulgar minhas apresentações para aumentar o alcance do meu calendário.
3. Como artista, quero buscar oportunidades de shows para encontrar convites alinhados ao meu perfil.
4. Como artista, quero receber propostas diretamente pelo aplicativo para centralizar negociações e reduzir perda de mensagens.

**Estabelecimento (Mateus)**

5. Como estabelecimento, quero buscar artistas por gênero para agilizar a curadoria da programação.
6. Como estabelecimento, quero visualizar perfis com vídeos para avaliar a adequação da atração ao meu espaço.
7. Como estabelecimento, quero contratar artistas pelo aplicativo para padronizar o fluxo de contratação.
8. Como estabelecimento, quero usar uma plataforma simples e organizada para reduzir retrabalho e erros de comunicação.

### Requisitos do Sistema

#### Requisitos funcionais

1. Cadastro, edição e visualização de perfil de artista, com dados básicos, estilo musical e mídia (link ou vídeo).
2. O artista pode cadastrar e listar apresentações ou oportunidades, com data e local conforme a gente definir na implementação.
3. O estabelecimento pode buscar e filtrar artistas (por exemplo por gênero) e abrir o perfil completo.
4. Envio e recebimento de propostas entre artista e estabelecimento dentro do sistema, com algum tipo de status para acompanhar.
5. Login e tipo de usuário (artista ou estabelecimento), com partes do site só para quem tem permissão.
6. O estabelecimento pode iniciar o fluxo de contratação a partir do perfil do artista (botão de proposta ou parecido).

#### Requisitos não funcionais

1. Usabilidade: telas claras, poucos passos confusos, mensagem de erro que dá para entender.
2. Desempenho: listas e perfil não podem ficar eternas para carregar no uso normal.
3. Segurança: senha guardada de forma adequada, site em HTTPS em produção, cada um só acessa o que é do seu tipo de conta.
4. Compatibilidade: uso razoável no celular e no computador, já que o público está acostumado a isso.

### Proposta de valor

**Dores do artista:** pouca visibilidade além do que posta nas redes; convite e proposta espalhados; dificuldade de mostrar rápido como é o show ao vivo.

**Dores do estabelecimento:** perder tempo caçando artista; não saber se combina com o espaço; conversa que não fecha direito.

**O que o artista ganha:** um perfil mais “profissional” num lugar só; chance maior de ser encontrado por quem já quer contratar; propostas num fluxo único.

**O que o estabelecimento ganha:** busca com filtro; perfil com vídeo; proposta mais padronizada e menos ida e volta perdida.

**Como a plataforma ajuda:** junta perfil, busca e canal de proposta para aproximar quem precisa de palco e quem precisa de atração, sem substituir totalmente Instagram ou WhatsApp, mas dando um caminho mais organizado.

### Projeto de Interface

#### Fluxo do usuário

A pessoa entra na aplicação, faz login como artista ou estabelecimento. O artista cuida do perfil, coloca vídeo e estilo, cadastra apresentações e pode ver oportunidades e propostas. O estabelecimento busca (por exemplo por gênero), abre o perfil, assiste ao material e manda proposta pelo sistema. A ideia é pouco clique entre “achei interessante” e “mandei proposta”.

#### Wireframes

São os rascunhos de tela em baixa fidelidade: onde fica menu, lista, formulário, área de vídeo. Serve para alinhar o fluxo antes de caprichar no visual final.

#### Protótipo interativo

[TI — Projeto de Interfaces no Figma](https://www.figma.com/design/LkoTl3oKDp301oRZIQ7S81/TI-Projeto-de-Interfaces?node-id=0-1&t=A83yy0KHKhqGcryK-1)

---

## 5. Metodologia

### Ferramentas

Usamos Visual Studio Code para programar, GitHub para código e histórico de alterações, Figma para telas e protótipo, WhatsApp ou Discord para conversar no grupo e Trello para organizar o que falta fazer.

**Links**

- GitHub: [https://github.com/LuanCosta345/TIAL](https://github.com/LuanCosta345/TIAL)
- Figma: [TI — Projeto de Interfaces](https://www.figma.com/design/LkoTl3oKDp301oRZIQ7S81/TI-Projeto-de-Interfaces?node-id=0-1&t=A83yy0KHKhqGcryK-1)
- Trello: *(link do quadro quando estiver público)*

### Organização da equipe

O grupo tenta seguir uma lógica parecida com Scrum: reunião para combinar o que fazer na semana ou no período, revisar o que saiu e ajustar o que ficou para depois. A divisão de papéis não é fixa o tempo todo, mas em cada sprint alguém fica mais focado em documentação e README, outra pessoa em telas e Figma, e outras em código e repositório — sempre combinando no grupo para ninguém ficar sozinho numa parte. Os nomes dos integrantes estão na **Introdução**.

### Kanban

No Trello usamos três colunas: A fazer, Em progresso e Concluído. Cada cartão pode ter nome de quem está fazendo e prazo da entrega da disciplina.

**Exemplos do que pode aparecer em cada coluna**

- A fazer: revisar texto do README; testar tela no celular; alinhar regra de proposta com o grupo.
- Em progresso: tela de login; busca por gênero; desenho da página de perfil no Figma.
- Concluído: matriz CSD combinada em reunião; wireframe da home; roteiro das entrevistas fictícias.
