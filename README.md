# TWworks
Matlab code for generating mazes, it runs well at Matlab(Version:R2017b) for Windows.
***
**There** is an example in the prompt statement,that is:
<br>Please input the size and connectivity of the Road Grid.
<br>**Example:**
<br>3 3
<br>0,1 0,2;0,0 1,0;0,1 1,1;0,2 1,2;1,0 1,1;1,1 1,2;1,1 2,1;1,2 2,2;2,0 2,1
<br>**Rrsult:**

|[W]|[W]|[W]|[W]|[W]|[W]|[W]|
|:----:|:----:|:----:|:----:|:----:|:----:|:----:|
|**[W]**|**[R]**|**[W]**|**[R]**|**[R]**|**[R]**|**[W]**|
|**[W]**|**[R]**|**[W]**|**[R]**|**[W]**|**[R]**|**[W]**|
|**[W]**|**[R]**|**[R]**|**[R]**|**[R]**|**[R]**|**[W]**|
|**[W]**|**[W]**|**[W]**|**[R]**|**[W]**|**[R]**|**[W]**|
|**[W]**|**[R]**|**[R]**|**[R]**|**[W]**|**[R]**|**[W]**|
|**[W]**|**[W]**|**[W]**|**[W]**|**[W]**|**[W]**|**[W]**|
***
Just run main.m, then you  can get the result.
***
<br>**input_co.m** for recognition of input.
<br>**out_range.m** for determine whether the number is out of range.
<br>**format_inc.m** for determine whether the format is wrong.
<br>**format_num.m** for determine whether the number is invalid.
<br>**format_maze.m** for determine whether the maze is error.
***
July 30, 2018,
