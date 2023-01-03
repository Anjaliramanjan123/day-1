# day-1
b=['1','2','3','4','5','6','8','7','9','11','10','12','14','13','15','17','16','18','19','20','21','22','23','24','26','27','28','30','29']
print(b)
 #to find the length of the list
print(len(b)) 
 #we can assign value by using indexingb[0]='anju' 
 #Append to insert element at end position 
b.append(1000)
print(b)
 #insert: to insert element at specified position
b.insert(0,'man')
print(b) 
 #remove:to remove wanted element
b.remove('20')
print(b)
 #to del element 
del b[2]
print(b)
 #pop: to remove element from last 
b.pop()
print(b)
 #pop using index 
b.pop(5)
print(b)
b.sort() 
# sort is used to sort elements
print(b)
b.sort(reverse=True)
print(b)


