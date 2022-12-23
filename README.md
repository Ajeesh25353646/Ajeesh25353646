- 👋 Hi, I’m @Ajeesh25353646
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Ajeesh25353646/Ajeesh25353646 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
print("hello world",7)
print(5**4)
print("bye")
print("Im a good boy\nIm 21")
print("hey", 6, 7, sep="-", end="009\n")
print("herry")
b = complex(8, 2)
print(b)
print("the type of b is ",type(b))
dict1 = {"name":"sakshi","age":20}
print(dict1)
name = "Ajeesh"
print(name[0])
me = """I am ajeesh 
I am not feeling well today"""
print(me)
a = 5
b = 6
#addition
print(a + b)
#multiplication
print(a*b)
#exponenetial
print(a**b)
#division
print(a/b)
#substraction
print(a-b)
name = "Ajeesh garg"
print(name.find("j"))

print(name.upper())
print(name.replace("Ajeesh garg" , "tony stark"))

# finding if the character is present in a string (True/False)
print("garg" in name)
print("h" in name)

# writing character present at a specific index
print(name[0])
print(name[7])
 
# Taking a new bigger string
names = "Harry,Shubham"

# For printing first five characters of the string - string slicing
print(names[0:4])
print(names[1:4])

# Negative string slicing
fruit = "Mango"
print(fruit[0:-3])
# here, the python consider the negative index is taken like  = lenght of string - the number, this means here 5-3 , here we see index as 0:2

print(fruit[-3:-1])


# To find the lenght of a string
print(len(names))


# Tells remainder
print(5%2)

# More string slicing bc concept is a little hard
nm = "Harry"
print(nm[-4:-2])

# Make the string into a list - divide all the ekements which have space in between them into different list elements of the same list
print(name.split())

print(name.upper)
print(name.lower)

# It says true and false & tells whether the given string ends withat particular characters or not
print(name.endswith("!!!"))

# To remove the something in the last of the string 
a = "!!!Harry!!!!!"
print(a.rstrip("!"))


# Capitalise method = It capitalises the first letter of the string and leave the rest of the string in lower cases
blogheading = "introduction to the js"
print(blogheading.capitalize())

# Count() = using this we can count no of times a word that occurs in a string
print(blogheading.count("to"))

# Centre method = Align the string to the centre in the output
print(blogheading.center(50))

# We can also provide padding character. It will fill the rest of the fill characters provided by the user.
#print(blogheading.centre(50, ".")

str = "He is name is Dan. He is an honest man"

# The find method searches for the first occurence of the given value and then tell the index of it  #python is just an intrepretor which doesnt understand that 's is also is, therefore it interprets the second is as the first is and shows its index
print(str.find("is"))

# If the defined characters arent present in the string, then the find method will show -1 as the index
print(str.find("ish"))

# Index method and find methods are same except the fact that in this method, it will shown an error (instead of showing -1) if the character isnt present in the string
#print(str.index("ish")

# strip method - The strip() method removes any white spaces before and after the string
print(str.strip())

# We can even also check for a value in-between the string by providing start and end index positions.
str1 = "Welcome to the Console !!!"
print(str1.endswith("to", 4, 10))

# isalnum() - The isalnum() method returns True only if the entire string only consists of A-Z, a-z, 0-9. If any other characters or punctuations are present, then it returns False.
str1 = "WelcomeToTheConsole"
print(str1.isalnum())

# isalpha() - The isalnum() method returns True only if the entire string only consists of A-Z, a-z. If any other characters or punctuations or numbers(0-9) are present, then it returns False.
str1 = "Welcome"
print(str1.isalpha())

# islower() - The islower() method returns True if all the characters in the string are lower case, else it returns False. 
str1 = "hello world"
print(str1.islower())


## isprintable() - The isprintable() method returns True if all the values within the given string are printable, if not, then return False.
str1 = "We wish you a Merry Christmas"
print(str1.isprintable())


#isspace() - The isspace() method returns True only and only if the string contains white spaces, else returns False.

str1 = "        "       #using Spacebar
print(str1.isspace())
str2 = "        "       #using Tab
print(str2.isspace())

# istitle()  -The istitile() returns True only if the first letter of each word of the string is capitalized, else it returns False.
str1 = "World Health Organization" 
print(str1.istitle())

str2 = "To kill a Mocking bird"
print(str2.istitle())
 
 
# isupper() - The isupper() method returns True if all the characters in the string are upper case, else it returns False. 
str1 = "WORLD HEALTH ORGANIZATION" 
print(str1.isupper())
  

# startswith() - The endswith() method checks if the string starts with a given value. If yes then return True, else return False. 
str1 = "Python is a Interpreted Language" 
print(str1.startswith("Python"))


# swapcase() - The swapcase() method changes the character casing of the string. Upper case are converted to lower case and lower case to upper case.
str1 = "Python is a Interpreted Language" 
print(str1.swapcase())

#title() - The title() method capitalizes each letter of the word within the string.

















