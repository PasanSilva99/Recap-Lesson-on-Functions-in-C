# Create a Psuedo code for adding 2 numbers

```
Begin
  Enter the two numbers
  numbers to assing two variables(num1,num2)
  create the another variable total
  asing the total = num1+num2;
  print the total variable.
End.
```
# Recap Lesson on Functions

## Types of Functions

1. `No Return Type` `No Parameters`
   ```c
    void Addition(){
      int Number1 = 10;
      int Number2 = 14;
      int Total = Number1 + Number2;
      printf("Total : %d", Total);
    }
   ```
3. `With Return Type` `No Parameters`
   ```c
    int Addition(){
      int Number1 = 10;
      int Number2 = 14;
      int Total = Number1 + Number2;
      return Total;
    }
   ```
5. `No Return Type` `With Parameters`
   ```c
    void Addition(int Number1, int Number2){
      int Total = Number1 + Number2;
      printf("Total : %d", Total);
    }
   ```
7. `With Return Type` `With Parameters`
   ```c
    int Addition(int Number1, int Number2){
      int Total = Number1 + Number2;
      return Total;
    }
   ```
   or
   ```c
    int Addition(int Number1, int Number2){
      return Number1 + Number2;
    }
   ```
# Practice Questions

## Observe the following functions
```c
int Addition(int num1, int num2){
  int total ;
  total=num1 + num2;
  return total;
}

void Display(int x){
  printf("%d",x);
}

void DisplayWithString(char abc[], int x){
  printf("%s : %d", abc, x);
}
```
> 1. Using only the given functions Construct a program that will add 2 numbers. Use only the `main` function and use of `printf()` is not allowed.

### Answer 
<details>
  <summary> Show Answer</summary>
  
  ```c
  int main(void){
    DisplayWithString("Total is: %d", Addition(12, 12);
    return 0;
  }
  ```
</details>

> 2. Create a Function that will get a number as a user input using `scanf` and return it.
   
### Answer 
<details>
  <summary> Show Answer</summary>
  
  ```c
  int GetInt(void){
    int num;
    printf("\nEnter a Number: ");
    scanf("%d", &num);
    return num;
  }
  ```
</details>

> 3. No using the get in function and above functions, Get 2 numbers from the user and show the total by adding them together. You can only edit the `main` function and use of `scanf` and `printf` inside the main function is not allowed.

### Answer 
<details>
  <summary> Show Answer</summary>
  
  ```c
  int main(void){
    DisplayWithString("Total is", Addition(GetInt(), GetInt()));
    return 0;
  }
  ```
</details>

---
