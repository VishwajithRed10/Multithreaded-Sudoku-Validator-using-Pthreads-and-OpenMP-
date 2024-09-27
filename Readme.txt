In the zip,
SrcOpenMp.cpp,Srcpthread.cpp are 2 cpp files to use OpenMp and Pthreads respectively.
File Input.txt is read by above cpp files to produce Output Files.

i)the file input.txt contain:
	a)2 integers in 1st line (Num of Threads and Order of Sudoku respectively).
	b)futher lines contain the Sudoku Grid.
 Always, give input according to the above order.

ii)in Terminal, for compiling Cpp code Srcpthread.cpp:
	line 1:g++ Srcpthread.cpp -lpthread
	line 2:./a.out.
			
				(or)

		for compiling Cpp code SrcOpenMp.cpp:
	line 1:g++ SrcOpenMp.cpp -fopenmp -lpthread
	line 2:./a.out.

This takes input from "Input.txt" and generates "Output.txt" consists:

1) Log file:
	with thread number, row/col/grid validity

2) Overall Sudoku Grid Validity.
3) Time Taken


