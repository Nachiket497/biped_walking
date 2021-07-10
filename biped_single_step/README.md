# biped_walking single step

# Aim 

- To Generate the COM trajectory and swing leg trajectory for the single step.


# COM Trajectory Genration 

- To generate the COM trajectory I use the [3DLIPM](https://www.cs.cmu.edu/~hgeyer/Teaching/R16-899B/Papers/KajiitaEA01IEEE_ICIRS.pdf) 

- The Dynamics equations are 
<p align="center">
  <img src = "https://github.com/Nachiket497/biped_walking/blob/main/biped_single_step/images/dynamics_equations.png">
  
</p>

# Results 

- X vs Time for COM

<p align="center">
  <img src = "https://github.com/Nachiket497/biped_walking/blob/main/biped_single_step/results/x_com_vs_time.png">
</p>

- Y vs Time for COM

<p align="center">
  <img src = "https://github.com/Nachiket497/biped_walking/blob/main/biped_single_step/results/y_com_vs_time.png">
</p>

- X vs Y for COM

<p align="center">
  <img src = "https://github.com/Nachiket497/biped_walking/blob/main/biped_single_step/results/x_com_vs_y_com.png">
</p>

# Swing leg Trajectory Genration

- To generate the swing leg trajectory I use the elliptical trajectory for z co-ordinate and x co-ordinate is the mirror image of the x co-ordinate of the fixed leg about the x co-ordinate of the COM

# Results

- X vs Time for Swing leg

<p align="center">
  <img src = "https://github.com/Nachiket497/biped_walking/blob/main/biped_single_step/results/x_swing_leg_vs_time.png">
</p>

- Z vs Time for Swing leg

<p align="center">
  <img src = "https://github.com/Nachiket497/biped_walking/blob/main/biped_single_step/results/z_swing_leg_vs_time.png">
</p>

- X vs Z for  Swing leg

<p align="center">
  <img src = "https://github.com/Nachiket497/biped_walking/blob/main/biped_single_step/results/x_swing_leg_vs_z_swing_leg.png">
</p>


# Combining both trajectory we get the complete single step trajectory

- 3D View

<p align="center">
  <img src = "https://github.com/Nachiket497/biped_walking/blob/main/biped_single_step/results/trajectory3d.gif">
</p>

- 2D Top View 

<p align="center">
  <img src = "https://github.com/Nachiket497/biped_walking/blob/main/biped_single_step/results/2d_top_view.gif">
</p>

- 2D Side View

<p align="center">
  <img src = "https://github.com/Nachiket497/biped_walking/blob/main/biped_single_step/results/2d_side_view.gif">
</p>

- 2D Front View

<p align="center">
  <img src = "https://github.com/Nachiket497/biped_walking/blob/main/biped_single_step/results/2d_front_view.gif">
</p>


