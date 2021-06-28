[
<img width="868" alt="Screen Shot 2021-06-27 at 9 33 28 PM" src="https://user-images.githubusercontent.com/80833988/123580839-73eae080-d78f-11eb-8c9a-6ed9078506f0.png">
](url)

# Machine Learning Trading Bot


📌 Challenge 14

> "In this Challenge, I assumed the role of a financial advisor at one of the top five financial advisory firms in the world. In recent years, the firm has heavily profited by using computer algorithms that can buy and sell faster than human traders.
"


## Table of content
- [Overview of the project and project goals](https://github.com/nataliaburrey/Neural_Network#overview-of-the-project-and-project-goals) 
- [Software version control](https://github.com/nataliaburrey/Neural_Network#software-version-control)
    - [Libraries](https://github.com/nataliaburrey/Neural_Network#libraries)
    - [Work with GitHub](https://github.com/nataliaburrey/Neural_Network#work-with-github)
    - [How to install](https://github.com/nataliaburrey/Neural_Network#how-to-install)
- [Project findings](https://github.com/nataliaburrey/Neural_Network#project-findings)
- [Helps recruiters](https://github.com/nataliaburrey/Neural_Network#helps-recruiters)
- [License](https://github.com/nataliaburrey/Neural_Network#license)

[
<img width="793" alt="Screen Shot 2021-06-27 at 9 33 58 PM" src="https://user-images.githubusercontent.com/80833988/123581019-e1970c80-d78f-11eb-9bd2-8231bc04da79.png">
](url)


## Overview of the project and project goals

In a Jupyter notebook I Implemented an algorithmic trading strategy that uses machine learning to automate the trade decisions, Adjusted the input parameters to optimize the trading algorithm, Trained a new machine learning model and compare its performance to that of a baseline model, Created an Evaluation Report



To complete the task the following steps were perfomed:

  - Establish a Baseline Performance

  - Tune the Baseline Trading Algorithm

  - Evaluate a New Machine Learning Classifier

 



## Software version control


### Libraries 
*  Pandas - is a software library designed for data analytics that makes it easier to work with data from practically any type of file. Pandas supplies powerful tools for working with time data in particular, and time is a key aspect of financial analysis. Analysts typically compare and measure financial assets—from single stocks to large portfolios—across time.
* Following libraries were imported

```
# Import the required libraries and dependencies

import pandas as pd
import numpy as np
from pathlib import Path
import hvplot.pandas
import matplotlib.pyplot as plt
from sklearn import svm
from sklearn.preprocessing import StandardScaler
from pandas.tseries.offsets import DateOffset
from sklearn.metrics import classification_report
```


 
### Work with GitHub
* Repository created on GitHub
* Files were  committed using command line
* Our repository is organized, and includes Resources folder with CSV  project files, 
* Jupyter Notebook with code runs without errors.
* Answers on nesassary questions are included

### How to install

* Save remote repo from GitHub to your computer (Desktop): in Terninal type:

```
cd desktop

git clone https://github.com/nataliaburrey/Machine_Learning_Trading_Bot.git
```

now you can find repo on your desktop


* Choose [ machine_learning_trading_bot.ipynb ] file to see the Jupyter Notebook with code.


## Project findings

[
<img width="1273" alt="Screen Shot 2021-06-27 at 10 01 31 PM" src="https://user-images.githubusercontent.com/80833988/123582936-8ff08100-d793-11eb-9626-cc47fe596878.png">
](url)

[
<img width="843" alt="Screen Shot 2021-06-27 at 10 02 05 PM" src="https://user-images.githubusercontent.com/80833988/123582798-51f35d00-d793-11eb-9866-c3ee04a6a828.png">
](url)


Its always a very complicated question to make a desision which strategy is to empliment. In this case first model seems like predicting an actual trend is better. In this scenation we see that first model project results closer to a actual ones, but classification report shows that the first one  has slitely better quality of prediction. It must very vell be likely, that first model is simply follows the first one, to make a decision I would further run one more version of the model to make sure my prediction is correct.

## Helps recruiters

The project was created in collaboration with Berkeley Fintech Bootcamp team


## License

MIT


📔 Contact me: 
📩 nataliaburrey@gmail.com
