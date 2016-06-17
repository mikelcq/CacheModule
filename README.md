# CacheModule
A small effective cache module managing general data objects in C/C++.


You can add this to C/C++ code.  Cache element could be a structure or a
method-free class.  There's no linked list but a caller-decide-size memory block in
RAM to store.

The main goal is to realize object allocation at one time and to save
effort of memory allocation/recycle from system lib, providing instant fetching and putting back. 

