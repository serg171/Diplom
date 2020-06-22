# Diplom
My diploma project is about label generation (summarization) task on RIA News (РИА Новости) text corpus (https://arxiv.org/abs/1901.07786).

In "RIA News corpus models" notebook I tried three models: seq2seq architecture with LSTM, transformer and reformer (https://arxiv.org/abs/2001.04451).

In "Experiments with LSH attention" I compared original transformer and transformer with LSH attention (that was suggested in reformer paper) on small part of RIA News dataset. LSH attention realization on pytorch is based on the code of the authors' paper (https://github.com/google/trax/blob/master/trax/layers/research/efficient_attention.py#L1083).
