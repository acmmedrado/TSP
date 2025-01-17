all:
	gcc -c list.c
	mpicc tsp_mpi.c list.o -o tsp_mpi
	time mpirun -n 4 ./tsp_mpi
debug:
	gcc -c list.c
	mpicc -DDEBUG tsp_mpi.c list.o -o tsp_mpi
	time mpirun -n 4  sp_mpi

