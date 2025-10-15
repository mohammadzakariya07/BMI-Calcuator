# 🧮 Body Mass Index (BMI) Calculator

A simple and interactive **C program** that calculates the Body Mass Index (BMI) based on user input for weight and height in various units. It converts the inputs to standard units and displays the calculated BMI along with its category — *Underweight, Normal, Overweight,* or *Obese*.

---

## 🚀 Features
- Supports multiple weight units (kilogram, gram, pound)
- Supports multiple height units (meter, centimeter, feet, inches)
- Displays BMI value up to three decimal places
- Categorizes BMI according to WHO standards
- Simple menu-driven interface

---

## 🗂️ Project Structure
```

BMI-Calculator/
│
├── src/
│   ├── main.c
│   ├── bmi_functions.c
│   └── bmi_functions.h
│
├── bin/                     # Compiled output (optional)
├── docs/                    # Documentation
│   └── README.md
├── assets/                  # Screenshots or diagrams
│   └── demo.png
└── Makefile                 # Optional build automation

````

---

## 🧑‍💻 How to Compile and Run

### Using GCC
```bash
gcc src/main.c src/bmi_functions.c -o bin/bmi_calculator
./bin/bmi_calculator
````

### Or, if everything is in one file:

```bash
gcc main.c -o bmi_calculator
./bmi_calculator
```

---

## 🖥️ Example Output

```
-----WELCOME TO THE BODY MASS INDEX CALCULATOR-----
-- MOHAMMAD ZAKARIYA --
1. CHOOSE THE WEIGHT UNIT
2. CHOOSE THE HEIGHT UNIT
3. CALCULATE BMI
4. EXIT
choose an option : 3
your BMI is : 22.857
category : normal weight


## 👨‍💻 Author

**Mohammad Zakariya**
📧 mzakariya0007@gmail.com
🌐 https://www.linkedin.com/in/mohammad-zakariya-3a2748279/
⭐ If you like this project, consider giving it a star on GitHub!
