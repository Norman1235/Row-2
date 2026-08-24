# Row-2 Repository Guide

## 👥 Team Members

* **Norman Price**
* **Nathan McCommon**
* **Noah Hardy**

---

## 🛠️ Essential Install

Install the required build tools:

```bash
sudo apt install build-essential
```

---

## 📂 Repository Workflow

### 1. Clone the Repository

First, clone the repository to your computer.

### 2. Create the C++ File

After cloning the repository, create your `.cpp` file using `nano`:

```bash
nano "Name".cpp
```

### 3. Add the `.cpp` Files

Add the `.cpp` files to the repository.

### 4. Push to the Remote Repository

Push the changes to the remote repository.

### 5. Create a Pull Request

Create a pull request for the changes.

### 6. Merge `dev` into `main`

After the pull request is ready, merge the `dev` branch into the `main` branch.

---

## 💻 Compiling and Executing

### Compile / Prepare

Use `g++` to compile the C++ file:

```bash
g++ "Name of File" -o "NameIt"
```

### Execute

Run the compiled program:

```bash
./NameIt
```

---

## 🔄 Quick Workflow

```text
Clone Repository
       ↓
Create .cpp File
       ↓
Add .cpp Files
       ↓
Push to Remote Repository
       ↓
Create Pull Request
       ↓
Merge dev → main
       ↓
Compile with g++
       ↓
Execute with ./NameIt
```
