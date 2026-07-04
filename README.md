## 📘 README — Convert Decimal Number to Binary (Python)

## 📌 Description

This Python program converts a **decimal number** into its **binary format** using a built-in Python function.
In this example, the number **10** is converted into binary.

---

## ⚙️ Code

```python
num = 10
binary = bin(num)

print(binary)
```

---

## 🧠 Step-by-Step Explanation (Simple)

### 1️⃣ Store the number

```python
num = 10
```

Here we store the decimal number **10** in a variable.

---

### 2️⃣ Convert to binary

```python
binary = bin(num)
```

* `bin()` is a **built-in Python function**
* It converts a decimal number into **binary format**

---

### 3️⃣ Print result

```python
print(binary)
```

This displays the binary value.

---

## ▶️ Output

```
0b1010
```

---

## ❓ What does **0b** mean?

`0b` is just a **prefix** that tells Python:
👉 “This number is in binary format.”

So:

```
0b1010 = 1010 (binary)
```

---

## 💡 If you want ONLY binary digits (without 0b)

Use this:

```python
num = 10
binary = bin(num)[2:]

print(binary)
```

Output:

```
1010
```

---

## 🔑 Key Concepts Learned

* Decimal vs Binary numbers
* Python `bin()` function
* String slicing `[2:]`

---

## 🚀 Real-World Uses

Binary conversion is used in:

* Computer memory
* Digital electronics
* Networking
* Embedded systems

---

## ⭐ Easy Trick to Remember

👉 `bin()` = “Binary Convert Function”

---
<img width="506" height="746" alt="image" src="https://github.com/user-attachments/assets/e32fdb65-d5b2-4865-ba48-0aa3fa95cb54" />
