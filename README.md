# Laboratórios de Modelos de Linguagem e PLN — UFCG

Este repositório contém os códigos e resoluções dos laboratórios práticos desenvolvidos para a disciplina de **Modelos de Linguagem de Grande Escala** da Universidade Federal de Campina Grande (UFCG).

---

## 📂 Conteúdo dos Laboratórios

### 1. Modelos de Linguagem N-Grama do Zero (`ngrams-from-scratch/`)
* **Descrição:** Implementação do zero (sem o uso de bibliotecas de PLN prontas como NLTK ou spaCy) de modelos de linguagem unigrama, bigrama e trigrama.
* **Principais tópicos:**
  * Limpeza, segmentação de sentenças e tokenização de textos literários (Projeto Gutenberg - *Dom Casmurro*).
  * Tratamento de vocabulário e palavras desconhecidas (`<UNK>`).
  * Estimação por Máxima Verossimilhança (MLE) e Suavização Add-k / Laplace.
  * Avaliação por **Perplexidade** em conjuntos de treino, validação e teste.
  * Interpolação linear e geração de texto estocástica no estilo Shannon.

### 2. Avaliação de Word Embeddings com Gensim (`word-embeddings-gensim/`)
* **Descrição:** Exploração, manipulação e avaliação de vetores de palavras estáticos pré-treinados (GloVe) utilizando a biblioteca Gensim.
* **Principais tópicos:**
  * Avaliação intrínseca (Analogias do Google, WordSim-353 e SimLex-999).
  * Resolução de analogias personalizadas e aritmética vetorial (3CosAdd e 3CosMul).
  * Análise de polissemia e testes de intrusos (`doesnt_match`).
  * Redução de dimensionalidade e visualização com **PCA** e **t-SNE**.
  * Quantificação e análise de viés de gênero em subespaços vetoriais de profissões.

---

## 🚀 Como Executar
1. Faça o upload do Jupyter Notebook desejado (`.ipynb`) para o **Google Colab**.
2. Execute as células sequencialmente. Dependências e arquivos de dados necessários são configurados de forma automatizada no início dos scripts.

---

## 📜 Licença
Desenvolvido para fins acadêmicos e educacionais sob a licença MIT