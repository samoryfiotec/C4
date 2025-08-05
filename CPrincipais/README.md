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

Para ilustrar a aplicação prática do modelo C4, vamos considerar um sistema de biblioteca. No nível de contexto, identificamos os atores externos, como clientes, fornecedores e sistemas de pagamento. No nível de contêiner, identificamos os principais contêineres, como o aplicativo web, o banco de dados e os serviços de pagamento. No nível de componente, descrevemos os principais componentes dentro de cada contêiner, como o carrinho de compras, o catálogo de produtos e o processador de pagamento. Por fim, no nível de código, podemos fornecer detalhes técnicos sobre a implementação desses componentes, como as classes e métodos utilizados.

O modelo C4 nos ajuda a ter uma visão clara e estruturada da arquitetura do sistema, facilitando a comunicação entre os membros da equipe e permitindo uma melhor compreensão do sistema como um todo.