# Data Science Projects in Python

## [Dynamic Time warping for Serial Correlation Analysis of Stock Market](https://github.com/TimoKropp/DTW-stock-analysis/blob/master/dtw_stock_analysis.py)
Dynamic time warping (DTW) is one of the algorithms for measuring similarity between two time series. The data may vary in time and amplitude with example applications in analysis of temporal sequences of video, audio, and graphics data or in general any data that can be turned into a linear sequence. One of the most recent applications is found in automatic speech recognition coping with different speeds of speaking. In this project, the DTW algorithm is used for a serial correlation analysis of stock market prices, for example the Nasdaq (NDAQ) from 2019-01 to 2020-08 as shown in the figure below.

 ![](/images/stock_analysis.png)
 
The minimum of the transformaton distance (excluding 2 times the correlation interval from the present date) indicates the best correlation (light green) with a start interval at the location of the minimum and the duration of the correlation period (dark green). 

Lessons learned:  
* Stock market data import to python
* Work flow with dataframes
* Dynamic time warping using fastDTW
* Time series analysis for seriel correlation
### [Click here for interactive notebook in your browser](https://mybinder.org/v2/gh/TimoKropp/DTW-stock-analysis/master)
# 1-Day Animation Projects in Python

## [Galton Board](https://github.com/Timokko/GaltonBoard/blob/master/GaltonBoard.py)
From Wikipedia:
The bean machine, also known as the Galton Board or quincunx, is a device invented by Sir Francis Galton to demonstrate the central limit theorem, in particular that with sufficient sample size the binomial distribution approximates a normal distribution. Among its applications, it afforded insight into regression to the mean or "regression to mediocrity".The Galton Board consists of a vertical board with interleaved rows of pegs. Beads are dropped from the top and, when the device is level, bounce either left or right as they hit the pegs. Eventually they are collected into bins at the bottom, where the height of bead columns accumulated in the bins approximate a bell curve.

 ![](/images/galton.gif)
 
Lessons learned:  
* Using pygame for animation
* Object orientated programming
* Insights in statistics and distribution patterns

## [Lonely Runner Conjectur](https://github.com/TimoKropp/LonelyRunner/blob/master/lonely_runner.py)
From Wikipedia:
Consider *k* runners on a circular track of unit length. At *t* = 0, all runners are at the same position and start to run; the runners' speeds are pairwise distinct. A runner is said to be lonely at time t if they are at a distance of at least *1/k* from every other runner at time *t*. The lonely runner conjecture states that each runner is lonely at some time.

 ![](/images/lonely_runner.gif)
 
 Lessons learned:    
* Using pygame for animation
* Object orientated programming
* Insights in geometry and number theory

# Game Development in Unity (C#)
## [3D Dodgeball Arena]()

In this game project developed in Unity(C#) you can play a robot in a sci-fi world with inverted gravity on the inside of a sphere. It is a fast paced multiplayer third-person game where you battle against other players online in a dodgeball arena. You can shoot a flighing orb as a guided missile to the next opponent. Dodging with special abilities like a fast charge forward or sliding unterneath the incoming orb to give it an extra spin upwards makes this game fun do play, easy to learn but hard to master. 

 ![](/images/dodgeball.png)
 
 Lessons learned:  
* 3D Game design
* C# scripting
* Realtime multiplayer networking with PhotonNetworking (PUN 2)
* User Interface development
