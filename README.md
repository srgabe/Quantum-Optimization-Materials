# 🌌 Quantum Intelligence: From Materials Science to Combinatorial Optimization

PhD Journey @ UFU | Physics • Quantum Computing • Artificial Intelligence

Este repositório consolida uma trajetória de pesquisa e desenvolvimento aplicada à Computação Quântica, explorando desde a simulação de matéria condensada até a resolução de problemas complexos de logística e finanças em hardware ruidoso (NISQ).

## 🏗️ 1. Otimização Combinatória (Algoritmo QAOA)
Implementação do Quantum Approximate Optimization Algorithm (QAOA) para a resolução do problema de Max-Cut, aplicado ao agrupamento de ativos e logística de redes.

Destaque Técnico: Mapeamento de problemas de decisão em Hamiltonianos de Ising.

Métrica de Sucesso: Identificação de partições ótimas em grafos, demonstrando o funcionamento da interferência quântica na busca por mínimos globais.

<img width="660" height="522" alt="image" src="https://github.com/user-attachments/assets/0a6dd097-44ec-4d14-842e-d4e4201c0227" />

Figura 1: Grafo bipartido otimizado via QAOA, separando nós em comunidades de máxima conectividade.

## 🔬 2. Engenharia de Robustez e Benchmarking
Uma análise profunda sobre o comportamento de algoritmos quânticos variacionais em condições reais de hardware.

Stress Test: Comparação sistemática entre o Simulador Ideal e um Hardware Realista (NISQ) com modelo de ruído de despolarização (2%).

Insight de Escalabilidade: O benchmark revelou o "ponto de saturação", onde o acúmulo de erro de porta supera o ganho de precisão algorítmica conforme a profundidade do circuito aumenta.

<img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/02b7bc97-170e-4439-9d15-b43a7be58ef9" />

Figura 2: Gráfico de Benchmarking comparando a convergência teórica ideal vs. a degradação por ruído térmico e decoerência.

## ⚛️ 3. Simulação de Materiais (Modelo de Hubbard)
Aplicação de computação quântica na Física da Matéria Condensada para o estudo do Grafeno.

Fenômeno: Simulação da Transição de Mott (Metal-Isolante).

Técnica: Utilização do algoritmo VQE (Variational Quantum Eigensolver) e mapeamento de Jordan-Wigner para tratar a estatística fermiônica de elétrons correlacionados.

<img width="861" height="553" alt="image" src="https://github.com/user-attachments/assets/51e4e5a0-81ed-4437-b947-1253d2b03e0c" />

Figura 3: Curva de energia do estado fundamental demonstrando a transição de fase quântica em função da interação de Coulomb (U).

## 🛠️ Tecnologias e SDKs
Quantum: Qiskit 1.x, Qiskit Aer (Noise Models), Qiskit Algorithms.

Data/IA: Python, TensorFlow, DuckDB, Pandas, Scipy (Optimize).

Physics: Second Quantization, Hubbard Hamiltonian, Ising Models.
