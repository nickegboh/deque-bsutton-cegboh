Description and Implementation of the Deque algorithm and any optimizations included

# Introduction #

We will be designing and implementing the class Deque<T, A> to conform to std::deque<T, A>.

A deque is an attractive compromise between a vector and a list. Deques may be implemented by specific libraries in different ways, but in all cases they allow for the individual elements to be accessed through random access iterators, with storage always handled automatically (expanding and contracting as needed).

Our entire code will have conform to this standard, more or less our\_Deque <==> Deque.


# Program Details #

The program will have to implement basic operator functions like >, <, ==,++, ->, under sub classes like iterator class and more. Also for a basic functioning deque we utilized some of the basic function structure of class "Vector".

Deque utilizes a lot of functions like resize, swap, push, pop, front, back and many more which help the "Type" work mostly in ~O(1) time.