# Magister test - Titanic Dataset

## Questions:

### 1. How many people were in the Titanic?

To return the number of **people**, we just execute the length function to **count** of the rows. That means **891** people survived according to the dataset.

### 2. How many male and female population survived?

According to the 'train' dataset, **233** female and **109** male populations **survived**. First of all, we filtered the information in a new dataframe, returned the count using the length function and then we displayed them in bar plots.

### 3. Which was the Top 10 older ages and the Top 10 older ages who did not survive?

To answer the questions, first, we created two new data frames to filter the people who survived and the ones who didn't make it in the other one. Afterwards, we **sorted** by age in **descending** order and **limiting** the rows returned by **10** for both data frames.

### 4. How many positions or titles were in the ship? (Captain, Mrs., Miss., etc.)

Instead of using REGEXP, we used the split function from Pandas in two steps: In the first, we extracted the characters AFTER the comma and then the characters BEFORE the dot symbol.

### 5. What is the sum of the fare value in EUR?

The total amount in EUR was **33.571,92€**, doing the total sum of multiplying each fare per 1,17, which is the exchange rate from June 2 of this year.
