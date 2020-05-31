First interview - Warmup: The interviewer asked me a series  of short questions. The running time (best, worst, average) of various sorting algorithms such as merge sort, quick sort and heapsort. He also asked me about hash table and hash functions (average and worst case complexity of insertion, deletion and lookup). Central Question: Consider a setup where a program is continuously receiving floats as inputs (a stream of numbers). The task is to write a method that at any given time returns a moving average. That is the average of the last k numbers received. If the method is called before the program has received k numbers, simply return the average of however many numbers have been received thus far. The solution should obviously be optimal. Second interview - Warmup: Given an array of integers, write a method that places all the zeros at the end. Main question: Consider an interface which has the following two methods: interface Counter {  void inc();  int getLastMinuteCount(); } The method inc() is supposed to help keep track of the number of requests that clients make to a server (or something else along those lines). The getLastMinuteCount() is supposed to return the number of requests that the server has received in the last minute. The question is to implement a class that has these two methods included.