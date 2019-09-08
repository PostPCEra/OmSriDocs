---
id: 19-ml-dl
title: ML & DL
---

## Courses, Libraries & future trends 

## Effectively Learning ML & DL
Top class Courses screend after careful examination from vast sea of available courses on Internet on ML/DL .

### 1. Hongkong University professor course
  Using Pytorch, slides and Youtube videos

### 2. Fast.ai course
  Using ...

### 3. ML Problem Framing!
  google Course 
  
  Introduction to [Machine Learning Problem Framing!](https://developers.google.com/machine-learning/problem-framing/?utm_source=googleAI&utm_medium=card-image&utm_campaign=training-hub&utm_term=&utm_content=problem-framing)

  Data Preparation and [Feature Engineering in ML](https://developers.google.com/machine-learning/data-prep/)

 Testing and [Debugging in Machine Learning](https://developers.google.com/machine-learning/testing-debugging/)

### 4. Deep Reinforcemnet Learning Book
  Has stock market project 


## Interesting Libraries & Systems
Some good ML/DL Systems & Libraries ....

### Lugwig 
  Ludwig : [Machine Learning with No Code](https://www.youtube.com/watch?v=w45t3itM5NM) -- by Uber

  Ludwig [intro](https://uber.github.io/ludwig/getting_started/)

### open AI Gym

  Getting [Started With OpenAI Gym](https://www.youtube.com/watch?v=8MC3y7ASoPs) -- code demo youtube
  
  [open AI Gym](https://gym.openai.com/)

  - Gym is a toolkit for developing and comparing reinforcement learning algorithms. It supports teaching agents everything from walking to playing games like Pong or Pinball.
  - We provide the environment; you provide the algorithm.You can write your agent using your existing numerical computation library, such as TensorFlow or Theano.




## Advancements in Deep Learning 
Following are major advancements in ML/Deep Learing models.

### 0. AlphaGO & AlphaGoZero

dThe 3 Tricks That Made [AlphaGo Zero Work](https://hackernoon.com/the-3-tricks-that-made-alphago-zero-work-f3d47b6686ef)

Dylan's blog [AlphaGo Zero demystified](https://dylandjian.github.io/alphago-zero/) -- github [code base](https://github.com/dylandjian/superGo)

miniGo : An open-source implementation [of the AlphaGoZero algorithm](https://github.com/tensorflow/minigo)

Look at these [simple projects to Learn AlphaGO methods](https://github.com/search?o=desc&q=alphago&s=stars&type=Repositories)
- AlphaZero_Gomoku : An implementation of the AlphaZero algorithm for Gomoku (also called Gobang or Five in a Row)

- chess-alpha-zero: Chess reinforcement learning by AlphaGo Zero methods.

- alpha-zero-general: A clean implementation based on AlphaZero for any game in any framework + tutorial + Othello/Gobang/TicTacToe/Connect4




### 1. BERT: A language model for NLP 

BERT Explained: State of the art [language model for NLP](https://towardsdatascience.com/bert-explained-state-of-the-art-language-model-for-nlp-f8b21a9b6270)

 It has caused a stir in the Machine Learning community by presenting state-of-the-art results in a wide variety of NLP tasks, including `Question Answering` (SQuAD v1.1), `Natural Language Inference` (MNLI), and others.

- Microsoft makes [Google’s BERT NLP model better](https://venturebeat.com/2019/05/16/microsoft-makes-googles-bert-nlp-model-better/)

- TensorFlow code and [pre-trained models for BERT](https://github.com/google-research/bert)
- A nice blog post explaining [recent progress in NLP ](https://ai.facebook.com/blog/new-advances-in-natural-language-processing-to-better-connect-people/)and translation and some Facebook AI's contributions.BERT, RoBERTa, backtranslation, GLUE, SuperGLUE, WMT explained....

- [Parl.ai](https://parl.ai/) : A unified platform for sharing, training and evaluating dialogue models across many tasks.


 > BERT’s key technical innovation is `applying` the bidirectional training of Transformer, a popular `attention model, to language modelling`. This is in contrast to previous efforts which looked at a text sequence either from left to right or combined left-to-right and right-to-left training. The paper’s results show that a language model which is bidirectionally trained can have a deeper sense of language context and flow than single-direction language model.


### 2. Habitat: embodied AI Simmulator

Habitat: A simulation platform for embodied AI research
- From a [robot asked to “grab my phone from the desk upstairs”](https://ai.facebook.com/blog/open-sourcing-ai-habitat-an-simulation-platform-for-embodied-ai-research/) to a device that helps its visually impaired wearer navigate an unfamiliar subway system, the `next generation of AI-powered assistants will need to demonstrate a broad range of abilities`. Many researchers believe the most effective way to develop these skills is to focus on embodied AI, which uses interactive environments to ground systems’ training in the real world, `rather than relying on static data sets`. 
  
- AI Habitat enables [training of embodied AI agents (virtual robots) in a highly photorealistic & efficient 3D simulator](https://medium.com/worasuchad/ai-habitat-4e9475a0275c), before transferring the learned skills to reality. This empowers a paradigm shift from ‘internet AI’ based on static datasets (e.g. ImageNet, COCO, VQA) to embodied AI where agents act within realistic environments, bringing to the fore active perception, long-term planning, learning from interaction, and holding a dialog grounded in an environment.

- Successful [real-world robotic applications call for a variety of skills](https://medium.com/ai%C2%B3-theory-practice-business/habitat-training-ground-for-embodied-ai-agents-4d1eea28ee3a) including visual perception, scene understanding, language understanding, and proper navigation skills.
- I wouldn’t say that tables have wholly turned, `but while datasets have been significant drivers` in computer vision and natural language processing progress, `richly built simulators may soon start assuming their roles`.


### 3. Deep learning protein-folding
> Alphafold: Deep learning makes its mark on protein-structure prediction.

The race to crack one of biology’s grandest challenges — predicting the 3D structures of proteins from their amino-acid sequences — is intensifying, thanks to new artificial-intelligence (AI) approaches.
https://www.nature.com/articles/d41586-019-01357-6

At the end of last year, `Google’s AI firm DeepMind debuted an algorithm called AlphaFold`, which combined two techniques that were emerging in the field and beat established contenders in a competition on protein-structure prediction by a surprising margin. 

And in April this year, a US researcher revealed an algorithm that uses a totally different approach. He claims his AI is up to `one million times faster` at predicting structures than DeepMind’s, although probably not as accurate in all situations.


These approaches are cheaper and faster than existing lab techniques such as X-ray crystallography, and the knowledge could help researchers to better understand diseases and design drugs. `“There’s a lot of excitement about where things might go now,”` says John Moult, a biologist at the University of Maryland in College Park and the founder of the biennial competition, called `Critical Assessment of protein Structure Prediction (CASP), where teams are challenged to design computer programs that predict protein structures from sequences.`

But he says that because his algorithm uses a mathematical function to calculate protein structures in a single step — rather than in two steps like AlphaFold, which uses the similar structures as groundwork in the first step — it can predict structures in milliseconds rather than hours or days.

`“AlQuraishi’s approach is very promising. It builds on advances in deep learning as well as some new tricks AlQuraishi has invented,”` says Ian Holmes, a computational biologist at the University of California, Berkeley. `“It might be possible that, in the future, his idea can be combined with others to advance the field,”` says Jinbo Xu, a computer scientist at the Toyota Technological Institute at Chicago, Illinois, who competed at CASP13.

### 4. GAN & StyledGAN

Explained: A Style-Based Generator Architecture for GANs - [Generating and Tuning Realistic Artificial Faces](https://towardsdatascience.com/explained-a-style-based-generator-architecture-for-gans-generating-and-tuning-realistic-6cb2be0f431)


How to Generate Game of [Thrones Characters Using StyleGAN](https://nanonets.com/blog/stylegan-got/)

## Large & Complex ML/DL Libraries
we list here, some of the complex ML/DL libraries that are open sourced. Studying these libraries enable students to gain knowlege on cutting edge reserach in the said fields.

### 1.  SPTAG: MS Bing search open sourced 

SPTAG: A library for fast approximate nearest neighbor search

> A distributed approximate nearest neighborhood search (ANN) library which provides a high quality vector index build, search and distributed online serving toolkits for large scale vector search scenario.

Microsoft open-sources [key Bing Search search algorithm](https://venturebeat.com/2019/05/15/microsoft-open-sources-key-bing-search-search-algorithm/)


### 2.  Deepchem: Drug Discovery platform
> Democratizing Deep-Learning for Drug Discovery, Quantum Chemistry, Materials Science and Biology https://deepchem.io/

> What is DeepChem?

DeepChem is a python library that provides [a high quality open-source toolchain for deep-learning in drug discovery](https://github.com/deepchem/deepchem), materials science, quantum chemistry, and biology.

> About Us

DeepChem is possible due to notable contributions from many people including Peter Eastman, Evan Feinberg, Joe Gomes, Karl Leswing, Vijay Pande, Aneesh Pappu, Bharath Ramsundar and Michael Wu (alphabetical ordering). `DeepChem was originally created by Bharath Ramsundar with encouragement and guidance from Vijay Pande.`

DeepChem started as a Pande group project at Stanford, and is now developed by many academic and industrial collaborators. DeepChem actively encourages new academic and industrial groups to contribute!



### 3.  ProteinNet : protein folding paltform

ProteinNet : Standardized data set for machine learning of protein folding structure

ProteinNet created by Mohammed AlQuraishi, [a biologist at Harvard Medical School in Boston](https://www.nature.com/articles/d41586-019-01357-6) who developed faster DL algoritms than Google AlphaFold.

#### [Motivation](https://github.com/aqlaboratory/proteinnet) 
Protein structure prediction is one of the central problems of biochemistry. While the problem is well-studied within the biological and chemical sciences, it is less well represented within the machine learning community. We suspect this is due to two reasons: `1) a high barrier to entry for non-domain experts, and 2) lack of standardization in terms of training / validation / test splits that make fair and consistent comparisons across methods possible.` 

If these two issues are addressed, protein structure prediction can become a major source of innovation in `ML research, alongside the canonical tasks of computer vision, NLP, and speech recognition`. Much like `ImageNet helped spur the development of new computer vision techniques, ProteinNet aims to facilitate ML research` on protein structure by providing a standardized data set, and standardized training / validation / test splits, that any group can use with minimal effort to get started.



## ML/DL Business Applications

### 1. APIs to train your customised needs

Nanonets.com : Counting [Cars In Parking Lots](https://nanonets.com/drone/counting-cars/)

By comparison, the same `3,000 spaces parking lot can be covered by a 15 minutes drone flight`. The drone flies along a pre-planned route over the parking lot collecting overhead images at regular intervals. `These images are then stitched together to form a huge orthomosaic image`. Nanonets web API can then be used to get the count of cars in the orthomosaic image created each hour. 

`Each orthomosaic image is processed within seconds` and the results are sent back to the server machine over the web. `1 human annotator then verifies the results of the API output and collates the results in his report.`

APIs to access a [trained model customised for your needs.](https://nanonets.com/#demo)

### 2. Trustpilot : Customer Review Analysis

Trustpilot : Customer Review Analysis platform

- Trustpilot has 700 employees globally, raised VC funding $110 M , [started applying ML/DL recently](https://venturebeat.com/2019/07/27/trustpilot-building-ai-for-your-company-means-not-falling-in-love/) . 
   
- How Staysure.co.uk maintains a Great TrustScore from 50,000 Reviews
Take the example of Staysure.co.uk, a UK-based insurance company that has collected over 50,000 reviews, most of which from happy customers. `They collect over 4,000 reviews per month`, which is almost impossible for any human to analyse and sort through.

- That’s why they chose to start using Trustpilot’s new AI tool - Review Insights - which analyses reviews almost instantly (to date, Trustpilot’s analysed 31 million reviews from various industries to deliver the best-in-class insights).

- Using the insights identified by the AI-powered tool, Staysure can now easily understand major customer concerns, and act to solve those issues before they become bigger problems.

![Trustpilot](/docs/assets/topic-switching-3.gif)



## Habitat: platform Details 

arXiv.org categorization: Computer Science > [Computer Vision and Pattern Recognition](https://arxiv.org/abs/1904.01201)

### Resarch paper
We present Habitat, a new platform for research in embodied artificial intelligence (AI). Habitat enables training embodied agents (virtual robots) in highly efficient photorealistic 3D simulation, before transferring the learned skills to reality. 

Specifically, [Habitat consists of the following:](https://arxiv.org/abs/1904.01201) 

- 1. Habitat-Sim: a flexible, high-performance 3D simulator with configurable agents, multiple sensors, and generic 3D dataset handling (with built-in support for SUNCG, Matterport3D, Gibson datasets). Habitat-Sim is fast -- when rendering a scene from the Matterport3D dataset, Habitat-Sim achieves several thousand frames per second (fps) running single-threaded, and can reach over 10,000 fps multi-process on a single GPU, which is orders of magnitude faster than the closest simulator. 
- 2. Habitat-API: a modular high-level library for end-to-end development of embodied AI algorithms -- defining embodied AI tasks (e.g. navigation, instruction following, question answering), 
- 3. configuring and training embodied agents (via imitation or reinforcement learning, or via classic SLAM), and benchmarking using standard metrics.
-  These large-scale engineering contributions enable us to answer scientific questions requiring experiments that were till now impracticable or `merely' impractical. 

3 Layers: [Habitat-Sim, Habitat-API & Configuring and training embodied agents] (https://ai.facebook.com/blog/open-sourcing-ai-habitat-an-simulation-platform-for-embodied-ai-research/)

- Habitat-Sim, with sits at the base of the stack and includes built-in support for existing 3D environment data sets, such as Gibson, Matterport3D. In addition to being widely compatible with existing 3D data sets, the simulator also renders these assets quickly: In benchmark tests, Habitat-Sim with multiple processes renders detailed scenes at `10,000 frames per second (FPS)` on a single GPU, compared with `a typical rate of 100 FPS` on other simulators.
- we’re also sharing `Replica, a data set of hyperrealistic 3D reconstructions of a staged apartment, retail store, and other indoor spaces` that were generated by a group of scientists within Facebook Reality Labs (FRL). 
- The second layer in AI Habitat’s software stack is `Habitat-API`, a high-level library for defining tasks such as visual navigation and question answering.
- The platform’s third and final layer is its most open-ended. `This is the concrete embodied task that systems are being asked to learn through simulation`. It’s also where users specify training and evaluation parameters, such as how difficulty might ramp across multiple runs and what metrics to focus on.
  
### embodied AI platform

Standardizing embodied AI research through open, modular design


Facebook AI has explored the potential of embodied AI for years, including creating agents that communicate with each other to find their way through simulated NYC streets and agents that navigate virtual indoor environments in order to answer questions. `These efforts shared the common goal of developing versatile, problem-solving AI that leverages progress in traditionally distinct research areas, such as using natural language processing (NLP) to communicate with humans or agents, computer vision (CV) to perceive simulated environments, and reinforcement learning (RL) techniques that power the decision-making to navigate real-world spaces`. 

But our work mirrored the larger state of embodied AI research — `with no standard platform available to easily run experiments and measure results against others, new projects often required starting from scratch`. Given the resource-intensive nature of building and rendering simulated environments, this made progress slower compared with subfields whose standard benchmarks — such as ImageNet and COCO — enable collaboration and rapid iteration.

### Habitat Challenge
Launching Habitat Challenge, [a field test for our embodied platform](https://ai.facebook.com/blog/open-sourcing-ai-habitat-an-simulation-platform-for-embodied-ai-research/)

- To demonstrate the utility of AI Habitat’s modular approach and emphasis on 3D photo-realism, we held the Habitat Challenge, a competition that focused on evaluating the specific provided task of goal-directed visual navigation. Unlike traditional challenges where people upload predictions based on a task related to a given benchmark such as ImageNet or VQA, `this one required participants to upload code. The code was run on new environments that their agents had not seen before`, and we're excited to announce the top-performing teams: `Team Arnold (a group of researchers from CMU) and Team Mid-Level Vision (a group of researchers from Berkeley and Stanford)`.

- The information that we shared for the challenge functioned as the task layer of AI Habitat’s three-layer stack. As researchers use the platform for their own experiments, they’ll create and apply new task parameters to complete the stack. `For our competition, agents were simulated as cylindrical, 1.5-meter-tall robots that could turn left or right in 10-degree increments and move forward 0.25 meter at a time. Stopping within 0.2 meter was considered a successful run`, with more detailed evaluation based on the total length of its path.

- [Challenge page](https://aihabitat.org/challenge/#participation)



