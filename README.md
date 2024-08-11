# ChatBot_DeepLearning

Developed a chatbot capable of answering questions based on a "story" provided to it, utilizing NLP techniques and neural network models.

### About the Project:
Chatbots powered by Deep learning using NLP are revolutionizing real-time applications across industries by delivering intelligent, context-aware interactions. They optimize customer support, assist in preliminary medical diagnoses, streamline financial transactions, and enhance education through personalized tutoring. These chatbots effectively process natural language, enabling precise responses to complex queries while continuously improving their performance and accuracy.

The dataset is structured with 10,000 samples for training and 1,000 samples for testing. Each sample includes a Story, which consists of one or more sentences that provide the necessary context. Accompanying the story is a Question, a single-sentence query that pertains to the story's content. The Answer is a binary response, either "yes" or "no," indicating whether the information in the story supports the question. This allows for the evaluation of models responding to context-based queries more accurately.

It includes the following layers: Embedding, LSTM, Dropout, Dense and Activation. The design of the model follows the idea "End-to-End Memory Networks".
Stores information in a memory component, allowing the model to reference past data when needed. Focuses on relevant memory parts using attention, helping the model decide what information is important. Trains the entire system, including memory and attention, in one go for cohesive learning. Enables the model to make several passes over the memory to gather and refine information before generating output. Suited for tasks that need reasoning over long sequences or contexts, such as answering complex questions or maintaining a conversation in chatbots.

Also, tested the chatbot with real-time questions to evaluate its performance. I asked various questions and assessed the chatbot's ability to provide accurate answers, measuring its accuracy in responding to these queries.

The chatbot demonstrated an accuracy rate of approximately 96.76% in answering real-time questions.


### Future Avenues:
1. Improved NLP: Enhanced understanding of context and user intent for more accurate responses.
2. Multimodal Interaction: Integration of text, voice, and visual inputs for richer user interactions.
3. Emotional Intelligence: Ability to recognize and respond to user emotions for better engagement.
4. Increased Integration and Security: Interaction with IoT devices and stronger measures to protect user data.
