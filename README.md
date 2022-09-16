# Python_FUnction_code
#Que.:-Write Python code to create a function called most_frequent that takes a string and prints the letters in decreasing order of frequency. Use dictionaries.


#Code:-
def most_frequent(String1):
    d =dict()
    for key in String1:
        if key not in d:
            d[key]=1
        else:
            d[key] +=1
    return d
a=most_frequent(reversed("Mississippi"))

print("\n",a)
