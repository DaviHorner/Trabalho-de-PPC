# Trabalho Prático da disciplina de Programação Paralela e Concorrente
## Davi Horner Hoe de Castro
### Descrição
A área de inteligência artificial (IA) está sendo bastante utilizada para geração de sistemas inteligentes, mas envolve o conhecimento de várias outras áreas e possui muitos algoritmos envolvidos. É necessário o conhecimento em estatística, computação, negócio e matemática. Exemplos de algoritmos utilizados são:

* Kmeans
* KNN
* Random Forest
* Support Vector Machines - SVM
* Apriori
* Redes Neurais Artificiais
* Algoritmos genéticos
* Naive Bayes
* PageRank

Na literatura existem várias versões sequenciais e paralelas desses algoritmos que podem ser consultadas.

Encontre um problema onde um desses algoritmos possa ser aplicado.

Em seguida, implemente uma versão paralela de um dos algoritmos acima usando uma ou mais bibliotecas de paralelização estudadas na disciplina e a linguagem de programação de sua preferência. O trabalho deverá ser submetido como um arquivo compactado, contendo o código fonte comentado e um vídeo de no máximo 5 minutos explicando como o problema foi resolvido. O arquivo deverá conter o nome e um sobrenome do aluno ("NomeSobrenome.zip"). Trabalhos que não compilam receberão nota ZERO, bem como trabalhos que sejam considerados como plágio. Deve ser adicionado no zip um arquivo README para explicar qual problema está sendo resolvido, qual o algoritmo escolhido e como funciona a compilação e a execução do programa implementado.

Exemplos de ferramentas para gravar vídeo: extensões do Chrome (Loom, Screencastify), CAMTASIA STUDIO, Movie Maker, OBS, etc.

A avaliação será realizada da seguinte forma: 60% para código implementado e 40% para vídeo de apresentação.

O trabalho deverá ser realizado individualmente.

## Trabalho

O meu trabalho é um CNN - Convolutional Neural Network (Rede Neural Convolucional), esse tipo de código usa Inteligencia Artificial para fazer análises de imagens, no caso desse trabalho é feito uma análise de uma séries de fotos de cachorros e gatos e tenta identificar corretamente as imagens e por fim apresenta a porcentagem de acertos da análise das pastas de teste,para fazer a paralelização foi criado 4 processos para acelerar o processo de treinamento e teste.

Para rodar o trabalho basta abrir o codigo no GoogleColab, e para rodar o código o atalho é  ```Ctrl+F9```, ao rodar o código é necessário indicar o arquivo ```kaggle.json``` da API do Kaggle para permitir o download direto do [dataset](https://www.kaggle.com/tongpython/cat-and-dog) depois disso é só esperar, caso esteja demorando muito é possivel mudar o valor de quantas vezes o dataset é analisado, ```Epoch = 5``` para um valor menor, mas tenha em mente que quanto menor o valor maiores as chance de entregar uma análise errada. 

## Referências

O meu trabalho foi feito usando como base o artigo do [Venkatesh Tata](https://becominghuman.ai/building-an-image-classifier-using-deep-learning-in-python-totally-from-a-beginners-perspective-be8dbaf22dd8) ou você pode olhar o código direto no [GitHub](https://github.com/venkateshtata/cnn_medium.) dele.
