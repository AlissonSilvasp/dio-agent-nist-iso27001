# Referenciais NIST e ISO/IEC 27001

## Visão geral

O NIST publica referenciais e orientações de segurança, como o Cybersecurity Framework (CSF) e a publicação SP 800-53. A ISO/IEC 27001 é uma norma internacional que especifica requisitos para um Sistema de Gestão de Segurança da Informação (SGSI).

Essas referências têm estruturas e propósitos diferentes. Podem ser usadas de forma complementar, mas não são equivalentes. A escolha depende do contexto, do escopo, dos objetivos e dos riscos da organização.

## Referenciais do NIST

O NIST (National Institute of Standards and Technology) é uma agência do Departamento de Comércio dos Estados Unidos que publica padrões, diretrizes e recomendações técnicas. Suas publicações têm objetivos e estruturas próprios; por isso, ao iniciar uma análise, identifique qual referência NIST será utilizada.

### NIST Cybersecurity Framework (CSF) 2.0

O NIST CSF 2.0 ajuda organizações a compreender, avaliar, priorizar e comunicar riscos de segurança cibernética. Ele organiza resultados de segurança em seis funções:

- **Govern (Governar):** estabelece estratégia, responsabilidades e supervisão para a gestão de riscos cibernéticos;
- **Identify (Identificar):** ajuda a compreender o contexto, os ativos e os riscos da organização;
- **Protect (Proteger):** orienta a adoção de salvaguardas para reduzir riscos;
- **Detect (Detectar):** ajuda a identificar e analisar possíveis eventos de segurança;
- **Respond (Responder):** orienta as ações diante de um incidente;
- **Recover (Recuperar):** apoia a restauração dos serviços e a melhoria após incidentes.

O CSF 2.0 contém **6 funções, 22 categorias e 106 subcategorias**. A função Govern foi adicionada na versão 2.0. A versão 1.1 tinha cinco funções: Identify, Protect, Detect, Respond e Recover.

O CSF organiza resultados de segurança em alto nível. Ele não determina uma única forma de implementação nem, por si só, comprova conformidade ou certificação.

### NIST SP 800-53

O NIST SP 800-53 é uma publicação diferente do CSF. Ela apresenta um catálogo de controles de segurança e privacidade, desenvolvido para sistemas e organizações federais dos Estados Unidos e também utilizado como referência por outras organizações.

O CSF e o SP 800-53 não devem ser tratados como se tivessem a mesma estrutura ou finalidade. O CSF ajuda a organizar resultados de segurança; o SP 800-53 oferece controles detalhados. Identifique a versão da publicação usada na análise.

## ISO/IEC 27001

A ISO/IEC 27001 é uma norma internacional que especifica requisitos para estabelecer, implementar, manter e melhorar continuamente um Sistema de Gestão de Segurança da Informação (SGSI).

A norma orienta a organização a:

- compreender seu contexto e definir o escopo do SGSI;
- avaliar e tratar riscos de segurança da informação;
- definir responsabilidades e políticas;
- acompanhar o desempenho do sistema de gestão;
- promover melhorias contínuas.

Na edição **ISO/IEC 27001:2022**, as cláusulas **4 a 10** contêm os requisitos do SGSI. São sete cláusulas numeradas de 4 a 10.

O **Anexo A** dessa edição contém **93 controles de referência**, organizados em quatro temas:

- organizacionais;
- relacionados a pessoas;
- físicos;
- tecnológicos.

As cláusulas 4 a 10 são requisitos do sistema de gestão; não devem ser confundidas com os controles do Anexo A. A organização determina os controles necessários com base no tratamento de riscos, compara sua seleção com o Anexo A e registra as decisões na Declaração de Aplicabilidade, incluindo justificativas e o status de implementação.

A ISO/IEC 27001 especifica requisitos para o SGSI. A ISO/IEC 27002 fornece orientação sobre controles de segurança da informação; não é a mesma norma nem substitui os requisitos da ISO/IEC 27001.

## Risco e controles de segurança

A avaliação de riscos pode considerar fatores como ameaças, vulnerabilidades, probabilidade e impacto. A forma de analisar e combinar esses fatores depende do método adotado pela organização.

Um controle de segurança é uma medida usada para modificar o risco. Conforme o contexto, ele pode:

