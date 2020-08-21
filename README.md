# Practical Deep Learning for Coders
> The book and the course that teaches everything you need for modern deep learning


Welcome to *Practical Deep Learning for Coders*. This web site covers the book and the 2020 version of the course, which are designed to work closely together. If you haven't yet go the book, you can [buy it here](https://www.amazon.com/Deep-Learning-Coders-fastai-PyTorch/dp/1492045527). It's also [freely available](https://github.com/fastai/fastbook) as interactive Jupyter Notebooks; read on to learn how to access them..

## How do I get started?

If you're ready to dive in right now, here's how to get started. If you want to know more about this course, read the next sections, and then come back here.

To watch the videos, click on the *Lessons* section in the navigation sidebar. The lessons all have searchable transcripts; click "Transcript Search" in the top right panel to search for a word or phrase, and then click it to jump straight to video at the time that appears in the transcript. The videos are all captioned and also translated into Chinese (简体中文) and Spanish; while watching the video click the "CC" button to turn them on and off, and the setting button to change the language.

Each video covers a chapter from the book. The entirety of every chapter of the book is available as an interactive Jupyter Notebook. [Jupyter Notebook](https://jupyter.org/) is the most popular tool for doing data science in Python, for good reason. It is powerful, flexible, and easy to use. We think you will love it! Since the most important thing for learning deep learning is writing code and experimenting, it's important that you have a great platform for experimenting with code.

To get started with one of the recommended online platforms (currently, Colab or Gradient, both of which are free), click on one of those options in the navigation sidebar. We strongly suggest using one of the recommended online platforms for running the notebooks, and to *not* use your own computer, unless you're very experienced with Linux system adminstration and handling GPU drivers, CUDA, and so forth.

## Is this course for me?

Thank you for letting us join you on your deep learning journey, however far along that you may be! Previous fast.ai courses have been studied by hundreds of thousands of students, from all walks of life, from all parts of the world. Many students have told us about how they've become [multiple gold medal winners](https://forums.fast.ai/t/my-first-gold-medal/54237) of [international machine learning competitions](https://towardsdatascience.com/my-3-year-journey-from-zero-python-to-deep-learning-competition-master-6605c188eec7), [received offers](https://forums.fast.ai/t/how-has-your-journey-been-so-far-learners/6480/2) from top companies, and having [research](https://ui.adsabs.harvard.edu/abs/2020EGUGA..2221465A/abstract) [papers](http://www.ieomsociety.org/ieom2020/papers/37.pdf) [published](https://pubs.rsna.org/doi/abs/10.1148/ryai.2019190113?journalCode=ai).

It doesn't matter if you don't come from a technical or a mathematical background (though it's okay if you do too!); we wrote this course to make deep learning accessible to as many people as possible. The only prequisite is that you know how to code (a year of experience is enough), preferably in Python, and that you have at least followed a high school math course. The first three chapters have been explicitly written in a way that will allow executives, product managers, etc. to understand the most important things they'll need to know about deep learning -- if that's you, just skip over the code in those sections.

Deep learning is a computer technique to extract and transform data–-with use cases ranging from human speech recognition to animal imagery classification–-by using multiple layers of neural networks. A lot of people assume that you need all kinds of hard-to-find stuff to get great results with deep learning, but as you'll see in this course, those people are wrong. Here's a few thing you *absolutely don't need* to do world-class deep learning:

| Myth (don't need) | Truth
|---|---|
| Lots of math | Just high school math is sufficient
| Lots of data | We've seen record-breaking results with <50 items of data
| Lots of expensive computers | You can get what you need for state of the art work for free

Deep learning has power, flexibility, and simplicity. That's why we believe it should be applied across many disciplines. These include the social and physical sciences, the arts, medicine, finance, scientific research, and many more. Here's a list of some of the thousands of tasks in different areas at which deep learning, or methods heavily using deep learning, is now the best in the world:

- **Natural language processing (NLP)** Answering questions; speech recognition; summarizing documents; classifying documents; finding names, dates, etc. in documents; searching for articles mentioning a concept
- **Computer vision** Satellite and drone imagery interpretation (e.g., for disaster resilience); face recognition; image captioning; reading traffic signs; locating pedestrians and vehicles in autonomous vehicles
- **Medicine** Finding anomalies in radiology images, including CT, MRI, and X-ray images; counting features in pathology slides; measuring features in ultrasounds; diagnosing diabetic retinopathy
- **Biology** Folding proteins; classifying proteins; many genomics tasks, such as tumor-normal sequencing and classifying clinically actionable genetic mutations; cell classification; analyzing protein/protein interactions
- **Image generation** Colorizing images; increasing image resolution; removing noise from images; converting images to art in the style of famous artists
- **Recommendation systems** Web search; product recommendations; home page layout
- **Playing games** Chess, Go, most Atari video games, and many real-time strategy games
- **Robotics** Handling objects that are challenging to locate (e.g., transparent, shiny, lacking texture) or hard to pick up
- **Other applications** Financial and logistical forecasting, text to speech, and much more...

## Who we are

We are Sylvain Gugger and Jeremy Howard, your guides on this journey. We're the co-authors of fastai, the software that you'll be using throughout this course.

Jeremy has been using and teaching machine learning for around 30 years. He started using neural networks 25 years ago. During this time, he has led many companies and projects that have machine learning at their core, including founding the first company to focus on deep learning and medicine, Enlitic, and taking on the role of President and Chief Scientist of the world's largest machine learning community, Kaggle. He is the co-founder, along with Dr. Rachel Thomas, of fast.ai, the organization that built the course this course is based on.

Sylvain has written 10 math textbooks, covering the entire advanced French maths curriculum! He is now a researcher at Hugging Face, and was previously a researcher at fast.ai.

We care a lot about teaching. In this course, we start by showing how to use a complete, working, very usable, state-of-the-art deep learning network to solve real-world problems, using simple, expressive tools. And then we gradually dig deeper and deeper into understanding how those tools are made, and how the tools that make those tools are made, and so on… We always teaching through examples. We ensure that there is a context and a purpose that you can understand intuitively, rather than starting with algebraic symbol manipulation.

## The software you'll be using

In this course, you'll be using [PyTorch](https://pytorch.org/) and [fastai](https://docs.fast.ai).

We've completed hundreds of machine learning projects using dozens of different packages, and many different programming languages. At fast.ai, we have written courses using most of the main deep learning and machine learning packages used today. We spent over a thousand hours testing PyTorch before deciding that we would use it for future courses, software development, and research. PyTorch is now the world's fastest-growing deep learning library and is already used for most research papers at top conferences.

PyTorch works best as a low-level foundation library, providing the basic operations for higher-level functionality. The fastai library is the most popular library for adding this higher-level functionality on top of PyTorch. In this course, as we go deeper and deeper into the foundations of deep learning, we will also go deeper and deeper into the layers of fastai. This course covers version 2 of the fastai library, which is a from-scratch rewrite providing many unique features.

## What you'll learn

After finishing this course you will know:

- How to train models that achieve state-of-the-art results in:
  - Computer vision, indlucing image classification (e.g., classifying pet photos by breed), and image localization and detection (e.g., finding where the animals in an image are)
  - Natural language processing (NLP), including document classification (e.g., movie review sentiment analysis) and language modeling
  - Tabular data (e.g., sales prediction) with categorical data, continuous data, and mixed data, including time series
  - Collaborative filtering (e.g., movie recommendation)
- How to turn your models into web applications
- Why and how deep learning models work, and how to use that knowledge to improve the accuracy, speed, and reliability of your models
- The latest deep learning techniques that really matter in practice
- How to read a deep learning research paper
- How to implement deep learning algorithms from scratch
- How to think about the ethical implications of your work, to help ensure that you're making the world a better place and that your work isn't misused for harm

See the table of contents for a complete list, but to give you a taste, here are some of the techniques covered (don't worry if none of these words mean anything to you yet--you'll learn them all soon): 

- Affine functions and nonlinearities
- Parameters and activations
- Random initialization and transfer learning
- SGD, Momentum, Adam, and other optimizers
- Convolutions
- Batch normalization
- Dropout
- Data augmentation
- Weight decay
- ResNet and DenseNet architectures
- Image classification and regression
- Embeddings
- Recurrent neural networks (RNNs)
- Segmentation
- U-Net
- And much more
