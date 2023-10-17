# Key Skills About List

* **Double Pointer**
    * Use double or multiple pointers to loop the list
      * Examples
        * 21 Merge Two Sorted Lists
            * 23. Merge k Sorted Lists
                * Similar operation to problem 21, for the list part
                * Use priority queue (based on binary heap) to sort the K numbers
        * 86 Partition List
            * Avoid pointer cycle
    * Use double or multiple pointers to get the location of a list, one fast, one slow
      * For the close-following pointer, can consider `x.Next.Next`
      * When the list node number is large, no necessary to insist 1 loop
      * if there is cycle in the list
      * Examples
        * 19 Remove Nth Node from End of List
        * 876 Middle of the Linked List
            * 2095 Delete the Middle Node of a Linked List
        * 142 Linked List Cycle II 
            * map or special idea
        * 160 Intersection of Two Linked Lists
            * 4 pointers. 2 faster, 2 slower
            * or use index


**Reference**
1. https://labuladong.github.io/algo/di-ling-zh-bfe1b/shuang-zhi-0f7cc/
