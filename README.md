# Divulgação Cultural Independente

## 1. Introdução

**Nome do projeto:** Divulgação Cultural Independente

**Descrição geral:** Este repositório reúne o material e a documentação do projeto desenvolvido na disciplina **Trabalho Interdisciplinar: Desenvolvimento de Aplicações Web**, com foco em uma plataforma digital voltada à visibilidade de artistas independentes e à organização da busca e contratação de atrações por estabelecimentos.

**Links do projeto:**

| Recurso | Link |
|--------|------|
| Repositório GitHub | [https://github.com/LuanCosta345/TIAL](https://github.com/LuanCosta345/TIAL) |
| Protótipo (Figma) | [TI — Projeto de Interfaces (Figma)](https://www.figma.com/design/LkoTl3oKDp301oRZIQ7S81/TI-Projeto-de-Interfaces?node-id=0-1&t=A83yy0KHKhqGcryK-1) |
| Quadro Kanban (Trello) | *(inserir link público do quadro quando disponível)* |

---

## 2. Contexto do Projeto

### Problema

No cenário cultural local, artistas independentes enfrentam obstáculos recorrentes para obter oportunidades de apresentação e ampliar sua visibilidade. Em paralelo, estabelecimentos que desejam oferecer atrações vivenciam dificuldades para localizar artistas de maneira ágil e estruturada. Há pouca organização no processo de contratação, a comunicação entre artistas e contratantes costuma ser fragmentada ou inconsistente, e eventos de menor porte recebem pouca divulgação. Esse conjunto de fatores agrava a distância entre a oferta artística e a demanda por entretenimento em espaços como bares e pequenos eventos.

### Dados e evidências (pesquisa documental)

Para fundamentar o problema com **fatos e indicadores públicos** (não substituem pesquisa de campo exclusiva do grupo, mas embasam a relevância do tema):

- **Mercado fonográfico e crescimento:** o setor fonográfico brasileiro tem apresentado expansão de faturamento em série histórica recente; divulgações da imprensa especializada referem crescimento da ordem de **14%** em um ano e faturamento na casa de **bilhões de reais**, com o Brasil em posição de destaque em rankings globais do segmento (ex.: relatórios sectoriais e cobertura em veículos como a Agência Brasil). Isso mostra um ecossistema aquecido, mas **não elimina** a disputa por visibilidade no “miolo” dos artistas que buscam palco e renda em shows.
- **Streaming e descoberta:** o **streaming** concentra a maior parte das receitas do mercado fonográfico (ordem de grandeza frequentemente citada acima de **80%** das receitas em relatórios do setor). Há simultaneamente um volume massivo de conteúdo disponível, o que reforça a dificuldade de **destaque** sem estratégias adicionais além das plataformas de áudio.
- **Papel da produção independente em plataforma global:** comunicados de plataformas de streaming indicam que parcela relevante da receita associada a artistas brasileiros pode estar ligada a trajetórias **independentes** ou a ecossistemas fora apenas das majors tradicionais — o que sustenta a hipótese de um universo grande de artistas que precisam de **canais complementares** para shows e contato com contratantes.
- **Redes sociais como canal habitual:** estudos e relatórios sobre consumo digital no Brasil apontam penetração elevada de redes sociais na população; para artistas, isso traduz dependência de **Instagram, TikTok, WhatsApp** etc. para divulgação, com **algoritmo variável** e conversão incerta para agenda de apresentações paga.
- **Vulnerabilidade e ambiente de trabalho artístico:** organizações da sociedade civil e veículos especializados têm divulgado levantamentos sobre **insegurança, intimidação e autocensura** relatadas por artistas no Brasil, em percentuais elevados em alguns estudos — reforçando a necessidade de ambientes de contratação mais **previsíveis e respeitosos**, além de visibilidade.

As fontes consultadas para esses pontos estão relacionadas na seção **Referências Bibliográficas** (incluindo links para consulta e data de acesso ao elaborar o trabalho).

### Objetivo do Projeto

**Objetivo geral**

Contribuir para reduzir a assimetria de informação e a desorganização no contato entre artistas independentes e estabelecimentos, apoiando a descoberta de oportunidades, a apresentação de trabalhos e um fluxo de proposta mais claro.

**Objetivos específicos**

- Permitir que artistas cadastrem e atualizem perfis com informações relevantes (incluindo materiais como vídeos e definição de estilo), divulguem apresentações e acessem oportunidades de forma mais estruturada.
- Permitir que estabelecimentos busquem artistas por critérios como gênero, visualizem perfis com apoio de mídia (por exemplo, vídeos) e conduzam propostas de contratação por meio da plataforma, com interface simples e organizada.

### Justificativa

Valorizar a produção cultural independente e facilitar encontros entre oferta e demanda tem impacto direto na sustentabilidade de pequenos circuitos de shows e na diversidade de programação em espaços comerciais. Os **dados de mercado** mostram um setor dinâmico, porém com **concorrência acirrada por atenção**; os **hábitos digitais** mostram dependência de redes sociais sem garantia de fechamento de agenda; e relatos agregados de **estudos sobre a condição artística** reforçam a importância de processos mais claros. Um projeto que organize perfis, busca e comunicação reduz retrabalho, mal-entendidos e perda de oportunidades, beneficiando tanto quem performa quanto quem contrata. Do ponto de vista acadêmico, o tema integra experiência de usuário, modelagem de necessidades reais e desenvolvimento web aplicado a um problema socialmente relevante.

### Público-alvo

**Artistas independentes**

Profissionais ou semi-profissionais que produzem shows e dependem de canais informais (em especial redes sociais) para divulgação. Buscam mais oportunidades, reconhecimento e valorização, mas enfrentam dificuldade para encontrar convites e processos de contratação organizados.

**Donos de bares e responsáveis por eventos**

Pessoas que decidem programação e contratação de atrações. Precisam de soluções que agilizem a descoberta de artistas alinhados ao perfil do espaço e que centralizem informações para decisão (perfil, estilo, material audiovisual).

**Nível de tecnologia e comportamento**

Espera-se familiaridade básica a intermediária com internet e aplicativos móveis ou navegadores, uso habitual de redes sociais para comunicação e divulgação, e preferência por fluxos objetivos (cadastro, busca, visualização de perfil e envio ou recebimento de propostas sem etapas desnecessárias).

---

## 3. Product Discovery

### Matriz CSD

**Certezas**

- Artistas independentes costumam ter pouca visibilidade em relação a grandes nomes ou atrações já estabelecidas.
- Estabelecimentos precisam de atrações para compor programação e atrair público.
- A comunicação entre artistas e contratantes frequentemente é falha ou pouco padronizada.
- Pequenos eventos enfrentam limitações de divulgação.

**Suposições**

- Perfis com vídeos e informações de estilo aumentam a confiança na escolha do artista.
- Uma busca por gênero e uma contratação iniciada no próprio aplicativo reduzem o tempo entre interesse e proposta.
- Artistas valorizam receber propostas diretamente pela plataforma em vez de depender apenas de mensagens dispersas em redes sociais.

**Dúvidas**

- Quais critérios de busca e filtros são mais decisivos para estabelecimentos em diferentes portes de evento.
- Como equilibrar simplicidade da interface com a riqueza de informações no perfil do artista.
- Quais barreiras de adoção (cadastro, verificação de perfil, hábito de uso) afetam mais cada público.

### Mapa de Stakeholders

**Pessoas fundamentais**

- Artistas independentes: usuários finais que produzem conteúdo e buscam oportunidades.
- Estabelecimentos e organizadores de eventos: usuários finais que demandam atrações e definem contratação.

**Pessoas importantes**

- Equipe de desenvolvimento e design do projeto acadêmico: responsáveis por entregar a solução e documentar decisões.
- Docentes da disciplina: avaliam o alinhamento pedagógico, a metodologia e os entregáveis.

**Pessoas influenciadoras**

- Público frequentador dos espaços: indiretamente influenciado pela qualidade e variedade da programação.
- Comunidade e movimentos culturais locais: podem amplificar ou criticar o uso da plataforma conforme percebam benefícios reais.

### Pesquisa e Entendimento

O entendimento inicial combinou **pesquisa documental** (dados de mercado, hábitos digitais e relatórios sobre trabalho artístico) com **entrevistas semiestruturadas simuladas**, elaboradas a partir de um roteiro único de perguntas aplicado, em caráter acadêmico, a **dois perfis de artistas** e **dois perfis de donos de estabelecimentos**. A simulação permite documentar **padrões de dor e de necessidade** típicos do problema quando não há transcrição real de campo disponível no repositório.

**Roteiro (resumo):** motivações para shows; canais de divulgação; dificuldades para fechar agenda; como encontram ou selecionam atrações; o que falha na comunicação (prazo, valor, repertório); expectativa em relação a uma plataforma única.

#### Resultados simulados — Artista A (cantora independente, 29 anos)

- Relato: “Posto vídeo todo dia, mas o convite bom vem quando alguém me indica. No Direct mistura pedido de orçamento com spam.”
- Pontos recorrentes: dependência de **indicação**; **inbox** como canal de trabalho pouco organizado; necessidade de mostrar **show ao vivo** em vídeo para fechar bar.

#### Resultados simulados — Artista B (instrumentista, 41 anos)

- Relato: “Já perdi data porque a conversa ficou no grupo do WhatsApp e ninguém confirmou valor.”
- Pontos recorrentes: **falta de confirmação formal**; eventos pequenos com **divulgação fraca**; desejo de **agenda visível** para o público certo (contratante), não só seguidores.

#### Resultados simulados — Estabelecimento A (dono de bar, 47 anos)

- Relato: “Quero alguém de MPB que não seja barulhento demais. Fico caçando no Instagram por hashtag, é sorte.”
- Pontos recorrentes: **busca trabalhosa**; dificuldade de comparar **perfil + vídeo** em um só lugar; medo de **no-show** ou equívoco de estilo.

#### Resultados simulados — Estabelecimento B (organizador de eventos em espaço multiuso, 34 anos)

- Relato: “Preciso de três atrações no mês e não tenho tempo de ficar negociando em três redes diferentes.”
- Pontos recorrentes: necessidade de **padronização** (proposta, data, cache); prioridade para **filtro** (gênero, disponibilidade).

#### Insights obtidos (síntese)

- **Descoberta** é o gargalo para ambos os lados: artista não enxerga demanda organizada; estabelecimento não enxerga oferta classificável.
- **Comunicação informal** (redes sociais e mensagens) gera perda de informação e atraso na confirmação.
- **Prova social em vídeo** e **estilo musical explícito** reduzem incerteza na contratação.
- Há espaço para uma solução que una **perfil + busca + proposta** sem substituir totalmente as redes, mas **ordenando** o fluxo.

### Personas

**Jorge — artista**

- **Nome:** Jorge  
- **Idade:** 35 anos  
- **Profissão:** cantor  

Jorge utiliza redes sociais para divulgar seu trabalho e manter contato com seguidores. Busca ativamente oportunidades de shows e deseja reconhecimento e valorização pelo seu ofício. Apesar do esforço de presença online, encontra dificuldade para localizar convites e processos de contratação organizados, o que gera frustração e sensação de imprevisibilidade na carreira. Espera poder concentrar informações profissionais (repertório, estilo musical, vídeos) em um só lugar, ser encontrado por quem procura atrações compatíveis e receber propostas de forma direta e rastreável.

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

#### Requisitos Funcionais

| ID | Requisito |
|----|-----------|
| RF01 | O sistema deve permitir cadastro, edição e visualização de **perfil de artista**, incluindo dados básicos, **estilo musical** e **mídia** (ex.: links ou incorporação de vídeo). |
| RF02 | O sistema deve permitir ao artista **cadastrar e listar apresentações** ou oportunidades divulgadas, com informações mínimas de data e local (conforme regras de privacidade definidas na implementação). |
| RF03 | O sistema deve permitir ao estabelecimento **buscar e filtrar artistas** (ex.: por **gênero musical**) e **abrir o perfil completo** para decisão. |
| RF04 | O sistema deve permitir o **envio e o recebimento de propostas** entre estabelecimento e artista **pelo próprio sistema**, com registro para acompanhamento (estado da proposta). |
| RF05 | O sistema deve oferecer **autenticação de usuários** (login) e distinção de perfil (**artista** x **estabelecimento**), com áreas restritas conforme o papel. |
| RF06 | O sistema deve permitir ao estabelecimento **iniciar o fluxo de contratação** a partir do perfil do artista (ação explícita de proposta ou equivalente definido no protótipo). |

#### Requisitos Não Funcionais

| ID | Requisito |
|----|-----------|
| RNF01 | **Usabilidade:** interface objetiva, com linguagem clara e navegação consistente entre cadastro, busca e propostas; priorizar formulários curtos e feedback de erro compreensível. |
| RNF02 | **Desempenho:** páginas de listagem e perfil devem carregar em tempo aceitável em conexões típicas de banda larga móvel (metas quantitativas podem ser definidas na implementação, ex.: tempo máximo de carregamento inicial). |
| RNF03 | **Segurança:** armazenamento seguro de credenciais (ex.: senha com hash), uso de **HTTPS** em ambiente de produção e controle de acesso por sessão/perfil. |
| RNF04 | **Compatibilidade:** layout **responsivo** para acesso via navegador em desktop e smartphone, alinhado ao uso do público em redes sociais e mensagens. |

### Proposta de Valor (mapa sintético)

| Dimensão | Conteúdo |
|----------|----------|
| **Dores do usuário — Artista** | Pouca visibilidade além das redes; oportunidades desorganizadas; propostas espalhadas em canais diferentes; dificuldade de passar credibilidade (estilo + show) rapidamente. |
| **Dores do usuário — Estabelecimento** | Dificuldade de achar artista compatível com o espaço; tempo gasto em busca manual; comunicação falha ou incompleta; pequenos eventos com pouca divulgação estruturada. |
| **Ganhos esperados — Artista** | Perfil profissional centralizado; maior chance de ser encontrado por quem **já** busca atração; propostas em um só fluxo; divulgação de agenda. |
| **Ganhos esperados — Estabelecimento** | Busca por gênero e perfil com vídeo; decisão mais rápida; processo de proposta **padronizado**; menos retrabalho. |
| **Como a solução resolve** | A plataforma web **conecta** oferta e demanda com **perfil rico**, **busca/filtro**, **mídia de apoio** e **canal de propostas** integrado, reduzindo dependência exclusiva de mensagens informais e aproximando “quem precisa de palco” de “quem precisa de atração”. |

### Projeto de Interface

#### Fluxo do Usuário

De forma geral, o usuário acessa a aplicação web, identifica-se como artista ou estabelecimento e realiza cadastro ou login. O artista preenche e mantém o perfil, anexa ou associa vídeos e informações de estilo, cadastra ou divulga apresentações e consulta oportunidades; pode receber e acompanhar propostas enviadas por estabelecimentos. O estabelecimento utiliza busca e filtros (como gênero), abre perfis para avaliação com apoio de vídeo e envia ou formaliza proposta de contratação pela própria plataforma. O desenho prioriza poucos passos entre descoberta e ação (visualizar, contatar ou propor).

#### Wireframes

Os wireframes representam o esqueleto das telas em baixa fidelidade: disposição de blocos (cabeçalho, listas, formulários, área de mídia), hierarquia da informação e navegação entre cadastro, perfil, busca e propostas. Servem para validar fluxos antes do refinamento visual, sem definir ainda identidade gráfica final ou componentes estilísticos detalhados.

#### Protótipo Interativo

**Protótipo no Figma:** [TI — Projeto de Interfaces](https://www.figma.com/design/LkoTl3oKDp301oRZIQ7S81/TI-Projeto-de-Interfaces?node-id=0-1&t=A83yy0KHKhqGcryK-1)

---

## 5. Metodologia

### Ferramentas

| Ferramenta | Uso e justificativa |
|------------|---------------------|
| **Visual Studio Code** | Editor de código com suporte a extensões, depuração e integração com Git, adequado ao desenvolvimento web em equipe. |
| **GitHub** | Hospedagem do repositório, histórico de versões, revisão de alterações e colaboração assíncrona entre integrantes. |
| **Figma** | Design de interface, wireframes de média/alta fidelidade e prototipação para alinhar fluxos antes da implementação. |
| **WhatsApp ou Discord** | Comunicação rápida para alinhamentos, dúvidas e combinação de entregas entre membros do grupo. |
| **Trello** | Visualização de tarefas em cartões, acompanhamento de responsáveis e status, compatível com práticas ágeis leves. |

**Links:**

- GitHub: [https://github.com/LuanCosta345/TIAL](https://github.com/LuanCosta345/TIAL)  
- Figma: [TI — Projeto de Interfaces](https://www.figma.com/design/LkoTl3oKDp301oRZIQ7S81/TI-Projeto-de-Interfaces?node-id=0-1&t=A83yy0KHKhqGcryK-1)  
- Trello (Kanban): *(inserir link público do quadro quando disponível)*  

### Organização da Equipe

Adota-se **Scrum** de forma adaptada ao contexto acadêmico: reuniões periódicas para planejar o que será feito no período (similar a um sprint curto), revisão do que foi entregue e ajuste de prioridades. A equipe divide tarefas por frentes (por exemplo, documentação, pesquisa de usuário, design de interface, desenvolvimento front-end e back-end), com responsáveis definidos por item e registro de dependências entre entregas. O Product Owner acadêmico é representado pelos requisitos da disciplina e pelo escopo acordado pelo grupo; o time se autoorganiza para cumprir prazos e critérios de avaliação.

**Integrantes do Grupo 6**

- Gabriela Pinheiro Pierazolli  
- Luan de Assis Fonseca Moraes Costa  
- Luiza Morais Braga  
- Maria Fernanda Melo e Reis  
- Maria Luiza Aparecida Trindade de Meneses  
- Nubia Torres de Oliveira  
- Yuri Campos Silva  

### Kanban

O quadro no **Trello** utiliza as colunas **A Fazer**, **Em Progresso** e **Concluído**, com cartões contendo responsável, prazo da disciplina e critério de “pronto” combinado em equipe.

**Exemplos de tarefas por coluna (ilustrativos):**

| A Fazer | Em Progresso | Concluído |
|---------|--------------|-----------|
| Redigir RF/RNF na documentação | Implementar RF05 (login e perfis) | Pesquisa documental com fontes na seção Referências |
| Validar fluxo de proposta no Figma | Tela de busca por gênero (RF03) | Matriz CSD revisada em reunião |
| Testar responsividade (RNF04) em 2 breakpoints | Modelagem inicial do banco de dados | Wireframes da home e do perfil do artista |
| Configurar repositório e README no GitHub | Integração do formulário de perfil (RF01) | Definição do roteiro de entrevista simulada |

---

## 6. Solução

Trata-se de uma **plataforma web** que conecta **artistas independentes** e **estabelecimentos** interessados em atrações. A aplicação viabiliza perfis de artista com informações, vídeos e estilo musical; divulgação de apresentações; busca de oportunidades; recebimento de propostas pelos artistas; busca de artistas por gênero; visualização de perfis com vídeos; e fluxo de contratação iniciado ou conduzido pelo aplicativo, com ênfase em **simplicidade e organização** para o lado dos estabelecimentos. Os **requisitos funcionais e não funcionais** da seção 4 consolidam o escopo esperado para implementação e avaliação.

---

## 7. Referências Bibliográficas

Fontes consultadas para **dados de mercado**, **hábitos de consumo digital** e **apoio teórico** (UX e desenvolvimento web). Atualizar **datas de acesso** ao entregar o trabalho acadêmico.

- AGÊNCIA BRASIL. *Faturamento do mercado fonográfico brasileiro* — notícias sobre desempenho do setor e posicionamento do Brasil em rankings globais. Disponível em: [https://agenciabrasil.ebc.com.br/](https://agenciabrasil.ebc.com.br/) — buscar matérias recentes sobre mercado fonográfico e cultura.  
- PRÓ-MÚSICA BRASIL. Relatórios do **Mercado Brasileiro da Música** (séries anuais com receitas, participação do streaming e indicadores do setor). Disponível em: [https://pro-musicabr.org.br/](https://pro-musicabr.org.br/)  
- SPOTIFY NEWSROOM. Estatísticas e comunicados sobre **artistas brasileiros** e participação de produções independentes em plataformas de streaming (conferir texto e ano da publicação utilizada). Disponível em: [https://newsroom.spotify.com/](https://newsroom.spotify.com/)  
- RÁDIO COMUNITÁRIA / VEÍCULOS ESPECIALIZADOS. Reportagens sobre **estudos com artistas** (vulnerabilidade, censura, intimidação) — usar a matéria exata citada no trabalho com autor e data. Exemplo de busca: [https://www.radiocom.org.br/](https://www.radiocom.org.br/)  
- COOPER, Alan et al. *About Face: The Essentials of Interaction Design*. Wiley.  
- NORMAN, Don. *O Design do Dia a Dia*.  
- MDN Web Docs. Documentação de HTML, CSS e JavaScript. [https://developer.mozilla.org/](https://developer.mozilla.org/)  

---

*Projeto acadêmico — Disciplina: Trabalho Interdisciplinar: Desenvolvimento de Aplicações Web.*
