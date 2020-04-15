Compilation and Running OpenACC
The following compilation and run instructions work on the Pitt
CRC cluster.
Enter each command in the order specified from the same directory as the desired files.
Compiling:
1: module load pgi
2: pgc++ -o [OUTFILE_NAME] [INFILE_NAME] -fast -Minfo=opt -ta=multicore -Minfo=accel

Running:
1: ./[OUTFILE_NAME]