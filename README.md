# LLMDataPapers
Must-read papers, and related blogs on the data-related methods for LLM.



## Data Processing For Pretraining

### Pre-Trained LLM with Data Processing Details 

1. 【GPT-2】**Language Models are Unsupervised Multitask Learners.** 

    *Alec Radford, Jeff Wu, Rewon Child, D. Luan, Dario Amodei, Ilya Sutskeve*  

2. 【GPT-3】**Language Models are Few-Shot Learners.** 
    
    *Tom B. Brown, Benjamin Mann, Nick Ryder, Melanie Subbiah, Jared Kaplan, Prafulla Dhariwal, Arvind Neelakantan, Pranav Shyam, Girish Sastry, Amanda Askell, Sandhini Agarwal, Ariel Herbert-Voss, Gretchen Krueger, Tom Henighan, Rewon Child, Aditya Ramesh, Daniel M. Ziegler, Jeffrey Wu, Clemens Winter, Christopher Hesse, Mark Chen, Eric Sigler, Mateusz Litwin, Scott Gray, Benjamin Chess, Jack Clark, Christopher Berner, Sam McCandlish, Alec Radford, Ilya Sutskever, Dario Amodei* 

3. 【T5】**Exploring the Limits of Transfer Learning with a Unified Text-to-Text Transformer**
    *Colin Raffel and Noam Shazeer and Adam Roberts and Katherine Lee and Sharan Narang and Michael Matena and Yanqi Zhou and Wei Li and Peter J. Liu*

4. 【Gopher】**Scaling Language Models: Methods, Analysis & Insights from Training Gopher**
    *Jack W. Rae, Sebastian Borgeaud, Trevor Cai, Katie Millican, Jordan Hoffmann, Francis Song, John Aslanides, Sarah Henderson, Roman Ring, Susannah Young, Eliza Rutherford, Tom Hennigan, Jacob Menick, Albin Cassirer, Richard Powell, George van den Driessche, Lisa Anne Hendricks, Maribeth Rauh, Po-Sen Huang, Amelia Glaese, Johannes Welbl, Sumanth Dathathri, Saffron Huang, Jonathan Uesato, John Mellor, Irina Higgins, Antonia Creswell, Nat McAleese, Amy Wu, Erich Elsen, Siddhant Jayakumar, Elena Buchatskaya, David Budden, Esme Sutherland, Karen Simonyan, Michela Paganini, Laurent Sifre, Lena Martens, Xiang Lorraine Li, Adhiguna Kuncoro, Aida Nematzadeh, Elena Gribovskaya, Domenic Donato, Angeliki Lazaridou, Arthur Mensch, Jean-Baptiste Lespiau, Maria Tsimpoukelli, Nikolai Grigorev, Doug Fritz, Thibault Sottiaux, Mantas Pajarskas, Toby Pohlen, Zhitao Gong, Daniel Toyama, Cyprien de Masson d'Autume, Yujia Li, Tayfun Terzi, Vladimir Mikulik, Igor Babuschkin, Aidan Clark, Diego de Las Casas, Aurelia Guy, Chris Jones, James Bradbury, Matthew Johnson, Blake Hechtman, Laura Weidinger, Iason Gabriel, William Isaac, Ed Lockhart, Simon Osindero, Laura Rimell, Chris Dyer, Oriol Vinyals, Kareem Ayoub, Jeff Stanway, Lorrayne Bennett, Demis Hassabis, Koray Kavukcuoglu, Geoffrey Irving*

5. 【Chinchilla】**Training Compute-Optimal Large Language Models**
    *Jordan Hoffmann, Sebastian Borgeaud, Arthur Mensch, Elena Buchatskaya, Trevor Cai, Eliza Rutherford, Diego de Las Casas, Lisa Anne Hendricks, Johannes Welbl, Aidan Clark, Tom Hennigan, Eric Noland, Katie Millican, George van den Driessche, Bogdan Damoc, Aurelia Guy, Simon Osindero, Karen Simonyan, Erich Elsen, Jack W. Rae, Oriol Vinyals, Laurent Sifre*

6. 【LLaMA】**LLaMA: Open and Efficient Foundation Language Models**
    *Hugo Touvron, Thibaut Lavril, Gautier Izacard, Xavier Martinet, Marie-Anne Lachaux, Timothée Lacroix, Baptiste Rozière, Naman Goyal, Eric Hambro, Faisal Azhar, Aurelien Rodriguez, Armand Joulin, Edouard Grave, Guillaume Lample*

### Scalable Data Processing Tool
1. 【CCNet】**CCNet: Extracting High Quality Monolingual Datasets from Web Crawl Data** 

    *Guillaume Wenzek, Marie-Anne Lachaux, Alexis Conneau, Vishrav Chaudhary, Francisco Guzmán, Armand Joulin, Edouard Grave*  

