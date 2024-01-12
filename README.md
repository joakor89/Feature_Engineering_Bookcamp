# Feature Engineering Bookcamp

## Introduction 

The field of Data Science, although seemingly complex, is in essence an exploration of information and the patterns within. Data science encompasses various methods and theories drawn from many fields within the context of mathematics, statistics, and computer science. This repository is devoted to a deeper understanding of Feature Engineering in Data Science, particularly Machine Learning, with exercises and solutions from the well-regarded book "Feature Engineering Bookcamp" (Ozdemir Sinan, 2022).

The primary aim of this repository is to provide an accessible yet comprehensive resource to those embarking on their journey in the field of feature engineering on data science. The repository will provide explanations, solutions, and insights into the numerous exercises contained within the aforementioned book.

## Content Overview

Section 1: Heatlhcare: Diagnosing Covid-19

Section 2: Bias & Fairness - Modeling Recidivism

Due to Libraries constraints, this notebook was run out on DeepNote. To resolve the ImportError: libtk8.6.so: cannot open shared object file: No such file or directory issue in a Deepnote notebook, you can attempt to install Tkinter, which should include the missing libtk8.6.so library. Since Deepnote runs in a cloud environment, direct system-level access to install packages like Tkinter might be limited, but you can try the following approach:

```sh
!apt-get install -y python3-tk
```

This command works for environments based on Debian or Ubuntu. If you're using a virtual environment within Deepnote, make sure to activate it before executing this command.

If this method does not work due to permission restrictions or specific configuration of the Deepnote environment, you may need to consult Deepnote's support or documentation for guidance on installing system-level dependencies.

In cases where installing Tkinter on Deepnote is not feasible, consider reviewing your code to confirm the necessity of Tkinter, or look for alternative approaches if Tkinter is not critical for your project. Additional docker file and requirements.txt can be found on data folder.

Section 3: Natural Language Processing - Classifying Social Media Sentiment

Section 4: Computer Vision - Object Recognition

Section 5: Time Series Analysis - Day Trading with Machine Learning

Section 6: Feature Store

Section 7: Putting All Together

## Usage and Contribution

This repository is open for all to use and learn from. However, keep in mind that this repository is meant to be a supplement to your learning and not a substitute for the book itself.

If you wish to contribute to this repository, please feel free to open a pull request. Let's cultivate a collaborative space where knowledge can be shared and gained.

### Note

As this repository strictly serves an educational purpose, it abides by the guidelines set forth regarding fair use. It does not aim to infringe upon any copyrights held by the author or the publisher.

### Citation

Ozdemir, S. (2022). Feature Engineering Bookcamp. Manning.

Remember: "It's for the ultimate end of science."

### Disclaimer

This repository is unofficial and not affiliated, endorsed or certified by Sinan Ozdemir, Manning. It has been created for educational purposes, and the repository owner is not responsible for any incorrect information or misuse.

Your journey in the exciting world of data science begins here. Dive in, explore, and let's learn together.

### Virtual Environment

```sh
pip install --upgrade pip
python3 -m pip install virtualenv
python3 -m venv env
source env/bin/activate
source env/bin/deactivate
pip3 install -r requirements.txt
```

### Github Environment

Performed from Terminal Console
```sh
1. git init
2. git remote add origin ["copy here ssh or https"]
3. git remote -v
4. git add -A
5. git add .
6. git commit -m "insert here your commit"
7. git status
8. git push origin master
```

### Additional GitHub Commands

if you already created your repository, then:
```sh
1. git remote add origin ["copy here ssh or https"] 
2. same procedure applied above
3. Note: if you already got your ReadMe.md & License.md then,
firstly request your git pull origin master. THIS IS ALWAYS A RECOMMENDED PRACTICE.
4. git push origin master
```
