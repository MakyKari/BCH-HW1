Sorting Algos Lib in Rust:

Usage:
Add dependency into your project
		```
		[dependencies]
		sorting_algos = { git = "https://github.com/MakyKari/BCH-HW1" }
  		```

open any Rust file and type
	```use sorting_algos::quick_sort::quick_sort;```
or use merging sort, selection sort or insertion sort

![image](https://github.com/MakyKari/BCH-HW1/assets/119777671/e6337de6-c8db-4912-bcc2-bf8921d19161)
![image2](image.png)

Example: 
    ```
    let mut arr = [10, 7, 8, 9, 1, 5];
    quick_sort(&mut arr, &|a, b| a < b);
    println!("Sorted array: {:?}", arr);
    ```