# GitHub Codespaces ♥️ Jupyter Notebooks

# Running and Making the project

#### I started by opening the Github Jupyter Pytorch template in a codespace, anyone can do this and start coding right away! https://github.com/github/codespaces-jupyter

#### Details are included in the code breaking down how everything works

# Hi! I'm Lucas. This is a project created as part of a Machine Learning Seminar. This has been the culmination of approximately 2 weeks of research, complete with a presentation, demonstration of training/analyzing a model, and some efficient aglorithms with Adjacency Matrices.  

# This project has been a tremendous learning exprience for me, and I am glad to have presented this to a board of 6 professors (includng the heads of Computer Science and Math Departments at Rutgers University Camden). 

# I am currently a Junior Computer Science and Applied Math Double Major, while this topic proved challenging intially, this has been an excellent experience that has taught me how neural networks, graphs, and GCNs work. It has also helped me refine my career goals and aspirations, and helped me understand the intersection of Computer Science and other STEM fields, and the implications of research like this. I want to further my research on topics like this, and hopefully research auto-immune diseases one day, although I do not study Chemistry/Biology/Health Sciences, I love all STEM fields.

# Here is a lecture (1 hr) explaining Graph Convolution Networks and testing the model

[![Lecture](https://img.youtube.com/vi/bRZ0R5iKlY0/0.jpg)](https://youtu.be/bRZ0R5iKlY0)

# Project Overview

### Presentation

#### I began my research by constructing the presentation, which is extremely important for understanding what the program accomplishes, how its different from a standard neural network, and how the system works overall.

#### The next thing I worked on was the Adjacency Matrix, although it is not that important to the Neural Network, it is important to understand how they work as input, and I found they have particluarly interesting properties.


### Demonstration

#### This was the last portion of my project, the problem comes from the book Understanding Deep Learning, and there was an existing database of molecules for the problem. Problems like these are actively being researched with more complex models to research medicine side effects, potential risk of new molecules and medicines without having to preform lab tests. This demonstration is a laymans understanding of the problem, but an accuracy of 75% is not bad!

# Future Work

I plan to build on this project in several directions that combine my interests in applied mathematics and computer science. Given the foundation I've established with this GCN implementation, I'm excited to extend my research in these areas:

## Health & Medicine Applications

I want to take my research towards machine learning for drug side effects, which would be a natural extension of this toxicity prediction work. This could involve:

- Implementing more complex molecular representation techniques that capture 3D structures
- Incorporating patient data to predict personalized side effect risks
- Developing multi-task models that simultaneously predict efficacy and side effects
- Working with larger pharmaceutical datasets beyond Tox21

## Financial Applications

Another area that interests me is applying similar graph-based techniques to the stock market. Financial markets naturally form graphs where companies are nodes and various relationships (supply chains, investments, etc.) form edges. This would involve:

- Adapting GCNs to temporal graph structures that change over time
- Incorporating market sentiment data alongside quantitative metrics
- Building prediction models for stock correlations and market movements
- Developing trading strategies based on graph pattern recognition

## Real-World System Optimization

I also want to look into real-world current systems and how they optimize and manage complexity. This could include:

- Studying how supply chain networks can be optimized using graph neural networks
- Exploring traffic flow prediction and optimization using spatial-temporal graphs
- Investigating power grid management with graph-based approaches
- Applying these techniques to university resource allocation or class scheduling

As I continue my studies in Computer Science and Applied Math, I'm particularly interested in finding opportunities to collaborate with professors and graduate students on these topics. The intersection of graph theory, deep learning, and real-world applications presents fascinating research possibilities that I'm eager to explore.


## Guidance

* Prof. Siqi Fu
* Prof. Sunil Shende
* Stanford Lecture Series
* 3Blue1Brown


# Resources Utilized

# Relevant Sources for Molecular Toxicity Prediction with Graph Neural Networks

## Academic Papers

* "Neural Message Passing for Quantum Chemistry" - Gilmer et al. (2017)
  https://arxiv.org/abs/1704.01212

* "MoleculeNet: A Benchmark for Molecular Machine Learning" - Wu et al. (2018)
  https://pubs.acs.org/doi/10.1021/acs.jcim.7b00663

* "DeepTox: Toxicity Prediction using Deep Learning" - Mayr et al. (2016)
  https://journal.frontiersin.org/article/10.3389/fenvs.2015.00080

* "Analyzing Learned Molecular Representations for Property Prediction" - Yang et al. (2019)
  https://pubs.acs.org/doi/10.1021/acs.jcim.9b00237

* "Chemprop: A Machine Learning Package for Chemical Property Prediction" - Chithrananda et al. (2020)
  https://arxiv.org/abs/2008.09742

* "Graph Convolutional Networks for Computational Drug Development and Discovery" - Li et al. (2019)
  https://pubs.acs.org/doi/10.1021/acs.jcim.8b00740

* "Predicting Drug Toxicity: Where Machine Learning Meets the Human Body" - Ramsundar et al. (2019)
  https://www.sciencedirect.com/science/article/pii/S2001037019300327

## Datasets and Resources

* "Tox21 Data Challenge 2014" - NIH
  https://tripod.nih.gov/tox21/challenge/

* "Tox21 Challenge: Deep Learning for Toxicity Prediction" - Huang et al. (2015)
  https://ncats.nih.gov/files/tox21-challenge-report.pdf

* "Open Chem: Deep Learning for Drug Discovery" - DeepChem
  https://deepchem.io/

* "RDKit: Open-source cheminformatics" - RDKit Documentation
  https://www.rdkit.org/docs/

## Tutorials and Implementations

* "Graph Neural Networks for Molecule Property Prediction" - PyTorch Geometric
  https://pytorch-geometric.readthedocs.io/en/latest/notes/introduction.html

* "Molecular Property Prediction with DGL" - Deep Graph Library
  https://docs.dgl.ai/en/latest/tutorials/property_prediction/index.html

* "Machine Learning for Drug Discovery" - Teachings from Stanford University
  https://web.stanford.edu/class/cs279/

* "Molecular Machine Learning with PyTorch" - Molecule-Net
  https://github.com/deepchem/deepchem/tree/master/examples/tutorials

## Review Articles

* "Machine Learning for Toxicity Prediction: From in silico to in vivo" - Alves et al. (2021) 
  https://www.sciencedirect.com/science/article/pii/S2001037021000167

* "Graph Neural Networks in TDM: Recent Advances and Applications" - Zhou et al. (2020)
  https://pubs.acs.org/doi/10.1021/acs.jcim.0c00868

* "Artificial Intelligence in Drug Discovery: What Is Realistic, What Are Illusions?" - Walters & Barzilay (2021)
  https://pubs.acs.org/doi/10.1021/acs.jcim.0c00793

## Books

* "Understanding Deep Learning" - Simon J.D. Prince (2023)
  https://udlbook.github.io/udlbook/

* "Deep Learning for the Life Sciences" - Vijay Pande, Patrick Walters, Peter Eastman, and Bharath Ramsundar (2019)
  https://www.oreilly.com/library/view/deep-learning-for/9781492039822/

* "Graph Representation Learning" - William L. Hamilton (2020)
  https://www.cs.mcgill.ca/~wlh/grl_book/

* "Machine Learning in Chemistry: The Impact of Artificial Intelligence" - Hugh M. Cartwright (2020)
  https://pubs.rsc.org/en/content/ebook/978-1-78801-538-0

## Software and Libraries

* "PyTorch Geometric" - Official Documentation
  https://pytorch-geometric.readthedocs.io/

* "TorchDrug: A Powerful and Versatile Machine Learning Platform for Drug Discovery" - Documentation
  https://torchdrug.ai/

* "RDKit: Open-Source Cheminformatics Software" - GitHub Repository
  https://github.com/rdkit/rdkit

* "DeepChem: Deep-Learning Models for Drug Discovery" - GitHub Repository
  https://github.com/deepchem/deepchem