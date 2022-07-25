
# Treat the missing values


- do nothing -> very risky
- replace with Zero -> this is also risky
- if numerical non-categorical column (continous) -> then replace:

        1. with average -> when the data is not skewed (normal distributed)
        2. with median -> when data is skewed.
- if categorical data, then find the most frequently occuring value (mode), and replce the nulls with this value.
- if non-categorical text data is missing, then if the missing bolume is very low -> then remove those rows. But ensure the corresponding rows in the other table(s) are removed.
