# O que é k-NN?

## 📒 Descrição
Utilizei o ChatGPT para elaborar um resumo sobre um dos assuntos que estou estudando na graduação atualmente.

## 🤖 Tecnologias Utilizadas
ChatGPT

## 🧐 Processo de Criação
Elaborei um prompt que solicita um resumo sobre o assunto especificado

## 🚀 Resultados
**Resumo sobre k-NN (k-Nearest Neighbors)**

### O que é o k-NN?
O k-NN é um algoritmo simples de aprendizado supervisionado usado para problemas de classificação e regressão. Ele se baseia na ideia de que pontos de dados próximos no espaço possuem características semelhantes.

### Como funciona?
1. **Definir o valor de k**: Escolha o número de vizinhos mais próximos a serem considerados.
2. **Calcular a distância**: Meça a distância entre o ponto de consulta e todos os pontos do conjunto de dados (exemplo: distância Euclidiana).
3. **Identificar os vizinhos mais próximos**: Selecione os k pontos mais próximos ao ponto de consulta.
4. **Decidir o rótulo ou valor**:
   - **Classificação**: Atribua a classe mais comum entre os k vizinhos.
   - **Regressão**: Calcule a média dos valores dos k vizinhos.

### Exemplo prático
Imagine um problema com três classes (círculos, quadrados e triângulos). Para classificar um ponto desconhecido, identificamos os 3 vizinhos mais próximos (k=3) e atribuimos a classe majoritária entre eles.

### Vantagens
- Simplicidade e facilidade de implementação.
- Boa performance com dados bem distribuídos.

### Desvantagens
- Custo computacional elevado para grandes conjuntos de dados.
- Sensível a características irrelevantes ou desbalanceamento de classes.
