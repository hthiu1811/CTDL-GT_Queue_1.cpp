# CTDL-GT_Queue_1.cpp
Queue
Nguon tham khao : https://blog.luyencode.net/hang-doi-queue/
Cai dat : 

void Enqueue(char queue[], char element, int& rear, int arraySize) 
{
    if(rear == arraySize)            // Queue is full
        printf("OverFlow\n");
    else 
    {
        queue[rear] = element;    // Add the element to the back
        rear++;
    }
}
