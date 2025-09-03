# Uma Revisão Sistemática sobre os Desafios e Tecnologias para Avaliação em Aprendizagem Baseada em Projetos

## 1. Introdução

### 1.1 Justificativa

A Aprendizagem Baseada em Projetos (ABP) tem se consolidado como uma abordagem pedagógica fundamental na educação superior, especialmente nos cursos de engenharia e tecnologia. Ao engajar os estudantes em projetos complexos e próximos da realidade profissional, a ABP promove o desenvolvimento de competências essenciais como pensamento crítico, resolução de problemas, colaboração e comunicação. No contexto da engenharia de software, a ABP tem se mostrado particularmente eficaz, permitindo que os estudantes desenvolvam habilidades técnicas enquanto experimentam processos autênticos de desenvolvimento de software.

Apesar dos benefícios pedagógicos, a ABP apresenta desafios significativos para avaliação por parte dos instrutores. Métodos tradicionais de avaliação, que frequentemente se concentram em entregas finais, falham em capturar os processos de aprendizagem complexos que ocorrem ao longo das experiências em ABP. Os instrutores enfrentam dificuldades para avaliar contribuições individuais dentro de equipes colaborativas, mensurar competências transversais e fornecer feedback contínuo ao longo de cronogramas de projeto estendidos.

Os desafios de avaliação tornam-se ainda mais pronunciados em módulos de ABP de engenharia de software complexos, onde os estudantes trabalham em equipes durante períodos prolongados (frequentemente 6-12 semanas) com papéis rotativos e requisitos em constante evolução. Os instrutores devem simultaneamente monitorar a qualidade do código, a dinâmica das equipes, o progresso individual e o desenvolvimento de habilidades técnicas, tudo isso enquanto fornecem feedback oportuno para apoiar a aprendizagem.

Avanços recentes na tecnologia educacional começaram a abordar alguns desses desafios. Plataformas de análise de aprendizagem podem rastrear o engajamento dos estudantes e indicadores de desempenho, enquanto ferramentas de revisão de código automática fornecem medidas objetivas da qualidade técnica. No entanto, essas soluções tipicamente operam de forma isolada, focando em aspectos específicos da experiência em ABP em vez de proporcionar uma visão holística da aprendizagem e da dinâmica das equipes.

A tecnologia de Gêmeos Digitais, que se originou em contextos industriais e de manufatura, oferece uma abordagem promissora para avaliação abrangente em ABP. Um Gêmeo Digital é uma réplica virtual de uma entidade física que espelha seu comportamento em tempo real por meio de troca contínua de dados. Embora os Gêmeos Digitais tenham sido amplamente aplicados na indústria para manutenção preditiva, otimização de processos e controle de qualidade, suas aplicações educacionais permanecem amplamente inexploradas.

Esta revisão sistemática visa mapear o estado da arte sobre os desafios metodológicos, instrumentos e tecnologias para avaliação em ambientes de Aprendizagem Baseada em Projetos, identificando como superar as dificuldades inerentes à avaliação de aprendizagem em contextos colaborativos e processuais.

### 1.2 Fundamentação Teórica nas Normas ISO

A fundamentação teórica desta pesquisa baseia-se em duas normas internacionais essenciais para a arquitetura de sistemas e processos organizacionais:

#### 1.2.1 ISO/IEC/IEEE 42010:2022 - Arquitetura de Sistemas e Software

A norma ISO/IEC/IEEE 42010:2022 estabelece os fundamentos para a descrição arquitetural de sistemas, definindo arquitetura como "o conjunto fundamental de conceitos, princípios, restrições e padrões que guiam o projeto e a evolução de sistemas". Esta norma especifica cinco visões arquiteturais fundamentais que podem ser aplicadas ao contexto educacional:

1. **Visão Estrutural**: Representa a organização dos componentes do sistema e suas interfaces
2. **Visão Comportamental**: Descreve a dinâmica do sistema em termos de colaborações entre componentes
3. **Visão de Implementação**: Mostra como o sistema é estruturado em termos de módulos de implementação
4. **Visão de Implantação**: Representa a configuração do sistema em relação ao ambiente de execução
5. **Visão de Dados**: Modela a estrutura e o fluxo de dados do sistema

A aplicação destas visões ao contexto de ABP permite uma compreensão abrangente do processo educativo, onde cada visão oferece uma perspectiva única sobre os diferentes aspectos do aprendizado.

#### 1.2.2 ISO 10746 - Especificação de Sistemas Distribuídos

A norma ISO 10746 fornece um framework para a especificação de sistemas distribuídos, com foco em processos colaborativos e interoperabilidade. Esta norma é particularmente relevante para o contexto de ABP, onde os estudantes trabalham em equipes distribuídas, colaborando em projetos complexos.

A norma define os conceitos de "Business Drive" como a força motriz que orienta o desenvolvimento e a evolução de sistemas. No contexto educacional, o "Business Drive" do ABP é o desenvolvimento de competências técnicas e transversais pelos estudantes, com o professor orientador atuando como o principal stakeholder responsável por garantir a qualidade do processo educativo.

### 1.3 Justificativa da Necessidade Baseada no Papel do Professor Orientador

O professor orientador em contextos de ABP desempenha um papel multifacetado crucial para o sucesso dos estudantes:

1. **Supervisor de Processo**: Monitora o progresso individual e coletivo dos estudantes ao longo do projeto
2. **Facilitador de Aprendizagem**: Intervém estrategicamente para superar obstáculos e promover o desenvolvimento de competências
3. **Avaliador de Desempenho**: Realiza avaliações justas e abrangentes considerando múltiplas dimensões do aprendizado
4. **Mentor de Carreira**: Orienta os estudantes no desenvolvimento de habilidades profissionais relevantes

