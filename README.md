

    ****Feature Engineering****

# Objective
Trying to use  **One hot encoding** for categorical column . Also remove less categorical column if any feature having long list of categorical data.(Only For fun)


# Step perform for one hot encoding

 1. Find data set from kaggle (mercedes-benz)
 2. load few columns from dataset
 3. Apply one hot encoding for all column and found for 6 columns , its creating new 111 columns
 4. After that tried to filter top 10 category for every feature and then apply one hot encoding
 5. After applying OHEN , 55 new column create 


# Type of encoding

 1. Nominal Encoding **(order doesn't mater)**
    - One Hot Encoding
    - One Hot Encoding with multiple category(Above solution)
    - Mean Encoding
 2. Ordinal Encoding
     - Lebel Encoding
     - Target Guided Ordinal Encoding



# Target guided ordinal encoding
   Take one feature  with output(classification ) column, and try to calculate means for all category with help of output and sort the mean list and assign that rank to feature **.(apply same way to other feature)**
   
