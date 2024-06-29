# Basic HTML Pills

## Example

<img width="246" alt="Screenshot 2024-06-28 at 5 56 27 PM" src="https://github.com/neriais/Instructional_Learning-Design/assets/57377953/5d6c9fb8-1c54-4fa9-890a-ab39e81c233e">


### Basic Code

```html
<ul class="pill">
    <li>30% of total</li>
    <li>2 Rules</li>
    <li>10pts</li>
</ul>
```
Instructions
Copy and paste the code above into the HTML editor of any section of your page where you would like to add pill-style information. Replace the text inside each `<li>` tag with your desired content. You can add or remove `<li>` elements as needed.

## Styling the Pills
### CSS Example

Below is an example of how you can style the pills to make them visually appealing.

```css
.pill {
    list-style-type: none;
    margin: 0;
    padding: 0;
    display: flex;
    gap: 10px;
}

.pill li {
    background-color: #e0e0e0;
    border-radius: 20px;
    padding: 10px 20px;
    display: inline-block;
    font-size: 14px;
}
```
