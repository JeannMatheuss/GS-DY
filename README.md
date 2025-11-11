# 🌐 Global Solution FIAP 2025 - Engenharia de Software: Dynamic Programming

## 🧩 Descrição
Este projeto resolve os 5 desafios do PDF **"Global Solution (GS): Engenharia de Software — Dynamic Programming"**, utilizando algoritmos em **Python** para otimização de habilidades no contexto do **Futuro do Trabalho**.  
Conecta a **requalificação profissional (ONU/OIT, ODS 8/10)**, simulando **transições tecnológicas e verdes**.

---

## 👥 Equipe
- **Jean Matheus Mohamed de Oliveira** — RM555519  
- **Pedro Henrique Ribeiro Sampaio** — RM555613

---

## 🧱 Estruturas Usadas
- **Grafo direcionado ponderado:** para pré-requisitos de habilidades.  
- **Dicionários:** metadados das habilidades (tempo, valor, complexidade).  
- **Listas, heaps e conjuntos:** para caminhos, filas e validações.  
- **Algoritmos:** DP multidimensional, Monte Carlo, enumeração, guloso, Merge Sort, DP look-ahead.

---

## 🚀 Como Usar
1. **Baixe o projeto  
2. **Execute as células em ordem:** validação → desafios → figuras.  
3. **Dados de entrada:** carregue `skills_data.json`.  
4. **Resultados:** prints no console; salve em `results.txt`.

---

## ⚙️ Dependências
- **Python 3.x** (padrão no Colab)  
- Nenhuma externa necessária  
  *(matplotlib e networkx são instaladas via pip no código)*

---

## ⚡ Execução Rápida
```python
# Validar grafo
validate_graph(graph)

# Executar desafios
desafio1()
desafio2()
# ...
```

## 📂 Arquivos do Projeto

| Arquivo              | Descrição                                                      |
|----------------------|----------------------------------------------------------------|
| `main.py`            | Código principal (copie os blocos do Colab).                   |
| `skills_data.json`   | Arquivo de entrada com dados das habilidades.                  |
| `results.txt`        | Resultados dos desafios (caminhos, custos, métricas).          |
| `relatorio.pdf`      | Relatório técnico com figuras, tabelas e análises.             |
| `figura1.png`        | Figura 1 do relatório (ex.: grafo de pré-requisitos).          |
| `figura2.png`        | Figura 2 do relatório (ex.: histograma / distribuição).        |
| `notebook_colab.ipynb` | Notebook público do Colab com execução e visualizações.     |

## 📊 Resultados Principais

| Desafio | Métrica / Saída                                               |
|---------|---------------------------------------------------------------|
| Desafio 1 | `Valor Máximo = 28`  `E[V] = 28.5`  `Std = 2.1`             |
| Desafio 2 | `Top 3 custos: 410, 420, 425`                                |
| Desafio 3 | `Guloso S = 12`  `Ótimo S = 14`                              |
| Desafio 4 | `Ordenação por complexidade` — Tempos: `0.0012s` (custom), `0.0008s` (nativo) |
| Desafio 5 | `Recomendações: ['S3', 'S4', 'S8']`                          |

> Observação: números são exemplos. Verifique `results.txt` para os outputs completos e logs.

## 📚 Referências

- **PDF:** *Global Solution — Engenharia de Software: Dynamic Programming*  
- **OIT (2025):** Relatório *Futuro do Trabalho*  
- **ONU:** Objetivos de Desenvolvimento Sustentável — ODS 8 (Trabalho decente) e ODS 10 (Redução das desigualdades)  
- **Bibliotecas e utilitários usados:** `itertools`, `random`, `matplotlib`, `networkx`  
