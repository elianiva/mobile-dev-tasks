# Practicum 1

## Step 1

![image](https://github.com/user-attachments/assets/0d8eb719-3f57-4d44-9cde-38e6756b3ece)

## Step 2

It initialised a list and asserts its content before printing the items.

## Step 3

![image](https://github.com/user-attachments/assets/98069db9-748a-4b6c-be04-2b77f54423e0)

# Practicum 2

## Step 1

![image](https://github.com/user-attachments/assets/5d4d6e0a-c156-4ea1-b499-65d92b77c482)

## Step 2

It prints the data

## Step 3

![image](https://github.com/user-attachments/assets/c74bbe77-fbc7-4600-a024-7db3865f7951)

# Practicum 3

## Step 1

![image](https://github.com/user-attachments/assets/112f2d9d-dbf2-44eb-b484-4766d0818457)

## Step 2

It prints the data

## Step 3

![image](https://github.com/user-attachments/assets/c982440d-a943-4620-a147-d7e7738467de)

# Practicum 4

## Step 1

![image](https://github.com/user-attachments/assets/09a5de71-f7a4-470e-93b2-046a8a5b13bb)

## Step 2

It initialise a list and prints it out

## Step 3

![image](https://github.com/user-attachments/assets/3ef8f229-831e-4783-bbe3-5553c7f45768)

## Step 4

![image](https://github.com/user-attachments/assets/439f26db-71db-488a-8375-f87a41b877b2)

It will add "Outlet" if `promoActive` is true

## Step 5

![image](https://github.com/user-attachments/assets/f2766821-5c5a-4d63-a564-7886bdd11574)

It will add "Inventory" if `login` is equal to "Manager"

## Step 6

![image](https://github.com/user-attachments/assets/7eb978d6-1eb3-4607-8076-881d14eac16a)

It's used to generate items inside a list

# Practicum 5

## Step 1

![image](https://github.com/user-attachments/assets/ad4eec92-9bb7-491a-b5da-de40c1a6d3f9)

## Step 2

It prints a record

## Step 3

![image](https://github.com/user-attachments/assets/7a184363-4e9f-4c3b-aaca-d1327cadb0ce)

It swaps the record item's position

## Step 4

![image](https://github.com/user-attachments/assets/8bfa23b9-7c58-4f18-8ee7-096939365f28)

## Step 5

![image](https://github.com/user-attachments/assets/4ed79597-0cfe-4e33-b559-8c84838c5f07)

# Practicum Assignments

1. Done
2. `Functions` are a set of procedure or a block of code that can be reused, it receives argument and usually returns a value.
3. Different types of functions parameter:
```dart
// required param
void function(int a, int b) {}

// optional param
void function([int a, int b]) {}

// named param
void function({int a, int b}) {}

// default values
void function (int a = 1, int b = 2) {}
```
4. Function is a first class object meaning that every function is an object. It means that a function can be passed to another function just like any object.
Example:
```dart
void printElement(int el) {
  print(el);
}
list.map(printElement);
```
5. Anonymous function is a function that doesn't have a name, but we can assign it to a variable
```dart
// using normal syntax
() {}

// using fat arrow syntax
() => ...
```
6. Lexical scope means a function can access a variable outside of its scope. Lexical closure means we can use another function outside of the current scope.
7. We can return multiple value using record which is introduced in Dart 3.0
```dart
(int, int) swap(int a, int b) {
  return (b, a);
}
```
