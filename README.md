# Ctrl + Livro — Sistema de Controle Bibliotecário

O **Ctrl + Livro** é uma aplicação WEB desenvolvida para o gerenciamento completo de acervos, usuários, empréstimos e devoluções. O diferencial do projeto é a integração de um **agente de Inteligência Artificial** focado na recomendação personalizada de leitura, garantindo que todas as sugestões respeitem estritamente as regras e o catálogo do estabelecimento.

---

## Funcionalidades Principais (MVP)

* **Gestão do Acervo:** Cadastro, edição, consulta de livros e controle de disponibilidade.


* **Gestão de Usuários:** Cadastro e controle de perfis (Leitores e Administradores).


* **Empréstimos e Devoluções:** Registro de movimentações e histórico.


* **Recomendação Inteligente por IA:**
* Identificação do perfil do leitor via preferências e interações.


* Agente de IA para geração de sugestões personalizadas.


* **Filtro de Diretrizes:** Validação automática que impede a exibição de livros fora do catálogo ou fora das regras da biblioteca.





---

## Tecnologias Utilizadas

* **Front-end:** HTML5, CSS3, JavaScript (Interface WEB)


* **Banco de Dados:** Firebase (Persistência de dados em tempo real)


* **Inteligência Artificial:** Algoritmo de análise de preferências e Agente de Recomendação



---

## Fluxo de Recomendação da IA

1. O usuário registra suas preferências e interações no sistema.


2. Os dados são armazenados e atualizados no **Firebase**.


3. O algoritmo identifica padrões de gosto e o Agente de IA gera candidatos a recomendação.


4. A **Camada de Diretrizes** valida se o livro pertence ao catálogo e cumpre as regras institucionais.


5. Somente sugestões 100% aprovadas são exibidas na interface.



---

## Equipe do Projeto

* **Camila Vitória de Oliveira** — *QA / Testes*

* **Darllan Jeferson Santiago Bandeira** — *Documentação*

* **Emerson Marcos Rodrigues Riofrio** — *Desenvolvimento & Banco de Dados*

* **Hanrry Aquiles G. de Magalhães** — *Planejamento & Gestão de Sprints*

* **Lislanny Silva Alves** — *UX/UI & Prototipação*


---

## Licença

Projeto desenvolvido no âmbito acadêmico para a disciplina de Fábrica de Software.
