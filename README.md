# 🤖 ChatbotSimulator

Um simulador de chatbot desenvolvido em C# com arquitetura baseada em **State Machine**.  
Esse projeto permite testar fluxos de conversa diretamente pelo terminal, **sem depender de APIs externas como Twilio ou WhatsApp**.

Perfeito para depuração, testes offline, estudos e demonstração de arquitetura orientada a estados!

---

## 🚀 Funcionalidades

- Simula uma conversa real com o cliente via terminal
- Armazena dados em memória (sem banco de dados)
- Usa lógica real de atendimento, com transições de estado
- Permite visualizar mudanças de estado com logs no console
- Inclui mensagens coloridas para fácil distinção entre cliente e bot

---

## 🛠️ Tecnologias Utilizadas

- .NET 9 (C#)
- Programação Orientada a Objetos
- Dicionário de estados (State Machine)
- Console interativo colorido
- Repository Pattern (com versão in-memory para testes)

---

## 🧪 Como Rodar Localmente

1. Clone este repositório:

```bash
git clone https://github.com/seu-usuario/ChatbotSimulator.git
