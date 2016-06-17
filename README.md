# year_when_100
import datetime
now = datetime.datetime.now()
print("What is your name?")
name = input()
print(("Thank you %s, and how old are you?") % (name))
age = int(input())
print("Have you already had your birthday this year?")
birthday_already = input()
if birthday_already == "yes" or "Yes":
    #optional print "if" statement to check which of if/or elif is being executed
    #print("if")
    year_when_100 = now.year + 100 - age
    print("You will turn 100 in the year %s" % (str(year_when_100)))
else:
    #print("else")
    year_when_100 = now.year + 99 - age
    print("You will turn 100 in the year %s" % (str(year_when_100)))
