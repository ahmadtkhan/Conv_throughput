# 2 way symmetry
Utilizes the kernel's x and y-axis symmetrical properties to decrease the number of DSP computations per pixel. Uses RAM based shift register instead of two FIFOs for caching data for sliding window. The design is highly pipelined to increase maximum frequency. The results derived using a testbench are shown below.

![Original image][2_way_symm/results/barbara_original.png]
*Figure 1: Original Image*

![Identity image][2_way_symm/results/identical_barbara.png]
*Figure 2: Identity Image*

![Edge image][2_way_symm/results/barabara_edge.png]
*Figure 3: Edge Image*

![Sharpened image][2_way_symm/results/sharpened_barbara.png]
*Figure 4: Sharpened Image*
