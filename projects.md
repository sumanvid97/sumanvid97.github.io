---
layout: default
title: Projects
---

### Semi-Supervised Learning for Vision-and-Language Tasks using MixMatch
*Computer Vision under Prof. [Subhransu Maji](https://people.cs.umass.edu/~smaji/), Fall 2019* \\
[[report]](/docs/cv_report.pdf) [[code]](https://github.com/martiansideofthemoon/mixmatch_lxmert)

<img src="/images/mixmatch.png" style="width:50%; height:50%"/>

Implemented a recent semi-supervised learning approach MixMatch on the LXMERT framework, by strategically mixing-up the labeled and unlabeled multi-modal examples of a visual-language reasoning dataset, NLVR2. \\
*Original Papers: [MixMatch: A Holistic Approach to
Semi-Supervised Learning](https://papers.nips.cc/paper/8749-mixmatch-a-holistic-approach-to-semi-supervised-learning.pdf), [LXMERT: Learning Cross-Modality Encoder Representations from Transformers](https://arxiv.org/pdf/1908.07490.pdf)*


### Unsupervised Learning for Archetypal Style Analysis
*Advanced Machine Learning under Prof. [Sunita Sarawagi](https://www.cse.iitb.ac.in/~sunita/), Spring 2019* \\
[[report]](/docs/aml.pdf) [[code]](https://github.com/sumanvid97/archetypal_style_analysis)

<img src="/images/style_transfer.png" style="width:30%; height:30%"/>

Derived 32 archetypal styles from van Gogh’s 2046 artworks, implemented the universal style transfer technique. Verified the findings of the paper like quality of stylization & archetypal analysis through multiple experiments. \\
*Original Paper: [Unsupervised Learning of Artistic Styles with
Archetypal Style Analysis](https://papers.nips.cc/paper/7893-unsupervised-learning-of-artistic-styles-with-archetypal-style-analysis.pdf)*


### Single Image Super-resolution using Adversarial Training
*Deep Learning under Prof. [P. Balamurugan](http://www.ieor.iitb.ac.in/balamurugan.palaniappan), Fall 2018* \\
[[report]](/docs/dl.pdf) [[code]](https://github.com/sumanvid97/super_resolution_gan)

<img src="/images/srgan_manifold.png" style="width:40%; height:30%"/>

Implemented a GAN for image super-resolution on Pascal VOC2012, using SRResNet as the generator network. Incorporated perceptual loss along with the adversarial loss for photo-realistic super-resolved generator outputs. \\
*Original Paper: [Photo-Realistic Single Image Super-Resolution Using a Generative Adversarial
Network](http://openaccess.thecvf.com/content_cvpr_2017/papers/Ledig_Photo-Realistic_Single_Image_CVPR_2017_paper.pdf)*


### Progressive Nets for Multitask Learning  
*Reinforcement Learning under Prof. [Shivaram Kalyanakrishnan](https://www.cse.iitb.ac.in/~shivaram/), Fall 2018* \\
[[report]](/docs/fila.pdf) [[code]](https://github.com/sumanvid97/progressive_nets_for_multitask_rl)

<img src="/images/prog_nets.png" style="width:25%; height:40%"/>

Investigated the prospects of multitask learning by adding lateral connections to the A3C framework. The idea was to transfer knowledge from source task (Pong) to target task (Breakout) to improve results on target task. \\
*Original Paper: [Progressive Neural Networks](https://arxiv.org/pdf/1606.04671.pdf)*


### Flappy Bird AI 
*Introduction to Machine Learning under Prof. [Amit Sethi](https://www.ee.iitb.ac.in/~asethi/), Spring 2018* \\
[[blog]](https://medium.com/@videshsuman/using-reinforcement-learning-techniques-to-build-an-ai-bot-for-the-game-flappy-bird-30e0fd22f990) [[code]](https://github.com/sumanvid97/FlappyBird-AI)

<img src="/images/flappy.gif" style="width:25%; height:35%"/>

Trained an environment agnostic bot for the game using Q-learning & Deep Q-Network to produce a comparative analysis between the two frameworks. The DQN framework learnt significantly faster. Ensured early convergence by incorporating greedy & experience replay strategies while training. \\
*Original Paper: [Playing Atari with Deep Reinforcement Learning](https://www.cs.toronto.edu/~vmnih/docs/dqn.pdf)*


### Deep Learning for Medical Image Analysis
*Literature Review under Prof. [Amit Sethi](https://www.ee.iitb.ac.in/~asethi/), Spring 2018* \\
[[slides]](/docs/rnd2.pdf)

Conducted extensive study on deep learning methods for instance segmentation & classification of WSIs. Presented reviews on:
- CNN-based classification to [detect clinical heart failure](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0192726) from H&E stained whole-slide images 
- [CRF-based pancreas segmentation](https://www.semanticscholar.org/paper/Pancreas-Segmentation-in-MRI-Using-Graph-Based-on-Cai-Lu/0dcf1410f08af6ed336c5908f89ceb0dad5d6a29) derived from the fused result from CNNs for tissue & boundary detections.


### Analytics in Tool Condition Monitoring
*Technical Project under Prof. [Asim Tewari](https://www.me.iitb.ac.in/?q=faculty/Prof.%20Asim%20Tewari), Fall 2017* \\
[[report]](/docs/rnd1.pdf)

Predicted the wear states using SVR (R2⇠ 98.8%) on a public force/vibration dataset of a cutting tool. Analyzed the frequency domain of collected signals (from actual milling experiments) to extract the required signal lobes (corresponding to the actual cutting of the workpiece) for each of the parameterized runs. 
