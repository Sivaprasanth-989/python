# python
working with dictionary 
dict_a={'name':'sivaprasanth','age':15}
dict_b=dict_a.copy()
dict_b['age']=19
print(dict_a)
print(dict_b)
print(id(dict_a))
print(id(dict_b))

dict_={'name':'monkey D Luffy','age':20,'dream':'pirate King'}
print(len(dict_))
is_present='monkey D Luffy' in dict_
print(is_present)
# dict_.clear()
print(dict_)

for keys in dict_.keys():
    if keys=='age':
        del dict_[keys]
print(dict_)



