<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=32&pause=1000&color=7dcfff&center=true&vCenter=true&width=800&lines=Eduardo+Henrique;Desenvolvedor+Backend;TypeScript+%7C+NestJS+%7C+DDD;Sistemas+em+Tempo+Real" alt="Typing SVG" />

📍 Região de Campinas, SP · Aberto a oportunidades Backend / Fullstack

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0D1117?style=for-the-badge&logo=linkedin&logoColor=7dcfff&labelColor=0D1117)](https://www.linkedin.com/in/eduardohnascimento/)
[![Email](https://img.shields.io/badge/Email-0D1117?style=for-the-badge&logo=gmail&logoColor=7dcfff&labelColor=0D1117)](mailto:duuhflow@gmail.com)
![Profile Views](https://komarev.com/ghpvc/?username=Eduhn26&style=for-the-badge&color=0D1117&labelColor=0D1117&label=Views)

</div>

---

## 💻 Sobre mim

Sou um desenvolvedor focado em backend, construindo minha transição para a área de tecnologia através de projetos reais e não apenas cursos.

Meu foco principal hoje é **TypeScript, NestJS, Clean Architecture, Domain-Driven Design, comunicação via WebSockets, testes automatizados e sistemas backend onde as regras de negócio são explícitas**.

Gosto de construir projetos que me forçam a pensar sobre:

* como o domínio deve se comportar
* onde as regras de negócio devem residir
* como evitar que o frontend se torne a fonte da verdade
* como testar o comportamento do sistema sem depender do framework
* como evoluir uma arquitetura em fases, sem precisar reescrever tudo do zero

Antes da tecnologia, construí uma longa trajetória profissional em um ambiente operacional. Essa bagagem moldou a forma como encaro o desenvolvimento de software: valorizo responsabilidade, clareza, processos bem definidos e sistemas que possam ser explicados.

> Não estou tentando construir projetos perfeitos.  
> Estou tentando construir projetos que mostrem como eu penso.

---

## 🛠️ Stack Principal

<div align="center">

| Backend | Banco de Dados | Frontend | Ferramentas |
| :---: | :---: | :---: | :---: |
| ![TypeScript](https://img.shields.io/badge/TypeScript-0D1117?style=for-the-badge&logo=typescript&logoColor=3178C6) | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0D1117?style=for-the-badge&logo=postgresql&logoColor=4169E1) | ![React](https://img.shields.io/badge/React-0D1117?style=for-the-badge&logo=react&logoColor=61DAFB) | ![Docker](https://img.shields.io/badge/Docker-0D1117?style=for-the-badge&logo=docker&logoColor=2496ED) |
| ![Node.js](https://img.shields.io/badge/Node.js-0D1117?style=for-the-badge&logo=nodedotjs&logoColor=339933) | ![MongoDB](https://img.shields.io/badge/MongoDB-0D1117?style=for-the-badge&logo=mongodb&logoColor=47A248) | ![Vite](https://img.shields.io/badge/Vite-0D1117?style=for-the-badge&logo=vite&logoColor=646CFF) | ![Jest](https://img.shields.io/badge/Jest-0D1117?style=for-the-badge&logo=jest&logoColor=C21325) |
| ![NestJS](https://img.shields.io/badge/NestJS-0D1117?style=for-the-badge&logo=nestjs&logoColor=E0234E) | ![Prisma](https://img.shields.io/badge/Prisma-0D1117?style=for-the-badge&logo=prisma&logoColor=white) | | ![Linux](https://img.shields.io/badge/Linux-0D1117?style=for-the-badge&logo=linux&logoColor=FCC624) |
| ![Express](https://img.shields.io/badge/Express-0D1117?style=for-the-badge&logo=express&logoColor=white) | | | ![Socket.IO](https://img.shields.io/badge/Socket.IO-0D1117?style=for-the-badge&logo=socketdotio&logoColor=white) |

</div>

---

## 🚀 Projetos em Destaque

### ♠️ [Truco Paulista](https://github.com/Eduhn26/Truco-Paulista2026)

Um projeto multiplayer em tempo real de Truco Paulista, construído como um estudo incremental focado na arquitetura de backend.

O projeto começou como uma prática de arquitetura, mas evoluiu para um ciclo de produto completo com autenticação, sistema de ranqueamento, histórico/replays, bots, modos 1v1 e 2v2, um frontend em React e uma experiência de partida polida.

**O que pratiquei a fundo aqui:**

* Domain-Driven Design com uma camada de domínio pura
* Definição de limites de aplicação no NestJS
* Orquestração de eventos WebSocket utilizando Socket.IO
* Persistência de dados em PostgreSQL utilizando Prisma
* Autenticação OAuth via Google/GitHub
* Projeção de estado de partida (dados públicos vs. privados)
* Arquitetura de decisão de bots operando atrás de *ports* da aplicação
* Interação de bots e sinais entre parceiros no modo 2v2
* Cobertura de testes com Jest nas camadas de domínio, aplicação, gateways e infraestrutura

**Por que este projeto é importante para mim:**

O Truco não é um problema simples de CRUD. Ele envolve turnos, equipes, informações ocultas, sistema de pontuação, ciclo de vida das mãos, hierarquia de cartas, escalada de apostas, inteligência artificial (bots) e gerenciamento de estado em tempo real. Isso o tornou o cenário ideal para testar como uma arquitetura de backend se comporta sob pressão.

`TypeScript` `NestJS` `PostgreSQL` `Prisma` `Socket.IO` `React` `Docker` `Jest`

🔗 [Live API](https://truco-paulista-backend.onrender.com/health/live)

---

### 🚗 [Agendamento de Frota de Veículos](https://github.com/Eduhn26/Fleet-Vehicle-Scheduling)

Um sistema de agendamento de veículos focado em regras de reserva, fluxos de aprovação e organização do backend. Este projeto me ajudou a praticar a modelagem de regras de negócio em um contexto mais corporativo/sistemas internos.

**Pontos principais:**

* Validação de conflitos de reserva
* Fluxo de aprovação para administradores
* Controle de acesso baseado em funções (RBAC)
* Regras de disponibilidade de frota
* Gatilhos baseados em quilometragem e manutenção
* Organização em camada de serviços (*Service Layer*)
* Persistência em MongoDB

`Node.js` `Express` `MongoDB` `React` `Jest` `Docker`

---

## 🧠 O que estou aprimorando

| Foco | Por que é importante para mim |
| :--- | :--- |
| **TypeScript Strict Mode** | Para utilizar o sistema de tipagem como parte do design da aplicação, não apenas para evitar erros. |
| **Arquitetura NestJS** | Para organizar as responsabilidades do backend com fronteiras mais claras. |
| **Domain-Driven Design** | Para modelar comportamentos em vez de espalhar regras de negócio pelos *controllers*. |
| **Testes Automatizados** | Para validar decisões arquiteturais e proteger o sistema durante refatorações. |
| **Sistemas em Tempo Real** | Para aprofundar o entendimento sobre sincronização de estado, eventos e fluxos multiplayer. |
| **Python / Dados / IA** | Para expandir minha base de backend em direção à automação, análise de dados e sistemas integrados com IA. |

---

## ⚙️ Como gosto de construir

* Começar simples, mas sem ignorar a arquitetura.
* Manter as regras de negócio isoladas e próximas ao domínio.
* Evitar sobrecarregar os *controllers* com lógica.
* Usar testes como documentação de comportamento.
* Refatorar apenas quando o sistema já demonstrou essa necessidade.
* Preferir entregas em pequenas fases ao invés de grandes reescritas.
* Tomar decisões técnicas que eu consiga defender e explicar no futuro.

---

## 📊 Estatísticas do GitHub

<div align="center">

<img height="165em" src="https://github-readme-stats.vercel.app/api?username=Eduhn26&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=7dcfff&icon_color=7dcfff&hide=issues&count_private=true"/>
<img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Eduhn26&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=7dcfff"/>

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com?user=Eduhn26&theme=tokyonight&hide_border=true&background=0D1117&ring=7dcfff&fire=7dcfff&currStreakLabel=7dcfff"/>

</div>
