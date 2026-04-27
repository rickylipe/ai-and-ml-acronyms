# AI & ML Acronyms

A comprehensive, community-maintained glossary of acronyms and abbreviations used across artificial intelligence, machine learning, and adjacent fields. Whether you're just getting started or deep in the literature, this reference is designed to give you quick, clear definitions alongside enough context to understand how each term fits into the broader landscape.

## What's Included

- **443 acronyms and abbreviations** spanning 18 topic areas
- Definitions written for clarity, not just completeness
- Organized by category so related terms are easy to find together

## How to Use This Reference

Browse by category below, or use your browser's search (`Ctrl+F` / `Cmd+F`) to jump directly to a term.

## Categories

- [General AI & Machine Learning](#general-ai-machine-learning)
- [Deep Learning & Neural Network Architectures](#deep-learning-neural-network-architectures)
- [Natural Language Processing](#natural-language-processing)
- [Computer Vision](#computer-vision)
- [Generative Models](#generative-models)
- [Reinforcement Learning](#reinforcement-learning)
- [Optimization & Training](#optimization-training)
- [Statistical & Classical ML Methods](#statistical-classical-ml-methods)
- [Explainability & Interpretability](#explainability-interpretability)
- [Evaluation Metrics & Benchmarks](#evaluation-metrics-benchmarks)
- [Data Attribution, Provenance & Unlearning](#data-attribution-provenance-unlearning)
- [Privacy, Security & Compliance](#privacy-security-compliance)
- [Cryptographic Methods](#cryptographic-methods)
- [Audio, Music & Speech Processing](#audio-music-speech-processing)
- [Sign Language & Accessibility](#sign-language-accessibility)
- [Datasets](#datasets)
- [Hardware, Infrastructure & Systems](#hardware-infrastructure-systems)
- [Organizations, Standards & Conferences](#organizations-standards-conferences)

---

*This glossary is maintained as a living document. See [CONTRIBUTING.md](CONTRIBUTING.md) to add entries or suggest improvements.*

## General AI & Machine Learning

| Acronym | Full Name | Definition |
|---------|-----------|------------|
| AGI | Artificial General Intelligence | The hypothetical ability of an intelligent agent to understand or learn any intellectual task that a human being can |
| AI | Artificial Intelligence | The simulation of human intelligence in machines that are programmed to think like humans and mimic their actions. |
| CF | Collaborative Filtering | Technique used in recommendation systems predicting user preferences based on patterns from similar users or items. |
| CTR | Collaborative Topic Regression | A recommendation model that integrates collaborative filtering with topic modeling (like LDA) to leverage item content information. |
| FSL | Few-Shot Learning | A learning paradigm where models generalize from very few labeled examples; relevant to attribution when target behaviors emerge from small demonstration sets. |
| GWAS | Genome-Wide Association Study | A genetic epidemiology method; used as a case study for membership inference in genomic data settings with strong privacy requirements. |
| ICL | In-Context Learning | A prompting technique where task demonstrations are provided in the input context rather than updating model weights; creates attribution challenges because outputs depend on both context and training. |
| i.i.d | Independent and Identically Distributed | A fundamental assumption in many statistical and machine learning models, stating that random variables in a sequence have the same probability distribution and are mutually independent. |
| IID | Independent and Identically Distributed | A standard statistical assumption that training examples are drawn from the same distribution independently; violated in many real-world settings and relevant to influence function validity. |
| KL | Kullback Leibler (KL) divergence | A measure of how one probability distribution diverges from a second, expected probability distribution; often used as a loss or regularization term (e.g., in VAEs). |
| LTR | Learning To Rank | Application of machine learning to construct ranking models for information retrieval systems, ordering items based on relevance. |
| MDL | Minimum description length (MDL) principle | A model selection principle stating that the best model provides the shortest combined encoding of itself and the training data, formalizing Occam's Razor. |
| MINT | Mutual Information based Transductive Feature Selection | A transductive feature selection method that uses mutual information to identify features most relevant to the target in a test-data-aware setting. |
| ML | Machine Learning | The study of computer algorithms that can improve automatically through experience and by the use of data. |
| NFL | No Free Lunch (NFL) theorem | A theoretical result stating no single algorithm universally outperforms all others across every problem; gains in some domains imply trade-offs elsewhere. |
| OOD | Out-of-Distribution | Refers to inputs or data that differ from the training distribution; relevant to attribution reliability when target outputs are generated for OOD queries. |
| PM | Project Manager | A professional responsible for planning, executing, and closing projects by coordinating teams, resources, and timelines to achieve defined goals. |
| POC | Proof of Concept | A small-scale prototype or experiment demonstrating that a concept or technical approach is feasible before committing resources to full development. |
| PU | Positive Unlabaled | Machine learning paradigma to learn from only positive and unlabeled data. |
| SBSE | Search-based software engineering | The application of metaheuristic search techniques such as genetic algorithms and simulated annealing to automate and optimize software engineering tasks. |
| STL | Selt-Taught Learning | A semi-supervised approach leveraging large unlabeled datasets for unsupervised feature pre-training before fine-tuning on a downstream supervised task with limited labels. |
| WMA | Weighted Majority Algorithm | An online learning algorithm combining expert predictions with multiplicatively updated weights, reducing influence of experts with higher historical error rates. |

## Deep Learning & Neural Network Architectures

| Acronym | Full Name | Definition |
|---------|-----------|------------|
| AE | AutoEncoder | A type of artificial neural network used to learn efficient codings of unlabeled data (unsupervised learning) |
| ANN | Artificial Neural Network | A collection of connected computational units or nodes called neurons arranged in multiple computational layers. |
| ARNN | Anticipation Recurrent Neural Network | A type of RNN designed to predict future inputs or states in sequential data. |
| BILSTM | Bidirectional Long Short-Term Memory | A bidirectional recurrent neural network architecture utilizing LSTM units (see LSTM). |
| BNN | Bayesian Neural Network | A type of artificial neural network built by introducing random variations into the network either by giving the network's artificial neurons stochastic transfer functions or by giving them stochastic weights |
| BRNN | Bidirectional Recurrent Neural Network | An RNN variant that processes sequence data in both forward and backward directions, capturing context from past and future elements. |
| CAE | Contractive AutoEncoder | An autoencoder variant that adds a penalty term to the loss function to encourage robustness of the learned representation to small input variations. |
| CDBN | Convolutional Deep Belief Networks | A type of deep artificial neural network composed of multiple layers of convolutional restricted Boltzmann machines stacked together. |
| CEC | Constant Error Carousel | A key component within LSTM units that allows error signals to propagate back through time without vanishing or exploding gradient issues. |
| CLNN | ConditionaL Neural Networks | Neural networks whose output or internal processing is dependent on an auxiliary conditional input. |
| CMAC | Cerebellar Model Articulation Controller | A type of neural network inspired by the mammalian cerebellum, often used for function approximation and control tasks, using associative memory principles. |
| CNN | Convolutional Neural Network | A class of artificial neural network (ANN), typically using convolutional layers, most commonly applied to analyze visual imagery. |
| ConvNet | Convolutional Neural Network | A class of artificial neural network (ANN), typically using convolutional layers, most commonly applied to analyze visual imagery. (Synonym for CNN) |
| CRBM | Conditional Restricted Boltzmann Machine | An extension of the Restricted Boltzmann Machine where the visible and/or hidden units are conditioned on additional input variables. |
| CRNN | Convolutional Recurrent Neural Network | A hybrid neural network architecture combining Convolutional Neural Networks (CNNs) and Recurrent Neural Networks (RNNs), typically for spatio-temporal data. |
| CTC | Connectionist Temporal Classification | A loss function used for training sequence models (like RNNs) on tasks where the alignment between input and output sequences is variable or unknown (e.g., speech). |
| DAE | Denoising AutoEncoder or Deep AutoEncoder | An autoencoder trained to reconstruct clean input from corrupted versions (Denoising AE), often with multiple hidden layers (Deep AE). |
| DBM | Deep Boltzmann Machine | An undirected probabilistic graphical model (like RBM) with multiple layers of hidden variables, allowing for more complex representations. |
| DBN | Deep Belief Network | A generative graphical model composed of multiple layers of latent variables ("beliefs"), typically trained greedily layer-by-layer using RBMs. |
| DCMDN | Deep Convolutional Mixture Density Network | Combines CNNs with Mixture Density Networks to model complex conditional probability distributions, often for image generation or regression tasks with uncertainty. |
| DeconvNet | DeConvolutional Neural Network | A neural network architecture often utilizing transposed convolutions (sometimes called deconvolutions) for tasks like image segmentation or visualization of CNN features. |
| DL | Deep Learning | A subfield of machine learning based on artificial neural networks with multiple layers (deep architectures) enabling learning of complex patterns. |
| DNN | Deep Neural Network | An artificial neural network (ANN) with multiple hidden layers between the input and output layers. |
| DSN | Deep Stacking Network | A deep learning architecture based on stacking blocks of simple modules (like MLPs) trained sequentially, layer by layer. |
| ELM | Extreme Learning Machine | A feedforward neural network training algorithm where hidden node parameters are randomly assigned and only output weights are learned analytically, often very fast. |
| ELU | Exponential Linear Unit | An activation function similar to ReLU but with negative values, which can help push mean activations closer to zero, potentially speeding up learning. |
| FC | Fully-Connected | Layers where all the inputs from one layer are connected to every activation unit of the next layer. |
| FC-CNN | Fully Convolutional Convolutional Neural Network | A neural network architecture consisting entirely of convolutional layers (and pooling/upsampling), without any fully-connected layers. |
| FC-LSTM | Fully Connected Long Short-Term Memory | An LSTM network where connections between time steps or layers might involve fully connected transformations, combining sequential and dense processing. |
| FCN | Fully Convolutional Network | A neural network that only performs convolution (and subsampling or upsampling) operations, often used for semantic segmentation. (Similar to FC-CNN) |
| FNN | Feedforward Neural Network | An artificial neural network where connections between nodes do not form a cycle; information moves only forward from input to output layers. |
| GAP | Global Average Pooling | A pooling operation often used in CNNs before the final classification layer, reducing each feature map to a single value by averaging, which helps reduce overfitting and enforces correspondence between feature maps and categories. |
| GFNN | Gradient Frequency Neural Networks | Neural networks possibly designed to better learn or represent high-frequency components in data, potentially by manipulating gradients during training. |
| GNN | Graph Neural Network | A class of neural networks operating on graph-structured data; relevant to attribution methods that model relationships between training examples. |
| HAN | Hierarchical Attention Network | A neural network architecture, typically used for document classification, employing attention mechanisms at both word and sentence levels to capture important information hierarchically. |
| HNN | Hopfield Neural Network | A form of recurrent artificial neural network popularized by John Hopfield, serving as content-addressable ("associative") memory systems with binary threshold nodes. |
| KAN | Kolmogorov-Arnold Networks | Ref. https://arxiv.org/abs/2404.19756v1 - A novel neural network architecture inspired by the Kolmogorov-Arnold representation theorem, potentially offering better interpretability and scaling properties compared to MLPs by using learnable activation functions on edges instead of fixed ones on nodes. |
| LSTM | Long Short-Term Memory | A recurrent neural network can process not only single data points (such as images) but also entire sequences of data (such as speech or video). |
| MADE | Masked Autoencoder for Distribution Estimation | An autoregressive model based on autoencoders, using carefully constructed masks to ensure that reconstructions respect autoregressive constraints, allowing for tractable density estimation. |
| MCLNN | Masked ConditionaL Neural Networks | Conditional neural networks where masking techniques might be applied, possibly to control information flow or enforce specific dependencies based on the condition. |
| MDN | Mixture Density Network | A neural network that outputs parameters of a mixture distribution (e.g., Gaussian mixture), enabling prediction of multi-modal probability distributions over outputs. |
| MDRNN | Multidimensional recurrent neural network | An extension of RNNs that processes data with multiple spatial dimensions by applying recurrent connections along each axis simultaneously. |
| MLP | Multi-Layer Perceptron | A fully connected class of feedforward artificial neural network |
| MSDAE | Modified Sparse Denoising Autoencoder | A denoising autoencoder variant incorporating sparsity regularization on hidden representations to encourage more compact and informative feature learning. |
| NAS | Neural Architecture Search | A technique for automating the design of artificial neural networks. |
| NC | Neural Collapse | A geometric phenomenon in the final layer of trained classifiers where class representations collapse to a simplex ETF; relevant to understanding attribution under representation sharing. |
| NN | Neural Network | A computational model loosely inspired by the brain, composed of interconnected layers of nodes (neurons) that learn by adjusting weighted connections from data. |
| NPE | Neural Physical Engine | A neural network trained to simulate physical dynamics, enabling physics-aware prediction and reasoning without relying on explicit physics equations. |
| NTK | Neural Tangent Kernel | A kernel function describing the behavior of infinitely wide neural networks; used as a theoretical foundation for gradient-based influence function approximations. |
| NTM | Neural Turing Machine | A neural network augmented with a differentiable external memory and attention-based read/write heads, enabling learning of complex algorithmic input-output mappings. |
| PCA | Principal Component Analysis | The process of computing the principal components and using them to perform a change of basis on the data sometimes using only the first few principal components and ignoring the rest. |
| PNN | Probabilistic Neural Network | A feedforward network based on kernel density estimation that computes class membership probabilities at output, used primarily for pattern classification. |
| PReLU | Parametric Rectified Linear Unit-Yor Topic Modeling | An activation function extending ReLU by treating the negative-side slope as a learnable parameter, improving performance in deep networks. |
| RandNN | Random Neural Network | A neural network where weights are randomly initialized and kept fixed (not trained), used in reservoir computing and random feature approximation methods. |
| RBF | Radial Basis Function | A function whose value depends only on the distance from a fixed center point, used as a kernel in SVMs and as activations in RBF neural networks. |
| RBFNN | Radial Basis Function Neural Network | A three-layer neural network using radial basis functions as hidden activations, commonly applied to function approximation, classification, and time-series modeling. |
| RBM | Restricted Boltzmann Machine | An undirected probabilistic neural network with visible and hidden layers and symmetric connections, used as building blocks in deep belief networks and generative models. |
| ReLU | Rectified Linear Unit | An activation function that allow fast and effective training of deep neural architectures on large and complex datasets. |
| ResNet | Residual Network | A deep convolutional network architecture using skip connections; standard image classification backbone for attribution evaluations. |
| RIM | Recurrent Interence Machines | A model using recurrent networks to iteratively refine latent variable estimates, commonly applied to inverse problems in imaging and signal processing. |
| RNN | Recurrent Neural Network | A neural network for sequential data that maintains a hidden state updated at each time step via recurrent connections, enabling memory of prior inputs. |
| RNNLM | Recurrent Neural Network Language Model (RNNLM) | A language model using an RNN to estimate the conditional probability of each word given all preceding words, capturing long-range sequential dependencies. |
| RTRL | Real-Time Recurrent Learning | An online algorithm for training RNNs that computes exact gradients with respect to all parameters in real time as the network processes each input step. |
| SAE | Stacked AE | A deep feature learning architecture built by stacking autoencoders, each pre-trained to encode the output of the previous layer in an unsupervised manner. |
| SDAE | Stacked DAE | A deep architecture formed by stacking denoising autoencoders, each trained to reconstruct clean inputs from corrupted versions to learn robust hierarchical representations. |
| seq2seq | Sequence to Sequence Learning | Desribes training approach to convert sequences from one domain (e.g. sentences in English) to sequences in another domain (e.g. the same sentences translated to French). |
| SLP | Single-Layer Perceptron | The simplest feedforward neural network with a single layer of trainable weights mapping inputs directly to outputs, limited to linearly separable problems. |
| SOM | Self-Organizing Map | A self-organizing map (SOM) or self-organizing feature map (SOFM) is an unsupervised machine learning technique used to produce a low-dimensional (typically two-dimensional) representation of a higher dimensional data set while preserving the topological structure of the data |
| SSL | Self-Supervised Learning | A learning paradigm where models are trained on pretext tasks derived from unlabeled data's inherent structure to learn transferable feature representations. |
| TLFN | Time-Lagged Feedforward Neural Network | A feedforward network augmented with time-delayed input copies as additional features, capturing temporal dependencies without requiring recurrent connections. |
| V-Net | Volumetric Convolutional neural network | 3D image segmentation based on a volumetric fully convolutional neural network |
| VPNN | Vector Product Neural Network | A neural network using vector product operations (e.g., cross products or Hadamard products) instead of conventional dot products to model feature interactions. |
| WRN | Wide Residual Network | A variant of ResNet with wider layers; used as an evaluation backbone for training data attribution on image tasks. |

## Natural Language Processing

| Acronym | Full Name | Definition |
|---------|-----------|------------|
| BERT | Bidirectional Encoder Representation from Transformers | Commonly used transformer-based language model. |
| BLEU | Bilingual Evaluation Understudy | A score of the effectiveness of translating one language into another one. |
| CBOW | Continuous Bag of Words | A neural network model architecture (part of Word2Vec) used for learning word embeddings by predicting a target word from its surrounding context words. |
| ELECTRA | Efficiently Learning an Encoder that Classifies Token Replacements Accurately | A transformer-based pre-training method that learns by distinguishing real input tokens from plausible fake tokens generated by another small network (discriminator task). |
| ELMo | Embeddings from Language Models | Contextual word embedding technique generating deep, character-based representations that vary based on the sentence context. |
| ERNIE | Enhanced Representation through kNowledge IntEgration | A transformer-based language model (often associated with Baidu) that incorporates external knowledge (e.g., knowledge graph facts) during pre-training. |
| FST | Finite state transducer | A finite automaton with two tapes (input and output), used for modeling sequence-to-sequence transformations (e.g., in NLP/speech). |
| GloVE | Global Vectors | An unsupervised learning algorithm for obtaining vector representations for words, trained on aggregated global word-word co-occurrence statistics from a corpus. |
| GPT | Generative Pre-trained Transformer | An autoregressive language model that uses deep learning to produce human-like text. |
| LDA | Latent Dirichlet Allocation | A generative statistical model that allows sets of observations to be explained by unobserved groups that explain why some parts of the data are similar. |
| LDA | Linear Discriminant Analysis | A dimensionality reduction technique also used for classification, which aims to find a linear combination of features that characterizes or separates two or more classes. |
| LLaMA | Large Language Model Meta AI | Meta's open-weight language model family; commonly used as an evaluation backbone for attribution and unlearning methods. |
| LLM | Large Language Model | A deep learning model trained on vast amounts of text data, capable of understanding and generating human-like text for various NLP tasks. |
| LSA | Latent semantic analysis | A technique in NLP using singular value decomposition (SVD) to analyze relationships between documents and terms, identifying latent semantic structures. |
| LSI | Latent Semantic Indexing | An indexing and retrieval method using LSA (SVD) to identify patterns in term-document relationships, improving information retrieval by handling synonymy and polysemy. (Often used interchangeably with LSA). |
| NER | Named Entity Recognition | An NLP task that identifies and classifies named entities (e.g., persons, organizations, locations) in text into predefined semantic categories. |
| NERQ | Named Entity Recognition in Query | The application of NER to search queries to identify entities and improve search relevance, intent detection, and query expansion. |
| NLP | Natural Language Processing | A subfield of AI focused on enabling computers to understand, interpret, and generate human language in meaningful and useful ways. |
| NLT | Neural Machine Translation | An approach to translation with the use of a neural network to predict a sequence of words. |
| PEGASUS | Pre-training with Extracted Gap-Sentences for Abstractive Summarization | A pre-training method for abstractive summarization that masks whole sentences and trains the model to reconstruct them as a proxy for the summarization task. |
| PLSI | Probabilistic Latent Semantic Indexing | A statistical method for discovering latent semantic structure in document-term co-occurrence data using a probabilistic latent variable model. |
| PMI | Pointwise Mutual Information | A measure of statistical association between two events quantifying how much more often they co-occur than expected if they were statistically independent. |
| POS | Part of Speech (POS) Tagging | An NLP task that assigns grammatical categories (e.g., noun, verb, adjective) to each token in a sentence based on its role and surrounding context. |
| PPMI | Positive Pointwise Mutual Information | A PMI variant that replaces negative values with zero, used in distributional semantics to capture positive word co-occurrence associations more robustly. |
| PT | Previous Token | A term used in LLM attribution research referring to the preceding token in a sequence as a conditioning variable. |
| QNLI | Question Natural Language Inference | An NLP benchmark derived from SQuAD; used in attribution evaluations on text classification tasks. |
| RAG | Retrieval-Augmented Generation | An inference architecture that retrieves relevant documents from an external index and incorporates them into the model context; makes attribution tractable by externalizing the provenance of retrieved content. |
| RoBERTa | Robustly Optimized BERT Pretraining Approach | Commonly used transformer-based language model. |
| T5 | Text-To-Text Transfer Transformer | Transformer based language model that uses a text-to-text approach. |
| ULMFiT | Universal Language Model Fine-Tuning | A transfer learning method for NLP that pre-trains a language model on a large corpus, then uses discriminative fine-tuning and gradual layer unfreezing to adapt it to target tasks. |
| WFST | Weighted finite-state transducer (WFST) | A finite automaton with weighted transitions mapping input symbol sequences to output sequences, widely used in speech recognition and NLP for sequence transduction. |

## Computer Vision

| Acronym | Full Name | Definition |
|---------|-----------|------------|
| BiFPN | Bidirectional Feature Pyramid Network | An efficient multi-scale feature fusion method used in object detection, allowing bidirectional (top-down and bottom-up) information flow. |
| CV | Coefficient of Variation | Intra-cluster similarity to measure the accuracy of unsupervised classification models based on clusters |
| CV | Computer Vision | A field of AI enabling computers to "see" and interpret information from digital images or videos. |
| CV | Cross Validation | Resampling method for training, validation and testing a model across different iterations on portions of the full data set. |
| CVPR | Computer Vision and Pattern Recognition | The premier annual computer vision conference; primary publication venue for visual attribution and watermarking methods. |
| ECCV | European Conference on Computer Vision | A major biennial computer vision conference; relevant publication venue for attribution and provenance methods. |
| FPN | Feature Pyramid Network | A neural network component, common in object detection, that builds multi-scale feature representations with rich semantics at all levels via lateral connections. |
| FWIoU | Frequency Weighted Intersection over Union | Metric in segmentation/object detection tasks. Weighted average of IoU's over classes, where weights depend on class frequency. |
| GLCM | Gray Level Co-occurrence Matrix | A statistical method for examining texture that considers the spatial relationship of pixels, used for feature extraction in image analysis. |
| GradCAM | GRADient-weighted Class Activation Mapping | A visualization technique for CNNs that uses the gradients flowing into the final convolutional layer to produce a coarse localization map highlighting important regions in the input image for predicting the concept. |
| ICCV | International Conference on Computer Vision | Major biennial computer vision conference; publication venue for visual watermarking and attribution methods. |
| IoU | Jaccard index (intersection over union) | Metric in segmentation/object detection tasks. Ratio of areas of intersection and union of two (segmentation) boxes, corresponding to e.g. prediction and label. |
| MIoU | Mean Intersection over Union | Metric in segmentation/object detection tasks. Mean of IoU's over classes. |
| MPA | Mean Pixel Accuracy | Metric in segmentation/object detection tasks. Average ratio of correctly classified pixels by class. |
| NCII | Non-Consensual Intimate Images | Images distributed without subject consent; a category of harmful training content subject to mandatory removal obligations. |
| NMS | Non Maximum Suppression | A technique used in Object Detection for removing redundand overlapping bounding boxes |
| NST | Neural Style Transfer | A method that uses of deep neural networks for transfering style. |
| PA | Pixel Accuracy | Metric in segmentation/object detection tasks. Ratio of correctly classified over total number of pixels. |
| RANSAC | RANdom SAmple Consensus | A robust iterative algorithm that estimates model parameters from data containing large proportions of outliers by fitting models to random minimal subsets. |
| RGB | Red Green Blue color model | An additive color model used for display of images |
| RICNN | Rotation Invariant Convolutional Neural Network | A CNN variant designed to produce consistent feature representations regardless of input rotation, achieved through architectural or training-based strategies. |
| ROI | Region Of Interest | A defined subset of an image or dataset designated for focused processing or analysis, widely used in object detection, medical imaging, and feature extraction. |
| SSD | Single-Shot Detector | A type of object detector that consists of a single stage. Some examples are YOLO RetinaNet and EfficientDet. |
| ST | Style Transfer | An algorithm that allows to tranfer properties of one object to another (i.e. transfer painitning style to a photography). |
| VGG | Visual Geometry Group | Popular deep convolutional model designed for classification. |
| ViT | Vision Transformer | A transformer architecture applied to image patches; used as an evaluation backbone for training data attribution methods in computer vision. |
| YOLO | You Only Look Once | Fast object detection algorithm. |

## Generative Models

| Acronym | Full Name | Definition |
|---------|-----------|------------|
| DCGAN | Deep Convolutional Generative Adversarial Network | A type of GAN that uses convolutional and convolutional-transpose layers in its discriminator and generator, respectively, primarily for image generation. |
| GAN | Generative Adversarial Network | A deep-learning-based generative model using "indirect" training through the discriminator another neural network that is able to tell how much an input is "realistic" which itself is also being updated dynamically. |
| MAF | Masked Autoregressive Flows | A type of normalizing flow model for density estimation that uses masked autoregressive transformations (like MADE) to ensure invertibility and efficient computation. |
| NF | Normalizing Flow | A class of generative models that transform a simple base distribution into a complex target distribution via a sequence of invertible, differentiable mappings. |
| SGVB | Stochastic Gradient Variational Bayes | A variational inference training method using the reparameterization trick to enable low-variance gradient estimation through stochastic latent variables in VAEs. |
| TGAN | Temporal Generative Adversarial Network | A GAN architecture designed to generate realistic temporal sequences such as video or time-series data by modeling both spatial content and temporal dynamics. |
| VAE | Variational AutoEncoder | An artificial neural network architecture belonging to the families of probabilistic graphical models and variational Bayesian methods. |
| VQ-VAE | Vector Quantized Variational Autoencoders | A VAE variant using a discrete, vector-quantized latent space instead of a continuous one, enabling high-fidelity image, audio, and video generation. |

## Reinforcement Learning

| Acronym | Full Name | Definition |
|---------|-----------|------------|
| CALA | Continuous Action-set Learning Automata | A type of reinforcement learning agent operating in environments with continuous (non-discrete) action spaces. |
| DPO | Direct Preference Optimization | A simplified alternative to RLHF for aligning language models with human preferences using a binary cross-entropy objective over preference pairs. |
| DQN | Deep Q-Network | A reinforcement learning algorithm that uses a deep neural network to approximate the Q-value (action-value) function. |
| FALA | Finite Action-set Learning Automata | A type of reinforcement learning agent operating in environments with a finite number of discrete actions. |
| MDP | Markov Decision Process | A mathematical framework for sequential decision-making using states, actions, transition probabilities, and rewards; the theoretical foundation of reinforcement learning. |
| POMDP | Partially Observable Markov Decision Process | An MDP extension for partially observable environments where the agent maintains a probability distribution (belief state) over possible hidden states to guide decisions. |
| RL | Reinforcement Learning | A machine learning paradigm where an agent learns optimal behavior through trial-and-error interactions with an environment, guided by reward signals. |
| RLHF | Reinforcement learning from human feedback | A fine-tuning technique that trains AI models using human preference comparisons to learn a reward signal, then applies RL to align behavior with human values. |
| SARSA | State-Action-Reward-State-Action | An on-policy TD reinforcement learning algorithm that updates Q-values using the action actually taken by the agent's policy rather than the greedy optimal action. |
| TD | Temporal Difference | A family of RL algorithms learning value functions by bootstrapping from subsequent estimates, combining the strengths of Monte Carlo and dynamic programming approaches. |
| TRPO | Trust Region Policy Optimization | A policy gradient RL algorithm constraining each parameter update to stay within a trust region, ensuring stable and monotonically improving policy optimization. |

## Optimization & Training

| Acronym | Full Name | Definition |
|---------|-----------|------------|
| ADA | AdaBoosted Decision Trees | Using AdaBoost to improve performance in decision trees. |
| AdaBoost | Adaptive Boosting | A statistical classification meta-algorithm that can be used in conjunction with many other types of learning algorithms to improve performance. |
| AdR | AdaBoostRegressor | Using AdaBoost to improve performance in regression. |
| AIWPSO | Adaptive Inertia Weight Particle Swarm Optimization | An optimization algorithm using an individual search ability (ISA) to indicate whether each particle lacks global exploration or local exploitation abilities in each dimension. |
| BFGS | Broyden-Fletcher-Goldfarb-Shanno | A quasi-Newton optimization algorithm; used in second-order influence function computation as an alternative to conjugate gradient for small-scale settings. |
| BP | BackPropagation | A widely used algorithm for training feedforward neural networks by propagating errors backward through the network. |
| BPTT | Backpropagation Through Time | A gradient-based technique for training certain types of recurrent neural networks (e.g., LSTMs) by unrolling the network through time steps. |
| CE | Cross-Entropy | A common loss function used in classification tasks, measuring the difference between predicted probability distributions and the true distribution. |
| CG | Conjugate Gradient | An iterative algorithm for solving linear systems; the standard method for approximating inverse Hessian-vector products in influence function computation without forming the full Hessian. |
| DAAF | Data Augmentation and Auxiliary Feature | A technique possibly involving using auxiliary features alongside data augmentation to improve model training. |
| DE | Differential Evolution | A metaheuristic optimization algorithm belonging to the family of evolutionary algorithms, used for finding global optima, particularly in continuous spaces. |
| EK-FAC | Eigenvalue-corrected Kronecker-Factored Approximate Curvature | A second-order optimization approximation used to compute scalable influence function estimates by approximating the inverse Hessian using a Kronecker product structure with eigenvalue correction. |
| FIM | Fisher Information Matrix | A matrix capturing the curvature of the log-likelihood function with respect to model parameters; used to construct tractable inverse Hessian approximations in influence function computation. |
| GA | Genetic Algorithm | A metaheuristic optimization algorithm inspired by natural selection, using concepts like mutation, crossover, and selection to evolve solutions. |
| GA | Gradient Ascent | An optimization technique that maximizes rather than minimizes an objective; used in some machine unlearning methods to increase loss on forget-set examples. |
| GD | Gradient Descent | An optimization algorithm used to minimize some function by iteratively moving in the direction of steepest descent as defined by the negative of the gradient. |
| GGN | Gauss-Newton Hessian | An approximation to the Hessian of the training loss that is guaranteed positive semi-definite; commonly used as an alternative to the full Hessian in influence function approximations. |
| IHVP | Inverse Hessian-Vector Product | The core computational primitive in influence function estimation; approximated using conjugate gradient, LiSSA, or Kronecker-factored methods to avoid full Hessian inversion. |
| LiSSA | Linear time Stochastic Second-order Algorithm | An iterative algorithm for approximating inverse Hessian-vector products; standard computational method for scalable influence function estimation. |
| LoRA | Low-Rank Adaptation | A parameter-efficient fine-tuning method that approximates weight updates as low-rank matrix products; relevant to attribution under fine-tuning because LoRA modifies only a subset of effective parameters. |
| PEFT | Parameter-Efficient Fine-Tuning | A family of methods for adapting pre-trained models using a small number of additional parameters; includes LoRA, prefix tuning, and adapter layers. |
| SBO | Structured Bayesian optimization | A Bayesian optimization approach that exploits known structural properties of the objective (e.g., decomposability or constraints) to improve search efficiency. |
| SCH | Stochastic convex hull | A probabilistic or randomized method for computing or approximating the convex hull of a point set, used in optimization and geometry-based machine learning. |
| SGD | Stochastic Gradient Descent | An optimization algorithm updating model parameters using gradients estimated from a single example or small mini-batch per step, enabling efficient large-scale learning. |
| SGLD | Stochastic Gradient Langevin Dynamics | A sampling algorithm combining SGD with Langevin noise; used in Bayesian influence function variants and approximate posterior sampling for attribution uncertainty. |
| SMBO | Sequential Model-Based Optimization | A hyperparameter optimization strategy that fits a probabilistic surrogate model of the objective and uses it to select the most promising configurations to evaluate. |
| STDA | Style Transfer Data Augmentation | A method using style transfer to augment dataset. |
| TDA | Targeted Data Augmentation | A data augmentation strategy concentrating augmentation effort on underrepresented or hard-to-classify examples to address class imbalance or improve targeted robustness. |
| TDA | Training Data Attribution | The broader problem class of determining which training examples are responsible for specific model behaviors; synonymous with data attribution (DA) in this research. |
| XGBoost | eXtreme Gradient Boosting | An efficient, regularized gradient boosting implementation known for speed, scalability, and strong performance on structured and tabular data tasks. |

## Statistical & Classical ML Methods

| Acronym | Full Name | Definition |
|---------|-----------|------------|
| ACE | Alternating conditional expectation (ACE) algorithm | An algorithm to find the optimal transformations between the response variable and predictor variables in regression analysis. |
| BDT | Boosted Decision Tree | An ensemble learning method combining multiple decision trees, typically using boosting algorithms like AdaBoost or Gradient Boosting. |
| BN | Bayesian Network | A probabilistic graphical model that represents a set of variables and their conditional dependencies via a directed acyclic graph (DAG). |
| BPMF | Bayesian Probabilistic Matrix Factorization | A probabilistic approach to matrix factorization, often used in recommender systems, incorporating Bayesian inference. |
| BRR | Bayesian Ridge Regression | A regression technique that incorporates Bayesian methods with Ridge Regression (L2 regularization). |
| CART | Classification And Regression Tree | An algorithm used to build decision trees for both classification and regression tasks by recursively partitioning the data space. |
| CMMs | Conditional Markov Model | A graphical model for sequence labeling that combines features of hidden Markov models (HMMs) and maximum entropy (MaxEnt) models. Also known as maximum-entropy Markov model (MEMM). |
| CRFs | Conditional Random Fields | A class of statistical modeling methods often used for structured prediction tasks like sequence labeling (e.g., in NLP), modeling conditional probabilities. |
| DBSCAN | Density-Based Spatial Clustering of Applications with Noise | A density-based clustering algorithm that groups together points closely packed together, marking outliers as noise. |
| DT | Decision Tree | A supervised learning model using a tree-like structure of decisions and their possible consequences to classify or regress data. |
| EM | Expectation maximization | An iterative method for finding maximum likelihood or MAP estimates of parameters in statistical models with latent (unobserved) variables. |
| EM | Exact Match | An evaluation metric that scores a prediction correct only if it exactly matches the reference string; used for question-answering attribution evaluation. |
| EMD | Entropy Minimization Discretization | A method for discretizing continuous features by finding split points that minimize the class information entropy within the resulting intervals. |
| EXT | Extremely Randomized Trees | An ensemble learning method similar to Random Forests, but introduces more randomness in selecting node splits (both attribute and split point). |
| FCM | Fuzzy C-Means | A clustering algorithm allowing data points to belong to multiple clusters with varying degrees of membership (fuzziness). |
| GAM | Generalized Additive Model | A regression model where the output variable depends linearly on unknown smooth functions of predictor variables, allowing for non-linear relationships. |
| GAM | Global Attribution Mapping | An explainability method, often used with CNNs, to identify which input regions (e.g., pixels in an image) contribute most significantly to a specific output class. |
| GAMLSS | Generalized Additive Models for Location, Scale and Shape | An extension of GAMs allowing not just the mean (location) but also other distribution parameters (like scale/variance and shape/skewness) to be modeled with additive predictors. |
| GBRCN | Gradient-Boosting Random Convolutional Network | A model likely combining gradient boosting techniques with randomly initialized convolutional features, possibly for time-series or image analysis. |
| GMM | Gaussian mixture model | A probabilistic model that assumes all the data points are generated from a mixture of a finite number of Gaussian distributions with unknown parameters. |
| GPR | Gaussian Process Regression | A non-parametric, Bayesian approach to regression where the model learns a distribution over functions, providing uncertainty estimates along with predictions. |
| HCA | Hierarchical Clustering Analysis | A method of cluster analysis which seeks to build a hierarchy of clusters, either agglomerative (bottom-up) or divisive (top-down). |
| HDP | Hierarchical Dirichlet process | A non-parametric Bayesian approach for modeling grouped data, often used in topic modeling to allow for an infinite number of topics shared across groups. |
| hLDA | Hierarchical Latent Dirichlet allocation | An extension of LDA that organizes topics into a hierarchy, allowing documents to be associated with paths of topics at different levels of granularity. |
| HMM | Hidden Markov Model | A statistical Markov model in which the system being modeled is assumed to be a Markov process with unobserved (hidden) states, commonly used for sequential data like speech or NLP. |
| ID3 | Iterative Dichotomiser 3 | An early algorithm used to generate a decision tree from a dataset, using information gain to select the best attribute at each step. |
| KDE | Kernel Density Estimation | A non-parametric way to estimate the probability density function of a random variable by placing kernels (usually Gaussian) over each data point. |
| k-NN | k-Nearest Neighbor | A non-parametric, instance-based learning algorithm where classification or regression is based on the majority vote or average of the 'k' nearest neighbors in the feature space. |
| kNN | k-Nearest Neighbours | A non-parametric supervised learning method used for classification and regression. (Synonym for k-NN) |
| KNN | K-Nearest Neighbors | A non-parametric retrieval method; adapted in datamodel-based attribution to identify training examples with similar gradient features to a target output. |
| KRR | Kernel Ridge Regression | A combination of Ridge Regression (L2-regularized linear regression) with the kernel trick, allowing it to learn non-linear functions in high-dimensional spaces. |
| LDADE | Latent Dirichlet Allocation Differential Evolution | Likely a hybrid approach combining LDA for topic modeling with Differential Evolution, possibly for optimizing LDA parameters or using topics within the DE process. |
| LightGBM | Light Gradient-Boosting Machine | Gradient boosting framework that uses tree based learning algorithms, originally developed by Microsoft. Known for efficiency and speed. |
| LVQ | Learning Vector Quantization | A prototype-based supervised classification algorithm, related to Self-Organizing Maps (SOM), that uses competitive learning to move prototypes towards or away from training instances based on class labels. |
| MAP | Maximum A Posteriori (MAP) Estimation | A method for estimating unknown parameters in Bayesian statistics, finding the mode (peak) of the posterior distribution, incorporating prior knowledge. |
| MARS | Multivariate Adaptive Regression Spline | Non-parametric regression technique, extends linear models. Note that the name is trademarked, open source implementations are often called "EARTH". |
| MART | Multiple Additive Regression Tree | Another name for Gradient Boosted Decision Trees (GBDT), particularly associated with Friedman's original work, emphasizing the additive nature of the tree ensemble. |
| MaxEnt | Maximum Entropy | Entropy a scientific concept as well as a measurable physical property that is most commonly associated with a state of disorderrandomnessor uncertainty. |
| MCMC | Markov Chain Monte Carlo | A class of algorithms for sampling from a probability distribution by constructing a Markov chain that has the desired distribution |
| MLE | Maximum Likelihood Estimation | A statistical method for estimating model parameters by finding values that maximize the probability of the observed training data under the assumed model. |
| NB | Na ̈ıve Bayes | A probabilistic classifier applying Bayes' theorem with a strong feature independence assumption, widely used for text classification and spam filtering. |
| NBKE | Na ̈ıve Bayes with Kernel Estimation | An extension of Naïve Bayes that uses kernel density estimation instead of parametric distributions for continuous features, providing greater modeling flexibility. |
| NCC | Nearest Class Center | A classification method assigning examples to the closest class centroid; used in machine unlearning evaluation. |
| OLR | Ordinary Linear Regression | A standard linear regression model estimating the linear relationship between a dependent variable and one or more predictors via least squares minimization. |
| OLS | Ordinary Least Squares | A method for fitting a linear regression model by minimizing the sum of squared differences between observed and model-predicted values. |
| PACO | Poisson Additive Co-Clustering | A co-clustering model that uses a Poisson distribution with additive block structure to simultaneously cluster both rows and columns of a count data matrix. |
| PMF | Probabilistic Matrix Factorization | A collaborative filtering method that factorizes a user-item rating matrix into low-dimensional latent user and item factor matrices using probabilistic modeling. |
| PYTM | Pitman | A non-parametric Bayesian topic model using the Pitman-Yor process to better capture the power-law frequency distribution of words compared to standard LDA. |
| REPTree | Reduced Error Pruning Tree | A decision tree learner that uses information gain for split selection and reduced-error pruning to build a compact tree that is less prone to overfitting. |
| RF | Random Forest | An ensemble method training many decision trees on random data and feature subsets, aggregating their predictions for improved accuracy and robustness. |
| RIPPER | Repeated Incremental Pruning to Produce Error Reduction | A rule induction algorithm that generates a compact set of classification rules by iteratively growing and pruning rules to minimize validation error. |
| RLFM | Regression based latent factors | A recommendation model that uses regression on observed user and item features to inform or initialize latent factor matrices in a collaborative filtering framework. |
| RR | Ridge Regression | A regularized linear regression technique adding an L2 penalty on coefficient magnitudes to reduce overfitting and stabilize estimates when features are correlated. |
| SBM | Stochastic block model | A generative random graph model assigning nodes to latent communities and modeling edge probabilities by community membership pairs, used for community detection. |
| SGBoost | Stochastic Gradient Boosting | A gradient boosting variant that trains each successive tree on a random subsample of the training data, introducing stochasticity to reduce variance and improve generalization. |
| SHLLE | Supervised Hessian Locally Linear Embedding | A supervised extension of Hessian LLE incorporating class label information during embedding to better preserve discriminative structure in the low-dimensional space. |
| SSVM | Smooth support vector machine | An SVM variant using smooth approximations of the hinge loss to enable unconstrained gradient-based optimization and faster convergence via Newton-type methods. |
| SVD | Singing Voice Detection | A music information retrieval task detecting the presence of singing voice within audio segments, typically framed as binary frame-level classification. |
| SVD | Singular Value Decomposition | A matrix factorization decomposing any matrix into U, Σ, and Vᵀ components, widely used for dimensionality reduction, noise filtering, and recommendation systems. |
| SVM | Support Vector Machine | Supervised learning models with associated learning algorithms that analyze data for classification and regression analysis. |
| SVR | Support Vector Regression | Supervised learning models with associated learning algorithms that analyze data for regression analysis. |
| THAID | THeta Automatic Interaction Detection | An early decision tree algorithm that automatically detects interactions among predictor variables by maximizing a discrimination measure at each recursive partition step. |
| t-SNE | t-distributed stochastic neighbor embedding | A nonlinear dimensionality reduction method for visualization that models pairwise similarities using a heavy-tailed t-distribution in low-dimensional space to prevent crowding. |
