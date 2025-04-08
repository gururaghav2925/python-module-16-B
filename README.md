#  Construct and Balance an AVL Tree

## Aim
To construct an AVL Tree using the elements:
Print the tree **before** and **after** balancing using appropriate Python packages and functions.

## Procedure
1. Insert elements into a standard (unbalanced) binary search tree.
2. Use AVL rotations (LL, RR, LR, RL) to balance the tree.
3. Define traversal functions to print tree nodes.
4. Display nodes before and after balancing.

## Python Program
```python
from TreeAVL.AVL import AVL

def getDictTree(self):
 return self.dict_tree

def Construct_AVL(L):
  tree = AVL(L)
  print("AVL Tree Before Balancing\n",getDictTree(tree))
  tree.BalanceTree()
  print("AVL Tree After Balancing\n",getDictTree(tree))
L=[11,8,18,5,13,17,4,7,2]

```
# Output:
![image](https://github.com/user-attachments/assets/cd184680-75da-467a-9b59-90622933dea5)

# Result:
The program builds the binary search tree using the given elements and balances it using AVL rotations.  
Both **inorder traversals** before and after balancing remain the same, confirming that the tree structure respects the binary search property, and balancing ensures minimal height.
