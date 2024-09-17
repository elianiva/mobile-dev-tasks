# Practicum 1: Applying If-Else Statement

## Step 1

![image](https://github.com/user-attachments/assets/1eb7da74-3ba5-4de1-b713-2dbf372aa822)

## Step 2

There are a lot of errors in the code, hence we need to fix it as such:

![image](https://github.com/user-attachments/assets/fe0d21b7-45bf-4c44-bb06-712d713b5866)

The errors mostly came from incorrectly written `If` and `Else` keyword

## Step 3

![image](https://github.com/user-attachments/assets/ea69dbe7-953b-4cbc-8d89-50705c953990)


# Practicum 2: Applying `While` and `Do-While`

## Step 1

![image](https://github.com/user-attachments/assets/ae19374d-5f7a-458e-9902-864e7ecee0c9)

## Step 3

![image](https://github.com/user-attachments/assets/d3e84371-1460-4f86-93e9-8ba772ea4b38)

# Practicum 3: Applying `For` and `Break-Continue`

## Step 1

![image](https://github.com/user-attachments/assets/0422c7f0-a13f-422b-8521-4aba6f50e098)

1. `Index` should be written as `index` since it's not a class
2. `var` should be added in front of `index` since it hasn't been declared yet

## Step 3

![image](https://github.com/user-attachments/assets/c9dd81ab-352a-4801-9bd7-8bd8b8d06e3a)

It doesn't output anything since we're not passing through any of the `if` statements


# Prime Number Algorithm using Dart

```dart
void main() {
  int start = 10;
  int end = 201;

  // Create a list to mark non-prime numbers
  List<bool> isPrime = List<bool>.filled(end + 1, true);

  // 0 and 1 are not prime numbers
  isPrime[0] = isPrime[1] = false;

  // Sieve of Eratosthenes
  for (int i = 2; i * i <= end; i++) {
    if (isPrime[i]) {
      for (int j = i * i; j <= end; j += i) {
        isPrime[j] = false;
      }
    }
  }

  // Print prime numbers in the range 10 to 201
  print("Prime numbers between $start and $end:");
  for (int i = start; i <= end; i++) {
    if (isPrime[i]) {
      print(i);
    }
  }
}
```

