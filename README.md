# 🔐 C++ Captcha Verification System

This is a simple C++ console application that generates a random alphanumeric captcha and prompts the user to enter it for verification. It checks if the entered captcha matches the generated one and gives appropriate feedback.

---

## 📌 Features

- Generates a random 9-character captcha
- Accepts user input for captcha verification
- Case-sensitive comparison
- Easy to understand and extend

---

## 💻 Technologies Used

- C++
- Standard Template Library (STL)
- `ctime` for random seeding
- `iostream` and `string` for input/output operations

---

## 🧠 How It Works

1. The program generates a captcha using a mix of:
   - Lowercase letters
   - Uppercase letters
   - Digits (0-9)
2. It displays the captcha to the user.
3. It prompts the user to enter the same captcha.
4. It then checks if the entered captcha matches the generated one.
5. Outputs "Captcha Matched" or "Captcha Not Matched" accordingly.

---

## 📂 Folder Structure

```
/CaptchaVerification
│
├── captcha_verification.cpp  # Main C++ source file
└── README.md                 # Project description
```

---
### Prerequisites

- A C++ compiler (e.g., g++, clang++)

---

## 📜 License

This project is open-source and available under the MIT License. You are free to use, modify, and distribute it.
