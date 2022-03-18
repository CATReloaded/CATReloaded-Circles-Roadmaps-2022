# **Animation**
### Introduction
Flutter is powerful in animation, you can build beautiful animations with flutter, building animation in Flutter is easy because Flutter provides you with tools to use it for building these animations. 

there are two kind of animations in Flutter 
* base_code animations
* drawing animation

#### Base_code animation
if you want to do some animations effects on existed widgets like  
{ `Column`, `ListView`, `Container`, `...` }
then you want to do base-code animation

#### Drawing animation
if you want to draw the animation itself from scratch, like drawing car moving fast or cat playing with ball
then you want to do drawing animation

---
### Animation types

* Tween animation
* Physics-based animation
 

##### Tween animation
Building animation with `Tween Animation` makes you needing to define a start value and end value, like changing the value of container's width from 100px to 200px the you need to build tween it's start value : 100 and end value : 200.

you can define the curve and the timeline for the `Tween Animation` for controlling the style and the duration of the animation

#### Physics-based animation
you can add more realistic and interactive to you animation with  
`Physics-based animation`, like making gravity effects on falling objects or throwback objects when it hit the wall (the constrains of the device).

---
### Decision road map
![image](images/animation-decision-tree.png)
