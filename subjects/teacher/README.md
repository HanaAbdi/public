## teacher

### Instructions

"let's play!"

"A **true teacher** does not jealously guard his mastery."

The commissioner was most impressed by the result of your answers.
He has now asked your help to create a training program for the future police inspectors. You gladly accept as you think that this will help lessen your burden of fighting crime in the future.

In a training folder, various folders `mystery` were prepared with some key differences in the data for each group of trainees. (those folders will not be called `mystery`, they will have different names but they will all be at the same level)

To simplify your life as a teacher and as the answers will not be exactly the same in each `mystery` folder, you need to write a `teacher.sh` file that does the following:

- step 1, it enters the `mystery` folder.(again, the names will vary)
- step 2, it isolates, through a similar command that you used to find it, and into an environment variable, the number (**and only the number**) of the key interview that helped solved the mystery (Unlike the interview number, the address will not change across the `mystery` folders that will be tested, hence the command to find the interview is the same across all the `mystery` folders that will be tested).
- step 3, it prints the newly created environment variable.
- step 4, it prints what the interview contains.
- step 5, it executes the command that should have printed the short list of 4 suspects. (it only shows the license Plate, the Make, the Color, the Owner, and the Height)
- step 6, it executes the command that should have gotten your main suspect convicted (as a reminder the result of that command should be the printing of a number) except that now you replace your suspect name with the environment variable MAIN_SUSPECT.

- step 7, step 1 to 6 are repeated for each `mystery` folder of the training folder that the program works in.

Note that for **step 2 to 6**, all the commands have to be executed with keeping in mind that the `mystery` folder is the current directory but that its name will vary.

Now show them who is the boss...

### Hint

Search how to do a loop with a `.sh` file now.
