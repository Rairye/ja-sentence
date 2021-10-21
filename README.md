# ja-sentence

A light-weight sentence tokenizer for Japanese.

## Installation

pip install ja-sentence

## Sample

```python
from ja_sentence.tokenizer import tokenize

paragraph_str = "えー！？くれるの？本当にいいの…？嬉しい！！"

sentence_list = tokenize(paragraph_str)

for sentence in sentence_list:
	print(sentence)
```

## Other languages

JavaScript -> https://github.com/Rairye/js-sentence-tokenizers
