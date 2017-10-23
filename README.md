# Interesting stuff of AI/ML/DL

## Weekly Digest 2017-10 \#4

**[A List of Chip/IP for Deep Learning (keep updating)](https://basicmi.github.io/Deep-Learning-Processor-List/)**
> Machine Learning, especially Deep Learning technology is driving the evolution of artificial intelligence (AI). At the beginning, deep learning has primarily been a software play. Start from the year 2016, the need for more efficient hardware acceleration of AI/ML/DL was recognized in academia and industry. This year, we saw more and more players, including world’s top semiconductor companies as well as a number of startups, even tech giants Google, have jumped into the race.
> I believe that it could be very interesting to look at them together. So, I build this list of AI/ML/DL ICs and IPs on Github and keep updating. If you have any suggestion or new information, please let me know.

**[Intel® Nervana™ Neural Network Processors (NNP) Redefine AI Silicon](https://www.intelnervana.com/intel-nervana-neural-network-processors-nnp-redefine-ai-silicon/)**
> As our Intel CEO Brian Krzanich discussed earlier today at Wall Street Journal’s D.Live event, Intel will soon be shipping the world’s first family of processors designed from the ground up for artificial intelligence (AI): the [Intel® Nervana™ Neural Network Processor](https://newsroom.intel.com/editorials/intel-pioneers-new-technologies-advance-artificial-intelligence/) family (formerly known as “Lake Crest”). This family of processors is over 3 years in the making, and on behalf of the team building it, I’d like to share a bit more insight on the motivation and design behind the world’s first neural network processor.

**[AlphaGo Zero: Learning from scratch](https://deepmind.com/blog/alphago-zero-learning-scratch/)**
> However, for some problems this human knowledge may be too expensive, too unreliable or simply unavailable. As a result, a long-standing ambition of AI research is to bypass this step, creating algorithms that achieve superhuman performance in the most challenging domains with no human input. In our most [recent paper](https://www.nature.com/nature/journal/v550/n7676/full/nature24270.html), published in the journal Nature, we demonstrate a significant step towards this goal.
> The paper introduces AlphaGo Zero, the latest evolution of AlphaGo, the first computer program to defeat a world champion at the ancient Chinese game of Go. Zero is even more powerful and is arguably the strongest Go player in history.
> David Silver and Julian Schrittwieser from DeepMind’s AlphaGo team answered Reddit questions on October 19th. Check out [their answers for novel insights into AlphaGo Zero and the team’s future goals](https://www.reddit.com/r/MachineLearning/comments/76xjb5/ama_we_are_david_silver_and_julian_schrittwieser/).

**[GOOGLE'S LEARNING SOFTWARE LEARNS TO WRITE LEARNING SOFTWARE](https://www.wired.com/story/googles-learning-software-learns-to-write-learning-software/)**
> In a project called AutoML, Google’s researchers have taught machine-learning software to build machine-learning software. In some instances, what it comes up with is more powerful and efficient than the best systems the researchers themselves can design. Google says the system recently scored a record 82 percent at categorizing images by their content. On the harder task of marking the location of multiple objects in an image, an important task for augmented reality and autonomous robots, the auto-generated system scored 43 percent. The best human-built system scored 39 percent.

**[Hey Siri: An On-device DNN-powered Voice Trigger for Apple’s Personal Assistant](https://machinelearning.apple.com/2017/10/01/hey-siri.html)**
> The “Hey Siri” feature allows users to invoke Siri hands-free. A very small speech recognizer runs all the time and listens for just those two words. When it detects “Hey Siri”, the rest of Siri parses the following speech as a command or query. The “Hey Siri” detector uses a Deep Neural Network (DNN) to convert the acoustic pattern of your voice at each instant into a probability distribution over speech sounds. It then uses a temporal integration process to compute a confidence score that the phrase you uttered was “Hey Siri”. If the score is high enough, Siri wakes up. This article takes a look at the underlying technology. It is aimed primarily at readers who know something of machine learning but less about speech recognition.

**[Routes to Defensibility for your AI Startup](https://machinelearnings.co/routes-to-defensibility-for-your-ai-startup-2875a1b51d4e)**
> A simple framework for understanding the impact of data network effects and incumbents’ advantages in your industry
> In short: VCs are looking for companies that could be worth hundreds of millions or billions of dollars by the next 5–10 years and:
> Projected future cash flows are a proxy for valuation,
> Ability to generate profit is a proxy for projected future cash flow,
> Moats are a proxy for the ability to generate profits.

**[Pixel Visual Core: image processing and machine learning on Pixel 2](https://www.blog.google/products/pixel/pixel-visual-core-image-processing-and-machine-learning-pixel-2/)**
> Pixel Visual Core is Google’s first custom-designed co-processor for consumer products. It’s built into every Pixel 2, and in the coming months, we’ll turn it on through a software update to enable more applications to use Pixel 2’s camera for taking HDR+ quality pictures.

**[Introducing NNVM Compiler: A New Open End-to-End Compiler for AI Frameworks](https://aws.amazon.com/cn/blogs/ai/introducing-nnvm-compiler-a-new-open-end-to-end-compiler-for-ai-frameworks/)**
> Diverse AI frameworks and hardware bring huge benefits to users, but it is very challenging to AI developers to deliver consistent results to end users. Luckily, we are not the first to face this kind of problems. Computer science has a long history of running various programming languages on different hardware. One key technology to solve this problem is the compiler. Motivated by the compiler technology, a group of researchers including Tianqi Chen, Thierry Moreau, Haichen Shen, Luis Ceze, Carlos Guestrin, and Arvind Krishnamurthy from Paul G. Allen School of Computer Science & Engineering, University of Washington, together with Ziheng Jiang from the AWS AI team, introduced the [TVM stack](http://tvmlang.org/2017/08/17/tvm-release-announcement.html) to simplify this problem.
> Today, AWS is excited to announce, together with the research team from UW, an end-to-end compiler based on the TVM stack that compiles workloads directly from various deep learning frontends into optimized machine codes. Let’s take a look at the architecture.

**[Numerai’s Master Plan](https://medium.com/numerai/numerais-master-plan-1a00f133dba9)**
> The core idea of Numerai was to give away all of our data for free, and let anyone train machine learning algorithms on it and submit predictions to our hedge fund. This was a very counterintuitive idea. We already had our own internal machine learning models on the data so it seemed like a distraction to open it up to the world.
> Some of our distractions have already proven themselves to be outrageously successful, and others are still developing, but they actually aren’t distractions at all. They are all part of the plan.

**[How machine learning is helping neuroscientists understand the brain](https://massivesci.com/articles/neuroscience-machine-learning-metaphors/)**
> The workings of the brain are the greatest mystery in science. Unlike our models of physics, strong enough to predict gravitational waves and unseen particles, our brain models explain only the most basic forms of perception, cognition, and behavior. We know plenty about the biology of neurons and glia, the cells that make up the brain. And we know enough about how they interact with each other to account for some reflexes and sensory phenomena, such as optical illusions. But even slightly more complex levels of mental experience have evaded our theories.
> We are quickly approaching the point when our traditional reasons for pleading ignorance – that we don’t have the right tools, that we need more data, that brains are complex and chaotic – will not account for our lack of explanations. Our techniques for seeing what the brain and its neurons are doing, at any given moment, get stronger every year.

**[A Berkeley View of Systems Challenges for AI](https://www2.eecs.berkeley.edu/Pubs/TechRpts/2017/EECS-2017-159.html)**
> With the increasing commoditization of computer vision, speech recognition and machine translation systems and the widespread deployment of learning-based back-end technologies such as digital advertising and intelligent infrastructures, AI (Artificial Intelligence) has moved from research labs to production. These changes have been made possible by unprecedented levels of data and computation, by methodological advances in machine learning, by innovations in systems software and architectures, and by the broad accessibility of these technologies.
> The next generation of AI systems promises to accelerate these developments and increasingly impact our lives via frequent interactions and making (often mission-critical) decisions on our behalf, often in highly personalized contexts. Realizing this promise, however, raises daunting challenges. In particular, we need AI systems that make timely and safe decisions in unpredictable environments, that are robust against sophisticated adversaries, and that can process ever increasing amounts of data across organizations and individuals without compromising confidentiality. These challenges will be exacerbated by the end of the Moore’s Law, which will constrain the amount of data these technologies can store and process. In this paper, we propose several open research directions in systems, architectures, and security that can address these challenges and help unlock AI’s potential to improve lives and society.

**[Intel Nervana has released Coach, an open source AI development framework](http://coach.nervanasys.com/design/index.html)**
> Coach is a python environment which models the interaction between an agent and an environment in a modular way. With Coach, it is possible to model an agent by combining various building blocks, and training the agent on multiple environments. The available environments allow testing the agent in different practical fields such as robotics, autonomous driving, games and more. Coach collects statistics from the training process and supports advanced visualization techniques for debugging the agent being trained.

**[Weekly Digest Aug. 2017 \#2](https://github.com/basicmi/Machine-Learning-Articles/blob/master/WeeklyDigest2017-08_2.md)**

**[Weekly Digest Aug. 2017 \#3](https://github.com/basicmi/Machine-Learning-Articles/blob/master/WeeklyDigest2017-08_3.md)**

**[Weekly Digest Aug. 2017 \#4](https://github.com/basicmi/Machine-Learning-Articles/blob/master/WeeklyDigest2017-08_4.md)**

**[Weekly Digest Aug. 2017 \#5](https://github.com/basicmi/Machine-Learning-Articles/blob/master/WeeklyDigest2017-08_5.md)**

**[Weekly Digest Sept. 2017 \#1](https://github.com/basicmi/Machine-Learning-Articles/blob/master/WeeklyDigest2017-09_1.md)**

**[Weekly Digest Sept. 2017 \#2](https://github.com/basicmi/Machine-Learning-Articles/blob/master/WeeklyDigest2017-09_2.md)**

**[Weekly Digest Sept. 2017 \#3](https://github.com/basicmi/Machine-Learning-Articles/blob/master/WeeklyDigest2017-09_3.md)**

**[Weekly Digest Sept. 2017 \#4](https://github.com/basicmi/Machine-Learning-Articles/blob/master/WeeklyDigest2017-09_4.md)**

**[Weekly Digest Oct. 2017 \#1](https://github.com/basicmi/Machine-Learning-Articles/blob/master/WeeklyDigest2017-10_1.md)**

**[Weekly Digest Oct. 2017 \#2](https://github.com/basicmi/Machine-Learning-Articles/blob/master/WeeklyDigest2017-10_2.md)**

**[Weekly Digest Oct. 2017 \#3](https://github.com/basicmi/Machine-Learning-Articles/blob/master/WeeklyDigest2017-10_3.md)**
