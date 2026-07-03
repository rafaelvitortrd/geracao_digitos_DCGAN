# tp2-IA

GAN para Geração de Dígitos Manuscritos (MNIST)

Este projeto implementa uma Rede Adversária Generativa (GAN) utilizando PyTorch para gerar imagens de dígitos manuscritos a partir da base de dados MNIST.

Configurações Utilizadas
Parâmetro	Valor
Batch Size	128
Latent Dimension	100
Epochs	100
Learning Rate	0.0002
Otimizador	Adam
Função de Perda	Binary Cross Entropy (BCELoss)

Execução

Instale as dependências:

pip install torch torchvision matplotlib numpy

Execute o script:

python Codigo_DCGAN.py

O dataset MNIST será baixado automaticamente na primeira execução.

Saídas Geradas

Ao final do treinamento serão gerados os seguintes arquivos:

curva_perdas.png

Gráfico contendo a evolução das perdas do Gerador e do Discriminador ao longo das épocas.

grade_resultados.png

Grade com imagens geradas em diferentes momentos do treinamento (épocas 1, 5, 20, 50 e 100), permitindo visualizar a evolução da qualidade das amostras produzidas pela GAN.
