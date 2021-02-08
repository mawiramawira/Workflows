During any Machine Learning project, do this:
[]PART I: Frame the problem
    []What is the business objective?
    []What the current solution looks like
    []Is it 
        []Supervised
        []Semi-supervised
        []Unsupervised
        []Reinforcement Learning
    []What kind of task is it
    []Should you use 
        []batch learning 
            []If whole dataset is needed
        []online learning techniques?
            []If data is live and incremental
            []If training/data is memory intensive
    []Check the assumptions
        []Validate and document any assumptions used
[]PART II: Start implementing the solution
    []Get the data
    []Start small
        []Use only 5 rows to model
        []Only expand when doing a major evaluation
    []Exploratory data analysis
        []Visualize the raw dataset and the features that are there
            []Number of features and rows
            []Missing data
        []Use statistics background to gain insight into the data
    []Prepare the data for machine learning algorithms
        []Split the data into train,validation and test sets
        []Cleaning
        []Refactoring labels
        []Dimensionality reduction
        []Combining features
        []Scaling and standardization
    []Iterate
        []What hypothesis is going to be used - model
        []Select a perfomance measure against the hypothesis
        []Implement the model and train it
        []Use the validation set to check the model
        []Fine tune parameters
            []Pick a model
            []Use an ensemble
            []Hyper-parameters
    []Check with the real test set
    []Deploy the system
 
