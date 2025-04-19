# IBM-IntroToAI

  Notes Prepared by Transcribing Handwritten Notes from the IBM AI Fundamentals Course:
Available Here: https://www.ibm.com/training/badge/artificial-intelligence-fundamentals

# INTRODUCTION TO ARTIFICIAL INTELLIGENCE:

  There are three levels of predictions that AI can make: narrow, broad and general. Artificial intelligence refers to the ability of a machine to learn patterns and make predictions. Augmented intelligence has the goal of helping humans with tasks that are not practical to do: e.g. reading 1000 pages in an hour. AI has a goal of mimicking human thinking and processes. 
-	Machines: are wonderful at ingesting large amounts of data.
-	Humans are wonderful at generalizing information, creativity, communication, and emotional intelligence. (Generalizing information = taking in a single piece of data and understanding what it represents). 

  With machine learning, the more data that is provided, the better that it gets. Deep learning models eliminate the need for feature extraction. Feature extraction is built into the process without human input. 
AI can analyze, sort, and organize massive amounts of data and it can predict, like autocorrect. There are three levels of

AI based on predicted growth in its ability to analyze data and make predictions:
i.	Narrow: focused on a single task like planning a day
ii.	Broad: can handle a wider range of related tasks
iii.	General (available in the future  estimated to exist by 2050). 

 	Dark Data is information without structure, just a huge, unsorted mass of facts. Tabulation is the act of slicing and dicing data to give it a structure. Data can be classified as structure, semi-structured or unstructured. Data is raw information, and structured data can be characterized by rows and columns, etc. Dark data is qualitative and includes images, texts, customer comments, etc. Semi-structured data is the bridge between structured and unstructured data. Semi-structured data uses metadata to identify specific data characteristics and to scale data into records and pre-set fields. 80% of the data in todays world is estimated to be unstructured.

# MACHINE LEARNING:

  Machine Learning uses probabilistic calculation There are two ways to construct classical and machine learning systems: deterministic and probabilistic. The former is basically binary thinking: yes or no. The second is never yes or no but analog (or a spectrum), existing between 0 and 1 but never 0 or 1. 
The methods of machine learning are:

i.	Supervised: Providing AI with enough examples of labeled data. It is required to explicitly inform the machine of the characteristics or “features” of the data.

ii.	Unsupervised: A large amount of data is fed to machines and questions are asked. The machine is then left to figure out the answer itself and the algorithms are not given a “right” or “wrong” outcome… just unlabeled data.

iii.	Reinforcement: The algorithm isn’t trained with sample data but learn through trial or error. 
State is a situation returned by the machine after each action taken by an agent. Actions are moves taken by the agent within the environment.

# NATURAL LANGUAGE PROCESSING AND COMPUTER VISION:

  IBM began developing project debater in 2012 with a goal of building a machine that could do more than win a debate with humans. IBM wanted the machine to respond intelligent and the goal was to develop an evidence-based, biased-free decision.  
  
  The four steps to winning a debate (according to their model) are:
  I. Learn and understand the topic, 
  II. Build a position, 
  III. Organize your proof, 
  IV. Respond to your opponent. 

  Machines use natural language processing (NLP) to understand human language. Chunks of information are tokens and tokens can be organized into categorized called entities and relationships. An entity is a noun representing a person, place, or thing. A relationship is a group of two or more entities that have a strong relationship with one another. Once AI has classified entities and relationships as in text or speech, then the AI can begin structuring it. A concept is something that is implied in a statement, but which is not actually stated. A concept matches ideas rather than specific words present in the sentence. 

  Emotion detection and sentiment analysis: Emotion detection identifies distinct human emotion types. Sentiment analysis is not a specific emotion but is a measure of the strength of an emotion. Sentiment analysis assesses whether data is positive, neutral, or negative. Human language can be vague or can have double meanings and this leads to a classification problem. AI cannot be 100% perfect and well-designed models provide confidence values with their responses to account for this. 

# CHATBOTS:

  Chatbots listen to user questions and generate useful answers. They work with small data and the front-end of a chatbot is the messaging channel where it interacts with humans. The backend of a chatbot is where the hard work takes place and where application logic is. Classifiers can map many different ways of asking a question by breaking it into parts and relating those parts to things in its memory. A chatbot’s goal is to identify entities and intents and then use what’s found to trigger a dialog. An intent is a purpose and an entity is a person, place, or thing. A dialog is a flowchart – an if/then laying out how a machine will respond to user events. The dialog represents each possible word or phrase a user might enter with responses for the chatbot, and the many possible subsequent replies to the user might make. The chatbot condenses each moment of the conversation into a node. The node is a statement made by the chatbot and a long expandable list of possible replies. AI combines NLP with intents, entities, dialog, and sentiment analysis. A question is asked and AI provides the answer with the highest confidence.

