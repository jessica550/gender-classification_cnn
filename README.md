
# Classificação de Gênero com CNN (Redes Neurais Convolucionais)

##### Desenvolvido por Jéssica Pereira da Silva e Rebecca Santana Santos

Este projeto utiliza Redes Neurais Convolucionais (CNN) para classificar imagens faciais em duas categorias: **Masculino** e **Feminino**. O modelo processa um conjunto de dados de imagens, realiza treinamento supervisionado e avalia o desempenho por meio de métricas relevantes, como precisão, recall e curva ROC-AUC.

---

## 1. Nome do Projeto
Classificação de Gênero com CNN

---

## 2. Descrição do Projeto
O objetivo deste projeto é implementar e avaliar o desempenho de um modelo baseado em CNN para a classificação de gênero a partir de imagens faciais. A análise considera variáveis relevantes para entender padrões visuais associados a gêneros.

O projeto aborda:
- Carregamento e preparação do conjunto de dados.
- Construção e treinamento do modelo CNN.
- Avaliação e otimização do modelo preditivo.
- Visualização e documentação detalhada do processo.

---

## 3. Estrutura dos Arquivos
- **data/photos** - Contém o conjunto de dados de imagens faciais classificadas como Masculino ou Feminino.
- **notebooks/GENDER_CLASSIFICATION_CNN.ipynb** - Notebook Jupyter com o código e análises do modelo CNN.
- **docs/relatório_final.pdf** - Documento técnico com a descrição detalhada do projeto e resultados.
- **README.md** - Este arquivo, com informações e instruções do projeto.

---

## 4. Requisitos
Certifique-se de ter as seguintes dependências instaladas antes de executar o projeto:
- Python 3.8 ou superior.
- Bibliotecas:
  - TensorFlow
  - NumPy
  - Matplotlib
  - Scikit-Learn
  - Pillow

Instale as dependências com:
```bash
pip install tensorflow numpy matplotlib scikit-learn pillow
```

---

## 5. Como Executar
1. Clone o repositório:
   ```bash
   git clone [link-do-repositorio]
   ```

2. Acesse o diretório do projeto:
   ```bash
   cd [diretorio-do-projeto]
   ```

3. Coloque o conjunto de dados na pasta `data/photos`.

4. Abra o notebook para executar o código e visualizar os resultados:
   ```bash
   notebooks/GENDER_CLASSIFICATION_CNN.ipynb
   ```

---

## 6. Tecnologias Utilizadas
- **Linguagem**: Python
- **Bibliotecas Principais**:
  - TensorFlow
  - NumPy
  - Matplotlib
  - Scikit-Learn
  - Pillow

---

## 7. Principais Métricas Utilizadas
As métricas utilizadas para avaliar o modelo incluem:
- **Accuracy** (Acurácia): Mede a proporção de predições corretas.
- **Recall e Precision**: Avaliam o desempenho para cada classe.
- **F1-Score**: Combina precisão e sensibilidade em uma única métrica.
- **ROC-AUC Curve**: Representa a relação entre taxa de verdadeiros positivos e falsos positivos.

---

## 8. Resultados
- O modelo apresentou alta acurácia no conjunto de validação e teste.
- As visualizações mostraram uma evolução consistente no treinamento.
- A curva ROC-AUC apresentou valores superiores a **0.85**, indicando boa capacidade de separação entre as classes.

---

## 9. Autores e Colaboradores
- **Jéssica Pereira da Silva** - Desenvolvedora principal e responsável pela implementação do modelo CNN e análise de dados.
- **Rebecca Santana Santos** - Colaboradora na otimização do modelo e documentação técnica.
