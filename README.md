# Data-Exploration
Data Exploration of ForestFire Dataset
Data Exploration:
1.
(i) Loading a Sample Dataset (forestfires.csv)
(ii) Brief explanation of the dataset columns.
(iii) Filtering dataset:
(a) creating a new dataset that only contains entries with an area value greater than 0
(b) How many rows does the new filtered dataset contain?
(iv) Statistical Analysis: Calculate the mean, minimum, maximum, and standard
deviation of the area column in the filtered dataset.
Discuss what the large standard deviation indicates about
the distribution of the area values

(v) Explore Distribution: Sort the filtered dataset by the area column in ascending
order and display the last 20 entries. Count entries
having an area larger than 100?

(vi) Calculate the median value for the area. State reason why median might be a
better measure than the mean.
(vii) Analysis:
(a) Find month that has the highest number of forest fires, mean temperature during that
month
(b) Find correlation between the number of forest fires and the mean temperature for
each month.

2. (i) Indexing:
(a) Convert it into a NumPy array. Retrieve and print the first 5 rows of the dataset using array
indexing.
(b) Retrieve and print the 'temp' (temperature) column using column indexing.
(ii) Slicing:
(a) Slice the dataset to obtain all rows and only the 'month', 'temp', and 'area' columns.
(b) Slice the dataset to get all entries from index 100 to 200.
(iii) Splitting:
(a) Split the dataset into two equal halves along the row axis. Showcase the first 5 rows of each
split.
(iv) Iteration:
(a) Calculate the sum of the 'temp' column using iteration and verify it
using NumPy's sum function
(v) Masking:
(a) Use boolean indexing to filter and print all rows where the 'temp' column has values greater
than 20°C. Create a boolean mask for entries where the 'area' is greater than 10 and use it to
retrieve and print the relevant rows.
