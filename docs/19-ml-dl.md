---
id: 19-ml-dl
title: Machine Learing & Deep Learning
---

## Courses, Libraries & future trends 

## Effectively Learning ML & DL
Top class Courses screend after careful examination from vast sea of available courses on Internet on ML/DL .

### 1. Hongkong University professor course
  Using Pytorch, slides and Youtube videos

### 2. Fast.ai course
  Using ...

### 3. Deep Reinforcemnet Learning Book
  Has stock market project 


## Advancements in Deep Learning 
Following are major advancements in ML/Deep Learing models.

### 1. BERT: language model for NLP 

BERT Explained: State of the art [language model for NLP](https://towardsdatascience.com/bert-explained-state-of-the-art-language-model-for-nlp-f8b21a9b6270)

 It has caused a stir in the Machine Learning community by presenting state-of-the-art results in a wide variety of NLP tasks, including `Question Answering` (SQuAD v1.1), `Natural Language Inference` (MNLI), and others.

- Microsoft makes [Google’s BERT NLP model better](https://venturebeat.com/2019/05/16/microsoft-makes-googles-bert-nlp-model-better/)

- TensorFlow code and [pre-trained models for BERT](https://github.com/google-research/bert)

 > BERT’s key technical innovation is `applying` the bidirectional training of Transformer, a popular `attention model, to language modelling`. This is in contrast to previous efforts which looked at a text sequence either from left to right or combined left-to-right and right-to-left training. The paper’s results show that a language model which is bidirectionally trained can have a deeper sense of language context and flow than single-direction language model.


### 2. Habitat: A simulation platform for embodied AI research

- From a [robot asked to “grab my phone from the desk upstairs”](https://ai.facebook.com/blog/open-sourcing-ai-habitat-an-simulation-platform-for-embodied-ai-research/) to a device that helps its visually impaired wearer navigate an unfamiliar subway system, the `next generation of AI-powered assistants will need to demonstrate a broad range of abilities`. Many researchers believe the most effective way to develop these skills is to focus on embodied AI, which uses interactive environments to ground systems’ training in the real world, `rather than relying on static data sets`. 
  
- AI Habitat enables [training of embodied AI agents (virtual robots) in a highly photorealistic & efficient 3D simulator](https://medium.com/worasuchad/ai-habitat-4e9475a0275c), before transferring the learned skills to reality. This empowers a paradigm shift from ‘internet AI’ based on static datasets (e.g. ImageNet, COCO, VQA) to embodied AI where agents act within realistic environments, bringing to the fore active perception, long-term planning, learning from interaction, and holding a dialog grounded in an environment.

- Successful [real-world robotic applications call for a variety of skills](https://medium.com/ai%C2%B3-theory-practice-business/habitat-training-ground-for-embodied-ai-agents-4d1eea28ee3a) including visual perception, scene understanding, language understanding, and proper navigation skills.
- I wouldn’t say that tables have wholly turned, `but while datasets have been significant drivers` in computer vision and natural language processing progress, `richly built simulators may soon start assuming their roles`.

## Large & Complex ML/DL Libraries
we list here, some of the complex ML/DL libraries that are open sourced. Studying these libraries enable students to gain knowlege on cutting edge reserach in the said fields.

### 1.  SPTAG: A library for fast approximate nearest neighbor search

> A distributed approximate nearest neighborhood search (ANN) library which provides a high quality vector index build, search and distributed online serving toolkits for large scale vector search scenario.

Microsoft open-sources [key Bing Search search algorithm](https://venturebeat.com/2019/05/15/microsoft-open-sources-key-bing-search-search-algorithm/)


## ML/DL Business Applications

### 1. Trustpilot : Customer Review Analysis platform

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
  
### Standardizing embodied AI research through open, modular design

Facebook AI has explored the potential of embodied AI for years, including creating agents that communicate with each other to find their way through simulated NYC streets and agents that navigate virtual indoor environments in order to answer questions. `These efforts shared the common goal of developing versatile, problem-solving AI that leverages progress in traditionally distinct research areas, such as using natural language processing (NLP) to communicate with humans or agents, computer vision (CV) to perceive simulated environments, and reinforcement learning (RL) techniques that power the decision-making to navigate real-world spaces`. 

But our work mirrored the larger state of embodied AI research — `with no standard platform available to easily run experiments and measure results against others, new projects often required starting from scratch`. Given the resource-intensive nature of building and rendering simulated environments, this made progress slower compared with subfields whose standard benchmarks — such as ImageNet and COCO — enable collaboration and rapid iteration.

### Habitat Challenge
Launching Habitat Challenge, [a field test for our embodied platform](https://ai.facebook.com/blog/open-sourcing-ai-habitat-an-simulation-platform-for-embodied-ai-research/)

- To demonstrate the utility of AI Habitat’s modular approach and emphasis on 3D photo-realism, we held the Habitat Challenge, a competition that focused on evaluating the specific provided task of goal-directed visual navigation. Unlike traditional challenges where people upload predictions based on a task related to a given benchmark such as ImageNet or VQA, `this one required participants to upload code. The code was run on new environments that their agents had not seen before`, and we're excited to announce the top-performing teams: `Team Arnold (a group of researchers from CMU) and Team Mid-Level Vision (a group of researchers from Berkeley and Stanford)`.

- The information that we shared for the challenge functioned as the task layer of AI Habitat’s three-layer stack. As researchers use the platform for their own experiments, they’ll create and apply new task parameters to complete the stack. `For our competition, agents were simulated as cylindrical, 1.5-meter-tall robots that could turn left or right in 10-degree increments and move forward 0.25 meter at a time. Stopping within 0.2 meter was considered a successful run`, with more detailed evaluation based on the total length of its path.

- [Challenge page](https://aihabitat.org/challenge/#participation)



