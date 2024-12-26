# Single Parameter Template Class Demo

A C++ program demonstrating a template class that can work with various data types using a single type parameter.

## Description

This program implements a template class `Test` that can store and display a value of any data type. It shows the versatility of class templates in C++ by demonstrating usage with different data types including numeric, character, and string types.

### Key Features
- Single parameter template class
- Support for multiple data types
- Simple constructor initialization
- Display functionality
- Versatile type handling

## Class Template Structure

```cpp
template <class T1>
class Test
{
    T1 a;
public:
    Test(T1 x);
    void show();
};
