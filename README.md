**Принцеп работы проекта:**
- Принимает фото товара (загрузка или URL)
- BLIP анализирует изображение и генерирует описание на английском
- RAG через FAISS подбирает релевантные SEO-ключи из базы знаний
- Gemini составляет продающую карточку товара на русском в формате Markdown
- Gradio UI позволяет использовать систему как мини-сайт прямо в Colab

**Источники:** BLIP(https://arxiv.org/abs/2201.12086) 
· FAISS(https://github.com/facebookresearch/faiss) 
· Sentence-Transformers(https://www.sbert.net) 
· Google GenAI SDK(https://pypi.org/project/google-genai/) 
· Gradio(https://www.gradio.app)
