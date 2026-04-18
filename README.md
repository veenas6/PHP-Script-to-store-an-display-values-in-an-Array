# 📄 PHP Array Traversal using foreach Loop

---

## 🌟 Project Overview

This project demonstrates how to create an **array in PHP** and display its elements using the **foreach loop**.

The program stores student names in an array and prints each name one by one.

The array contains:

* Veena
* Om
* Amey
* Niranjan

---

## 🎯 Objective

✔ Understand arrays in PHP
✔ Learn foreach loop concept
✔ Traverse array elements easily
✔ Display data dynamically using PHP

---

## 🛠️ Technologies Used

* 🐘 **PHP**
* 💻 **XAMPP / WAMP Server**
* 🌐 **Web Browser**
* 🧾 **Text Editor / VS Code**

---

## ⚙️ Working Principle

### 🔹 Step 1 — Create an Array

Student names are stored in an indexed array.

```php
$students = array("Veena", "Om", "Amey", "Niranjan");
```

---

### 🔹 Step 2 — Display Heading

The heading is printed using `echo`.

```php
echo "Student Names:<br>";
```

---

### 🔹 Step 3 — Traverse Array using foreach

The `foreach` loop accesses each element one by one.

```php
foreach($students as $name)
```

---

### 🔹 Step 4 — Print Each Name

Each student name is displayed on a new line.

```php
echo $name . "<br>";
```

---

## 💻 Program Code

```php
<?php
$students = array("Veena", "Om", "Amey", "Niranjan");

echo "Student Names:<br>";
foreach($students as $name) {
    echo $name . "<br>";
}
?>
```

---

## ▶️ How to Run the Program

1️⃣ Install **XAMPP/WAMP**
2️⃣ Save file as:

```text
students.php
```

3️⃣ Move file into **htdocs** folder
4️⃣ Start Apache server
5️⃣ Open browser:

```text
http://localhost/students.php
```

---

## 🖥️ Sample Output

```text
Student Names:
Veena
Om
Amey
Niranjan
```

---

## ✨ Features

✅ Simple and easy to understand
✅ Uses PHP array concept
✅ Demonstrates foreach loop
✅ Beginner-friendly example
✅ Dynamic data display

---

## 📚 Learning Outcomes

* Understanding indexed arrays
* Using foreach loop in PHP
* Traversing array elements
* Writing basic PHP programs

---

## 📌 Conclusion

This project successfully demonstrates how to store multiple values in an array and display them using the `foreach` loop in PHP. It is a useful beginner project for learning arrays and loops in PHP.
