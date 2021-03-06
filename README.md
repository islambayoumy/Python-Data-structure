# Python-Data-Structure

### Prerequisites
- Python 3.x
- pytest, pytest-cov ~ use 'pip install' to install the previous modules


## Singly LinkedList

Implementation of Singly LinkedList with most common methods using **Python 3** & their unit-tests using **Pytest** framework.

To run the LinkedList class and play with it's methods:

```sh
$ cd Singly\ LinkedList/
$ python3 LinkedList.py
```

> Try whatever methods you want inside the 'test_func()'

To run the unit tests:

```sh
$ cd Singly\ LinkedList/
$ pytest --cov-report term-missing --cov=LinkedList
```
> Make sure you have 'pytest'
> If not, install it using
```sh
$ pip install pytest
```

## Doubly LinkedList

Implementation of Doubly LinkedList with most common methods using **Python 3** & their unit-tests using **Pytest** framework.

Run the same steps for Singly LinkedList above (change --cov=LinkedList to --cov=DoublyLinkedList).


## Circular LinkedList

Implementation of Circular LinkedList with most common methods using **Python 3** & their unit-tests using **Pytest** framework.

Run the same steps for Singly LinkedList above (change --cov=LinkedList to --cov=CircularLinkedList).

You can just extend the Singly LinkedList class and overwrite it's methods as it's just a special case of the Singly LinkedList

## Stack

Two different implementations of the stack with basic operations:
- Using lists [getting maximum would have complexity O(n)]
- Using linked lists [reteriving maximum with complexity O(1)] to track previous max value

Run the same steps for Singly LinkedList above (change --cov=LinkedList to --cov=Stack).

Implementation of 'Balanced Parentheses' method
