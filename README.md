# São três opções de criação de agentes:

## Template de agente pronto
Apesar de ser um Template pronto ele te permite determinadas configurações que serão assimiladas com I.A  
- Descrição do agente  
- instruções para tomada de decisões  
- gestão das fontes de conhecimento.  

Agente criado a partir de Template herdará o método de orquestração definido no Template.

## Baseado em descrição com I.A
- Não há template, a I.A precisará de maiores treinamentos para obter a mesma desenvoltura de um Agente pronto com conjunto de instruções já pré-definidas.  
- É um copilot que irá entender o seu prompt para criar um Agente com base na instrução dada.

## Em branco, totalmente do zero
- A Microsoft tem duas formas de configuração: estilo conversa ou por um painel de configuração. Assim como os outros, você será apoiado pelo copilot.  
- Não há configurações a serem herdadas de nenhum template, você precisará treinar seu agente.  
- Não é recomendado escolher fonte de conhecimento agora.  
- Aguarde a arquitetura estar pronta para que possa aproveitar melhor as possibilidades.

---

Os agentes são locais e dependem do desenvolvedor liberá-los em outros ambientes.  
Os agentes apresentam diversas ferramentas para controlar a estrutura do copilot: Visão geral, Conhecimento, Tópicos, Ações, Atividade, Análise e Canais.

### Visão geral
Exibe os detalhes como Nome, descrição, instruções gerais, orquestração.  
- Um ponto importante é a orquestração guiada por I.A generativa ser ligada ou desligada. Cada uso tem uma finalidade, é importante averiguar o caso.  
  - Orquestração generativa: I.A escolhe as melhores ações, conhecimento e tópicos.  
  - Orquestração clássica: Baseada em gatilhos e frases-chave.

### Tópicos
Permite adicionar ponto-chave na conversa para guiar a maneira que o agente responde no chat.

### Conhecimento
Gerencia os recursos de informação do Agente. Aqui podemos habilitar pesquisa na Web.

### Ações
Permite capacitar a I.A para concluir tarefas específicas. Pense em automação.

### Gatilhos
É a aba que nos permite decidir quais eventos específicos irão ativar o agente. Ele nos permite estruturar a lógica da resposta.  
- Quando a orquestração generativa está ativada, os gatilhos podem ser ativados por contexto da conversa.

---

### Agente publicado
Um agente publicado é a disponibilização para uso em canais da Microsoft, sites ou aplicativos, podendo ser integrado.  
- Algumas ações e integrações só funcionam quando o agente é publicado.  
- Se permitido, um agente pode responder usuários fora do ambiente de desenvolvimento.

---

Você pode reaproveitar suas soluções em outros agentes, reaproveitando toda arquitetura de agentes diferentes.
