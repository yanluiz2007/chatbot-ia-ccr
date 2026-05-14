# Chatbot Inteligente CCR

## Descrição do Projeto

Este projeto apresenta o desenvolvimento de um chatbot inteligente voltado para suporte operacional e atendimento automatizado, utilizando Inteligência Artificial integrada com system prompts e processamento contextual.

A solução foi criada com o objetivo de otimizar a comunicação entre usuários e sistemas operacionais, permitindo respostas mais rápidas, organizadas e personalizadas conforme o perfil identificado durante a interação.

---

# Objetivo

O sistema recebe mensagens dos usuários, interpreta a intenção da solicitação, identifica automaticamente a persona responsável e gera respostas inteligentes com base em contexto operacional e dados em tempo real.

O projeto busca melhorar:

- agilidade no atendimento
- automação de processos
- organização operacional
- experiência do usuário
- precisão nas respostas

---

# Funcionamento do Sistema

O fluxo principal do chatbot ocorre da seguinte forma:

1. Usuário envia uma mensagem
2. O sistema processa e sanitiza a entrada
3. A intenção da solicitação é classificada
4. O chatbot identifica a persona responsável
5. O sistema consulta APIs e dados operacionais
6. Informações são inseridas no contexto da IA
7. A IA gera uma resposta personalizada
8. A resposta é retornada ao usuário

---

# Personas Identificadas

O chatbot realiza ramificação automática para diferentes perfis operacionais:

## Motorista EV
Responsável por informações relacionadas a:

- recarga de veículos
- status de carregadores
- preços
- rotas
- disponibilidade

## Gestor Energético
Responsável por consultas relacionadas a:

- monitoramento energético
- inversores
- peak shaving
- consumo
- dados MODBUS

## Operação Técnica
Responsável por:

- telemetria
- logs MQTT
- monitoramento técnico
- alertas operacionais
- status de comunicação

---

# Tecnologias Utilizadas

O projeto utiliza:

- Inteligência Artificial
- Claude API
- System Prompt
- HTML
- CSS
- JavaScript
- APIs externas
- MQTT
- MODBUS
- Processamento contextual

---

# Estrutura do Fluxo

O sistema foi estruturado utilizando:

- processamento de entrada
- classificação de intenção
- identificação de persona
- integração com APIs
- montagem de contexto
- geração de resposta via IA
- tratamento de exceções

---

# Diferenciais do Projeto

- Respostas contextualizadas
- Identificação automática de perfil
- Integração com dados em tempo real
- Estrutura escalável
- Arquitetura organizada
- Fluxo inteligente de atendimento

---

# Fluxograma do Sistema

O fluxograma completo do funcionamento do chatbot pode ser visualizado abaixo:

![Fluxograma](./docs/fluxograma_chatbot.png)

---

# Estrutura do Repositório

```text
/docs
    fluxograma_chatbot.png

README.md