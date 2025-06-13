# Customização de Agentes no Microsoft Copilot Studio

## Introdução
Os agentes do Copilot Studio permitem a customização de tópicos através de uma viewport interativa e intuitiva. Ao criar um agente em branco, podemos definir frases de gatilho ou outros métodos de ativação.

## Frases de Gatilho
As frases de gatilho são formas de ensinar ao agente, através de linguagem natural, diferentes maneiras de se referir ao tópico.

## Respostas Generativas (Tanto no Tópico quanto em config. de Ambiente)
- Por padrão, não possuem bases de conhecimento.
- Possuem permissões desabilitáveis que permitem usar o conteúdo geral da IA.

## Node de Respostas Generativas
- Requer um input, que pode ser `activity.Text` para receber o que foi digitado no node anterior.
- A função de customização modera como as respostas generativas apresentarão resultados.
- Podemos utilizar linguagem natural para configurar essa moderação.

## Limitações e Configurações
- **Prompts de customização** têm um limite de **8 mil caracteres** (o valor das variáveis chamadas no prompt também conta).
- **Nível de moderação** pode ser ajustado para **alto, médio ou baixo**, influenciando a criatividade do agente na resposta.
- O sistema é baseado em **probabilidade**, e os retornos possuem um valor termômetro que indica o quão conciso e alinhado está com o input.
- Assim, podemos configurar a **qualidade das respostas**.

## Fallback (Mensagens de Erro)
- Permite personalizar mensagens de erro, como **conflito de conteúdo** ou **falta de reconhecimento**.
- Se o **Conversational Boosting** (tópico de sistema) estiver ativo, ele será acionado quando o conteúdo não for reconhecido.
- O **Fallback** lida com erros de conflito.
- Funciona como um `__end__` no Python, parametrizando falhas.

## Recomendações
- Sempre **atualize a conversa** para um teste fluído.

##Um projeto está sendo elaborado para melhorar explorar as habilidades adquiridas neste módulo.
- [Projeto Copilot Studio - BritoWB](https://github.com/britowb/CopilotStudio)
