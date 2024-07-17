# BST-Project-Cipher-CPP
This setup and code should help you understand how to organize a C++ project and implement a BST with the specified functions, including the traversal methods.

Explanation
Node Structure: Defined a structure for the nodes of the BST.
newNode: Creates a new node with a given value.
insert: Inserts a new value into the BST.
search: Searches for a value in the BST.
deleteNode: Deletes a node with a specified value from the BST. If the node to be deleted has two children, it finds the in-order successor (smallest value in the right subtree), copies its value to the node to be deleted, and then deletes the in-order successor.
inorder: Performs an inorder traversal of the BST.
preorder: Performs a preorder traversal of the BST.
postorder: Performs a postorder traversal of the BST.
main: The main function handles reading input, performing operations, and outputting results.
This code will read the input from input.txt, perform the specified operations, and print the results to output.txt. Make sure the input.txt file is in the same directory as the executable when you run the program.
