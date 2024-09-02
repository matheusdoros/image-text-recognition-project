# image-text-recognition-project
Este projeto demonstra a utilização de técnicas de IA generativa e reconhecimento de texto para processar e analisar imagens. O objetivo principal é extrair texto de imagens utilizando modelos treinados e técnicas avançadas de aprendizado de máquina.

# Projeto de Reconhecimento de Texto em Imagens

## Introdução
Este projeto demonstra a aplicação de técnicas de IA generativa e reconhecimento de texto para processar e analisar imagens. O objetivo é extrair texto de imagens usando modelos treinados.

## Processo
1. 1. **Configuração**:
   - Utilizei [Tesseract OCR](https://github.com/tesseract-ocr/tesseract) para reconhecimento óptico de caracteres. Tesseract é uma das bibliotecas mais populares para OCR e foi escolhida devido à sua precisão e suporte para múltiplos idiomas.
   - [TensorFlow](https://www.tensorflow.org/) foi usado para treinar um modelo generativo, especificamente uma Rede Neural Convolucional (CNN), para melhorar a precisão do reconhecimento de texto nas imagens.

2. **Reconhecimento de Texto**:
   - As imagens foram processadas através do Tesseract OCR para extrair o texto contido em cada uma.
   - O modelo generativo treinado ajudou a melhorar a qualidade do reconhecimento ao gerar e refinar o texto extraído.

## Imagens e Resultados
### Imagens Originais
![Imagem Original 1](inputs/remosoul.jpg)

### Resultados
![Resultado 1](outputs/remosoul-text.jpg)

## Possibilidades Futuras
- Melhorar a precisão do modelo com mais dados de treinamento.
- Implementar técnicas de pré-processamento para melhorar a qualidade da extração de texto.
