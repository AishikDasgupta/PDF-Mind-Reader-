# 📄 PDF Mind Reader 🧠

PDF Mind Reader is a tool for querying and extracting answers from PDF documents using natural language. It allows you to load a PDF file, split it into chunks, index the contents using vector embeddings, and then query the contents using natural language questions.

## Features

- 📥 Load PDF documents
- ✂️ Split PDFs into chunks for processing  
- 🧠 Index PDF contents using OpenAI embeddings
- 💬 Query PDF contents using natural language
- 💡 Retrieve answers from PDFs

## Usage

To use PDF Mind Reader:

1. 📦 Install requirements
```
pip install -r requirements.txt
```

2. 🔐 Set your OpenAI API key
``` 
export OPENAI_API_KEY=your_key
```

3. 🚀 Run PDF Mind Reader
```
python pdf_mind_reader.py path/to/pdf.pdf 
```

4. 💭 Enter a natural language query when prompted

5. 🎉 View the extracted answer

PDF Mind Reader uses LangChain under the hood for querying the vector index of the PDF contents.

## Credits

PDF Mind Reader was created by Aishik Dasgupta. It utilizes LangChain, OpenAI embeddings, and other libraries for PDF loading and NLP capabilities.

## License 📜

PDF Mind Reader is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contribution 🤝

We welcome community contributions! To contribute:

1. 🍴 Fork the repo
2. ✨ Create a new branch
3. 🛠️ Make your improvements
4. 🧪 Test thoroughly
5. 📦 Create a pull request

Please ensure your code adheres to our coding style, is well-documented, and includes clear commit messages.

By contributing, you agree to license your contributions under the MIT License. Thank you for helping make PDF Mind Reader better! 🙌

