# Accordion Menu

## Example

<img width="990" alt="Screenshot 2024-06-28 at 5 38 57 PM" src="https://github.com/neriais/Instructional_Learning-Design/assets/57377953/0be5dc43-3b77-4bf3-af11-2ece75e0dcc8">


### Basic Code

```html
<details style="border: 1px solid #C3C3C3; margin: 0 0 10px 0; background-color: #ffffff;">
    <summary style="padding: 10px;">*Insert Title*</summary>
    <p style="margin-left: 10px; margin-right: 10px;">*Insert Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim
ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in
reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in
culpa qui officia deserunt mollit anim id est laborum.*</p>
</details>
<details style="border: 1px solid #C3C3C3; margin: 0 0 10px 0; background-color: #ffffff;">
    <summary style="padding: 10px;">*Insert Title*</summary>
    <p style="margin-left: 10px; margin-right: 10px;">*Insert Text Content*</p>
</details>
<details style="border: 1px solid #C3C3C3; margin: 0 0 10px 0; background-color: #ffffff;">
    <summary style="padding: 10px;">*Insert Title*</summary>
    <p style="margin-left: 10px; margin-right: 10px;">*Insert Text Content*</p>
</details>
```
## Instructions
Copy and paste the code above into the HTML editor of any section of your page where you would like to add an accordion menu. Replace the red, italicized Title with the title of your accordion menu. Replace the red, italicized Text Content portion with the content you would like to put inside the menu.

## Enhance with some CSS

### Example
<img width="701" alt="Screenshot 2024-06-28 at 6 50 51 PM" src="https://github.com/neriais/Instructional_Learning-Design/assets/57377953/d7d23493-e586-4e1c-9a26-a8a160f5191c">



```css
/* Style for the details element */
details {
    border: 1px solid #C3C3C3;
    border-radius: 5px;
    margin: 0 0 15px 0;
    background-color: #ffffff;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    transition: all 0.3s ease;
}

details:hover {
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
}

/* Style for the summary element */
summary {
    padding: 15px;
    cursor: pointer;
    font-weight: bold;
    list-style: none;
    background-color: #f0f0f0;
    border-bottom: 1px solid #C3C3C3;
    transition: background-color 0.3s ease;
}

summary::-webkit-details-marker {
    display: none;
}

summary::after {
    content: '+';
    float: right;
    font-size: 1.5em;
    line-height: 0.8;
    transition: transform 0.3s ease;
}

details[open] summary::after {
    content: '-';
}

summary:hover {
    background-color: #e0e0e0;
}

/* Style for the content inside details */
details p {
    margin: 15px;
    padding: 0;
    line-height: 1.6;
}

/* Animation for opening/closing */
details[open] summary {
    background-color: #e8e8e8;
}

details[open] summary ~ * {
    animation: sweep .5s ease-in-out;
}

@keyframes sweep {
    0%    {opacity: 0; transform: translateY(-10px)}
    100%  {opacity: 1; transform: translateY(0)}
}
```