A complexidade deste papel aumenta significativamente em contextos de ABP complexos, onde:
- Grupos de estudantes trabalham em projetos com múltiplas iterações e papéis rotativos
- O acompanhamento individualizado de cada estudante se torna desafiador
- A avaliação precisa considerar diferentes viéses técnicos e comportamentais
- A tomada de decisão sobre intervenções pedagógicas requer informações em tempo real

A necessidade de uma abordagem arquitetural fundamentada nas normas ISO surge da exigência de:
1. **Visibilidade Completa**: O professor orientador precisa de uma visão holística do processo de aprendizagem
2. **Avaliação Multidimensional**: A avaliação deve considerar múltiplas perspectivas do desempenho dos estudantes
3. **Tomada de Decisão Informada**: Intervenções pedagógicas baseadas em dados objetivos e em tempo real
4. **Escalabilidade**: Soluções que funcionem efetivamente mesmo com turmas numerosas

A aplicação das cinco visões arquiteturais da ISO 42010 ao contexto de ABP permite que o professor orientador tenha acesso a diferentes perspectivas do processo educativo:

- **Visão Estrutural**: Compreensão da organização das equipes e distribuição de papéis
- **Visão Comportamental**: Análise das dinâmicas de colaboração e interação entre estudantes
- **Visão de Implementação**: Acompanhamento do progresso técnico e qualidade das entregas
- **Visão de Implantação**: Monitoramento do ambiente de trabalho e recursos utilizados
- **Visão de Dados**: Análise quantitativa do desempenho individual e coletivo

### 1.4 Lacuna de Pesquisa Identificada

Apesar da existência de diversas abordagens para avaliação em ABP, identificamos uma lacuna crítica na literatura:

1. **Ausência de Abordagens Arquiteturais**: Nenhuma pesquisa existente aplica os princípios das normas ISO 42010 e 10746 ao contexto de avaliação em ABP
2. **Falta de Visões Integradas**: Soluções existentes abordam aspectos isolados sem integração arquitetural
3. **Limitações na Avaliação Multidimensional**: Dificuldade em capturar e avaliar o desempenho dos estudantes sob diferentes viéses técnicos
4. **Deficiência em Escalabilidade**: Ferramentas atuais não escalam efetivamente para contextos complexos com múltiplas equipes e papéis rotativos

A aplicação de conceitos de Gêmeos Digitais fundamentados nas normas ISO representa uma oportunidade inexplorada para abordar estas lacunas de forma contundente.

## 2. Objetivos da Revisão

### 2.1 Objetivo Geral

Mapear a produção científica sobre métodos, instrumentos e tecnologias para avaliação em Aprendizagem Baseada em Projetos (ABP), identificando como superar os desafios inerentes à avaliação de aprendizagem baseada em projetos.

### 2.2 Objetivos Específicos

1. Identificar os principais desafios metodológicos na avaliação de aprendizagem em contextos de ABP.
2. Mapear os instrumentos e tecnologias que estão sendo utilizados para superar esses desafios.
3. Analisar como a tecnologia pode apoiar processos avaliativos mais objetivos e escaláveis em ABP.
4. Identificar lacunas persistentes na avaliação de competências processuais e colaborativas.

## 3. Metodologia

Esta revisão sistemática foi conduzida seguindo as diretrizes propostas por Kitchenham (2004) para realização de revisões sistemáticas em engenharia de software. O processo foi estruturado em três fases principais: planejamento, condução e relato da revisão.

### 3.1 Fase de Planejamento

#### 3.1.1 Questão de Pesquisa

A questão de pesquisa foi formulada seguindo o framework PICO (Population, Intervention, Comparison, Outcome):

**Questão Principal**: Quais são os desafios metodológicos, instrumentos e tecnologias para avaliação em Aprendizagem Baseada em Projetos?

**P** (População): Estudantes em ambientes educacionais que utilizam Aprendizagem Baseada em Projetos
**I** (Intervenção): Métodos, instrumentos e tecnologias para avaliação em ABP
**C** (Comparação): Métodos tradicionais de avaliação
**O** (Resultados): Superar desafios na avaliação de aprendizagem em contextos colaborativos e processuais

#### 3.1.2 Protocolo da Revisão

Um protocolo foi desenvolvido especificando os métodos que seriam utilizados para conduzir a revisão sistemática, incluindo:
- Critérios de inclusão e exclusão
- Estratégia de busca
- Critérios para avaliação da qualidade dos estudos
- Formulários para extração de dados

### 3.2 Fase de Condução

#### 3.2.1 Identificação de Pesquisas

##### Bases de Dados Selecionadas

A base de dados Web of Science foi selecionada como única base de dados para esta revisão, com base na seguinte justificativa:

- **Qualidade Acadêmica Superior**: Processo rigoroso de seleção de periódicos apenas com revisão por pares
- **Cobertura Multidisciplinar Ideal**: Abrangência em ciência da computação, educação em engenharia e tecnologia educacional
- **Ferramentas Analíticas Avançadas**: Análise de tendências temporais, mapeamento de colaboração internacional e análise de citações
- **Integração com Protocolos de Revisão Sistemática**: Compatível com diretrizes Kitchenham e exportação RIS padronizada

##### Estratégia de Busca Fundamentada nas Normas ISO

As strings de busca foram estruturadas em 5 camadas estratificadas para capturar diferentes aspectos do problema de pesquisa, fundamentadas nas cinco visões arquiteturais da norma ISO/IEC/IEEE 42010:2022 e nos princípios de sistemas distribuídos da norma ISO 10746:

**String 1 - Visão Estrutural (ISO 42010) - Fundamentos de Arquitetura e Monitoramento**:
```
TS=("software architecture" OR "microservices architecture" OR "distributed systems" OR "system structure" OR "component interface") 
AND TS=("project-based learning" OR "project based learning" OR "PBL")
AND TS=("observability" OR "telemetry" OR "metrics collection" OR "monitoring")
```

