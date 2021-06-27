# Python-Numpy
To create arrays of data. it could be of list.

Shape of Numpy is mainly handled only when it is 2 dimensional array. 
For instance, p=array([1,2 3,4,5]) => the p.shape displays as (5,)
SO, only for 2 dimensional arrays, it displays with correct answer: p=array([2,4],[4,5]) => (2,2)
To specify the object with different length in the array string, we have to go with the below option:
p=np.array([[1,2,3],[2,4],[1,2,3,4]],dtype=object)
array([list([1, 2, 3]), list([2, 4]), list([1, 2, 3, 4])], dtype=object)
