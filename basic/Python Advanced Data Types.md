# Advanced Data types 

This guide is an overview of five Fundatamental data types:

1. bytes/ byte array : image/ video/ audio 
2. list[] mutable
3. tuple () Immutable
4. set (Mutable : duplicates not allowed )/forzenset(immutable )/
5. dict {}

### Missing Data types in Python 3 
1. long data type is not aviable in pythin 3 that is avilable in python 2 
2. char data type is not present , we can represent by str only

### List
1. insertion order preserved.
2. duplicate objects are allowed
3. heterogeneous objects are allowed.
4. List is dynamic because based on our requirement we can increase the size and decrease
the size.
5. In List the elements will be placed within square brackets and with comma seperator.
Ex:
a=[10,20,30,40]
l=[ i+i for i in a]
print(l)

#### List Methods
1. list.append(x) :Add an item to the end of the list. Equivalent to a[len(a):] = [x].
2. list.extend(iterable) :Extend the list by appending all the items from the iterable. Equivalent to a[len(a):] = iterable.
3. list.insert(i, x) Insert an item at a given position. The first argument is the index of the element before which to insert, so a.insert(0, x) inserts at the front of the list, and a.insert(len(a), x) is equivalent to a.append(x).

4. list.remove(x) :Remove the first item from the list whose value is x. It is an error if there is no such item.
5. list.pop([i ]) : Remove the item at the given position in the list, and return it. If no index is specified, a.pop() removes and returns the last item in the list. (The square brackets around the i in the method signature denote that the parameter is optional, not that you should type square brackets at that position. You will see this notation frequently in the Python Library Reference.)

6. list.clear() Remove all items from the list. Equivalent to del a[:].
7. list.index(x[, start[, end ]]) Return zero-based index in the list of the first item whose value is x. Raises a ValueError if there is no such item. The optional arguments start and end are interpreted as in the slice notation and are used to limit the search to a particular subsequence of the list. The returned index is computed relative to the beginning of the full sequence rather than the start argument.

8. list.count(x) :Return the number of times x appears in the list.
9. list.sort(key=None, reverse=False) Sort the items of the list in place (the arguments can be used for sort customization, see sorted() for their explanation).

10. list.reverse() :Reverse the elements of the list in place.
11. list.copy() :Return a shallow copy of the list. Equivalent to a[:].

### Tuple
1. Tuple is exactly same as List except that it is immutable. i.e once we creates Tuple
object,we cannot perform any changes in that object.
Hence Tuple is Read Only version of List.
2. If our data is fixed and never changes then we should go for Tuple.
3. Insertion Order is preserved
4. Duplicates are allowed
5. Heterogeneous objects are allowed.
6. We can preserve insertion order and we can differentiate duplicate objects by using
index. Hence index will play very important role in Tuple also.
Tuple support both +ve and -ve index. +ve index means forward direction(from left to
right) and -ve index means backward direction(from right to left)
7. We can represent Tuple elements within Parenthesis and with comma seperator.
Parenethesis are optional but recommended to use.
Ex:
s=(10,20,30)
s=10,20,30,40 
t=10,20,30,40 
print(t[0])
print(t[:])

### Set
1. If we want to represent a group of unique values as a single entity then we should go
for set.
2. Duplicates are not allowed.
3. Insertion order is not preserved.But we can sort the elements.
4. Indexing and slicing not allowed for the set.
5. Heterogeneous elements are allowed.
6. Set objects are mutable i.e once we creates set object we can perform any changes in
that object based on our requirement.
7. We can represent set elements within curly braces and with comma seperation
8. We can apply mathematical operations like union,intersection,difference etc on set
objects.
Ex. 
s={10,20,30}
s[0] : not work because insertion order is not preserved 
s[:] : not applicable 

### Dict
1. Duplicate keys are not allowed but values can be duplicated.
2. Hetrogeneous objects are allowed for both key and values.
3. insertion order is not preserved
4. Dictionaries are mutable
5. Dictionaries are dynamic
6. indexing and slicing concepts are not applicable
ex.
d={100:'vijay',a:'raj'}
print(d[100])
print(d[a])


