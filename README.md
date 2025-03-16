Assignment-03-List-and-Tuples-method
Q: What is a List in Python?
A list is like a container where you can store multiple items (like numbers, words, or even other lists).
Q: What is append?
append is a way to add a new item to the end of a list.
Q: What is extend in Python?
The extend method is used to add all the elements of one list to the end of another list.
* Key Difference Between append and extend:
append adds a single element to the end of a list.
extend adds all the elements of another list to the end of a list.
Q: What is insert in Python?
The insert method is used to add an element at a specific position (index) in a list.
Q: How Indexing Works in Python
In Python, lists are zero-indexed, meaning the first element is at index 0, the second at index 1, and so on.
Q: What is remove in Python?
The remove method is used to delete the first occurrence of a specific value from a list.
* Key Points About remove:
It only removes the first occurrence of the value. If there are multiple occurrences, only the first one is removed.
If the value is not found in the list, Python will raise a ValueError.
Q: What is pop in Python?
The pop method is used to remove and return an element from a list. By default, it removes the last element of the list.
* Key Points About pop:
By default, pop() removes the last element of the list.
You can also specify an index to remove an element at a specific position.
Q: What is count in Python?
The count method is used to count how many times a specific value appears in a list.
* Key Points About count:
The count method checks how many times a specific value appears in a list.
If the value is not found in the list, it returns 0
Q: What is sort in Python?
The sort method is used to arrange the elements of a list in a specific order (ascending or descending). By default, it sorts the list in ascending order.
* Key Points About sort:
The sort method modifies the original list. If you want to keep the original list unchanged, use the sorted() function instead.
Q: What is reverse in Python?
The reverse method is used to reverse the order of elements in a list.
* Key Points About reverse:
The reverse method modifies the original list. If you want to keep the original list unchanged, you can use slicing to create a reversed copy.
Q: How to Copy a List in Python
There are two ways to copy a list:
Shallow Copy: Creates a new list but references the same objects as the original list.
Deep Copy: Creates a new list and new copies of the objects inside the list.
For simple lists (like the one in your question), a shallow copy is sufficient. You can create a shallow copy using:
The copy() method.
Slicing ([:]).
* Key Points About Copying Lists:
If you use the = operator, both variables will reference the same list.
Q: What is clear in Python?
The clear method is used to remove all elements from a list, making it empty.
* Key Points About clear:
The clear method modifies the original list and makes it empty.
If you want to create a new empty list without modifying the original, you can simply reassign the variables.
Q: What is a Tuple in Python?
A tuple is similar to a list, but it is immutable, meaning its elements cannot be changed after creation. Tuples are defined using parentheses ().
Q: What is Tuple Unpacking?
Tuple unpacking allows you to assign the elements of a tuple to separate variables in a single statement.
* Key Points About Tuple Unpacking:
The number of variables on the left-hand side must match the number of elements in the tuple.
Q: How to Sort Without Using sort()?
To sort a list without using the built-in sort() method, we can use an algorithm like Bubble Sort, Selection Sort, or any other sorting algorithm. Here, I'll use the Selection Sort algorithm because it's simple and easy to understand.
Q: What is Selection Sort?
Selection Sort works by repeatedly finding the largest (or smallest) element in the unsorted part of the list and swapping it with the first unsorted element. This process continues until the entire list is sorted.
