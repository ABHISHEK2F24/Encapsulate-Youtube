# Encapsulate Youtube
Natural Language Processing (NLP) is one of the exciting field of data science. I was wondering if we can somehow know the content of video before watching the video. Then I found about this mini project. Here we use a youtube video and using its available subtitle we can see is this video worth watching. But other problem is if video is very lengthy still it takes so much time to read the subtitles. So using NLP we can cut short the whole subtitle into small paragraph. Let's dive in.

# Technical Overview
We are using Summarization library. Summarization is the technique of making short, understandable notes for a given large text document without excluding the important contents of the passage. There are 2 types of summarization in NLP, extractive summarization and abstractive summarization.

In extractive summarization, the system will extract the important paragraphs and contents from the given passage and combine these extracted paragraphs to create the summarized text.

In abstractive summarization, the system will create a summary based on the given passage with its own words. This is more complex than extractive summarization.

For our YouTube summarizer, we are using extractive summarization. For extractive summarization, we are using different summarization techniques like using BART or Bidirectional and Auto-Regressive Transformer, using TFIDF Vectorizer, etc.