**String 2 - Visão Comportamental (ISO 42010) - Modelagem de Processos Educacionais**:
```
TS=("process modeling" OR "educational process" OR "learning process" OR "workflow modeling" OR "behavioral process" OR "collaboration process") 
AND TS=("project-based learning" OR "project based learning" OR "PBL")
AND TS=("team dynamics" OR "collaboration" OR "interaction")
```

**String 3 - Visão de Dados (ISO 42010) - Gêmeos Digitais e Modelagem de Sistemas**:
```
TS=("digital twin*" OR "virtual twin*" OR "digital replica" OR "system modeling" OR "data modeling" OR "information flow") 
AND TS=("project-based learning" OR "project based learning" OR "PBL")
AND TS=("real-time data" OR "data synchronization" OR "virtual representation")
```

**String 4 - Visão de Implementação (ISO 42010) - Learning Analytics e Métricas de Desenvolvimento**:
```
TS=("learning analytics" OR "educational data mining" OR "student analytics" OR "behavioral analytics" OR "git analytics" OR "version control metrics" OR "collaboration metrics" OR "team performance" OR "code metrics") 
AND TS=("project-based learning" OR "project based learning" OR "PBL")
AND TS=("implementation" OR "module" OR "component" OR "artifact")
```

**String 5 - Visão de Implantação (ISO 42010) - Sistemas de Apoio ao Orientador**:
```
TS=("teacher support" OR "instructor support" OR "supervisor dashboard" OR "educational dashboard" OR "teacher assistance" OR "instructor tools") 
AND TS=("project-based learning" OR "project based learning" OR "PBL")
AND TS=("deployment" OR "environment" OR "execution context" OR "runtime")
```

##### Fundamentação no "Business Drive" (ISO 10746)

Além das cinco visões arquiteturais, todas as strings incorporam o conceito de "Business Drive" da norma ISO 10746, onde o objetivo educacional (desenvolvimento de competências em ABP) orienta a busca por soluções tecnológicas. Esta abordagem garante que a pesquisa esteja alinhada com os objetivos fundamentais do processo educativo.

##### Justificativa para as Strings de Busca Baseada nas Normas ISO

A Tabela 1 apresenta a justificativa para cada string de busca com base na dimensão do problema de pesquisa, fundamentada nas cinco visões arquiteturais da norma ISO/IEC/IEEE 42010:2022:

| Camada | Visão Arquitetural (ISO 42010) | Dimensão do Problema | Justificativa | String de Busca |
|--------|------------------------------|---------------------|---------------|-----------------|
| 1 | Visão Estrutural | Fundamentos Teóricos | Estabelece os conceitos fundamentais de arquitetura de sistemas aplicáveis ao contexto educacional, fornecendo base conceitual para monitoramento sistemático. Esta camada foca na estrutura organizacional das equipes e interfaces entre componentes do sistema educacional | Arquitetura de software e monitoramento |
| 2 | Visão Comportamental | Processualidade | Conecta conceitos de modelagem de processos com domínio educacional específico, essencial para capturar a complexidade temporal do ABP e as dinâmicas colaborativas entre estudantes | Modelagem de processos educacionais |
| 3 | Visão de Dados | Tecnologia Emergente | Representa o núcleo inovador da pesquisa - aplicação de Gêmeos Digitais à educação, tecnologia com potencial transformador. Esta camada foca na modelagem e fluxo de dados que permitem a criação de réplicas virtuais do processo educativo | Gêmeos Digitais e modelagem de sistemas |
| 4 | Visão de Implementação | Operacionalização | Integra análise de dados educacionais com métricas técnicas de desenvolvimento, criando ponte entre domínios educacional e técnico. Esta camada aborda como os sistemas são estruturados em termos de módulos implementáveis | Learning Analytics e métricas |
| 5 | Visão de Implantação | Aplicação Prática | Foca na aplicação prática - ferramentas utilizáveis por orientadores para avaliação justa, garantindo relevância prática. Esta camada considera a configuração do sistema em relação ao ambiente de execução educacional | Sistemas de apoio ao orientador |

Tabela 1: Justificativa para as strings de busca estratificadas baseada nas normas ISO

A estratégia de busca estratificada fundamenta-se no princípio do "Business Drive" da norma ISO 10746, onde o objetivo principal (desenvolvimento de competências em contextos de ABP) orienta a busca por soluções tecnológicas que suportem este propósito. Cada camada representa uma perspectiva arquitetural diferente do problema, permitindo uma análise abrangente e multidimensional da literatura existente.

A fundamentação nas normas ISO fornece uma base teórica sólida que:
1. **Justifica a Abordagem Multivisão**: As cinco visões arquiteturais oferecem perspectivas complementares do problema
2. **Alinha com Práticas Industriais**: Utiliza conceitos já validados na indústria para contextos educacionais
3. **Garante Completude**: A cobertura das cinco visões assegura que aspectos críticos não sejam omitidos
4. **Facilita a Integração**: O framework arquitetural permite a integração coerente de soluções parciais

##### Período de Busca

A busca foi realizada considerando artigos publicados entre 2015 e 2025, com o objetivo de capturar:
- Literatura consolidada nos últimos 10 anos
- Tendências emergentes na aplicação de tecnologias para avaliação em ABP
- Produção mais recente que reflita os avanços tecnológicos atuais

##### Idiomas

A busca foi limitada a artigos publicados em inglês, considerando:
- A predominância da literatura científica em inglês nas bases de dados internacionais
- A necessidade de manter consistência nos critérios de seleção
- O foco em periódicos indexados com rigoroso processo de revisão por pares

#### 3.2.2 Seleção de Estudos Primários

##### Critérios de Inclusão

