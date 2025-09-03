# Uma Revisão Sistemática sobre os Desafios e Tecnologias para Avaliação em Aprendizagem Baseada em Projetos

## 1. Introdução

### 1.1 Justificativa

A Aprendizagem Baseada em Projetos (ABP) representa uma mudança paradigmática no ensino superior, especialmente em áreas tecnológicas, onde a formação de profissionais capazes de enfrentar os desafios complexos do mercado contemporâneo se torna imperativa. No contexto brasileiro, a experiência do Instituto de Tecnologia e Liderança (Inteli) evidencia tanto o potencial transformador da ABP quanto os desafios significativos enfrentados por professores orientadores na implementação eficaz dessa metodologia.

Conforme documentado por Valente et al. (2025), "a qualidade dos concluintes dos cursos de computação tradicionais não está atendendo às necessidades do mercado e do país", evidenciando a necessidade crítica de abordagens pedagógicas mais eficazes. A estrutura curricular do Inteli, organizada em Learning BackLogs (LBLs), ilustra a complexidade inerente à ABP contemporânea, onde os módulos integram conhecimentos técnicos de computação, matemática e física com competências transversais de liderança, negócios e design de experiência do usuário (INTELI PPC, 2024).

A implementação prática da ABP no contexto do Inteli revela desafios metodológicos específicos que requerem "um planejamento integrado de todas as vertentes e uma revisão constante para assegurar que todos os conteúdos essenciais sejam cobertos de maneira adequada". Esta complexidade operacional gera questões fundamentais sobre como realizar a evolução sistemática dos módulos de aprendizagem e quais aspectos da aprendizagem devem ser utilizados como base para compor os requisitos de revisão.

A experiência prática de implementação da ABP em engenharia de software revela questões fundamentais que emergem da complexidade metodológica. Conforme documentado por Arakaki et al. (2025): "Como realizar a evolução sistemática dos módulos de aprendizagem baseados em projetos (LBLs)? Quais aspectos da aprendizagem devem ser utilizados como base para compor os requisitos de revisão? Como os pacotes de conceitos e práticas podem ser reconfigurados sem prejuízo das disciplinas essenciais?" 

A complexidade dessa implementação é amplificada pelos desafios inerentes à engenharia de software moderna. Pressman & Maxim (2021) destacam que os sistemas de informação enfrentaram uma "esfera crescente de desafios" à medida que os problemas se tornaram mais complexos, demandando programas cada vez mais sofisticados. Esta realidade técnica, combinada com a necessidade de formar profissionais capazes de "lidar com a complexidade e a rápida evolução do mercado de trabalho" (Arakaki et al., 2025), cria um contexto educacional onde professores orientadores enfrentam dificuldades operacionais específicas:

**Avaliação de Contribuições Individuais em Equipes Colaborativas**: A natureza colaborativa dos projetos em ABP torna complexa a identificação e mensuração das contribuições específicas de cada membro da equipe, especialmente quando o trabalho é interdependente e os papéis são rotativos ao longo dos módulos.

**Mensuração de Competências Transversais ao Longo do Processo**: A necessidade de avaliar tanto hard skills quanto soft skills de forma integrada apresenta desafios significativos, pois essas competências se manifestam de forma processual e contextual, requerendo instrumentos específicos que capturam sua evolução temporal.

**Fornecimento de Feedback Contínuo em Projetos Estendidos**: O fornecimento de feedback formativo durante cronogramas prolongados demanda monitoramento constante e personalizado, representando um desafio de escalabilidade quando aplicado a contextos complexos com múltiplas equipes.

**Monitoramento Multidimensional Integrado**: A necessidade simultânea de monitorar qualidade técnica do código, dinâmica das equipes, progresso individual e desenvolvimento de competências transversais revela a inadequação de ferramentas isoladas que abordam apenas aspectos específicos da experiência em ABP.

