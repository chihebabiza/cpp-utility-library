# clsUtil Library

## Overview

The `clsUtil` library provides a set of utility functions for generating random numbers, characters, words, and keys, as well as array operations, swapping values, text encryption/decryption, and text formatting. This library is designed to simplify common programming tasks in C++.

## Features

- Random number generation
- Random character, word, and key generation
- Array operations (filling with random values, shuffling, swapping)
- Basic encryption and decryption
- String formatting utilities

## Installation

Include `clsUtil.h` in your project and ensure that it is in the correct include path.

```cpp
#include "clsUtil.h"
```

## Usage

### Random Number Generation

```cpp
int randomNum = clsUtil::RandomNumber(1, 100);
```

### Character Generation

```cpp
char randomChar = clsUtil::GetRandomCharacter(clsUtil::CapitalLetter);
```

### Generate Random Word

```cpp
string word = clsUtil::GenerateWord(clsUtil::MixChars, 8);
```

### Generate Random Key

```cpp
string key = clsUtil::GenerateKey();
```

### Fill an Array with Random Numbers

```cpp
int arr[100];
clsUtil::FillArrayWithRandomNumbers(arr, 10, 1, 100);
```

### Fill an Array with Random Words

```cpp
string words[100];
clsUtil::FillArrayWithRandomWords(words, 10, clsUtil::CapitalLetter, 5);
```

### Shuffle an Array

```cpp
clsUtil::ShuffleArray(arr, 10);
clsUtil::ShuffleArray(words, 10);
```

### Swapping Values

```cpp
int a = 10, b = 20;
clsUtil::Swap(a, b);
```

### Encrypt & Decrypt Text

```cpp
string encrypted = clsUtil::EncryptText("Hello", 3);
string decrypted = clsUtil::DecryptText(encrypted, 3);
```

## License

This library is open-source. You are free to use and modify it.

## Author

Chiheb Abiza
