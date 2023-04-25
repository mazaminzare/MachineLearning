# Machine Learning Design Pattern
Design patterns are standard and recommended ways that programmers can use to address typical issues while developing a system or application.

## Rebalancing: Problem Representation 
**Choosing the right performance metric:**

    	Balanced Data: Accuracy.
    	Imbalanced Data: Precision, recall, F1 score, AUC.
        
**Sampling methods:**

    	Over-sampling.
    	Down-sampling.
        
**Weighted classes**

        Penalized learning algorithms.
 
## Transform: Reproducibility Design Pattern
**Separate input from features**

        Extract features from raw input.
    
**Transformation and Preprocessing:**

        	Standardization.
        	Scaling.
        	Encoding.

## Checkpoints: Model Training
**Snapshot of a model’s internal state:**

            To keep models especially deep learning models from unexpected events like power outages, operating system problems, interruptions in tasks, or other types of errors.
            
        	Keep Weights and current learning rate.
        	Keep a checkpoint at the end of every epoch.
        	Save the model with the best accuracy.


## Workflow Pipeline: Reproducibility

        Isolate and containerize the individual steps of a machine learning workflow into an organized workflow.
        Repeatable Model.
        Ensure maintainability and scalability.
        MLOps.



## Explainable Predictions: Responsible AI
**Separate input from features**

        Clear understanding of the model behavior.
       	Diagnose errors.
	    Identify potential biases (Fair and Unfair biases).

**Model Explainability:**

           	understand why and how the model made the predictions in a certain way.
           	Python libraries for model explainability: ELI5, SHAP and LIME.
