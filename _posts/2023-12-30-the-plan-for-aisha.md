---
title: The plan for Aisha
categories:
  - aisha
tags:
  - cool
  - aisha
  - ai
last_modified_at: 2023-12-30T15:26
toc: true
---

Aisha's goal is to make possible good use of private data, and serve it in human way.

## Motivation

You have many data you have collected along the years, let it be images, contacts, text documents, audio, etc. These are great, but practically useless if you do not have a good way to get what you want. Just like a book. You can read the whole thing, or you can simply go to a specific chapter in which it has your data.

Many kind of data is practically unstructured. This makes it difficult to get something out of it. AI comes to the rescue here. Algorithms can help you find the content you want in a matter of seconds.

## How is it done?

Any kind of data can be converted to a [vector embedding](https://www.pinecone.io/learn/vector-embeddings/). When you want to search for something, you can just use the similarity of this vector embedding to the vector embedding of your query. The results then gets inputted to the [LLM](https://en.wikipedia.org/wiki/Large_language_model) to be served with the general knowledge of what you want. So, for example, you ask "How to get a girlfriend?". Then LLM, that has been trained with many many knowledge, aided by the additional private data, gives an answer to it.
