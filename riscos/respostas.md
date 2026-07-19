# Estratégias de Resposta aos Riscos

Estratégias de resposta (evitar, mitigar, transferir e aceitar) para os riscos identificados no projeto de reescrita do ERP da rede de farmácias, e uma reflexão sobre como a IA Generativa poderia ter ajudado nessas respostas se estivesse disponível na época do projeto.

## 1. Estratégias Possíveis por Risco

### Risco 01: Estimativa de esforço subdimensionada
Evitar: não aceitar propostas comerciais baseadas só em levantamento macro. Exigir uma fase de descoberta técnica remunerada antes de qualquer estimativa formal.
Mitigar: criar uma reserva de contingência no orçamento e no cronograma para módulos mais complexos (como o fiscal), e reestimar cada módulo antes de começar o desenvolvimento.
Transferir: negociar o contrato em modelo de time e material (ou por módulo/marco) em vez de escopo fechado, passando parte do risco de estimativa para um modelo de precificação mais flexível.
Aceitar: assumir o estouro como custo de aprendizado da consultoria, absorvendo horas extras não faturáveis para manter a relação comercial.

### Risco 02: Falta de validação técnica antes de fechar o contrato
Evitar: criar uma política interna obrigatória: nenhuma proposta é assinada sem revisão técnica formal (mesmo que rápida) de um arquiteto ou desenvolvedor sênior.
Mitigar: criar um checklist técnico mínimo de validação de escopo, aplicável mesmo sob pressão comercial de tempo.
Transferir: envolver um parceiro técnico externo para validar tecnicamente propostas de projetos grandes antes do fechamento.
Aceitar: manter o processo comercial como está, assumindo o risco de estimativas erradas como parte do modelo de negócio da consultoria.

### Risco 03: Equipe pequena demais
Evitar: dimensionar a equipe com base numa estimativa técnica detalhada, não na estimativa macro inicial.
Mitigar: prever pontos de checagem nas primeiras semanas do projeto para reavaliar o tamanho da equipe assim que o esforço real começar a divergir do estimado.
Transferir: contratar squads complementares ou parceiros terceirizados para picos de demanda em módulos mais complexos.
Aceitar: manter a equipe enxuta e aceitar o atraso de cronograma como consequência.

### Risco 04: Desalinhamento de expectativas dos stakeholders
Evitar: formalizar por escrito, já na proposta comercial, o que está e o que não está no escopo, deixando claro que é uma reescrita de tecnologia, não uma correção de regras de negócio.
Mitigar: fazer uma reunião de kickoff técnico com os stakeholders para alinhar expectativas antes de começar o desenvolvimento, e revisitar esse alinhamento periodicamente.
Transferir: envolver o gerente de TI do cliente como corresponsável formal pela validação e comunicação do escopo com os demais stakeholders internos.
Aceitar: não agir preventivamente e lidar com a insatisfação só quando ela aparecer na entrega.

### Risco 05: Perda de credibilidade da consultoria
Evitar: ser transparente com o cliente assim que o desvio de estimativa for percebido, em vez de tentar esconder o problema.
Mitigar: manter uma comunicação de status frequente e honesta (ver comunicacao/status-stakeholders.md), reduzindo o efeito surpresa de más notícias.
Transferir: envolver a liderança executiva da consultoria direto na relação com o cliente para administrar a percepção em momentos críticos.
Aceitar: aceitar o desgaste pontual da relação como custo do erro de planejamento, sem ação estruturada de recuperação de confiança.

## 2. O que faríamos hoje com apoio de IA Generativa

Esse projeto aconteceu antes da IA Generativa existir como ferramenta de trabalho. Veja como ela poderia ter ajudado em cada ponto crítico, se estivesse disponível na época:

Na estimativa (Risco 01): usar IA Generativa para comparar a descrição macro do escopo com estimativas de projetos parecidos (reescritas de ERP, módulos fiscais), avisando quando uma estimativa foge do padrão antes da proposta ser fechada.
Na validação de escopo (Risco 02): usar IA para gerar uma lista de perguntas técnicas de esclarecimento a partir da descrição macro do projeto, funcionando como um checklist mínimo antes de assinar o contrato.
No dimensionamento da equipe (Risco 03): usar IA para simular cenários de esforço (otimista, realista, pessimista) a partir das premissas do levantamento macro, mostrando o risco de planejar a equipe com base em um único cenário.
No alinhamento de expectativas (Risco 04): usar IA para escrever, de forma clara e sem ambiguidade, um documento de escopo separando reescrita de tecnologia de correção de regras de negócio, reduzindo a chance de interpretação errada pelos stakeholders.
Na comunicação de status (Risco 05): usar IA para traduzir rápido informações técnicas (horas, desvios, causas) em relatórios executivos focados em impacto de negócio, facilitando a comunicação transparente com o cliente.

## 3. Considerações sobre aplicação das estratégias

Evitar funciona melhor para riscos com causa raiz no processo (Riscos 02 e 04), porque ataca a origem do problema.
Mitigar é a abordagem mais equilibrada quando o processo comercial não pode ser reestruturado rápido (Riscos 01, 03 e 05).
Transferir depende de flexibilidade contratual e comercial, nem sempre disponível em relações de consultoria já estabelecidas.
Aceitar só deveria ser considerado quando o custo de agir for maior que o impacto do risco, o que claramente não era o caso neste projeto, dado o desvio de mais de 2.000% em um único módulo.

Limitação importante: nenhuma dessas estratégias substitui a decisão humana de governança comercial. O ponto de maior alavancagem identificado neste case é a falta de uma etapa de validação técnica antes de fechar o contrato, algo que nenhuma ferramenta sozinha resolveria sem uma mudança de processo.
