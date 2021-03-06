# Introduction to Artificial Intelligence: "Connect K" Adversarial AI

This project is a deterministic artificial intelligence using a minimax algorithm to play "Connect K": a variation of Connect 4 that 
allows for different win conditions depending on the "K" value provided. The bulk of my artificial intelligence is in the file DKKAI.py 
in the src directory. Also included is the "Connect K" backend in "ConnectKSource_python" that was provided by my instructor. 

Note that in DKKAI.py, there is a block of code that is labeled in the comments not to be interfered with by students. This is further code provided by the professor, used to interface my artificial intelligence with the "Connect K" backend. 

Included in the doc directory is the report that I presented with my final project. In it, I described my heuristic method and other
aspects of my project.

Working on this AI provided me with extensive experience in optimization. Based on my experience, I have learned that Python is far from 
the ideal language to iterate through the many possible states in Connect K at a reasonable pace. To compensate for the weaknesses of the 
language, I wrote my code carefully to avoid redundancy and ensure that data structures were not duplicated unnecesarily. This helped keep 
run time down over the many iterations necessary for a deterministic AI such as this.

From this project, I gained an excellent baseline knowledge of deterministic artificial intelligence. This knowledge informed and inspired 
my future projects in artificial intelligence and eventually machine learning. 
