# Yet Another Calculator
## What is it
This is a test task I did for someone. It displays a text field you can enter a math expression, and it will show the result spotlight-style.

## How it works
JS searches for the elements with class ‘yas-component’ and adds to their content markup required for the calculator to function.

It takes text from the input, sanitizes, normalizes, and passes it to the `eval()`. Then it displays the result in the format acceptable to the user.

Preformatted numbers like 1,000.42, 1.000,42, or 1 000,42 will be parsed according to browser locale.

## What can be improved, but if I had more time
1. Deal with numbers that are too large.
2. Adapt the virtual keyboard for mobiles and use it instead of a native keyboard.
3. Use of a virtual keyboard does not move the cursor outside the text field.
4. Virtual keyboard enters symbols at the cursor and not just at the end.
5. 3. Keyboard Icon instead of text.
6. Move most css values to css variables and create some themes.



 