**Tomada de Decisões Informadas sobre Intervenções Pedagógicas**: A falta de visibilidade integrada sobre o processo educativo limita a capacidade dos professores orientadores de tomar decisões baseadas em informações em tempo real, comprometendo a eficácia das intervenções pedagógicas necessárias.

Soluções tecnológicas existentes operam de forma isolada, focando em aspectos específicos da experiência em ABP em vez de proporcionar uma visão holística do processo educativo que apoie efetivamente o trabalho do professor orientador. Esta fragmentação impede uma abordagem integrada que considere as múltiplas dimensões da aprendizagem em contextos de ABP.

A tecnologia de Gêmeos Digitais, que se originou em contextos industriais, oferece uma abordagem promissora para apoiar professores orientadores na avaliação abrangente em ABP. Embora amplamente aplicados na indústria, seus usos educacionais permanecem amplamente inexplorados, representando uma lacuna significativa na literatura.

Esta revisão sistemática visa mapear o estado da arte sobre os desafios metodológicos, instrumentos e tecnologias para auxiliar professores orientadores na avaliação em ambientes de Aprendizagem Baseada em Projetos, identificando como superar as dificuldades enfrentadas na avaliação de aprendizagem em contextos colaborativos e processuais.

### 1.2 Fundamentação Teórica nas Normas ISO

Esta pesquisa baseia-se na norma ISO 10746 para fundamentar a arquitetura da solução proposta, utilizando o conceito de "Business Drive" como elemento orientador das cinco visões arquiteturais:

#### 1.2.1 ISO 10746 - Especificação de Sistemas Distribuídos como Fundamento Arquitetural

A norma ISO 10746 fornece um framework para especificação de sistemas distribuídos baseado em cinco visões arquiteturais fundamentais, onde o "Business Drive" (BD) atua como a força motriz que orienta o desenvolvimento e a evolução do sistema. No contexto educacional do ABP, o "Business Drive" é o desenvolvimento de competências técnicas e transversais pelos estudantes, com o professor orientador como principal stakeholder responsável por garantir a qualidade do processo educativo.

As cinco visões arquiteturais da norma ISO 10746 aplicadas ao contexto de ABP são:

1. **Visão de Business Drive (BD)**: Representa o propósito fundamental do sistema - o desenvolvimento de competências dos estudantes em contextos de ABP. Esta visão define os objetivos educacionais que orientam todo o sistema de avaliação.

2. **Visão de Information View (IV)**: Modela a estrutura e o fluxo de informações educacionais, incluindo dados sobre progresso dos estudantes, qualidade do código, dinâmica das equipes e desenvolvimento de competências.

3. **Visão de Computational View (CV)**: Descreve os processos computacionais e algoritmos necessários para coletar, processar e analisar os dados educacionais, incluindo métricas de código, análise de colaboração e monitoramento de progresso.

4. **Visão de Engineering View (EV)**: Define a arquitetura técnica do sistema, incluindo componentes de software, interfaces, protocolos de comunicação e integração com ferramentas educacionais existentes.

5. **Visão de Technology View (TV)**: Especifica as tecnologias e plataformas que suportam a implementação do sistema, incluindo infraestrutura, frameworks e padrões tecnológicos utilizados.

#### 1.2.2 Aplicação das Visões Arquiteturais na Estratégia de Busca

A estratégia de busca foi estruturada em cinco camadas correspondentes às cinco visões arquiteturais da norma ISO 10746, onde cada camada busca soluções específicas para apoiar o "Business Drive" educacional:

- **Camada 1 (Engineering View)**: Busca fundamentos arquiteturais e tecnológicos que suportem a estrutura do sistema de avaliação
- **Camada 2 (Computational View)**: Procura processos e algoritmos para análise de dados educacionais
- **Camada 3 (Information View)**: Identifica soluções para modelagem e fluxo de informações educacionais
- **Camada 4 (Technology View)**: Explora tecnologias específicas que podem ser aplicadas na solução
- **Camada 5 (Business Drive)**: Foca em soluções que apoiam diretamente os objetivos educacionais do professor orientador

