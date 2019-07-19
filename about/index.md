---
title: ''
author: Ameya Prabhu
layout: page
permalink: "/about"
dsq_thread_id:
---
Table of Contents     [About Me](#biography)     [Highlights](#highlights)     [Research](#research)    
 [Projects](#projects)     [Publications](#publications)

---

## <a name="biography" id="biography"></a>About Me

Hi! I’m Ameya, and since you're reading this: a-mae-Ya. "Ameya" is the sanskrit word "अमेय" meaning "Impossible". Just too full of energy as a baby, right? My parents went from "You're impossible" to "You're Ameya". I like to think about **the future** in general, currently intrigued by intelligent assistance (IA), economics and philosophy of science. I want to dedicate my career towards designing principled algorithms to acquire more general notions of intelligence through learning for better automating tasks and assisting humans. Serious researchers think it's cute when I talk about constitutional law or price theory. I'm nevertheless amazed by the insights offered by these fields.

Speaking of homegrounds, I aspire to the ideal of "theoretically grounded approaches should go hand-in-hand with challenging practical problems": Principled approaches can accelerate research compared to extensive hit-and-try approaches popular today. Conversely, it's important to make real-world assumptions to model computationally hard problems and side-step worst-case complexity.

The Jungian personality type of the academic me is currently INTP, dominated by Ti and Ne. Here is the [non-academic me](https://bayesianconspirator.github.io/about/) if he intrigues you more, also [a note]() about better fake frameworks.

## <a name="highlights" id="highlights"></a>Highlights

<table style="border-collapse: collapse; border: none; margin: 0px auto;" width="100%" align='left'> <tr style="border: none;"> <td style="border: none; "><h3>Education</h3></td><td style="border: none; "><h3>Experience</h3></td><td style="border: none; "><h3>Research</h3></td> <td style="border: none; "><h3>Code</h3></td> </tr> <tr> <td style="border: none; "> <img src="https://raw.githubusercontent.com/drimpossible/drimpossible.github.io/master/images/Oxford.png" height="60px" width="60px" /> <img src="https://raw.githubusercontent.com/drimpossible/drimpossible.github.io/master/images/IIITH.png" height="60px" width="60px" /> </td> <td style="border: none; "> <img src="https://raw.githubusercontent.com/drimpossible/drimpossible.github.io/master/images/IBM.png" height="60px" width="60px" /> <img src="https://raw.githubusercontent.com/drimpossible/drimpossible.github.io/master/images/Verisk.jpg" height="60px" width="60px" /></td> <td style="vertical-align: top;"><strong> <a href="http://openaccess.thecvf.com/content_ECCV_2018/papers/Ameya_Prabhu_Deep_Expander_Networks_ECCV_2018_paper.pdf"> ECCV</a><br/> <a href="https://arxiv.org/abs/1804.03867">WACV</a><br/> <a href="https://aclanthology.info/papers/C16-1234/c16-1234">COLING</a><br/><br/> </strong></td> <td style="vertical-align: top;"><strong>
<a href="https://github.com/drimpossible/Deep-Expander-Networks"><img src="https://raw.githubusercontent.com/drimpossible/drimpossible.github.io/master/images/github.png" height="15px" width="15px">Deep Expander Networks</a><br/>
<a href="https://github.com/erilyth/HybridBinaryNetworks-WACV18"><img src="https://raw.githubusercontent.com/drimpossible/drimpossible.github.io/master/images/github.png" height="15px" width="15px">Hybrid Binary Networks</a><br/>
<a href="https://github.com/drimpossible/Sub-word-LSTM"><img src="https://raw.githubusercontent.com/drimpossible/drimpossible.github.io/master/images/github.png" height="15px" width="15px">Subword-LSTM</a><br/>
</strong></td>
</tr>
</table>

## <a name="achievements" id="achievements"></a>Achievements

### 2019

* Completed my bachelors and masters in computer science at [IIIT-Hyderabad](http://www.iiit.ac.in). [**My thesis**]() focused on developing principled approaches for sparse connectivity (pruning) and methods to exploit fast-binary convolutions for building efficient but accurate deep networks.
* Got outstanding reviewer award for CVPR 2019! Here is the [reviewer guideline](/blog/life/reviewing_for_dummies/) I developed for reference.
* I'm pursuing a PhD in Machine Learning at University of Oxford, one small step towards achieving my big goal.

### 2018

* Got a yearlong residency at **Verisk HQ**, to work for the ML group of a NASDAQ 100 financial risk assessment corporation.
* I attended [**ECCV 2018**](https://eccv2018.org/). Thank you [Google](https://ai.google/research/) for providing full travel-grant!
* My research on Pruning [**Deep Expander Networks: Efficient Networks from Graph Theory**](http://openaccess.thecvf.com/content_ECCV_2018/papers/Ameya_Prabhu_Deep_Expander_Networks_ECCV_2018_paper.pdf) got accepted at ECCV 2018 (Oral). Details [here]().
* I completed a research internship at IBM Research to experience industrial research.
* I attended [**WACV 2018**](http://wacv18.wacv.net/). Thank you [CVIT](http://cvit.iiit.ac.in/) for providing full-funding!
* My research on Hybrid Binary Networks [**Hybrid Binary Networks: Optimizing for Accuracy, Efficiency and Memory**](https://arxiv.org/abs/1804.03867) got accepted at WACV 2018 (Oral). Details [here]().
* My research on Distribution-aware Binary Networks [**Distribution-Aware Binarization of Neural Networks for Sketch Recognition**](https://arxiv.org/abs/1804.02941) got accepted at WACV 2018 (Oral). Details [here]().

## <a name="publications" id="publications"> Publications

#### Deep Expander Networks, ECCV 2018 (Oral)
<details> <summary><a>Abstract</a></summary>
Efficient CNN designs like ResNets and DenseNet were proposed to improve accuracy vs efficiency trade-offs. They essentially increased the connectivity, allowing efficient information flow across layers. Inspired by these techniques, we propose to model connections between filters of a CNN using graphs which are simultaneously sparse and well connected. Sparsity results in efficiency while well connectedness can preserve the expressive power of the CNNs. We use a well-studied class of graphs from theoretical computer science that satisfies these properties known as Expander graphs. Expander graphs are used to model connections between filters in CNNs to design networks called X-Nets. We present two guarantees on the connectivity of X-Nets: Each node influences every node in a layer in logarithmic steps, and the number of paths between two sets of nodes is proportional to the product of their sizes. We also propose efficient training and inference algorithms, making it possible to train deeper and wider X-Nets effectively.
Expander based models give a 4% improvement in accuracy on MobileNet over grouped convolutions, a popular technique, which has the same sparsity but worse connectivity. X-Nets give better performance trade-offs than the original ResNet and DenseNet-BC architectures. We achieve model sizes comparable to state-of-the-art pruning techniques using our simple architecture design, without any pruning. We hope that this work motivates other approaches to utilize results from graph theory to develop efficient network architectures.
</details>
[\[PDF\]](http://openaccess.thecvf.com/content_ECCV_2018/papers/Ameya_Prabhu_Deep_Expander_Networks_ECCV_2018_paper.pdf) [\[Code\]](https://github.com/drimpossible/Deep-Expander-Networks)

---
