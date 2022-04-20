# winter_of_code

## Linear Regression

function gradient_descent takes 4 inputs 
1. feature value (input value of columns)
2. output value (y_true)
3. learing rate (default=0.02) 
4. max iterations (default=1000)

function standard scaler is used to standardise the feature values 

function cost_func returns the RMSE value 

matplotlib is used to plot graph of iteration vs cost

## polynomial regression

function find_cases retruns all the possible powers it takes two inputs 
1. value_sum refers to total power
2. numb_features refers to number of varibales 

all_powers function provides the all powers 

function cost_func returns the RMSE value 

poly_features function apply power to all the columns 


## logistic regression 
in the main code block it takes one output and then creates a data frame with that particular output 
and then run binary logistic regression and save that model 

get_para function rerurns parameters for that data frame 
standardize function is used to standardize data set 


## neural network 
generate_parameters function generates random parameters 

forawrd prop fills the variable nodes_values with values after every pass

after complete one forawrd pass we work with back prop that provides the value of gradients 
function back_prop is used 

function update_parameters updates the parameters using the gradients it gets after back prop

cost function here is log loss function 

multi_class_y_train is used as one hot encoder 

## knn algorithm 
3 different types of distance formulae are being used here 
1. Euclidean_distance
2. Hamming_distance
3. Manhattan_distance

first find all the distances and then sort them then
take first k points and then take the most repeating labels 
that would be final answer 

there is some issue while running the code on google colab 

## k means clusterring










