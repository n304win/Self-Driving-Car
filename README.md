# Behavioral Cloning For Self Driving Cars

Transfer learning for end to end autonomous driving using pre trained ResNet50 weights in google colab.

Check out the corresponding medium blog post [https://medium.com/@abhinav.sagar/how-to-train-your-self-driving-car-using-deep-learning-ce8ff76119cb](https://medium.com/@abhinav.sagar/how-to-train-your-self-driving-car-using-deep-learning-ce8ff76119cb).

## Goal

Train a end-to-end deep learning model that would let a car drive itself around the track in a driving simulator.

## Data collection

In this project Udacity driving simulator has been used which has two different tracks. One of them was used for collecting training data, and the other one — never seen by the model — as a substitute for test set.

The driving simulator would save frames from three front-facing "cameras", recording data from the car's point of view; as well as various driving statistics like throttle, speed and steering angle. We are going to use camera data as model input and expect it to predict the steering angle in the [-1, 1] range.

## Results

<p align="center">
  <img src="run.gif" alt="Driving"/>
</p>

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


