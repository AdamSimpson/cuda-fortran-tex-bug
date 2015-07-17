This example sets values of a device array to 15.4275d0, associates a texture pointer to the device array, and then launches a kernel to copy the values from texture memory to the original array.
```
$ pgfortran cudaf_tex.cuf
$ ./a.out
 
 global values:     15.42750000000000         15.42750000000000      
    15.42750000000000         15.42750000000000         15.42750000000000      
    15.42750000000000         15.42750000000000         15.42750000000000      
    15.42750000000000        5.5144973327215701E-315
 texture values:     15.42749786376953         15.42749786376953      
    15.42749786376953         15.42749786376953         15.42749786376953      
    15.42749786376953         15.42749786376953         15.42749786376953      
    15.42749786376953         0.000000000000000     
```