Esta abordagem arquitetural permite uma análise abrangente da literatura existente, garantindo que aspectos críticos do problema não sejam omitidos e que soluções parciais possam ser integradas de forma coerente.

### 1.3 Justificativa da Necessidade Baseada no Papel do Professor Orientador

O professor orientador em contextos de ABP precisa:

1. **Monitorar o progresso** individual e coletivo dos estudantes em projetos com múltiplas iterações e papéis rotativos
2. **Avaliar desempenho** considerando diferentes viéses técnicos e comportamentais
3. **Tomar decisões informadas** sobre intervenções pedagógicas com base em informações em tempo real
4. **Escalar sua supervisão** para funcionar efetivamente com turmas numerosas

A aplicação das cinco visões arquiteturais da ISO 42010 ao contexto de ABP fornece ao professor orientador diferentes perspectivas do processo educativo:

- **Visão Estrutural**: Organização das equipes e distribuição de papéis
- **Visão Comportamental**: Dinâmicas de colaboração e interação entre estudantes
- **Visão de Implementação**: Progresso técnico e qualidade das entregas
- **Visão de Implantação**: Ambiente de trabalho e recursos utilizados
- **Visão de Dados**: Desempenho individual e coletivo quantitativo

### 1.4 Lacuna de Pesquisa Identificada

Apesar da existência de diversas abordagens para avaliação em ABP, identificamos uma lacuna crítica na literatura:

1. **Ausência de Abordagens Arquiteturais**: Nenhuma pesquisa existente aplica os princípios das normas ISO 42010 e 10746 ao contexto de avaliação em ABP
2. **Falta de Visões Integradas**: Soluções existentes abordam aspectos isolados sem integração arquitetural
3. **Limitações na Avaliação Multidimensional**: Dificuldade em capturar e avaliar o desempenho dos estudantes sob diferentes viéses técnicos
4. **Deficiência em Escalabilidade**: Ferramentas atuais não escalam efetivamente para contextos complexos com múltiplas equipes e papéis rotativos

A aplicação de conceitos de Gêmeos Digitais fundamentados nas normas ISO representa uma oportunidade inexplorada para abordar estas lacunas de forma contundente.

## 2. Objetivos da Revisão

### 2.1 Objetivo Geral

Mapear a produção científica sobre métodos, instrumentos e tecnologias para auxiliar professores orientadores na avaliação em Aprendizagem Baseada em Projetos (ABP), identificando como superar as dificuldades inerentes à avaliação de aprendizagem baseada em projetos.

### 2.2 Objetivos Específicos

1. Identificar os principais desafios metodológicos enfrentados por professores orientadores na avaliação de aprendizagem em contextos de ABP.
2. Mapear os instrumentos e tecnologias que estão sendo utilizados para apoiar professores orientadores na superação desses desafios.
3. Analisar como a tecnologia pode apoiar professores orientadores em processos avaliativos mais objetivos e escaláveis em ABP.
4. Identificar lacunas persistentes no suporte a professores orientadores na avaliação de competências processuais e colaborativas.

## 3. Metodologia

Esta revisão sistemática foi conduzida seguindo as diretrizes propostas por Kitchenham (2004) para realização de revisões sistemáticas em engenharia de software. O processo foi estruturado em três fases principais: planejamento, condução e relato da revisão.

### 3.1 Fase de Planejamento

#### 3.1.1 Questão de Pesquisa

A questão de pesquisa foi formulada seguindo o framework PICO (Population, Intervention, Comparison, Outcome) (Santos, Pimenta & Nobre, 2007), focando nas dificuldades do professor orientador na avaliação em ambientes de Aprendizagem Baseada em Projetos:

**Questão Principal**: Quais são os desafios metodológicos, instrumentos e tecnologias para auxiliar professores orientadores na avaliação em Aprendizagem Baseada em Projetos?

