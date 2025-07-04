YouTube Transcript Summarizer
This project uses HuggingFace’s Transformers library in Python to perform abstractive text summarization on YouTube video transcripts fetched via the YouTube Transcript API.

🔧 Tech Stack
HuggingFace Transformers

YouTube Transcript API

Python (Core scripting)

🧠 What It Does
Retrieves a video’s transcript using the YouTube API.

Applies abstractive summarization using a pretrained transformer model.

Outputs a human-like summary that’s concise and restructured — not just extracted snippets.

💡 Why This Approach?
While the problem can be solved in several ways, this implementation avoids:

Converting video to audio and using ASR (which is resource-heavy and slow for long videos).

Raw subtitle parsing, which requires additional effort to clean and restructure into coherent text.

By working directly with the YouTube transcript and applying NLP-based summarization, this solution is both efficient and lightweight.