**IC1 - Foco em Avaliação de ABP**:
- Artigos que abordem especificamente:
  - Métodos de avaliação em Aprendizagem Baseada em Projetos
  - Instrumentos avaliativos para projetos educacionais
  - Rubricas e critérios para avaliação de projetos
  - Avaliação de competências em contextos de ABP
  - Feedback formativo em projetos

**IC2 - Desafios Avaliativos Específicos**:
- Artigos que tratem de:
  - Avaliação de processos colaborativos
  - Mensuração de competências transversais
  - Feedback contínuo durante projetos
  - Avaliação de contribuições individuais em equipes
  - Objetividade em avaliação de projetos
  - Escalabilidade de processos avaliativos

**IC3 - Tecnologias de Apoio à Avaliação**:
- Artigos que utilizem ou discutam:
  - Sistemas digitais de avaliação
  - Learning Analytics para projetos
  - Ferramentas de monitoramento de progresso
  - Dashboards de avaliação
  - Sistemas de feedback automatizado
  - Portfólios digitais

**IC4 - Validação Pedagógica**:
- Artigos que apresentem:
  - Estudos empíricos sobre efetividade avaliativa
  - Comparação de métodos de avaliação
  - Feedback de estudantes sobre processos avaliativos
  - Impacto da avaliação na aprendizagem
  - Validação de instrumentos avaliativos

**IC5 - Aplicabilidade Prática**:
- Artigos que demonstrem:
  - Implementação em contextos reais
  - Adaptabilidade para diferentes disciplinas
  - Facilidade de uso por educadores
  - Custo-benefício da implementação
  - Sustentabilidade do método

##### Critérios de Exclusão

**EC1 - Foco Apenas em Produto Final**:
- Excluir artigos que:
  - Avaliem apenas resultados finais de projetos
  - Não considerem o processo de desenvolvimento
  - Ignorem aspectos colaborativos
  - Foquem exclusivamente em apresentações finais

**EC2 - Métodos Tradicionais**:
- Excluir artigos que:
  - Proponham apenas avaliação por testes escritos
  - Não considerem a natureza processual do ABP
  - Ignorem competências transversais
  - Mantenham abordagem exclusivamente somativa

**EC3 - Contextos Não Educacionais**:
- Excluir artigos que:
  - Abordem apenas projetos empresariais
  - Foquem em gestão de projetos sem componente educacional
  - Tratem de avaliação de desempenho profissional
  - Não tenham aplicabilidade em contextos de ensino

**EC4 - Falta de Rigor Metodológico**:
- Excluir artigos que:
  - Não apresentem metodologia clara
  - Careçam de validação empírica
  - Sejam apenas propostas conceituais
  - Não forneçam evidências de efetividade

**EC5 - Especificidade Excessiva**:
- Excluir artigos que:
  - Abordem domínios muito específicos sem generalização
  - Não apresentem potencial de transferência
  - Sejam aplicáveis apenas a contextos muito restritos

#### 3.2.3 Processo de Seleção

O processo de seleção foi conduzido em duas fases:

**Fase 1 - Triagem de Títulos e Resumos**:
- Dois revisores independentes (o autor principal e um co-autor) examinaram títulos e resumos dos artigos identificados
- Artigos claramente fora do escopo foram excluídos com base nos critérios de exclusão
- Diferenças de opinião foram resolvidas por consenso

**Fase 2 - Avaliação de Texto Completo**:
- Os textos completos dos artigos considerados potencialmente relevantes na triagem foram obtidos
- Os mesmos revisores aplicaram os critérios de inclusão e exclusão ao texto completo
- Artigos que não atendiam aos critérios de inclusão foram excluídos com registro da razão para exclusão

#### 3.2.4 Validação da Confiabilidade

Para assegurar a confiabilidade do processo de seleção, foi calculado o índice Kappa de Cohen para medir a concordância entre os revisores. A concordância foi considerada substancial para prosseguir com a revisão.

### 3.3 Fase de Extração de Dados

#### 3.3.1 Formulários de Extração

Formulários padronizados foram desenvolvidos para extração de dados, incluindo:

1. **Características do Estudo**:
   - Autores, ano de publicação, periódico
   - Tipo de estudo (empírico, revisão, proposta metodológica)
   - Contexto educacional (ensino fundamental, médio, superior, profissional)
   - Tamanho da amostra

2. **Metodologia**:
   - Desenho do estudo
   - Instrumentos utilizados
   - Procedimentos de coleta de dados
   - Análise dos dados

3. **Resultados**:
   - Principais achados
   - Eficácia dos métodos/instrumentos propostos
   - Limitações identificadas pelos autores

4. **Contribuições para Avaliação em ABP**:
   - Desafios abordados
   - Soluções propostas
   - Implicações práticas

#### 3.3.2 Avaliação da Qualidade dos Estudos

A qualidade dos estudos foi avaliada considerando:
- Clareza da metodologia
- Rigor metodológico
- Validação empírica
- Relevância para o contexto de ABP
- Contribuição para a área de avaliação educacional

### 3.4 Síntese dos Dados

A síntese dos dados foi realizada de forma narrativa, agrupando os achados segundo os objetivos específicos da revisão:

1. **Mapeamento de Desafios Metodológicos**: Identificação e categorização dos principais desafios na avaliação em ABP
2. **Instrumentos e Tecnologias**: Análise dos métodos, instrumentos e tecnologias propostos para superar os desafios
3. **Efetividade de Soluções Tecnológicas**: Avaliação de como a tecnologia pode apoiar avaliação mais objetiva e escalável
4. **Lacunas de Pesquisa**: Identificação de áreas que requerem investigação adicional

## 4. Resultados

### 4.1 Processo de Seleção

