# 🎮 LifeQuest - RPG da Vida Real (Em desenvolvimento)

Transforme sua rotina em um jogo de RPG!  
LifeQuest é uma aplicação web gamificada onde você completa missões, ganha XP e sobe de nível, como em um verdadeiro jogo de aventura — só que na vida real.

---

## 🚀 Funcionalidades

- ✅ Cadastro e autenticação de usuários
- 🧩 Criação, edição e conclusão de missões diárias
- 📈 Sistema de XP e níveis por progresso
- 🎯 Recompensas e conquistas desbloqueáveis
- 🧭 Painel de progresso com estatísticas pessoais (futuro)

---

## 🧪 Tecnologias utilizadas

| Camada      | Stack                         |
|-------------|-------------------------------|
| Backend     | Java 17, Spring Boot, Maven   |
| Banco       | MySQL (Planetscale ou H2)     |
| Frontend*   | ReactJS (planejado)           |
| Deploy      | Render.com / Railway          |

---

## 🏗️ Arquitetura

- Estrutura baseada em camadas (MVC):
  - `Controller` → entrada (API REST)
  - `Service` → regras de negócio (XP, missões, níveis)
  - `Repository` → persistência (JPA + MySQL)
  - `Model` → entidades do domínio

- Princípios SOLID aplicados em toda a estrutura
- Injeção de dependência com Spring

---

## 🧰 Como rodar localmente

```bash
# 1. Clone o repositório
git clone https://github.com/seu-usuario/lifequest.git
cd lifequest

# 2. Rode com Spring Boot
./mvnw spring-boot:run
```

- O backend será iniciado em `http://localhost:8080`

---

## 📁 Estrutura de diretórios

```
lifequest/
├── controller/
├── service/
├── repository/
├── model/
├── dto/
├── config/
└── application.properties
```

---

## 🤝 Contribuição

Contribuições são bem-vindas!  
Você pode abrir uma **issue**, enviar um **pull request**, ou sugerir melhorias no sistema.

---

## 🧠 Futuro do projeto

- Modo multiplayer com ranking global
- Conexão com APIs externas (Google Calendar, Discord)
- Integração com smartwatch para rastrear hábitos físicos

---

## 📝 Licença

Este projeto está sob a licença MIT.