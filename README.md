# Master in Bioinformatics and Functional genomics
Some exercises and example for the neural networks section of the course.

## Setup
To setup everything needed for the lessons, once you have python and git installed on your system, please run the following script in your terminal:
```bash
  git clone https://github.com/LucaCappelletti94/Master-in-Bioinformatics-and-Functional-genomics.git
  cd Master-in-Bioinformatics-and-Functional-genomics
  python -m pip install --upgrade -r requirements.txt
```

## Lessons
### [1 - Lesson on MLP](https://github.com/LucaCappelletti94/Master-in-Bioinformatics-and-Functional-genomics/tree/master/1%20-%20Lesson%20on%20MLP)

In [this lesson](https://github.com/LucaCappelletti94/Master-in-Bioinformatics-and-Functional-genomics/tree/master/1%20-%20Lesson%20on%20MLP), we will learn how to use a multi-layer perceptron to predict the values of an arbitraty *unknown* function.

### [2 - Practice on MLP](https://github.com/LucaCappelletti94/Master-in-Bioinformatics-and-Functional-genomics/tree/master/2%20-%20Practice%20on%20MLP)

In [this lesson](https://github.com/LucaCappelletti94/Master-in-Bioinformatics-and-Functional-genomics/tree/master/2%20-%20Practice%20on%20MLP), after learning how to load and execute a preliminary analysis on a real dataset, we will create an MLP model and introduce the concept of Dropout layers. Guided free experimentation will follow.

### [3 - Lesson and practice on CNN](https://github.com/LucaCappelletti94/Master-in-Bioinformatics-and-Functional-genomics/tree/master/3%20-%20Lesson%20on%20CNN)

In [this lesson](https://github.com/LucaCappelletti94/Master-in-Bioinformatics-and-Functional-genomics/tree/master/3%20-%20Lesson%20on%20CNN) we will learn how to create a convolutional neural network that can learn patterns, afterwards we will proceed to create a neural network that repairs a pattern.

### [4 - Lesson on prediction active regulatory regions](https://github.com/LucaCappelletti94/Master-in-Bioinformatics-and-Functional-genomics/tree/master/4%20-%20Lesson%20on%20prediction%20active%20regulatory%20regions)
In [this lesson](https://github.com/LucaCappelletti94/Master-in-Bioinformatics-and-Functional-genomics/tree/master/4%20-%20Lesson%20on%20prediction%20active%20regulatory%20regions) we have practiced with the preparation of the active regulatory regions dataset (retrieving data, one-hot encoding data, quick dataset analysis, preparation of the labels for training) and used the data for training a simple MLP.

### 5 - 27/05/2019 - Creating, testing and deploying a neural network

In this lesson, in a step by step fashion, we created a MLP trained on the standard dataset Boston Housing and proceeded with guided experimentation in class with its model structure. Afterwards, a simple pytest test was created to test the model in a CI fashion.
Finally, a simple example of the neural network deployment for production was shown.

## Additional materials
In this brief course we could not touch as deeply as we would like to a number of topics, so here are a few links that any of you could explore. I tried to select only materials that I enjoyed and that I would love to watch again.

### 3Blue1Brown
This is a youtube channel with great animations which can show you in an enjoyable way what a neural network is:
- [What is a neural network?](https://www.youtube.com/watch?v=aircAruvnKk&t=1s)
- [Gradient Descent](https://www.youtube.com/watch?v=IHZwWFHWa-w)
- [Backpropagation - high level](https://www.youtube.com/watch?v=Ilg3gGewQ5U)
- [Backpropagation - low level](https://www.youtube.com/watch?v=tIeHLnjs5U8)

### Tesla
The presentation of how they cracked autonomous driving at Tesla:
- [Tesla: autopilot day](https://www.youtube.com/watch?v=Ucp0TTmvqOE)

### Welch labs
A small video playplist on neural networks:
- [Neural networks demistified](https://www.youtube.com/watch?v=bxe2T-V8XRs)

### Kurtzgesagt
The rise of automation
- [The Rise of the Machines – Why Automation is Different this Time](https://www.youtube.com/watch?v=WSKi8HfcxEk&t=27s)

### CGP Grey
A video showing how artificial intelligence will be taking our jobs way before it becomes sentient:
- [Humans need not apply](https://www.youtube.com/watch?v=7Pq-S557XQU)