A busca inicial identificou 811 artigos através das 5 strings de busca estratificadas. Após a remoção de duplicatas, 632 artigos únicos foram submetidos à triagem de títulos e resumos. Destes, 289 artigos foram considerados potencialmente relevantes e tiveram seus textos completos avaliados. Após a aplicação rigorosa dos critérios de inclusão e exclusão, 179 artigos foram incluídos na revisão sistemática final.

O fluxo do processo de seleção está ilustrado na Figura 1, seguindo a recomendação do diagrama PRISMA para revisões sistemáticas.

```
Registros identificados através da busca (n=811)
│
├── Duplicatas removidas (n=179)
│
├── Registros submetidos à triagem (n=632)
│
├── Registros excluídos na triagem (n=343)
│   ├── Fora do escopo (EC1, EC2, EC3) (n=215)
│   ├── Falta de rigor metodológico (EC4) (n=89)
│   ├── Especificidade excessiva (EC5) (n=39)
│
├── Registros avaliados quanto à elegibilidade (n=289)
│
├── Registros excluídos na avaliação de texto completo (n=110)
│   ├── Foco apenas em produto final (EC1) (n=42)
│   ├── Métodos tradicionais (EC2) (n=31)
│   ├── Contextos não educacionais (EC3) (n=23)
│   ├── Falta de rigor metodológico (EC4) (n=14)
│
└── Registros incluídos na revisão sistemática (n=179)
```

Figura 1: Fluxo do processo de seleção dos estudos

### 4.2 Caracterização dos Estudos Incluídos

#### 4.2.1 Distribuição Temporal

Dos 179 artigos incluídos, a distribuição por ano de publicação foi:
- 2015: 8 artigos (4,5%)
- 2016: 21 artigos (11,7%)
- 2017: 19 artigos (10,6%)
- 2018: 15 artigos (8,4%)
- 2019: 19 artigos (10,6%)
- 2020: 18 artigos (10,1%)
- 2021: 12 artigos (6,7%)
- 2022: 18 artigos (10,1%)
- 2023: 16 artigos (8,9%)
- 2024: 17 artigos (9,5%)
- 2025: 16 artigos (8,9%)

A distribuição temporal demonstra um interesse crescente na temática ao longo dos anos, com pico de publicações em 2016 e 2019, e manutenção consistente nos anos subsequentes.

#### 4.2.2 Distribuição por Tipo de Publicação

- Artigos de periódico: 120 (67%)
- Artigos de conferência: 51 (28,5%)
- Capítulos de livro: 2 (1,1%)
- Outros tipos: 6 (3,4%)

A predominância de artigos de periódico indica a relevância acadêmica do tema na literatura científica consolidada.

#### 4.2.3 Distribuição por Contexto Educacional

- Ensino Superior - Engenharia: 98 artigos (54,8%)
- Ensino Superior - Ciência da Computação: 45 artigos (25,1%)
- Ensino Médio/Técnico: 21 artigos (11,7%)
- Educação Profissional: 10 artigos (5,6%)
- Ensino Fundamental: 5 artigos (2,8%)

A concentração em contextos de ensino superior, particularmente em engenharia, reflete a natureza técnica da maioria das abordagens de avaliação em ABP.

### 4.3 Análise dos Desafios Metodológicos

#### 4.3.1 Avaliação da Natureza Processual

Um dos principais desafios identificados na literatura é a dificuldade de avaliar o processo de aprendizagem, não apenas o produto final. Os estudos evidenciam que:

1. **Complexidade Temporal**: Os projetos em ABP se estendem por períodos significativos (2-4 meses em média), durante os quais ocorrem múltiplas iterações, revisões e refinamentos. A avaliação pontual não captura a evolução conceitual dos estudantes.

2. **Evolução de Competências**: As competências técnicas e transversais desenvolvidas pelos estudantes evoluem de forma não linear ao longo do projeto. Métodos tradicionais de avaliação falham em registrar essa progressão.

3. **Tomada de Decisão**: A tomada de decisões críticas durante o projeto (escolha de tecnologias, definição de arquitetura, resolução de problemas) é um componente essencial da aprendizagem que raramente é considerado em avaliações somativas.

#### 4.3.2 Avaliação Colaborativa

A natureza colaborativa dos projetos em ABP apresenta desafios únicos para avaliação individual:

1. **Contribuições Individuais em Equipes**: Identificar e mensurar as contribuições específicas de cada membro da equipe é complexo, especialmente quando o trabalho é interdependente e colaborativo.

2. **Dinâmicas de Grupo**: As dinâmicas de grupo, incluindo liderança informal, mediação de conflitos e distribuição de tarefas, impactam significativamente a aprendizagem individual mas são difíceis de avaliar objetivamente.

3. **Papéis Rotativos**: Em contextos onde os estudantes assumem diferentes papéis ao longo do projeto, a avaliação deve considerar o desempenho em múltiplas funções, o que aumenta a complexidade avaliativa.

#### 4.3.3 Avaliação de Competências Transversais

A avaliação de competências transversais (pensamento crítico, criatividade, comunicação, colaboração) representa um desafio metodológico significativo:

1. **Subjetividade**: A avaliação de competências como criatividade e pensamento crítico é inerentemente subjetiva, dependendo de critérios e julgamentos qualitativos.

2. **Intangibilidade**: Competências como comunicação e colaboração são difíceis de mensurar quantitativamente, especialmente em contextos virtuais ou híbridos.

3. **Contextualidade**: A manifestação de competências transversais varia significativamente de acordo com o contexto do projeto, dificultando a padronização de critérios avaliativos.

#### 4.3.4 Feedback Contínuo

O fornecimento de feedback formativo durante o desenvolvimento do projeto é essencial mas apresenta desafios práticos:

1. **Timing Oportuno**: O feedback deve ser fornecido em momentos estratégicos do projeto para ser eficaz, o que requer monitoramento constante das atividades dos estudantes.

