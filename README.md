# AI-Study-Notes-Quiz-Generator
A Streamlit app that creates reusable prompts for study summaries, MCQs, flashcards, and revision packs from user-provided learning material.

Features


Summary, quiz, flashcard, and mixed-revision modes

Choose learner level, difficulty, language, and question count

Optional answer key and explanations

Download generated prompts as text files

Instructions to avoid inventing facts beyond the source material


Tech Stack

Python, Streamlit, prompt engineering.


Setup

pip install -r requirements.txt
streamlit run app.py

Limitations

This version builds prompts; it does not call an AI model or independently verify generated answers. Check AI-generated study material against class notes and trusted sources.


Future Improvements


Optional LLM API integration

Export quizzes to CSV/PDF

Track quiz attempts and scores

Automated prompt tests
