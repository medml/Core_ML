# Core_ML
This is where you'll find the notebooks we consider 'core' to learning medicine-relevant ML.

## Introductions
We'll have a set of introductory notebooks focused on interactively understanding ML and how it differs from what came before.

## Basic Concepts
### Training/Testing
One of the core concepts in ML is seeing your *data* separate from your *patient*.
If we just looked at all of our data and calculating stuff on it, there's a big chance we're analysing things that have nothing to do with our patient.

The idea of "training and testing" splits in ML is central to understanding how we can build big, complex models on data in a way that's trustworthy.
Think of it like a "virtual second experiment".

### Ethics and Bias
Everything we do introduces **bias**.
This means something specific in ML, but it also involves societal biases.
This is important to see early in your ML learning.

## Types of Models
### Regressions
Linear regression is the core of ML, all of it, so getting a solid foundation here is worth it!

Think of linear regression as a way to map from "lab values" to "health values"

### Classifications

Being able to tell which 'group' a dataset belongs to is largely what we're taught in medical school.
Symptoms = Data, and Groups = Diseases.
Using ML to assist us in this by seeing patterns that we can't easily see is a perfect starting point for us to understand ML.

### Neural Networks
Where all the 'excitement' seems to be happening in modern ML.
We'll have some simple notebooks meant to highlight how DL goes beyond traditional ML by using powerful computers.
Naturally, it'll be tough to run these live in a workshop so we'll be relying on other resources to bridge you towards full understanding.
