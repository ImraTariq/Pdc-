# Pdc-
Compilation:
mpicxx -o obj main.c -fopenmp
Execution:
mpirun -np n./obj
where obj is object 
n is number of objects