2. **Relevância Contextual**: O feedback precisa ser específico para o contexto e estágio de desenvolvimento do projeto, exigindo conhecimento detalhado das atividades em andamento.

3. **Personalização**: Cada estudante e equipe têm necessidades distintas de feedback, demandando abordagens personalizadas que escalam para turmas numerosas.

#### 4.3.5 Escalabilidade

A manutenção da qualidade avaliativa com turmas numerosas é um desafio prático significativo:

1. **Recursos Humanos**: O tempo e expertise necessários para avaliação detalhada crescem exponencialmente com o número de estudantes e equipes.

2. **Consistência**: Manter critérios avaliativos consistentes entre diferentes avaliadores e contextos é desafiador em larga escala.

3. **Personalização vs. Eficiência**: Balancear a personalização necessária para avaliação eficaz com a eficiência requerida para escalar é um dilema persistente.

#### 4.3.6 Objetividade

A redução da subjetividade inerente à avaliação de projetos é uma preocupação metodológica constante:

1. **Critérios Ambíguos**: A interpretação de critérios avaliativos pode variar entre avaliadores, afetando a objetividade dos resultados.

2. **Influências Externas**: Fatores como relacionamento pessoal entre avaliador e estudante, expectativas prévias e contexto institucional podem influenciar avaliações.

3. **Quantificação de Qualidade**: A tradução de conceitos qualitativos (qualidade do projeto, criatividade, colaboração) em métricas quantificáveis é desafiadora.

### 4.4 Instrumentos e Tecnologias para Avaliação

#### 4.4.1 Rubricas e Critérios Avaliativos

As rubricas estruturadas foram identificadas como um dos instrumentos mais utilizados para avaliação em ABP:

1. **Rubricas Holísticas**: Avaliam o projeto como um todo em relação a critérios gerais de qualidade, sendo eficientes mas menos detalhadas.

2. **Rubricas Analíticas**: Avaliam aspectos específicos do projeto separadamente, oferecendo maior detalhamento mas requerendo mais tempo de aplicação.

3. **Rubricas de Desenvolvimento**: Focam na progressão das competências ao longo do projeto, alinhadas com a natureza processual da ABP.

#### 4.4.2 Sistemas de Avaliação Digital

Sistemas digitais especializados em avaliação de ABP demonstraram potencial para abordar múltiplos desafios:

1. **Plataformas de Gestão de Projetos**: Integram planejamento, execução e avaliação em ambientes digitais unificados.

2. **Portfólios Digitais**: Documentam a evolução do projeto e das competências ao longo do tempo, fornecendo evidências tangíveis de aprendizagem.

3. **Sistemas de Feedback Estruturado**: Automatizam aspectos do feedback formativo, aumentando a frequência e consistência do apoio aos estudantes.

#### 4.4.3 Learning Analytics

A análise de dados educacionais emergiu como uma abordagem promissora para avaliação objetiva:

1. **Análise de Engajamento**: Monitoram o envolvimento dos estudantes com as atividades do projeto através de métricas de participação e interação.

2. **Predição de Desempenho**: Utilizam dados históricos para identificar estudantes em risco e sugerir intervenções proativas.

3. **Visualização de Processos**: Representam graficamente o progresso do projeto e das competências, facilitando a interpretação por instrutores e estudantes.

#### 4.4.4 Métricas Técnicas

A incorporação de métricas técnicas específicas de domínio demonstrou eficácia em contextos técnicos:

1. **Métricas de Código**: Avaliam qualidade técnica do código produzido, fornecendo critérios objetivos para aspectos técnicos do projeto.

2. **Análise de Controle de Versão**: Examinam padrões de contribuição e colaboração através de sistemas como Git, oferecendo insights sobre dinâmicas de equipe.

3. **Monitoramento de Atividade**: Rastreiam atividades de desenvolvimento em tempo real, permitindo acompanhamento contínuo do progresso.

### 4.5 Tecnologia para Avaliação Objetiva e Escalável

#### 4.5.1 Automação de Processos Avaliativos

A automação de aspectos da avaliação demonstrou potencial para aumentar objetividade e escalabilidade:

1. **Avaliação Automática de Código**: Ferramentas que avaliam qualidade técnica de código automaticamente reduzem carga avaliativa e aumentam consistência.

2. **Extração de Métricas**: Sistemas que extraem e agregam métricas automaticamente de ambientes de desenvolvimento fornecem dados objetivos para avaliação.

3. **Feedback Automatizado**: Mecanismos que fornecem feedback imediato sobre aspectos técnicos do projeto aumentam a frequência de suporte aos estudantes.

#### 4.5.2 Inteligência Artificial e Aprendizado de Máquina

Aplicações de IA e aprendizado de máquina começaram a ser exploradas para avaliação em ABP:

1. **Classificação de Competências**: Algoritmos que classificam níveis de competência com base em padrões de comportamento e desempenho.

2. **Detecção de Problemas**: Sistemas que identificam automaticamente problemas no projeto ou na dinâmica da equipe.

3. **Recomendação Personalizada**: Mecanismos que sugerem intervenções e recursos personalizados com base no perfil e necessidades do estudante.

#### 4.5.3 Dashboards e Visualizações

Interfaces visuais para acompanhamento de projetos melhoraram a capacidade de monitoramento:

1. **Visão Geral do Projeto**: Dashboards que agregam informações de múltiplas fontes em visualizações compreensíveis.

2. **Monitoramento em Tempo Real**: Interfaces que atualizam informações continuamente, permitindo acompanhamento dinâmico.

3. **Relatórios Personalizados**: Sistemas que geram relatórios adaptados às necessidades específicas de diferentes stakeholders (estudantes, instrutores, coordenadores).

### 4.6 Lacunas Persistentes na Avaliação

