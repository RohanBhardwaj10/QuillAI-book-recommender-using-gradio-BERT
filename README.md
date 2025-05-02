# QuillAI-book-recommender-using-gradio-BERT
📚 Book Recommender AI : A smart AI-powered app that recommends books based on your input description using a BERT-based model. 
🔗 Live Demo: https://03b9be91ecd029d836.gradio.live/  
🚀 Features
🔍 BERT-powered category classification from book descriptions.

📖 Smart recommendations based on selected or predicted category.

🖼️ Visual gallery of book covers with titles.

✅ Fallback to default image for missing thumbnails.

⚡ Built using Gradio, deployable with one line.

🧠 How It Works
User enters a book description or selects a category.

The BERT model classifies the description into a category (if "All" is selected).

A curated list of books is fetched from a dataset (pandas) matching the category.

Covers and titles are shown in a clean, scrollable gallery using Gradio's Gallery component.

🛠 Tech Stack
transformers – BERT tokenizer & classifier

pandas – Data manipulation

Gradio – Web interface & hosting

Python – Core logic


