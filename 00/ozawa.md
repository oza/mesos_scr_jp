
## Agenda

* I will read how scheduler works
	* src/master/allocator/*
* Let's read the code togather

### sorter

* A base class which has virtual methods
* DRFSorter is only one implementation

* (suppliment) should I talk about how sorting and scheduling are related?

### DRFSorter

* Methods to be read
	* DRFComparator
	* DRFSorter::allocated
	* DRFSorter::sort
	* DRFSorter::activate

* allocator/sorter/drf/sorter.hpp


### Data structures shared between nodes

* include/mesos/v1/mesos.proto 

### allocator

* Source codes
	* allocator/mesos/hierarchical.cpp

* Methods to be read
	* HierarchicalAllocatorProcess::addFramework
