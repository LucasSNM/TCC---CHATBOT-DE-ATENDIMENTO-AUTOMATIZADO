# Chatbot Automatizado para Atendimento via WhatsApp
Este projeto foi desenvolvido como Trabalho de Conclusão de Curso (TCC) para obtenção do título de Bacharel em Sistemas de Informação pela FEPI - Centro Universitário de Itajubá, concluído em 2022.


# 🎯 Objetivo

O objetivo deste trabalho é desenvolver e testar um chatbot automatizado para atendimento de pedidos em uma lanchonete, utilizando o WhatsApp como meio de interação. Para isso, foram empregadas tecnologias da Google Cloud Platform e a API do WhatsApp, proporcionando um atendimento eficiente e automatizado.


# 🛠️ Arquitetura do Projeto

A arquitetura do projeto segue um modelo estruturado em três camadas:

📱 Interface (View): A comunicação com o usuário ocorre via WhatsApp.

⚙️ Controle (Controller): Utiliza a API do WhatsApp via Twilio, que recebe as mensagens e as encaminha para o Dialogflow, responsável pelo processamento e resposta inteligente.

💾 Modelo de Dados (Model): O Dialogflow acessa o Firebase Realtime Database sempre que necessário para buscar ou armazenar informações sobre os pedidos.

A estrutura do sistema pode ser visualizada no diagrama abaixo:

![image](https://github.com/user-attachments/assets/944ffdd6-0304-41eb-a40b-f135de9dc8dc)


# 🎬 Demonstração
Confira o vídeo abaixo para ver o chatbot em ação:

https://github.com/user-attachments/assets/452b74a4-2fff-4e5f-8373-53f53255e97e
