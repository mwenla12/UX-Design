# Basic Tabbed Menu
## Example
<img width="980" alt="Screenshot 2024-06-28 at 5 28 19 PM" src="https://github.com/neriais/Instructional_Learning-Design/assets/57377953/c8e1374a-906d-4acf-b4fa-6646d72003d1">

## Basic Code

```html
<div class="enhanceable_content tabs">
    <ul>
        <li><a href="#tabs-1">Tab One</a></li>
        <li><a href="#tabs-2">Tab Two</a></li>
        <li><a href="#tabs-3">Tab Three</a></li>
        <li><a href="#tabs-4">Tab Four</a></li>
    </ul>
    <div id="tabs-1">Tab 1 content</div>
    <div id="tabs-2">Tab 2 content</div>
    <div id="tabs-3">Tab 3 content</div>
    <div id="tabs-4">Tab 4 content</div>
</div>
```
## Instructions
Copy and paste the code above into the HTML editor of any section of your page where you would like to add a tabbed menu. Replace the first four pieces of blue, italicized text with your tab titles. Replace the next four pieces of blue italicized text with the content contained in each tab.


### Here is an example of CSS to style the tabs in your tabbed menu:
```
.enhanceable_content.tabs ul {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
    border-bottom: 1px solid #ccc;
}

.enhanceable_content.tabs ul li {
    margin: 0;
}

.enhanceable_content.tabs ul li a {
    display: block;
    padding: 10px 20px;
    text-decoration: none;
    color: #333;
    border: 1px solid #ccc;
    border-bottom: none;
    background-color: #f9f9f9;
    margin-right: -1px;
}

.enhanceable_content.tabs ul li a:hover,
.enhanceable_content.tabs ul li a:focus {
    background-color: #e9e9e9;
}

.enhanceable_content.tabs ul li a.active {
    background-color: #fff;
    color: #000;
    border-bottom: 1px solid #fff;
}

.enhanceable_content.tabs div {
    padding: 20px;
    border: 1px solid #ccc;
    background-color: #fff;
    display: none;
}

.enhanceable_content.tabs div.active {
    display: block;
}
```
