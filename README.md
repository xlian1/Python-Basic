# Python basic
This is a file to help me with learn Python, noting what I don't familiar with.

1. Chaining Comparision Operator in Python

  if a < b < c:

    statements()


2. While loop
  
  while (condition):
  
    statements(s)

3. For loop

  sequence may be range(1,n), list=[], tuple=(), string, or dict.
  
  for iterator_var in sequence:
  
    statements(s)


4. Loop Control Statement: Continue/break
  
  Continue: start a new loop
  
  break: jump out of the loop


5. Iterator
  A =['cat', 'dog', 'rabbit']
  
  a. C-type 
  
    for(i > len(A)):
    
      print A[i]
      
      i += 1
      
  b. for each
  
    for i in A:
    
      print i
  
  c. Enumerate
  
    for i, x in Enumerate(A, start=1):
    
      print i, x
      
6. Looping Extensions:

  1) Zip function
  
    Combining similar iterators at the same ith position
    
    a = [1,2,3]
    
    b = [4,5,6]
    
    for a,b in zip(a, b):
    
      print a,b
    
  2) 'Unzip' function
    
    a, b = zip(* [(1,4)
                  (2,5)
                  (3,6)])
    
    output: a=[1,2,3]  b=[4,5,6]
    
    
  
  
    
    
  
      
  
  


