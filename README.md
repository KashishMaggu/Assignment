# Assignment
#task 1 To print First Name starting with a vowel
users=['Angela','Frances','Louise','Julie','Brandon','Gary','Kimberly','Lillian','Jeremy',
       'Shawn','Diana','Donna','Lois','Matthew','Joshua']
vowels = "AaEeIiOoUu"
result=list(filter(lambda x:x[0] in vowels,users))
print(result)

#task2 write a program to create a map function using lambda function to return fahrenheit value.
celsius=[87,99,12,99,-11,93,71,22,37,97.5]
fahrenheit = list(map(lambda x: (9/5)*x + 32, celsius))
print (fahrenheit)
    
