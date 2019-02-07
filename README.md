# Project on churn Prediction of telecom customers
We have the customer data for a telecom company which offers many services like phone, internet, TV Streaming and Movie Streaming.

The problem statment is to 
1. Find the Best model that predict the behavior to retain customers.
2. Analyze all relevant customer data and develop focused customer retention programs.

## How to view the project
1. Simply open the notebook file (dlnd_language_translation_acad.ipynb) in the project by clicking it. 
2. If it is showing any error, may be bacause of slow intenet or other issue open the below link
 
      &nbsp;&nbsp;&nbsp;&nbsp; Click here [Project link](https://nbviewer.jupyter.org/github/kumar-sam/project-8/blob/master/preventing_customer_from_unscribing_a_telecom_plan.ipynb) 

## Installation
To run this project, following library need to be installed inside a local virtual environment

```
conda install numpy
conda install pandas
conda install matplotlib
```
```
!pip install xgboost
```
## Running the project
To run this project, first download the notebook file(.ipynb) and extract it. Then set up your conda virtual environment. You may take help from interet for how to setup conda virtual environment.

once you set up virtual enviroment. start the notebook by running the following command in Command prompt(windows).
```
activate environment_name
jupyter notebook
```
You will be redirected to a browser tab. Navigate to the notebook file location through the notebook browser and open it.

once you open the notebook file, just go cell by cell and run it by
```
Ctrl + Enter
Shift + Enter
```

### Hyperparameters

Hyperparameter          | Number |
----------------------- | ------ |
Epochs                  | 10     |
Batch size              | 512    |
RNN size                | 128    |
LSTM layers             | 2      |
Encoding embedding size | 128    |
Decoding embedding size | 128    |
Learning rate           | 0.001  |
Keep probability        | 0.55   |

## Observations

1. better model performance with 91% validation accuracy.  
2. Sample output  

 - Input  
    - Word Ids:      [120, 172, 10, 36, 151, 179, 186]  
    - English Words: ['he', 'saw', 'a', 'old', 'yellow', 'truck', '.']  

 - Prediction  
   - Word Ids:      [182, 99, 65, 195, 282, 5, 243, 69, 1]  
   - French Words: il a de visiter le camion automne . <EOS>  


### Author: Sanjeev kumar
#### *** This project is strictly for learning purposes only. **