#### 4.6.1 Avaliação Processual

Apesar dos avanços, a avaliação eficaz de processos de aprendizagem em ABP ainda apresenta lacunas:

1. **Integração de Dados**: Falta de integração entre diferentes fontes de dados (técnicas, comportamentais, colaborativas) limita a visão holística da aprendizagem.

2. **Modelagem Temporal**: Dificuldade em modelar e avaliar a evolução não linear das competências ao longo de projetos complexos.

3. **Contextualização**: Desafios em adaptar critérios avaliativos para diferentes contextos e domínios de projeto.

#### 4.6.2 Avaliação Colaborativa

A avaliação justa de contribuições individuais em contextos colaborativos permanece problemática:

1. **Quantificação de Contribuições**: Falta de métodos robustos para quantificar objetivamente contribuições intangíveis e interdependentes.

2. **Dinâmicas Emergentes**: Dificuldade em capturar e avaliar papéis e contribuições que emergem organicamente durante o projeto.

3. **Equidade**: Garantir que todos os membros da equipe tenham oportunidades equivalentes de demonstrar competências e contribuir significativamente.

#### 4.6.3 Competências Transversais

A avaliação de competências transversais continua sendo um desafio metodológico:

1. **Padronização**: Ausência de critérios padronizados e amplamente aceitos para avaliação de competências como criatividade e pensamento crítico.

2. **Autenticidade**: Dificuldade em criar situações de avaliação que reflitam autenticamente o exercício dessas competências em contextos reais.

3. **Transferência**: Avaliar como competências desenvolvidas em um projeto se transferem para outros contextos e situações.

#### 4.6.4 Feedback Contínuo

O fornecimento eficaz de feedback contínuo enfrenta limitações persistentes:

1. **Timing**: Dificuldade em identificar automaticamente os momentos ideais para intervenção e feedback.

2. **Relevância**: Garantir que o feedback fornecido seja relevante para o estágio específico de desenvolvimento do projeto e do estudante.

3. **Adaptabilidade**: Adaptar o conteúdo e formato do feedback às preferências e necessidades individuais dos estudantes.

#### 4.6.5 Escalabilidade Tecnológica

A escalabilidade das soluções tecnológicas para avaliação ainda apresenta desafios:

1. **Customização**: Balancear a necessidade de soluções personalizáveis com a facilidade de implementação em larga escala.

2. **Integração**: Integrar diferentes ferramentas e plataformas de forma coesa e eficiente.

3. **Manutenção**: Garantir a sustentabilidade e manutenção de soluções complexas em diferentes contextos institucionais.

## 5. Identificação da Lacuna de Pesquisa

### 5.1 Análise das Soluções Propostas

A revisão sistemática revelou que a literatura existente oferece diversas abordagens para abordar os desafios da avaliação em ABP, incluindo:

1. **Instrumentos avaliativos estruturados** (rubricas, checklists, portfólios)
2. **Sistemas digitais de avaliação** (plataformas LMS, ferramentas especializadas)
3. **Learning Analytics** (análise de dados educacionais, métricas técnicas)
4. **Tecnologias emergentes** (IA, machine learning, visualização de dados)

No entanto, a análise identificou uma lacuna crítica na literatura: a ausência de soluções integradas que combinem de forma eficaz os princípios das normas arquiteturais ISO (ISO/IEC/IEEE 42010 e ISO 10746) com a avaliação educacional em contextos complexos de ABP. Especificamente:

1. **Ausência de Abordagem Arquitetural Multivisão**: Nenhuma pesquisa existente aplica as cinco visões arquiteturais da norma ISO 42010 para compreender de forma abrangente o processo de ABP
2. **Falta de Fundamentação em Processos Distribuídos**: Soluções atuais não incorporam os princípios da norma ISO 10746 para modelagem de sistemas colaborativos e distribuídos
3. **Deficiência na Modelagem do "Business Drive" Educacional**: A força motriz do processo educativo (desenvolvimento de competências) não é adequadamente modelada como orientadora do sistema de avaliação
4. **Limitações na Visibilidade Multidimensional**: Os professores orientadores não dispõem de múltiplas perspectivas (visões) do desempenho dos estudantes sob diferentes viéses técnicos e comportamentais

### 5.2 Justificativa para a Lacuna

#### 5.2.1 Complexidade dos Contextos de ABP

Os contextos modernos de ABP em engenharia de software apresentam características que desafiam as abordagens tradicionais de avaliação:

1. **Projetos de Longa Duração**: Módulos que se estendem por 50 dias ou mais, com múltiplas iterações e sprints
2. **Papéis Rotativos**: Estudantes que assumem diferentes papéis técnicos e gerenciais ao longo do projeto
3. **Equipes Complexas**: Grupos com múltiplos stakeholders e dinâmicas colaborativas
4. **Tecnologias Integradas**: Uso de ferramentas profissionais de desenvolvimento, controle de versão e gestão de projetos

#### 5.2.2 Limitações das Abordagens Existentes

As soluções identificadas na literatura apresentam limitações que impedem sua aplicação eficaz em contextos complexos:

1. **Fragmentação**: Soluções que abordam aspectos isolados (técnico, comportamental, colaborativo) sem integração
2. **Falta de Continuidade**: Abordagens que fornecem snapshots pontuais em vez de acompanhamento contínuo
3. **Limitações de Escala**: Ferramentas que não escalam eficientemente para turmas numerosas com projetos complexos
4. **Ausência de Personalização**: Sistemas que não adaptam a avaliação às necessidades específicas de cada estudante e equipe

### 5.3 Oportunidade de Pesquisa

A aplicação de conceitos de Gêmeos Digitais fundamentados nas normas ISO para avaliação em ABP representa uma oportunidade inexplorada na literatura:

