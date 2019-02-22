# Tensorboard-101

This tutorial is for those who are running the 'graph_tensorboard.py' program.

Begin with checking if you can import tensorflow from the terminal.

![alt text](https://github.com/dniboghgnis/Tensorboard-101/blob/master/Tensorboard-drawings/Screenshot%202019-02-23%20at%202.50.02%20AM.png)

If everything is fine, you should get no errors.

Else try checking the python path (code included to print the path) and add tensorflow to the path using sudo nano bash.

Once tensorflow can be imported to the terminal, exit the python shell. ['quit()']

Navigate to the parent directory of the graph folder. 

Type 'tensorboard --logdir=graphs' [since the event files are saved in this location on finder as specified in the code]

![alt text](https://github.com/dniboghgnis/Tensorboard-101/blob/master/Tensorboard-drawings/Screenshot%202019-02-23%20at%202.52.40%20AM.png)

Copy the generated link and paste it in the browser.

![alt text](https://github.com/dniboghgnis/Tensorboard-101/blob/master/Tensorboard-drawings/Screenshot%202019-02-23%20at%202.54.22%20AM.png)

Change the desired variable to see the expected changes.

Tensorboard doesn't like multiple event files in the same folder. Make sure to delete the previous event file before writing a new one to the folder. Or better use a different folder. [ graphs/101, graphs/102 etc etc.]
