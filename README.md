# Model Recompilation 

Experimentation around resizing models to different shapes and the effect on model performance  

The main idea is to see whether you can take a pre-trained model and copy its weights into an entirely different model architecture (i.e. re-wiring the connections between the parameters). The intuition is that if the model's weights store a knowledge base then you should be able to retrieve information from those weights even if the model is rewired in a slightly different way - perhaps by re-compiling that information you can induce different behavior of the model while perserving some of the information that is stored in a compressed manner within the weights. 

