# Deque Implementation using `collections.deque` in Python

## Aim
To demonstrate the use of `collections.deque` for implementing a double-ended queue (deque) and performing right-end insertions.

## Procedure
1. Import `deque` from the `collections` module.
2. Create an empty deque.
3. Take 3 user inputs and append them to the deque.
4. Append three more fixed elements ('h', 'o', 'n') to the right end of the deque.
5. Print the final state of the deque.

## Program

```python
from collections import deque

# Create empty deque
dq = deque()

# Append 3 user inputs
for i in range(3):
    iop = input()
    dq.append(iop)

# Append additional elements
dq.append('h')
dq.append('o')
dq.append('n')

# Output the final deque
print("The deque after appending at right is :")
print(dq)
```

## output
![Screenshot 2025-04-20 213554](https://github.com/user-attachments/assets/9d5a6599-3dee-4beb-836e-49409718e8bb)

## Result
The program successfully demonstrates right-end insertions in a deque using collections.deque.