**P** (População): Professores orientadores em ambientes educacionais que utilizam Aprendizagem Baseada em Projetos
**I** (Intervenção): Métodos, instrumentos e tecnologias para apoio à avaliação em ABP
**C** (Comparação): Métodos tradicionais de avaliação sem suporte tecnológico
**O** (Resultados): Superar dificuldades dos professores orientadores na avaliação justa e abrangente de estudantes em contextos colaborativos e processuais

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

##### Estratégia de Busca Fundamentada nas Visões Arquiteturais da ISO 10746

As strings de busca foram estruturadas em 5 camadas estratificadas correspondentes às cinco visões arquiteturais da norma ISO 10746, onde cada camada busca soluções específicas para apoiar o "Business Drive" educacional (desenvolvimento de competências em ABP):

**String 1 - Visão Engineering View (EV) - Fundamentos de Arquitetura e Monitoramento**:
```
TS=("software architecture" OR "microservices architecture" OR "distributed systems" OR "system structure" OR "component interface") 
AND TS=("project-based learning" OR "project based learning" OR "PBL")
AND TS=("observability" OR "telemetry" OR "metrics collection" OR "monitoring")
```

**String 2 - Visão Computational View (CV) - Modelagem de Processos Educacionais**:
```
TS=("process modeling" OR "educational process" OR "learning process" OR "workflow modeling" OR "behavioral process" OR "collaboration process") 
AND TS=("project-based learning" OR "project based learning" OR "PBL")
AND TS=("team dynamics" OR "collaboration" OR "interaction")
```

**String 3 - Visão Information View (IV) - Gêmeos Digitais e Modelagem de Sistemas**:
```
TS=("digital twin*" OR "virtual twin*" OR "digital replica" OR "system modeling" OR "data modeling" OR "information flow") 
AND TS=("project-based learning" OR "project based learning" OR "PBL")
AND TS=("real-time data" OR "data synchronization" OR "virtual representation")
```

**String 4 - Visão Technology View (TV) - Learning Analytics e Métricas de Desenvolvimento**:
```
TS=("learning analytics" OR "educational data mining" OR "student analytics" OR "behavioral analytics" OR "git analytics" OR "version control metrics" OR "collaboration metrics" OR "team performance" OR "code metrics") 
AND TS=("project-based learning" OR "project based learning" OR "PBL")
AND TS=("implementation" OR "module" OR "component" OR "artifact")
```

**String 5 - Visão Business Drive (BD) - Sistemas de Apoio ao Orientador**:
```
TS=("teacher support" OR "instructor support" OR "supervisor dashboard" OR "educational dashboard" OR "teacher assistance" OR "instructor tools") 
AND TS=("project-based learning" OR "project based learning" OR "PBL")
AND TS=("business drive" OR "educational objectives" OR "competency development" OR "learning outcomes")
```

##### Alinhamento com o Business Drive Educacional

Todas as strings de busca incorporam o conceito de "Business Drive" da norma ISO 10746, onde o objetivo educacional fundamental (desenvolvimento de competências técnicas e transversais em contextos de ABP) orienta a busca por soluções tecnológicas. Esta abordagem garante que a pesquisa esteja alinhada com os objetivos fundamentais do processo educativo, com o professor orientador como principal stakeholder responsável por garantir a qualidade da avaliação.

##### Justificativa para as Strings de Busca Baseada nas Visões Arquiteturais da ISO 10746

A Tabela 1 apresenta a justificativa para cada string de busca com base na dimensão do problema de pesquisa, fundamentada nas cinco visões arquiteturais da norma ISO 10746:

