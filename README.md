# Machine Learning Design Pattern
Design patterns are standard and recommended ways that programmers can use to address typical issues while developing a system or application.

## Rebalancing: Problem Representation 
**Choosing the right performance metric:**

    	Balanced Data: Accuracy
    	Imbalanced Data: Precision, recall, F1 score, AUC
        
**Sampling methods:**

    	Over-sampling
    	Down-sampling
        
**Weighted classes**

        Penalized learning algorithms
 
## Transform: Reproducibility Design Pattern
**Separate input from features**

        Extract features from raw input
    
**Transformation and Preprocessing:**

        	Standardization
        	Scaling
        	Encoding

## Checkpoints: Model Training
**Snapshot of a model’s internal state:**

        To keep models especially deep learning models from unexpected events like power outages, operating system problems, interruptions in tasks, or other types          of errors
        	Weights and current learning rate
        	Keep a checkpoint at the end of every epoch
        	Save the model with the best accuracy
