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

**Issue Summary:**

While working with `pandas_profiling` in a Python environment, I encountered a compatibility issue related to the `pydantic` library. The error message indicated a `PydanticImportError`, stating that `BaseSettings` had been moved to the `pydantic-settings` package in `pydantic` version 2.5. This change led to a conflict with the existing `pandas_profiling` implementation, which seemed to rely on the older structure of `pydantic`.

**Steps Taken:**

1. **Updated Imports**: Attempted to update the import statement in my code to use `from pydantic_settings import BaseSettings` as per the new `pydantic` structure.

2. **Library Updates**: Ensured that `pandas_profiling` was up to date, along with other related libraries like `ydata-profiling` and `pydantic`.

3. **Dependency Conflict Investigation**: Utilized `pip show` to investigate the versions and dependencies of the involved libraries. Identified that `pandas_profiling` was the problematic library causing the `PydanticImportError`.

4. **Attempted Alternatives**: Explored updating other related libraries, like `confection`, `spacy`, and `thinc`, which also depend on `pydantic`, to ensure compatibility with the newer version of `pydantic`.

**Outcome:**

Despite these efforts, the compatibility issue with `pandas_profiling` and `pydantic` could not be resolved. As a temporary workaround, the decision was made to comment out the problematic `pandas_profiling` code snippet and proceed with the exploratory data analysis, bypassing the use of `pandas_profiling` for the time being.

This experience highlights the challenges of managing dependencies in Python environments, especially when dealing with rapidly evolving libraries. Future updates to these libraries may resolve this issue, and revisiting the implementation at a later date might be beneficial.

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
