# 🚀 Sign In & Sign Up Form with Validation

This project is a **Sign In and Sign Up** form with **JavaScript validation** that ensures proper user input. The form includes error messages for incorrect entries, improving user experience.

## 📷 Screenshots
| Validation | Screenshot |
|------------|-----------|
| **Empty Username & Password (Sign In)** | ![signin-empty](screenshots/signin-empty.png) |
| **Invalid Password (Sign In)** | ![signin-invalid-password](screenshots/signin-invalid-password.png) |
| **Empty Fields (Sign Up)** | ![signup-empty](screenshots/signup-empty.png) |
| **Invalid Email (Sign Up)** | ![signup-invalid-email](screenshots/signup-invalid-email.png) |
| **Mismatched Passwords (Sign Up)** | ![signup-password-mismatch](screenshots/signup-password-mismatch.png) |

## ✨ Features
- ✅ **Sign In Form**
  - Checks if username and password are entered.
  - Validates password (must contain at least **6 characters, 1 number, and 1 special character**).
  - Displays error messages when incorrect input is provided.

- ✅ **Sign Up Form**
  - Checks if all fields are filled.
  - Validates:
    - **Full name** should not be empty.
    - **Username** should not be empty.
    - **Email** should be in proper format.
    - **Password** should contain at least **6 characters, 1 number, and 1 special character**.
    - **Confirm password** should match the password.
    - **Phone number** should be exactly **11 digits**.
    - **Age** should be greater than **0**.
    - **Gender** must be selected.

## 📌 Validation Logic (JavaScript)
### **Sign In Form**
- If the **username** is empty → Shows `"Username cannot be empty."`
- If the **password** is empty → Shows `"Password cannot be empty."`
- If the password doesn't meet the **strength criteria** → Shows `"Password must be at least 6 characters, contain one number, and one special character."`

### **Sign Up Form**
- **Full Name**: Cannot be empty.
- **Username**: Cannot be empty.
- **Email**: Must match format (`example@example.com`).
- **Password**: Must be at least **6 characters long**, contain **1 number and 1 special character**.
- **Confirm Password**: Must match the password.
- **Phone Number**: Must be exactly **11 digits**.
- **Age**: Must be greater than **0**.
- **Gender**: Cannot be left empty.

## 📂 How to Upload Screenshots on GitHub
1. Create a **screenshots** folder inside your GitHub repository.
2. Upload the images using GitHub's **"Upload files"** option.
3. Ensure the filenames match the ones listed above:
   - `signin-empty.png`
   - `signin-invalid-password.png`
   - `signup-empty.png`
   - `signup-invalid-email.png`
   - `signup-password-mismatch.png`
4. Once uploaded, they will be displayed in the README file.

## 🚀 How to Update Your GitHub Repository (If It Already Exists)
### **Using Git Bash / Terminal**
```sh
git add README.md
git add screenshots/
git commit -m "Added README and validation screenshots"
git push origin main
