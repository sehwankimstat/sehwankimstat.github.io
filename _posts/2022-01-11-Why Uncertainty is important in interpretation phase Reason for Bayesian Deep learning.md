---
title: Why Uncertainty is important in interpretation phase? Reason for Bayesian Deep learning  
layout: post
post-image: "https://miro.medium.com/max/1400/1*5qCpNUKy5HxY1IkM47CPWA.png"
description: Image Credits: Cited from [Sukriti Paul's post] (https://medium.com/lean-in-women-in-tech-india/fast-and-scalable-estimation-of-uncertainty-using-bayesian-deep-learning-e312571042bb)
tags:
- Uncertainty
- Bayesian Deep Learning
---

Why have many people been enthusiastic about deep learning recently? Perhaps because deep learning models are solving things that have not been solved in the past. Neural Network models using deep learning have made great progress with image clasification, and models such as AlphaGo overshadowed the predictions that it would take a long time to build a machine that beats humans with Go. In addition, new concept models such as GANs are carrying out interesting projects.

But is deep learning model all-around? Finding areas where deep learning works well and developing new models are important, but it is also very important to find areas where deep learning does not work well and come up with measures to solve them.


---

> ... In May 2016 there was the first fatality from an assisted driving system, caused by the perception system confusing the white side of a trailer for bright sky. In a second recent example, an image classification system erroneously identified two African Americans as gorillas, raising concerns of racial discrimination. If both these algorithms were able to assign a high level of uncertainty to their erroneous predictions, then the system may have been able to make better decisions and likely avoid disaster. 


 [What Uncertainties Do We Need in Bayesian Deep Learning for Computer Vision?] 


As can be seen from the case above, the current deep learning method cannot express the uncertainty of the result value. To explain it as a more specific problem, let's think about the Regression Problem using the Neural Network.


###### Source : [`Jekyll Docs`](https://jekyllrb.com/docs/)

> ### To know more and get started with Jekyll you can click [here](https://jekyllrb.com/){:targe="_blank"}
	
# Installation
**Jekyll is a Ruby Gem that can be installed on most systems.**
### Requirements
* [Ruby](https://www.ruby-lang.org/en/downloads/){:target="_blank"} version 2.5.0 or above, including all development headers (ruby version can be checked by running ruby -v)
* [Ruby Gems](https://rubygems.org/pages/download){:target="_blank"} (which you can check by running gem -v)
* [GCC](https://gcc.gnu.org/install/){:target="_blank"} and [Make](https://www.gnu.org/software/make/){:target="_blank"}

### After Installing the Requirements you can follow these guides:
**For detailed install instructions have a look at the guide for your operating system.**
* [macOS](https://jekyllrb.com/docs/installation/macos/){:target="_blank"}
* [Ubuntu](https://jekyllrb.com/docs/installation/ubuntu/){:target="_blank"}
* [Other Linux Distros](https://jekyllrb.com/docs/installation/other-linux/){:target="_blank"}
* [Windows](https://jekyllrb.com/docs/installation/windows/){:target="_blank"}

### Creating a new Jekyll site
**We can create a new Jekyll site just by a simple command:**<br>
> # `jekyll new my-site`

Jekyll will create a new directory named as `my-site` which is customizable (i.e., you can change the name from `my-site` to anything you want for example `jekyll new brutus`).

### Changing into the Directory
**We have to go inside the directory:**<br>
> # `cd my-site`

Again, `my-site` is just a random name which is customizable.

### Building the site and making it available on a local server
> # `bundle exec jekyll serve`

### Browsing your Jekyll site
> # Browse to [`http://localhost:4000/`](http://localhost:4000/){:target="_blank"}

### References 
[1]
[2]
[3] 