## 4.2 - Label tag, required attribute

### Part 1
1. Add the following attributes on the form tag: `action="#" method="POST"`
2. Add the text `required` at the end of the input tag that has `type="password"`.
3. Open your preview in a full screen.
4. Click the Submit button without entering any text in any of the form fields. What do you notice happens?

### Part 2
1. Inside your HTML, go to this input tag: `<input type="checkbox" name="isStudent"> Click here if a student at AoIT
.`
2. In the input tag, add an ID attribute.
3. Inside the id attribute, add the name "student". You should have the following: id="student".
4. Right next to your input, you will see some text that does not have HTML tags around it named "Click here if a student at AoIT".
5. Wrap the text with `<label> </label>` tags.
6. Inside your label tag, add the attribute 'for=" "'.
7. Inside the quotations of our new for attribute, add the value from the ID attribute of the input tag. For this line, it should be student. In the end, you should have: `<label for="student">` text here `</label>`

### Part 3
1. Click the TEXT of your new label tag. What do you notice happens? If you are successful, your checkbox should toggle without you actually clicking the box.
2. Repeat the steps for the next checkbox.

### Part 4
1. Add the attribute "disabled" (without quotation marks) to the first input tag, located on line 13.
2. Try to click or type information into the input box. What do you notice has now happened to our input box?
