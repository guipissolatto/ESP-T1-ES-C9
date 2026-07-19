# Identificação de Riscos

Lista dos riscos identificados no projeto de reescrita do ERP (Delphi para Java) de uma rede de farmácias, com base no relato real do projeto: levantamento de requisitos macro, equipe enxuta, estouro de estimativa e desalinhamento de expectativas dos stakeholders.

## 1. Lista de Riscos Identificados

### Risco 01
**Risco:** Estimativa de esforço subdimensionada por causa de um levantamento de requisitos raso.
**Descrição:** O levantamento foi feito em 15 dias, em nível macro, só pelo gerente executivo da consultoria e pelo gerente de TI do cliente, sem detalhamento técnico. Isso gerou estimativas muito abaixo do esforço real.
**Contexto de ocorrência:** Durante o desenvolvimento de cada módulo, ao encontrar regras de negócio, exceções fiscais e integrações que não foram mapeadas na fase macro. Exemplo: o módulo de emissão de notas fiscais foi estimado em 40h e levou mais de 1.000h.
**Nota de validação:** não se sabe se a consultoria tinha dados históricos de esforço de projetos parecidos (reescrita de ERPs fiscais) que poderiam ter sido usados como referência na estimativa macro.

### Risco 02
**Risco:** Falta de validação técnica do escopo antes de fechar o contrato.
**Descrição:** A proposta comercial e o escopo foram fechados sem nenhuma consulta prévia a arquitetos ou desenvolvedores seniores, o que impediu identificar riscos técnicos e de esforço com antecedência.
**Contexto de ocorrência:** No momento de montar e assinar o contrato com o cliente, antes de começar o projeto.
**Nota de validação:** não se sabe se a consultoria tinha algum processo formal de revisão técnica comercial, ou se essa foi uma exceção só deste projeto.

### Risco 03
**Risco:** Equipe pequena demais para o levantamento detalhado, a análise e o desenvolvimento.
**Descrição:** Foi definida uma equipe enxuta para tocar sozinha desde o levantamento detalhado até o desenvolvimento completo de um ERP inteiro, sem dimensionamento proporcional ao volume real de trabalho.
**Contexto de ocorrência:** Ao longo de todas as fases depois do levantamento macro, à medida que o volume real de esforço se mostrava muito maior que o estimado.

### Risco 04
**Risco:** Desalinhamento entre a expectativa dos stakeholders e o escopo real do contrato.
**Descrição:** Os stakeholders da rede de farmácias esperavam que os problemas do sistema antigo (Delphi) fossem corrigidos. O que foi vendido e contratado foi só uma reescrita de tecnologia do ERP para Java, sem corrigir as regras de negócio problemáticas.
**Contexto de ocorrência:** Ao longo da execução e, principalmente, nas entregas e homologações, quando o cliente percebe que os problemas antigos continuam no novo sistema.
**Nota de validação:** não se sabe se essa expectativa foi só combinada verbalmente em reuniões comerciais, sem registro formal no escopo. Isso dificulta rastrear a origem exata do desalinhamento.

### Risco 05
**Risco:** Perda de credibilidade da consultoria e desgaste comercial com o cliente.
**Descrição:** A soma de estouro de horas, atraso de cronograma e insatisfação por expectativas não atendidas pode prejudicar a relação comercial de longo prazo entre a consultoria e a rede de farmácias.
**Contexto de ocorrência:** Nas entregas parciais e, principalmente, na homologação final, quando os efeitos dos outros riscos ficam visíveis para o cliente.
