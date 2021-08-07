# Parkinson-s-Prediction
Diagnosis Parkinson using ML 
# Introduction
As the Parkinson’s disease detection is the top most chronic disease which was on the 3rd position. By using the parameters of both Parkinson and Non-Parkinson’s person, we can build a model using algorithms which can easily detect the disease. For dealing with the dataset which is of high dimensions, that can leads to noise or redundancy which may affect the model performance. For choosing the Optimum Features that are required for the model building is to be selected using the Nature Inspired Optimization Techniques like Particle Swarm Optimization (PSO), Gravitational Search Algorithm (GSA), Differential Evolution (DE), Evolutionary Programming (EP), and Evolution Strategy (ES).Among all Binary Grey Wolf Optimizer is the best method for optimum features for building a model and similarly the machine learning techniques like K-nearest neighbours,Decision Tree Clssifier, Navie Bayes, Support Vector Machine and implemented with kernalised, Ensemble Learning techniques which having more that one classifier like Bagging,Boosting,Adaboosting are used for best performance,Among all Extreme Gradient Boosting algorithm acheives the best performance characteristics is implementedand obtained the satisfactory classification Accuracy results.

# Training 
# Binary 	Grey wolf optimizer (GWO): 
  Grey Wolf Optimization is one of the latest bio-inspired optimization techniques, which simulate the hunting process of grey wolves in nature. a new meta-heuristic called Grey Wolf Optimizer (GWO) inspired by grey wolves (Canis lupus). The GWO algorithm mimics the leadership hierarchy and hunting mechanism of grey wolves in nature.
Grey Wolves mostly prefers to live in a pack .Hierarchy of Grey wolf pack consists of four types: 
1.	Alpha Wolves: The alpha are dominant wolf in the pack, the alpha wolves are responsible for making decisions about hunting, sleeping place, time to wake.
2.	Beta Wolves: The betas are subordinate wolves that help the alpha in decision making or other activities.
3.	Delta Wolves: The deltas have to submit alphas and betas, but they dominate the omega. Scouts, sentinels, elders, hunters, and caretakers belong to this category 
4.	Omega Wolves: The omega plays the role of scapegoat. Omega wolves always have to submit to all the other dominant wolves.

 
Types of wolves
Social Hierarchy:	
	In the mathematical model for the GWO the fittest solution is called the alpha (α). The second and the third best solutions are named beta (β) and delta (δ).The rest of the candidate solutions are assumed to be omega (ω).
The main phases of Grey Wolf Hunting’s are 
•	Trucking, chasing and approaching the prey.
•	Pursuing, encircling and harassing the prey until it starts moving
•	Stationary situation and Attack towards the prey.
	Mathematically, the top three fittest solutions in GWO are called alpha (α), beta (β), and delta (δ), respectively. The rest are assumed to be omega (ω). In GWO, the hunting process is guided by α, β, δ and ω, while w follows these three leaders

# Extreme Gradient Boosting (XGB) Classifier Model:
Extreme Gradient Boosting is one of the Ensemble machine learning technique of highly versatile and flexible that can work through classification, regression and ranking problems. XGBoost is a decision-tree-based ensemble machine learning technique which used a gradient boosting technique in prediction, for unstructured data format (images, text) artificial neural network (ANN) is outperformed where for structured and tabular data; decision tree based model is implemented for better results
