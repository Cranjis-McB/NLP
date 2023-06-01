# NLP
A Deep Dive into the vast world of the Natural Language Processing.

## Courses

### 101

**Objectives**

1. Implement the Transformer Architecture as mentioned in the paper [Attention Is All You Need
](https://arxiv.org/abs/1706.03762) from Scratch in PyTorch 1.0 [[Link]](https://github.com/Cranjis-McB/NLP/blob/main/101/attention_is_all_you_need.ipynb) :white_check_mark:
2. Choose a dataset for Text Classification or other NLP task. [[Link]](https://www.kaggle.com/competitions/feedback-prize-effectiveness/data?select=train.csv) :white_check_mark:
3. Use a GOOD pretrained model such as [Huggingface BERT](https://huggingface.co/docs/transformers/model_doc/bert) or etc and train on the chosen Dataset.
4. Create a new model with lesser size from the implemented Architecture in 1. (use less number of encoder-decoder blocks/MultiAttentionHeads and Embeddings etc.)
5. Train this Model on the same dataset with same configuration. (Same Train-Validation set or Random SEED)
6. Now, use [Knowledge Distillation](https://arxiv.org/abs/1503.02531) (Pretrained BERT or other Good model (in 3) as Teacher and smaller model (in 4) as Student) to train the smaller model.
7. Compare the Performance of 3, 5, and 6 and Show the impact of Knowledge Distillation on the Accuracy (or any other Metric used for the Task).
8. Do the Similar excersise for 3-7 in [PyTorch 2.0](https://pytorch.org/get-started/pytorch-2.0/)
9. Compare the difference in Time and Accuracy for PyTorch 1.0 and 2.0.

**References**
1. [Attention Is All You Need](https://arxiv.org/abs/1706.03762)
2. [Huggingface BERT](https://huggingface.co/docs/transformers/model_doc/bert)
3. [Knowledge Distillation](https://arxiv.org/abs/1503.02531)
4. [PyTorch 2.0](https://pytorch.org/get-started/pytorch-2.0/)
5. [Feedback Prize - Predicting Effective Arguments](https://www.kaggle.com/competitions/feedback-prize-effectiveness/overview/prizes)
