# Sobel_and_Prewitt_edge_methods_Netpbm
Minimal Image Library for Computer Vision - Sobel and Prewitt edge methods example for Netpbm images

<img src="https://user-images.githubusercontent.com/49571967/87052481-bf138880-c1f8-11ea-9224-a76cc4cbab88.jpg" width="45%"></img> 
<img src="https://user-images.githubusercontent.com/49571967/87052478-bde25b80-c1f8-11ea-9d52-4778ca699e80.jpg" width="45%"></img> 

## Usage
* Open Linux terminal, navigate to the application folder and run ./edge \[inputname] \[outputname] \[edge_detection] \[threshold]
    * \[inputname] Is the origin Netpbm image name and extension. Must be in the same folder as the executable.
    * \[outputname] Is the destination Netpbm image name and extension. For a correct use, save the image with the .pgm extension.
    * \[edge_detection] The edge method, must be \"sobel\" or \"prewitt\".
    * \[threshold] Threshold value to consider. Must be between \[0.001, 1.00\].
    
## Compilation
* Compile via Linux make command
    * Use \<make\> to create the executable
    * Use \<make clean\> to clean the object files
    
## Dependencies
* To compile, you need the make command
    * make: sudo apt-get install make

## Release History
* 0.0.1
    * Create README.md
 
## Meta
> Eduardo Oliveira - eduardo.oliveira@ieee.org;

