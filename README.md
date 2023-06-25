# Modern Artificial Intelligence final project
Our final project is to implement a hide and seek game in an environment that we created.  
We have to character in this game, police and theif, these two character are both turtlebot. Our goal is using Q-learning to train the police and the theif that the police can successfully catch the theif and the theif will try to escape from the police.  
In our environment, there are 25 pressure plates and 2 outlets, if the thief go through the pressure plates, then the police will get the position of the thief. And the goal of the thief is to arrive the two outlets.  
Since our environment for the theif is disadvantage, our prediction is that if we finish our training correctly, the police can catch the thief very often.  
The experiment was doing on the Python first, to make sure our algorithm is correct, after that we simulated on ROS.  

I think our algorithm has some error, so that we can not train these two bot very well.
