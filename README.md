# Pandas-Challenge

- District Summary: It is rather straightforward to calculate and return the values for the district summary. One interesting point is that the solution that calculates the total student count is logically incorrect in my opinion. There were duplicated student names so I applied the nunique() at first and the number was slightly smaller than that provided in the solution. The solution wanted us to apply the count() which does not factor in the duplicate student names.
- School Summary: For this portion of the exercise, when I did not polish the code and only conducted what was asked of, the output did not have header for the second column. Therefore, I had to reset the index back to default interger index and convert the dataFrame to a string presentation. I also noticed the type display at the bottom of the output is removed which makes the output more organized.
- Highest-Performing Scchools & Bottom Performing Schools: sort the % Overall Passing values and display the top 5 rows (using head()) in descending order (ascending=False) and asecending order (asecending=True) respectively. The instructor informed us about this in class.
- Math Scores by Grade & Reading Scores by Grade: This part is relatively straightforward. Most of the code were pre-existed and I only had to combine them to make one single DataFrame.
- Scores by School Spending & Scores by School Size & Score by School Type: The exercise's most challenging portion for me was the pd.cut function to categorize spending based on the bins. I used https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.cut.html and Stack Overflow (Q: Pandas how to use pd,cut()) as well as a lot of trial and error to produce the results.
