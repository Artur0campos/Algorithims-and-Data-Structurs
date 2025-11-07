# 🧩 Coleção de Algoritmos (Python)

Este repositório contém implementações de algoritmos fundamentais em **Python**, com foco em **estrutura de dados** e **teoria dos grafos**.

Cada algoritmo é implementado com **código limpo** e uma **estrutura organizada** para facilitar o aprendizado.

---

## 📚 Índice

- [Sobre](#sobre)
- [Algoritmos](#algoritmos)
  - [Busca em Grafos](#busca-em-grafos)
    - [BFS – Busca em Largura](#bfs--busca-em-largura)
    - [DFS – Busca em Profundidade](#dfs--busca-em-profundidade)
    - [Dijkstra – Caminho Mínimo](#dijkstra--caminho-mínimo)
- [Como Executar](#como-executar)
- [Próximas Adições](#próximas-adições)
- [Licença](#licença)

---

## 🧾 Sobre

Este projeto serve como um **material de estudo e referência** para algoritmos amplamente usados em:
- Estruturas de Dados  
- Teoria dos Grafos  
- Inteligência Artificial  
- Busca e Caminho Mínimo  

Cada arquivo de algoritmo inclui:
- Uma explicação breve  
- Implementação em Python  
- Exemplo de execução  

---

## ⚙️ Algoritmos

### 🕸️ Busca em Grafos

#### **BFS – Busca em Largura**

**Descrição:**  
Explora todos os vizinhos de um nó antes de avançar para o próximo nível.  
Utiliza uma **fila** (estrutura FIFO).  

**Usos comuns:**  
- Encontrar o menor caminho em grafos não ponderados  
- Exploração de redes  
- Resolução de labirintos  

📄 **Arquivo:** `bfs.py`

---

#### **DFS – Busca em Profundidade**

**Descrição:**  
Segue o caminho mais profundo possível antes de retroceder (backtracking).  
Utiliza uma **pilha** ou **recursão**.  

**Usos comuns:**  
- Explorar todos os nós de um grafo  
- Resolver problemas de backtracking  
- Detectar ciclos  

📄 **Arquivo:** `dfs.py`

---

#### **Dijkstra – Caminho Mínimo**

**Descrição:**  
Calcula o **menor caminho entre um vértice de origem e todos os outros** em um grafo com pesos **não negativos**.  
Utiliza uma **fila de prioridade (min-heap)** para escolher sempre o vértice com a menor distância acumulada.  

**Usos comuns:**  
- GPS e rotas de navegação  
- Redes de computadores  
- Planejamento de caminhos em IA  

📄 **Arquivo:** `dijkstra.py`

---

## ▶️ Como Executar

Você pode executar qualquer algoritmo diretamente com **Python 3**:

```bash
python bfs.py
python dfs.py
python dijkstra.py
