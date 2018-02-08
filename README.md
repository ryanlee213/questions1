# questions1

1. With pandas data frames, I'm having a difficult time figuring out how to separate the rows with integers from the rows == 'nan'. 
When I used the .describe() method, the output came out NaN for the quartiles. I was hoping to find a way to take out or ignore the NaN in the dataframes. I am able to extract anything that is a number into a list, and possibly a dictionary, but I was hoping to be able to do so within the data frames. I have been trying things with notnull(), but haven't been successful with that as well.

- Or, if df.iloc[1, 0] = 1955, then how can I get the row index (in this case 1) given 1955?

- With that, I want returned another column's values in those row indices.




2. Is pandas different for Python 2 and 3?
Because some of the code in the pandas documentation doesn't work when I try using it (i.e., isna(), instead using notnull())
https://pandas.pydata.org/pandas-docs/stable/missing_data.html



3. In Unit 3 Lesson 3 Assignment 2, ln 4, plotting the variable rand1 against norm in qqplots:
plt.plot(norm, rand1, "o") 
plt.show() 

# What does the "o" do?
