# Keylogger

README FILE

### Installing Python
1. Install the nodes python with the following commands in the command line: sudo apt install python3-pip

### Create the Python script for the keylogger
1. Create a python script file for the keylogger with nano keylogger.py

Using the nano command will immediately allow you to edit the contents of the python script. (Upon creation, it will be blank.)

2. Copy and paste one of the two scripts to the keylogger.py file. Once copied, exit the keylogger.py file and save it.

### Run the Python keylogger script
1. To run your python script, use enter the following in the command line: python3 keylogger.py

This will make the script run in the background while you work on 

### Testing Your Keylogger
1. To test your keylogger, open your internet browser and go to any website. For the sake of example, we’ll go to Facebook. (Please see Screenshot 01)
2. Type in any email and password combination as if you are going to login. (Please see Screenshot 01)
3. Go into the Home folder of your Ubuntu virtual machine, and you will see a text file named “keyfile.txt.” (Please see Screenshot 02 and Screenshot 03)
4. After you open “keyfile.txt,” which was a text file automatically created with the Python script, you will see that the keylogger recorded all the keystrokes when you used the internet browser. (Please see Screenshot 04)
5. To turn off the keylogger, go back to the command line and press CTRL+C.
