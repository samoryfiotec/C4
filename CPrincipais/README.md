# Principais Diagramas do C4

O modelo C4 é uma abordagem para descrever a arquitetura de software utilizando diferentes níveis de abstração. Ele é composto por quatro principais diagramas:

## 1. Diagrama de Contexto

O diagrama de contexto mostra o sistema como um todo, seus usuários (atores) e sistemas externos com os quais interage.

![Diagrama de Contexto](/out/Contexto/AplicacaoContext.png)

---

## 2. Diagrama de Container

O diagrama de container detalha os principais containers (aplicações, serviços, bancos de dados, etc.) que compõem o sistema, bem como suas interações.

![Diagrama de Container](/out/Container/AplicacaoContainer.png)

---

## 3. Diagrama de Componentes

O diagrama de componentes aprofunda-se em um container específico, mostrando os componentes internos e suas relações.

![Diagrama de Componente](/out/Component/AplicacaoComponent.png)

---

## 4. Diagrama de Código

O diagrama de código (ou de classes) mostra detalhes de implementação, como classes, interfaces e suas relações dentro de um componente.

![Diagrama de Código](/out/Codigo/AplicacaoCodigo.png)

Enfim, esses diagramas ajudam a comunicar a arquitetura de software de forma clara e estruturada, facilitando o entendimento entre equipes técnicas e não técnicas.

## Exemplo Prático

Imagine uma aplicação de gerenciamento de tarefas online:

- **Diagrama de Contexto:** Mostra o sistema de gerenciamento de tarefas interagindo com usuários (como administradores e colaboradores) e sistemas externos, como serviços de autenticação.
- **Diagrama de Container:** Detalha os principais containers, como a aplicação web, uma API backend, um banco de dados e um serviço de notificações.
- **Diagrama de Componentes:** Aprofunda, por exemplo, na API backend, mostrando componentes como controle de autenticação, gerenciamento de tarefas e envio de notificações.
- **Diagrama de Código:** Exibe as classes e interfaces dentro do componente de gerenciamento de tarefas, como `Tarefa`, `Usuario`, `RepositorioTarefas` e suas relações.

Esses diagramas permitem visualizar desde a interação geral do sistema até detalhes de implementação, facilitando o entendimento e a comunicação entre todos os envolvidos no projeto.
