# Behavioral Cloning For Self Driving Cars

Implementation of the paper "End to End Learning for Self-Driving Cars"

## IMPORTANT

Absolutely, under NO circumstance, should one ever pilot a car using computer vision software trained with this code (or any home made software for that matter).

This code is purely for research and statistics, absolutley NOT for application or testing of any sort.

## If this repository helps you in anyway, show your love :heart: by putting a :star: on this project :v:

Check out the corresponding medium blog post [https://towardsdatascience.com/how-to-train-your-self-driving-car-using-deep-learning-ce8ff76119cb](https://towardsdatascience.com/how-to-train-your-self-driving-car-using-deep-learning-ce8ff76119cb).

## Goal

Train a end-to-end deep learning model that would let a car drive itself around the track in a driving simulator.

## Data collection

In this project Udacity driving simulator has been used which has two different tracks. One of them was used for collecting training data, and the other one — never seen by the model — as a substitute for test set.

The driving simulator would save frames from three front-facing "cameras", recording data from the car's point of view; as well as various driving statistics like throttle, speed and steering angle. We are going to use camera data as model input and expect it to predict the steering angle in the [-1, 1] range.

## Results

<p align="center">
  <img src="run.gif" alt="Driving"/>
</p>

## References

1. https://arxiv.org/pdf/1604.07316.pdf

2. http://cs231n.stanford.edu/reports/2017/pdfs/626.pdf

## Citing

```
@misc{Abhinav:2019,
  Author = {Abhinav Sagar},
  Title = {Self Driving Car},
  Year = {2019},
  Publisher = {GitHub},
  Journal = {GitHub repository},
  Howpublished = {\url{https://github.com/abhinavsagar/Self-Driving-Car}}
}
```

## Contacts

If you want to keep updated with my latest articles and projects follow me on Medium. These are some of my contacts details:

1. [Personal Website](https://abhinavsagar.github.io/)
2. [Linkedin](https://in.linkedin.com/in/abhinavsagar4)
3. [Medium](https://medium.com/@abhinav.sagar)
4. [GitHub](https://github.com/abhinavsagar)
5. [Kaggle](https://www.kaggle.com/abhinavsagar)

