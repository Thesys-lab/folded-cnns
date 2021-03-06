# FoldedCNNs

![alt text](folding_example.png "Example of a FoldedCNN")

## ICML 2021

**Title:** Boosting the Throughput and Accelerator Utilization of Specialized CNN Inference Beyond Increasing Batch Size

**Abstract:**
Datacenter vision systems widely use small, specialized convolutional neural networks (CNNs) trained on specific tasks for high-throughput inference. These settings employ accelerators with massive computational capacity, but which specialized CNNs underutilize due to having low arithmetic intensity. This results in suboptimal application-level throughput and poor returns on accelerator investment. Increasing batch size is the only known way to increase both application-level throughput and accelerator utilization for inference, but yields diminishing returns; specialized CNNs poorly utilize accelerators even with large batch size. We propose FoldedCNNs, a new approach to CNN design that increases inference throughput and utilization beyond large batch size. FoldedCNNs rethink the structure of inputs and layers of specialized CNNs to boost arithmetic intensity: in FoldedCNNs, f images with C channels each are concatenated into a single input with fC channels and jointly classified by a wider CNN. Increased arithmetic intensity in FoldedCNNs increases the throughput and GPU utilization of specialized CNN inference by up to 2.5x and 2.8x, with accuracy close to the original CNN in most cases.

**Paper:** [PMLR link](http://proceedings.mlr.press/v139/kosaian21a.html)

**ICML 2021 schedule for the paper:** Spotlight presentation and Q&A in the "AutoML and Neural Network Architectures 1" session, on Tuesday 20th July 2021, 10 a.m. EDT — 11 a.m. EDT. Poster at Spot C2 in Virtual World, Tuesday 20th July 2021, 11 a.m. EDT — 2 p.m. EDT.

## Video
The spotlight presentation for the paper is available at this [link](https://icml.cc/virtual/2021/spotlight/8416). Access to this link requires that one be registered for ICML 2021.

## Code
The code used in developing and evaluating FoldedCNNs is available and maintained in the following repository: [https://github.com/msr-fiddle/folded-cnns](https://github.com/msr-fiddle/folded-cnns). Please raise any issues and pull requests within this linked repository.

# Support
This work was completed in part through the support of Microsoft Research during a summer internship. Co-author Jack was also funded in part by an NSF Graduate Research Fellowship (DGE-1745016 and DGE-1252522). Co-authors Jack and Rashmi were also funded in part by Amazon Web Services and in part by the AIDA project (POCI-01-0247- FEDER-045907) co-financed by the European Regional Development Fund through the Operational Program for Competitiveness and Internationalisation 2020.
