# biped_walking Multistep

# Aim 

- To Generate the COM trajectory,swing leg, fix leg trajectory for the multiple step.

# Trajectory Planning

## Trajectory generator is divided into 6 different phases

- configuaring into initial position
- moving COM on right leg
- taking the half step by left leg
- taking multiple steps along with the COM shifting simultaneously
- taking the half step
- stopping 

## All the trajectory are generated in the fixed foot frame of reference and then converted into required frames


# COM Trajectory Genration

- To generate the COM trajectory I used the [3DLIPM](https://www.cs.cmu.edu/~hgeyer/Teaching/R16-899B/Papers/KajiitaEA01IEEE_ICIRS.pdf)

- The Dynamics equations are

<p align="center" >
  <img src="https://github.com/Nachiket497/biped_walking/blob/main/biped_single_step/images/dynamics_equations.png">
</p>

- To generate the initial trajectory upto 3 phase I use a cosign velocity profile 
- for remeaning part I use the dynamics equations

## Results

<p align="center" >
  <img src="https://github.com/Nachiket497/biped_walking/blob/main/biped_multistep/results/com_traj.png">
</p>

# Swing leg Trajectory genration

- for x co-ordinate part I used the cosign velocity profile to generate the trajectory
- for z co-ordinate part I used the cubic Bézier curves  
- the -ve valude of y co ordinate denotes that it is a right leg and +ve  denotes that it is a left leg


## Results 


<p align="center" >
  <img src="https://github.com/Nachiket497/biped_walking/blob/main/biped_multistep/results/swing_leg_traj.png">
</p>

# Trajectories in the Global frame 

- Fixed leg

<p align="center" >
  <img src="https://github.com/Nachiket497/biped_walking/blob/main/biped_multistep/results/fix_leg_traj_global.png">
</p>

- Swing leg 


<p align="center" >
  <img src="https://github.com/Nachiket497/biped_walking/blob/main/biped_multistep/results/swing_leg_traj_global.png">
</p>


- COM trajectory


<p align="center" >
  <img src="https://github.com/Nachiket497/biped_walking/blob/main/biped_multistep/results/com_traj_global.png">
</p>



# Trajectories in the COM frame 


- Fixed leg

<p align="center" >
  <img src="https://github.com/Nachiket497/biped_walking/blob/main/biped_multistep/results/fix_leg_com_frame.png">
</p>

- Swing leg 


<p align="center" >
  <img src="https://github.com/Nachiket497/biped_walking/blob/main/biped_multistep/results/swing_leg_com_frame.png">
</p>



# Combining both trajectory we get the complete multiple steps trajectory

- 3D View 

<p align="center" >
  <img src="https://github.com/Nachiket497/biped_walking/blob/main/biped_multistep/results/Multistep_3D.gif">
</p>

- Top View 

<p align="center" >
  <img src="https://github.com/Nachiket497/biped_walking/blob/main/biped_multistep/results/2d_top_view.gif">
</p>


- Side View 

<p align="center" >
  <img src="https://github.com/Nachiket497/biped_walking/blob/main/biped_multistep/results/2d_side_view.gif">
</p>



