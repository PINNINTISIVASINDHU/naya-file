# linked list : https://www.geeksforgeeks.org/top-20-linked-list-interview-question/

## Finding middle element in a linked list 

* class Solution
*{
*int getMiddle(Node head)
*{

*Node temp = head;
*int count =0 ;
*while(temp!=null){
*count += 1;
*temp = temp.next;}
*temp = head;
*int i=0;
*while(i<count/2){
*temp = temp.next;
*i++;
*}
*return temp.data;
*}
*}