1. 【Data-Juicer】**Data-Juicer: A One-Stop Data Processing System for Large Language Models** 

    *Daoyuan Chen, Yilun Huang, Zhijian Ma, Hesen Chen, Xuchen Pan, Ce Ge, Dawei Gao, Yuexiang Xie, Zhaoyang Liu, Jinyang Gao, Yaliang Li, Bolin Ding, Jingren Zhou*

### PreTraining Datasets
1. 【Pile】**The Pile: An 800GB Dataset of Diverse Text for Language Modeling** 

    *Leo Gao, Stella Biderman, Sid Black, Laurence Golding, Travis Hoppe, Charles Foster, Jason Phang, Horace He, Anish Thite, Noa Nabeshima, Shawn Presser, Connor Leahy*  

1. 【Roots】**The BigScience ROOTS Corpus: A 1.6TB Composite Multilingual Dataset** 

    *Hugo Laurençon, Lucile Saulnier, Thomas Wang, Christopher Akiki, Albert Villanova del Moral, Teven Le Scao, Leandro Von Werra, Chenghao Mou, Eduardo González Ponferrada, Huu Nguyen, Jörg Frohberg, Mario Šaško, Quentin Lhoest, Angelina McMillan-Major, Gerard Dupont, Stella Biderman, Anna Rogers, Loubna Ben allal, Francesco De Toni, Giada Pistilli, Olivier Nguyen, Somaieh Nikpoor, Maraim Masoud, Pierre Colombo, Javier de la Rosa, Paulo Villegas, Tristan Thrush, Shayne Longpre, Sebastian Nagel, Leon Weber, Manuel Muñoz, Jian Zhu, Daniel Van Strien, Zaid Alyafeai, Khalid Almubarak, Minh Chien Vu, Itziar Gonzalez-Dios, Aitor Soroa, Kyle Lo, Manan Dey, Pedro Ortiz Suarez, Aaron Gokaslan, Shamik Bose, David Adelani, Long Phan, Hieu Tran, Ian Yu, Suhas Pai, Jenny Chim, Violette Lepercq, Suzana Ilic, Margaret Mitchell, Sasha Alexandra Luccioni, Yacine Jernite*  

1. 【RedPajama】*RedPajama: An Open Source Recipe to Reproduce LLaMA training dataset* 

    *Together Computer*  

1. 【Falcon】**The RefinedWeb Dataset for Falcon LLM: Outperforming Curated Corpora with Web Data, and Web Data Only* 

    *Guilherme Penedo, Quentin Malartic, Daniel Hesslow, Ruxandra Cojocaru, Alessandro Cappelli, Hamza Alobeidli, Baptiste Pannier, Ebtesam Almazrouei, Julien Launay*  

### Scalabe Data Processing Methods
1. 【Deduplication】*Deduplicating Training Data Makes Language Models Better*
    *Katherine Lee, Daphne Ippolito, Andrew Nystrom, Chiyuan Zhang, Douglas Eck, Chris Callison-Burch, Nicholas Carlini* 

2. 【Filter by PPL】*When Less is More: Investigating Data Pruning for Pretraining LLMs at Scale*
    
    *Max Marion, Ahmet Üstün, Luiza Pozzobon, Alex Wang, Marzieh Fadaee, Sara Hooker*

2. 【Filter by Active Learning】*Batch Active Learning at Scale*
    
    *Gui Citovsky, Giulia DeSalvo, Claudio Gentile, Lazaros Karydas, Anand Rajagopalan, Afshin Rostamizadeh, Sanjiv Kumar*

2. 【Filter by Active Learning】*Active Learning at the ImageNet Scale*
    
    *Zeyad Ali Sami Emam, Hong-Min Chu, Ping-Yeh Chiang, Wojciech Czaja, Richard Leapman, Micah Goldblum, Tom Goldstein*

3. 【Filter by Training Dynamics】*Dataset Cartography: Mapping and Diagnosing Datasets with Training Dynamics*
    
    *Swabha Swayamdipta, Roy Schwartz, Nicholas Lourie, Yizhong Wang, Hannaneh Hajishirzi, Noah A. Smith, Yejin Choi*

## Data Processing for Finetuning/Instruction-Tuning

### Instruction Tuning Datasets
1. 【Natural Instruction】**Cross-task generalization via natural language crowdsourcing instructions** 

    *Mishra, Swaroop and Khashabi, Daniel and Baral, Chitta and Hajishirzi, Hannaneh*  

