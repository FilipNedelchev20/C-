Create a new project named ImplementLinkedList, rename class Program.cs to StartUp.cs and add new
public class LinkedList.cs.
Create a dynamic list implementation. Use the following structure for the class:
For the dynamic implementation of the linked list we will need two classes:
 The class Node ‐ it holds a single element of the list and a reference (pointer) to the next element which is
of the same class Node. The class is inner to the class LinkedList (it is declared as a private member) and is
therefore accessible only to it.
 The main list class LinkedList which will hold a sequence of elements as well as the head and the tail of the
list. Upon the initial construction the list is empty and for this reason we assign head = tail = null and count =
0.
We have created constructors that we need to fill in.
In our LinkedList we have 3 fields:
 head – pointer to the first element
 tail – pointer to the last element
 count – counter of the elements

1. Method Add(object item)
Two cases are considered: an empty list and a non‐empty list. In both cases we append the element at the end of
the list (where tail points) and after the operation all fields (head, tail and count) have correct values.
Hints:
If we have an empty list ‐> create a new head and tail.
If we have a non‐empty list ‐> append the item after tail.
Increase Count.

2. Method Remove(int index)
Check if the given index is valid, and if it's not, throw new ArgumentOutOfRangeException with message:
"Invalid index: " + index. Search for the element for removal by moving forward from the beginning of the
list to the next element exactly index times. Once the removal element is found (currentNode), it is removed by
considering the following 3 possible cases:
 The list remains empty after the removal ‐> we remove the whole list along with its head and tail (head =
null, tail = null, count = 0).
 The element for removal is at the start of the list (there is no previous element) ‐> we make head to point at
the element immediately after the removed element (or at null, if the removed element was the last one).
 The element is in the middle or at the end of the list ‐> we direct the element before it to point to the
element after it (or at null, if there is no next element).
Hints

3. Method Remove(object item)
Deleting by element value works like deleting by index, but there is a peculiarity: the searched element may not
exist, then the code must return a value ‐1.
For the method, it is necessary for the elements in the array to be comparable, to have a correctly implemented
method Equals().
Hints

4. Method IndexOf(object item)
The searching for an element works like in the method for removing: we start from the beginning of the list and
check sequentially the next elements one after another, until we reach the end of the list or find the searched
element. If no item is found, the code must return a value ‐1.
Hints

5. Method Contains(object item)
Checks to see if an element is in the list and returns true / false.
Hints

6. Indexer this[int index]
The indexer works pretty straightforward ‐ first checks the validity of the specified index and then starts from the
head of the list goes to the next node index times. Once the node containing the element the specified index is
found, it is accessed directly. In case an invalid index is submitted, throw new ArgumentOutOfRangeException with
message: "Invalid index: " + index.
Hints

7. Test Your Code
Test the program in the Main method of the class StartUp.cs.
