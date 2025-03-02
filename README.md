# Criando um Copiloto com Fluxo de Conversa Personalizado no Microsoft Copilot Studio

O objetivo desse desafio é aprender a criar tópicos no Copilot Studio e escrever um resumo do que foi aprendido.

## Resumo

### Criação do agente

Para começar, foi criado um agente com instruções para utilizar o Microsoft Learn.

### Criação do tópico

Em seguida foi criado um tópico para gerar respostas de mensagens relacionadas à AI Builder.

Foram utilizadas as seguintes frases para acionar o gatilho:
 - Buscar informações de AI Builder
 - O que é IA Builder
 - Onde encontro informações da ferramenta de AI da Power Platform

Com isso, caso o usuário faça alguma pergunta relacionada à AI Builder, esse tópico será ativado.

### Alterações do tópico Conversation boosting

Para finalizar, foi feito alterações no tópico padrão do sistema, o Conversation boosting. Esse tópico é ativado quando o agente não consegue reconhecer a mensagem do usuário, ou quando ocorre algum erro.

Foi adicionado uma mensagem para caso esse tópico seja ativado, enviando uma mensagem com informações de contato ao usuário para que o problema possa ser resolvido.

Também foi alterado algumas configurações:
 - Desativação da opção da IA utilizar os próprios conhecimentos gerais, para que o agente utilize apenas o conteúdo da documentação do Microsoft Learn
 - Configuração do nível de moderação de conteúdo para alto
