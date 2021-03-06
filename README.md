# Flag simulation with wind action using spring-mass system

<!-- ![simulation_drapeau.gif](simulation_drapeau.gif) -->

<p align=center>
  <img src="https://github.com/JinFrx/flag-simulation/blob/main/simulation_drapeau.gif" alt="showcase image" style="width: 650px; max-width: 100%; height: auto" title="Click to enlarge picture" />
</p>

## Description

A simulation of a flag made with Godot Engine, as part of a university project  (2021).

The flag is modelised with a spring-damper-mass system.

The action of wind on the flag is modelised by computing wind and air forces that act on the mesh faces.

Code is located in flag.gd.

This application allows the user to have interactions with the simulation by pressing some keys:
- Press I to hide or show simulation parameters information
- Press M (AZERTY keyboard) to change the rendering mode (POINTS, LINES, FACES)
- Press T to change the texture of the flag
- Press Spacebar to randomly change the velocity of the wind
