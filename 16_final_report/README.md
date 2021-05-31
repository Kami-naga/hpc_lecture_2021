# Student ID
20M38050
# Brief Intro
N=2048, f_node=1  

I completed it by getting the code from simd_blocking. Then I modified it to get the right answer. But I just found that it gets better result by only `./a.out`(275gflops), and a bit poor result by `mpirun -np 4 ./a.out`(242gflops), which gets me a bit confused. 
