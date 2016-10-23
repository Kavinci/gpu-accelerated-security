# gpu-accelerated-security

The internet today is getting fast and bandwidths are getting larger. This results in various types of Denial Of Service attacks or DOS attacks in which many machines make request from a server or a few powerful machines make requests from a server resulting in the machine not being able to keep up with with all of the request and become overloaded and deny service. This is a growing problem for the internet in this day and age. 

This project is a proof of concept to see if we can utilize the much faster graphics processor to route, process, and rule match incoming traffic in hopes to outpace normal server traffic. This proof of concept will be speed tested on basic terms with simple tools. Monitoring software may be a future integration but is outside the scope of this project.

This project is designed to run on the <a href="http://www.nvidia.com/object/jetson-tk1-embedded-dev-kit.html">NVIDIA Jetson TK1</a> board and utilizes <a href="https://developer.nvidia.com/cuda-zone">CUDA</a>, <a href="https://developer.nvidia.com/opengl">OpenGL 4.4</a>, and <a href="http://opencv.org/">Tegra-accelerated OpenCV</a>.

This software will remain free and open source.
