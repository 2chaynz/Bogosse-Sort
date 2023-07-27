#TRI STUPID

import random
from random import randint #distribution uniforme
#float : uniform , randint : int

def stupid(arr):
    triée = False
    while triée!= True:
        k=0
        for i in range(len(arr)-1):
            j = random.randint(0, len(arr)-1)
            arr[i], arr[j] = arr[j], arr[i]
            #CF shuflle(), un peu different mais même idée

        for i in range(len(arr)-1):
            if arr[i]<=arr[i+1]:
                k+=1
            else:
                None 
        if k==(len(arr)-1):
            triée = True
    return arr

test=[6,7,4,2,8,98]
stupid(test)
