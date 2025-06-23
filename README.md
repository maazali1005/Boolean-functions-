# Boolean-functions

#all

near= [0,0,0,1]

boo=[True, False, True]

res=np.all(near)

print(res)

resb=np.all(boo)

print(resb)

#any

near= [0,0,0,1]

boo=[True, False, True]

res=np.any(near)

print(res)

resb=np.any (boo)

print(resb)

#where
arr=np.array([2,3,5,6])

h=np.where(arr > 5, 'high', 'low')

print(h)# Boolean-functions-
