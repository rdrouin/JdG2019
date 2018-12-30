# JdG2019
## Competition Académique Info - Numero 3

Find the path through the mountain. The file `mountain.txt` countains a 10x10x3 test file of a smaller mountain.

You can walk on `0`
You can't walk on `1`
You can climb up on `10`
You can climb down on `11`
You can climb both side on `12`
Start point `100`
End point `101`

A first line will indicate the dimension. The first floor will follow on a single line. The line is every row of the maze on after the other on the same floor.

```
100 0 0 0 0
0 1 0 0 1
1 1 1 0 1
10 1 0 0 0
0 0 0 0 0
```

is represented as
`100 0 0 0 0 0 1 0 0 1 1 1 1 0 1 10 1 0 0 0 0 0 0 0 0`

Actions must be printed in a file with the following format.

* Actions separated by commas
* Actions are either following:
	* North: 1
	* West: 2
	* South: 3
	* East: 4
	* Climb up: 5
	* Climb down: 6

### Required to launch
* TODO

### Explanation
* TODO