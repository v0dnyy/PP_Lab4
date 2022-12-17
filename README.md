[![Typing SVG](https://readme-typing-svg.herokuapp.com?color=%2336BCF7&lines=Lab+4)](https://git.io/typing-svg)
### Info for files: ###

* mainGPU.h           - main code 

* matMulGPU.cu           - matrix multiplication code

----

### Task: Modify the program from l/w №1 for parallel work using CUDA technology. ###

----

Work done in release x64 and block size = 10(Time in ms):

![](/size_time.jpg) 

Comparing number of threads(Time in ms):

![](/5.jpg) ![](/10.jpg) ![](/25.jpg)


----

### Conclusion: With the help of CUDA technology, two square matrices of 1000 by 1000 were first created, and then the result of multiplying these two matrices was calculated, and the time spent on multiplication was also measured. Higher efficiency is achieved by increasing the number of blocks. The most effective was the use of 25 size blocks (time ≈6,28 ms). ###
