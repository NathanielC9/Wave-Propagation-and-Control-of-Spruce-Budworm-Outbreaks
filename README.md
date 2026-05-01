#Spruce Budworm Reaction Diffusion Model

This project studies wave propagation and control of spruce budworm outbreaks using a reaction diffusion model from *Mathematical Biology I: An Introduction*.

The model is

u_t = D u_xx + f(u)

where

f(u) = r u (1 - u/q) - u^2 / (1 + u^2)

The project investigates how local growth, predation, and spatial diffusion determine whether a localized budworm outbreak spreads through space or returns to a refuge state.

## Main Ideas

- Multiple steady states
- Refuge state, threshold state, and outbreak state
- Traveling wave solutions
- Numerical simulation using finite differences
- Outbreak spread versus return to refuge

Install the required packages:

```bash
pip install -r requirements.txt