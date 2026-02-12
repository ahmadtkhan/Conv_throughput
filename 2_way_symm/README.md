# 2 way symmetry
Utilizes the kernel's x and y-axis symmetrical properties to decrease the number of DSP computations per pixel. Uses RAM based shift register instead of two FIFOs for caching data for sliding window. The design is highly pipelined to increase maximum frequency. The results derived using a testbench are shown below.

![Original image](results/barbara_original.png) <br>
*Figure 1: Original Image*

![Identity image](results/identical_barbara.png) <br>
*Figure 2: Identity Image*

![Edge image](results/barabara_edge.png) <br>
*Figure 3: Edge Image*

![Sharpened image](results/sharpened_barbara.png) <br>
*Figure 4: Sharpened Image*
