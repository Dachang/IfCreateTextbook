## Human Learning and Machine Learning

Learning is the act of acquiring new or reinforcing existing knowledge, behaviors, skills or values. To rapidly make sense of a world, babies instinctively learn by observing elements of that world. The discrete pieces of information — faces, places, objects — are then rapidly transformed into concepts, forming a flexible framework that lets babies ask questions beginning with “what.” But babies aren’t just observers. By watching others, babies pick up essential skills, social rules and laws of nature. They then categorize them into concepts and combine these building blocks in new ways to invent new solutions.

We do not code specific sets of rules — for example, what makes a cat a cat — to teach machines. Instead, the best approach currently is to provide the computer with thousands of examples and let the algorithm figure out the best solution. But unlike people, machines can not generalize what they have learned to new problems.

## Machine Learning

Machine learning focuses on the development of computer programs that can access data and use it learn for themselves. The process of learning begins with observations or data, such as examples, direct experience, or instruction, in order to look for patterns in data and make better decisions in the future based on the examples that we provide. The primary aim is to allow the computers learn automatically without human intervention or assistance and adjust actions accordingly.

## Supervised learning

Supervised learning can apply what has been learned using labeled examples to predict future events. Starting from the analysis of a known training dataset, the learning algorithm produces an inferred function to make predictions about the output values. The system is able to provide targets for any new input after sufficient training. The learning algorithm can also compare its output with the correct, intended output and find errors in order to modify the model accordingly. 

## Unsupervised Learning

Unsupervised learning is used when the information used to train is neither classified nor labeled. Unsupervised learning studies how systems can infer a function to describe a hidden structure from unlabeled data. The system doesn’t figure out the right output, but it explores the data and can draw inferences from datasets to describe hidden structures from unlabeled data. 

## Reinforcement learning

Reinforcement learning is a learning method that interacts with its environment by producing actions and discovers errors or rewards. It helps us formulate reward-motivated behavior exhibited by living species. Let’s say, you want to make a kid sit down to study for an exam. It is very difficult to do so, but if you give him a bar of chocolate every time he finishes a chapter/topic he will understand that if he keeps on studying he will get more chocolate bars. So he will have some motivation to study for the exam. Now initially the kid has no sense of time or how to prepare (he might go through every line and ponder upon it). He might take up hours studying a topic and never finish the syllabus in time. So, let’s say if he finishes a topic within an hour we give him a huge bar, if he takes 1.5 hours a regular bar and a toffee if he takes longer than that. So, now not only does he study but his brain devises ways in which he can finish topics faster. The kid represents the Agent. The reward system and the exam represent the Environment. The topics are analogous to States in reinforcement learning. So, the kid has to decide which topics to give more importance to (i.e., to calculate the value of each topic). This will be the work of our Value-Function. So, every time he travels from one state to another he gets a Reward and the methods he uses to complete the topics within time is our Policy. This is carried out by our Dopamine system in our brain which takes care of reward-motivated behaviour.

Trial and error search and delayed reward are the most relevant characteristics of reinforcement learning. This method allows machines and software agents to automatically determine the ideal behavior within a specific context in order to maximize its performance. Simple reward feedback is required for the agent to learn which action is best; this is known as the reinforcement signal.

## Classification

Classification is a kind of supervised learning problems, we start with a data set containing training examples with associated correct labels. For example, when learning to classify handwritten digits, a supervised learning algorithm takes thousands of pictures of handwritten digits along with labels containing the correct number each image represents. The algorithm will then learn the relationship between the images and their associated numbers and apply that learned relationship to classify completely new images (without labels) that the machine hasn’t seen before. 

## Regression

Regression predicts a continuous target variable. It allows you to estimate a value, such as housing prices or human lifespan, based on input data. Here, continuous means there are not gaps (discontinuities) in the value that can take on. For example, A person’s weight and height are continuous values. Discrete variables, on the other hand, can only take on a finite number of values — for example, the number of kids somebody has is a discrete variable. Predicting income is a classic regression problem. Your input data includes all relevant information about individuals in the data set that can be used to predict income, such as years of education, years of work experience, job title, or zip code. These attributes are called features, which can be numerical (e.g. years of work experience) or categorical (e.g. job title or field of study).

## Clustering

Clustering is a method of unsupervised learning. that involves the grouping of data points. Given a set of data points, we can use a clustering algorithm to classify each data point into a specific group. Data points that are in the same group should have similar properties and/or features, while data points in different groups should have highly dissimilar properties and/or features. 

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Dachang/IfCreateTextbook/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
