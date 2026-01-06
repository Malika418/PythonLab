Loom Video for Pyhton: https://www.loom.com/share/02b3e48c22af4aa18643fd58c095f25d
# Activity: Assign Python Variables

## Introduction

Variables help security analysts keep track of a variety of security-related information. For example, analysts may need to create Python variables for users who are allowed to log in, the number of login attempts permitted, and the current number of attempts a user has made.

In this lab, you practice assigning values to variables and determining their data types.

---

## Scenario

You are a security analyst responsible for writing code to automate analysis of login attempts made to a specific device. As the first step, you create variables to keep track of information relevant to the login process, including:

* Device ID
* Approved usernames
* Maximum login attempts allowed
* Current login attempts
* Login status

---

## Task 1: Assign a Device ID

Assign the device ID `"72e08x0"` to a variable named `device_id` and display its value.

```python
device_id = "72e08x0"
print(device_id)
```

**Output:**

```
72e08x0
```

---

## Task 2: Determine the Data Type of `device_id`

Find the data type of `device_id`, store it in `device_id_type`, and display it.

```python
device_id_type = type(device_id)
print(device_id_type)
```

**Output:**

```
<class 'str'>
```

---

## Task 3: Create a List of Approved Usernames

Create a list of approved usernames and assign it to `username_list`.

```python
username_list = ["madebowa", "jnguyen", "tbecker", "nhersh", "redwards"]
print(username_list)
```

**Output:**

```
['madebowa', 'jnguyen', 'tbecker', 'nhersh', 'redwards']
```

---

## Task 4: Determine the Data Type of `username_list`

Store and display the data type of `username_list`.

```python
username_list_type = type(username_list)
print(username_list_type)
```

**Output:**

```
<class 'list'>
```

---

## Task 5: Update the Username List

Reassign `username_list` to include a new user and display the list before and after the update.

```python
username_list = ["madebowa", "jnguyen", "tbecker", "nhersh", "redwards"]
print(username_list)

username_list = ["madebowa", "jnguyen", "tbecker", "nhersh", "redwards", "lpope"]
print(username_list)
```

**Output:**

```
['madebowa', 'jnguyen', 'tbecker', 'nhersh', 'redwards']
['madebowa', 'jnguyen', 'tbecker', 'nhersh', 'redwards', 'lpope']
```

---

## Task 6: Define Maximum Login Attempts

Assign the value `3` to `max_logins`, determine its data type, and display it.

```python
max_logins = 3
max_logins_type = type(max_logins)
print(max_logins_type)
```

**Output:**

```
<class 'int'>
```

---

## Task 7: Track Current Login Attempts

Assign the value `2` to `login_attempts`, determine its data type, and display it.

```python
login_attempts = 2
login_attempts_type = type(login_attempts)
print(login_attempts_type)
```

**Output:**

```
<class 'int'>
```

---

## Task 8: Compare Login Attempts

Determine whether the current number of login attempts is less than or equal to the maximum allowed.

```python
print(login_attempts <= max_logins)
```

**Output:**

```
True
```

---

## Task 9: Test a Failed Login Scenario

Reassign `login_attempts` to a value greater than the maximum allowed and observe the result.

```python
login_attempts = 4
print(login_attempts <= max_logins)
```

**Output:**

```
False
```

---

## Task 10: Assign a Boolean Login Status

Create a Boolean variable `login_status`, store its data type, and display it.

```python
login_status = False
login_status_type = type(login_status)
print(login_status_type)
```

**Output:**

```
<class 'bool'>
```

---

## Summary

In this lab, you practiced:

* Assigning variables
* Working with strings, lists, integers, and Booleans
* Using the `type()` function
* Comparing values using Boolean expressions

These skills are foundational for automating security-related tasks using Python.
