---
layout: as-physics
title: AS Physics
date: 2021-01-23 18:05:40
tags:
description: A short summary for AS physics lecture and exercises. Basic formula and definitions, concepts, and solutions are included. Specifically, review projects are offered at the end of each chapter.  
mathjax: true
---
# Part 1: Mechanics
## Chapter 1  Kinematics

## Chapter 2  Dynamics: Newton's Law

## Chapter 3  Forces

## Chapter 4  Energy

## Chapter 5  Momentum

## Chapter 6  Elasticity

## Chapter 7 Circular motion

## Review Project 1: Crazy Alex Yu

<center>
<img src="./AS-Physics/figure.png" width=70% />
</center>

Alex Yu wants to go to the tower across the river. There is no bridge, no boat,
no plane, no any transportation. But she is crazily enthusiastic. She must arrive the tower.

Her teacher, Isaac Wang, is helping her design a
crazy facility so that this crazy guy and arrive the other side of the river.

### Part 1: Ejection from the spring

She sits in a small chair with wheels, holding on the spring by a rod which is
attached to an rolling axis. A known force $F$ is pushing the top of the rod so
that Alex is holding at the position. The spring is compressed. The platform is
smooth. Then release the force $F$, she is ejected, and flies out the platform at point A.

Known quantities: force $F$, rod length $l$ and $3l$, spring constant $k$, and mass of you and your car $m$.

- Initially, Alex is hold at that position. What is the force from the spring that makes her in equilibrium?
- How much length is the spring compressed?
- Once she is well prepared, the force $F$ is released, and Alex is ejected out. What is the speed of her after she leaves the spring?
  
**Solutions** : 
- For Alex, two forces are exerting on her: the spring force and the rod force. For the rod, two forces combined to keep it in rotation equilibrium: the force from Alex, and the external force $F$. Thus we can write down the equation for the equilibium of the rod rotation:
$$
  F_{spring} l=F \cdot 3l
$$
Thus we have 
$$
F_{spring} = 3F
$$

- The spring force is given by the Hooke's law: $F_{spring} = k \Delta x$, so we have
$$
\Delta x = \frac{3F}{k}
$$

- Here, the elastic potential energy stored in the spring is transformed into the kinetic energy of Alex. The initial elastic potential energy is:
  $$
  E_p = \frac{1}{2}k \Delta x^2
  $$
  The final kinetic energy is:
  $$
  E_k = \frac{1}{2} m v^2
  $$
  We have $E_p = E_k$, so the velocity is:
  $$
  v_A=\frac{3F}{\sqrt{mk}}
  $$

### Part 2: Flying in the sky

After ejected from the platform, she flies in the sky and exactly enters the track at point B.
(by "exactly", it means that the velocity direction is exactly parallel to the direction of the track at point B)

Known quantities: the angle $\theta$, and all the quantities solved above.

- What is the initial velocity when she flies out from the platform?
- What is the horizontal and vertical velocity at point B?
- How much time does she fly from A to B?
- What is the horizontal and vertical distance from A to B?

**Solutions**:

- Of course the initial velocity is just the velocity $v_A$.
- From A to B, Alex has two motions: in horizontal direction, the motion is at a constant velocity. While at vertical direction, it's at a constant acceleration $g$ with zero initial velocity. So the horizontal velocity at B is still equals to that at A: 
  $$v_{Bx}=v_A$$
  
  We do not know the time so far, so we cannot directly calculate the vertical velocity at B. However, we know that the direction of the total velocity at B is along $\theta$, so 
  
  $$v_{By} = v_{Bx} \tan \theta = v_A \tan \theta$$

- Now we can solve the time: from 
  $$v_{By} = g t$$
  we get
  $$t_{AB} = v_{By}/g = \frac{v_A \tan \theta}{g}$$ 

- With time calculated, we can immediately get the displacement:
  $$
  x_{AB} = v_A t_{AB} = \frac{v_A^2 \tan \theta}{g} \\
  y_{AB} = \frac{1}{2} g t_{AB}^2 = \frac{v_A^2 \tan^2\theta}{2g}
  $$

### Part 3: Running in the track

After she enters the track at point B, she runs along the track and finally arrives C. No energy lost at point B during she enters the track. But remember, this car has no engine.

The track is smooth, but not straight. No energy lost while moving in the track.

Known quantities: height between B and C $h_{BC}$, and the quantities calculated above.

- What is the kinetic energy at point B?
- What is the change of gravitational potential energy from B to C?
- What is the speed at point C?

**Solutions**:
- Kinetic energy is simply:
  $$
  E_k = \frac{1}{2}m v_B^2
  $$
- The gravitational potential gets higher. Since we know that
  $$
  h_{BC} = h_C - h_B
  $$
  we know that
  $$
  \Delta E_{p}=E_{pC} - E_{pB} = mgh_C - mgh_B = mgh_{BC}
  $$
  This is a positive value.
- During this process, energy is conserved: kinetic energy is transferred into gravitational potential energy. We can write down:
  $$
  \Delta E_k = \frac{1}{2}m(v_C^2 - v_B^2) = -\Delta E_p = -mgh_{BC}
  $$
  Solve this equation and we can get 
  $$
  v_C = \sqrt{v_B^2 - 2gh_{BC}}
  $$

### Part 4: Running along the slope

After finishing the track, she arrives point C. Now the tower is exactly at D. Only a straight way remaining! No energy lost at point C. That means, the speed at C when her leave the track BC is the speed that she starts moving along CD.

But this way is not smooth. The friction is $f$. She exactly stops at D finally.

Known quantities: slope of CD $\alpha$, and all the quantities calculated above.

- How many forces are exerting on her?
- What is her acceleration?
- She finally stops at D. How long is CD? How much time does it take?

**Solutions**: 
- Gravity, supporting force from the slope, and friction.
- Decompose the forces along the slope. Friction is down along the slope. One componenet of gravity also points down along the slope. So the acceleration is given by:
  $$
  f+mg\sin \alpha = ma
  $$
  so
  $$
  a = g\sin \theta + \frac{f}{m}
  $$

- Write down the equation:
  $$
  0 - v_C^2 = -2 a l_{CD}
  $$
  so
  $$
  l_{CD} = \frac{v_C^2}{2(g \sin \theta + f/m)}
  $$

**Congratulations to Alex Yu. She finally arrives the tower! (Although she is
crazy...) Let's move on to the next journey!**


# Part 2: Thermal Physics

# Part 3: Electricity and Magnetics

# Part 4: Modern Physics