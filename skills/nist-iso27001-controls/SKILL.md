---
name: nist-iso27001-controls
description: Use quando o estudante precisar mapear, analisar ou priorizar controles de segurança com base em NIST e ISO 27001, identificando lacunas, riscos e ações de mitigação.
---

# Skill: Controles NIST e ISO 27001

Ajuda o estudante a interpretar e aplicar controles de segurança em contexto real, com foco em governança, risco, continuidade e proteção de ativos.

## Quando usar

Use esta skill quando o estudante:

- pedir ajuda para entender controles da NIST ou ISO 27001;
- quiser comparar requisitos de segurança com práticas reais;
- precisar mapear lacunas em uma organização ou sistema;
- avaliar maturidade de controles;
- montar plano de ação para conformidade ou segurança;
- precisar relacionar risco, controle e evidência.

## Processo

### 1. Entenda o contexto antes de classificar qualquer controle

Pergunte, uma coisa por vez:

- qual organização, processo ou sistema está sendo analisado;
- qual é o objetivo: conformidade, segurança, auditoria ou risco;
- existe infraestrutura, aplicação, dados ou operação específica envolvida;
- há uma referência do framework que o estudante quer usar: NIST CSF, NIST 800-53, ISO 27001 ou ambos;
- qual é o nível de maturidade atual;
- qual versão ou edição está sendo usada (por exemplo, NIST CSF 2.0 ou ISO/IEC 27001:2022).

Se faltar informação, peça contexto antes de sugerir qualquer controle ou remediação.

### 2. Identifique o domínio e o objetivo do controle

Explique em linguagem clara:

- qual área está sendo coberta;
- qual risco ela atende;
- qual princípio de segurança ela protege;
- se o objetivo é prevenir, detectar, responder ou recuperar.

Os principais grupos típicos incluem:

- governança e políticas;
- gestão de ativos;
- acesso e identidade;
- segurança de redes e infraestrutura;
- proteção de dados;
- resposta a incidentes;
- continuidade de negócios;
- conscientização e treinamento;
- monitoramento e evidência.


### 3. Relacione a análise ao referencial escolhido

Consulte `agent/knowledge/nist-iso27001.md` e use a referência e a versão confirmadas pelo estudante. Não misture estruturas ou numerações de referenciais diferentes.

- **NIST CSF 2.0:** organize a análise pelas seis funções: Govern, Identify, Protect, Detect, Respond e Recover. O CSF 2.0 tem 22 categorias e 106 subcategorias; não chame funções ou categorias de controles.
- **ISO/IEC 27001:2022:** diferencie os requisitos do SGSI, nas cláusulas 4 a 10, dos 93 controles de referência do Anexo A. Os controles do Anexo A estão organizados em quatro temas: organizacionais, relacionados a pessoas, físicos e tecnológicos. A aplicabilidade depende do contexto e do tratamento de riscos da organização.
- **NIST SP 800-53:** use a versão confirmada. É um catálogo de controles de segurança e privacidade, diferente do CSF e do SP 800-30.
- **NIST SP 800-30:** é uma referência para avaliação de riscos, não um catálogo de controles.

Ao mapear referências, explique que qualquer correspondência é contextual: NIST e ISO/IEC 27001 têm estruturas e propósitos distintos. Se a versão ou a correspondência não puder ser confirmada, declare a incerteza em vez de inventar um número ou controle.

### 4. Avalie lacunas, riscos e impacto

Estruture a análise em partes claras:

#### Controle em análise
Descreva o controle ou área de governança.

#### Risco coberto
Explique o risco que o controle mitiga.

#### Evidência esperada
Cite exemplos de evidência:
- políticas;
- procedimentos;
- registros de acesso;
- relatórios de monitoramento;
- treinamento;
- testes;
- logs;
- auditorias internas.

#### Lacuna identificada
Descreva se o controle:
- não existe;
- existe, mas não é efetivo;
- é documentado, mas não é realizado;
- é operacional, mas sem evidência.

#### Impacto
Explicite o efeito de falha:
- vazamento de dados;
- indisponibilidade;
- perda de confiança;
- não conformidade;
- penalidade regulatória ou operacional.

### 5. Priorize ações de mitigação

Sempre oriente a correção com foco em criticidade e viabilidade:

- priorizar controles que reduzam maior risco;
- corrigir lacunas de governança antes de controles mais específicos;
- garantir evidência e rastreabilidade;
- priorizar controles que protejam ativos críticos;
- definir cronograma e responsável;
- vincular cada ação a risco, impacto e prazo.

### 6. Reforce o caráter defensivo da análise

O estudante deve aprender a pensar em:

- governança;
- risco;
- evidência;
- operação real;
- continuidade do negócio;
- accountability.

Não trate controles como checklist vazio. Eles são mecanismos para reduzir risco e demonstrar compromisso com segurança.

### 7. Finalize com uma recomendação prática

Ao concluir, apresente um resumo no formato:

#### Resumo executivo
- contexto;
- risco principal;
- domínio envolvido;
- status do controle.

#### Lacunas
- o que está ausente ou incompleto.

#### Prioridades
- o que resolver primeiro;
- o que manter em acompanhamento;
- o que requer documentação ou evidência.

#### Próximos passos
- políticas;
- treinamento;
- testes;
- monitoramento;
- governança e revisão.

## Regras

Sempre:
- consulte `agent/knowledge/nist-iso27001.md` antes de responder sobre esses referenciais;
- confirme o referencial e a versão antes de apresentar requisitos, números ou controles;
- para o NIST CSF 2.0, informe seis funções: Govern, Identify, Protect, Detect, Respond e Recover;
- não confunda as funções do CSF com suas 22 categorias e 106 subcategorias;
- para a ISO/IEC 27001:2022, diferencie os requisitos das cláusulas 4 a 10 dos 93 controles de referência do Anexo A;
- se não tiver certeza da edição ou do dado, declare a incerteza e não invente.

Nunca:
- apresente “4 cláusulas” como o total de cláusulas de requisitos da ISO/IEC 27001:2022;
- omita Govern ao descrever as funções do NIST CSF 2.0;
- trate versões diferentes como se tivessem a mesma estrutura.
## Lembre-se

NIST e ISO 27001 não são só “listas de regras”: são estruturas para reduzir risco, aumentar resiliência e demonstrar controle em operações reais. O melhor uso da skill é ajudar o estudante a pensar como quem analisa segurança e governança, não apenas como quem copia requisitos.