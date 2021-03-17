# How to use RISE -  a short example targetting AI Campus content

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/PeerHerholz/AI_campus_notebooks_RISE_example/HEAD)

### What's happening?

Ahoi hoi everyone,

are you working with [Jupyter Notebooks]() within your lectures to provide students/participants with a hands-on application-driven learning experience instead of  just plain static and abstract slides? That's nothing but fantastic and if we all are honest, the only way forward in the age of (attention: buzz words coming) big data and machine/deep learning. However, while [Jupyter Notebooks]() are great, they have some disadvantages concerning teaching: might be overwhelming, easy to get lost/lose track and potentially less interaction between lecturer and students/participants. So, what to do? Isn't there some sort of mixture between slides and [Jupyter Notebooks]()? Say no more, within this repository we will show you how you can use [RISE]() to turn your [Jupyter Notebooks]() into amazing interactive slideshows in just a few steps.

### What's in here?

In this repository we created a small example that shows you how you can use [RISE]() to turn a [Jupyter Notebook]() into a slidedeck and set it up in a way that you can run/explore it via the awesome [binder service](), i.e. a free service that turns your repository into a [Docker image]() which is then hosted on a [JupyterHub]() that allows to work with your [Jupyter Notebooks] or slides interactively. To get to this mysterious interactive instance, you just have to click this button: 

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/PeerHerholz/AI_campus_notebooks_RISE_example/HEAD)

To make everythin a bit more relatable to [AI Campus](), the example notebook will showcase how a [deep neural network]() can be used to predict if participants had their eyes closed or open during a [functional magnetic resonance imaging (fMRI)]() session based on the acquired 4D fMRI images. 
The files in more detail:

- [data/environment.yml]() - a text file that indicates all [python]() modules/libraries we need for the example
- [fmri_cnn_example.ipynb]() - the example jupyter notebook in "standard form"
- [fmri_cnn_example_rise.ipynb]() - the example jupyter notebook converted to a slideshow

### I have a question/How can I get help?

No biggie at all. We are happy to answer all questions you might have and help solve problems you might face when running this resource. Please just open an [issue here]() and we will get back to you asap!

### I found a :bug:

First of all: are you sure it's not a feature? JK, that's great and we would appreciate you reporting it via an [issue](). If you are up for it and want to submit a [PR]() to fix it, even better. If you don't have experience with that, no worries, we will help you to get there!
