Some best practices that I took away from the course are the following:

- Always use transfer learning (e.g. ImageNet model) as a starting point in computer vision, but carefully choose the point in the model to add new layers.
- Try different learning rates for different layers in transfer learning for computer vision (e.g. differential learning).
- Use test time augmentation to give a model multiple chances of making a good prediction.
- First train a model with very small images, then later re-train with larger images (e.g. progress resizing of images).
- Use cyclical learning rates to quickly find a good learning rate for SGD (e.g. the learning rate finder).
    - [Cyclical Learning Rates for Training Neural Networks, 2015.](https://arxiv.org/abs/1506.01186)
- Use transfer learning for language models.
    - [Universal Language Model Fine-tuning for Text Classification, 2018.](https://arxiv.org/abs/1801.06146)
- Use of embedding layers more broadly, such as for all categorical input variables, not just words.
- Use of embedding layers for movies and users in collaborative filtering.



For deeper understanding of how PyTorch really works, you may want to check out this [official PyTorch tutorial](https://pytorch.org/tutorials/beginner/nn_tutorial.html) by Jeremy. 