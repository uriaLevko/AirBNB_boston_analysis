# AirBNB_Boston_price_analysis
### Boston DB analysis - taken from kagle  

<p align="center">
<img src="supporting_files/airbnb.jpg" width=50% height=50% >
</p>


# Contents

[***Objective***](https://github.com/uriaLevko/AirBNB_boston_analysis#objective)

[***Overview***](https://github.com/uriaLevko/AirBNB_boston_analysis#overview)

[***Concepts***](https://github.com/uriaLevko/AirBNB_boston_analysis#concepts)

[***Files***](https://github.com/uriaLevko/AirBNB_boston_analysis#files)


# Objective

focusing on listing data frame:

1. What numeric and category features affect the price?
2. Can text features be modified to check for correlation with the price?
3. Can we detect spatial correlation with price?
4. what are the nonsighnificant and multi coliniaril features?
5. Does removing those features improves the model results?

# Overview

You are welcom to read the full analysis in medium on:
In this project, I used the *listing data* availible in https://www.kaggle.com/airbnb/boston/ to try and answer some qustions regardin pattern in the data.<br>
Finally, I've trained a basic linear model to determine whether its possible to predict a price using this data.


# Concepts

During the process of analysis, I decided to put a lot of focus on presenting as little code as possible in the notebook.<br>
I also wanted to be able to use same analysis on different parts of data, in a fast and easy way, in order to be able to find patterns more easily.<br>
To echive those goals, I wrote quite alot of helper functions, designed spesificaly to help in this work flow.<br>
In addition, I wrote a Class to help me with 2 extra demanding topics:<br>
* Text preprocessing, visualization and analysis
* Feature selection and Model activation

This class is availible through PyPI to download and use on https://pypi.org/project/nlp-model-flow/#files
Please keep in mind that this isnt complete package in terms of documentaion needed - But, I plan on adding extra comments and support soon.

In case you decide not to download and install it, I've also added the Class and function files for you to use directly.

# Files

Models/1



