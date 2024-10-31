## The Problem

> fundamental problem of linear algebra : solve a system of linear equations

- **start with a case when we have n linear equations, n unknowns (normal, nice case)**

## The Matrix

#### example 1

![example 1](https://github.com/user-attachments/assets/79ae3e84-353e-415f-b80d-91f2e0749526)

- Coefficient Matrix
  - **A** is Coefficient Matrix
  
![equation](https://github.com/user-attachments/assets/605016cd-5b1f-42b5-b1a7-419aa9b1efab)


1. Row picture : the picture of one equation at a time
   
   ![Screenshot from 2024-10-31 04-34-37](https://github.com/user-attachments/assets/b4c56041-5465-4b47-a467-fd9c0f1d3f92)

2. **Column picture** : the picture of one column at a time
   - finding right **linear combination**(multiply some number and add...) of columns
     
   ![equation(4)](https://github.com/user-attachments/assets/f3888b83-f472-462f-a9e8-e532353dec46)

   ![Screenshot from 2024-10-31 10-54-01](https://github.com/user-attachments/assets/28744648-3f3f-4dec-b616-1d152d9539e9)

   - 관련영상 : [Linear transformations and matrices | 3Blue1Brown ](https://www.youtube.com/watch?v=kYB8IZa5AuE&list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab&index=3)

#### example 2

![example 2](https://github.com/user-attachments/assets/6f7e97fa-3eab-4ae1-9731-10b22788fefb)

![equation(7)](https://github.com/user-attachments/assets/4dfcc68c-dbfa-4670-9ee8-1fcca685a31f)

1. row picture

    - row picture consists of three planes and if everything works right, three planes meet in one point and thats's a solution
   
2. column picture

   - find right linear combination to make b($x = 0, y = 0, z = 1$)
     
   ![equation(8)](https://github.com/user-attachments/assets/580c4c76-87e6-495f-823a-a2c26a06f70e)

   ![Screenshot from 2024-10-31 11-23-11](https://github.com/user-attachments/assets/aa48ff04-cf4a-4374-9a34-f8bb7345a4f4)
> think about all bs(all right-hand sides)
- Can I solve $Ax=b$ for every $b$?
  - = Do the linear combinations of the columns fill 3-D space?
  - **For this A, answer is YES**
    
## When could it go wrong?

> If these three columns all lie in the same plane, then there combinations will lie in that same plane

## Matrix form

- Matrix form(the algebra way to look at problem) : using matrix
  
    - $Ax = b$
    - How do you multiply a matrix by a vector?
        1. column way: **$Ax$ is a the comb of columns of $A$** 
        3. row way: the idea of dot product
