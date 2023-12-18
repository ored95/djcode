# Intro to DL

View: [Source](https://www.kaggle.com/learn/intro-to-deep-learning/course)

+ Environment: `python<=3.10`
+ [learntools](https://github.com/Kaggle/learntools)
    + Installing [Kaggle](https://www.kaggle.com/) learntools in local machine:

        + First go to the below link and download the file in Zip format:
    https://github.com/Kaggle/learntools

        + extract the file.

        + Go to command line, change the directory to extracted folder `learntools-master\learntools-master` , where `setup.py` file is available

        + Then type command `python setup.py install` and press **Enter**.

    + If you end up with error like – `File "C:\ProgramData\Anaconda3\Lib\site-packages\learntools-master\learntools-master\learntools__init__.py", line 2
    machine_learning, ml_explainability, ml-insights, ml_intermediate, python, \`. Then follow below steps:

        + open file – `learntools-master\learntools-master\learntools__init.py` from the extracted folder

        + Remove `ml_insights, ` from the `__init.py` python file
        + Save and close it.

        + Again, Go to command line, change the directory to extracted folder `learntools-master\learntools-master` , where `setup.py` file is available. Then type command `python setup.py install` and press **Enter**.
    