# CNNS/GANS:

  An AI system uses convolutional neural network (CNN) to analyze images. CNN makes it possible to identify things in an image (by visual recognition systems). A CNN is an area of deep learning that specializes in pattern recognition. An artificial neural network consists of multiple layers that are interconnected, with each layer receiving some input, transforming that input into something else, and then passing the input to the next layer. CNN is a particular part of a neural network. Within the layers, filters perform the pattern recognition. As we go deeper into the neural network, filters become more abstract. In a CNN, two small groups of pixels that overlap each other are compared mathematically to get a value. A vision recognition system can use a generative adversarial network (GAN) to create new drawings and photos. One way to create deepfakes is to pit two CNN networks against one another in a “contest” called a GAN where they battle each other until one becomes good at creating art. 

  A GAN is an example of unsupervised learning: it supervises itself and consists of two sub-models: I. A generator, and II. A discriminator sub-model. The generator creates fake input/samples and the discriminator tries to figure out if the input/samples are real or fake. With generators and discriminators, there is always a winner and a loser and it is a zero-sum game. Both of these are implemented as CNNS, and they are not always used for photo generation but also for image enhancement. A CNN makes image recognition possible!

# MACHINE LEARNING AND DEEP LEARNING:
  Artificial intelligence describes computer systems as subjects that previously required human intelligence. Machine learning can enable systems to predict and classify data (in response to ever changing data). Deep learning is a type of machine learning. Acquiring knowledge through experience is a process called cognition. Structured data can take the form of images, labeled photos of species in a collection of flower photos, etc. 

Two different technologies for machine learning: 
I.	Classical machine learning
II.	Deep learning

  There are three typical algorithms used in classical computing: decision trees, linear regression, and logistic regression. A decision tree is a supervised learning algorithm. The flowchart has a root node and branches that connect to internal nodes, and then more that connect to leaf nodes. Classical machine learning starts with a known set of data and forms a reasonable prediction. Linear regression is data that may be graphed as a straight line. Linear repression learns all the variables and calculates a reasonably accurate prediction, effectively resolving a mass of data into a “most likely” line. Logistic regression is for things that do not fall into a straight line. Note: an S shaped curve is a sigmoid function.

# NEURAL NETWORKS 
  The foundation for many applications is a neural network. In a neural network, a building block is called a perceptron, and this acts as the equivalent of a single neuron. A neural network has an input layer, one or more hidden layers, and then an output layer. A node often uses a sigmoid function to determine whether to fire a sigmoid function. A sigmoid function can generate a binary answer such as Yes or No. The binary answer tells a node whether to fire. If there are other nodes connected to the node, they are activated when the signal reaches them. If the other nodes reach their own thresholds, they also fire. A neural network = pure mathematics. In a neural network, the individual nodes in a layer work on algorithms simultaneously and calculate and adjust in response to external factors. This is called machine learning. Machine learning has evolved into applications called the deep learning ecosystem Once a neural network has ingested or “learned” a certain amount of data, it stores the data in its body of information called the corpus. To learn, the neural network constantly checks the new data against its corpus. It then incorporates or adjusts as necessary. Many AI Systems output a confidence value outside an answer or prediction. In many modern applications of AI, the unstructured data is complex enough to overwhelm even a single perceptron – the extra “oomph” for calculating comes in the form of deep learning. Deep learning relies on the multiple layers of nodes to finish the work and produce an output in a reasonable amount of time. 

# AI SYSTEMS:
Advanced AI systems use many hidden layers – this is a deep neural network. Most AI systems are discriminative AI models which predict and classify data. Generative AI is a type of deep learning AI system that uses algorithms to generate content in response to a prompt.

The overall generative AI process: 
  I.	A person feeds the AI a large amount of data, 
  II.	II. the AI system looks for patterns and relationships between different pieces of data,
  III.	AI uses what it has learned to create something new…(via pattern identification and analysis).

The Three Primary Types of Generative AI models:
  i.	Variational Autoencoders (VAE): Compresses input data into lower dimensional representation and then reconstructs the original data to capture underlying patterns and structure to generate new data.
  ii.	GAN models: Function as a competition between forger and critic. The goal is for the forger to generate something new and realistic-enough to fool the critic.
  iii.	Auto-Regressive models: Generate new content for predicting the next element in a sequence based on previous elements. (Note these are particularly well-suited for generating text).

  Examples of generative AI applications currently available: Chatgpt, IBM Watson discovery, DALL-E/DALL-E2
Machine learning algorithms are programs which are coded to recognize patterns in data sets. Machine learning models are a set/group of machine learning algorithms. A machine learning model doesn’t depend on humans alone to write its code… rather a machine learning model can reprogram itself.

____________________________________________________________________________________________

# Additional Notes:

  Creating machine learning models is the primary job of the IBM Watson studio IDE. Watson studio is a collaborative data science and machine learning environment that supports easy visualizations, efficient and collaborative workflows, a built-in neural network modeler, and open-source tools like Jupyter Notebook and R Studio. IBM Watson studio is configured as a service with free (and subscription based) plans.

# Future Oriented technologies: 

I. Quantum Computing, 
II. Distributed Deep Learning, 
III. Neuromorphic Systems, 
IV. Homomorphic systems, 
V. Machine foresight, 
VI. Cognitive discovery
