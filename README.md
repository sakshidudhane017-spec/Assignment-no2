# Assignment-no2
Assignment no 2
#Program to declare variables and display their types

integer_value = 10
float_value = 10.5
string_value = "Sakshi"
boolean_value = True

print("Integer value:", integer_value, "Type:", type(integer_value))
print("Float value:", float_value, "Type:", type(float_value))
print("String value:", string_value, "Type:", type(string_value))
print("Boolean value:", boolean_value, "Type:", type(boolean_value))

Output:
Integer value: 10 Type: <class 'int'>
Float value: 10.5 Type: <class 'float'>
String value: Sai Type: <class 'str'>
Boolean value: True Type: <class 'bool'>



# Program to demonstrate type casting

a = 10        # integer
b = 5.5       # float

print("Original value of a:", a, "Type:", type(a))
print("Original value of b:", b, "Type:", type(b))

# Type casting
a = float(a)
b = int(b)

print("After type casting a:", a, "Type:", type(a))
print("After type casting b:", b, "Type:", type(b))


Output:
Original value of a: 10 Type: <class 'int'>
Original value of b: 5.5 Type: <class 'float'>
After type casting a: 10.0 Type: <class 'float'>
After type casting b: 5 Type: <class 'int'>




# Program to demonstrate logical operators

a = True
b = False

print("Value of a:", a)
print("Value of b:", b)

print("a AND b:", a and b)
print("a OR b:", a or b)
print("NOT a:", not a)
print("NOT b:", not 
