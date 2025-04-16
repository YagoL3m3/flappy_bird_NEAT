🐦 IA Jogando Flappy Bird com NEAT
Este projeto implementa uma Inteligência Artificial capaz de aprender a jogar Flappy Bird utilizando o algoritmo NEAT (NeuroEvolution of Augmenting Topologies), uma técnica evolutiva que combina algoritmos genéticos com redes neurais.

🎯 Objetivo
Desenvolver um agente autônomo que aprenda, por tentativa e erro, como vencer o Flappy Bird, sem regras pré-definidas de como jogar. A IA evolui suas decisões com base em um sistema de recompensa, melhorando a performance a cada geração.

🧠 Tecnologias e Conceitos Utilizados
Python

Pygame – Para simular o ambiente do jogo

NEAT-Python – Biblioteca que implementa o algoritmo NEAT

Algoritmos Genéticos – Para evolução da população de agentes

Redes Neurais – Estruturas adaptadas dinamicamente pelo NEAT

⚙️ Como Funciona
Cada "pássaro" no jogo é controlado por uma rede neural.

A cada geração, os pássaros jogam o Flappy Bird tentando maximizar sua pontuação.

Os melhores desempenhos são utilizados para gerar uma nova geração, com cruzamentos e mutações nas redes neurais.

Ao longo do tempo, os agentes aprendem a evitar os canos e sobreviver por mais tempo.

📈 Resultados Esperados
Após algumas gerações, a IA começa a mostrar um comportamento muito mais eficiente, conseguindo desviar dos obstáculos com precisão. O processo evolutivo permite que o agente aprenda sem intervenção humana direta.

📚 Referências
NEAT Paper

NEAT-Python Documentation
