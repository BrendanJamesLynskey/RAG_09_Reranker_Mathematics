# RAG 09 &mdash; Reranker Mathematics

Inside stage 2. Twelve slides deriving the scoring functions, training losses, and evaluation metrics behind every modern reranker. Cross-encoder architecture (where tokens meet); ColBERT late-interaction MaxSim (a strict relaxation of cross-attention); the learning-to-rank loss family (pointwise, pairwise, listwise); RankNet&apos;s sigmoid-cross-entropy and its gradient (the &ldquo;lambdas&rdquo;); LambdaRank&apos;s metric-aware reweighting by <code>|&Delta;NDCG|</code> and the LambdaMART GBDT implementation; InfoNCE for first-stage bi-encoder training (with the hard-negatives story); MarginMSE distillation of cross-encoder &rarr; bi-encoder; and formal derivations of DCG / NDCG / MRR / MAP.

Companion to [RAG 03 &mdash; Hybrid Search &amp; Reranking](https://brendanjameslynskey.github.io/RAG_03_Hybrid_Search_and_Reranking/) (operator-focused overview) and [RAG 08 &mdash; Two-Step Retrieval Architecture](https://brendanjameslynskey.github.io/RAG_08_Two_Step_Retrieval_Architecture/) (architecture &amp; cost-quality math).

**Live site:** https://brendanjameslynskey.github.io/RAG_09_Reranker_Mathematics/

Part of the [RAG &amp; Retrieval Systems sub-hub](https://github.com/BrendanJamesLynskey/LLM_Hub_RAG_Retrieval)