| Camada | Visão Arquitetural (ISO 10746) | Dimensão do Problema | Justificativa | String de Busca |
|--------|------------------------------|---------------------|---------------|-----------------|
| 1 | Engineering View (EV) | Fundamentos Arquiteturais | Estabelece os conceitos fundamentais de arquitetura de sistemas aplicáveis ao contexto educacional, fornecendo base conceitual para monitoramento sistemático. Esta camada foca na estrutura organizacional das equipes e interfaces entre componentes do sistema educacional que apoia o professor orientador | Arquitetura de software e monitoramento |
| 2 | Computational View (CV) | Processamento Computacional | Conecta conceitos de modelagem de processos com algoritmos computacionais para análise de dados educacionais, essencial para capturar a complexidade temporal do ABP e as dinâmicas colaborativas entre estudantes | Modelagem de processos educacionais |
| 3 | Information View (IV) | Modelagem de Informações | Representa o núcleo inovador da pesquisa - aplicação de Gêmeos Digitais à educação, tecnologia com potencial transformador. Esta camada foca na modelagem e fluxo de informações educacionais que permitem a criação de réplicas virtuais do processo educativo | Gêmeos Digitais e modelagem de sistemas |
| 4 | Technology View (TV) | Tecnologias de Implementação | Integra análise de dados educacionais com tecnologias específicas de implementação, criando ponte entre soluções teóricas e ferramentas práticas aplicáveis ao contexto educacional | Learning Analytics e métricas |
| 5 | Business Drive (BD) | Objetivos Educacionais | Foca nos objetivos fundamentais do processo educativo - desenvolvimento de competências técnicas e transversais pelos estudantes, com o professor orientador como principal stakeholder. Esta camada considera como as soluções tecnológicas apoiam diretamente os objetivos educacionais | Sistemas de apoio ao orientador |

Tabela 1: Justificativa para as strings de busca estratificadas baseada nas visões arquiteturais da ISO 10746

A estratégia de busca estratificada fundamenta-se no princípio do "Business Drive" da norma ISO 10746, onde o objetivo principal (desenvolvimento de competências em contextos de ABP) orienta a busca por soluções tecnológicas que suportem este propósito através das diferentes visões arquiteturais. Cada camada representa uma perspectiva arquitetural diferente do problema, permitindo uma análise abrangente e multidimensional da literatura existente.

A fundamentação na norma ISO 10746 fornece uma base teórica sólida que:
1. **Justifica a Abordagem Multivisão**: As cinco visões arquiteturais oferecem perspectivas complementares do problema, garantindo que aspectos críticos não sejam omitidos
2. **Alinha com Práticas Industriais**: Utiliza conceitos já validados na indústria para contextos educacionais, facilitando a transferência de tecnologias
3. **Garante Completude Arquitetural**: A cobertura das cinco visões assegura uma solução arquitetural completa que atenda às necessidades do professor orientador
4. **Facilita a Integração**: O framework arquitetural permite a integração coerente de soluções parciais em uma arquitetura unificada

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

A literatura existente oferece diversas abordagens para os desafios da avaliação em ABP:

1. **Instrumentos avaliativos estruturados** (rubricas, checklists, portfólios)
2. **Sistemas digitais de avaliação** (plataformas LMS, ferramentas especializadas)
3. **Learning Analytics** (análise de dados educacionais, métricas técnicas)
4. **Tecnologias emergentes** (IA, machine learning, visualização de dados)

No entanto, identificou-se uma lacuna crítica: a ausência de soluções integradas que combinem os princípios das visões arquiteturais da norma ISO 10746 com a avaliação educacional em contextos complexos de ABP. Especificamente:

1. **Ausência de Abordagem Arquitetural Multivisão Baseada em ISO 10746**: Nenhuma pesquisa aplica as cinco visões arquiteturais da norma ISO 10746 para compreender o processo de ABP como um sistema distribuído orientado pelo "Business Drive" educacional
2. **Falta de Integração Arquitetural Coerente**: Soluções atuais abordam aspectos isolados sem uma arquitetura unificada que integre as diferentes visões (Engineering, Computational, Information, Technology e Business Drive)
3. **Deficiência na Modelagem do "Business Drive" Educacional**: O desenvolvimento de competências não é adequadamente modelado como elemento orientador de todas as visões arquiteturais
4. **Limitações na Visibilidade Multidimensional para Professores Orientadores**: Professores orientadores não dispõem de uma visão abrangente que integre as cinco perspectivas arquiteturais do processo de avaliação

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

