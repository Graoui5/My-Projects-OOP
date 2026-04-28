# My-Projects-OOP
# My Projects

##  Godot Game
#  Spearfishing Correction Game (Godot)

##  Project Description

This project is an interactive game developed using the Godot Engine.
It simulates the phenomenon of light refraction in water and its effect on visual perception.

The player attempts to hit a target located underwater. However, due to refraction, the perceived position of the target differs from its actual position. The goal of the game is to understand and correct this visual error.

---

##  Physics Concept

The game is based on the principle of light refraction when passing between two media (air and water).

When light travels from water to air, it bends, making objects appear closer to the surface than they actually are. This creates an error in aiming, similar to real-life spearfishing.

The relationship between real depth and apparent depth is approximately linear:

[
h = n \cdot h'
]

Where:

* ( h ): Real depth (actual position)
* ( h' ): Apparent depth (observed position)
* ( n ): Refractive index of water (≈ 1.33)

---

##  Game Objective

* The player clicks on the screen to aim at the target.
* Due to refraction, the click position is not accurate.
* The player must learn to adjust their aim to hit the real target.

---

##  Visualization

The game uses a linear model to represent the difference between:

* Observed position (apparent depth)
* Real position (true depth)

The gap between these two represents the **error caused by refraction**.

---

## Technologies Used

* Godot Engine
* GDScript
* Basic physics modeling (optics)

---

##  How to Run the Game

1. Open the project using Godot Engine.
2. Run the main scene.
3. Click to aim and try to hit the underwater target.
4. Adjust your aim based on the observed error.

---

##  Educational Purpose

This game helps students:

* Understand light refraction visually
* Relate physics concepts to real-life situations
* Improve intuition about optical phenomena

* 
##  Presentations
- Presentation 1:
- #  The Laser Grid (Plane Mirrors)

##  Project Description

This presentation explores the behavior of light when reflected by plane mirrors.
It is based on a laser security system scenario where a beam must be redirected using mirrors without triggering alarms.

The objective is to understand how light rays interact with reflective surfaces and how their paths can be controlled using geometric principles.

---

##  Physics Concept

The project is based on the **Law of Reflection**, which states:

[
i = r
]

Where:

* ( i ): Angle of incidence
* ( r ): Angle of reflection

This law applies to all reflections on plane mirrors.

---

##  Problem Overview

A laser beam strikes a first mirror ( M_1 ) at an angle of incidence:

[
i_1 = 30^\circ
]

The reflected ray then hits a second mirror ( M_2 ), which is perpendicular to the first mirror.

The study focuses on:

* Determining the reflection angle from the first mirror
* Calculating the new incidence and reflection angles on the second mirror
* Understanding the final direction of the beam

---

##  Key Results

* The angle of reflection on the first mirror equals the angle of incidence:
  [
  r_1 = i_1 = 30^\circ
  ]

* After reflection on two perpendicular mirrors:

  * The outgoing ray becomes **parallel to the original ray**
  * The direction is **reversed (opposite direction)**

---

##  Objective

* Analyze light reflection step by step
* Apply geometric reasoning to ray tracing
* Understand how mirror orientation affects light direction

---

##  Tools Used

* PowerPoint Presentation
* Geometrical optics diagrams
* Mathematical reasoning

---

##  Educational Value

This presentation helps students:

* Master the law of reflection
* Visualize ray paths in mirror systems
* Develop problem-solving skills in optics

---

- Presentation 2:
- 2 Simulation Tracks
2.1 Track 1: The Spy's Echo (Reflection)
Context
A wireless signal carrying a password reflects completely off a metal wall. An interceptor must be placed at a point where the signal strength is strongest to capture the password.

Physics principle
The reflected signal interferes with the incoming wave, forming a standing wave. According to the law of reflection, maximum signal amplitude occurs at the antinodes of the standing wave.

Goal of the simulation
Find the position where the amplitude is maximal, allowing the interceptor to be placed optimally
