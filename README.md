# Day 1: CSS Learning Journey 🌟  

## What I Learned Today  
On my first day of learning CSS, I explored the foundational concepts and properties that make styling web pages beautiful and interactive. Here's a summary of my progress:  

---

### 1. **Color Properties** 🎨  
- **Text Color**:  
  `color: red; /* Sets the text color to red */`
- **Background Color**:  
  `background-color: blue; /* Sets the background color to blue */`
- **CSS Color Systems**:  
  `/* Named colors */`
  `color: green;`
  `/* Hexadecimal */`
  `color: #ff5733;`
  `/* RGB */`
  `color: rgb(255, 87, 51);`
  `/* RGBA (with transparency) */`
  `color: rgba(255, 87, 51, 0.5);`
  `/* HSL */`
  `color: hsl(9, 100%, 60%);`
  `/* HSLA (with transparency) */`
  `color: hsla(9, 100%, 60%, 0.5);`

---

### 2. **Text Properties** ✍️  
- **Font Family**:  
  `font-family: Arial, sans-serif;`
- **Font Size**:  
  `font-size: 16px; /* Sets font size to 16px */`
- **Font Weight**:  
  `font-weight: bold; /* Options: normal, bold, bolder, lighter, 100-900 */`
- **Text Align**:  
  `text-align: center; /* Options: left, right, center, justify */`
- **Text Decoration**:  
  `text-decoration: underline; /* Options: none, underline, line-through */`
- **Text Transform**:  
  `text-transform: uppercase; /* Options: uppercase, lowercase, capitalize */`
- **Line Height**:  
  `line-height: 1.5; /* Adjusts the spacing between lines */`

---

This was my first step into the world of CSS. I'm excited to keep learning and applying these styles to real projects! 🚀

# CSS Basics - Day 2 ReadMe  

## **1. CSS Selectors**

### **Simple Selectors**
- `*` (Universal selector): Selects all elements.  
- `tagName` (Type selector): Targets elements by tag name (e.g., `p`, `div`).  
- `.className` (Class selector): Targets elements with a specific class.  
- `#idName` (ID selector): Targets elements with a specific ID.  

### **Combinator Selectors**
- **Descendant Selector** (`A B`): Selects all `B` inside `A`.  
- **Child Selector** (`A > B`): Selects `B` elements that are direct children of `A`.  
- **Adjacent Sibling Selector** (`A + B`): Selects `B` immediately after `A`.  
- **General Sibling Selector** (`A ~ B`): Selects all `B` that are siblings of `A`.  

### **Attribute Selectors**
- `[attr]`: Selects elements with the specified attribute.  
- `[attr="value"]`: Selects elements with an attribute equal to the value.  
- `[attr^="value"]`: Selects elements with an attribute starting with the value.  
- `[attr$="value"]`: Selects elements with an attribute ending with the value.  
- `[attr*="value"]`: Selects elements with an attribute containing the value.  

---

## **2. Pseudo-classes**
Pseudo-classes define the state of an element:  
- `:hover`: When the user hovers over an element.  
- `:focus`: When an element gains focus.  
- `:nth-child(n)`: Targets the nth child.  
- `:first-child`, `:last-child`: Target the first and last child elements.  
- `:not(selector)`: Selects everything except the specified selector.  

---

## **3. Pseudo-elements**
Pseudo-elements allow you to style specific parts of an element:  
- `::before`: Inserts content before the element’s content.  
- `::after`: Inserts content after the element’s content.  
- `::first-line`: Styles the first line of a block of text.  
- `::first-letter`: Styles the first letter of a block of text.  

---

## **4. Specificity**
Defines how CSS rules are applied:  
- Inline styles: **1000**  
- ID selectors: **100**  
- Class, attributes, and pseudo-classes: **10**  
- Type selectors and pseudo-elements: **1**  
Higher specificity overrides lower specificity.  

---

## **5. Cascading and Inheritance**
- **Cascading**: Determines which rule applies when multiple rules target the same element (based on specificity and rule order).  
- **Inheritance**: Certain properties (e.g., `color`, `font-family`) are inherited by child elements.  

---

## **6. Box Model**
Defines how elements are structured in CSS:  
- **Content**: The actual content of the box.  
- **Padding**: Space between content and border.  
- **Border**: The edge of the box.  
- **Margin**: Space outside the border.

---

## **7. Dimensions**
- `height` & `width`: Set the size of the element content box.  
- `padding`: Adds space between the content and border.  
- `margin`: Creates space outside the border.  
- `border`: Adds a border around the element.  
- `border-radius`: Creates rounded corners on elements.  

---

## **8. Display Property**
Defines how elements are displayed:  
- `block`: Element takes up the full width.  
- `inline`: Element takes up only as much width as its content.  
- `inline-block`: Behaves like an inline element but accepts `height` and `width`.  
- `none`: Hides the element.  

---

## **9. Positioning**
- `static` (default): Elements are positioned in the normal document flow.  
- `relative`: Positioned relative to its normal position.  
- `absolute`: Positioned relative to its nearest positioned ancestor.  
- `fixed`: Positioned relative to the viewport.  
- `sticky`: Toggles between `relative` and `fixed` depending on scroll.

---

## **10. Relative Units**
- `%`: Relative to the parent element.  
- `em`: Relative to the font size of the parent.  
- `rem`: Relative to the font size of the root element.  

---

## **Key Notes**
- CSS follows a cascading order (inline > internal > external).  
- Always consider specificity and inheritance for conflicts.  
- Mastering the box model is critical for layouts and spacing.  
- Practice positioning and relative units for responsive designs.

