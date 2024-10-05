# test_vscode
This is a repository for IB9JHO to test you can compile and run C/C++ in the correct enviroment with vscode.

# Setting up the Environment

The easiest way to get straight to programming is to create/open a codespace in the cloud and selecting the GCC compiler
when prompted. 
You can do this with:

+ Github directly
![codespace](https://github.com/Aurashk/test_vscode/assets/9390150/3e4bd62e-12dc-4cd6-a924-34e7c5acef85)

+ Vscode installed on your device
![codespace_in_vscode](https://github.com/Aurashk/test_vscode/assets/9390150/61e950e5-237c-40c1-8062-e62d7f535b59)

A local enviroment on your device is faster, not limited on computing resources, and available offline. 
If you want to set this up follow the [instructions here](https://github.com/Aurashk/test_vscode/files/12751241/Configuring.vscode.for.local.use.pdf)

Test that your environment is working by compiling and running the C code in this repository found in src/main.c.

![compile_and_run](https://github.com/Aurashk/test_vscode/assets/9390150/6ba50f14-55fe-465d-ba9e-186118b39586)
Click the play button highlighted in yellow to compile and run. You should see the program output from the print
statement in our code as highlighted in orange. 

# Testing

Assignments are marked automatically using tests. You can run the tests in vscode by going to the tests tab and clicking the play button.

![running_tests](https://github.com/Aurashk/test_vscode/assets/9390150/bd73917c-e4c0-43f4-bc28-e4920f088b3a)

The tests are failing because the output of our program is not what we expect it to be. The correct output can be found in tests/IO/correct_output.txt.
Correct the code and rerun the tests to verify that the output of the program is correct.

# Submission

Once you have confirmed all the tests are passing. You can submit an assignment by pushing (updating) the repository with all your changes.
![submit_assignment](https://github.com/Aurashk/test_vscode/assets/9390150/55b9a810-9af9-4963-9a75-eb7edb31eea9)

Once you have submitted your assignment and all the tests are passing you should notice the red cross will change to a green tick in 
github.

+ Tests are *not* passing
  
![tests_not_passing_repo](https://github.com/Aurashk/test_vscode/assets/9390150/1a45c2cf-903b-4e5f-bfa2-471e28e7349d)

+ Tests are passing

![tests_passing_in_repo](https://github.com/Aurashk/test_vscode/assets/9390150/2c339c18-a7e3-4183-bcf5-8a1299e4b9e9)

