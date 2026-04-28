# 🚀 clsString Library: Professional String Manipulation in C++

The `clsString` library is a comprehensive C++ class designed to simplify and supercharge string manipulation. It provides a wide range of functions that are not directly available in the standard `std::string` library, making your code cleaner, faster, and more organized. ✨

## 🌟 Key Benefits
- **Time-Saving**: No need to rewrite complex algorithms for splitting or trimming strings. ⏱️
- **Hybrid Support**: Use it statically via `clsString::FunctionName` or through object instances. 🛠️
- **Property Support**: Includes Microsoft C++ `__declspec(property)` for an elegant way to get/set values. 💎

## 📚 Core Functions

The library is packed with essential tools for every developer:

### 1. 🔠 Case Management
- `UpperAllString`: Converts the entire string to UPPERCASE.
- `LowerAllString`: Converts the entire string to lowercase.
- `UpperFirstLetterOfEachWord`: Capitalizes the first letter of every word.
- `InvertAllLettersCase`: Swaps case (A -> a, b -> B).

### 2. 🔢 Counting & Statistics
- `CountWords`: Efficiently counts the number of words. 📝
- `CountLetters`: Counts specific types of letters (Small, Capital, or All).
- `CountVowels`: Returns the number of vowels (a, e, i, o, u). 🗣️
- `CountSpecificLetter`: Counts how many times a certain character appears.

### 3. ✂️ Trimming & Editing
- `Trim`, `TrimLeft`, `TrimRight`: Removes extra whitespace from ends.
- `Split`: Breaks a string into a `vector` of words based on a delimiter. 🖇️
- `JoinString`: Merges a vector or array of strings into one.
- `ReplaceWord`: Swaps a specific word with another one. 🔄
- `RemovePunctuations`: Cleans the string from symbols like (!, ?, ., etc.).

### 4. 🧠 Advanced Processing
- `ReverseWordsInString`: Flips the order of words in a sentence.
- `IsVowel`: Checks if a specific character is a vowel.

---

## 🛠️ How to Integrate into Your Project

You can easily add this library to your C++ project by following these steps:

1. **Create the File**: Create a new file in your project named `clsString.h`. 📄
2. **Paste the Code**: Copy the library code and paste it inside this header file.
3. **Organize**: Place `clsString.h` inside your **Header Files** folder to keep your project structure professional. 📁
4. **Include It**: In your `main.cpp` or any source file, add the following line at the top:

```cpp
#include "clsString.h"