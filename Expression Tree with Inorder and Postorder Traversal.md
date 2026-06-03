# Ex. No: 15C - Expression Tree with Inorder and Postorder Traversal

## AIM:
To write a Python program to build the given expression tree and print the inorder and postorder traversals.

---

## ALGORITHM:

1. **Start the program.**
2. Import the required modules (`build` and `Node` from `binarytree`).
3. Define a list `x` representing the expression tree in pre-order fashion (with `None` for missing nodes).
4. Use the `build()` function to generate the binary tree.
5. Print the **inorder** and **postorder** traversal of the tree.
6. **End the program.**

---

## PROGRAM:

```python
from binarytree import build
nodes=['A','B','C','D','E','F',None,'G']
root=build(nodes)
print("Binary tree:")
for i in (root.values):
    print(i,'-->',end="")
print("\nlevel order traversal:",root.levelorder)
print("\nInorder traversal:",root.inorder)
print("\nPreorder traversal:",root.preorder)
print("\nPostorder traversal:",root.postorder)
```

## OUTPUT

<img width="937" height="197" alt="image" src="https://github.com/user-attachments/assets/2cda059d-a7ba-4e92-b121-65748064b09a" />

## RESULT

Thus, the python code is written and executed successfully.
