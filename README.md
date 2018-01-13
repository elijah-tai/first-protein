# originproject
Have you ever wondered how life came to be? Can a Github repo help answer the origins of life?

## Basic Building Blocks of Life

In physics we have atoms, in computer science we have bits, and in biology we have deoxyribonucleic acid (DNA for short). All of these things can be further divisible but these building blocks are all carriers of information. Biology has the central dogma, which says that genetic information flows from DNA, which gets transcribed into ribonucleic acid (RNA) by RNA polymerase, which is then translated into proteins which are made up of amino acids by the ribosome. DNA is made up of four different bases, adenine (A), cytosine (C), guanine (G) and thymine (T). This DNA is transcribed into RNA, where thymine is replaced with uracil. The RNA is read in tuples of three, translating into one of 20 different amino acids which when combined together make a protein.

Life as we know it, the organisms that we see - the matter that makes up our own body, is made through a mosaic of many different complex processes. Somehow, they found the energy and the design to assemble matter in such a way to create muscle, bone, ligaments, etc. To examine how these larger macro structures came to be, we should look at how the smaller components that make up the larger part came to be. The bacteria is one of the most simplest forms of life on this planet. In 2016, Craig Venter’s team designed and synthesized a minimal bacterial genome to create a self-replicating bacteria using 473 genes [1]. The bacteria was named JCVI-syn1.0.  Whether or not JCVI-syn1.0 is a good representative of a potential early example of life on this planet, I’m not sure. But even the self-replicating bacteria is made up of genes

## Implementation Ideas

* uniform distribution of selecting A, T, C, G
    * or - make a prior using empirical Bayesian approach by getting a distribution of nucleotides in the body
* The Homo sapiens protein length is distributed exponentially

Want to take a generative approach to protein genesis.

### Resources
1. Design and synthesis of a minimal bacterial genome http://science.sciencemag.org/content/351/6280/aad6253
2. First Life: The search for the first replicator https://www.newscientist.com/article/mg21128251-300-first-life-the-search-for-the-first-replicator/
