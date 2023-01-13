# DeepLearningProject

In this project, we worked on image caption generation in Hindi language.
For this we have considered Flickr8k dataset and converted all the English captions into Hindi captions using a python script. Then by using that dataset we have trained our model.
The architecture includes an ENCODER-DECODER model in which we have used attention mechanism for assigning captions.
We have used InceptionV3 model for feature extraction for image input and we have used LonG-short-term-Memory model to predict next words in caption generation.
This model gave a bleu score of 0.594435 which is a better significant score while working with languages mainly Hindi(a regional language).
