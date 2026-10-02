# Reflection Answers

## 1. Why does the form need both HTML constraints and JavaScript?

HTML constraints provide built-in browser validation for rules such as required fields, email syntax, URL syntax and the allowed seat range. JavaScript is needed for custom behaviour such as comparing the two passwords and choosing the individual or group booking description.

## 2. How do the array and loop work together to create the dropdown?

The `workshops` array stores the workshop names. The `for...of` loop visits each name, creates a new `<option>` element, assigns the workshop as its value and visible text, and appends the option to the existing select element.

## 3. Why use valueAsNumber rather than value when comparing seats?

The `value` property returns the number input as a string, while `valueAsNumber` returns it as a JavaScript number. Using `valueAsNumber` makes numeric comparison with `1` correct and direct.

## 4. Why must a custom validity message be cleared after a correction?

A non-empty custom validity message makes the control invalid. After the user corrects the value, `setCustomValidity("")` clears the custom error so the form can pass validation.
