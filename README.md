# Dictionary
print("DICTIONARY")
DICTIONARY={"ROSE":"A kind of flower" ,"CYCLE":"A kind of vehicle" ,"BEE":"A kind of insect" ,"COTTAGE":"A type of house"}
# print(DICTIONARY)
print("ENTER YOUR WORD-\n")
W=input()
WORD=W.upper()
MEANING=DICTIONARY.get(WORD)
print("THE MEANING IS-\n")
print(MEANING)
print("Is it okay?")
input()
print("THANK YOU")
