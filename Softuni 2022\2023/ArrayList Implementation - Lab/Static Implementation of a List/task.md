Create a new console C# project in Visual Studio named ImplementArrayList, rename class Program.cs to
StartUp.cs and add new public class CustomArrayList.cs.
Implement a resizable list in C#. Use the following structure for the class:
In the provided structure we have:
 An array of object type in which we will store the list elements.
 Property Count, which will keep track of how many elements are in the array at the moment.
 A constructor that initializes our array‐based list with initial capacity (which is 4 elements by default)
Since the Add(item) method is similar to the Insert(index, item) method, we will write code where the
Add(...) method calls the Insert(...) method. If the array is full, it will allocate twice as much space and copy the
elements from the old to the new array. This can be done in the method Resize().

1. Method Insert(index, item)
Let’s implement the Insert(index, item). It will insert an element into the array at given position.
Hints:
This is how we can insert an element to given position:
 First we check the capacity and resize the underlying array if the capacity is not enough.
 Then we move the elements [index+1...end] on the right.
 Finally, we save the new element at position index.
This is how our code may look like:
This is how we can resize the array to increase its capacity twice:

2. Method Add(item)
Adds an element by calling the Insert method and uses the number of elements for the index.
 Just invoke the Insert() method.

3. Method IndexOf(item)
Searches for an item and returns its index or ‐1 if no item is found.
Hints
You will need the Equals method to compare two items.

4. Method Clear()
Deletes the elements in the array and returns it to its initial capacity and count.

5. Method Contains(item)
Checks if the item exists in the list and returns true / false.
Hints:
You can use a method that you have already written.

6. Indexer: this[int index]
Used to access the items by their index. Before setting or getting an index of the property, it is necessary to check
whether the index is within the array. In case an invalid index is submitted, throw new
ArgumentOutOfRangeException with message: "Invalid index: " + index.
Hints:

7. Method Remove(int index)
Removes an element located on a given index and returns that element. For this purpose, we will first find the
required element, remove it, and then move the elements after it so that there is no space in the corresponding
position. This rearrangement can be performed in the Shift method. In case the count of the elements in the array is
less than 1⁄2 of its current size, perform the Shrink method, which reduces the size of the array by half, deleting part
of the empty cells.
It is necessary to check whether the index is within the array. In case an invalid index is submitted, throw new
ArgumentOutOfRangeException with message: "Invalid index: " + index.

8. Method Remove(object item)
Removes an element and returns the index on which that element is located.

9. Test Your Code
Test the program in the Main() method of the class StartUp.cs.
Using an array of object type allows us to store different data of object type. For example, in this case we can store
the int 7 and the string Tomato.
