
The program is divided in three FreerRtos tasks, using 2 queues and 1 counting semaphore and 2 binary semaphores to manage the tasks and communication beetwen them


The tasks are divided in
-TASK1 writes in the Queues the morse encription for the entered character
-Task04 reads from the LED queue and manages the led flash
-Task05 reads from the Serial queue the encription and sends it over the serial interface
