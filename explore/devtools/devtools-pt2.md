![image1](/explore/devtools/result-calculateSum.png)
![image2](/explore/devtools/result-dataType.png)

1. The bug in the code was in the `calculateSum` function. The function was adding the two parameters as strings instead of numbers so the function was concatenating the two parameters instead of adding them. 
2. I fixed the bug by using the parseInt() function to convert the parameters to numbers. 
![image3](/explore/devtools/fix.png)