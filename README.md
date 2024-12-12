---

# Password Generator  

This is a simple web-based password generator that creates random alphanumeric passwords. It's built using HTML, JavaScript, and a bit of CSS for simplicity.  

---

## **How It Works**  
- The webpage displays a button labeled **"generate"**.  
- When you click the button, a JavaScript function generates a random password using the `Math.random()` and `toString(36)` methods.  
- The password is displayed on the page in real time under the heading **Password**.  

---

## **Usage**  
1. Clone the repository or download the HTML file.  
2. Open the file in any modern web browser (e.g., Chrome, Firefox, Edge).  
3. Click the **generate** button to create a new password.  

---

## **Code Explanation**  

### HTML  
- The HTML structure includes a header displaying the generated password and a button to trigger password generation.  

```html
<h1 id="pass">Password : </h1>
<button onclick="generate()">generate</button>
```

### JavaScript  
- The `generate()` function creates a random alphanumeric string using JavaScript and updates the text inside the header.  

```javascript
function generate() {
    const generate = Math.random()
        .toString(36).slice(2);
    document.getElementById("pass").innerHTML = "Password : " + generate;
}
```

---

## **Preview**  
Below is what the page looks like:  

1. Displays the **Password :** heading.
2. Includes a **generate** button.  
3. Updates the password dynamically on the page when the button is clicked.  

---

## **Future Enhancements**  
- Add options for customizable password length.  
- Include special characters for stronger passwords.  
- Improve the UI/UX with better styling.  

---

## **Contributing**  
Feel free to fork the repository, create an issue, or submit a pull request to contribute.  

---

## **Contact**  
Follow [Codes Buster](https://www.linkedin.com/in/codesbuster/) for more coding projects and tutorials.  

---
