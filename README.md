# 🎙️ Assistente de Voz Multi-Idiomas com Whisper e ChatGPT

![Capa do Projeto](docs/banner.png)

---

## 🚀 Status do Projeto

![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)
![License](https://img.shields.io/badge/license-MIT-green)
![Version](https://img.shields.io/badge/version-1.0.0-blue)

---

## 📌 Descrição

Este projeto consiste em um **assistente de voz multi-idiomas** desenvolvido utilizando **Whisper (OpenAI)** para reconhecimento de fala e **ChatGPT** para processamento de linguagem natural e geração de respostas.

A aplicação permite que o usuário interaja por voz, realizando transcrição automática, interpretação do conteúdo e geração de respostas inteligentes, com suporte a múltiplos idiomas.

O projeto foi estruturado com foco em **aprendizado prático de IA aplicada**, integração de APIs e construção de pipelines de processamento de áudio.

---

## 🎥 Demonstração

> Execução disponível via Google Colab  
> Link: https://colab.research.google.com/drive/1rHGq5N-sbEGtZsNUiQFT8q60BhRbj99b

Fluxo da aplicação:

1. Captura de áudio do usuário  
2. Transcrição com Whisper  
3. Envio do texto para o ChatGPT  
4. Geração de resposta  
5. (Opcional) Conversão para áudio  

---

## 💡 Destaques Técnicos

- Integração prática com APIs de IA (Speech-to-Text + NLP)
- Pipeline completo de processamento de voz
- Aplicação funcional em ambiente **Google Colab**
- Manipulação de áudio em tempo real
- Arquitetura simples e didática (ideal para aprendizado)
- Uso de modelos modernos de IA (Whisper + GPT)

---

## 🧠 Organização do Código

O projeto segue uma organização simples e funcional, adequada para experimentação em ambiente Colab:

- Separação lógica entre etapas:
  - Captura de áudio
  - Transcrição
  - Processamento com IA
  - Resposta
- Código estruturado em células independentes
- Fluxo linear e fácil de entender

---

## 🧩 Boas Práticas Aplicadas

- Separação de responsabilidades por etapa do pipeline
- Uso de funções reutilizáveis
- Comentários explicativos para aprendizado
- Uso de variáveis configuráveis (API Keys, idioma, etc.)
- Estrutura pensada para fácil expansão

---

## ⚙️ Funcionalidades Principais

- Captura de áudio do usuário  
- Transcrição automática com Whisper  
- Suporte a múltiplos idiomas  
- Integração com ChatGPT para respostas inteligentes  
- Pipeline completo de voz → texto → resposta  
- Execução via Google Colab (sem necessidade de setup local complexo)  

---

## 🛠️ Tecnologias Utilizadas

- Python
- OpenAI Whisper
- OpenAI ChatGPT API
- Google Colab
- Bibliotecas de áudio (como `pydub`, `sounddevice` ou similares)
- Manipulação de arquivos `.wav` / `.mp3`
