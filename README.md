# Description
   These codes reproduces results/figures in the report, which 
   expeted to be published as Kajiwara et al. (2021).
  
--------------
# Requirments
    
  Matlab, Statistical and Signal Processing Toolbox and Statistics and Machine Learning Toolbox are necessary to run these code.
  
----------------
# To generate figure 5b
  
  addpath(genpath('./'));
  fig5b
  
----------------
# Description of fig5b.m
 
  This program products figure 5(b).
  Figure 5 shows basic properties of neuronal networks, and
  especially 5-(b) shows degree histgrams, histgrams of number of connections.

-----------------
# To generate figures 5c and 5e
  
   addpath(genpath('./'));
   fig5ce
  
----------------
# Description of fig5ce.m

  This program products figure 5(c)(e).
  Figure 5 shows basic properties of neuronal networks, especially
  the panel (c) shows histgrams of firing rate for excitatory and inhibitory neurons.
  the panel (e) shows histgrams of connectivity strenghs for excitatory and inhibitory neurons.

-----------------
# To generate figure 5d
  
   addpath(genpath('./'));
   fig5d
  
----------------
# Description of fig5d.m

  This program products figure 5(d).
  Figure5 shows basic properties of neuronal networks, and especially
  the panel (d) shows the total number of identified excitatory and inhibitory neurons.

-----------------
# To generate figure 6a and 6b
  
   addpath(genpath('./'));
   fig6ab
  
----------------
# Description of fig6ab.m

  This program products figure 6(a)(b). 
  This figure shows E/I cell categories and k-core centralities, especially
  (a) shows the difference of averaged k-core values for excitatory and inhibitory neurons, and
  (b) shows the difference of averaged k-core values for excitatory and inhibitory neurons within individual layers.

-----------------
# To generate figure 7a and 7b
  
   addpath(genpath('./'));
   fig7ab
  
----------------
# Description of fig7ab.m

   This program products figure 7(a)(b).
   This figure shows E/I cell category and FVS (Feedback Vertex Set), especially
   (a) shows the difference of ratios of FVS for excitatory or inhibitory neurons.
   (b) shoes the difference of ratios of FVS for excitatory or inhibitory neurons within individual layers.

-----------------
# To generate basic data for drawing figure 7c
  
   addpath(genpath('./'));
   fig7c
  
----------------
# Description of fig7c.m

   This program products data set for plotting the Venn diagram
   to compare between high K-Core nodes and FVS (Feedback Vertex Set) of nodes.

------------------
   # Reference
   If you use this code, cite this following article: 
   Kajiwara et al. (2021) under review.

