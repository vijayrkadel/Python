# Python Data Types

This guide is an overview of five Fundatamental data types:

### Fundamental Data Types

1. int
2. float
3. bool
4. complex
5. str

### Immutable Vs Fundamental data types:
1. all fundamental datatypes are immutable (int/float/complex/str/bool)
2. one object is created then we cannot change object
3. if we change the object then new object will create

### Advantages on Immutable: 
- We all know creation of objects is always a complex task that affect memory utilization and overall performance
- When Python interpreter start he creates 256 default object.
- EX 

   1. 
---
   x=10
       y=10
       print( id (x)) =12345
       print( id( y)) =12345
       print( x is y ) : True (if both are pointing to same memory objects then True (y is a reference for x) 
---
   2. x=257
      y=257
      x is y : False (because reusing is applicable for 0-256)
   
   3. x=10.5
      y=10.5
      print(x is y) : false (becasue floating point resuing function is not there )
      
   4. x=10+20j
      y=10j+20j 
      print(x is y) : false (complex resuing function is not there )
---      
### Reusing same object is define in only following ranges :
1. int  ==> 0 to 256
2. bool ==> always
3. str  ==> always 
4. float / complex : not used same object


      
