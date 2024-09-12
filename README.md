# Machine-Learning-for-Emotional-Intelligence
This is a proof-of-concept for a tool to help foster emotional intelligence and assist web-based mental health interventions, including apps, websites, hotlines, etc.

Emotional intelligence is defined as the ability to understand and harness our and others' emotions, and is a key factor in positively coping with personal hardship and empathetically dealing with interpersonal conflicts. It is a skill practiced by mental health professionals and volunteer counselors alike, as simply understanding our emotional state at a given moment can be challenging. By fostering emotional intelligence among the general public, the US' overtaxed mental health infrastucture might experience some relief.

I thus aimed to create a tool that could infer your emotional state based on two pieces of information - a photo of your facial expression and a caption of what had just happened. This approach should come as second nature among those who use social media frequently. If people simply understood what they were feeling, they coulf then adapt their thinking to solving the inner turmoil they are experiencing. Additionally, if this tool were implemented with an app, for instance, the app could then recommend resources specific to its users' emotional state.

To accomplish this, I utilize two machine learning models - a multilayer perceptron for the image data and a text classifier for the caption data - and a soft voting ensemble that combines their predictions. The model can predict one of seven emotions from the combined output of the two models with around 52% accuracy.

Image data was sourced from this project: https://www.kaggle.com/datasets/praveengovi/emotions-dataset-for-nlp
Text data was sourced from this project: https://github.com/Valendrew/ekman-emotion-detection
