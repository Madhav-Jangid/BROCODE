# BROCODE - A Fun Programming Language for Bros 🤙

BROCODE is a toy programming language designed to bring Hindi-style syntax to programming, making it more accessible and fun for Hindi-speaking developers! 🚀 Perfect for those who want to enjoy programming in a language they speak daily.
---



## 📝 **Table of Contents**

- [Introduction](#introduction)
- [Official Website](#official-website)
- [Installation](#installation)
- [Usage](#usage)
- [BROCODE Syntax](#brocode-syntax)
- [DOM Integration](#how-to-setup-dom-with-brocode)
- [Features](#features)
- [See BROCODE in Action](#see-what-brocode-can-do)
- [Contributing](#contributing)
- [License](#license)




## Documentation

For detailed documentation, check out the official **BROCODE** documentation:

[**BROCODE Documentation**](https://brocode-cli.vercel.app/docs/introduction-to-brocode)

---

## Official Website

Visit the official website for **BROCODE**:

[**BROCODE Official Website**](https://brocode-cli.vercel.app/)

---

## Installation

```bash
npm install -g brocode-cli@latest
```

---

## Usage

### 1. Create a file with a `.bc` extension:

```javascript
// hello.bc
// A basic program to find the factorial of a number

bro function FACTORIAL(n) {
    bro maanle fact hai 1;
    bro maanle i hai 1;

    bro jbb tk (i <= n) hai {
        bro maanle fact hai fact * i;
        i++;
    }

    bro dikha de("Factorial of " + n + " is: " + fact);
}

FACTORIAL(5);
```

### 2. Run your code:

```bash
brocode your-file.bc
```

**OR**

```bash
npx brocode your-file.bc
```

---

## Command Line Options

- **Basic usage:** `brocode filename.bc`
- **Debug mode:** `brocode filename.bc --debug`

---

## Features

- Hindi-style syntax for better understanding
- Clear error messages
- Debug mode for development
- Easy to use CLI interface

---

## **BROCODE** syntax

### 1. **Declaring a Variable:**

```javascript
// Declaring variable 'num' and assigning value 5
bro maanle num hai 5;
```

### 2. **Print something:**

```javascript
bro dikha de("Hello World!");
```

### 3. **Function Declaration:**

```javascript
bro function <functionName>(pram_a, param_b) {
    bro dikha de(pram_a + param_b);
}

<functionName>(5, 3);
```

### 4. **Conditional Statements:**

```javascript
//Declaring num with 2
bro maanle num hai 2;

// if statement
bro agar (num < 3){
    bro dikha de("Number is less than 3");
}
//else statement
bro leave it{
    bro dikha de("Number is greater than 3");
}
```

### 5. **While Loop:**

```javascript
// Declaring initial value from where loop starts
bro maanle num hai 2;

// defining while loop with condition num < 3
bro jbb tk (num < 3) hai {
    bro dikha de(num);

    // break statement
    bro nikal;

    // incrementing num
    num++;
}
```

---


## How to Setup DOM with **BROCODE**

To set up DOM functionality in your project, follow these steps:

1. **Add this in the `<head>` tag:**

```html
<script src="https://brocode-cli.vercel.app/api/ajj-kuch-tufani-krte-hai"></script>
```

2. **Create a `<bro-script>` tag at the end of your body tag:**

```html
<bro-script src="index.bc"></bro-script>
```

Make sure to provide the correct path to your `.bc` file.

That's it! You're good to go. 🎉



## **BROCODE** DOM Statements 

### **Select an element by its ID**  

```javascript
bro ye id ("<id>") wala lake <variable> me rakhde;
```

### **Select an element using a CSS selector**  
```javascript
bro isko ("<selector>") uthake <variable> me rakhde;
```

### **Select all elements matching a CSS selector**  
```javascript
bro iske ("<selector>") jese sab uthake <variable> me rakhde;
```

### **Change the inner HTML of an element**  
```javascript
bro <element> ka html bdl ke ("<new content>") krde;
```

### **Change the text content of an element**  
```javascript
bro <element> ka text bdl ke ("<new content>") krde;
```

### **Set an attribute value on an element**  
```javascript
bro <element> ka attribute ("<name>", "<value>") set krde;
```

### **Get an attribute value from an element**  
```javascript
bro <element> ka attribute ("<name>") le aa;
```

### **Remove an attribute from an element**  
```javascript
bro <element> ka attribute ("<name>") hta de;
```

### **Change the style property of an element**  
```javascript
bro <element> ka <property> "<value>" krde;
```

### **Add a class to an element**  
```javascript
bro <element> ki classes me "<className>" add krde;
```

### **Remove a class from an element**  
```javascript
bro <element> ki classes me "<className>" remove krde;
```

### **Toggle a class on an element**  
```javascript
bro <element> ki classes me "<className>" toggle krde;
```

### **Add an event listener to an element**  
```javascript
bro <element> pe sun ("<event>", <function()>);
```

### **Remove an event listener from an element**  
```javascript
bro <element> pe sunna bnd kr ("<event>", <function()>);
```

### **Create a new element**  
```javascript
bro document me "<tagName>" ka nya element <variable> me bna de;
```

### **Append a child element to a parent element**  
```javascript
bro <element> me <childElement> append krde;
```

### **Remove an element from the DOM**  
```javascript
bro <element> hta de;
```

### **Get the parent node of an element**  
```javascript
bro <element> ka parent <variable> me rakhde;
```

### **Get the child elements of an element**  
```javascript
bro <element> ka children <variable> me rakhde;
```

### **Get the value of a form input element**  
```javascript
bro <inputElement> ki value <variable> me rakhde;
```

### **Scroll an element into view**  
```javascript
bro <element> me scroll krde;
```

### **Scroll the window to a specific position**  
```javascript
bro window ko (x, y) tkk scroll krde;
```
---

 
## See what BROCODE can do: 

Yes now you can make basic web applications with BROCODE 💀

[**To-Do-list made with html,css and BROCODE**](https://madhav-jangid.github.io/To-Do-List-with-BROCODE/) 
