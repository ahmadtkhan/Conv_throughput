# Specific Coefficient
Applies a 3x3 sharpening kernel on a 512 x 512 image by utilizing the kernel's properties and compacting the kernel into one equation per pixel. Uses one RAM based shift register rather than two FIFOs for storing two line buffers to utilize memory efficiently. 
