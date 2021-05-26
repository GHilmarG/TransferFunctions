


# Transfer Functions

 

[//]: <> (pandoc index.md -f markdown -t html -s -o test1.html)

This is the index file

These functions describe the transfer of pertubations in bed
topography (B) and basal slipperiness (C) on surface topograpy (S) and
surface velocities (U and V) for both full Stokes and the SSA/STREAM systems.


Example:

```
T_SB_3vcs		:  full Stokes, bed-to-surface transfer from B to S in steady state


SSTREAM_Tuc_t_3d 	:  SSA/SSTREAM, time-dependent bed-to-surface transfer from basal slipperinss (c) to x component of surface velocity (u)
```



Run driver_FullStokes_GaussPeak.m to see the response to a
Gaussian-shaped pertubation in bedrock and basal slipperiness on
surface fields.

To calculate the transfer, do a FFT of the basal pertubations,
multiply with the transfer functions, and do an inverse FFT.  Have a
look at driver_FullStokes_GaussPeak.m for an exampel of how to do
this.

[Hilmar Gudmundsson](mailto:hilmar.gudmundsson@northumbria.ac.uk)