# ja-sentence

A light-weight sentence tokenizer for Japanese.

## Sample

```python
from ja_sentence.tokenizer import tokenize

paragraph_str = "えー！？くれるの？本当にいいの…？嬉しい！！"

sentence_list = tokenize(input_str)

for sentence in sentence_list:
	print(sentence)
```