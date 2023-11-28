# Is it Huggable?
An image classifier that tells if something's huggable or not? 

Made using [fastai](https://docs.fast.ai/).

Play with it on the [website](https://daspartho.github.io/is-it-huggable/) or on [HuggingFace Space](https://huggingface.co/spaces/daspartho/is-it-huggable).

# How it works?
A pretrained image classification model (here resnet34) is fine tuned on images of multiple examples of both categories, like for huggable, pillow photos and for not huggable, images of cactus.

For steps to make the model check the [model](https://github.com/daspartho/is-it-huggable/blob/main/model.ipynb) notebook in the repo.

# Examples
![](demo-images/plushie.png)
![](demo-images/chainsaw.png)
![](demo-images/shark.png)
![](demo-images/snowman.png)
![](demo-images/dog.png)
![](demo-images/tiger.png)
![](demo-images/cactus.png)
![](demo-images/bed.png)
![](demo-images/trex.png)
![](demo-images/knife.png)
![](demo-images/bunny.png)

# Important Notes
- Huggability is very subjective.
- The model is not looking for particular faces or characters but general features of it.
- It's just picking up on features that makes a thing huggable or vice-versa from the training data, like sharpness.

# Contributing
If you want to contribute code, just write a quick pull request and the developers will take a look at it. If you want to suggest an idea, just write an issue and the developers will check it out!
