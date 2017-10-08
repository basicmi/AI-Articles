# Interesting stuff of AI/ML/DL

## Weekly Digest 2017-10 \#2

**[A List of Chip/IP for Deep Learning (keep updating)](https://basicmi.github.io/Deep-Learning-Processor-List/)**

**1. [Real-Time Recognition of Handwritten Chinese Characters Spanning a Large Inventory of 30,000 Characters](https://machinelearning.apple.com/2017/09/12/handwriting.html)**
> Handwriting recognition can enhance user experience on mobile devices, particularly for Chinese input given the relative complexity of keyboard methods. Chinese handwriting recognition is uniquely challenging, due to the large size of the underlying character inventory. Unlike alphabet-based writing, which typically involves on the order of 100 symbols, the set of Hànzì characters in Chinese National Standard GB18030-2005 contains 27,533 entries, and many additional logographic characters are in use throughout Greater China.

**2. [The Seven Deadly Sins of Predicting the Future of AI](https://rodneybrooks.com/the-seven-deadly-sins-of-predicting-the-future-of-ai)**
> We are surrounded by hysteria about the future of Artificial Intelligence and Robotics. There is hysteria about how powerful they will become how quickly, and there is hysteria about what they will do to jobs.
> Below I outline seven ways of thinking that lead to mistaken predictions about robotics and Artificial Intelligence. We find instances of these ways of thinking in many of the predictions about our AI future. I am going to first list the four such general topic areas of such predictions that I notice, along with a brief assessment of where I think they currently stand.

**3. [STYLE2PAINTS](https://lllyasviel.github.io/)**
> The AI can paint on a sketch accroding to a given specific color style.
> The codes can be found [here](https://github.com/lllyasviel/style2paints).

**4. [Nonlinear Computation in Deep Linear Networks](https://blog.openai.com/nonlinear-computation-in-linear-networks)**
> We’ve shown that deep linear networks — as implemented using floating-point arithmetic — are not actually linear and can perform nonlinear computation. We used evolution strategies to find parameters in linear networks that exploit this trait, letting us solve non-trivial problems.
> Neural networks consist of stacks of a linear layer followed by a nonlinearity like tanh or rectified linear unit. Without the nonlinearity, consecutive linear layers would be in theory mathematically equivalent to a single linear layer. So it’s a surprise that floating point arithmetic is nonlinear enough to yield trainable deep networks.

**5. [GPUs vs. TPUs — Can NVIDIA Hold On To Its Lead?](https://ark-invest.com/research/gpu-tpu-nvidia)**
> Now that deep learning has turbocharged NVIDIA’sNVDA data center business by five-fold in the past two years, competition is brewing. As of 2017 nearly a dozen startups have launched, with the goal of building dedicated chips for deep learning applications. In addition, large public tech companies such as Alphabet, Intel, AMD, Qualcomm, and Apple plan to enter the market for deep learning chips.
> Given this intense and growing competition, can NVIDIA maintain its lead in the market for deep learning chips? And, which of the newcomers are best positioned to succeed?

**6. [Experts Weigh in on Fairness and Performance Trade-Offs in Machine Learning](https://www.theregreview.org/2017/10/04/wong-fairness-performance-machine-learning/)**
> Artificial intelligence plays an increasingly important role in informing public policy—for everything from the likelihood of an individual becoming homeless or dropping out of school can be predicted through algorithms today. But how do these algorithms generate their predictions? Are the results fair? How do we define “fair” when we balance technology and government decisions?

**7. [Google and Uber’s Best Practices for Deep Learning](https://medium.com/intuitionmachine/google-and-ubers-best-practices-for-deep-learning-58488a8899b6)**
> There is more to building a sustainable Deep Learning solution that what is provided by Deep Learning frameworks like TensorFlow and PyTorch. These frameworks are good enough for research, but they don’t take into account the problems that crop up with production deployment. I’ve written previously about technical debt and the need from more adaptive biological like architectures. To support a viable business using Deep Learning, you absolutely need an architecture that supports sustainable improvement in the presence of frequent and unexpected changes in the environment. Current Deep Learning framework only provide a single part of a complete solution.

**8. [A Brain Built From Atomic Switches Can Learn](https://www.quantamagazine.org/a-brain-built-from-atomic-switches-can-learn-20170920)**
> A tiny self-organized mesh full of artificial synapses recalls its experiences and can solve simple problems. Its inventors hope it points the way to devices that match the brain’s energy-efficient computing prowess.

**9. [Intel Gears Up For FPGA Push](https://www.nextplatform.com/2017/10/02/intel-gears-fpga-push/)**
> Chip giant Intel has been talking about CPU-FPGA compute complexes for so long that it is hard to remember sometimes that its hybrid Xeon-Arria compute unit, which puts a Xeon server chip and a midrange FPGA into a single Xeon processor socket, is not shipping as a volume product. But Intel is working to get it into the field and has given The Next Platform an update on the current plan.

**10. [Will the Future of AI Learning Depend More on Nature or Nurture?](https://spectrum.ieee.org/tech-talk/robotics/artificial-intelligence/ai-and-psychology-researchers-debate-the-future-of-deep-learning)**
> NYU's Yann LeCun and Gary Marcus debate whether or not AI needs more built-in cognitive machinery similar to that of humans and animals to achieve similar intelligence

**11. [GANs are Broken in More than One Way: The Numerics of GANs](http://www.inference.vc/my-notes-on-the-numerics-of-gans/)**
> Last year, when I was on a mission to "fix GANs" I had a tendency to focus only on what the loss function is, and completely disregard the issue of how do we actually find a minimum. Here is the paper that has finally challenged that attitude: Mescheder, Nowozin, Geiger (2017): [The Numerics of GANs](https://arxiv.org/abs/1705.10461)
> I reference [Marr's three layers of analysis](http://blog.shakirm.com/2013/04/marrs-levels-of-analysis/) a lot, and I enjoy thinking about problems at the computational level: what is the ultimate goal we do this for? I was convinced GANs were broken at this level: they were trying to optimize for the wrong thing or seek equilibria that don't exist, etc. This is why I enjoyed f-GANs, Wasserstein GANs, instance noise, etc, while being mostly dismissive of attempts to fix things at the optimization level, like DCGAN or improved techniques (Salimans et al. 2016). To my defense, in most of deep learning, the algorithmic level is sorted: stochastic gradient descent. You can improve on it, but it's not broken, it doesn't usually need fixing.
 
**[Weekly Digest Aug. 2017 \#2](https://github.com/basicmi/Machine-Learning-Articles/blob/master/WeeklyDigest2017-08_2.md)**

**[Weekly Digest Aug. 2017 \#3](https://github.com/basicmi/Machine-Learning-Articles/blob/master/WeeklyDigest2017-08_3.md)**

**[Weekly Digest Aug. 2017 \#4](https://github.com/basicmi/Machine-Learning-Articles/blob/master/WeeklyDigest2017-08_4.md)**

**[Weekly Digest Aug. 2017 \#5](https://github.com/basicmi/Machine-Learning-Articles/blob/master/WeeklyDigest2017-08_5.md)**

**[Weekly Digest Sept. 2017 \#1](https://github.com/basicmi/Machine-Learning-Articles/blob/master/WeeklyDigest2017-09_1.md)**

**[Weekly Digest Sept. 2017 \#2](https://github.com/basicmi/Machine-Learning-Articles/blob/master/WeeklyDigest2017-09_2.md)**

**[Weekly Digest Sept. 2017 \#3](https://github.com/basicmi/Machine-Learning-Articles/blob/master/WeeklyDigest2017-09_3.md)**

**[Weekly Digest Sept. 2017 \#4](https://github.com/basicmi/Machine-Learning-Articles/blob/master/WeeklyDigest2017-09_4.md)**

**[Weekly Digest Oct. 2017 \#1](https://github.com/basicmi/Machine-Learning-Articles/blob/master/WeeklyDigest2017-10_1.md)**
