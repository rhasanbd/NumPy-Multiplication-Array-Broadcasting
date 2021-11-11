# NumPy-Multiplication-Array-Broadcasting

This notebook series presents two useful linear algebra operations by NumPy.


          Notebook 1: Multiplication between N-dimensional Arrays


We describe the techniques for multiplying N-dimensional arrays (ndarray) using NumPy. Specifically, we describe the following types of multiplications.

- Element-wise multiplication (Hadamard product): * and np.multiply
- Dot product: np.dot
- Matrix multiplication: np.matmul and @

We provide a guideline to select a suitable multiplication technique.


        Notebook 2: Array Broadcasting


We describe the array broadcasting technique. NumPy provides a mechanism for performing mathematical operations on arrays of unequal shapes. This mechanism is known as array broadcasting or broadcasting.


The term broadcasting describes how numpy treats arrays with different shapes during arithmetic operations. Subject to certain constraints, the smaller array is “broadcast” across the larger array so that they have compatible shapes. 

Broadcasting provides a means of vectorizing array operations so that looping occurs in C instead of Python. It does this without making needless copies of data and usually leads to efficient algorithm implementations. 
