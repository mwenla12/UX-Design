# Basic Forms

## Example

<img width="204" alt="Screenshot 2024-06-28 at 6 18 04 PM" src="https://github.com/neriais/Instructional_Learning-Design/assets/57377953/b51b0d14-3995-4e7e-a2e3-94e13b4fa7e9">


### Basic Code

```html
<form>
    <label for="name">Name:</label><br>
    <input type="text" id="name" name="name"><br>
    <label for="email">Email:</label><br>
    <input type="email" id="email" name="email"><br>
    <input type="submit" value="Submit">
</form>
```

## Styling the Form
### CSS Example

<img width="370" alt="Screenshot 2024-06-28 at 6 19 33 PM" src="https://github.com/neriais/Instructional_Learning-Design/assets/57377953/d7105e5e-70ee-42e5-9b18-a7f98c846cd5">


#### Below is an example of how you can style the form to make it visually appealing.

```css
form {
    display: flex;
    flex-direction: column;
    gap: 10px;
    width: 300px;
}

label {
    font-weight: bold;
}

input[type="text"], input[type="email"] {
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

input[type="submit"] {
    background-color: #007bff;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

input[type="submit"]:hover {
    opacity: 0.8;
}
```

## Instructions

Copy and paste the code above into the HTML editor of any section of your page where you would like to add a form. Replace the form fields and labels as needed and apply the CSS for styling.
