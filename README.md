# Emerging Technologies

## Contents

* [Project Details](#details)
* [Why This Repository Exists](#why) 
* [What Is In It](#what)
* [How To Run The Notebook](#how)
* [Research](#research)
* [References](#references)

## Project Details<a name = "details"></a>

| Project Details   |     |
| --- | --- |
| **College** | Galway-Mayo Institute of Technology|
| **Course** | BSc (Hons) in Computing in Software Development  |
| **Module** |  Emerging Technologies |
| **Student** | Emmanuel Osabuehien (G00373559) |

## Why This Repository Exists<a name = "why"></a>

This repository exists to contain my Emerging Technology project which shows you how to use the scikit-learn library built into python by demonstrating different algorithms that can be built using this library and it also shows you an demonstration and explanation of the Deutsch–Jozsa algorithm using the qiskit package built into python

## What Is In It<a name = "what"></a>

<b>.dockerignore - </b> This file specifies which folders/files should Docker ignore when building. <br>
<b>.gitignore - </b> This file specifies which folders/files should Git ignore when building. <br>
<b>Dockerfile - </b> This file contains the commands a user calls in the command line to generate an image.<br>
<b>README.md - </b> This is a text file containing information used to introduce and explain the project, te README.md explains questions such as why this repository exists, what is in it and how to run the notebook. <br>
<b>docker-compose.yml -</b> This is a config file, it is for docker-composeIt used for a variety of things such as to specify what images are required, which ports you want to expose, what commands should be run when they start, how to link containers, etc.<br>
<b>combined_process_power_plant.csv - </b> This is a data file containing 9568 data points collected from a combined cycle power plant that will be used for one of the algortihms in the scikit-learn notebook. <br>
<b>processed.cleveland.data.csv - </b> This is a data file containing data regarding patients in a clinic that will be used for one of the algortihms in the scikit-learn notebook. <br>
<b>quantum-deutsch.ipynb - </b> This jupyter notebook contains information on what is quantum computing, how does it work and what is the different between classical and quantum computing and it also contains an explanation of the Deutsch algorithm. <br>
<b>scikit-learn.ipynb - </b> This is a juptyer notebook that contains information on what is the scikit-learn python library and shows different algorithms that can be done using the scikit-learn library. <br>
<b>requirements.txt - </b> This is a text file which specifies the python packages needed the run this project. <br>

## How To Run The Notebook<a name = "how"></a>

1. Download [Anaconda]().
2. Download [cmder]() if on Windows.
3. Ensure that git is installed.
4. Create a blank folder in your cmder
5. 'cd' into the directory
6. 'git clone' repository "https://github.com/Emmanuel-Osabuehien/EmergingTechnologyProject.git"
7. 'cd' into the repository folder
8. Run `juypter lab`.
9. Jupyter should run in browser
10. You can restart and run all cells in either the 'scikit-learn.ipynb' or 'quantum-deutsch.ipynb' notebooks.

Alternatively, if you have docker installed:
  
1. Go through parts 1-7
2. Run `docker-compose up`.
3. Docker should run in browser
4. You can restart and run all cells in either the 'scikit-learn.ipynb' or 'quantum-deutsch.ipynb' notebooks.

<p> System requirements that are needed to run the project includes: </p>

- Python 3.9
- Git
- Docker
- Cmder
- WSL2

<p> Model requirements that are needed to run the project includes: </p>

- Numpy (Version 1.21.2)
- Matplotlib (Version 3.4.3)
- Pandas (Version 1.3.4)
- Seaborn (Version 0.11.2)
- Qiskit (Version 0.32.0)

## Research<a name = "research"></a>
- [Playing with Jupyter,<br> https://github.com/Emmanuel-Osabuehien/playing-with-jupyter](https://github.com/Emmanuel-Osabuehien/playing-with-jupyter)
- [Numpy Random,<br> https://github.com/Emmanuel-Osabuehien/numpy-random](https://github.com/Emmanuel-Osabuehien/numpy-random)
- [Quantum Computing,<br> https://github.com/Emmanuel-Osabuehien/quantum-computing.git](https://github.com/Emmanuel-Osabuehien/quantum-computing.git)

## References<a name = "references"></a>

- [Scikit-Learn.org,<br> https://scikit-learn.org/stable/#](https://scikit-learn.org/stable/#)
- [Qiskit.org,<br> https://qiskit.org/](https://qiskit.org/)
- [Datacamp.com,<br> https://www.datacamp.com/community/tutorials/machine-learning-python/](https://www.datacamp.com/community/tutorials/machine-learning-python/)
- [pythonprogramming.net,<br> https://pythonprogramming.net/Deutsch-jozsa-hadamard-quantum-computer-programming-tutorial/](https://pythonprogramming.net/Deutsch-jozsa-hadamard-quantum-computer-programming-tutorial/)
- O. Kramer, *Scikit-learn*, New York, NY: Springer, 2016
- G. Hackeling, *Mastering Machine Learning with scikit-learn*, Birmingham, UK: Packt Publishing Ltd, 2017
- C. Boettiger, *An introduction to Docker for reproducible research*, New York, NY: ACM , 2015
- J. Gruska, *Quantum Computing*, vol 2005, London, UK: McGraw-Hill, 1999
- O. H. M. Ross, *A review of quantum-inspired metaheuristics: Going from classical computers to real quantum computers*, vol 8, Piscataway, NJ: IEEE, 2019, pp. 814-838 
- S. Aarthi and P. N. Singh, *Quantum Circuits - An Application in Qiskit-Python*, Piscataway, NJ: IEEE, 2021, PP. 661-667
- M. Hillery, *Coherence as a resource in decision problems: The Deutsch-Jozsa algorithm and a variation*, vol 93, St. Paul, MN: Springer, APS, 2016, pp. 12-111