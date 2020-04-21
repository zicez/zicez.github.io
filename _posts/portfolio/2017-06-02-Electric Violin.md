---
layout: article
title: MASLAB - No Motorcycles Allowed
categories: portfolio
share: false
image:
    feature: /maslab/3.jpg
    teaser: /maslab/3.jpg
---
2018 IAP MASLAB Competition

#### No Motorcycles Allowed
MASLAB is a competion in which teams will build a fully autonomous robot to complete a challlege. Our team, No Motorcycles Allowed, built Mr. Motorcycle. The year challenge involves collecting color balls and then depositing them into the corresponding goals. Our team won first that year. 

#### Mechanism Design
The design of the robot is very simple. We opted for simplicity because we really only had 3.5 weeks to put together a robot. It has two powered wheels in front and one ball caster in the back. In the front of the robot, we had a collection mechanism which is a roller made with rubber bands. The roller is powered by a DC motor geared down to the approriate rotation speed. The roller with the rubber bands allows the robot to grip onto the wooden balls. Behind the roller is an inclined ramp, so the balls are always guaranteed to be against the roller. This allows the roller to push the ball out when needed. We built a tower up above from the robot, so we can attach cameras higher up. This allowed the robot to have a better vantage views over the field. Additionally, we mounted proximity sensors around the perimeter of the robot.

#### Operating Algorithm
The robot operates in a very simple algorithm. It starts out in the collection state. It moves in a straight line with the collector in front constantly spinning. When it detects that it is near a wall with the proximity sensors, it will spins away from the wall and then continue to move in a straight line. As it travels randomly around the arena, the camera will try to detect for colored balls on the field, and when it does, it moves toward the ball to collect it. 

Finally, when it has collected all the balls or after a certain amount of time (a time out), the robot then switch to the depositing state. It stops wall bouncing and starts wall following. As it moves around the perimeter of the arena, it searches for the corresponding goal to deposit the balls. Once it found the right goal, it goes into a fixed maneuver to deposit the balls. It turns toward the goal then back far away from the goal. This allows the robot to better align with the goal. It then finally goes head first into the goal and then reverse the roller to push the balls toward the goal.  

#### Images

| | |
|:-------------------------:|:-------------------------:|
|<img width="1604" alt="bridge_1" src="/images/maslab/1.jpg">|<img width="1604" alt="bridge_2" src="/images/maslab/2.jpg">|

|<img width="1604" alt="bridge_3" src="/images/maslab/3.jpg">|<img width="1604" alt="bridge_4" src="/images/maslab/4.jpg">|

#### In Action
I unfortunately did not collect any video of the fully working robot. Here are two videos of the robot partially working.

Collecting:
<iframe width="560" height="315" src="https://www.youtube.com/embed/4bo-fo4mORs" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Depositing:
<iframe width="560" height="315" src="https://www.youtube.com/embed/L7YV1Svg2pM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

     



