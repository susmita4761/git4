# git4
Task 4 -Virtual Internship
#combining two dictionary adding values:
PYTHON DICTIONARY:

dict1={'a':100,'b':200,'c':300}
dict2={'a':200,'d':200,'c':100}
new={}
new.update(dict1)
for key,value in new.items():
    for i,j in dict2.items():
        if key==i:
            value=value+j
            new.update({key:value})
            print(new)
			