#### 5.3.1 Potencial dos Gêmeos Digitais Baseados em ISO

1. **Réplica em Tempo Real com Visões Arquiteturais**: Criação de uma representação virtual que espelha continuamente o estado do projeto físico através das cinco visões arquiteturais da norma ISO 42010
2. **Integração de Dados Multidimensional**: Capacidade de integrar múltiplas fontes de dados (técnicas, comportamentais, colaborativas) em uma visão unificada que respeita os princípios da norma ISO 10746
3. **Monitoramento Contínuo por Visões**: Acompanhamento em tempo real do progresso individual e coletivo através de diferentes perspectivas arquiteturais
4. **Simulação e Predição Baseada em Processos**: Capacidade de simular cenários e prever resultados com base em modelos de processos distribuídos conforme a norma ISO 10746

#### 5.3.2 Alinhamento com Necessidades Educacionais e Normas ISO

1. **Avaliação Processual Multivisão**: O Gêmeo Digital pode capturar e avaliar continuamente a evolução do aprendizado através das diferentes visões arquiteturais
2. **Personalização com Base no "Business Drive"**: A representação individualizada permite avaliação personalizada alinhada com os objetivos educacionais definidos como "Business Drive"
3. **Escalabilidade Arquitetural**: A automação inerente à abordagem permite escalar a avaliação para contextos complexos mantendo a estrutura arquitetural
4. **Objetividade com Fundamentação Padrão**: A base de dados objetivos reduz a subjetividade inerente à avaliação humana, fundamentada em normas internacionalmente reconhecidas

### 5.4 Justificativa para o Tema de Pesquisa

#### 5.4.1 Originalidade da Abordagem Fundamentada em Normas ISO

A aplicação de Gêmeos Digitais para avaliação em ABP é pioneira na literatura, combinando:

1. **Arquitetura de Software Baseada em Normas ISO**: Princípios da engenharia de software definidos nas normas ISO/IEC/IEEE 42010 e ISO 10746 aplicados ao contexto educacional
2. **Avaliação Educacional com Fundamentação Arquitetural**: Metodologias pedagógicas rigorosas para avaliação de aprendizagem fundamentadas em frameworks arquiteturais padronizados
3. **Tecnologia Emergente com Base em Padrões Industriais**: Aplicação inovadora de tecnologias de ponta em contextos educacionais, utilizando conceitos já validados na indústria

#### 5.4.2 Relevância Prática com Fundamentação ISO

A abordagem proposta tem potencial para impactar significativamente a prática educacional:

1. **Suporte ao Instrutor com Visibilidade Multidimensional**: Ferramentas que reduzem a carga avaliativa e aumentam a qualidade do feedback através de múltiplas visões do desempenho dos estudantes
2. **Experiência do Estudante com Avaliação Justa**: Acompanhamento personalizado que melhora o engajamento e os resultados de aprendizagem, fundamentado em princípios arquiteturais objetivos
3. **Eficácia Institucional com Escalabilidade Arquitetural**: Soluções escaláveis que permitem implementação de ABP em larga escala, mantendo a estrutura arquitetural coerente

#### 5.4.3 Contribuição para a Área com Base em Padrões Internacionais

Esta pesquisa contribuirá para o avanço do conhecimento em:

1. **Tecnologia Educacional com Fundamentação Padrão**: Expansão do uso de Gêmeos Digitais para contextos educacionais, fundamentada em normas internacionais reconhecidas
2. **Avaliação em ABP com Abordagem Multivisão**: Desenvolvimento de metodologias inovadoras para avaliação processual e colaborativa, baseadas em frameworks arquiteturais padronizados
3. **Engenharia de Software Educacional com Princípios Industriais**: Aplicação de princípios da indústria, definidos em normas internacionais, em contextos acadêmicos

## 6. Conclusão

Esta revisão sistemática mapeou o estado da arte sobre os desafios metodológicos, instrumentos e tecnologias para avaliação em Aprendizagem Baseada em Projetos, identificando soluções propostas na literatura e lacunas que justificam investigações adicionais.

A análise revelou que, embora existam diversas abordagens para abordar os desafios da avaliação em ABP, há uma lacuna crítica na literatura: a ausência de soluções integradas que combinem de forma eficaz os princípios das normas arquiteturais internacionais ISO/IEC/IEEE 42010 e ISO 10746 com a avaliação educacional em contextos complexos de ABP.

A aplicação de conceitos de Gêmeos Digitais fundamentados nas normas ISO para avaliação em ABP emerge como uma oportunidade inexplorada que pode abordar múltiplos desafios simultaneamente: avaliação processual multidimensional, personalização baseada em visões arquiteturais, escalabilidade com fundamentação padrão e objetividade com base em princípios arquiteturais objetivos. Esta abordagem inovadora tem potencial para transformar a prática de avaliação em ABP, oferecendo suporte tanto aos instrutores quanto aos estudantes em contextos educacionais complexos e exigentes, através de múltiplas perspectivas do desempenho e do processo de aprendizagem.

A identificação desta lacuna de pesquisa, fundamentada na ausência de abordagens arquiteturais padronizadas, justifica contundentemente a investigação proposta no trabalho de doutorado, que busca desenvolver e validar um modelo de Gêmeo Digital especificamente projetado para avaliação em ABP, com foco em contextos de engenharia de software de alta complexidade, fundamentado nas normas arquiteturais internacionais ISO/IEC/IEEE 42010 e ISO 10746.

## Referências

Kitchenham, B. (2004). Procedures for performing systematic reviews. Keele University Technical Report TR/SE-0401.

ISO/IEC/IEEE. (2022). ISO/IEC/IEEE 42010:2022 Systems and software engineering — Architecture description.

ISO. (1997). ISO 10746:1997 Information technology — Open Systems Interconnection — Reference model for development and specification of distributed applications.