# Data-Structures-Algorithms


## Segement Tree 
   1. Leaf Nodes are the elements of the input array 
   2. Each internal node represents some merging of the leaf nodes. The merging may be different for different problems. 
   3. An array representation of tree is used to represent Segment Trees. For each node at index i, the left child is at index 2*i+1, right child at 2*i+2 and the parent is at st1.
   4. In each step, the segment is divided into half and the two children represent those two halves. So the height of the segment tree will be log2N. 
   5. There are N leaves representing the N elements of the array. The number of internal nodes is N-1, so the total number of nodes are 2*N-1.
   
         ### Implementation 
         
          
