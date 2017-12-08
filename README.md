# originproject
A project which tries to answer how life came to be.

## What is the Origin Project?

In the summer going into my third year of undergrad, I saw this video: [MarI/O - Machine Learning for Video Games](https://www.youtube.com/watch?v=qv6UVOQ0F44). It used genetic algorithms and neural networks to learn how to play and win the Super Mario World game. I thought this was super cool, and thought, “could we use machine learning to teach a model how to bring nucleotides together in some sensible order to make a functional protein?” I suggested this idea to my research professor at the time, and he told me that it was too complex to be an undergrad project. He was right - knowing how little I know even now, and even less two years ago, I would have gotten very lost and wouldn’t have very much to show by the end of my project.

Sort of like a brain virus, the idea has stuck with me for the past few years. The Origin Project seeks to explore and understand how the very first protein came to be from a computational point of view.

## Basic Building Blocks of Life

If we’re going to explore how we can model the origin of life, we need to first define the substrate that constitutes it. In physics we have atoms, in computer science we have bits, and in biology we have deoxyribonucleic acid (DNA for short). All of these things can be further divisible but these building blocks are all carriers of information. Biology has the central dogma, which says that genetic information flows from DNA, which gets transcribed into ribonucleic acid (RNA) by RNA polymerase, which is then translated into proteins which are made up of amino acids by the ribosome. DNA is made up of four different bases, adenine (A), cytosine (C), guanine (G) and thymine (T). This DNA is transcribed into RNA, where thymine is replaced with uracil. The RNA is read in tuples of three, translating into one of 20 different amino acids which when combined together make a protein.

What is the most basic building block of life?

Life as we know it, the organisms that we see - the matter that makes up our own body, is made through a mosaic of many different complex processes. Somehow, they found the energy and the design to assemble matter in such a way to create muscle, bone, ligaments, etc. To examine how these larger macro structures came to be, we should look at how the smaller components that make up the larger part came to be. The bacteria is one of the most simplest forms of life on this planet. In 2016, Craig Venter’s team designed and synthesized a minimal bacterial genome to create a self-replicating bacteria using 473 genes [1]. The bacteria was named JCVI-syn1.0.  Whether or not JCVI-syn1.0 is a good representative of a potential early example of life on this planet, I’m not sure. But even the self-replicating bacteria is made up of genes

## Implementation Ideas

* uniform distribution of selecting A, T, C, G
    * or - make a prior using empirical Bayesian approach by getting a distribution of nucleotides in the body
* The Homo sapiens protein length is distributed exponentially

Want to take a Bayesian approach to making proteins through a generative approach.


## Pre-requisites:
* a decent knowledge of PGMs (need to take the course by Daphne Koller)
* Bayesian methods

### Resources
1. Design and synthesis of a minimal bacterial genome http://science.sciencemag.org/content/351/6280/aad6253
2. First Life: The search for the first replicator https://www.newscientist.com/article/mg21128251-300-first-life-the-search-for-the-first-replicator/

#### On the Name
I was initially going to go with the name “Genesis” because it initially sounded pretty cool, but I realized that it would be too controversial to name it after the first book of the Bible. So instead I went with “Origin”.
