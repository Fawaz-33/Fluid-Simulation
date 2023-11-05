# Stable Fluid-Simulation

The main algorith of the stable fluids was introduced by Jos Stam in his paper titled 'Real-time fluid dynamics for games' where 
he introduced easier and simple ways to solve navier stokes equation where the physical accuracy of the solution is of secondary importance.
The pressure poisson eqn is solved by matrix method taking divergence of velocity as a source term and the advection part is solved by 4th order Runge Kutta method. 
The procedure and the basis of the code is taken from the two yt videos --- 
https://www.youtube.com/watch?v=cM47L5RddsM
https://www.youtube.com/watch?v=DYUJWPlPRQ8
