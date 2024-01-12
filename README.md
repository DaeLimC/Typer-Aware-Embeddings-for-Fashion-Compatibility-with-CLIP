# Typer-Aware-Embeddings-for-Fashion-Compatibility-with-CLIP

In our study, we extend the work of Vasileva
et al. (1) in ”Learning Type-Aware Embeddings for Fashion Compatibility” by
integrating OpenAI’s CLIP as a central component for both text and image em-
beddings. This strategic replacement is premised on CLIP’s robust, pre-trained
features, which encapsulate a wide range of styles and contexts, enabling more
nuanced and accurate representations of fashion items. Additionally, we shift the
focus towards minimizing Euclidean distances in the embedding space rather than
employing the original approach of generalizing distance metrics through a fully-
connected layer. This simplification aligns with the geometric intuition of embed-
ding spaces, where distances more directly and transparently represent similarities
and dissimilarities. Our modifications have culminated in a notable improvement
in the model’s performance, enhancing the Fill In The Blank (FITB) task accuracy
and Area Under Curve (AUC) metrics by 7.6% and 5% respectively. These results
underscore the efficacy of our approach, marking a stride in the quest for advanced
fashion recommendation systems.
