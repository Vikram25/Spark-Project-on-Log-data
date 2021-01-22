## Log Data Analysis 

### Business Understanding

I'm going to perform some Data Engineering operations on log Dataset. The task or questions I will target for as below:
1. Cleaning and preparing raw data. 
2. Apply Spark transformation to get the final result.

My task is get the total number for GET and POST request each hour from log dataset.

### Table of Contents
1. [Installation](#installation)
2. [File Descriptions](#files)
3. [Results](#results)
4. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>
For this project I have used [Google Colab](https://colab.research.google.com/). 
    ### Setting up PySpark in Colab
    Use below code to install required programs to setup your environment.
    ```
    !apt-get install openjdk-8-jdk-headless -qq > /dev/null
    !wget -q https://downloads.apache.org/spark/spark-2.4.7/spark-2.4.7-bin-hadoop2.7.tgz
    !tar xf spark-2.4.7-bin-hadoop2.7.tgz
    !pip install -q findspark  ```

    Follow notebook for furthur instructions.

## File Descriptions <a name="files"></a>
There are 1 notebooks available here to showcase work related to the above questions. 
Markdown cells & comments were used to assist in walking through the thought process for individual steps.

log.txt - This file contains log data in raw format.



