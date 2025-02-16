# AVL-AlgoX 🌳

📌 AVL-AlgoX is an implementation of an AVL tree, a self-balancing binary search tree where the difference between heights of left and right subtrees cannot be more than    one for all nodes. This program allows insertion, deletion, and searching of nodes while ensuring the tree remains balanced through rotations.

## 🚀 Features

➕ **Insertion** : Inserts nodes into the AVL tree while maintaining balance.  

➖ **Deletion** : Removes nodes and rebalances the tree.  

🔎 **Searching** : Searches for a node in the tree.  

🛤 **Traversals** : Supports Pre-Order, In-Order, and Post-Order traversals.  

🔄 **Balancing** : Implements Left Rotation, Right Rotation, Left-Right Rotation, and Right-Left Rotation.  

## Usage

1️⃣ Enter the number of nodes to insert.  
2️⃣ Input values for each node.  
3️⃣ View the tree traversal outputs.  
4️⃣ Search for a node by entering its key.  
5️⃣ Delete a node and observe the updated tree structure.  

## 🔧 Function Descriptions

📌 **getNode()**: 🏗️ Creates a new node with a given key.  

📏 **height(node*)**: 📊 Computes the height of a given node.  

⚖️ **balance_factor(node*)**: 🔢 Calculates the balance factor of a node.  

🔄 **Rotations (Right, Left, Left-Right, Right-Left)**: ♻️ Balances the tree after insertion and deletion.  

➕ **Insert_node(node*)**: 🌱 Inserts a node while maintaining AVL balance.  

➖ **delete_node(node*)**: ❌ Deletes a node and rebalances the tree.  

🔎 **search_node(node*, int)**: 🕵️ Searches for a node with a given key.  

🛤 **PreOrder(), InOrder(), PostOrder()**: 📜 Traverses the tree in different orders.  

## Requirements:
- GCC Compiler (for Linux/Windows)
- Basic knowledge of C programming

## Steps to Compile and Run:

1. Open a terminal or command prompt.
   
2. Navigate to the directory containing `AVL-AlgoX.c`.
   
3. Compile the program using:
   ```sh
   gcc AVL-AlgoX.c -o AVL-AlgoX
   ```
   
4. Run the compiled program:
   ```sh
   ./AVL-AlgoX
   ```

## Example Run

```
Enter the number of nodes: 5
Enter the info for node: 10
Enter the info for node: 20
Enter the info for node: 30
Enter the info for node: 40
Enter the info for node: 50

Binary Search Tree traversal...
Pre-Order traversal...
30 20 10 40 50
Post-Order traversal...
10 20 50 40 30
In-Order traversal...
10 20 30 40 50

Enter the node to search: 30
Node found!

Enter the info to delete: 20

Binary Search Tree traversal after deletion...
Pre-Order traversal...
30 10 40 50
```

### 👨‍💻 Happy Coding & Tree Balancing! 🌲
