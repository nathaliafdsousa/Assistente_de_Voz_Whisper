 🎙️ Assistente de Voz Multi-Idiomas com Whisper + OpenAI

Este projeto é um **assistente de voz multi-idiomas** que:
- Grava sua fala diretamente pelo navegador (via JavaScript + Colab).
- Transcreve o áudio usando o modelo **Whisper**.
- Traduz o texto para outro idioma.
- Envia a transcrição para a **API da OpenAI** para gerar respostas inteligentes.
- Converte a resposta em áudio com **gTTS** (Google Text-to-Speech).

---

 🚀 Funcionalidades
- 🎤 Captura de áudio no navegador.
- 📝 Transcrição automática com Whisper.
- 🌍 Tradução para múltiplos idiomas.
- 🤖 Integração com ChatGPT (API da OpenAI).
- 🔊 Resposta falada com gTTS.

---

 📦 Como testar

1. Abra o notebook `.ipynb` no **Google Colab** ou no **VS Code/Jupyter**.
2. Instale as bibliotecas necessárias:
   ```bash
   pip install openai
   pip install git+https://github.com/openai/whisper.git
   pip install gtts
3. Crie sua API Key da OpenAi em: https://platform.openai.com
