#include <stdio.h>
#include <mpi.h>

int main(int argc, char **argv){

  int size,proc;

  MPI_Init(&argc, &argv);                    /* initialize communication */

  MPI_Comm_size(MPI_COMM_WORLD,&size);       /* number of processors */
  MPI_Comm_rank(MPI_COMM_WORLD, &proc);       /* our number */

  fprintf(stdout,"I am processor %d out of %d.\n",proc,size);

  MPI_Finalize();

  return 0;
}
