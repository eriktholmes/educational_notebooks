# Educational resources

I learn by doing, by building/working to solve problems and by attempting to explain things to others. This is supposed to be a repo specifically for in depth writeups and 'from scratch' builds. I will start with ML/AI resources since that is my current interest/focus on here. 

## ML Content: the beginning of a beginners guide
1) [Basic MLP](/mlp_explained_pytorch.ipynb): A psuedo 'from scratch' notebook on MLPs. This mirrors the [micrograd](https://github.com/eriktholmes/Zero-to-hero-course/tree/main/episode-1/micrograd) documentation but with Pytorch for efficiency. Ultimately, the micrograd experimentation ended with the MNIST dataset so I figured I would write up a direct analogue of that basic setup using tensors and with somewhat thorough explanations throughout for those new to the topic. From there I wanted to dive into an MLP trained on MNIST but approached from the perspective of interpretability. That is available [HERE](https://github.com/eriktholmes/interpreting_mnist). In any case, I hope the content in this notebook is useful and/or somewhat informative!


2) [Transformer Outline](https://github.com/eriktholmes/educational_notebooks/blob/main/Transformer_outline.ipynb):  A step by step (and slightly poetic 😆) walkthrough of transformer components, based on our implementation of a mini GPT trained on Robert Frost’s poetry.
      This notebook outlines how to build a transformer from the ground up — assuning we know the bigram model and gradually introducing token embeddings, attention, residuals, MLPs, multi-headedness, and optimization techniques. Inspired by [Andrej Karpathy’s “GPT from scratch” video](https://www.youtube.com/watch?v=bZQun8Y4L2A&list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ&index=8), which trains on Shakespeare.
  > *Note: The model itself (Frosty) is small and trained on a laptop — but the architecture is scalable, and we aim for this short outline to be "pedagogically useful".*

3) ***To come:** I plan to do some similar 'bare bones' builds of CNNs ~and Transformers~ for both learning/teaching purposes.*
