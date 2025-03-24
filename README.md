# ProX Programming Language  

**ProX** is a high-level, Python-like programming language designed for modern development. It features simplicity, power, and flexibility, making it ideal for both beginners and professionals.  

---

## 🌟 Features  

✅ **Python-like Syntax** – Easy to read and write.  
✅ **32 Keywords** – Designed for efficiency.  
✅ **50 Built-in Functions** – Predefined functions for various operations.  
✅ **12 Data Types** – Strong and dynamic typing support.  
✅ **32 Operators** – Powerful mathematical and logical operations.  
✅ **5 Special Constants** – Unique constants for enhanced functionality.  
✅ **PRM (ProX Repository Manager)** – Manage ProX packages efficiently.  
✅ **Cross-Platform** – Works on Windows, macOS, and Linux.  
✅ **Custom Standard Library** – Extensive modules for development.  
✅ **Fast Execution** – Optimized for performance.  
✅ **Open Source** – Community-driven and actively developed.  

---

## 📥 Installation  

### Using PRM (ProX Repository Manager)  
Install ProX with a single command:  
```sh
prm install prox
```

### Manual Installation  
Clone the repository and install manually:  
```sh
git clone https://github.com/yourusername/prox.git
cd prox
python setup.py install
```

### Running ProX  
Verify installation by running:  
```sh
prox --version
```

---

## 🚀 Getting Started  

### Writing Your First ProX Script  
Create a file named `hello.prox`:  
```python
print("Hello, ProX!")
```
Run the script:  
```sh
prox hello.prox
```

### Variables & Data Types  
```python
name = "ProX"
age = 15
price = 49.99
is_active = True
items = ["apple", "banana", "cherry"]
```

### Conditional Statements  
```python
if age > 18:
    print("Adult")
else:
    print("Minor")
```

### Loops  
```python
for i in range(5):
    print(i)

while age < 18:
    age += 1
```

### Functions  
```python
def greet(name):
    return "Hello, " + name

print(greet("ProX"))
```

### Classes & Objects  
```python
class Person:
    def __init__(self, name, age):
        self.name = name
        self.age = age

    def info(self):
        return f"{self.name} is {self.age} years old."

p = Person("Alice", 20)
print(p.info())
```

---

## 📚 Standard Library  

### Math Module  
```python
import math

print(math.sqrt(16))  # 4.0
print(math.pow(2, 3))  # 8.0
```

### File Handling  
```python
with open("file.txt", "w") as file:
    file.write("Hello, ProX!")
```

### Working with JSON  
```python
import json

data = {"name": "ProX", "version": 1.0}
json_str = json.dumps(data)
print(json_str)
```

---

## 🔌 ProX Package Manager (PRM)  

PRM allows you to install and manage packages easily.  

### Installing a Package  
```sh
prm install package_name
```

### Listing Installed Packages  
```sh
prm list
```

### Removing a Package  
```sh
prm remove package_name
```

---

## 🛠 Advanced Features  

### Lambda Functions  
```python
square = lambda x: x * x
print(square(5))  # 25
```

### List Comprehension  
```python
numbers = [x for x in range(10) if x % 2 == 0]
print(numbers)  # [0, 2, 4, 6, 8]
```

### Exception Handling  
```python
try:
    x = 10 / 0
except ZeroDivisionError:
    print("Cannot divide by zero!")
```

---

## 🖥️ Running ProX Scripts  

### Running a File  
```sh
prox myscript.prox
```

### Running in Interactive Mode  
```sh
prox
>>> print("Hello, ProX!")
```

---

## 🏗️ Contributing  

We welcome contributions from the community!  

### How to Contribute  
1. **Fork the repository**  
2. **Create a new branch** (`feature-name`)  
3. **Make your changes**  
4. **Commit and push**  
5. **Open a pull request**  

### Reporting Issues  
If you find a bug, please open an issue on GitHub.  

---

## 📜 License  

This project is licensed under the **MIT License**.  

---

## 📬 Contact  

For any questions, reach out at:  
📧 Email: [programmerkr.123@gmail.com](mailto:programmerkr.123@gmail.com)  
🌐 Website: [prox.com](https://prox.com)  
📌 GitHub: [github.com/ProgrammerKR](https://github.com/ProgrammerKR)  

---

**Happy Coding with ProX! 🎉**
