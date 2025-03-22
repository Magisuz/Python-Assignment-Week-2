# Python-Assignment-Week-2
#Create empty list called my_list
my_list = []
#Append element 10,20,30,40
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)
#Insert value 15 at the 2nd position
my_list.insert (1,15)
#Extend my_list with another list
my_2_list = [50,60,70]   #my_list.extend([50,60,70])
my_list.extend(my_2_list)
#Remove last element from my_list
my_list.pop (-1)
#Sort my_list in ascending order
my_list.sort () 
#Print the index of value 30 in my list
print (my_list.index(30))
#Print my list
print (my_list)
