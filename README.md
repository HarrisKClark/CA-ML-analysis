Elementary Analysis of Cellular Automata


Files:
Main.py
- Main file, handles all UI, and the Cellular Automata algorithm and analysis outputs all data to a CSV files “CAdata.csv”, which can then be copy pasted and run in ML-Algo.py

- Further description of specific methods can be found at https://docs.google.com/document/d/1zvYRDorI1X60Ikm91E2PNGDfpCa_zmXGo8GM1uKP6dQ/edit?usp=sharing or by reading the comments 

ML-Algo.py
- Handles all ML parts of this project, copy paste in the data from Main.py into the project folder and it will run. Preforms an elbow test, which is left in for prosperities sake. It works by preforming K-means clustering, and then visualizes data using PCA

- Further description of specific methods can be found at https://docs.google.com/document/d/1zvYRDorI1X60Ikm91E2PNGDfpCa_zmXGo8GM1uKP6dQ/edit?usp=sharing or by reading the comments 



How to Run:
-ensure all python packages are fully installed, and main should run correctly, copy paste data once completed into ML-Algo, and that should run.

Runs on python 3.8


Libraries:
pygame, pyperclip, numpy, matplotlib, sklearn, pandas, numpy
https://www.pygame.org/news, https://numpy.org/ , https://pypi.org/project/pyperclip/, https://matplotlib.org/, https://scikit-learn.org/stable/, https://pandas.pydata.org/
 
- Harris Clark 
