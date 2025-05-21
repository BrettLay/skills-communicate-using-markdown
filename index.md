# Hello
I am writing a markdown for the changes I made to this file. 

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)

A code example from Python:

#declare variables
income = float()
amount = str()
rate = float()
saved = float()
left_over = float()
#Get income and how much the user wants to save
income = float(input("Enter your income this week:  "))
amount = input("How much do you want to save (none, a little, half or a lot):  ")
#Determine the rate of savings
if amount == "none":
    rate = 0
elif amount == "a little":
    rate = 0.2
elif amount == "half":
    rate = 0.5
else:
    rate = "0.75"
#Determine amount for savings
saved = rate * income
#Determine leftover amount
left_over = income - saved
#output rate, saved and left over 
print("Savings Rate:  ", rate)
print("Amount Saved:  $", saved)
print("Left over:  $"+ str(left_over))
