# SureStart
## Responses
#### Day 1, July 6
I'm excited to learn more about deep learning algorithms and how to improve models. Also, I the create-a-thon aspect sounds like a new and interesting approach to AI, compared to my previous experiences in the field.
#### Day 2, July 7
Having been a long-time creative writer, I found it interesting how elements of storytelling can be used to create a compelling argument and get people to listen, two important qualities of effective leadership.
#### Day 3, July 8
##### What is the difference between supervised and unsupervised learning?
Supervised learning is when the model is given the answers and given feedback after each training step. Examples include regression tasks and classification tasks. In contrast, unsupervised learning is when the model is expected to find patterns in the data without any feedback regarding the correct answer. The primary task for unsupervised learning is clustering.
##### Describe why the following statement is FALSE: Scikit-Learn has the power to visualize data without a Graphviz, Pandas, or other data analysis libraries.
Scikit-learn specifically has the tools needed to sort through and describe data and produce decision trees. However, it does not include the ability to produce images; graphs and diagrams produced by other Python libraries are needed in order to visualize the data in a way that is easy for humans to understand.
#### Day 4, July 9
One problem that I think could be solved with machine learning is spam detection. Currently, the softwares involved in spam detection are extremely inaccurate, and more often than not, manual rules are far more helpful than the hundreds of crucial emails that go unread due to them being classified as spam (which necessitates reading through emails labelled as spam, which defeats the whole purpose of the algorithm).

Here's a dataset I found sorting emails into "ham" or spam. https://www.kaggle.com/uciml/sms-spam-collection-dataset

I think simple algorithms like the decision tree we made for practice would be rather ineffective at such a complex problem, seeing as how currently-implemented algorithms do absolutely terribly at this task. Rather, I think that a more complex algorithm involving natural language processing and deep learning might do better.

As a side note, I think there ought to be an option to enable spam algorithms to become tailored to individuals' preferences. What some people consider spam may not be necessarily identical to another's idea. Some are clearly important or spam, but I think there is an enormous gray area.

#### Day 7, July 12
##### What are “Tensors” and what are they used for in Machine Learning?
Tensors are a way to store data in multiple "dimensions," with scalars being a "0-dimensional tensor," vectors being a "1-dimensional tensor," matrices being a "2-dimensional tensor," and so on. Tensors are used to represent data, which can be used by machine learning libraries like TensorFlow to learn patterns.
##### What did you notice about the computations that you ran in the TensorFlow programs (i.e. interactive models) in the tutorial?
One thing I noticed was that while the TensorFlow tutorial and the Keras tutorial both ended up teaching us how to make an ML model, the Keras code was a lot more intuitive and made more sense.

#### Day 8, July 13
Although I already knew about activation functions and problems like vanishing/exploding gradients, I never really understood why exactly vanishing/exploding gradients exist until now. I learned about how activation functions mitigate this problem by fixing values between 0 and 1 (or -1 and 1), though it isn't a perfect solution for deep networks.

#### Day 9, July 14
I learned that maxpooling is not the only type of pooling used for CNNs, as there is also average pooling. I also learned about bias a variance and how they relate to overfitting and underfitting.

#### Day 10, July 15
##### How do you think Machine Learning or AI concepts were utilized in the design of this game?
The creators of the game specifically chose the results of the "AI" to reflect how real AI models might learn and then exaggerate trends in the dataset that ought not to be used as a determining factor in the applicants' qualification for a job position. In this example, the "AI" "learned" that people from the Orange region (and therefore colored orange) tended to be slightly more likely to be qualified for a job position, and since this was the most reliable factor for the AI to latch onto, it exaggerated the results, forming a major discriminatory boundary.

##### Can you give a real-world example of a biased machine learning model, and share your ideas on how you make this model more fair, inclusive, and equitable? Please reflect on why you selected this specific biased model.
The first one that comes to mind was the iPhone photo labelling model, which mistakenly labelled a person with dark skin as a gorilla (and of course causing an uproar). This was likely due to a lack of diversity in the dataset of human faces (with a large proportion of lighter-skinned people), so a possible "fix" would have been to equalize the dataset, either by getting more data or removing data so that each racial group are represented fairly equally in the dataset.

#### Day 11, July 16
I learned about the overall architecture of a typical CNN model and why batches of images are usually fed into the CNN at once, saving computational power.

#### Day 15, July 20
ReLU is a very popular activation function for hidden layers, particularly in CNNs. It is computationally easy because the function is simple. It is also beneficial in that it creates a lot of sparsity (0-valued outputs), which helps better streamline the outputs of the machine learning model. 

#### Day 17, July 22
Today, I learned about image classification and the various challenges that come with it, such as intra-class variation, viewpoint variation, occlusion, illumination, and a cluttered image. I also learned about image classification vs. object localization vs. object detection.

#### Day 21, July 26
Today, I learned about autoencoders, which are a form of unsupervised learning that attempt to reconstruct images similar to the original dataset by first encoding then decoding information, with an information bottleneck in the middle.

#### Day 22, July 27
Today, I learned about the challenges with detecting emotion through AI, as it is multi-faceted and involves many cues beyond just the words we use, including body language, tone of voice, and context. I also learned about affective AI, which tries to overcome these challenges to detect mental states such as drowsiness while driving.

#### Day 23, July 28
I learned about natural language processing (NLP), which are usually done by RNNs or similar architectures. I also learned about the processing that occurs before even running the model, such as data preprocessing and feature extraction. Since language is complicated, simplifying the data through lemmatization or extracting important features (vectorizing the sentence) via methods such as bag of words, TF-IDF, or word2vec can make it easier for the model to learn from the data.

#### Day 24, July 29
I learned more about object detection and computer vision. What I found most interesting was the sheer number of different ways a person can implement computer vision, from simple image classification to object segmentation and even object tracking. This could also be extended to image generation, style transfer, colorization, and super-resolution. I also learned about GANs, which I think is a brilliant idea, as the model is, in a sense, training itself.

#### Day 25, July 30
We went through an overview of what we had learned so far, which I found very useful in coalescing four weeks' worth of materials into a firm idea in my head. I also gained valuable lessons in entrepreneuring, with the most valuable take-away being, in my opinion, to try to find problems that relate to many people, not just yourself and close family and friends, as this will make the end product meaningful to more than just its creator.

#### Day 28, August 2
Today, we didn't exactly learn much, but we spent much of the day brainstorming ideas for our Create-a-Thon project, discussing problems, potential AI-related solutions to those problems, and pros and cons to each problem and solution.

#### Day 29, August 3
Today, I learned about identifying the exact problem that needs to be addressed and asking the right question. For example, there was the example of Henry Ford asking "What do you want?" and receiving "faster horses" for a response. Yet the real answer was "faster transportation," which Ford then solved with his Model T car.

#### Day 30, August 4
Today, I learned about what it means to design a product and how to go about creating the design. One thing that stood out to me was the advice to start with the low-fidelity sketch first to get a general, big-picture idea of how it works before working out the high-fidelity details.