- reduzir a probabilidade de um evento;
- reduzir o impacto de um incidente;
- melhorar a capacidade de detectar, responder e recuperar;
- gerar evidências para avaliar sua implementação e eficácia.

A existência de um controle não garante, por si só, que o risco esteja adequadamente tratado. É importante verificar se o controle está implementado, funciona como esperado e é revisado periodicamente.

## Exemplos de áreas de controle

Os exemplos abaixo são áreas comuns de segurança. Não substituem a consulta aos requisitos da ISO/IEC 27001 ou aos controles de uma publicação NIST específica.

### Governança e políticas

A organização define políticas, responsabilidades e processos de supervisão alinhados ao seu contexto e aos seus objetivos.

### Gestão de ativos

A organização identifica e classifica ativos que precisam de proteção, como:

- dados;
- sistemas e aplicações;
- dispositivos;
- infraestrutura;
- credenciais e segredos.

### Identidade e acesso

As práticas de gestão de acesso podem incluir:

- autenticação adequada;
- autorização baseada nas responsabilidades;
- separação de funções;
- princípio do menor privilégio;
- revisão periódica de acessos;
- gestão segura de contas e credenciais.

### Segurança de infraestrutura

A proteção de redes, servidores, dispositivos e serviços pode incluir:

- segmentação de rede;
- atualização de sistemas;
- configuração segura;
- monitoramento de eventos;
- gestão de vulnerabilidades;
- proteção e revisão de registros.

### Proteção de dados

Os dados devem ser protegidos durante seu ciclo de vida:

- coleta;
- armazenamento;
- processamento;
- transmissão;
- backup;
- descarte.

As medidas podem incluir classificação de dados, criptografia, controle de compartilhamento, regras de retenção e testes de restauração de backups.

### Resposta a incidentes

A organização precisa estar preparada para identificar, analisar e responder a incidentes. Isso pode envolver:

- processos e responsabilidades definidos;
- comunicação interna e externa;
- preservação de evidências;
- análise do incidente;
- revisão posterior e melhoria dos processos.

### Continuidade e recuperação

A preparação para interrupções pode incluir:

- backups;
- testes de recuperação;
- planos de continuidade;
- planos de contingência;
- priorização de serviços críticos.

## NIST e ISO/IEC 27001 na prática

Os referenciais NIST e a ISO/IEC 27001 podem ser usados de forma complementar, mas não são equivalentes:

- o NIST CSF 2.0 organiza resultados de segurança em seis funções, 22 categorias e 106 subcategorias;
- o NIST SP 800-53 apresenta um catálogo detalhado de controles de segurança e privacidade;
- a ISO/IEC 27001 estabelece requisitos para um sistema de gestão de segurança da informação;
- o Anexo A da ISO/IEC 27001:2022 contém 93 controles de referência;
- um mapeamento entre referências depende das versões, do escopo e do contexto analisados.

Usar uma referência não comprova automaticamente conformidade com outra. Também não substitui a avaliação de riscos, a implementação dos controles ou a análise de evidências.

## Avaliação de implementação e maturidade

Um controle pode estar documentado sem ser executado, ou estar em operação sem evidências suficientes de sua eficácia. Ao avaliar uma prática, considere:

- se há política ou processo definido;
- se existem responsáveis;
- se a prática é executada de forma consistente;
- se sua operação é monitorada;
- se há evidências adequadas;
- se sua eficácia é revisada;
- se os resultados levam a melhorias.

## Boas práticas para análise

- identifique a referência e a versão utilizadas;
- defina o objetivo e o escopo da análise;
- relacione cada controle ao risco que pretende tratar;
- verifique se o controle está documentado e em operação;
- procure evidências apropriadas, sem expor informações confidenciais;
- diferencie conformidade documental de efetividade operacional;
- registre lacunas, responsáveis e prioridades;
- consulte as publicações oficiais para requisitos e detalhes atualizados.

## Conclusão

Os referenciais NIST e a ISO/IEC 27001 oferecem abordagens diferentes que podem apoiar a gestão de segurança da informação. Uma análise útil considera o contexto, o escopo, os riscos, os controles aplicáveis e as evidências de implementação.

O objetivo é entender por que cada controle é necessário e como ele contribui para tratar riscos, em vez de apenas preencher uma lista.