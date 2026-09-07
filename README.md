**https://bcs702.vercel.app/Manual.html**

TO RUN THE CODE:

 gcc -fopenmp EXP4.c -o EXP4
 
 ./EXP4.exe                 


TO RUN THE CODE for MPI Program(EXP 5,6,7,8,9):

Open x64 Native Tools Command Prompt for VS and Navigate to the folder where your MPI code is saved (example if file is in `E:\PC_LAB`): cd /d "E:\PC_LAB"
Now you can compile the code using    cl EXP5.c msmpi.lib
Run using      mpiexec -n 2 EXP4.exe
