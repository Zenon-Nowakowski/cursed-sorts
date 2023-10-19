# Purpose 
This is a compilation of a series of aweful sorting algorithms I made for fun they should never be used in any serious context.'
# Algorithms on display: 
These algorithms are mostly taken from the [video](https://youtu.be/ktgxMtWMflU)
## Stalinsort 
Stalin sort sends all values which are out of order out of the list and returns a sorted list of values, with some data being removed in the process however the time complexity will always be linear 
## naptime
Naptime sets a set of threads equal to the lenght of the list to sleep for an equal amount of time as the value of the node, they all then wake up at set intervals, sorting by whichever nodes wake up first. 
## Slow sort 
A recurseive algorithm similar to merge sort however during the sub-sorting step it only take out the highest value last element, then it repeats 
## Bogo sort 
randomly sorts the list until its sorted 
### Bozo sort 
randomly selects 2 elements and swaps them, then checks if list is sorted, keeps doing this until its sorted 
### bogobogo sort 
Just like bogo but introduces sub lists. These sublists are resorted every time and are calculated by added in the next value of the array into the sublists and bogo sorts it. Then if the sublist is incorrect, it *deletes it* and attempts to bogo sort from the beganning. 
### Quantum bogo sort: 
Bogo sort but async'd, a bunch of 'universes' sort the data, and once one universe figures it out that is the return and all others are destroyed. 
# Sources: 
https://youtu.be/ktgxMtWMflU