# Problem-Solving1_Variables

# Example, a = 5 and b = 10. Then output a = 10 and b = 5. Whatever 'a' was before, it  will be 'b' result and vice versa. 

# Don't change the code below############################

a = input("a: ")

b = input("b: ")

# Don't change the code above###############

# Write your code below this line###############

c = a

# Explanation: so assign c the empty variables c = a. Because a = 5, so 'c' is 5 now.

a = b

# Explantion: Because b = 10. We make a = b. so 'a' is 10. 

b = c

# Explanation: we know 'c' is 5 in the start because of line 15, we assigned 'b' to be equal to 'c'. Therefore, 'b' is 5.

# In conclusion: we will get a = 10 and b = 5. 

# write your code above this line##################

# Don't change the code below################

print("a: " + a)

print("b: " + b)

# This is how I solve this problem. We know we have two variables, which is 'a' and 'b'.

# For simplity, we image that there are cups. 'a' is coffee and 'b' is tea. Actually we also can do this problem with strings as variables.

# Solution: We add another variables, which is getting another empty cup. Let's call it, 'c'. 

# 1. Pour 'a' (coffee) to 'c'. Now 'c' has coffee. Hence, c = a. (Line 15)

# 2. According to Python, 'a' still has coffee. We pour 'a' coffee away to the sink, and fill with 'b' tea. Now 'a' has tea. Hence, a = b. (Line 19)

# 3. According to Python, 'b' still has tea. We pour 'b' tea away to the sink, and fill with 'c' coffee. Now 'b' has coffee. Hence, b = c (Line 23)

# 4. This is not important, but for people to understand. 'c' is still filled with coffee. If it is in an integer for a = 5; b = 10 , the result 'c' is still 5. 
