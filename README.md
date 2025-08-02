# 🖼️ Sistema de Recomendação por Similaridade de Imagens

Este projeto implementa um sistema de recomendação baseado na similaridade visual entre imagens. A partir de uma imagem de entrada, o sistema retorna as imagens mais semelhantes dentro de um conjunto pré-definido, utilizando técnicas de aprendizado profundo e métricas de distância.

## 📌 Objetivo

Criar um sistema capaz de recomendar imagens visualmente similares, útil para aplicações como:

- E-commerces (recomendar produtos semelhantes)
- Organização de galerias de fotos
- Sistemas de busca por imagem

## ⚙️ Como Funciona

1. **Pré-processamento**: As imagens são redimensionadas e normalizadas para se adequar ao modelo VGG16.
2. **Extração de Embeddings**: Utiliza-se o VGG16 (sem a camada de classificação) para extrair vetores de características das imagens.
3. **Cálculo de Similaridade**: A similaridade entre imagens é calculada usando a distância euclidiana entre os embeddings.
4. **Recomendação**: Para uma imagem de entrada, o sistema retorna as imagens mais próximas em termos de distância vetorial.

