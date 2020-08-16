# combinations_generator
Python Jupyter notebook that generates all combinations of 10 features


- calculates the number of combinations
- generates the combinations using itertools.combinations i.e. number of single features, number of pairs etc e.g. ['title, firstname', 'title, surname'...]
- creates a dataframe of binary values for the combinations e.g. {"title":[1],"firstname":[0], ...}
- downloads dataframe to a csv (so it can be opened in Excel where conditional formatting can be applied to more easily see the combinations)


