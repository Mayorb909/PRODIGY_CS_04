# PRODIGY_CS_04
Building a keylogger.

### OBJECTIVE
Create a basic keylogger program that records and logs keystrokes. Focus on logging the keys pressed and saving them to a file. 

### SKILLS LEARNED
* I learnt how to import Python library
* I learnt how to use "pynput."
* I mastered hownto use logic fuction( fuction like: if, else, elif)
* learnt how to make Python code work like an application with the simple call of a function
* learnt how to turn Python code into a Windows and Android application. 

### TOOLS
![Python](https://img.shields.io/badge/Python-Language-3776AB?style=for-the-badge&logo=python&logoColor=white)


### STEPS/PROCESS
* I import pynput from the Python library
* I import 'Listener' from pynput.keyboard
* I define a function to write to a file with pynput listener
* I created a file with the {"open with(---, 'a') as file: } that keyboard strokes will be appended to
* I create a filter rule with an if statement to format capture keys to only alphanumeric and special characters pressed on the keyboard. example:
  *  keydata = keydata.replace("'", "")
    
  * if keydata == "Key.space":
    *  keydata = " "
    
  * if keydata == "Key.enter":
     *  keydata = "\n"
    
### PROJECT CODE
[![Python](https://img.shields.io/badge/Python-Task_Code-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://github.com/Mayorb909/PRODIGY_CS_04/blob/main/Code)
