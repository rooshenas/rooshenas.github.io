---
title: "Search-Guided, Lightly-Supervised Training of Structured Prediction Energy Networks"
collection: publications
permalink: /publication/sg-spen
excerpt: 'This paper is about training SPENs using indirect supervision that comes from reward functions. <br> <img style="width:40%; height:auto;" src="/images/sg-spen.png">'
date: 2019-10-27
venue: 'Neurips'
paperurl: 'http://rooshenas.github.io/files/sg-spen.pdf'
citation: 'Rooshenas, A., Zhang, D., Sharma, G., McCallum, A., .&quot; <i>Neurips 2019 1</i>'
---
This paper is about training SPENs using indirect supervision that comes from reward functions.
[Download paper here](http://academicpages.github.io/files/paper1.pdf)


--- 
Here I show the behavior of SG-SPEN on a toy 1-D dimensional problem, in which we have one output variable of 1000 dimension.
The reward function shows the reward value for each of these dimensions that the output variable can take.
<br> <img style="width:40%; height:auto;" src="/images/reward.png">

I plot the negative of the energy values during training. As we can see, the energy function approximates the relative position of important local optima. 
<br> <img style="width:40%; height:auto;" src="/images/energy.gif">

<br><br>
Here is a short video that describes the algorithm:
<video width="320" height="240" controls>
  <source src="/files/sg-spen.mp4" type="video/mp4">
</video>
