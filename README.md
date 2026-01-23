# TodoList API - Estudo de Caso 



Esta API REST para gerenciamento de tarefas foi desenvolvida como parte da trilha de aprendizado em Java da Rocketseat. O projeto prioriza a clareza do código e a implementação de fundamentos essenciais do Spring Boot.



## Sobre o Projeto

O sistema permite o cadastro de usuários e a organização de listas de tarefas individuais. A principal regra de negócio aplicada é o isolamento de dados: cada usuário autenticado tem acesso exclusivo às suas próprias informações, garantindo privacidade e integridade.



## Tecnologias Utilizadas

* **Linguagem:** Java 17

* **Framework:** Spring Boot 3

* **Segurança:** Spring Security (BCrypt / Basic Auth)

* **Persistência:** Spring Data JPA

* **Banco de Dados:** H2 (Banco em memória para testes)

* **Gerenciador:** Maven



## Aprendizados e Conceitos Aplicados

Como um projeto focado em estudo e prática guiada, os seguintes tópicos foram explorados:



* **Segurança:** Implementação de hashing de senhas com BCrypt para armazenamento seguro.

* **Autenticação:** Uso de filtros (Middlewares) para validação de credenciais em rotas protegidas.

* **Validação:** Lógica para impedir que tarefas sejam criadas com datas de início ou término retroativas.

* **Padronização:** Estruturação de endpoints seguindo os princípios REST e tratamento simplificado de erros.



## Como Executar

1. Clone este repositório:

   `git clone https://github.com/ggabrielisaias/todolist_rocket.git`

2. Certifique-se de ter o Java 17 e Maven instalados.

3. Execute o comando:

   `mvn spring-boot:run`





