Project: AI-Powered Medical Assistant (Speech-to-Reasoning RAG)

How to Run:
1. Open Google Colab (https://colab.research.google.com).
2. Upload the 'Task_3_Final.ipynb' file.
3. Upload 'medical_guide.pdf' to the folder icon in the left sidebar.
4. Select a T4 GPU runtime (Runtime > Change runtime type > T4 GPU).
5. Run all cells from top to bottom.
6. In the final cell, you can either:
   - Type a medical question in the text box.
   - Click 'Start Recording' to ask via voice.

Technical Stack:
- Model: Llama-3.2-3B-Instruct (4-bit Quantized via Unsloth)
- Transcription: OpenAI Whisper (Base)
- Vector DB: FAISS with LangChain
- Embeddings: sentence-transformers/all-MiniLM-L6-v2