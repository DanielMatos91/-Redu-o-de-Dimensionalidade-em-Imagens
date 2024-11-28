# -Redução de Dimensionalidade em Imagens para usar em Redes Neurais.

Este projeto contém funções em Python para converter imagens BMP para níveis de cinza e para binarização (preto e branco) sem o uso de bibliotecas externas.

Obs.: As imagens .jpg, .jpeg e outras podem ser convertidas em sites free.

# Conversão de Imagens BMP para Níveis de Cinza e Binarização

Este projeto consiste em duas funções principais que convertem uma imagem BMP para níveis de cinza e para uma imagem binarizada (preto e branco). O código é projetado para funcionar sem o uso de bibliotecas externas de manipulação de imagens, o que significa que ele realiza operações de leitura, manipulação e escrita de arquivos BMP manualmente.

## Descrição

O código realiza a leitura de uma imagem BMP, converte-a para níveis de cinza ou binariza a imagem, e então salva a imagem convertida de volta no formato BMP. O objetivo é demonstrar como essas operações podem ser feitas manualmente sem a ajuda de bibliotecas externas como PIL ou OpenCV.

## Funcionalidades

- **Carregar Imagem BMP:** Leitura dos dados de uma imagem BMP e armazenamento em um array de pixels.
- **Converter para Níveis de Cinza:** Aplicação de uma fórmula para converter os pixels RGB para níveis de cinza.
- **Converter para Binarização:** Conversão dos pixels para preto e branco com base em um limite de intensidade.
- **Salvar Imagem BMP:** Escrita dos dados manipulados de volta em um arquivo BMP.

## Uso

### Requisitos

- Python 3.x

### Exemplos de Uso

```python
# Caminhos das imagens
caminho_imagem = '/content/rio-de-janeiro.bmp'
caminho_saida_cinza = '/content/imagem_cinza.bmp'
caminho_saida_binarizada = '/content/imagem_binarizada.bmp'
