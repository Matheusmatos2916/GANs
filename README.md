# Projeto de Redes GANs com Dataset MNIST

## 📒 Descrição
Este projeto utiliza Redes Adversárias Generativas (GANs) para gerar imagens de dígitos manuscritos que são visualmente semelhantes aos dígitos do dataset MNIST. O objetivo é explorar a capacidade das GANs de aprender e replicar padrões complexos em dados visuais.

## 🤖 Tecnologias Utilizadas
- **TensorFlow**: Biblioteca de código aberto para aprendizado de máquina.
- **Keras**: API de alto nível para construção e treinamento de modelos de aprendizado profundo.
- **Python**: Linguagem de programação utilizada para desenvolver o projeto.

## 🧐 Processo de Criação
1. **Escolha do Dataset**: Utilizamos o dataset MNIST, que contém imagens de dígitos manuscritos de 0 a 9.
2. **Construção do Modelo**: Desenvolvemos uma GAN com um gerador e um discriminador, ambos baseados em redes neurais convolucionais.
3. **Treinamento do Modelo**: O modelo foi treinado por 10.000 epochs, com um batch size de 64, utilizando o otimizador Adam.
4. **Avaliação dos Resultados**: Registramos e plotamos as métricas de perda e acurácia do discriminador e do gerador ao longo do tempo.

## 🚀 Resultados
Os resultados mostram que a GAN é capaz de gerar imagens de dígitos manuscritos que são visualmente semelhantes aos dígitos do dataset MNIST. Durante o treinamento, o gerador aprimorou sua capacidade de criar imagens realistas, enquanto o discriminador se tornou mais eficiente em distinguir entre imagens reais e falsas. As imagens geradas evoluíram de ruído aleatório para representações claras e definidas dos dígitos manuscritos.

As métricas de perda e acurácia ao longo do treinamento indicam uma melhora contínua na capacidade do modelo, com a perda diminuindo e a acurácia do discriminador aumentando progressivamente.

---

Esperamos que este projeto sirva como um ponto de partida para quem deseja explorar a aplicação de GANs em tarefas de geração de imagens.
