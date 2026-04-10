# 🌐 DOM (Document Object Model)

## 📌 What is DOM?

The **Document Object Model (DOM)** is a programming interface for web documents. It represents the structure of an HTML or XML document as a tree of objects.

With DOM, programming languages like JavaScript can:

* Access HTML elements
* Modify content
* Change styles
* Handle events dynamically

---

## 🧱 DOM Structure

The DOM represents a webpage as a **tree structure**:

* Document → Root node
* Element → HTML tags
* Attributes → Properties of elements
* Text → Content inside elements

Example:

```html
<html>
  <body>
    <h1>Hello World</h1>
  </body>
</html>
```

This is converted into a tree where:

* `<html>` is the root
* `<body>` is a child
* `<h1>` is a child of body

---

## ⚙️ DOM Manipulation using JavaScript

### 1. Selecting Elements

```javascript
document.getElementById("id");
document.querySelector(".class");
```

### 2. Changing Content

```javascript
element.innerHTML = "New Content";
```

### 3. Changing Styles

```javascript
element.style.color = "blue";
```

### 4. Adding Events

```javascript
element.addEventListener("click", function() {
  alert("Clicked!");
});
```

---

## 🚀 Why DOM is Important?

* Makes web pages interactive
* Allows dynamic updates without reloading
* Connects HTML, CSS, and JavaScript

---

## 📚 Conclusion

The DOM acts as a bridge between web pages and programming languages, enabling developers to build dynamic and responsive websites.
