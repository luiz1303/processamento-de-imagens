# Trabalho Final - Processamento de Imagens

O desafio proposto foi realizar a segmentação de imagens de rios e mares com os conhecimentos obtidos em sala de aula. Para isto, utilizou-se o dataset disponível em: <a href='https://www.kaggle.com/datasets/franciscoescobar/satellite-images-of-water-bodies'>Satellite images of water bodies</a>.

Como escolha pessoal, para segmentar as imagens foi utilizada a U-Net, uma arquitetura de Rede Neural Convolucional (CNN) reconhecida por sua ampla utilização em tarefas de segmentação para baixas quantidades de dados. A U-Net possui uma estrutura simétrica em forma de U, com um caminho de contração (downsampling) e um caminho de expansão (upsampling), que permitem capturar informações contextuais em diferentes níveis de resolução, melhorando a precisão da segmentação.

No arquivo `main.ipynb` são realizadas todas etapas necessárias, desde a leitura de arquivos e pré-processamento, até para implementação da arquitetura da CNN. Vale destacar que a implementação da U-Net não foi realizada completamente por autoria própria, baseando-se no tutorial: <a href='https://www.youtube.com/watch?v=68HR_eyzk00&list=PLZsOBAyNTZwbR08R959iCvYT3qzhxvGOE&index=3&t=51s'>Image Segmentation using U-Net - Part 2 (Defining U-Net in Python using Keras)</a>.