1. 【Super Natural Instruction】**Super-NaturalInstructions: Generalization via Declarative Instructions on 1600+ NLP Tasks** 

    *Yizhong Wang, Swaroop Mishra, Pegah Alipoormolabashi, Yeganeh Kordi, Amirreza Mirzaei, Anjana Arunkumar, Arjun Ashok, Arut Selvan Dhanasekaran, Atharva Naik, David Stap, Eshaan Pathak, Giannis Karamanolakis, Haizhi Gary Lai, Ishan Purohit, Ishani Mondal, Jacob Anderson, Kirby Kuznia, Krima Doshi, Maitreya Patel, Kuntal Kumar Pal, Mehrad Moradshahi, Mihir Parmar, Mirali Purohit, Neeraj Varshney, Phani Rohitha Kaza, Pulkit Verma, Ravsehaj Singh Puri, Rushang Karia, Shailaja Keyur Sampat, Savan Doshi, Siddhartha Mishra, Sujan Reddy, Sumanta Patro, Tanay Dixit, Xudong Shen, Chitta Baral, Yejin Choi, Noah A. Smith, Hannaneh Hajishirzi, Daniel Khashabi*  

1. 【Flan】**The Flan Collection: Designing Data and Methods for Effective Instruction Tuning** 

    *Shayne Longpre, Le Hou, Tu Vu, Albert Webson, Hyung Won Chung, Yi Tay, Denny Zhou, Quoc V. Le, Barret Zoph, Jason Wei, Adam Roberts*  

1. 【Self-Instruct】**Self-Instruct: Aligning Language Model with Self Generated Instructions** 

    *Yizhong Wang, Yeganeh Kordi, Swaroop Mishra, Alisa Liu, Noah A. Smith, Daniel Khashabi, Hannaneh Hajishirzi* 

1. 【Alpaca】**Stanford Alpaca: An Instruction-following LLaMA model** 

    *Rohan Taori and Ishaan Gulrajani and Tianyi Zhang and Yann Dubois and Xuechen Li and Carlos Guestrin and Percy Liang and Tatsunori B. Hashimoto*  

1. 【GPT-4 Instruction】**Instruction Tuning with GPT-4** 

    *Peng, Baolin and Li, Chunyuan and He, Pengcheng and Galley, Michel and Gao, Jianfeng*  

2. 【ShareGPT】**Instruction Tuning with GPT-4** [[dataset](https://huggingface.co/datasets/anon8231489123/ShareGPT_Vicuna_unfiltered)]

1. 【Orca】**Orca: Progressive Learning from Complex Explanation Traces of GPT-4** 

    *Subhabrata Mukherjee, Arindam Mitra, Ganesh Jawahar, Sahaj Agarwal, Hamid Palangi, Ahmed Awadallah*  

2. 【LIMA】**LIMA: Less Is More for Alignment** 

    *Chunting Zhou, Pengfei Liu, Puxin Xu, Srini Iyer, Jiao Sun, Yuning Mao, Xuezhe Ma, Avia Efrat, Ping Yu, Lili Yu, Susan Zhang, Gargi Ghosh, Mike Lewis, Luke Zettlemoyer, Omer Levy*  

2. 【oasst】**OpenAssistant Conversations -- Democratizing Large Language Model Alignment** 

    *Andreas Köpf, Yannic Kilcher, Dimitri von Rütte, Sotiris Anagnostidis, Zhi-Rui Tam, Keith Stevens, Abdullah Barhoum, Nguyen Minh Duc, Oliver Stanley, Richárd Nagyfi, Shahul ES, Sameer Suri, David Glushkov, Arnav Dantuluri, Andrew Maguire, Christoph Schuhmann, Huu Nguyen, Alexander Mattick*     

### Data Filtering Methods (Not Scalable)

1. *AlpaGasus: Training A Better Alpaca with Fewer Data*

    *Lichang Chen, Shiyang Li, Jun Yan, Hai Wang, Kalpa Gunaratna, Vikas Yadav, Zheng Tang, Vijay Srinivasan, Tianyi Zhou, Heng Huang, Hongxia Jin*  

1. *Instruction Mining: High-Quality Instruction Data Selection for Large Language Models*

    *Yihan Cao, Yanbin Kang, Lichao Sun* 

1. *Becoming self-instruct: introducing early stopping criteria for minimal instruct tuning*

    *Waseem AlShikh, Manhal Daaboul, Kirk Goddard, Brock Imel, Kiran Kamble, Parikshith Kulkarni, Melisa Russak* 

1. *Maybe Only 0.5% Data is Needed: A Preliminary Exploration of Low Training Data Instruction Tuning*

    *Hao Chen, Yiming Zhang, Qi Zhang, Hantao Yang, Xiaomeng Hu, Xuetao Ma, Yifan Yanggong, Junbo Zhao* 

1. *Probabilistic bilevel coreset selection*

    *Xiao Zhou, Renjie Pi, Weizhong Zhang, Yong Lin, Zonghao Chen, Tong Zhang* 

1. *Self-Guided Noise-Free Data Generation for Efficient Zero-Shot Learning*

    *Jiahui Gao, Renjie Pi, LIN Yong, Hang Xu, Jiacheng Ye, Zhiyong Wu, Weizhong Zhang, Xiaodan Liang, Zhenguo Li, Lingpeng Kong* 

