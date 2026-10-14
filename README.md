# Gestor de Metrô - Grafos na Prática 

Um simulador interativo de redes de metrô desenvolvido como aplicação prática de Teoria dos Grafos. O projeto demonstra a criação dinâmica de nós e arestas e utiliza algoritmos de busca para resolução de rotas.

##  Contexto Acadêmico
Projeto desenvolvido como atividade prática para a matéria de Inteligência Artificial.

##  Estruturas e Algoritmos Aplicados
O jogo foi construído em HTML5 Canvas e JavaScript puro, aplicando os seguintes conceitos matemáticos:

* **Vértices (Nós):** Representam as estações de metrô.
* **Arestas (Grafos Não-Direcionados):** Representam os trilhos que conectam as estações.
* **Lista de Adjacência:** Estrutura de dados escolhida no lugar da Matriz de Adjacência por ser mais performática e consumir menos memória em grafos esparsos (onde nem todas as estações se conectam a todas).
* **Busca em Largura (BFS - Breadth-First Search):** Algoritmo utilizado pela lógica do jogo para calcular a rota dos passageiros. O BFS garante que o passageiro encontre o caminho com o *menor número de conexões* (arestas) até o seu destino.

##  Como executar
Como a aplicação é estática (Client-side puro), basta clonar este repositório e abrir o arquivo `index.html` em qualquer navegador. Nenhum servidor local ou instalação de dependências é necessário.
