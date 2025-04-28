# Criando um Copiloto com Fluxo de Conversa Personalizado no Microsoft Copilot Studio

## 1. Acessar o Microsoft Copilot Studio

- Acesse: [CopilotStudio](https://copilotstudio.microsoft.com)
- Crie um agente em branco.
- Defina o idioma para Inglês.
- Preencha:
  - Nome do agente.
  - Descrição.
  - Instruções utilizando engenharia de prompt.

## 2. Customizar um Tópico

- Vá até a seção Tópicos.
- Crie um tópico em branco ou use a criação por descrição.
- Adicione frases de gatilho para ativar o fluxo de conversa desejado.
- Personalize o tópico

## 3. Personalizar Mensagens de Erro

Existem duas opções para personalizar mensagens de erro:

- **Pelo tópico "Conversational Boosting"**:
  - Configure a resposta no bloco "**All Other Conditions**".
- **Pelo tópico "Fallback"**:
  - Configure mensagens de fallback diretamente para tratar erros.

## 4. Ajustar a Qualidade das Respostas Generativas

Dentro dos tópicos que usam respostas generativas:

- Clique em Editar.
- É possível:
  - Selecionar bases de conhecimento que o agente irá consultar.
  - Permitir ou não o uso de conhecimento geral (GPT-4).
  - Inserir prompts específicos para orientar melhor a IA sobre o que buscar.
  - **Configurar o nível da IA**:
    - A base de dados utiliza uma proporção para decidir a relevância da informação.
    - Defina o valor de confiança entre 0 e 100.
    - **Escolha o nível de precisão**:
      - **High**: Mais preciso.
      - **Medium**: Médio.
      - **Low**: Menos rigoroso.
- Além da configuração por tópico, você também pode ajustar o nível geral da IA nas Configurações do Agente.
