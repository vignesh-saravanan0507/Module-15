# Ex. No: 15E - Build and Evaluate an Expression Tree

## AIM:
To write a Python program to build and evaluate the given Expression tree.

---

## ALGORITHM:

1. **Start the program.**
2. Create nodes for operators and operands.
3. Build the expression tree by connecting nodes in the correct hierarchical structure.
4. Define a recursive function `evaluate(root)`:
   - If the node is a number (leaf), return it.
   - Else, recursively evaluate left and right subtrees.
   - Apply the operator at the current node to the results.
5. Return the final result from the root node.
6. **End the program.**

---


## PROGRAM:

```python

from binarytree import build
x=['*','+','-',9,3,8,4]
t=build(x)
print(t.inorder)
print(t.postorder)

```

## OUTPUT:

<img width="848" height="117" alt="image" src="https://github.com/user-attachments/assets/99b8da23-79d5-4ecf-a84a-10e4caef6030" />

## RESULT:

Thus, the python code is written and executed successfully.
