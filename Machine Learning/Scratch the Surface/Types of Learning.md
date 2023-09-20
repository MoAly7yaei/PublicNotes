tags: #explanation

related to: [[Create ML Model]]

To make any ML solution we have to get the data and fit it in any [[Learning Algorithms]] and algorithm has to be selected based on the [[General Use cases]].

# *Model = Algorithm + Data*

When Data is been fit it into the Algorithm we get the model that is able to predict or classify and types of Learning methods.

## Supervised Learning
It is about making the algorithm learns the changes and patterns and what will happen if those changes occur. Let's say I want to teach a child to understand the names of colors. So, I bring every color and tell him or her the names. This way, the child will be able to differentiate between colors and name the color of any object. The child can also describe what he or she wants to wear for a weekend trip or maybe even have a favorite color. Treat any Supervised Learning algorithm like a child, and you'll see that it needs to be trained with features (the color itself) and labels (the name of the color). After the algorithm is trained, the outcome is a model with the ability to classify based on the given features.

Even in prediction cases, if I want to teach a child how to cook and I want him or her to estimate the quantity of flour needed to make pizza, I show him or her that if I use one cup of flour, I'll get 2 pizzas. Hopefully, he or she will understand that if I want to make 6 pizzas, I will need 3 cups of flour. That's how a model is built; we give the algorithm the amount of flour as input and the number of pizzas as output. We then get a model that can predict the number of pizzas based on the provided amount of flour.

As practice, check out [[General Use cases]] and try to see how many use cases can be solved using Supervised Learning.

## Unsupervised Learning
Imagine you're trying to teach a child about animals, but this time you don't actually tell the child what each animal is called. You show them pictures of various animals like dogs, cats, birds, and fish. Slowly, the child starts to notice patterns and groups animals with similar features together like all the animals with feathers, or all those that swim. Essentially, the child is doing what Unsupervised Learning algorithms do: find patterns or clusters in the data without being explicitly told what to look for.

So, in the world of Machine Learning, Unsupervised Learning is like a curious kid exploring a toy box. The algorithm sorts through the data (the toys) and starts grouping them based on similarities or differences, even though you didn't give it specific labels (like "these are cars" or "these are dolls"). The end result? A model that understands the underlying structure of your data.

In cases where you're trying to detect anomalies, it's like if the kid spots a toy that's really different from the rest, like a spaceship among a bunch of cars. The child knows it's special because it doesn't fit with any of the other groups. Similarly, Unsupervised Learning algorithms can identify outliers or anomalies in the data set.

same as Supervised Learning, check out [[General Use cases]] and try to see how many use cases can be solved using Unsupervised Learning.

## Semi-Supervised Learning
Alright, think about it this way: You've got a pile of fruit, some apples and some oranges, but only a few of them have labels. You tell the kid, "These are apples, and these are oranges," but you only point out a couple from each group. The child starts sorting the fruits into two piles based on the labeled examples and their own observations.

Here's the kicker: the kid uses the initial labeled fruits (apples and oranges you pointed out) to understand the basic features—like color, texture, and size. But then, they also start using their own judgment to classify the rest of the unlabeled fruits. Maybe the child thinks, "Ah, this looks like those apples because it's round and red."

So, in the Machine Learning world, Semi-Supervised Learning is kinda like that smart kid who learns from both labeled (Supervised Learning) and unlabeled data (Unsupervised Learning). You start with a small set of labeled data and a larger set of unlabeled data. The algorithm uses the labeled data to kick-start its learning process and then further refines its understanding with the unlabeled data.

Why is this cool? Well, labeling data can be time-consuming and expensive, right? Semi-Supervised Learning gives you the best of both worlds—you save time and resources but still get a pretty accurate model.

same as Supervised and Unsupervised Learning, check out [[General Use cases]] and try to see how many use cases can be solved using Unsupervised Learning.