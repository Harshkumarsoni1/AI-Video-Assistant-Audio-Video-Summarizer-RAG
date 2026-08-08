# AI-Video-Assistant-Audio-Video-Summarizer-RAG
Built an end-to-end pipeline that ingests a YouTube URL or local audio/video file, then transcribes it via local Whisper (English) or the Sarvam
AI speech-to-text-translate API (Hinglish).

● Implemented map-reduce summarization and structured extraction (action items, decisions, open questions) via Mistral LLM chains, plus a
ChromaDB RAG mode for transcript Q&A, in a custom Streamlit UI.

● Tech: Python, Whisper, Sarvam AI API, LangChain, Mistral AI, ChromaDB, HuggingFace Embeddings, yt-dlp, Streamlit.

![Uploading ChatGPT Image Aug 8, 2026, 02_48_38 PM.png…]()
