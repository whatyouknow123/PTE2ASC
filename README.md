# PTE2ASC

This is a word embedding resource built by ourselves with PTE which is a semisupervised representation learning tool proposed by [Tang et al., 2015]. This tool could leverage both labeled and unlabeled data to build a large-scale heterogeneous network and use the network to train the word vectors. In our implementation, on one hand, the labeled data is collected from Amazon by [McAuley et al., 2015]. Specifically, we pick 5 domains, i.e., Books, CDs, Clothing, Electronics and Health and each review is automatically assigned with a positive category if its rating score is 4 or 5 and a negative category if its rating score is 1 or 2. On the other hand, the unlabeled data is the data from SemEval-2015 Task, as introduced above. The vocabulary size is about 1.2 million and the dimensionality of word vector is 300.

[Tang et al., 2015] Jian Tang, Meng Qu, and Qiaozhu Mei. PTE: predictive text embedding through large-scale heterogeneous text networks. In Proceedings of SIGKDD2015, pages 1165–1174, 2015.

[McAuley et al., 2015] Julian J. McAuley, Rahul Pandey, and Jure Leskovec. Inferring networks of substitutable and complementary products. In Proceedings of SIGKDD2015, pages 785–794, 2015.
