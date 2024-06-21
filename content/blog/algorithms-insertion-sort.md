+++
author = "Johnny"
title = "Algorithms - Insertion Sort"
date = "2024-06-20"
description = "Learning Go Through Algorithms"
tags = [
    "go",
    "algorithms"
]
+++

### Insertion Sort

Insertion sort is one algorithm to solve the problem of sorting a sequence of numbers in monotonically increasing order. The algorithm creates a sorted sequence of the array one element at a time by inserting each element into its correct sorted position relative to the other elements in the array which have already been sorted.

### Implementation in Go
```go
package main

import "fmt"

func main(){ 
	var a = [7]int{7, 1, 6, 3, 25, 10}

	for i := 1; i < len(a); i++ {
		var key int = a[i]
		var j = i - 1

		for j >= 0 && a[j] > key {
			a[j+1] = a[j]
			j = j - 1
		}

		a[j+1] = key
		
	}

	fmt.Println(a)
}

Output: [0 1 3 6 7 10 25]
```