A aplicação de conceitos de Gêmeos Digitais fundamentados nas visões arquiteturais da norma ISO 10746 para apoio a professores orientadores na avaliação em ABP representa uma oportunidade inexplorada na literatura:

#### 5.3.1 Potencial dos Gêmeos Digitais Baseados em Visões Arquiteturais ISO 10746

1. **Réplica em Tempo Real com Integração Multivisão**: Criação de uma representação virtual que espelha continuamente o estado do projeto físico através da integração coerente das cinco visões arquiteturais da norma ISO 10746
2. **Integração de Dados Multidimensional Baseada em Arquitetura**: Capacidade de integrar múltiplas fontes de dados (técnicas, comportamentais, colaborativas) em uma visão unificada que respeita os princípios arquiteturais da norma ISO 10746
3. **Monitoramento Contínuo por Visões Arquiteturais**: Acompanhamento em tempo real do progresso individual e coletivo através das diferentes perspectivas arquiteturais (EV, CV, IV, TV, BD)
4. **Simulação e Predição Baseada em Processos Distribuídos**: Capacidade de simular cenários e prever resultados com base em modelos de processos distribuídos conforme a norma ISO 10746

#### 5.3.2 Alinhamento com Necessidades dos Professores Orientadores e Visões Arquiteturais

1. **Avaliação Processual Multivisão**: O Gêmeo Digital pode capturar e avaliar continuamente a evolução do aprendizado através das diferentes visões arquiteturais, fornecendo ao professor orientador múltiplas perspectivas do desempenho
2. **Personalização com Base no "Business Drive" Educacional**: A representação individualizada permite avaliação personalizada alinhada com os objetivos educacionais definidos como "Business Drive", apoiando o trabalho do professor orientador
3. **Escalabilidade Arquitetural**: A automação inerente à abordagem permite escalar o apoio à avaliação para contextos complexos mantendo a estrutura arquitetural coerente
4. **Objetividade com Fundamentação Arquitetural**: A base de dados objetivos reduz a subjetividade inerente à avaliação humana, fundamentada em uma arquitetura padronizada internacionalmente

### 5.4 Justificativa para o Tema de Pesquisa

#### 5.4.1 Originalidade da Abordagem Fundamentada em Visões Arquiteturais ISO 10746

A aplicação de Gêmeos Digitais para apoio a professores orientadores na avaliação em ABP é pioneira na literatura, combinando:

1. **Arquitetura de Software Baseada em Visões ISO 10746**: Princípios da engenharia de software definidos na norma ISO 10746 aplicados ao contexto educacional como sistema distribuído orientado pelo "Business Drive"
2. **Avaliação Educacional com Fundamentação Arquitetural Multivisão**: Metodologias pedagógicas rigorosas para avaliação de aprendizagem fundamentadas em frameworks arquiteturais padronizados com cinco perspectivas integradas
3. **Tecnologia Emergente com Base em Padrões Industriais**: Aplicação inovadora de tecnologias de ponta em contextos educacionais, utilizando conceitos já validados na indústria através da arquitetura ISO 10746

#### 5.4.2 Relevância Prática com Fundamentação em Visões Arquiteturais

A abordagem proposta tem potencial para impactar significativamente a prática educacional:

1. **Suporte ao Professor Orientador com Visibilidade Multidimensional**: Ferramentas que reduzem a carga avaliativa e aumentam a qualidade do feedback através de múltiplas visões arquiteturais do desempenho dos estudantes
2. **Experiência do Estudante com Avaliação Justa e Integrada**: Acompanhamento personalizado que melhora o engajamento e os resultados de aprendizagem, fundamentado em uma arquitetura objetiva que integra todas as perspectivas
3. **Eficácia Institucional com Escalabilidade Arquitetural**: Soluções escaláveis que permitem implementação de ABP em larga escala, mantendo a estrutura arquitetural coerente baseada em normas internacionais

#### 5.4.3 Contribuição para a Área com Base em Padrões Arquiteturais Internacionais

Esta pesquisa contribuirá para o avanço do conhecimento em:

