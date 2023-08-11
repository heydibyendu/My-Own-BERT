# How to train a BERT model from scratch

myBERT will be a DistillBERT-like model as it has the same architechture of 6 layers and 12 heads.

myBERT will implement a byte-level byte-pair encoding tokenizer (used by GPT-2). BERT models mostly use a workpiece tokenizer. There will be no token type IDs as the segment will be separated by the separation token .

We'll use use the complete works of William Shakespeare as our dataset, train a tokenizer, train the transformer, save it, and run it with a masked language modeling examples.

Let's dive in!
