# Projeto: Reescrita do ERP de uma Rede de Farmácias (Delphi para Java)

Este repositório reúne a documentação de gestão de riscos e comunicação de um projeto real de consultoria que participei. 

Esse projeto aconteceu antes da IA Generativa existir como ferramenta de trabalho. A análise de riscos deste repositório é retrospectiva: usei IA hoje para revisar o relato do projeto e organizar como a identificação, análise e resposta a riscos poderiam ter sido feitas se a ferramenta estivesse disponível na época.

## 1. Visão Geral do Projeto

O projeto consistia na reescrita completa do ERP legado (Delphi) de uma grande rede de farmácias para uma nova tecnologia em Java para permitir a expansão do cliente, contratada por uma consultoria. O escopo fechado era só a migração de tecnologia: reescrever o sistema existente em outra linguagem, sem previsão contratual de corrigir as regras de negócio problemáticas do sistema antigo.

### 1.1 Linha do tempo e decisões críticas

- Levantamento macro (15 dias): feito só pelo gerente executivo da consultoria e pelo gerente de TI do cliente, em nível de visão geral, sem detalhamento técnico.
- Fechamento de escopo e proposta comercial: feito sem nenhuma consulta técnica prévia. Nenhum arquiteto ou desenvolvedor foi ouvido antes da assinatura do contrato.
- Definição da equipe: equipe enxuta, responsável por todas as fases seguintes (levantamento detalhado, análise, desenvolvimento).
- Execução: as estimativas macro se mostraram muito abaixo do necessário. O módulo de emissão de notas fiscais, estimado em 40 horas, consumiu mais de 1.000 horas reais.

## 2. Estrutura da Equipe

- 1 Gerente Executivo (consultoria): negociação comercial e levantamento macro inicial.
- 1 Gerente de TI (cliente): contraparte no levantamento macro.
- Equipe enxuta de desenvolvimento e análise: responsável por todo o levantamento detalhado, análise e desenvolvimento do ERP, sem reforço proporcional ao tamanho real do projeto.

## 3. Estado Atual e Desafios Críticos

1. Estimativa de esforço subdimensionada: o levantamento macro não capturou a complexidade real de módulos críticos, como a emissão fiscal, gerando estouro de horas muito acima do estimado.
2. Falta de validação técnica antes do fechamento do contrato: o escopo foi vendido e assinado sem nenhuma revisão técnica, o que impediu identificar riscos de esforço e complexidade com antecedência.
3. Desalinhamento de expectativas dos stakeholders: o cliente esperava a correção dos problemas do sistema antigo. O que foi contratado foi só uma reescrita de tecnologia, do jeito que estava, só que em Java.

## 4. Estrutura do Repositório

```
projeto-erp-farmacias/
├── README.md
├── riscos/
│   ├── identificacao.md
│   ├── analise.md
│   └── respostas.md
└── comunicacao/
    └── status-stakeholders.md
```

## 5. Sobre o uso de IA Generativa nesta atividade

Como o projeto real não teve IA Generativa disponível na época, o valor desta atividade está em mostrar como a IA teria ajudado a prevenir e tratar esses riscos se estivesse disponível durante a execução do projeto, e não só em documentar o que já aconteceu. Essa reflexão está detalhada no arquivo riscos/respostas.md.
