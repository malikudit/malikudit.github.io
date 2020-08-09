---
title: Lorem ipsum dolor sit amet
permalink: /notes/
layout: page
excerpt: Just messing around
comments: false
---

#### Testing Markdown

Lorem ipsum dolor sit amet

```bash
# generate corpus
def lyrics_corpus(text, column):
    text[column] = text[column].str.replace('[{}]'.format(string.punctuation), '')
    text[column] = text[column].str.lower()
    lyrics = text[column].str.cat()
    corpus = lyrics.split('\n')
    for item in range(len(corpus)):
        corpus[item] = corpus[item].rstrip()
    corpus = [item for item in corpus if item != '']
    return corpus
```
---
