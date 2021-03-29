Complete the table below with your results, and then provide your interpretation at the end.

Note that:

- When calculating the parallel speed-up S, use the time output by the code, which corresponds
  to the parallel calculation and does not include reading in the file or performing the serial check.

- Take as the serial execution time the time output by the code when run with a single process
  (hence the speed-up for 1 process must be 1.0, as already filled in the table).


No. Process:                        Mean time (average of 3 runs)           Parallel speed-up, S:
===========                         ============================:           ====================
1                                    0.00050497066                                
2                                    0.000840663 
4                                    0.000713984 

Architecture that the timing runs were performed on:
I am using a windows 10 machine which is running a Windows Subsystem for Linux (Ubunutu) virtually.
Unfortunately, trying to set up MPI on Windows was more hassle then it was worth, which is why I ended
up using the WSL. It works perfectly well on it so I don't think it is affecting the execution time too much. 

A brief interpretation of these results (2-3 sentences should be enough):

