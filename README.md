# AI-Programming-using-Python
# Contents:
First part:

# Search problems
        Uninformed search strategies:
            BFS, DFS, UCS, DLS, IDS
        Informed search strategies:
            Gready, A-star

![22222](https://user-images.githubusercontent.com/55910811/205471282-d7175ef6-7486-4eec-880c-627ee37c9512.png)
Example: solving 8-puzzle using search algorithms. 

- Local search:
    - Hill climbing, Simulated Annealing, Genetic algorithms
    ![50-tsp-sa](https://user-images.githubusercontent.com/55910811/205471320-b375fc19-e737-4927-b9be-dae2234a2725.gif)
Example solution found by simulated annealing for TSP problem (for 50 cities). 
![10-queens](https://user-images.githubusercontent.com/55910811/205471333-b25b1d66-bf94-439f-b882-b2541517e19f.gif)
Example: solving 10-Queens using simulated annealing. 

- Adversarial search and games
    - MiniMax, alpha-beta pruning
    
 # Python programming concepts

    Object oriented programming in Python
        Using and defining special python methods (dunder methods).
        Immutable objects.
        Making an object hashable (implementing __hash__() and __eq__() methods.
        Implementing decortors in Python.
        Class methods and static methods.
        __repr__() and __str__() methods.
        
 # Second part:

    Machine learning
        Supervised learning:
            KNN, Naive Bayes, Desision Trees, SVM, Neural Nets
        Unsupervised learning:
            k-Means clustering
        Reinforcement learning
            Q-learning

 # Example problems

    Search:
        N-Puzzle, N-Queens, TSP
    Games:
        Pacman, Chess
    Learning:
        Pacman, Chess, etc.

1: Uninformed (blind) search strategies

    Implementing data structures like stack, queue and priority queue
    Implementing N-Puzzle (8-Puzzle)
    Implementing uninformed search strategies: BFS, DFS, UCS, DLS, IDS
    Programming assignment

2: Informed search strategies

    Implementing informed search strategies: Greedy, A-star
    Programming assignment

3: Local search

    Implementing N-Queens and TSP(a graphical implementation)
    Implementing local search strategies: hill climbing, simulated annealing and genetic algorithms
    Programming assignment

4: Adversarial search and games

    Implementing Otello
    Implementing adversarial search algoritms: Minimax and alpha-beta prunning
    Programming assignment
    
  # After first part:

    You will have a good understanding of basic AI techniques (solving problems using searching)
    You will become a real python programmer and most importantly a real programmer!
    You will see a lot of programming challenges and you will learn how to solve them



# AI in medicine/ medical imaging classification 
(tensorflow tutorial)


From mammograms to cat scans, AI can diagnose a disease better than any human can if given the right training dataset. This will drastically reduce patient death, save medical practices a lot of money, and aid doctors in the patient care process. Everyone will win and its important to remember that AI won’t replace doctors. It will become the most powerful tool they’ve ever used. And once enough AI startups start impacting the field of healthcare, it will become as common a tool as the stethoscope has been.
Which is a test that wrongly indicates the possibility of cancer in a 10-year period.
Radiologists regularly disagree on their respective interpretations of medical images.  AI can do what no radiologist can, it can learn from hundreds of thousands of medical images and is estimated to be up on  ten percent more accurate than the average radiologist that accuracy gap will only increase as computing power gets cheaper and can be applied to any of the countless subfields of medicine not just radiology like what the startup vizhai is doing for brain scans.
Doctors also have to interpret patient medical records which can be a very complex task NLP and branch of AI that helps computers understand and interpret human language can review thousands of medical records and output the optimal steps for evaluating and managing patients with many illnesses some doctors really are gifted.

An AI can learn from the best by watching them  do their work if all doctors match the performance of the top 20% patient deaths from a variety of diseases would decrease by the hundreds of thousands per year and wild doctors have natural biases AI is more likely to produce objective diagnosis for patients without preconceived socio-economic notions which can produce disparities is care ml will become an essential tool for doctors like stethoscope has been and as more of the profession is automated human empty and compassion for patients will become paramount to their success in the field also good looks let’s just be real so how do we pick a problem to solve the AI and healthcare market is expected to grow at an incredible forty eight percent compound annual growth rate in the next five years according to research and markets the tech giants like Google and Microsoft have massive amounts of data talent and computing power they have a huge advantage when it comes to building horizontal products these are products that can be applied to many use cases but as  a start-up you can build a vertical product one that tackles a single problem very well since they don’t have the time to do that one way to do this is to find relevant problems in online communities where doctors congregate, these can be forums slack channels subreddits Grey’s Anatomy chat rooms about McDreamy and see what kind of problems they’re having another way would be to call up or schedule a visit to a local practice to hear firsthand about the type of problems they’re having listening before acting is an important first step when finding the right problem to solve eventually we’ll come across problem that is dealt with by multiple doctors let’s say for the case of this demo its diagnosing diabetic retinopathy correctly. We can build a classifier to help solve this problem but first we’ve got to collect some quality data the foundation of all machine learning is having lots of quality data that’s how it learns very few companies actually generate and own medical grade data since collecting this data from patients is quite difficult so we’re gonna have to  get a little creative we can search the web by searching public imaging datasets for diabetic retinopathy we’ll come across a few some will require us to apply and  register before getting access so we can go ahead and do that and hope for the best alternatively if you’re a student at a university you can go find the nearest imaging research center and ask the professor there they’re always willing to help with projects PubMed is also a great place to find biomedical research papers we can search for papers by the type of scan data we’re looking for and once we find a good one we can just email those researchers directly explain our project and how it could be mutual beneficial to both of us. If we frame it more like we’re trying to help them than asking them for sth they’ll be more likely to help us, if we can get our hands on a quality data set ideally with labels because labeled datasets are always easier to learn from then we know that we have a shot at solving this problem.

But before we actually invest our time and energy into building an AI model, we need to make sure that we’re able to get customers the easiest way is to create a simple landing page. We can find a template pretty easily online that asks for a simple email signup we’d explain our product in  detail and the landing page and once we have it we can send it to potential clients in our case that would be doctors and medical companies we can find a directory of them online and email them one by one post it in facebook groups and see if we get any signups if we’re able to get a sufficient amount of signups then we know that there is indeed interest in our products and we can go ahead and start building there’s an entire ecosystem of libraries and services that help us build models our kyv sanity is a great tool to help a search for how the latest AI models have been applied to medical diagnosis in research labs once we find a cool paper we can use it as a guide to help build our own model it’s important to remember that there are so many tweaks and modifications we can potentially make to our model to improve it but the best thing to do is to first build a prototype that works as fast as possible and then iterate from there CCNs are a type of model that have proven to outperform all others when comes to image classification which is our use case the fastest and easiest way to build a CNN is by using the chaos machine learning library it. It lets us build NNs easily with its high-level APU  each line of code corresponds to a different layer in a NN.


# Biotechnology: 

A Chinese scientist claimed to have created the first genetically modified humans. This triggered memories of that dystopian eugenics book Brave New World that I noted in high school no regrets he used a very popular gene editing tool called CRISPR to modify the embryos for a couple during fertility treatments to make them resistant to HIV infection which resulted in the birth of twin girls immediately afterward one of the inventors of CRISPR through some scientific shade at him by calling for a global moratorium on using it to create gene-edited babies. This Fiasco has brought some really hard questions in biotechnology to the limelight that I’m going to address should we be engineering our own biology and that of our offspring what are the other potentials for this technology and what does it even meat to be human in 1919 the Hungarian agricultural engineer Carl Araki foresaw a time when biology could be used to turn raw materials into useful products he coined the term biotechnology to describe the merging of biology and technology we can consider agriculture to be a form of early biotech when farmers introduced their plans to new environments and selectively bred them with others they inadvertently altered their genetics also brewing bear so hipsters are basically biotechnologists and after more than 40 years of running on parallel tracks the information and life sciences are slowly beginning to fuse into a single technological and economic force we’re using computers to decipher manage and organize vast amounts of genetic data which is the raw resource of the emerging biotech economy Iraqis vision has now  been realized we are at the stage where we’re able to program living systems and organisms to solve problems and make products introducing glow-in-the-dark water thousands of biotechnology startups are popping up across the world with products like new medicines medical devices resilient crops biofuels and pollution controls were creating biological data banks using genetic information of millions of years of evolution to remake the natural world the breakthrough that Laid the groundwork for modern biotechnology came when the structure of DNA was discovered by Watson and Crick in the early 1950s DNA is a long coiled molecule found in the center of a cell it provides the full blueprint for the construction and operation of a life-form via a miniscule microbe an elephant or even a human every cell in an organism holds a  complete copy of that organisms DNA the data in DNA is not stored as ones and zeros as it is on silicon chips but instead as code made up of four basic building blocks a C T and G called nucleotides the order they appear is like the order of the letters that spell words their order forms different genes and each gene contains the instructions for specific protein the genes in the DNA of a cell can be either active or inactive depending on the cell’s needs once a gene is active its data is used to make the protein for which it codes proteins can put molecules together break them apart relay messages between cells act as antibodies to defend against diseases or act as structural building blocks giving shape to cells and organs now you can retake your bio exam and pass biotechnology is advancing really fast these days due to two reasons ai and CRISPR for example ibm’s Watson AI uses an ensemble of different ML models to drive insights from data and in a demo was fed 70k papers published around one single protein what would have taken a well-trained human years to understand Watson was able to do instantly it integrated the data created a map of interaction and added seven new protein interactions that humans later discovered independently and then there’s CRISPR.
Scientists usually don’t like using the word miracle but it seems like they make an exception when comes to this crisply named gene editing tool CRISPR stands for clustered regularly interspaced short palindromic repeats.


The name sounds ridiculous I know it refers to unusual DNA sequences that help protect organisms identifying threats like viruses and attacking them when we look at the DNA sequences themselves they are clustered they are spaced out at clear intervals and when assigned latter values they do look like short palindromes repeating over and over with slight variation bacteria uses these repeats like collections of mugshots to identify bad viruses and another crucial component here is cast 9 this is an enzyme that can cut apart DNA bacteria fight viruses by sending the cast 9 enzyme to cut up viruses that have a mugshot in the collection researchers have used a similar approach to turn this microbe virus fighting system into the hottest new lab tool an organism’s genome the entire set of its DNA instructions can be altered quickly and efficiently using CRISPR it’s low cost easy to use in fact you can buy a $150 chip to use CRISPR at home some middle schoolers are already doing it in their science classes and all I got to do was cup open a frog for those who don’t want to conduct experiments locally cloud labs like transcriptic makes it possible to do so remotely using robotics it automates the tedious stuff like tool building which lets aspiring bio-data scientists focus on answering questions. CRISPR and cast9 work as a homing device that guides molecular scissors to a target selection of DNA it’s like a computer mouse just point at the place in the genome and you can do anything you want at that spot both the cost of gene sequencing technology and computer processing power has dropped dramatically allowing for this field to flourish the question then become how can we engineer are world with biotechnology well to start by ending hunger huge questions vexed the future of food how do we feed 9 billion people how do we form in an era of unprecedented climate uncertainty will Starbucks survive in illy know so far genetically modified organisms or GMOs have been used to help feed the world’s hungry but they are still not seen as a sustainable solution by some governments because it involves inserting desired foreign genes into the existing genome of a plant or animal but gene editing techniques namely CRISPR instead modifies the organism directly without introducing foreign genetic material which allows for a new realm of both legal and scientific possibility in sub-saharan Senegal researchers tested thousands of wheat varieties using CRISPR before developing wheat that could flourish despite heat hovering constantly above 100 degrees Fahrenheit their wheat yield required less water and had 5 times more protein as well as more vitamins and minerals than Senegalese rice, all right I’m getting hungry now but look we can use CRISPR to protect and the environment from any harm we caused one example are biofuels plants naturally turn carbon dioxide and sunlight into by products with CRISPR we can use the sugars that’s or alcohols produced by them  as potential alternative fuel sources we can even turn plans into sensors they are already are naturally by responding to chemicals in their environments but by re-engineering them we can get them to signal the presence of environmental pollutants and once identified it could trigger a bio remediation pathway and we can think about environmental sustainability in an entirely new way in the form of bio design people are already modifying genes to redesign extinct species make plans glow-in-the-dark and help flowers change color depending on the time of day Adidas even made shoe from bioengineered fiber which was inspired by spider silk still cheaper than Easy’s taking it a step further we cloud theoretically engineer a tree’s DNA to grow into a tree house or even engineer entire cities to be built from and around nature living harmoniously with it. 

# Installation Instructions
In Anaconda I did installed follow codes:
pip install biopython
pip install biopython --upgrade
python -m ensurepip
python3.9 -m pip install biopython
pypy -m pip install biopython

Sangamo therapeutics for example helped a man with Hunter syndrome by injecting him with the replacement copy of his flawed gene but why and at curing diseases why not cure death itself if we could choose when to die rather than succumb to a genetically predetermined death it would give us much more of an opportunity to experience life. Some say that death is the only motivation to do great things in life but why assume it’s like that for all people curiosity, competition, spicy ramen there are a wide variety of motivations for people rejuvenate bio is a startup that has plans to reverse aging in dogs then reverse aging in humans they’ve used gene therapy to additional instructions into the DNA of aged mice and use these instructions to regulate and modify the activity of various genes their plan is to increase or inhibit gene expression depending on its contribution to aging in an attempt to restore the production of secreted molecules to youthful levels we cloud also modify genes to theoretically make ourselves more fit smarter more attractive an ex NASA scientist was inspired by s report from China about the first gene  edited dog that grew muscles and injected himself in front of a live audience with a gene he edited to prevent his myostatin gene from inhibiting his muscle growth and that brings us to the Chinese scientist who claimed to have created the first genetically modified babies to be HIV resistant parents can theoretically use gene editing technology to create the ideal type of child in their eyes they can enjoy raising a super genius who grows up to be faster than Usain Bolt more beautiful than Lana Del Ray and more creative than Shia LaBeouf somehow but should we be modifying humans at early age in a world where that’s possible and it is fast becoming a reality some people will and their children will have a clear advantage over the rest in fact someday it could be considered morally outrages to  not use gene enhancement on your child to help them keep up with an increasingly information dense and fast-paced society and while genetic data will give people the power to predict and plan their lives in ways never before possible it could also be used by government and employers to determine insurance premiums employment prospects and give rise to a new form of discrimination based on a genetic profile our very notion of equity could be transformed meritocracy could be transformed into Jen autocracy where people are categorized by their genotype think of it like an informal biological caste system Indians know that I’m talking about here let’s not do that again.

