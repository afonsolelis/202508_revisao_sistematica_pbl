# Registro de alterações — Revisão Sistemática ABP/PBL

Data: 2025-09-21

Arquivo afetado: `revisao_sistematica_tese.md`

## Principais mudanças

- Inclusão de 3.2.1.5 “Expansão de Estratégias de Busca com CEP e Tempo Real”
  - Novas strings com: complex event processing (CEP), stream processing, observability, real-time, telemetry; variações para PBL/capstone/studio-based e termos em português.
- Inclusão de 3.2.1.6 “Bases e Fontes Adicionais”
  - Acrescentadas Scopus, ERIC, IEEE Xplore, ACM DL e SciELO como bases complementares (sensibilidade/recall).
- Revisão de 5.2 “Oportunidade de Pesquisa” (Gêmeo Digital + CEP)
  - Padronização para “Gêmeo Digital (Digital Twin, DT)”.
  - Arquitetura CEP detalhada (janelas sliding/tumbling, latência alvo ≤ 5 min).
  - Definição dos Canais: Canal 4 como linha de sustentação; Canal 1 como indicadores essenciais; ligação com Cenários 3, 5 (tempo real) e 6 (pontos críticos).
  - Governança de dados: schema-on-read, dicionário de eventos, metadados; princípio “o dado está dentro do sistema”.
  - Regras de automação no DT para alertas e replanejamento (exemplos de SLA).
- Expansão de 5.2.2 “Pontos de Ataque e ‘Requisitos Modelados’”
  - Seis pontos críticos operacionalizados por padrões CEP: contribuição, aderência a rubricas/pesos, cadência, qualidade técnica, feedback, coordenação.
  - Métrica “requisitos modelados”: contagem, completude, maturidade, evolução; Plano B quando dados técnicos forem escassos.
  - Estratégia de agregação (indivíduo → equipe → turma → coorte) e exposição de deltas (planejado vs. realizado; peso nominal vs. efetivo).
  - Distinção entre Learning Design e Lógica de Dados.
- Inclusões na Discussão
  - 5.4 “Mapeamento Histórico (1990–2025)”.
  - 5.5 “Conexão com as DCNs”.
  - 5.6 “Ameaças à Validade” (interna, externa, construto/conclusão; dados semiestruturados; riscos éticos/operacionais).

## Remoções e ajustes de terminologia

- Removidas menções a “F8 medir” e placeholders associados.
- Substituição de “GD” por “DT (Digital Twin)”.
- Correção tipográfica (“и” → “e”).
- Substituição do caractere “↔” por “<->” na seção 5.5 para evitar avisos de fonte no PDF.

## Compilação

- Criada pasta `build/` e arquivo `build/header.tex` (pacotes: longtable, booktabs, array, ragged2e, graphicx, caption).
- Compilado com `pandoc` + `xelatex` para `build/revisao_sistematica_tese.pdf`.
- Avisos de fonte resolvidos após substituição de “↔”.

## Próximos passos (quando Scopus estiver disponível)

- Executar as novas strings nas bases adicionais e exportar RIS.
- Atualizar contagens por camada, fluxograma e tabelas conforme Kitchenham.
- (Opcional) Adicionar quadro “DCN <-> Evidências (DT/CEP)” e figura do pipeline (CEP + Canais + Pontos críticos).

