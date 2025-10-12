# 🎧 Esteganografia em Áudio: Ocultando Informações com LSB

Este repositório contém uma implementação didática da técnica de Least Significant Bit (LSB) para ocultar qualquer tipo de informação (texto, imagens, ou outros arquivos) dentro de um arquivo de áudio no formato WAV.

A esteganografia LSB em áudio é um método discreto, pois as modificações são feitas nos bits menos importantes das amostras, resultando em uma alteração imperceptível ao ouvido humano.

## 💡 Conceitos Principais e Descrição dos Arquivos

| Conceito                     | Explicação                                                                                                     |
|------------------------------|-----------------------------------------------------------------------------------------------------------------|
| Esteganografia               | A arte de esconder a existência de uma comunicação.                                                            |
| LSB (Bit Menos Significativo) | O bit mais à direita de uma amostra digital (áudio, imagem). Mudar este bit causa uma alteração de valor mínima (±1), que é inaudível. |
| esteganografia.excalidraw | Diagramas criados para ilustrar os processos de ocultação e extração de informações em arquivos de áudio. |
| audio-demo.wav | O arquivo de áudio WAV original, que serve como recipiente.        
| imagem-demo                      | Imagem utilizada como informação oculta no áudio.  ||
| Payload                      | Os dados secretos (sua mensagem ou imagem) mais o cabeçalho de tamanho.  

## Tecnologias Utilizadas

[![ElevenLabs](https://img.shields.io/badge/ElevenLabs-000000?style=for-the-badge&logo=elevenlabs&logoColor=white)](https://elevenlabs.io)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org)
[![Google Colab](https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)](https://colab.research.google.com)
[![Google Imagens](https://img.shields.io/badge/Google_Imagens-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://images.google.com)

## 👨‍💻 Autor

[![Autor](https://img.shields.io/badge/Autor-João%20Pedro%20Nunes%20Oliveira-blue?style=for-the-badge&logo=github)](https://github.com/jpedrou)
