# SimpleRouting

## Problem Formulation
 Design a program to find the shortest path on a 2D grid (M by N) from a
 starting point (source) to an endpoint (sink) while avoiding all obstacles (blocks)


## Program Requirements
Your program should be executed by:
```
$./SimpleRouter <input_file> <output_file>
```

Upon execution, the program should generate an <output_file> containing all the required routing information.

For example:
```
$./SimpleRouter testcase1.txt testcase1_out.txt
```

## Checker
The Checker program validates the output file against a reference input:
Validation Criteria
1. Output Format Correct:
* Ensures the output file follows the specified syntax and structure.
2. Path Legality:
* No segment of the path crosses any block.
* All path segments lie within the grid.
* No diagonal moves are present.
3. Source and Sink:
* The output file correctly identifies the source and sink points as defined in the input.
4. Bends:
* The bend points are valid and necessary.
* No redundant bends exist.
5. Path Length:
* The total length of the path matches the sum of all segments.

## Checker Usage
The Checker program can be executed with the following command:
```
$./Checker <input_file> <output_file>
```

For example:
```
$./Checker testcase1.txt testcase1_out.txt
```
