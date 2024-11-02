Submitted by:
Assaf Ariely 315420836
Tom Mandel  205633688

Our compiled program is running on Nvidia Geforce GTX 1650 GPU so the arch and code is 75 instead of 61 as the assignment mentioned, incase that the program doesn't compiled or running try to compile the code with:

nvcc -gencode arch=compute_61,code=sm_61 scan_strcmp.cu -o foo 