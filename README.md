dpm_gpu
=======

## Requirements
- CUDA
- OpenCV

## How to Build
1. Download source code (We assume that we downloaded the code under YOUR_INSTALL_PATH below)
2. `$ cd YOUR_INSTALL_PATH`
3. Modify two-digit number on line 4 of CAR_TRACKING/CAR_TRACKING.makefile in accordance with your NVIDIA GPU compute capability (FYI : https://developer.nvidia.com/cuda-gpus)
4. Execute `$ make` under the YOUR_INSTSALL_PATH directory

## How to run
1. `$ cd YOUR_INSTALL_PATH`
2. `$ ./gccRelease/CAR_TRACKING.exe`
(If you want to run the program with debug information, then run `$ ./gccDebug/CAR_TRACKING.exe`)
3. Type 'ESC' key to terminate the program, or type any other key to process next image