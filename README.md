# chatbot-using-chatgpt
Estudo da API da OpenAI para criação de um Chatbot

# Chat Teste com ChatGPT Turbo

Este é um projeto que demonstra a integração do ChatGPT Turbo da OpenAI em um aplicativo Streamlit para criar um chatbot interativo. 
O chatbot é capaz de receber perguntas do usuário e responder usando a API da OpenAI.

## Pré-requisitos

Certifique-se de ter o Python e o Streamlit instalados em sua máquina. Você pode instalar as dependências listadas no arquivo `requirements.txt`.

```bash
pip install -r requirements.txt

```
## Chave da API
Você também precisará de uma chave de API da OpenAI para usar o ChatGPT. Essa chave deve ser definida como uma variável de ambiente com o nome SENHA_OPEN_AI.
A chave é feita no site da OpenAi: https://platform.openai.com/overview 
### Caminho: faça o login > clique no ícone do canto superior esquerdo, onde está o seu perfil > View API Keys > clique no botão "create a secret key" (salve o conteúdo em algum documento txt, para que você não o perca)

## Funcionalidades

- Os usuários podem inserir suas perguntas na interface do aplicativo.
- O chatbot processa as perguntas usando a API da OpenAI para gerar respostas.
- As conversas são exibidas na tela, alternando entre as perguntas dos usuários e as respostas do chatbot.
- As conversas podem ser salvas em um documento do Word.


## Executando o Aplicativo

1. Clone este repositório em sua máquina local:

```Execute o aplicativo Streamlit:
 streamlit run nome_do_arquivo.py

```

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositor
``` 

## Uso
Na interface do aplicativo, digite uma pergunta na caixa de texto e clique no botão "Enviar pergunta".

O chatbot responderá com base na pergunta usando a API da OpenAI.

A conversa será exibida na tela, mostrando as perguntas dos usuários e as respostas do chatbot.

Se desejar, você pode salvar o histórico da conversa em um documento do Word clicando no botão "Salvar o conteúdo".
