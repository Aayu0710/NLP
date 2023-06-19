# NLP
My code contains two functions one is for summarization and another is for translation.

For summarization, I have used sumy library, which includes inbuild's functions which made my task easy.
It aims to extract the most important sentences from a document to create a concise summary.

Here are some key features and components of the Sumy library:

Summarization Algorithms: The library offers several summarization algorithms, including LexRank, LSA (Latent Semantic Analysis), Luhn, Edmundson, TextRank, and KL-Sum. Each algorithm has its own approach to identifying important sentences based on different criteria.

Document Parsing: sumy provides parsers that can handle different document formats such as plain text, HTML, or XML. These parsers preprocess the documents and split them into sentences or paragraphs for summarization.

Sentence Tokenization: The library includes tokenizers that break the text into individual sentences. Proper sentence tokenization is crucial for accurate summarization, as it ensures that each sentence is considered independently during the summarization process.

Sentence Scoring: sumy utilizes specific scoring metrics associated with each summarization algorithm to rank sentences. These metrics evaluate the relevance, centrality, or importance of each sentence within the document.

Summary Generation: The library generates a summary by selecting the top-ranked sentences based on their scores. The number of sentences to include in the summary can be specified as a parameter.

Language Support: sumy supports multiple languages, enabling text summarization for documents written in various languages.

For translation, I have used simple translater library.

