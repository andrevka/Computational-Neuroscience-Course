Computational Neuroscience Course
=================================

This repository contains materials and codebase for the Computation Neuroscience course at the Institute of Computer Science of University of Tartu.
https://courses.cs.ut.ee/2015/neuro/spring/Main/HomePage

2020
----
There will be 6 home works. We highly recommend using conda to make things easier and compact. 

1. Install the propriate [miniconda](https://conda.io/miniconda.html) in relation to your operating system 
2. For **linux** open terminal, **Windows** users need to open conda terminal.
3. Execute
```
conda create -n Py3_ICNS python=3 matplotlib jupyter numpy pandas
```
4. Activate the environment
	1. **Linux** ``` source activate Py3_ICNS```
	2. **Windows** ``` activate Py3_ICNS```
5. Execute ``` jupyter notebook```

2019
----
In 2019 everything will be done in jupyter notebook. To make things easier we suggest using conda, you can install the it from here:https://conda.io/miniconda.html

We included Py3_ICNS.yml file in `2019` folder to help you to create a conda envrionment. To import the file use the command below.

```
conda env create -f Py3_ICNS.yml
```

Notice: the homeworks are not final until the due time to issue each homework.


2018
----
Only 5 homeworks. Slight changes in the excersises. 

2015
----
Second run of the course. Changed order of practice sessions, updated exercises.

2014
----
First version of the course materials

Copyright
---------
Copyright 2014, Raul Vicente, Ilya Kuzovkin.
University of Tartu.

* Lecture and Practice materials are subject to CC-BY-SA licence. 
* Source code is subject to MIT licence.
* Libraries and data used are subject to their own licences and copyrights.
