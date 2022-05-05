# Simulations folder

This folder contains short trajectories from steered MD simulations used as
starting points for umbrealla sampling runs. Note that the xtc files are here
reduced to save space.

Example of how to extract windows from SMD trajectories:

~~~ bash
# Extract
gmx trjconv -s pull.tpr -f dc-dlpc.xtc -o windows.gro -sep
gmx grompp -f npt.mdp -c windows.gro -p topol.top -r windows.gro -n index.ndx -o npt-windows.tpr
gmx mdrun -deffnm npt-windows
# WHAM
gmx wham -it tpr-files.dat -if pullf-files.dat -o -hist
~~~
