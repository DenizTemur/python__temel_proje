def flatten(x):
    flattened=[]
    for i in x:
        if type(i)==list:
            flatten(i)
        else:
            flattened.append(i)
    return flattened
