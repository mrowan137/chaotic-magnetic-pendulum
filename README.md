# Chaotic magnetic pendulum

This directory contains a
[simplified physics model](https://github.com/mrowan137/chaotic-magnetic-pendulum/blob/main/chaotic_magnetic_pendulum.nb)
(implemented in [Mathematica](https://www.wolfram.com/mathematica/)) of a
chaotic magnetic pendulum. The model simulates the motion of a magnet that
swings freely over an arrangement of magnets placed at the vertices of a
hexagon. Animation of the model:

<p align="center">
  <img src="https://github.com/mrowan137/chaotic-magnetic-pendulum/blob/main/docs/demo/chaotic_magnetic_pendulum_demo.gif">
</p>


## Description

The model makes a number of simplifying assumptions:
* pendulum is assumed to move only in the x-y plane
* radially-inward component of pendulum tension is treated as a spring force
  (Hooke’s law)
* magnets treated as 'point-like magnetic dipole', i.e. two opposite poles
  brought together as close as possible

These assumptions significantly reduce the complexity of the original system,
while still capturing characteristic motion of the pendulating magnet.


## Author

Michael E. Rowan — [mrowan137](https://github.com/mrowan137) — [michael@mrowan137.dev](mailto:michael@mrowan137.dev).


## License

[MIT License](https://github.com/mrowan137/chaotic-magnetic-pendulum/blob/main/LICENSE).


## Acknowledgments

Aaron Santos