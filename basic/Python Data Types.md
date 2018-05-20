# Python Data Types

This guide is an overview of five Fundatamental data types:

### Fundamental Data Types

1. int
2. float
3. complex
4. complex

### Immutable Vs Fundamental data types:
1. all fundamental datatypes are immutable (int/float/complex/str/bool)
2. one object is created then we cannot change object
3. if we change the object then new object will create

Advantages on Immutable: 
We all know creation of objects is always a complex task that affect memory utilization and overall performance
		-EX 
		1  x=10
		  y=10
		  -id (x) =12345
		  -id( y) =12345
		  -x is y ; True (if both are pointing to same memory objects then this True (is operator used to check ))

		  y is a reference for x 

		  -Before creating a new object python check the content and create a references so performance and memory will Up

		2 x=257
		  y=257
		  x is y : False (because reusing is applicable for 0-256)
