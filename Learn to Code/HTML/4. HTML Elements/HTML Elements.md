## 📘 HTML Elements

An **HTML element** is defined by:

- A **start tag**
    
- Some **content**
    
- An **end tag**
    

```html
<tagname>Content goes here...</tagname>
```

### 🧾 Examples of HTML Elements

| Start Tag | Element Content     | End Tag  |
| --------- | ------------------- | -------- |
| `<h1>`    | My First Heading    | `</h1>`  |
| `<p>`     | My first paragraph. | `</p>`   |
| `<br>`    | _(none)_            | _(none)_ |

> 💡 **Note:** Some HTML elements like `<br>` are **empty elements** — they have **no content** and **no closing tag**.

---

## 🔁 Nested HTML Elements

HTML elements can be **nested** (placed inside one another). All HTML documents are composed of nested elements.

Here’s a sample HTML with 4 elements:

```html
<!DOCTYPE html>
<html>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>
```

---

### 🧠 Example Explained

- `<html>`: Root element of the document
    
- `<body>`: Contains the page’s visible content
    
    - `<h1>`: A top-level heading
        
    - `<p>`: A paragraph of text
        

---

### 🔷 Mermaid Diagram – HTML Nesting

Paste that into Obsidian inside a code block to render a **nested tree diagram**.

---

## ❗ Never Skip the End Tag

HTML **sometimes works** without an end tag, but it's **bad practice**.

### 🚫 Incorrect Example:

```html
<p>This is a paragraph
<p>This is another paragraph
```

Browsers may still display it, but it can break formatting or lead to bugs.

✅ **Always use proper opening and closing tags.**

---

## 🕳️ Empty HTML Elements

Empty elements have no content and **do not require an end tag**.

### Example:

```html
<p>This is a <br> paragraph with a line break.</p>
```

---

## 🔡 HTML is Not Case Sensitive

HTML treats tags like `<P>` and `<p>` the same.  
However:

- ✅ **W3C recommends lowercase**
    
- ✅ **XHTML requires lowercase**
    

---

## 🏷️ Common HTML Tags Reference

|Tag|Description|
|---|---|
|`<html>`|Root of an HTML document|
|`<body>`|Document's visible content container|
|`<h1>`–`<h6>`|Headings, from most to least important|
|`<p>`|Paragraph|
|`<br>`|Line break (empty element)|

---
## 🏷️ Tags
#Programming_Languages #Learn_to_Code  #HTML_Elements #HTML 

[[HTML]]