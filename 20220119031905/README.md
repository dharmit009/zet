# Python functions cannot be stored as values in Dictionaries.

One of the most annoying things about Python is it does not support 
`switch` case statement. The closest alternative to `switch` case statement
in Python is a `dictionary`. A `dictionary` stores items in pairs as 
key and values. 

One of the problems with dictionaries is that you cannot store functions as 
values to any key. 

Here is a sample code:

```
select_op = {
		"1": openacc(),
		"2": deposit(),
		"3": withdraw(),
		"4": displayInfo(),
}

```
