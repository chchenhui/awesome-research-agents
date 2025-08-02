# Awesome-Research-Agents🌟
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PR Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen)](https://github.com/chchenhui/awesome-research-agents/pulls)

This is a collection of papers, blogs and projects about research agents powered by large language models (LLMs).

This repository will be continuously updated to track the resources of LLM research agents.

## Table of Contents

- [📖 Papers](#papers)
  - [Scientific Discovery](#scientific-discovery)
  - [Idea Generation](#idea-generation)
  - [Literature Review](#literature-review)
  - [Research Engineering](#research-engineering)
  - [Paper Writing](#paper-writing)
  - [Research Assessment](#research-assessment)
- [🔧 Projects](#projects)

## 📖 Papers
```
format:
- [time] [title](paper link)
  - author1, author2, and author3...
  - publisher
  - code
  - experimental environments and datasets
```
### Scientific Discovery
- [Aug 2024] [The AI Scientist: Towards Fully Automated Open-Ended Scientific Discovery](https://arxiv.org/pdf/2408.06292)
  - Chris Lu, Cong Lu, Robert Tjarko Lange, Jakob Foerster, Jeff Clune, David Ha
  - https://github.com/SakanaAI/AI-Scientist
- [Nov 2024] [CycleResearcher: Improving Automated Research via Automated Review](https://arxiv.org/pdf/2411.00816)
  - Yixuan Weng, Minjun Zhu, Guangsheng Bao, Hongbo Zhang, Jindong Wang, Yue Zhang, Linyi Yang
  - https://github.com/zhu-minjun/Researcher
- [Jan 2025] [Agent Laboratory: Using LLM Agents as Research Assistants](https://arxiv.org/pdf/2501.04227)
  - Samuel Schmidgall, Yusheng Su, Ze Wang, Ximeng Sun, Jialian Wu, Xiaodong Yu, Jiang Liu, Zicheng Liu, Emad Barsoum
  - https://github.com/SamuelSchmidgall/AgentLaboratory
- [Feb 2025] [MLGym: A New Framework and Benchmark for Advancing AI Research Agents](https://arxiv.org/pdf/2502.14499)
  - Deepak Nathani, Lovish Madaan, Nicholas Roberts, Nikolay Bashlykov, Ajay Menon, Vincent Moens, Amar Budhiraja, Despoina Magka, Vladislav Vorotilov, Gaurav Chaurasia, Dieuwke Hupkes, Ricardo Silveira Cabral, Tatiana Shavrina, Jakob Foerster, Yoram Bachrach, William Yang Wang, Roberta Raileanu
- [Mar 2025] [AgentRxiv: Towards Collaborative Autonomous Research](https://arxiv.org/pdf/2503.18102)
  - Samuel Schmidgall, Michael Moor
- [Apr 2025] [PaperBench: Evaluating AI’s Ability to Replicate AI Research](https://arxiv.org/pdf/2504.01848)
  - Giulio Starace, Oliver Jaffe, Dane Sherburn, James Aung, Chan Jun Shern, Leon Maksin, Rachel Dias, Evan Mays, Benjamin Kinsella, Wyatt Thompson, Johannes Heidecke, Amelia Glaese, Tejal Patwardhan
  - https://github.com/openai/preparedness
- [Apr 2025] [The AI Scientist-v2: Workshop-Level Automated Scientific Discovery via Agentic Tree Search](https://arxiv.org/pdf/2504.08066)
  - Yutaro Yamada, Robert Tjarko Lange, Cong Lu, Shengran Hu, Chris Lu, Jakob Foerster, Jeff Clune, David Ha
  - https://github.com/SakanaAI/AI-Scientist-v2
- [Apr 2025] [Paper2Code: Automating Code Generation from Scientific Papers in Machine Learning](https://arxiv.org/pdf/2504.17192)
  - Minju Seo, Jinheon Baek, Seongyun Lee, Sung Ju Hwang
  - https://github.com/going-doer/Paper2Code
- [Jul 2025] [AI Research Agents for Machine Learning: Search, Exploration, and Generalization in MLE-bench](https://arxiv.org/pdf/2507.02554)
  - Edan Toledo, Karen Hambardzumyan, Martin Josifoski, Rishi Hazra, Nicolas Baldwin, Alexis Audran-Reiss, Michael Kuchnik, Despoina Magka, Minqi Jiang, Alisia Maria Lupidi, Andrei Lupu, Roberta Raileanu, Kelvin Niu, Tatiana Shavrina, Jean-Christophe Gagnon-Audet, Michael Shvartsman, Shagun Sodhani, Alexander H. Miller, Abhishek Charnalia, Derek Dunfield, Carole-Jean Wu, Pontus Stenetorp, Nicola Cancedda, Jakob Nicolaus Foerster, Yoram Bachrach
  - https://github.com/facebookresearch/aira-dojo
- [July 2025] [Open-ended Scientific Discovery via Bayesian Surprise](https://arxiv.org/pdf/2507.00310)
  - Dhruv Agarwal, Bodhisattwa Prasad Majumder, Reece Adamson, Megha Chakravorty, Satvika Reddy Gavireddy, Aditya Parashar, Harshit Surana, Bhavana Dalvi Mishra, Andrew McCallum, Ashish Sabharwal, Peter Clark

### Idea Generation
- [Apr 2024] [ResearchAgent: Iterative Research Idea Generation over Scientific Literature with Large Language Models](https://arxiv.org/pdf/2404.07738)
  - Jinheon Baek, Sujay Kumar Jauhar, Silviu Cucerzan, Sung Ju Hwang
- [Sep 2024] [Can LLMs Generate Novel Research Ideas? A Large-Scale Human Study with 100+ NLP Researchers](https://arxiv.org/pdf/2409.04109)
  - Chenglei Si, Diyi Yang, Tatsunori Hashimoto
  - https://github.com/NoviScl/AI-Researcher
- [Oct 2024] [Chain of Ideas: Revolutionizing Research Via Novel Idea Development with LLM Agents](https://arxiv.org/pdf/2410.13185)
  - Long Li, Weiwen Xu, Jiayan Guo, Ruochen Zhao, Xingxuan Li, Yuqian Yuan, Boqiang Zhang, Yuming Jiang, Yifei Xin, Ronghao Dang, Deli Zhao, Yu Rong, Tian Feng, Lidong Bing
  - https://github.com/DAMO-NLP-SG/CoI-Agent
- [Oct 2024] [SciPIP: An LLM-based Scientific Paper Idea Proposer ](https://arxiv.org/pdf/2410.23166)
  - Wenxiao Wang, Lihui Gu, Liye Zhang, Yunxiang Luo, Yi Dai, Chen Shen, Liang Xie, Binbin Lin, Xiaofei He & Jieping Ye
  - https://github.com/cheerss/SciPIP
- [Dec 2024] [Learning to Generate Research Idea with Dynamic Control](https://arxiv.org/pdf/2412.14626)
  - Ruochen Li, Liqiang Jing, Chi Han, Jiawei Zhou, Xinya Du
- [Dec 2024] [LLMs can realize combinatorial creativity: generating creative ideas via LLMs for scientific research](https://arxiv.org/pdf/2412.14141)
  - Tianyang Gu, Jingjin Wang, Zhihao Zhang, HaoHong Li
- [Jun 2025] [Predicting Empirical AI Research Outcomes with Language Models](https://arxiv.org/pdf/2506.00794?)
  - Jiaxin Wen, Chenglei Si, Yueh-han Chen, He He, Shi Feng
- [Jun 2025] [The Ideation-Execution Gap: Execution Outcomes of LLM-Generated versus Human Research Ideas](https://arxiv.org/pdf/2506.20803)
  - Chenglei Si, Tatsunori Hashimoto, Diyi Yang

### Literature Review
- [Jun 2024] [AutoSurvey: Large Language Models Can Automatically Write Surveys](https://arxiv.org/pdf/2406.10252v1)
  - Yidong Wang, Qi Guo, Wenjin Yao, Hongbo Zhang, Xin Zhang, Zhen Wu, Meishan Zhang, Xinyu Dai, Min Zhang, Qingsong Wen, Wei Ye, Shikun Zhang, Yue Zhang
- [Dec 2024] [LLMs for Literature Review: Are we there yet?](https://www.arxiv.org/pdf/2412.15249)
  - Shubham Agarwal, Gaurav Sahu, Abhay Puri, Issam H. Laradji, Krishnamurthy DJ Dvijotham, Jason Stanley, Laurent Charlin, Christopher Pal
- [Feb 2025] [SurveyX: Academic Survey Automation via Large Language Models](https://arxiv.org/pdf/2502.14776)
  - Xun Liang, Jiawei Yang, Yezhaohui Wang, Chen Tang, Zifan Zheng, Shichao Song, Zehao Lin, Yebin Yang, Simin Niu, Hanyu Wang, Bo Tang, Feiyu Xiong, Keming Mao, Zhiyu li

### Research Engineering
- [Oct 2023] [SWE-bench: Can Language Models Resolve Real-World GitHub Issues?](https://arxiv.org/pdf/2310.06770)
  - Carlos E. Jimenez, John Yang, Alexander Wettig, Shunyu Yao, Kexin Pei, Ofir Press, Karthik Narasimhan
  - https://github.com/swe-bench/SWE-bench
- [Oct 2023] [MLAgentBench: Evaluating Language Agents on Machine Learning Experimentation](https://arxiv.org/pdf/2310.03302)
  - Qian Huang, Jian Vora, Percy Liang, Jure Leskovec
  - https://github.com/snap-stanford/MLAgentBench
- [Feb 2024] [Benchmarking Data Science Agents](https://arxiv.org/pdf/2402.17168)
  - Yuge Zhang, Qiyang Jiang, Xingyu Han, Nan Chen, Yuqing Yang, Kan Ren
- [Jul 2024] [OpenHands: An Open Platform for AI Software Developers as Generalist Agents](https://arxiv.org/pdf/2407.16741)
  - Xingyao Wang, Boxuan Li, Yufan Song, Frank F. Xu, Xiangru Tang, Mingchen Zhuge, Jiayi Pan, Yueqi Song, Bowen Li, Jaskirat Singh, Hoang H. Tran, Fuqiang Li, Ren Ma, Mingzhang Zheng, Bill Qian, Yanjun Shao, Niklas Muennighoff, Yizhe Zhang, Binyuan Hui, Junyang Lin, Robert Brennan, Hao Peng, Heng Ji, Graham Neubig
  - https://github.com/All-Hands-AI/OpenHands
- [Jul 2024] [SciCode: A Research Coding Benchmark Curated by Scientists](https://arxiv.org/pdf/2407.13168)
  - Minyang Tian, Luyu Gao, Shizhuo Dylan Zhang, Xinan Chen, Cunwei Fan, Xuefei Guo, Roland Haas, Pan Ji, Kittithat Krongchon, Yao Li, Shengyan Liu, Di Luo, Yutao Ma, Hao Tong, Kha Trinh, Chenyu Tian, Zihan Wang, Bohao Wu, Yanyu Xiong, Shengzhu Yin, Minhui Zhu, Kilian Lieret, Yanxin Lu, Genglin Liu, Yufeng Du, Tianhua Tao, Ofir Press, Jamie Callan, Eliu Huerta, Hao Peng
  - https://github.com/scicode-bench/SciCode
- [Aug 2024] [CodeAgent: Enhancing Code Generation with Tool-Integrated Agent Systems for Real-World Repo-level Coding Challenges](https://arxiv.org/pdf/2401.07339)
  - Kechi Zhang, Jia Li, Ge Li, Xianjie Shi, Zhi Jin
- [Sep 2024] [DSBench: How Far Are Data Science Agents to Become Data Science Experts?](https://arxiv.org/pdf/2409.07703)
  - Liqiang Jing, Zhehui Huang, Xiaoyang Wang, Wenlin Yao, Wenhao Yu, Kaixin Ma, Hongming Zhang, Xinya Du, Dong Yu
  - https://github.com/LiqiangJing/DSBench
- [Sep 2024] [CORE-Bench: Fostering the Credibility of Published Research Through a Computational Reproducibility Agent Benchmark](https://arxiv.org/pdf/2409.11363)
  - Zachary S. Siegel, Sayash Kapoor, Nitya Nadgir, Benedikt Stroebl, Arvind Narayanan
  - https://github.com/siegelz/core-bench
- [Oct 2024] [MLE-Bench: Evaluating Machine Learning Agents on Machine Learning Engineering](https://arxiv.org/pdf/2410.07095)
  - Jun Shern Chan, Neil Chowdhury, Oliver Jaffe, James Aung, Dane Sherburn, Evan Mays, Giulio Starace, Kevin Liu, Leon Maksin, Tejal Patwardhan, Lilian Weng, Aleksander Mądry
  - https://github.com/openai/mle-bench
- [Oct 2024] [ScienceAgentBench: Toward Rigorous Assessment of Language Agents for Data-Driven Scientific Discovery](https://arxiv.org/pdf/2410.05080)
  - Ziru Chen, Shijie Chen, Yuting Ning, Qianheng Zhang, Boshi Wang, Botao Yu, Yifei Li, Zeyi Liao, Chen Wei, Zitong Lu, Vishal Dey, Mingyi Xue, Frazier N. Baker, Benjamin Burns, Daniel Adu-Ampratwum, Xuhui Huang, Xia Ning, Song Gao, Yu Su, Huan Sun
- [Nov 2024] [RE-Bench: Evaluating frontier AI R&D capabilities of language model agents against human experts](https://arxiv.org/pdf/2411.15114)
  - Hjalmar Wijk, Tao Lin, Joel Becker, Sami Jawhar, Neev Parikh, Thomas Broadley, Lawrence Chan, Michael Chen, Josh Clymer, Jai Dhyani, Elena Ericheva, Katharyn Garcia, Brian Goodrich, Nikola Jurkovic, Megan Kinniment, Aron Lajko, Seraphina Nix, Lucas Sato, William Saunders, Maksym Taran, Ben West, Elizabeth Barnes
- [May 2025] [EXP-Bench: Can AI Conduct AI Research Experiments?](https://arxiv.org/pdf/2505.24785)
  - Patrick Tser Jern Kon, Jiachen Liu, Xinyi Zhu, Qiuyi Ding, Jingjia Peng, Jiarong Xing, Yibo Huang, Yiming Qiu, Jayanth Srinivasa, Myungjin Lee, Mosharaf Chowdhury, Matei Zaharia, Ang Chen
- [Jun 2025] [ResearchCodeBench: Benchmarking LLMs on Implementing Novel Machine Learning Research Code](https://arxiv.org/pdf/2506.02314)
  - Tianyu Hua, Harper Hua, Violet Xiang, Benjamin Klieger, Sang T. Truong, Weixin Liang, Fan-Yun Sun, Nick Haber

### Paper Writing
- [Jun 2024] [Let’s Get to the Point: LLM-Supported Planning, Drafting, and Revising of Research-Paper Blog Posts](https://arxiv.org/pdf/2406.10370v1)
  - Marissa Radensky, Daniel S. Weld, Joseph Chee Chang, Pao Siangliulue, Jonathan Bragg
- [Jan 2025] [OmniThink: Expanding Knowledge Boundaries in Machine Writing through Thinking](https://arxiv.org/pdf/2501.09751)
  - Zekun Xi, Wenbiao Yin, Jizhan Fang, Jialong Wu, Runnan Fang, Ningyu Zhang, Jiang Yong, Pengjun Xie, Fei Huang, Huajun Chen
- [Apr 2025] [ScholarCopilot: Training Large Language Models for Academic Writing with Accurate Citations](https://arxiv.org/pdf/2504.00824)
  - Yubo Wang, Xueguang Ma, Ping Nie, Huaye Zeng, Zhiheng Lyu, Yuxuan Zhang, Benjamin Schneider, Yi Lu, Xiang Yue, Wenhu Chen

### Research Assessment
- [May 2024] [Is LLM a Reliable Reviewer? A Comprehensive Evaluation of LLM on Automatic Paper Reviewing Tasks](https://aclanthology.org/2024.lrec-main.816.pdf)
  - Ruiyang Zhou, Lu Chen, Kai Yu
- [Jun 2024] [LLMs Assist NLP Researchers: Critique Paper (Meta-)Reviewing](https://arxiv.org/pdf/2406.16253)
  - Jiangshu Du, Yibo Wang, Wenting Zhao, Zhongfen Deng, Shuaiqi Liu, Renze Lou, Henry Peng Zou, Pranav Narayanan Venkit, Nan Zhang, Mukund Srinath, Haoran Ranran Zhang, Vipul Gupta, Yinghui Li, Tao Li, Fei Wang, Qin Liu, Tianlin Liu, Pengzhi Gao, Congying Xia, Chen Xing, Jiayang Cheng, Zhaowei Wang, Ying Su, Raj Sanjay Shah, Ruohao Guo, Jing Gu, Haoran Li, Kangda Wei, Zihao Wang, Lu Cheng, Surangika Ranathunga, Meng Fang, Jie Fu, Fei Liu, Ruihong Huang, Eduardo Blanco, Yixin Cao, Rui Zhang, Philip S. Yu, Wenpeng Yin
- [Jun 2024] [AgentReview: Exploring Peer Review Dynamics with LLM Agents](https://arxiv.org/pdf/2406.12708)
  - Yiqiao Jin, Qinlin Zhao, Yiyang Wang, Hao Chen, Kaijie Zhu, Yijia Xiao, Jindong Wang
- [Dec 2024] [Are We There Yet? Revealing the Risks of Utilizing Large Language Models in Scholarly Peer Review](https://arxiv.org/pdf/2412.01708?)
  - Rui Ye, Xianghe Pang, Jingyi Chai, Jiaao Chen, Zhenfei Yin, Zhen Xiang, Xiaowen Dong, Jing Shao, Siheng Chen
- [Dec 2024] [OpenReviewer: A Specialized Large Language Model for Generating Critical Scientific Paper Reviews](https://arxiv.org/pdf/2412.11948)
  - Maximilian Idahl, Zahra Ahmadi
- [Apr 2025] [Can LLM feedback enhance review quality? A randomized study of 20K reviews at ICLR 2025](https://arxiv.org/pdf/2504.09737)
  - Nitya Thakkar, Mert Yuksekgonul, Jake Silberg, Animesh Garg, Nanyun Peng, Fei Sha, Rose Yu, Carl Vondrick, James Zou

## 🔧 Projects
- [gpt-researcher](https://github.com/assafelovic/gpt-researcher): an autonomous agent designed for comprehensive web and local research on any given task.
- [AI-Scientist](https://github.com/SakanaAI/AI-Scientist): Fully Automated
Open-Ended Scientific Discovery.
- [AI-Researcher](https://github.com/HKUDS/AI-Researcher): Fully-Automated Scientific Discovery with LLM Agents.
- [MLE-Agent](https://github.com/MLSysOps/MLE-agent): Your intelligent companion for seamless AI engineering and research.
- [Data-Agent](https://github.com/xlang-ai/OpenAgents/tree/main/real_agents/data_agent): a comprehensive toolkit designed for efficient data operations.
- [smolagents](https://github.com/huggingface/smolagents): a library that enables you to run powerful agents in a few lines of code.
- [AIDE](https://github.com/WecoAI/aideml): the Machine Learning Engineer Agent.
- [OpenHands](https://github.com/All-Hands-AI/OpenHands): a platform for software development agents powered by AI.
- [VisionAgent](https://github.com/landing-ai/vision-agent): an agent framework which can generate code to solve your vision task.
- [OpenDeepResearch](https://github.com/dzhng/deep-research): a simple implementation of a deep research agent - e.g. an agent that can refine its research direction overtime and deep dive into a topic.
- [gpt-pilot](https://github.com/Pythagora-io/gpt-pilot): the first real AI developer.
