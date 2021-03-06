# GANs
Repository papers and code on different GAN models.

This [[slides]](https://github.com/AdalbertoCq/GANs/blob/master/slides/GANs_Slides.pdf) are tutorial introduction for GANs covering the following topics:
* __GANs__:
  * Model.
  * Zero-Sum Game and Nash Equilibrium.
  * Optimal Point.
  * Maximum Likelihood Models vs GANs.
  * GAN Problems.
  * Evaluation.
* __Models__:
  * DCGAN.
  * WGAN/WGAN-GP.
  * SNGAN.
  * ProGAN.
  * Conditional GANs.
  * SAGAN.
  * BigGAN.

The plan is to include in the future other models and relevant papers:
 * InfoGAN
 * Unrolled GANs
 * RSGAN/RASGAN
 * Two Time-Scale Update Rule
 * StyleGAN
 * CycleGAN
 * Is Generator Conditioning Causally Related to GAN Performance?

__Papers__:

* __Original GAN__: 'Generative Adversarial Networks' Ian J. Goodfellow, Jean Pouget-Abadie, Mehdi Mirza, Bing Xu, David Warde-Farley, Sherjil Ozair, Aaron Courville, Yoshua Bengio. 2014. [[Arxiv]](https://arxiv.org/pdf/1406.2661.pdf).

* __DCGAN__: 'Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks' Alec Radford, Luke Metz, Soumith Chintala. 2016. [[Arxiv]](https://arxiv.org/abs/1511.06434). [[Code]](https://github.com/AdalbertoCq/GANs/blob/master/gans/DCGAN.py).

* __InfoGAN__: 'InfoGAN: Interpretable Representation Learning by Information Maximizing Generative Adversarial Nets' Xi Chen, Yan Duan, Rein Houthooft, John Schulman, Ilya Sutskever, Pieter Abbeel. 2016. [[Arxiv]](https://arxiv.org/abs/1606.03657). [[Code]](https://github.com/AdalbertoCq/GANs/blob/master/gans/InfoGAN.py).

* __LSGAN__: 'Least Squares Generative Adversarial Networks' Xudong Mao, Qing Li, Haoran Xie, Raymond Y.K. Lau, Zhen Wang, Stephen Paul Smolley. 2017. [[Arxiv]](https://arxiv.org/abs/1611.04076). [[Code]](https://github.com/AdalbertoCq/GANs/blob/master/gans/LSGAN.py).

* __WGAN__: 'Wassertein GAN' Martin Arjovsky, Soumith Chintala, Léon Bottou. 2017. [[Arxiv]](https://arxiv.org/abs/1701.07875). [[Code]](https://github.com/AdalbertoCq/GANs/blob/master/gans/WGAN.py).

* __WGAN-GP__: 'Improved Training of Wasserstein GANs' Ishaan Gulrajani, Faruk Ahmed, Martin Arjovsky, Vincent Dumoulin, Aaron Courville. 2017. [[Arxiv]](https://arxiv.org/abs/1704.00028). [[Code]](https://github.com/AdalbertoCq/GANs/blob/master/gans/WGAN_GP.py).

* __RSGAN & RaSGAN__: 'The relativistic discriminator: a key element missing from standard GAN' Alexia Jolicoeur-Martineau. 2018. [[Arxiv]](https://arxiv.org/abs/1807.00734). [[RaSGAN Code]](https://github.com/AdalbertoCq/GANs/blob/master/gans/RaSGAN.py). [[RaLSGAN Code]](https://github.com/AdalbertoCq/GANs/blob/master/gans/RaLSGAN.py). [[RaSGAN-GP Code]](https://github.com/AdalbertoCq/GANs/blob/master/gans/RaSGAN_GP.py).

* __Spectral Normalization GAN__: 'Spectral Normalization for Generative Adversarial Networks' Takeru Miyato, Toshiki Kataoka, Masanori Koyama, Yuichi Yoshida. 2018. [OpenReview](https://openreview.net/forum?id=B1QRgziT-). [[Code]](https://github.com/AdalbertoCq/GANs/blob/master/gans/SNGAN.py).

* __Self Attention GAN__: 'Self-Attention Generative Adversarial Networks' Han Zhang, Ian Goodfellow, Dimitris Metaxas, Augustus Odena. 2018. [[Arxiv]](https://arxiv.org/abs/1805.08318) [[Code]](https://github.com/AdalbertoCq/GANs/blob/master/gans/SAGAN.py)
