# Github-pages


## ✅ **TASK 6: Host a Static Website with GitHub Pages**

### 🎯 **Objective:**  
Put a basic website online using just HTML (and optional CSS) for **free** using **GitHub Pages**.

---

### 🧰 **Tools Used:**

| Tool            | What it does                                          |
|------------------|--------------------------------------------------------|
| **GitHub**      | A website to store and share code online.              |
| **Git**         | A tool to save versions of your code. (Used in terminal)|
| **GitHub Pages**| A free service to host static websites from GitHub repos.|

---

## 🪜 **Mini Guide – Simple Steps**

### ✅ 1. **Create an `index.html` file**
----
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>My Static Site</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f0f4f8;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .container {
      text-align: center;
      background: white;
      padding: 40px;
      border-radius: 10px;
      box-shadow: 0 0 15px rgba(0,0,0,0.1);
    }

    h1 {
      color: #333;
    }

    p {
      color: #666;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Hello from GitHub Pages!</h1>
    <p>This is a static website with HTML and CSS in one file.</p>
  </div>
</body>
</html>



```

Save this as `index.html`.

---

### ✅ 2. **Push it to a new GitHub repository**

In terminal (Linux, AWS, or your computer):

```bash
git init
git add index.html
git commit -m "Add simple HTML page"
gh repo create my-static-site --public --source=. --remote=origin --push
```

> 📝 This creates a repo on GitHub and uploads your file.

---

### ✅ 3. **Enable GitHub Pages**

Go to your GitHub repo in your browser:

- Click on **Settings**
- Scroll down to **Pages**
- Under **Source**, choose:
  - **Branch**: `main`
  - **Folder**: `/ (root)`
- Click **Save**

---

### ✅ 4. **Get the live website link**

After enabling GitHub Pages, GitHub gives you a link like:

```
 https://shaikyounus155.github.io/Github-pages/
```

Click it to see  live website 🎉

---

## 🏁 **Deliverables**

- ✅ GitHub repo with `index.html`  
- ✅ Live website link from GitHub Pages

---
