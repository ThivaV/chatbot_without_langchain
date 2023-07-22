# Chatbot without 🦜️🔗 LangChain

> Chatbot without Langchain

## Requirments

* ```pip install pdfminer.six```
* ```pip install -U sentence-transformers```
* ```pip install text-generation```

## PDFMiner
    
[PDFMiner](https://pypi.org/project/pdfminer.six/)

Pdfminer.six is a community maintained fork of the original [PDFMiner](https://pypi.org/project/pdfminer/). It is a tool for extracting information from PDF documents. It focuses on getting and analyzing text data. Pdfminer.six extracts the text from a page directly from the sourcecode of the PDF. It can also be used to get the exact location, font or color of the text.

It is built in a modular way such that each component of pdfminer.six can be replaced easily. You can implement your own interpreter or rendering device that uses the power of pdfminer.six for other purposes than text analysis.

Check out the full documentation on [Read the Docs](https://pdfminersix.readthedocs.io/en/latest/).

## SentenceTransformers

[SentenceTransformers Documentation](https://www.sbert.net/#sentencetransformers-documentation)

SentenceTransformers is a Python framework for state-of-the-art sentence, text and image embeddings. The initial work is described in our paper [Sentence-BERT: Sentence Embeddings using Siamese BERT-Networks](https://arxiv.org/abs/1908.10084).

You can use this framework to compute sentence / text embeddings for more than 100 languages. These embeddings can then be compared e.g. with cosine-similarity to find sentences with a similar meaning. This can be useful for [semantic textual similar](https://www.sbert.net/docs/usage/semantic_textual_similarity.html), [semantic search](https://www.sbert.net/examples/applications/semantic-search/README.html), or [paraphrase mining](https://www.sbert.net/examples/applications/paraphrase-mining/README.html).

The framework is based on [PyTorch](https://pytorch.org/) and [Transformers](https://huggingface.co/docs/transformers/index) and offers a large collection of [pre-trained models](https://www.sbert.net/docs/pretrained_models.html) tuned for various tasks. Further, it is easy to [fine-tune your own models](https://www.sbert.net/docs/training/overview.html).

## Text-Generation

[text-generation 0.6.0](https://pypi.org/project/text-generation/)

Text Generation, The Hugging Face Text Generation Python library provides a convenient way of interfacing with a ```text-generation-inference``` instance running on [Hugging Face Inference Endpoints](https://huggingface.co/inference-endpoints) or on the Hugging Face Hub.