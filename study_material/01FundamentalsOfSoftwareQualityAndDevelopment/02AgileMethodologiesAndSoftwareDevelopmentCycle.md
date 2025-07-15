# Fundamentos de Qualidade e Desenvolvimento de Software 🎯

![GitHub repo size](https://img.shields.io/github/repo-size/fzanneti/quality-assurance-qa-experience-training)
![GitHub forks](https://img.shields.io/github/forks/fzanneti/quality-assurance-qa-experience-training?style=social)
![GitHub Repo stars](https://img.shields.io/github/stars/fzanneti/quality-assurance-qa-experience-training?style=social)
![Plataforma](https://img.shields.io/badge/Powered%20by-DIO.io-red?logo=data:image/svg+xml;base64,PHN2ZyBmaWxsPSIjZmZmIiB2aWV3Qm94PSIwIDAgMzIgMzIiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+PHBhdGggZD0iTTYuNzEgMy4yNWMtMi44OCAxLjQxLTUuMDcgNC4yMy01LjA3IDcuNzYgMCAzLjU4IDIuMjggNi43IDUuMzMgOC4xNSAxLjgzLS42MiAyLjQtMi4yNiAyLjQtMy44MSAwLS4yMy0uMDItLjQ1LS4wNS0uNjZBLjQ0LjQ0IDAgMDExMC4xIDExYy4yNC0uNzUuMTEtMS41My0uMy0yLjIyQzguOTIgNy45NiA3LjMzIDcuNSA1Ljc0IDcuNjZhNS41NSA1LjU1IDAgM)
![Autor](https://img.shields.io/badge/Autor-fzanneti-blue?style=flat-square&logo=github)

---

> 📚 [Material Complementar (Repositório) - Bootcamp DIO X WEX](https://github.com/fzanneti/wex-e2e-csharp/tree/main/study_material/06IntroductionToSoftwareQuality)

---

# Metodologias Ágeis e Ciclo de Desenvolvimento de Software 🔄

## 🔧 Processo de Software

### 📌 Apresentação

Um **processo de software** é como um mapa que guia o desenvolvimento de sistemas, desde a ideia inicial até a entrega de um produto funcional. Ele engloba todas as **atividades, métodos, práticas e ferramentas** usadas para criar e manter software com qualidade, eficiência e dentro do prazo. Pense nele como a receita de um bolo: cada ingrediente (atividade) e cada passo (método) precisa ser seguido para garantir o resultado esperado.  

**Por que isso é importante para QA?**  

- O QA não é só "testar". Ele atua em todas as etapas do processo, garantindo que cada parte do software atenda aos padrões de qualidade e às necessidades do cliente.  

---

### 🧩 Definindo Processo, Fluxo e Padrões de Software

- **Processo de Software:** É o conjunto de etapas organizadas para transformar uma necessidade (ex.: "quero um app de delivery") em um sistema funcional. Exemplo: análise de requisitos → design → codificação → testes → entrega.
- **Fluxo de Trabalho:** É a ordem lógica em que essas etapas acontecem. Por exemplo, você não testa antes de codificar. O fluxo ajuda a evitar bagunça e retrabalho.
- **Padrões de Software:** São normas que garantem consistência e qualidade. Exemplos incluem:
  - **ISO/IEC 12207:** define processos de ciclo de vida de software.
  - **IEEE 829:** padrão para documentação de testes.
  - **CMMI (Capability Maturity Model Integration):** modelo para melhorar processos organizacionais.

> 🎯 **Objetivo:** Padronizar o desenvolvimento para garantir previsibilidade, qualidade e eficiência.     
> ✍️ **Dica de Estudo:** Familiarize-se com esses padrões, pois muitas empresas os utilizam para auditorias e certificações. Eles são como "regras do jogo" que o QA precisa conhecer.

---

### 🗂️ Modelo Prescritivo - Tradicional 

Os **Modelos Prescritivos** são abordagens tradicionais, estruturadas e sequenciais, ideais para projetos com requisitos bem definidos e pouco propensos a mudanças. Eles seguem um caminho linear, como um checklist.

- **Modelo Cascata (Waterfall):**
  - **O que é?** Um processo linear onde cada fase (requisitos, design, implementação, testes, manutenção) é concluída antes da próxima começar.
  - **Exemplo:** Um projeto de software para um banco, onde os requisitos são fixos e regulados por lei.
  - **Vantagem:** Fácil de gerenciar, com documentação clara.
  - **Limitação:** Pouco flexível para mudanças durante o projeto.
  - **Quando usar?** Projetos com escopo estável, como sistemas governamentais.

- **Modelo V:**
  - **O que é?** Uma variação do Cascata que associa cada fase de desenvolvimento a uma fase de teste correspondente (ex.: design é testado com revisão técnica, implementação com testes unitários).
  - **Exemplo:** Para cada requisito, há um teste de aceitação planejado desde o início.
  - **Vantagem:** Garante validação e verificação em cada etapa.
  - **Limitação:** Ainda é rígido para mudanças.

> 🔍 **Para QA:** No Modelo V, o QA planeja os testes desde a fase de requisitos, garantindo que cada entrega seja validada contra os critérios iniciais.

---

### 🔄 Modelos Incremental, Iterativo e Concorrente

- **Incremental:**
  - **O que é?** O software é construído e entregue em partes menores (incrementos), cada uma funcional por si só.
  - **Exemplo:** Um app de e-commerce pode lançar primeiro o módulo de busca de produtos, depois o carrinho de compras, e assim por diante.
  - **Vantagem:** Permite entregas rápidas e feedback precoce do cliente.
  - **Para QA:** Cada incremento precisa ser testado individualmente e integrado com os anteriores.

- **Iterativo:**
  - **O que é?** O software é desenvolvido em ciclos, com cada iteração refinando o produto com base em feedback.
  - **Exemplo:** Um sistema de gestão começa com uma versão básica e vai sendo aprimorado a cada iteração.
  - **Vantagem:** Permite corrigir erros e ajustar requisitos ao longo do tempo.
  - **Para QA:** Testes são repetidos e expandidos a cada iteração, com foco em regressão.

- **Concorrente:**
  - **O que é?** Diferentes atividades (design, codificação, testes) ocorrem ao mesmo tempo.
  - **Exemplo:** Enquanto uma equipe codifica a funcionalidade A, outra testa a funcionalidade B.
  - **Vantagem:** Acelera o desenvolvimento, mas exige boa comunicação.
  - **Para QA:** Requer automação de testes para acompanhar o ritmo acelerado.

> 🔍 **Vantagem:** Flexibilidade para adaptar o projeto conforme o aprendizado e mudanças nos requisitos.

---

### 🚀 Modelos Especializados

Esses modelos combinam características dos anteriores, mas com enfoques específicos:

- **Modelo RAD (Rapid Application Development):**
  - **O que é?** Prioriza a criação rápida de protótipos para validar ideias com o cliente.
  - **Exemplo:** Um startup cria um protótipo de app em semanas para testar no mercado.
  - **Vantagem:** Rápido e centrado no cliente.
  - **Limitação:** Pode gerar código menos robusto se não houver planejamento.
  - **Para QA:** Testes exploratórios são comuns para validar protótipos rapidamente.

- **Modelo Espiral:**
  - **O que é?** Combina iteração com análise de riscos em cada ciclo.
  - **Exemplo:** Um sistema médico crítico avalia riscos (ex.: falhas de segurança) antes de cada iteração.
  - **Vantagem:** Ideal para projetos complexos e arriscados.
  - **Para QA:** Envolve testes baseados em riscos para mitigar problemas críticos.

- **Modelo DevOps:**
  - **O que é?** Integra desenvolvimento (Dev) e operações (Ops) para entregas contínuas e automáticas.
  - **Exemplo:** Um site como a Netflix, que atualiza funcionalidades sem interrupção.
  - **Vantagem:** Automação e integração contínua garantem entregas rápidas e confiáveis.
  - **Para QA:** Testes automatizados são essenciais, com pipelines CI/CD (Integração Contínua/Entrega Contínua).

> **Tendência em 2025:** DevOps está dominando o mercado, com ferramentas como GitHub Actions, Jenkins e CircleCI sendo amplamente usadas para automação de testes e entregas.

---

### 🏗️ Processo Unificado

O **Rational Unified Process (RUP)** é um framework que organiza o desenvolvimento em quatro fases:

1. **Iniciação:** Define o escopo e os objetivos do projeto. Ex.: identificar stakeholders e requisitos iniciais.
2. **Elaboração:** Planeja a arquitetura e detalha os requisitos. Ex.: criar diagramas UML.
3. **Construção:** Desenvolve e testa o software. Ex.: codificação e testes unitários.
4. **Transição:** Entrega o software ao cliente e realiza ajustes finais. Ex.: implantação e treinamento.

> 🛠️ **Diferencial:** Baseado em casos de uso e orientado a arquitetura.
> 🔍 **Para QA:** O RUP enfatiza casos de uso, então o QA deve garantir que cada funcionalidade atenda aos cenários definidos. Ferramentas como Jira ou Azure DevOps ajudam a rastrear esses casos.

---

## 🚀 Desenvolvimento Ágil

### 📜 O Manifesto Ágil

Lançado em 2001, o **Manifesto Ágil** revolucionou o desenvolvimento de software ao priorizar:
1. **Indivíduos e interações** sobre processos e ferramentas.
2. **Software funcionando** sobre documentação extensa.
3. **Colaboração com o cliente** sobre negociação de contratos.
4. **Resposta a mudanças** sobre seguir um plano rígido.

> 💡 **Princípio:** Entregas frequentes e foco no cliente. 
> 💡 Em vez de gastar meses escrevendo um documento de requisitos, uma equipe ágil entrega uma versão inicial do software em semanas e ajusta com base no feedback do cliente.
> 📜 **Dica de Estudo:** Leia o [Manifesto Ágil](https://agilemanifesto.org/iso/ptbr/) e seus 12 princípios. Eles são a base de frameworks como Scrum e Kanban.

---

### ⚡ Extreme Programming (XP)

O **XP** é uma metodologia ágil focada em práticas de engenharia para melhorar a qualidade do código e a colaboração. Suas práticas incluem:

- **Programação em Par:** Dois desenvolvedores trabalham juntos, um codificando e outro revisando.
- **TDD (Test-Driven Development):** Escrever testes antes do código, garantindo que o software atenda aos requisitos.
- **Integração Contínua:** Código é integrado e testado frequentemente, usando ferramentas como Jenkins ou GitLab CI.
- **Feedback Constante:** Reuniões regulares com o cliente para validar entregas.

> 🔧 **Objetivo:** Melhorar a qualidade do software e a capacidade de resposta às mudanças.
> 🔍 **Para QA:** No XP, o QA colabora na escrita de testes automatizados e valida entregas frequentes, garantindo que cada funcionalidade seja testada antes da integração.

---

### 🏉 Scrum

O **Scrum** é o framework ágil mais usado globalmente. Ele organiza o trabalho em **Sprints** (ciclos de 1 a 4 semanas) e define:

- **Papéis:**
  - **Product Owner:** Define o que será construído (prioriza o Product Backlog).
  - **Scrum Master:** Facilita o processo e remove impedimentos.
  - **Time de Desenvolvimento:** Constrói e testa o software.

- **Eventos:**
  - **Sprint Planning:** Planeja o que será feito no Sprint.
  - **Daily Scrum:** Reunião diária de 15 minutos para alinhamento.
  - **Sprint Review:** Apresenta o incremento ao cliente.
  - **Sprint Retrospective:** Reflete sobre o que funcionou e o que melhorar.

- **Artefatos:**
  - **Product Backlog:** Lista de tudo que o produto precisa.
  - **Sprint Backlog:** Itens selecionados para o Sprint.
  - **Incremento:** Produto funcional entregue ao final do Sprint.

> **Para QA:** No Scrum, o QA participa ativamente do Sprint Planning, escreve casos de teste para o Sprint Backlog e garante que o Incremento seja testado antes da Review.
> **Tendência em 2025:** Ferramentas como Jira, Trello e Monday.com são amplamente usadas para gerenciar Sprints e Backlogs.

---

### 📌 Outros Modelos Ágeis

- **Kanban:**
  - **O que é?** Usa um quadro visual (ex.: Trello) para gerenciar o fluxo de trabalho contínuo, com colunas como "A Fazer", "Em Andamento" e "Concluído".
  - **Vantagem:** Ideal para equipes que precisam gerenciar tarefas contínuas, como suporte.
  - **Para QA:** Monitora o fluxo de tarefas de teste e identifica gargalos.

- **Lean Software Development:**
  - **O que é?** Inspirado na manufatura enxuta, elimina desperdícios (ex.: funcionalidades desnecessárias) e maximiza valor para o cliente.
  - **Exemplo:** Focar apenas nas funcionalidades que o usuário realmente precisa.
  - **Para QA:** Prioriza testes que agregam valor ao cliente.

- **Crystal:**
  - **O que é?** Adapta o processo ao tamanho e criticidade do projeto, com menos rigidez que o Scrum.
  - **Exemplo:** Projetos pequenos podem usar Crystal Clear, com menos formalidades.
  - **Para QA:** Flexibilidade para ajustar o nível de testes conforme o projeto.

- **FDD (Feature-Driven Development):**
  - **O que é?** Foca no desenvolvimento de funcionalidades específicas, com planejamento detalhado.
  - **Exemplo:** Um app pode ser dividido em features como "login" e "busca".
  - **Para QA:** Testes são planejados por funcionalidade, com validação clara de cada feature.

---

## 🧪 Testes no Mundo Ágil

### 🌍 Contextualizando a Atividade de Teste
No mundo ágil, testes não são uma fase isolada no final do projeto. Eles são **contínuos** e integrados desde o início, garantindo que cada entrega (incremento) tenha qualidade. O QA deixa de ser um "fiscal" e se torna um **parceiro do time**, colaborando em todas as etapas.

> **Exemplo:** Em um Sprint de 2 semanas, o QA escreve casos de teste durante o planejamento, executa testes automatizados durante o desenvolvimento e valida o incremento na Sprint Review.

---

### 🔄 Testes nas Abordagens Ágeis

- **Testes Contínuos:** Executados a cada commit ou integração, usando ferramentas como Selenium ou Cypress.
- **Automação de Testes:** Essencial para acompanhar o ritmo ágil. Ex.: testes de API com Postman ou testes de interface com Playwright.
- **Testes Baseados em Riscos:** Prioriza testar funcionalidades críticas que impactam o negócio, como o pagamento em um e-commerce.

> **Benefício:** Identificar defeitos cedo reduz custos, pois corrigir um bug na fase de desenvolvimento é muito mais barato que após a entrega.
> **Tendência em 2025:** A automação de testes está evoluindo com IA, com ferramentas como Testim e Mabl usando machine learning para gerar e otimizar casos de teste.

---

### 🧰 Métodos de Testes nos Modelos Ágeis

- **TDD (Test-Driven Development):**
  - **O que é?** Escrever o teste antes do código, garantindo que o software atenda aos requisitos desde o início.
  - **Exemplo:** Para uma funcionalidade de login, o QA escreve um teste que verifica se o usuário é autenticado com credenciais válidas antes do desenvolvedor codificar.
  - **Vantagem:** Código mais limpo e menos bugs.

- **BDD (Behavior-Driven Development):**
  - **O que é?** Escreve testes em linguagem natural (ex.: Gherkin) para descrever o comportamento esperado do sistema, envolvendo até stakeholders não técnicos.
  - **Exemplo:** "Dado que sou um usuário, quando insiro credenciais válidas, então devo acessar o sistema."
  - **Ferramentas:** Cucumber, SpecFlow.
  - **Para QA:** Facilita a comunicação com o Product Owner.

- **ATDD (Acceptance Test-Driven Development):**
  - **O que é?** Define testes de aceitação com o cliente antes do desenvolvimento, garantindo que o software atenda às expectativas.
  - **Exemplo:** Um teste de aceitação verifica se o carrinho de compras calcula o total corretamente.
  - **Vantagem:** Alinha o time com os objetivos do cliente.

- **Exploratory Testing:**
  - **O que é?** Testes baseados na experiência e criatividade do QA, sem scripts rígidos.
  - **Exemplo:** Explorar um app para encontrar falhas inesperadas, como botões que não respondem.
  - **Vantagem:** Identifica problemas que testes automatizados podem não captar.

---

### ✅ Conclusão

As metodologias ágeis transformaram o desenvolvimento de software, trazendo **flexibilidade**, **colaboração** e **entregas rápidas**. O QA desempenha um papel central, garantindo qualidade em cada Sprint e colaborando com desenvolvedores, Product Owners e outros stakeholders. Dominar testes contínuos, automação e práticas ágeis é essencial para se destacar como QA em 2025.

---

## 📚 Referências e Leitura Complementar
- [Manifesto Ágil](https://agilemanifesto.org/iso/ptbr/) – Base dos princípios ágeis.
- [Scrum Guide](https://scrumguides.org/) – Guia oficial do Scrum, atualizado em 2020.
- [Extreme Programming Explained](https://www.extremeprogramming.org/) – Livro de Kent Beck sobre XP.
- [Kanban Guide](https://kanbanguides.org/) – Guia oficial do Kanban.
- [ISTQB Foundation Level Syllabus](https://www.istqb.org/) – Certificação essencial para QAs.
- [Blog da xAI sobre DevOps](https://x.ai/devops) – Artigos sobre tendências em CI/CD e automação (acesso em 15/07/2025).

---

## 📊 Visualização de Dados: Comparação de Modelos de Desenvolvimento

Para ajudar no estudo, aqui está um gráfico comparando os modelos de desenvolvimento mencionados, com base em **flexibilidade** e **complexidade de gerenciamento**:

![Modelos de Desenvolvimento](https://github.com/fzanneti/quality-assurance-qa-experience-training/blob/main/study_material/assets/images/chart.png)

> **Explicação do Gráfico:** O radar compara três modelos em cinco critérios (1 a 10). O Cascata é menos flexível, mas fácil de gerenciar. O Scrum é altamente flexível e rápido, mas exige mais coordenação. O DevOps lidera em velocidade e escalabilidade, mas também requer maior complexidade de gerenciamento.

---

##### ✍️ Seção criada por: *Fabio Zanneti* - 🎯 **Formação Quality Assurance (QA) Experience**
[![GitHub](https://img.shields.io/badge/GitHub-fzanneti-181717?style=flat&logo=github)](https://github.com/fzanneti)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-fzanneti-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/fzanneti)