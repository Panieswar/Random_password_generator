# Random_password_generator

we will create a password generator that helps us generate random and strong passwords quickly.

Why do we need a password generator?

Because we can’t think of different patterns of passwords instantly.

But, it is not the same case with computers. Computers can generate random and strong passwords based on our customizations in seconds. There are many password generators available.



Password Generator

The best thing about creating our own password generator is that we can customize it as we like.

First, we will create a password generator that asks the length of the password and generates a random password containing digits, alphabets, and special characters.

Next, we will improve it by asking the number of each type of character, like the number of digits, alphabets, and special characters.


Steps

1)Store all the characters as a list. We can use the string module of Python or type all of them.

2)Ask the user to enter the length of the password.

3)Shuffle the characters using the random.shuffle method.

4)Initialize an empty list to store the password.

5)Write a loop that iterates length times.

6)Pick a random character from all the characters using the random.choice method.

7)Append the random character to the password.

8)Shuffle the resultant password list to make it more random.

9)Convert the password list to string using the join method.

10)Print the password.



We have seen how to create a password generator.

Can we add more features to it?

Yeah, we can add as many as we want. But, make sure that the resultant password is strong enough.

Generate the passwords from the code and use them for your next online account.
