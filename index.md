# ML/AI CoP Adversarial Attacks Tutorial

There are many types of adversarial attacks on virtually every system built by humans.  Machine learning is by no means safe from adversarial attacks.  There are many resources for learning about attack types, methods, and defenses including:

* [Wikipedia](https://en.wikipedia.org/wiki/Adversarial_machine_learning)
* [OpenAI](https://openai.com/blog/adversarial-example-research/)
* [Adversarial Robustness Toolbox](https://github.com/Trusted-AI/adversarial-robustness-toolbox)  *\*We'll use this in the tutorial!*
* [DeepMind x UCL Course](https://youtu.be/MhNcWxUs-PQ)
* [Google Scholar](scholar.google.com) for many of the original papers.

## What are adversarial attacks/examples?

Put simply, adversarial attacks are inputs to a machine learning model where the expected output seems obvious to a human, but where the model is fooled into an incorrect output.  Examples include injecting words into email to avoid spam filters, adding noise to an image, and adding noise or sounds to audio.  In this tutorial we will be concerned with adversarial attacks on simple models for computer vision.  Here are a few famous examples:

![](https://user-images.githubusercontent.com/7811157/131561314-b4f5b3bc-fd76-4887-906f-64826c6ff017.png)

Adding a small amount of noise causes the model to classify a panda as a gibbon. <sup id="a1">[1](#f1)</sup>



## Why do we care?

## Taxonomy of attacks

## Defenses

## Hands-on

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jalane76/adversarial-attacks-tutorial/blob/main/adversarial_attacks_tutorial.ipynb)

## References

<b id="f1">[1]</b> Ian J. Goodfellow, Jonathon Shlens, & Christian Szegedy. (2015). Explaining and Harnessing Adversarial Examples. [↩](#a1)
