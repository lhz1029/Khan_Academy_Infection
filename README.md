# Khan_Academy_Infection

This project is part of the Khan Academy Project Interview Infection Question. The specs for this project can be found here: https://docs.google.com/a/khanacademy.org/document/d/1NiKv-MjULOFyyc8f5w8R_EqvuPJ10wJVJgZhtTK9VKc/edit#heading=h.24vvz52659j3. 

My project is as follows:

1. I implemented total_infection() to infect an entire connected component of users given a starting user.

2. I implemented limited_infection() in terms of the the *suggested optional enhancement* of infecting an **exact** number of users while keeping connected users under the same infected state. This dramatically increased the complexity of limited_infection, but gives us the ability to determine total infection size of the network.

3. In addition, I also optionally created an **visualization** of a sample network after a call to total_infection.

### Next steps
If I spent more time, I would improve my version of limited_infection() as well as my visualization. Regarding limited_infection(), I would increase the efficiency and organization of limited_infection(); allow the number of nodes infected to lie within a range instead of reaching an exact number; and allow the infection of different versions of a feature on the network for use, say, in multiple comparisons in A/B testing. Regarding the visualization, I would create a function that would generalize to any graph after both total_infection() and limited_infection(). I would also organize my project by separating out the testing from the functions and creating completely automated testing. More information about my code, algorithms, and future thoughts can be found in my iPython Notebook.

###### Setup

I submitted my project in a iPython Notebook (.ipynb) format, as well as in corresponding .html and .py formats.  For best viewing, you can see the entirety of my project via the iPython Notebook, including the output of the programmed cells and inline visualizations.

Requirements: To run the code on the iPython Notebook (the output from my running the code is already shown), you must first install Jupyter Notebook (http://jupyter.readthedocs.org/en/latest/install.html). Otherwise, you can simply open and run the .py file since it includes all the code, with the tests and the code to call them placed right after each function. 

