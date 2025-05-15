We have a vector of dates and you want to select one or more, Use two boolean conditions as the start and end dates Alternatively, we can set the date column as the DataFrame’s index and then slice using loc
Whether we use boolean conditions or index slicing is situation dependent. If we wanted to do some
complex time series manipulation, it might be worth the overhead of setting the date column as the
index of the DataFrame, but if we wanted to do some simple data wrangling, the boolean conditions
might be easier.