1. **Tecnologia Educacional com Fundamentação Arquitetural**: Expansão do uso de Gêmeos Digitais para contextos educacionais, fundamentada em normas arquiteturais internacionais reconhecidas (ISO 10746)
2. **Avaliação em ABP com Abordagem Multivisão Integrada**: Desenvolvimento de metodologias inovadoras para avaliação processual e colaborativa, baseadas em frameworks arquiteturais padronizados que integram múltiplas perspectivas
3. **Engenharia de Software Educacional com Princípios Arquiteturais Industriais**: Aplicação de princípios arquiteturais da indústria, definidos em normas internacionais, em contextos acadêmicos através da integração das cinco visões da norma ISO 10746

## 6. Conclusão

Esta revisão sistemática mapeou o estado da arte sobre os desafios metodológicos, instrumentos e tecnologias para auxiliar professores orientadores na avaliação em Aprendizagem Baseada em Projetos, identificando soluções propostas na literatura e lacunas que justificam investigações adicionais.

A análise revelou uma lacuna crítica na literatura: a ausência de soluções integradas que combinem os princípios das visões arquiteturais da norma ISO 10746 com o apoio a professores orientadores na avaliação educacional em contextos complexos de ABP.

A aplicação de conceitos de Gêmeos Digitais fundamentados nas visões arquiteturais da norma ISO 10746 para apoiar professores orientadores na avaliação em ABP emerge como uma oportunidade inexplorada que pode abordar múltiplos desafios simultaneamente: avaliação processual multidimensional através das cinco visões arquiteturais, personalização baseada em arquitetura integrada, escalabilidade com fundamentação arquitetural padrão e objetividade com base em princípios arquiteturais objetivos.

A identificação desta lacuna de pesquisa, fundamentada na ausência de abordagens arquiteturais padronizadas baseadas na norma ISO 10746, justifica contundentemente a investigação proposta no trabalho de doutorado, que busca desenvolver e validar um modelo de Gêmeo Digital especificamente projetado para apoiar professores orientadores na avaliação em ABP, com foco em contextos de engenharia de software de alta complexidade, fundamentado nas visões arquiteturais da norma ISO 10746.

## Referências

Arakaki, R. et al. (2025). Aprimoramento Sistemático do PBL na Engenharia de Software: Um Método Baseado em Objetivos de Aprendizagem e Visões Arquiteturais. In: CONGRESSO BRASILEIRO DE EDUCAÇÃO EM ENGENHARIA (COBENGE), 53., 2025, Campinas. Anais [...]. Campinas: PUC-Campinas, 2025.

INTELI PPC. (2024). Projeto Pedagógico do Curso de Bacharelado em Engenharia de Software. Instituto de Tecnologia e Liderança. Disponível em: https://www.inteli.edu.br/engenharia-de-software. Acesso em: set. 2025.

ISO. (1997). ISO 10746:1997 Information technology — Open Systems Interconnection — Reference model for development and specification of distributed applications.

ISO/IEC/IEEE. (2022). ISO/IEC/IEEE 42010:2022 Systems and software engineering — Architecture description.

Kitchenham, B. (2004). Procedures for performing systematic reviews. Keele University Technical Report TR/SE-0401.

Pressman, R.; Maxim, B. (2021). Engenharia de Software: Uma Abordagem Profissional. 8. ed. Porto Alegre: AMGH. Revisão técnica: Reginaldo Arakaki.

Santos, C. M. C., Pimenta, C. A. M., & Nobre, M. R. C. (2007). A estratégia PICO para a construção da pergunta de pesquisa e busca de evidências. Revista Latino-Americana de Enfermagem, 15(3), 502-507.

Valente, J. A.; Bittencourt, I. I.; Santoro, F. M.; Garcia, M.; Isotani, S.; Garcia, A.; Habimorad, M. (2025). O Ensino Superior de Computação Baseado em Projetos: o Inteli no caminho da inovação. Revista Brasileira de Informática na Educação, v. 33, p. 605-642.