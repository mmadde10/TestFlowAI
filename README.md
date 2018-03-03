# TestFlowAI
Testing AI

## Warning!
This version of Tensorflow is not optimized for CPU. If you have a GPU then you are fine. CPU will work but will throw some warnings. To optimize please [Build from Source](https://www.tensorflow.org/install/install_sources)



## Set Up
  * Install Python 
  ``` brew install python```

  * Install Pip if not included in Python
  
  * Clone Repo
  ```git clone https://github.com/Guaranteed-Rate/InceptionTests.git```

  * cd into Repo
  
  * Setup Virtual Environment  
   * The recommended way to run your tests would be in [virtualenv](https://virtualenv.readthedocs.org/en/latest/). It will isolate the build from other setups you may have running and ensure that the tests run with the specified versions of the modules specified in the requirements.txt file.
    ```$ pip install virtualenv```
    * Create a virtual environment in your project folder the environment name is arbitrary.
    ```$ virtualenv venv```
    * Activate the environment:
    ```$ source venv/bin/activate```
    * Install the required packages:
    ```$ pip install -r requirements.txt```
  
  
## Dataset 
  * This repo creates a model based on California house prices. This Repo is meant for training purposes only.
  
## Start
  * ```sh 
    python main.py
  ```
