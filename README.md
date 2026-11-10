# 🤖 DIO Agent

> Seu mentor de Inteligência Artificial para aprender mais e melhor na [DIO](https://dio.me).

O **DIO Agent** é um agente de IA que acompanha você na sua jornada de estudos. Ele conhece as experiências da DIO (Bootcamps, Formações, Cursos, Desafios e muito mais) e ajuda você a estudar com mais clareza, destravar desafios e entender qualquer conceito.

E você não precisa instalar nada complicado. Em **3 passos simples**, o seu mentor de IA estará pronto para usar.

---

## ✨ Antes de começar: dois conceitos rápidos

Para usar o DIO Agent, basta entender duas palavras. As duas estão no [Glossário completo](docs/glossary.md), mas aqui vai a versão rápida:

- 🧠 **Agente de IA:** um chatbot comum responde perguntas, como um buscador mais esperto. Um *agente* de IA vai além: ele lê, planeja e executa passos para te ajudar a alcançar um objetivo. É a diferença entre alguém que te explica o caminho e alguém que caminha junto com você. O DIO Agent é um agente desse tipo: um tutor particular que acompanha a sua evolução.

- 🖥️ **Harness:** é o programa onde a conversa com o agente acontece. Vale a comparação: o agente é o professor, e o harness é a sala de aula. O mesmo professor pode dar aula em salas diferentes. Por isso o DIO Agent funciona em qualquer harness: você escolhe a "sala" no Passo 1, e o seu mentor continua o mesmo.

Pronto. Com isso já dá para começar.

---

## 🎯 O que o DIO Agent faz por você

| Você precisa de... | O DIO Agent... |
|--------------------|----------------|
| Saber por onde começar | Monta um plano de estudos no seu ritmo |
| Destravar um desafio | Te guia até a solução, sem entregar a resposta pronta |
| Entender um conceito | Explica de forma simples, com analogias e exemplos |

Ele conhece os formatos da DIO: Bootcamps, Formações, Acelerações, Cursos, English4Tech, Desafios de Código, Desafios de Projeto, Desafios Criativos, Lives e Mentorias. Assim, as recomendações sempre apontam para algo que você já tem na plataforma.

---

## 🚀 Comece em 3 passos

### 1️⃣ Instale um Harness

O harness é o programa que dá vida ao agente. Recomendamos o **Google Antigravity**, que tem limites de uso mais generosos para quem está começando. Mas qualquer harness moderno funciona.

| Harness | Documentação oficial |
|---------|----------------------|
| Google Antigravity (recomendado) | https://antigravity.google/docs |
| Claude Code | https://docs.claude.com/en/docs/claude-code |
| Codex | https://developers.openai.com/codex |
| OpenCode | https://opencode.ai/docs |
| Hermes | https://hermes-agent.nousresearch.com/docs |

Escolha um e siga o passo a passo da documentação oficial dele. Cada documentação já traz tudo certinho para o seu sistema, então a instalação é tranquila.

### 2️⃣ Configure o DIO Agent

Agora você vai baixar este repositório para o seu computador. Escolha a forma mais simples para você:

**Opção A: com Git** (se você já usa Git)

```bash

(https://github.com/AlissonSilvasp/dio-agent-nist-iso27001.git)```

**Opção B: baixando o .zip** (se você não usa Git)

Na página do repositório no GitHub, clique no botão verde **Code** e depois em **Download ZIP**. Em seguida, extraia a pasta em um lugar fácil de encontrar.

Com o repositório baixado, abra a pasta `dio-agent` no harness que você instalou. Cada harness tem o seu jeito de abrir uma pasta de projeto, e a documentação dele mostra como fazer isso.

E é só isso! O harness lê automaticamente o arquivo `AGENTS.md` e o agente já sabe quem é: o seu mentor de estudos da DIO.

> 🔄 **Fique de olho nas atualizações.** Não importa se você usou o Git ou o .zip: o repositório do DIO Agent evolui com o tempo. De tempos em tempos, vale voltar aqui e pegar a versão mais recente. Quem usou Git pode rodar `git pull` (ou pedir pro próprio DIO Agent rodar); quem baixou o .zip pode baixar de novo. Assim o seu mentor está sempre com o melhor que a gente tem a oferecer.

### 3️⃣ Hands On!

Agora é só conversar. Você pode falar naturalmente, com as suas palavras. Mas, principalmente nas primeiras vezes, vale usar um modelo de prompt pronto: é só copiar e preencher os campos entre colchetes. Quanto mais contexto você dá, melhor o agente ajuda.

**🗺️ Plano de estudos**

```
Quero montar um plano de estudos (se possível, com materiais complementares).
- Meu objetivo: [ex: aprender mais sobre IA, ser dev back-end, concluir um bootcamp]
- Experiência ou carreira da DIO: [URL ou nome do bootcamp/formação, ou de uma carreira da DIO]
- Meu nível hoje: [iniciante, intermediário, avançado]
- Tempo disponível: [ex: 1 hora por dia, de segunda a sexta]
```

**🔓 Destravar desafio**

```
Estou travado em um Desafio de [Código, Projeto ou Criativo] da DIO.
- O que o desafio pede: [cole o enunciado ou descreva]
- Onde eu travei: [explique o ponto da dificuldade]
- Meu código atual: [cole aqui, se for Desafio de Código]
- Link do repositório base: [cole aqui, se for Desafio de Projeto]
Me ajuda a destravar sem dar a resposta pronta.
```

**💡 Explicar conceito**

```
Me explica o conceito de [ex: API, laço de repetição, herança].
- Meu nível: [nunca vi, já ouvi falar, quero aprofundar]
- Onde apareceu: [ex: no curso X de um bootcamp] (opcional)
```

Não precisa de comando especial nem de formato perfeito: o agente conduz a conversa a partir daí e pede mais detalhes se precisar.

---

## 🧩 As skills do agente

Uma **skill** é uma habilidade do agente, descrita em um guia passo a passo. O DIO Agent possui as seguintes skills:

| Skill | Para que serve |
|-------|----------------|
| [Plano de estudos](skills/study-plan/SKILL.md) | Organiza o que estudar, em que ordem e em quanto tempo |
| [Destravar desafio](skills/unblock-challenge/SKILL.md) | Conduz você até a solução de um desafio, sem dar a resposta pronta |
| [Explicar conceito](skills/explain-concept/SKILL.md) | Explica conceitos de forma didática, com analogias e exemplos |
| [Pesquisa na web](skills/web-search/SKILL.md) | Ajuda a encontrar informações atuais e verificáveis |
| [Revisão de portfólio](skills/portfolio-review/SKILL.md) | Ajuda a revisar um portfólio |
| [Análise de vulnerabilidades](skills/vulnerability-analysis/SKILL.MD) | Orienta análises defensivas de vulnerabilidades |
| [Controles NIST e ISO/IEC 27001](skills/nist-iso27001-controls/SKILL.md) | Ajuda a compreender e avaliar controles, riscos e evidências |

Você não precisa "chamar" uma skill. O agente deve perceber o que você precisa e aplicar a skill adequada.

---

## 🗂️ Estrutura do repositório

```
dio-agent/
├── README.md
├── AGENTS.md
├── CLAUDE.md
├── agent/
│   ├── persona.md
│   └── knowledge/
│       ├── dio-platform.md
│       ├── learning-experiences.md
│       ├── security-basics.md
│       └── nist-iso27001.md
├── skills/
│   ├── README.md
│   ├── explain-concept/
│   ├── nist-iso27001-controls/
│   │   ├── SKILL.md
│   │   └── README.MD
│   ├── portfolio-review/
│   ├── study-plan/
│   ├── unblock-challenge/
│   ├── vulnerability-analysis/
│   │   ├── SKILL.MD
│   │   └── README.md
│   └── web-search/
└── docs/
    └── glossary.md
```

> 🔍 **Por que funciona em qualquer harness?** O coração do projeto é o arquivo `AGENTS.md`, um padrão aberto que harnesses modernos sabem ler. O `CLAUDE.md` apenas aponta para ele, então você pode usar o harness que preferir.

---

## 📖 Glossário rápido

Termos como *agente*, *harness*, *skill* e *prompt* estão explicados com analogias simples no **[Glossário completo](docs/glossary.md)**. Se algum termo soar estranho, comece por lá.

---

## 💬 Sobre este projeto

O DIO Agent foi criado para acompanhar você desde o início dos Bootcamps e Formações da DIO. A ideia é simples: aprender na era da IA fica mais fácil quando você tem um mentor disponível a qualquer hora.

Bons estudos, e vem com a gente. 🚀

---

## Especialização em NIST e ISO/IEC 27001

Este projeto foi ampliado para ajudar estudantes a compreender referenciais de segurança da informação do NIST e da ISO/IEC 27001. Escolhi essa especialização para que o agente ajude a relacionar riscos, controles e evidências ao contexto analisado, em vez de fornecer recomendações genéricas.

### Arquivos criados ou atualizados

- `skills/nist-iso27001-controls/SKILL.md` — processo que orienta o agente a perguntar sobre referencial, versão e escopo antes da análise.
- `skills/nist-iso27001-controls/README.MD` — explicação da skill.
- `agent/knowledge/nist-iso27001.md` — informações sobre NIST e ISO/IEC 27001.
- `agent/persona.md` — orientações sobre o comportamento do agente nessa especialização.
- `AGENTS.md` — registro da skill e indicação de quando consultar o knowledge.

### Melhoria escolhida

A melhoria escolhida foi fazer o agente confirmar o referencial, a versão e o escopo antes de avaliar controles. Isso ajuda a evitar que ele misture estruturas diferentes ou apresente requisitos sem considerar o contexto.

O agente também deve distinguir:

- o NIST CSF do NIST SP 800-53 e do NIST SP 800-30;
- as seis funções do NIST CSF 2.0 — Govern, Identify, Protect, Detect, Respond e Recover — de categorias, subcategorias e controles;
- os requisitos das cláusulas 4 a 10 da ISO/IEC 27001:2022 dos 93 controles de referência do Anexo A.

### Como executar no Hermes

1. Instale e configure o Hermes seguindo a [documentação oficial](https://hermes-agent.nousresearch.com/docs).
2. Abra a pasta deste projeto no VS Code.
3. Abra o terminal integrado na raiz do projeto, onde está o arquivo `AGENTS.md`.
4. Inicie o Hermes nesse terminal, conforme o comando indicado na documentação da sua instalação.
5. Faça uma pergunta sobre NIST ou ISO/IEC 27001.

Iniciar o Hermes na raiz do projeto ajuda o harness a encontrar o `AGENTS.md`, as skills e os arquivos de conhecimento.


### Teste realizado

O teste foi realizado com uma empresa fictícia de comércio eletrônico. O Hermes perguntou qual referencial e versão seriam usados, confirmou o escopo e, após receber os dados do cenário, apresentou uma avaliação preliminar usando o NIST CSF 2.0. A resposta relacionou os backups não testados a RC.RP, a falta de revisão periódica de acessos a PR.AA e o monitoramento irregular de logs a DE.CM. O agente não declarou conformidade e deixou detalhes não informados como pontos a confirmar.

Durante os testes, respostas anteriores apresentaram imprecisões, que foram apontadas e revisadas com novas instruções. Por isso, os resultados são educacionais e devem ser conferidos com fontes oficiais. O teste não comprova a precisão de todos os mapeamentos nem a conformidade de uma organização.

