# Millikan Oil Drop Experiment Lab Notebook
In this experiment performed in my Physics lab class my partner and I use tiny droplets of oil in an electric field to measure the value of the elementary electric charge.

## Introduction
The Millikan oil drop experiment is a famous physics experiment first performed in 1909 by Robert A. Millikan and Harvey Fletcher to measure the elementary electric charge $e$. The experiment consists of measuring the rise and fall velocities of tiny droplets of oil in an electric field. These droplets are so small that in the absence of an external force they reach their terminal fall velocity almost instantly. By ionizing these droplets with an alpha radiation source we can give them a small positive charge, so that when we switch on an electric field we can cause them to rise with a velocity proportional to their charge. 

Stoke's Law gives the frictional force exerted on spherical objects with very small Reynolds numbers in a viscous fluid – like our oil droplet moving through air. At terminal velocity the force of gravity is balanced against the frictional force of the air, and since we know both the gravitational constant $g$ and the coefficient of friction for air $k$ (as a function of air pressure and temperature), by measuring the terminal velocity $v_f$ of the droplet we can use Stoke's Law to solve for its mass. With its mass known, we can measure the total charge of the droplet by observing its motion in an applied electric field of a known strength. We can even change the charge of a single droplet by reionizing it and observing its change in velocity. Once we have collected enough data, **we expect to find that the measured charge values of the droplets are integer multiples of some elementary constant.**

In his original experiment Millikan obtained his velocity measurements by watching these oil droplets move up and down and measuring the time they took to move a known distance. This is no easy task. One must peer through a backlit microscope lens and keep their eye trained on a single microscopic droplet for as long as they can bear, or until it loses its charge and falls out of view. After attempting this classic method for about 20 minutes I decided it wasn't worth losing vision in my right eye over and opted to make use of some of the 21st century technology Millikan lacked access to. In our version of the experiment we used an iPhone 8 camera to record footage of the droplets moving up and down. Additionally, rather than timing these droplets by hand to get their velocity data, I had the idea to automate this as well by motion tracking the droplet footage using one of my all time favorite pieces of open source software, Blender. The tracking went beautifully, and this is primary dataset we will be using in this analysis. 
