---
layout: post
title:  "Lipizzaner development environment setup"
author: jamal
categories: [ tutorial ]
image: assets/images/tutorials/installer.png
tags: [tutorial, setup]
---

Lipizzaner source code is freely available in GitHub. Thus, to start one has just to clone the master branch.

```
git clone https://github.com/ALFA-group/lipizzaner-gan.git
```  

Then, there are two different options to setup the environment to use our framework. 
##### Conda
```
conda env create -f ./src/helper_files/environment.yml
source activate lipizzaner
```

##### Pip
```
pip install -r ./src/helper_files/requirements.txt
```