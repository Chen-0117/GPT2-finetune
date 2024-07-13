# Emotional Chatbot
## The problem and why it is important
+ Gap in digital interactions due to lack of emotional understanding.
+ There's a critical need for empathetic, effective communication in digital assistants, enhancing user experience and engagement.
+ Driven by a passion for AI to foster human-like interactions.
+ Motivated by the vast potential in improving customer service and mental health support.
## Data Overview
Friends Corpus - Utterance-level information

67,373 rows of text with emotions

train/test = 0.9 
<img width="464" alt="image" src="https://github.com/user-attachments/assets/fab59644-9e4b-4b6e-8199-f22f7f3097e6">

## Limitations & Challenges
+ Imbalanced Data
+ Emotion Complexity
+ Limited Emotional Labels
+ Annotation Inconsistency

## Model Pipline
<img width="726" alt="image" src="https://github.com/user-attachments/assets/8a92f3c8-a071-476a-a1f4-32c5df48339a">

## Discussion
+ Small Training Dataset: The limited size of the dataset restricts the model's ability to generate diverse and contextually appropriate responses.
+ Over Reliance on Specific Sources: The model frequently uses sentences directly from the TV show "Friends," indicating a lack of diverse linguistic patterns in its responses.
+ Contextual Appropriateness: While capable of matching the emotional tone of inputs, the model struggles with providing responses that are relevant and appropriate to the given context.

## ROUGE-L Comparison
Outstanding Performance of Our Chatbot Model Compared With Untrained GPT-2.
<img width="551" alt="image" src="https://github.com/user-attachments/assets/45e7c856-f428-4780-90cb-7468addeb062">

## Future Improvement
+ Expand the Training Dataset: Increasing the size and diversity of the dataset can help improve the model's understanding of different contexts and emotional tones.
+ Refine Loss Optimization: Adjusting the approach to optimizing the loss function may enhance the model's ability to generate more contextually relevant responses.
+ Diverse Source Material: Incorporating a wider range of linguistic sources could help reduce the model's overreliance on specific patterns or phrases.


 
