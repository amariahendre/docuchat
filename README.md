# LangChain LLM Question-Answering Application 🤖

Welcome to the LangChain Question-Answering Application! This app allows you to ask questions about the content of your uploaded PDF, DOCX, or TXT files using OpenAI's language models (LLMs) and embeddings. Here's how you can use it:

## Getting Started
1. **OpenAI API Key**: In the sidebar, enter your OpenAI API Key. If you don't have one, you can obtain it from OpenAI. This key is required for the language model to function properly.

2. **Upload a File**: Click the "Upload a file" button to browse and select a PDF, DOCX, or TXT file that you want to analyze. Once you've selected a file, click the "Add Data" button to start processing it.

3. **Chunk Size**: Adjust the "Chunk size" parameter if needed. This parameter controls how the file is split into smaller pieces for processing. Smaller values may result in more accurate answers, but larger values may be faster. Changing the chunk size will clear the chat history.

4. **k Value**: Set the "k" parameter, which determines how many similar documents the application will search for when answering your questions. A higher value of "k" may provide more diverse answers but could also be slower.

## Asking Questions
1. Enter your question in the "Ask a question about the content of your file" text input box.

2. Press Enter to submit your question.

## Viewing Answers
- The LangChain LLM will provide an answer to your question, which will be displayed in the "LLM Answer" text area.

## Chat History
- The chat history, including your questions and the LLM's answers, is displayed in the "Chat History" text area at the bottom of the page.

## Embedding Cost
- The estimated cost of embedding the file in terms of tokens and USD is displayed after you upload a file. This cost is based on the size and complexity of the document.

## Clearing History
- You can clear the chat history at any time by clicking the "Add Data" button or changing the chunk size or "k" value.

## Important Notes
- Please make sure to keep your OpenAI API Key secure.
- The performance of the application may vary depending on the size and complexity of the uploaded document.
- The application will save and display your chat history during your session.

Enjoy using the LangChain LLM Question-Answering Application! If you encounter any issues or have feedback, please let us know.