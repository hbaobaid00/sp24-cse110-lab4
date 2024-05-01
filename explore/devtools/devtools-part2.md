# Answers
1. The bug was that JavaScript was reading the two variables, `num1` and `num2` as strings and not actual numbers. Because of this, the javascript is doing string concatenation instead of doing basic arithmetic.
2. You can fix this by doing a type conversion using Number() which would convert the two variables data type from string to number.
