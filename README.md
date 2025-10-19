# python-data-programming
#In Class Assessment 3
print(f"Total number of records: {df.shape[0]}")
print(f"Total number of columns: {df.shape[1]}")
print(f"Total number of records: {df.shape[0]}")
print(f"Total number of columns: {df.shape[1]}")
print("country recorded the highest number of casualties overall is",df.loc[df['Casualties'].idxmax()]['Country'])
