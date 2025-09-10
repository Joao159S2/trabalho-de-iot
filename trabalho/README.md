# 📘 Atividade – Ciência de Dados 

## 👥 Equipe  
- joão douglas ziviani de lima

---

##  Estrutura do Repositório  
├── results/  
│   ├── alcohol_hist.png           # Histograma da variável alcohol  
│   ├── ph_by_quality_boxplot.png  # Boxplot do pH por quality  
├── dados.ipynb        # Questão 4 – funções puras de estatística  
├── pokemon.ipynb      # Questão 5 – integração com a PokeAPI  
├── vinho.ipynb        # Questão 3 – gráficos do dataset wine_quality  
├── README.md          # Este arquivo com instruções  

---

## 🛠️ Pré-requisitos  
Antes de rodar os notebooks, instale:  

- **Python 3.9+**  
- **VS Code** com a extensão **Jupyter** habilitada  
- Pip atualizado  
- Bibliotecas necessárias:  

pip install pandas seaborn matplotlib requests jupyter

---

## ▶️ Como executar cada notebook no VS Code  

### 3 – Vinho (`vinho.ipynb`)  
- Abre o notebook `vinho.ipynb` no VS Code.  
- Execute as células.  
- O notebook gera:  
  - `results/alcohol_hist.png`  
  - `results/ph_by_quality_boxplot.png`  

---

### 4 – Dados (`dados.ipynb`)  
- Abre o notebook `dados.ipynb` no VS Code.  
- Execute as células.  
- Calcula funções **puras**: média, mediana, moda e IQR.  
- Mostra comparação com `pandas.Series.describe()`.  

---

### 5 – Pokémon (`pokemon.ipynb`)  
- Abre o notebook `pokemon.ipynb` no VS Code.  
- Execute as células.  
- Faz requisição à [PokeAPI](https://pokeapi.co/).  
- Salva os dados no arquivo `game_index_pokemon.csv` (formato UTF-8, separador `;`).  

---

## ⚠️ Tratamento de Erros (Questão 5)  
- Caso a API retorne erro HTTP (≠ 200), mensagem exibida no notebook.  
- Caso ocorra **timeout** (10s), mensagem exibida no notebook.  

---

## 🔗 Entrega  
- Os códigos estão nos notebooks `.ipynb`.  
- As imagens geradas ficam na pasta `results/`.  
- O arquivo `README.md` contém todas as instruções para reprodução.  
